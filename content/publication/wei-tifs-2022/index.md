---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Contextual Measures for Iris Recognition"
authors: ["Jianze Wei", "Yunlong Wang", "Huaibo Huang", "Ran He", "Zhenan Sun", "Xingyu Gao"]
date: 2022-11-14T08:12:05+08:00
doi: "10.1109/TIFS.2022.3221897"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-11-14T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Information Forensics and Security ( Volume: 18)*"

abstract: "The iris patterns of the human contain a large amount of randomly distributed and irregularly shaped microstructures. These microstructures make the human iris informative biometric traits. To learn identity representation from them, this paper regards each iris region as a potential microstructure and proposes contextual measures (CM) to model the correlations between them. CM adopts two parallel branches to learn global and local contexts in iris image. The first one is the globally contextual measure branch. It measures the global context involving the relationships between all regions for feature aggregation and is robust to local occlusions. Besides, we improve its spatial perception considering the positional randomness of the microstructures. The other one is the locally contextual measure branch. This branch considers the role of local details in the phenotypic distinctiveness of iris patterns and learns a series of relationship atoms to capture contextual information from a local perspective. In addition, we develop the perturbation bottleneck to make sure that the two branches learn divergent contexts. It introduces perturbation to limit the information flow from input images to identity features, forcing CM to learn discriminative contextual information for iris recognition. Experimental results suggest that global and local contexts are two different clues critical for accurate iris recognition. The superior performance on four benchmark iris datasets demonstrates the effectiveness of the proposed approach in within-database and cross-database scenarios."

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

url_pdf: "https://ieeexplore.ieee.org/abstract/document/9947055"
url_code: "https://github.com/reborn20200813/Contextual-Measures"
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
