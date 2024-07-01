---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Flexible Iris Matching Based on Spatial Feature Reconstruction"
authors: ["Zihui Yan", "Lingxiao He", "Yunlong Wang", "Zhenan Sun", "Tieniu Tan"]
date: 2021-08-30T16:12:05+08:00
doi: "10.1109/TBIOM.2021.3108559"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-08-30T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Biometrics, Behavior, and Identity Science(TBIOM)*"

abstract: "In an iris recognition-at-a-distance (IAAD) system used in surveillance scenarios, the camera usually captures a large number of low-quality images. These images exhibit partial occlusions due to eyelids and eyelashes, specular reflections, and severe deformations caused by pupil dilations and contractions. Recognizing these low-quality images is a challenging yet dominant problem in IAAD. To mitigate this issue, current iris recognition systems mostly filter out low-quality images by using strict criteria based on image quality evaluation. This strategy, however, wastes device capabilities and produces low throughput of subjects. Other systems require highly cooperative users. In this work, we propose a novel occlusion-robust, deformation-robust, and alignment-free framework for low-quality iris matching, which integrates the merits of deep features and sparse representation in an end-to-end learning process known as iris spatial feature reconstruction (ISFR). Here each probe image can be sparsely reconstructed on the basis of appropriate feature maps from gallery high-quality images. ISFR uses the error from robust reconstruction over spatial pyramid features to measure similarities between two iris images, which naturally avoids the time-consuming alignment step. In summary, the distinctiveness of deep features, the robustness of sparse reconstruction, and the flexibility of multiscale matching strategy are unified in a general framework to attain more accurate and reasonable iris matching. Extensive experimental results on four public iris image databases demonstrate that the proposed method significantly outperforms both traditional and deep learning-based iris recognition methods."

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

url_pdf: "https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9524810"
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
  caption: "Flexible Iris Matching Based on Spatial Feature Reconstruction"
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
