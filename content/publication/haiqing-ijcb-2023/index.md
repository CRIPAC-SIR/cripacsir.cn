---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Sclera-TransFuse: Fusing Swin Transformer and CNN for Accurate Sclera Segmentation"
authors: ["Li Haiqing", "Wang Caiyong", "Zhao Guangzhe", "He Zhaofeng", "Wang Yunlong","Zhenan Sun"]
date: 2023-09-28T16:12:05+08:00
doi: "10.1109/IJCB57857.2023.10448814"

# Schedule page publish date (NOT publication's date).
publishDate: 2024-03-01T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*2023 IEEE International Joint Conference on Biometrics (IJCB)*"

abstract: "Sclera segmentation is a crucial step in sclera recognition, which has been greatly advanced by Convolutional Neural Networks (CNNs). However, when dealing with non-ideal eye images, many existing CNN-based approaches are still prone to failure. One major reason is that due to the limited range of receptive fields, CNNs are difficult to effectively model global semantic relevance and thus robustly resist noise interference. To solve this problem, this paper proposes a novel two-stream hybrid model, named Sclera-TransFuse, to integrate classical ResNet-34 and recently emerging Swin Transformer encoders. Specially, the self-attentive Swin Transformer has shown a strong ability in capturing long-range spatial dependencies and has a hierarchical structure similar to CNNs. The dual encoders firstly extract coarse- and fine-grained feature representations at hierarchical stages, separately. Then a novel Cross-Domain Fusion (CDF) module based on information interaction and self-attention mechanism is introduced to efficiently fuse the multi-scale features extracted from dual encoders. Finally, the fused features are progressively upsampled and aggregated to predict the sclera masks in the decoder meanwhile deep supervision strategies are employed to learn intermediate feature representations better and faster. Experimental results show that Sclera-TransFuse achieves state-of-the-art performance on various sclera segmentation benchmarks. Additionally, a UBIRIS.v2 subset of 683 eye images with manually labeled sclera masks, and our codes are publicly available to the community through https://github.com/Ihqqq/Sclera-TransFuse."

# Summary. An optional shortened abstract.
summary: ""

# tags: ["iris super-resolution", "smart iris recognition"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://ieeexplore.ieee.org/document/10448814"
url_awards: "https://ijcb2023.ieee-biometrics.org/award-winners/"
# url_dataset:  "http://www.idealtest.org/dbDetailForUser.do?id=4#/"
url_poster: IJCB2023-2-poster.pdf
# url_project:
# url_slides:
# url_source:
# url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: " The overall architecture of Sclera-TransFuse model"
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["Sclera Recognition"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
