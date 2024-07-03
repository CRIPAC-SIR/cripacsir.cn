---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multiscale Dynamic Graph Representation for Biometric Recognition with Occlusions"
authors: ["Min Ren", "Yunlong Wang", "Yuhao Zhu", "Kunbo Zhang", "Zhenan Sun"]
date: 2023-07-20T16:12:05+08:00 
doi: "10.1109/TPAMI.2023.3298836"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-07-20T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Pattern Analysis and Machine Intelligence (T-PAMI)*"

abstract: "Occlusion is a common problem with biometric recognition in the wild. The generalization ability of CNNs greatly decreases due to the adverse effects of various occlusions. To this end, we propose a novel unified framework integrating the merits of both CNNs and graph models to overcome occlusion problems in biometric recognition, called multiscale dynamic graph representation (MS-DGR). More specifically, a group of deep features reflected on certain subregions is recrafted into a feature graph (FG). Each node inside the FG is deemed to characterize a specific local region of the input sample, and the edges imply the co-occurrence of non-occluded regions. By analyzing the similarities of the node representations and measuring the topological structures stored in the adjacent matrix, the proposed framework leverages dynamic graph matching to judiciously discard the nodes corresponding to the occluded parts. The multiscale strategy is further incorporated to attain more diverse nodes representing regions of various sizes. Furthermore, the proposed framework exhibits a more illustrative and reasonable inference by showing the paired nodes. Extensive experiments demonstrate the superiority of the proposed framework, which boosts the accuracy in both natural and occlusion-simulated cases by a large margin compared with that of baseline methods."

# Summary. An optional shortened abstract.
summary: ""

tags: ["biometrics", "deep learning", "face recognition", "graph neural networks", "iris recognition"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://ieeexplore.ieee.org/abstract/document/10193782"
url_code: https://github.com/RenMin1991/Dyamic-Graph-Representation
# url_dataset:  "http://www.cripacsir.cn/dataset/"
# url_poster:
# url_project:
# url_slides:
# url_source:
# url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Framework of the proposed MS-DGR"
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
