---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "PDVN: A Patch-based Dual-view Network for Face Liveness Detection using Light Field Focal Stack"
authors: ["Yunlong Wang", "Mupei Li", "Zhengquan Luo", "Zhenan Sun"]
date: 2022-10-13T16:12:05+08:00
doi: "10.1109/IJCB54206.2022.10007998"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-10-13T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*2022 IEEE International Joint Conference on Biometrics (IJCB)*"

abstract: "Light Field Focal Stack (LFFS) can be efficiently rendered from a light field (LF) image captured by plenoptic cameras. Differences in the 3D surface and texture of biometric samples are internally reflected in the defocus blur and local patterns between the rendered slices of LFFS. This unique property makes LFFS quite appropriate to differentiate presentation attack instruments (PAIs) from bona fide samples. A patch-based dual-view network (PDVN) is proposed in this paper to leverage the merits of LFFS for face presentation attack detection (PAD). First, original LFFS data are divided into various local patches along spatial dimensions, which distracts the model from learning the useless facial semantics and greatly relieve the problem of insufficient samples. The strategy of dual-view branches is innovatively proposed, wherein the original view and microscopic view can simultaneously contribute to liveness detection. Separable 3D convolution on the focal dimension is verified to be more effective than vanilla 3D convolution for extracting discriminative features from LFFS data. The voting mechanism on predictions of patch LFFS samples further strengthens the robustness of the proposed framework. PDVN is compared with other face PAD methods on IST LLFFSD dataset and achieves perfect performance, i.e., ACER drops to 0."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Liveness Detection", "Light Field Imaging"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://ieeexplore.ieee.org/abstract/document/10007998"
url_code: "https://github.com/lmp1265/PDVN-project-for-light-field-liveness-detection.git"
#url_dataset: 
url_poster: https://wylcasia.github.io/papers/IJCB2022-2-poster.pdf
# url_project:
# url_slides:
# url_source:
# url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: " Overview of PDVN"
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["Light Field Photography"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
