---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "AIF-LFNet: All-in-Focus Light Field Super-Resolution Method Considering the Depth-Varying Defocus"
authors: ["Shubo Zhou", "Liang Hu", "Yunlong Wang", "Zhenan Sun", "Kunbo Zhang", "Xue-qin Jiang"]
date: 2023-01-16T16:12:05+08:00
doi: "10.1109/TCSVT.2023.3237593"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-01-16T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Circuits and Systems for Video Technology ( Early Access )*"

abstract: "As an aperture-divided computational imaging system, microlens array (MLA) -based light field (LF) imaging is playing an increasingly important role in computer vision. As the trade-off between the spatial and angular resolutions, deep learning (DL) -based image super-resolution (SR) methods have been applied to enhance the spatial resolution. However, in existing DL-based methods, the depth-varying defocus is not considered both in dataset development and algorithm design, which restricts many applications such as depth estimation and object recognition. To overcome this shortcoming, a super-resolution task that reconstructs all-in-focus high-resolution (HR) LF images from low-resolution (LR) LF images is proposed by designing a large dataset and proposing a convolutional neural network (CNN) -based SR method. The dataset is constructed by using Blender software, consisting of 150 light field images used as training data, and 15 light field images used as validation and testing data. The proposed network is designed by proposing the dilated deformable convolutional network (DCN) -based feature extraction block and the LF subaperture image (SAI) Deblur-SR block. The experimental results demonstrate that the proposed method achieves more appealing results both quantitatively and qualitatively."



# Summary. An optional shortened abstract.
summary: ""

tags: ["Light Field Super-Resolution"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10018388"
url_code: "https://github.com/qingpu1988/AllfocusNet"
url_dataset: "https://github.com/qingpu1988/AllfocusNet"
# url_poster:
# url_project:
# url_slides:
# url_source:
# url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Dataset Samples"
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
  ![Figure 1](1.png " The framework of AIF-LFNet")