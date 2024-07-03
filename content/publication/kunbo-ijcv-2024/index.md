---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Open-Vocabulary Text-Driven Human Image Generation"
authors: ["Kaiduo Zhang", "Muyi Sun", "Jianxin Sun", "Kunbo Zhang", "Zhenan Sun", "Tieniu Tan"]
date: 2024-05-15T16:12:05+08:00
doi: "10.1007/s11263-024-02079-7"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-05-15T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*2024 International Journal of Computer Vision (IJCV)*"

abstract: "Generating human images from open-vocabulary text descriptions is an exciting but challenging task. Previous methods (i.e., Text2Human) face two challenging problems: (1) they cannot well handle the open-vocabulary setting by arbitrary text inputs (i.e., unseen clothing appearances) and heavily rely on limited preset words (i.e., pattern styles of clothing appearances); (2) the generated human image is inaccuracy in open-vocabulary settings. To alleviate these drawbacks, we propose a flexible diffusion-based framework, namely HumanDiffusion, for open-vocabulary text-driven human image generation (HIG). The proposed framework mainly consists of two novel modules: the Stylized Memory Retrieval (SMR) module and the Multi-scale Feature Mapping (MFM) module. Encoded by the vision-language pretrained CLIP model, we obtain coarse features of the local human appearance. Then, the SMR module utilizes an external database that contains clothing texture details to refine the initial coarse features. Through SMR refreshing, we can achieve the HIG task with arbitrary text inputs, and the range of expression styles is greatly expanded. Later, the MFM module embedding in the diffusion backbone can learn fine-grained appearance features, which effectively achieves precise semantic-coherence alignment of different body parts with appearance features and realizes the accurate expression of desired human appearance. The seamless combination of the proposed novel modules in HumanDiffusion realizes the freestyle and high accuracy of text-guided HIG and editing tasks. Extensive experiments demonstrate that the proposed method can achieve state-of-the-art (SOTA) performance, especially in the open-vocabulary setting."

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

url_pdf: "https://link.springer.com/article/10.1007/s11263-024-02079-7"
# url_code:
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
  caption: "Overview of the HumanDiffusion framework"
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
