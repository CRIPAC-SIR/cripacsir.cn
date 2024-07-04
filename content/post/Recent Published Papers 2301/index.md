---
title: One paper was accepted to International Joint Conference on Biometrics (IJCB 2023)
summary: "Sclera-TransFuse: Fusing Swin Transformer and CNN for Accurate Sclera Segmentation"
tags: ["smart iris recognition"]
date: "2023-09-28T00:00:00Z"

# Optional external URL for project (replaces project detail page)

external_link: ""

---

## 1. Sclera-TransFuse: Fusing Swin Transformer and CNN for Accurate Sclera Segmentation

> Li Haiqing, Wang Caiyong, Zhao Guangzhe, He Zhaofeng, Wang Yunlong,Zhenan Sun. Sclera-TransFuse: Fusing Swin Transformer and CNN for Accurate Sclera Segmentation. seventh International Joint Conference on Biometrics (IJCB), 2023. <https://ijcb2023.ieee-biometrics.org/>

![IJCB 2023](IJCB2023-pic1.png)

Sclera segmentation is a crucial step in sclera recognition, which has been greatly advanced by Convolutional Neural Networks (CNNs). However, when dealing with non-ideal eye images, many existing CNN-based approaches are still prone to failure. One major reason is that due to the limited range of receptive fields, CNNs are difficult to effectively model global semantic relevance and thus robustly resist noise interference. To solve this problem, this paper proposes a novel two-stream hybrid model, named Sclera-TransFuse, to integrate classical ResNet-34 and recently emerging Swin Transformer encoders. Specially, the self-attentive Swin Transformer has shown a strong ability in capturing long-range spatial dependencies and has a hierarchical structure similar to CNNs. The dual encoders firstly extract coarse- and fine-grained feature representations at hierarchical stages, separately. Then a novel Cross-Domain Fusion (CDF) module based on information interaction and self-attention mechanism is introduced to efficiently fuse the multi-scale features extracted from dual encoders. Finally, the fused features are progressively upsampled and aggregated to predict the sclera masks in the decoder meanwhile deep supervision strategies are employed to learn intermediate feature representations better and faster. Experimental results show that Sclera-TransFuse achieves state-of-the-art performance on various sclera segmentation benchmarks. Additionally, a UBIRIS.v2 subset of 683 eye images with manually labeled sclera masks, and our codes are publicly available to the community through https://github.com/Ihqqq/Sclera-TransFuse.

