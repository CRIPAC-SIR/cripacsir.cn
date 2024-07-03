---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Pose-Appearance Relational Modeling for Video Action Recognition"
authors: ["Mengmeng Cui","Wei Wang","Kunbo Zhang","Zhenan Sun","Liang Wang"]
date: 2022-12-14T16:12:05+08:00
doi: "10.1109/TIP.2022.3228156"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-12-14T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*2022 IEEE Transactions on Image Processing (TIP)*"

abstract: "Recent studies of video action recognition can be classified into two categories: the appearance-based methods and the pose-based methods. The appearance-based methods generally cannot model temporal dynamics of large motion well by virtue of optical flow estimation, while the pose-based methods ignore the visual context information such as typical scenes and objects, which are also important cues for action understanding. In this paper, we tackle these problems by proposing a Pose-Appearance Relational Network (PARNet), which models the correlation between human pose and image appearance, and combines the benefits of these two modalities to improve the robustness towards unconstrained real-world videos. There are three network streams in our model, namely pose stream, appearance stream and relation stream. For the pose stream, a Temporal Multi-Pose RNN module is constructed to obtain the dynamic representations through temporal modeling of 2D poses. For the appearance stream, a Spatial Appearance CNN module is employed to extract the global appearance representation of the video sequence. For the relation stream, a Pose-Aware RNN module is built to connect pose and appearance streams by modeling action-sensitive visual context information. Through jointly optimizing the three modules, PARNet achieves superior performances compared with the state-of-the-arts on both the pose-complete datasets (KTH, Penn-Action, UCF11) and the challenging pose-incomplete datasets (UCF101, HMDB51, JHMDB), demonstrating its robustness towards complex environments and noisy skeletons. Its effectiveness on NTU-RGBD dataset is also validated even compared with 3D skeleton-based methods. Furthermore, an appearance-enhanced PARNet equipped with a RGB-based I3D stream is proposed, which outperforms the Kinetics pre-trained competitors on UCF101 and HMDB51. The better experimental results verify the potentials of our framework by integrating various modules."

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

url_pdf: "https://ieeexplore.ieee.org/document/9986038"
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
  caption: " Architecture of the proposed PARNet"
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
