---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Iris-GuideNet: Guided Localisation and Segmentation Network for Unconstrained Iris Biometrics"
authors: ["Jawad Muhammad", "Caiyong Wang", "Yunlong Wang", "Kunbo Zhang", "Zhenan Sun"]
date: 2023-04-19T08:12:05+08:00
doi: "10.1109/TIFS.2023.3268504"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-04-19T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Information Forensics and Security(Volume:18)*"

abstract: "In recent years, unconstrained iris biometrics has become more prevalent due to its wide range of user applications. However, it also presents numerous challenges to the Iris pre-processing task of Localization and Segmentation (ILS). Many ILS techniques have been proposed to address these challenges, among which the most effective is the CNN-based methods. Training the CNN is data-intensive, and most of the existing CNN-based ILS approaches do not incorporate iris-specific features that can reduce their data dependence, despite the limited labelled iris data in the available databases. These trained CNN models built upon these databases can be sub-optimal. Hence, this paper proposes a guided CNN-based ILS approach IrisGuideNet. IrisGuideNet involves incorporating novel iris-specific heuristics named Iris Regularization Term (IRT), deep supervision technique, and hybrid loss functions in the training pipeline, which guides the network and reduces the model data dependence. A novel Iris Infusion Module (IIM) that utilizes the geometrical relationships between the ILS outputs to refine the predicted outputs is introduced at network inference. The proposed model is trained and evaluated with various datasets. Experimental results show that IrisGuideNet has outperformed most models across all the database categories. The codes implementation of the proposed IrisGuideNet will be available at: https://github.com/mohdjawadi/IrisGuidenet."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://ieeexplore.ieee.org/document/10105641"
url_code: https://github.com/mohdjawadi/IrisGuidenet
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
  caption: "Schematic diagram of the proposed IrisGuideNet including (1) proposed network architecture; (2) deep supervision; (3) novel Iris Regularization
Term (IRT); (4) hybrid losses; and (5) novel Iris Infusion Module (IIM)"
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
