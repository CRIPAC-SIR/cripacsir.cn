---
title: MediaPipe Iris
summary: Real time iris tracking and depth estimation
tags:
- Iris Recognition
date: "2020-08-08T00:00:00Z"

---
<!--<div align='center'><font size='10'>MediaPipe Iris 实时虹膜跟踪和深度估计</font></div>    
<div style='display:none'>
标题居中
</div>-->
 <font size='5'>
 &emsp;&emsp;包括计算摄影（例如，人像模式和闪光反射）和增强现实效果（例如，虚拟化身）在内的大量实际应用程序都依赖于通过跟踪虹膜来估计眼睛位置。一旦获得了准确的虹膜跟踪，我们就可以确定从相机到用户的距离，而无需使用专用的深度传感器。反过来，这可以改善各种用例，从计算摄影到适当大小的眼镜和帽子的虚拟试戴，到根据视听者的距离采用字体大小的可用性增强。
 由于有限的计算资源，可变的光照条件和遮挡物（例如头发或人斜视）的存在，虹膜跟踪是在移动设备上解决的一项艰巨任务。通常，会使用复杂的专用硬件，从而限制了可在其中应用该解决方案的设备范围。
 </font>
 
<div align=center>
<img src="https://pic1.zhimg.com/v2-abc83ffe57801610f81c22845ec1a937_b.gif" alt="show" width="650" height="230" />
</div>
<div align='center'>由MediaPipe Iris实现的眼睛重新着色示例</div> 
</div>
 <font size='5'>
&emsp;&emsp;谷歌日前发布了用于精确虹膜估计的全新机器学习模型：MediaPipe Iris。所述模型以MediaPipe Face Mesh的研究作为基础，而它无需专用硬件就能够通过单个RGB摄像头实时追踪涉及虹膜，瞳孔和眼睛轮廓的界标。利用虹膜界标，模型同时能够在不使用深度传感器的情况下以相对误差小于10％的精度确定对象和摄像头之间的度量距离。请注意，虹膜追踪不会推断人们正在注视的位置，同时不能提供任何形式的身份识别。MediaPipe是一个旨在帮助研究人员和开发者构建世界级机器学习解决方案与应用程序的开源跨平台框架，所以在MediaPipe中实现的这一系统能够支持大多数现代智能手机，PC，笔记本电脑，甚至是Web。
<div>

<div align=center>
<img src="http://p3.itc.cn/q_70/images03/20200808/b4ad6d1e27c5402c9f6752ce39d9a24a.gif" alt="show" width="240" height="270">
</div>
<div align='center'><font size='3'>用于远视用户的可用性原型：无论距离如何、字体大小能够保持恒定</div> 
<!-- 用于远视用户的可用性原型：无论距离如何、字体大小能够保持恒定--> 

**<font color=#000000 size=5 face="黑体">1. 用于虹膜追踪的机器学习管道</font>** 
 
<font size='5'>&emsp;&emsp;谷歌介绍道，开发系统的第一步利用了之前针对3D Face Meshes的研究，亦即通过高保真面部界标来生成近似面部几何形状的网格。根据所述网格，研究人员分离出原始图像中的眼睛区域以用于虹膜追踪模型。然后，谷歌将问题分为两个部分：眼睛轮廓估计和虹膜位置。他们设计了一个由一元化编码器组成的多任务模型，每个组件对应一个任务，这样就能够使用特定于任务的训练数据。
<div align=center>
<img src="http://p3.itc.cn/q_70/images03/20200808/462869a0c5844bc28f5c89f65479dd02.gif" alt="show" width="300" height="300"，>
<div align='center'><font size='3'>用于远视用户的可用性原型：无论距离如何、字体大小能够保持恒定</div> 

</div> 
<font size='5'>&emsp;&emsp;为了将裁剪后的眼睛区域用于模型训练，团队手动注释了大约50万张图像。其中，图像涵盖了不同地理位置的各种照明条件和头部姿势，如下所示

<div align=center>
<img src="d07b74a8b05a4721b72eb12c1a81f383.png" alt="show" width="700" height="200"，>
<div align='center'><font size='3'>用于远视用户的可用性原型：无论距离如何、字体大小能够保持恒定</div> 
<div align=center>
<img src="d9331ef1d8864e79a8288a210f869815.png" alt="show" width="700" height="260"，>
<div align='center'><font size='3'>裁剪的眼睛区域形成模型的输入，而它将通过单独的组件预测界标</div> 

**<div align=left><font color=#000000 size=5 face="黑体">2. 虹膜深度：用单个图像进行深度估计</font>** 
<font size='5'>&emsp;&emsp;无需任何专门的硬件，这个虹膜追踪模型能够以不到10％的误差确定对象到摄像头的度量距离。相关的原理事实是，人眼的水平直径虹膜基本恒定为11.7±0.5毫米。作为说明，请想象将针孔摄像头模型投影到正方形像素的传感器。你可以使用摄像头的焦距估计从面部界标到对象的距离，而这可以通过Camera Capture API或直接从捕获图像的EXIF元数据，以及其他摄像头固有参数进行获取。给定焦距，对象到摄像头的距离与对象眼睛的物理尺寸成正比，如下图所示
<div align=center>
<img src="366c2353e9654a7998c87ac32c491daf.png" alt="show" width="700" height="500"，>
<div align='center'><font size='3'>利用类似的三角形，我们可以根据焦距（f）和虹膜大小来计算对象的距离（d）</div> 
<div align=center>
<img src="http://p7.itc.cn/q_70/images03/20200808/0ba5001e03ca4c42a17036b97ed0326b.gif" alt="show" width="300" height="260"，>
<div align='center'><font size='3'>左边：在Pixel 2运行的MediaPipe Iris正在以cm为单位估计度量距离，没有采用任何深度摄像头；右边：groud-truth深度</div> 
<div align='left'><font size='5'>&emsp;&emsp;为了量化所述方法的精确性，研究人员收集了200多位被试的正向同步视频和深度图像，并将其与iPhone 11的深度传感器进行比较。团队使用激光测距设备，通过实验确定iPhone 11的深度传感器在2米以内的误差小于2％。对于使用虹膜大小进行深度估算的方法，平均相对误差为4.3％，标准偏差是2.4％。谷歌对有眼镜被试和正常视力被试（不计入隐形眼镜情况）测试了所述方法，并发现眼镜会将平均相对误差略微提高到4.8％（标准偏差是3.1％）。另外，实验没有测试存在任何眼睛疾病的被试。考虑到MediaPipe Iris不需要专门的硬件，所述结果表明系统能够支持一系列成本范围的设备根据单张图像获取度量深度
<div align=center>
<img src="f49af869c2c34877a244ab791ee17b27.png" alt="show" width="500" height="420"，>
<div align='center'><font size='3'>估计误差的直方图（左边），以及实际和估计距离的比较（右边）</div> 

**<div align=left><font color=#000000 size=5 face="黑体">3. 发布MediaPipe Iris</font>** 
<div align='left'><font size='5'>&emsp;&emsp;这个虹膜和深度估计模型将作为支持PC，移动设备和Web的跨平台MediaPipe管道发布。正如谷歌在最近一篇关于MediaPipe的博文所述，团队利用WebAssembly和XNNPACK在浏览器中本地运行Iris ML管道，无需将任何数据发送到云端。

<div align=center>
<img src="http://p7.itc.cn/q_70/images03/20200808/6974ce3508e94a1c87418733ba3a3928.gif" alt="show" width="300" height="420"，>
<div align='center'><font size='3'>使用MediaPipe的WASM堆栈。你可以在浏览器种运行模型</div> 
<div align=center>
<img src="http://p6.itc.cn/q_70/images03/20200808/ede608441d4141629bf58a576ed495ba.gif" alt="show" width="300" height="420"，>
<div align='center'><font size='3'>仅使用包含EXIF数据的单张图片计算虹膜深度</div> 

**<div align=left><font color=#000000 size=5 face="黑体">4. 未来方向</font>** 
<div align='left'><font size='5'>&emsp;&emsp;谷歌计划进一步扩展MediaPipe Iris模型，实现更稳定的追踪性能以降低误差，并将其部署用于无障碍用例。谷歌在相关文档和随附的Model Card中详细说明了预期的用途，限制和模型的公平性，从而确保模型的使用符合谷歌的AI原则。请注意，任何形式的监视监控都明显超出应用范围，故不予支持。团队表示：“我们希望的是，通过向广泛的研究与开发社区提供这种虹膜感知功能，从而促使创造性用例的出现，激发负责任的新应用和新研究途径。”