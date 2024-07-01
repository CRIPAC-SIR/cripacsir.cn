---
title: "Boosting multi-modal ocular recognition via spatial feature reconstruction and unsupervised image quality estimation"
date: 2024-01-15           
publishDate: 2024-01-15
authors: ["Zihui Yan", "Lingxiao He", "Yunlong Wang", "Kunbo Zhang", "Zhenan Sun", "Tieniu Tan"]
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]   

# Publication name and optional abbreviated publication name.
publication: "*Machine Intelligence Research(Volume: 21)*"

abstract: "In the daily application of an iris-recognition-at-a-distance (IAAD) system, many ocular images of low quality are acquired. As the iris part of these images is often not qualified for the recognition requirements, the more accessible periocular regions are a good complement for recognition. To further boost the performance of IAAD systems, a novel end-to-end framework for multi-modal ocular recognition is proposed. The proposed framework mainly consists of iris/periocular feature extraction and matching, unsupervised iris quality assessment, and a score-level adaptive weighted fusion strategy. First, ocular feature reconstruction (OFR) is proposed to sparsely reconstruct each probe image by high-quality gallery images based on proper feature maps. Next, a brand new unsupervised iris quality assessment method based on random multiscale embedding robustness is proposed. Different from the existing iris quality assessment methods, the quality of an iris image is measured by its robustness in the embedding space. At last, the fusion strategy exploits the iris quality score as the fusion weight to coalesce the complementary information from the iris and periocular regions. Extensive experimental results on ocular datasets prove that the proposed method is obviously better than unimodal biometrics, and the fusion strategy can significantly improve the recognition performance."
# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: (https://link.springer.com/article/10.1007/s11633-023-1415-y)
url_code: 
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Illustration of the whole framework"
  focal_point: 
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