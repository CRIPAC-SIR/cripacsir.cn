---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multi-Faceted Knowledge-Driven Graph Neural Network for Iris Segmentation"
authors: ["Jianze Wei", "Yunlong Wang", "Xingyu Gao", "Ran He", "Zhenan Sun"]
date: 2024-06-14T08:12:05+08:00
doi: "10.1109/TIFS.2024.3407508"

# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-14T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Information Forensics and Security ( Volume: 19)*"

abstract: "Accurate iris segmentation, especially around the iris inner and outer boundaries, is still a formidable challenge. Pixels within these areas are difficult to semantically distinguish since they have similar visual characteristics and close spatial positions. To tackle this problem, the paper proposes an iris segmentation graph neural network (ISeGraph) for accurate segmentation. ISeGraph regards individual pixels as nodes within the graph and constructs self-adaptive edges according to multi-faceted knowledge, including visual similarity, positional correlation, and semantic consistency for feature aggregation. Specifically, visual similarity strengthens the connections between nodes sharing similar visual characteristics, while positional correlation assigns weights according to the spatial distance between nodes. In contrast to the above knowledge, semantic consistency maps nodes into a semantic space and learns pseudo-labels to define relationships based on label consistency. ISeGraph leverages multi-faceted knowledge to generate self-adaptive relationships for accurate iris segmentation. Furthermore, a pixel-wise adaptive normalization module is developed to increase the feature discriminability. It takes informative features in the shallow layer as a reference to improve the segmentation features from a statistical perspective. Experimental results on three iris datasets illustrate that the proposed method achieves superior performance in iris segmentation, increasing the segmentation accuracy in areas near the iris boundaries."

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

url_pdf: "https://ieeexplore.ieee.org/document/10555436"
# url_code: "https://github.com/reborn20200813/uncertainty"
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
  caption: "An illustration of the proposed method"
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
