---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Personalized Graph Generation for Monocular 3D Human Pose and Shape Estimation"
authors: ["Junxing Hu", "Hongwen Zhang", "Yunlong Wang", "Min Ren", "Zhenan Sun"]
date: 2023-08-31T16:12:05+08:00
doi: "10.1109/IJCB52358.2021.9484357"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-08-31T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Circuits and Systems for Video Technology ( Volume: 34)*"

abstract: "3D human pose and shape estimation from a single RGB image is an appealing yet challenging task. Due to the graph-like nature of human parametric models, a growing number of graph neural network-based approaches have been proposed and achieved promising results. However, existing methods build graphs for different instances based on the same template SMPL mesh, neglecting the geometric perception of individual properties. In this work, we propose an end-to-end method named Personalized Graph Generation (PGG) to construct the geometry-aware graph from an intermediate predicted human mesh. Specifically, a convolutional module initially regresses a coarse SMPL mesh tailored for each sample. Guided by the 3D structure of this personalized mesh, PGG extracts the local features from the 2D feature map. Then, these geometry-aware features are integrated with the specific coarse SMPL parameters as vertex features. Furthermore, a body-oriented adjacency matrix is adaptively generated according to the coarse mesh. It considers individual full-body relations between vertices, enhancing the perception of body geometry. Finally, a graph attentional module is utilized to predict the residuals to get the final results. Quantitative experiments across four benchmarks and qualitative comparisons on more datasets show that the proposed method outperforms state-of-the-art approaches for 3D human pose and shape estimation."

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

url_pdf: "https://ieeexplore.ieee.org/document/10236465"
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
  caption: "Overview of the proposed Personalized Graph Generation (PGG)"
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
