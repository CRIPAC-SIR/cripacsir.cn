---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Lightweight Multi-Label Segmentation Network for Mobile Iris Biometrics"
authors: ["Caiyong Wang", "Yunlong Wang", " Boqiang Xu", "Yong He", " Zhiwei Dong", "Zhenan Sun"]
date: 2020-04-09T16:12:05+08:00
doi: "10.1109/ICASSP40776.2020.9054353"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-04-09T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)*"

abstract: "This paper proposes a novel, lightweight deep convolutional neural network specifically designed for iris segmentation of noisy images acquired by mobile devices. Unlike previous studies, which only focused on improving the accuracy of segmentation mask using the popular CNN technology, our method is a complete end-to-end iris segmentation solution, i.e., segmentation mask and parameterized pupillary and limbic boundaries of the iris are obtained simultaneously, which further enables CNN-based iris segmentation to be applied in any regular iris recognition systems. By introducing an intermediate pictorial boundary representation, predictions of iris boundaries and segmentation mask have collectively formed a multi-label semantic segmentation problem, which could be well solved by a carefully adapted stacked hourglass network. Experimental results show that our method achieves competitive or state-of-the-art performance in both iris segmentation and localization on two challenging mobile iris databases."

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

url_pdf: "https://ieeexplore.ieee.org/abstract/document/9054353"
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
  caption: "The proposed unified iris segmentation and localization framework"
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
