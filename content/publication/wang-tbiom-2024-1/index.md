---
title: "Sclera-TransFuse: Fusing Vision Transformer and CNN for Accurate Sclera Segmentation and Recognition"
date: 2024-06-17
publishDate: 2024-06-17T11:44:49.293511Z
authors: ["Caiyong Wang", "Haiqing Li", "Yixin Zhang", "Guangzhe Zhao", "Yunlong Wang", "Zhenan Sun"]
publication_types: ["2"]
abstract: "This paper investigates a deep learning based unified framework for accurate sclera segmentation and recognition, named Sclera-TransFuse. Unlike previous CNN-based methods, our framework incorporates Vision Transformer and CNN to extract complementary feature representations, which are beneficial to both subtasks. Specifically, for sclera segmentation, a novel two-stream hybrid model, referred to as Sclera-TransFuse-Seg, is developed to integrate classical ResNet-34 and recently emerging Swin Transformer encoders in parallel. The dual-encoders firstly extract coarse-and fine-grained feature representations at hierarchical stages, separately. Then a Cross-Domain Fusion (CDF) module based on information interaction and self-attention mechanism is introduced to efficiently fuse the multi-scale features extracted from dual-encoders. Finally, the fused features are progressively upsampled and aggregated to predict the sclera masks in the decoder meanwhile deep supervision strategies are employed to learn intermediate feature representations better and faster. With the results of sclera segmentation, the sclera ROI image is generated for sclera feature extraction. Additionally, a new sclera recognition model, termed as Sclera-TransFuse-Rec, is proposed by combining lightweight EfficientNet B0 and multi-scale Vision Transformer in sequential to encode local and global sclera vasculature feature representations. Extensive experiments on several publicly available databases suggest that our framework consistently achieves state-of-the-art performance on various sclera segmentation and recognition benchmarks, including the 8th Sclera Segmentation and Recognition Benchmarking Competition (SSRBC 2023). A UBIRIS.v2 subset of 683 eye images with manually labeled sclera masks, and our codes are publicly available to the community through https://github.com/lhqqq/Sclera-TransFuse."
featured: true
publication: "*IEEE Transactions on Biometrics, Behavior, and Identity Science (TBIOM)*"
tags: ["Smart Iris Recognition", "Sclera segmentation", "sclera recognition"]
doi: "10.1109/TBIOM.2024.3415484"
url_pdf: https://ieeexplore.ieee.org/document/10559402
projects: ["Sclera Recognition"]
image:
  caption: "Overall framework of the proposed Sclera-TransFuse"
  focal_point: "Smart"
  preview_only: false
---

