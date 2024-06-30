---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Towards Complete and Accurate Iris Segmentation Using Deep Multi-Task Attention Network for Non-Cooperative Iris Recognition"
authors: ["Caiyong Wang", "Jawad Muhammad", "Yunlong Wang", "Zhaofeng He", "Zhenan Sun"]
date: 2020-03-16T16:12:05+08:00
doi: "10.1109/TIFS.2020.2980791"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-16T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Information Forensics and Security ( Volume: 15)*"

abstract: "Iris images captured in non-cooperative environments often suffer from adverse noise, which challenges many existing iris segmentation methods. To address this problem, this paper proposes a high-efficiency deep learning based iris segmentation approach, named IrisParseNet. Different from many previous CNN-based iris segmentation methods, which only focus on predicting accurate iris masks by following popular semantic segmentation frameworks, the proposed approach is a complete iris segmentation solution, i.e., iris mask and parameterized inner and outer iris boundaries are jointly achieved by actively modeling them into a unified multi-task network. Moreover, an elaborately designed attention module is incorporated into it to improve the segmentation performance. To train and evaluate the proposed approach, we manually label three representative and challenging iris databases, i.e., CASIA.v4-distance, UBIRIS.v2, and MICHE-I, which involve multiple illumination (NIR, VIS) and imaging sensors (long-range and mobile iris cameras), along with various types of noises. Additionally, several unified evaluation protocols are built for fair comparisons. Extensive experiments are conducted on these newly annotated databases, and results show that the proposed approach achieves state-of-the-art performance on various benchmarks. Further, as a general drop-in replacement, the proposed iris segmentation method can be used for any iris recognition methodology, and would significantly improve the performance of non-cooperative iris recognition."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Iris Segmentation"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://ieeexplore.ieee.org/abstract/document/9036930"
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
  caption: "Pipeline of a iris recognition system"
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
