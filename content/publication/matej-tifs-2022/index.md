---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Exploring Bias in Sclera Segmentation Models: A Group Evaluation Approach"
authors: ["Matej Vitek", "Abhijit Das", "Diego Rafael Lucio", "et.al"]
date: 2022-10-21T08:12:05+08:00
doi: "10.1109/TIFS.2022.3216468"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-10-21T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Information Forensics and Security ( Volume: 18)*"

abstract: "Bias and fairness of biometric algorithms have been key topics of research in recent years, mainly due to the societal, legal and ethical implications of potentially unfair decisions made by automated decision-making models. A considerable amount of work has been done on this topic across different biometric modalities, aiming at better understanding the main sources of algorithmic bias or devising mitigation measures. In this work, we contribute to these efforts and present the first study investigating bias and fairness of sclera segmentation models. Although sclera segmentation techniques represent a key component of sclera-based biometric systems with a considerable impact on the overall recognition performance, the presence of different types of biases in sclera segmentation methods is still underexplored. To address this limitation, we describe the results of a group evaluation effort (involving seven research groups), organized to explore the performance of recent sclera segmentation models within a common experimental framework and study performance differences (and bias), originating from various demographic as well as environmental factors. Using five diverse datasets, we analyze seven independently developed sclera segmentation models in different experimental configurations. The results of our experiments suggest that there are significant differences in the overall segmentation performance across the seven models and that among the considered factors, ethnicity appears to be the biggest cause of bias. Additionally, we observe that training with representative and balanced data does not necessarily lead to less biased results. Finally, we find that in general there appears to be a negative correlation between the amount of bias observed (due to eye color, ethnicity and acquisition device) and the overall segmentation performance, suggesting that advances in the field of semantic segmentation may also help with mitigating bias."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Sclera Segmentation"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://ieeexplore.ieee.org/abstract/document/9926136"
# url_code:
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
projects: ["Sclera Recognition"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
