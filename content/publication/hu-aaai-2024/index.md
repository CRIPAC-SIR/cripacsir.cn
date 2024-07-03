---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Learning Explicit Contact for Implicit Reconstruction of Hand-held Objects from Monocular Images"
authors: ["Junxing Hu","Hongwen Zhang","Zerui Chen","Mengcheng Li","Yunlong Wang","Yebin Liu","Zhenan Sun"]
date: 2023-12-13T16:12:05+08:00
doi: "10.1609/aaai.v38i3.27995"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-13T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*AAAI 2024*"

abstract: "Reconstructing hand-held objects from monocular RGB images is an appealing yet challenging task. In this task, contacts between hands and objects provide important cues for recovering the 3D geometry of the hand-held objects. Though recent works have employed implicit functions to achieve impressive progress, they ignore formulating contacts in their frameworks, which results in producing less realistic object meshes. In this work, we explore how to model contacts in an explicit way to benefit the implicit reconstruction of hand-held objects. Our method consists of two components: explicit contact prediction and implicit shape reconstruction. In the first part, we propose a new subtask of directly estimating 3D hand-object contacts from a single image. The part-level and vertex-level graph-based transformers are cascaded and jointly learned in a coarse-to-fine manner for more accurate contact probabilities. In the second part, we introduce a novel method to diffuse estimated contact states from the hand mesh surface to nearby 3D space and leverage diffused contact probabilities to construct the implicit neural representation for the manipulated object. Benefiting from estimating the interaction patterns between the hand and the object, our method can reconstruct more realistic object meshes, especially for object parts that are in contact with hands. Extensive experiments on challenging benchmarks show that the proposed method outperforms the current state of the arts by a great margin. Our code is publicly available at https://junxinghu.github.io/projects/hoi.html."

# Summary. An optional shortened abstract.
summary: ""

# tags: ["iris super-resolution", "smart iris recognition"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://ojs.aaai.org/index.php/AAAI/article/view/27995"
url_code: "https://github.com/JunxingHu/CHOI"
# url_dataset:  "http://www.idealtest.org/dbDetailForUser.do?id=4#/"
# url_poster:
url_project: "https://junxinghu.github.io/projects/hoi.html"
# url_slides:
# url_source:
url_video: "https://underline.io/lecture/93986-learning-explicit-contact-for-implicit-reconstruction-of-hand-held-objects-from-monocular-images"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: " The overview of learning explicit contact"
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
