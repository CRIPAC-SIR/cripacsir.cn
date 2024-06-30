---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multitask deep active contour-based iris segmentation for off-angle iris images"
authors: ["Tianhao Lu", "Caiyong Wang", "Yunlong Wang", "Zhenan Sun"]
date: 2022-02-17T16:12:05+08:00
doi: "10.1117/1.JEI.31.4.041211"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-02-17T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Electronic Imaging (February 2022).*"

abstract: "
Iris recognition has been considered as a secure and reliable biometric technology. However, iris images are prone to off-angle or are partially occluded when captured with fewer user cooperations. As a consequence, iris recognition especially iris segmentation suffers a serious performance drop. To solve this problem, we propose a multitask deep active contour model for off-angle iris image segmentation. Specifically, the proposed approach combines the coarse and fine localization results. The coarse localization detects the approximate position of the iris area and further initializes the iris contours through a series of robust preprocessing operations. Then, iris contours are represented by 40 ordered isometric sampling polar points and thus their corresponding offset vectors are regressed via a convolutional neural network for multiple times to obtain the precise inner and outer boundaries of the iris. Next, the predicted iris boundary results are regarded as a constraint to limit the segmentation range of noise-free iris mask. Besides, an efficient channel attention module is introduced in the mask prediction to make the network focus on the valid iris region. A differentiable, fast, and efficient SoftPool operation is also used in place of traditional pooling to keep more details for more accurate pixel classification. Finally, the proposed iris segmentation approach is combined with off-the-shelf iris feature extraction models including traditional OM and deep learning-based FeatNet for iris recognition. The experimental results on two NIR datasets CASIA-Iris-off-angle, CASIA-Iris-Africa, and a VIS dataset SBVPI show that the proposed approach achieves a significant performance improvement in the segmentation and recognition for both regular and off-angle iris images."

# Summary. An optional shortened abstract.
summary: ""

tags: ["iris segmentation", "smart iris recognition"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://www.spiedigitallibrary.org/journals/journal-of-electronic-imaging/volume-31/issue-4/041211/Multitask-deep-active-contour-based-iris-segmentation-for-off-angle/10.1117/1.JEI.31.4.041211.short?SSO=1&tab=ArticleLink"
url_code: "https://github.com/lutianhao/IrisGazeSeg"
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
  caption: " The architecture of IrisGazeSeg"
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
