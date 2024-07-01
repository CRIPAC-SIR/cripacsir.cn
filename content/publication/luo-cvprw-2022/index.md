---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "FedIris: Towards More Accurate and Privacy-Preserving Iris Recognition via Federated Template Communication"
authors: ["Zhengquan Luo", "Yunlong Wang", "Zilei Wang", "Zhenan Sun", "Tieniu Tan"]
date: 2022-06-20T16:12:05+08:00
# doi: "10.1007/978-3-031-20233-9_14"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-06-20T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops, 2022*"

abstract: "As biometric data undergo rapidly growing privacy concerns, building large-scale datasets has become more difficult. Unfortunately, current iris databases are mostly in small scale, e.g., thousands of iris images from hundreds of identities. What's worse, the heterogeneity among decentralized iris datasets hinders the current deep learning (DL) frameworks from obtaining recognition performance with robust generalization. It motivates us to leverage the merits of federated learning (FL) to solve these problems. However, traditional FL algorithms often employ model sharing for knowledge transfer, wherein the simple averaging aggregation lacks interpretability, and divergent optimization directions of clients lead to performance degradation. To overcome this interference, we propose FedIris with solid theoretical foundations, which attempts to employ the iris template as the communication carrier and formulate federated triplet (Fed-Triplet) for knowledge transfer. Furthermore, the massive heterogeneity among iris datasets may induce negative transfer and unstable optimization. The modified Wasserstein distance is embedded into the FedTriplet loss to reweight global aggregation, which drives the clients with similar data distributions to contribute more mutually. Extensive experimental results demonstrate that the proposed FedIris outperforms SOLO training, model-sharing-based FL training, and even centralized training."

# Summary. An optional shortened abstract.
summary: ""

tags: ["smart iris recognition", "federated learning"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://openaccess.thecvf.com/content/CVPR2022W/FedVision/papers/Luo_FedIris_Towards_More_Accurate_and_Privacy-Preserving_Iris_Recognition_via_Federated_CVPRW_2022_paper.pdf"
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
