---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Towards More Discriminative and Robust Iris Recognition by Learning Uncertain Factors"
authors: ["Jianze Wei", "Huaibo Huang", "Yunlong Wang", "Ran He", "Zhenan Sun"]
date: 2022-02-28T08:12:05+08:00
doi: "10.1109/TIFS.2022.3154240"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-02-28T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Information Forensics and Security ( Volume: 17)*"

abstract: "The uncontrollable acquisition process limits the performance of iris recognition. In the acquisition process, various inevitable factors, including eyes, devices, and environment, hinder the iris recognition system from learning a discriminative identity representation. This leads to severe performance degradation. In this paper, we explore uncertain acquisition factors and propose uncertainty embedding (UE) and uncertainty-guided curriculum learning (UGCL) to mitigate the influence of acquisition factors. UE represents an iris image using a probabilistic distribution rather than a deterministic point (binary template or feature vector) that is widely adopted in iris recognition methods. Specifically, UE learns identity and uncertainty features from the input image, and encodes them as two independent components of the distribution, mean and variance. Based on this representation, an input image can be regarded as an instantiated feature sampled from the UE, and we can also generate various virtual features through sampling. UGCL is constructed by imitating the progressive learning process of newborns. Particularly, it selects virtual features to train the model in an easy-to-hard order at different training stages according to their uncertainty. In addition, an instance-level enhancement method is developed by utilizing local and global statistics to mitigate the data uncertainty from image noise and acquisition conditions in the pixel-level space. The experimental results on six benchmark iris datasets verify the effectiveness and generalization ability of the proposed method on same-sensor and cross-sensor recognition."

# Summary. An optional shortened abstract.
summary: ""

tags: ["smart iris recognition"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://ieeexplore.ieee.org/abstract/document/9722888"
url_code: "https://github.com/reborn20200813/uncertainty"
# url_dataset:
# url_poster:
# url_project:
# url_slides: 
# url_source:
# url_video: "Supplementary.zip"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
