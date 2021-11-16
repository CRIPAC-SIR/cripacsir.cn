---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Contrastive Uncertainty Learning for Iris Recognition with Insufficient Labeled Samples"
authors: ["Jianze Wei", "Ran He", "Zhenan Sun"]
date: 2021-04-07T16:12:05+08:00
doi: "10.1109/IJCB52358.2021.9484388"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-04-07T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*International Joint Conference on Biometrics 2021 (IJCB2021)*"

abstract: "Cross-database recognition is still an unavoidable challenge when deploying an iris recognition system to a new environment. In the paper, we present a compromise problem that resembles the real-world scenario, named iris recognition with insufficient labeled samples. This new problem aims to improve the recognition performance by utilizing partially-or un-labeled data. To address the problem, we propose Contrastive Uncertainty Learning (CUL) by integrating the merits of uncertainty learning and contrastive self-supervised learning. CUL makes two efforts to learn a discriminative and robust feature representation. On the one hand, CUL explores the uncertain acquisition factors and adopts a probabilistic embedding to represent the iris image. In the probabilistic representation, the identity information and acquisition factors are disentangled into the mean and variance, avoiding the impact of uncertain acquisition factors on the identity information. On the other hand, CUL utilizes probabilistic embeddings to generate virtual positive and negative pairs. Then CUL builds its contrastive loss to group the similar samples closely and push the dissimilar samples apart. The experimental results demonstrate the effectiveness of the proposed CUL for iris recognition with insufficient labeled samples."

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

url_pdf: "https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9484388"
# url_code:
# url_dataset:
# url_poster:
# url_project:
# url_slides:
# url_source:
# url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Contrastive Uncertainty Learning for Iris Recognition with Insufficient Labeled Samples"
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
