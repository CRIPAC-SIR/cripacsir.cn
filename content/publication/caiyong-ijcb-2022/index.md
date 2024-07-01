---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "D-ESRGAN: A Dual-Encoder GAN with Residual CNN and Vision Transformer for Iris Image Super-Resolution"
authors: ["Caiyong Wang", "Tianhao Lu", "Gaosheng Wu", "Yunlong Wang", "Zhenan Sun"]
date: 2023-01-17T16:12:05+08:00
doi: "10.1109/IJCB54206.2022.10007938"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-01-17T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*2022 IEEE International Joint Conference on Biometrics (IJCB)*"

abstract: "Iris images captured in less-constrained environments, especially at long distances often suffer from the interference of low resolution, resulting in the loss of much valid iris texture information for iris recognition. In this paper, we propose a dual-encoder super-resolution generative adversarial network (D-ESRGAN) for compensating texture lost of the raw image meanwhile maintaining the newly generated textures more natural. Specifically, the proposed D-ESRGAN not only integrates the residual CNN encoder to extract local features, but also employs an emerging vision transformer encoder to capture global associative information. The local and global features from two encoders are further fused for the subsequent reconstruction of high-resolution features. During the training, we develop a three-stage strategy to alleviate the problem that generative adversarial networks are prone to collapse. Moreover, to boost the iris recognition performance, we introduce a triplet loss to push away the distance of super-resolved iris images with different IDs, and pull the distance of super-resolved iris images with the same ID much closer. Experimental results on the public CASIA-Iris-distance and CASIA-Iris-M1 datasets show that D-ESRGAN archives better performance than state-of-the-art baselines in terms of both super-resolution image quality metrics and iris recognition metric."

# Summary. An optional shortened abstract.
summary: ""

tags: ["iris super-resolution", "smart iris recognition"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://ieeexplore.ieee.org/abstract/document/10007938"
# url_code:
url_dataset:  "http://www.idealtest.org/dbDetailForUser.do?id=4#/"
# url_poster:
# url_project:
# url_slides:
# url_source:
# url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: " The structure diagram of D-ESRGAN"
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["Iris Recognition"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
