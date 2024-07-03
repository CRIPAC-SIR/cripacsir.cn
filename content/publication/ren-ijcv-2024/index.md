---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Artificial Immune System of Secure Face Recognition Against Adversarial Attacks"
authors: ["Min Ren", "Yunlong Wang", "Yuhao Zhu", "Yongzhen Huang", "Zhenan Sun", "Qi Li", "Tieniu Tan"]
date: 2024-06-26T16:12:05+08:00
doi: "10.1007/s11263-024-02153-0"

# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-26T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*International Journal of Computer Vision*"

abstract: "Deep learning-based face recognition models are vulnerable to adversarial attacks.In contrast to general noises, the presence of imperceptible adversarial noises can lead to catastrophic errors in deep face recognition models. The primary difference between adversarial noise and general noise lies in its specificity. Adversarial attack methods give rise to noises tailored to the characteristics of the individual image and recognition model at hand. Diverse samples and recognition models can engender specific adversarial noise patterns, which pose significant challenges for adversarial defense. Addressing this challenge in the realm of face recognition presents a more formidable endeavor due to the inherent nature of face recognition as an open set task. In order to tackle this challenge, it is imperative to employ customized processing for each individual input sample. Drawing inspiration from the biological immune system, which can identify and respond to various threats, this paper aims to create an artificial immune system (AIS) to provide adversarial defense for face recognition. The proposed defense model incorporates the principles of antibody cloning, mutation, selection, and memory mechanisms to generate a distinct “antibody” for each input sample, where in the term “antibody” refers to a specialized noise removal manner. Furthermore,we introduce a self-supervised adversarial training mechanism that serves as a simulated rehearsal of immune system invasions. Extensive experimental results demonstrate the efficacy of the proposed method, surpassing state-of-the-art adversarial defense methods. The source code is available here, or you can visit this website: https://github.com/RenMin1991/SIDE."

# Summary. An optional shortened abstract.
summary: ""

# tags: ["iris segmentation", "iris localization"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://link.springer.com/article/10.1007/s11263-024-02153-0"
url_code: "https://github.com/RenMin1991/SIDE"
url_dataset:  "https://paperswithcode.com/dataset/megaface"
url_arxiv: https://arxiv.org/abs/2406.18144
# url_poster:
# url_project:
# url_slides:
# url_source:
# url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "The architecture of the proposed adversarial defense method."
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: ["Iris Recognition"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
