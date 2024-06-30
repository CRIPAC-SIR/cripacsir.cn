---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Combining 2D texture and 3D geometry features for Reliable iris presentation attack detection using light field focal stack"
authors: ["Zhengquan Luo", "Yunlong Wang", "Nianfeng Liu", "Zilei Wang"]
date: 2022-08-27T16:12:05+08:00
doi: "10.1049/bme2.12092"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-08-27T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IET Biometrics 11.5 (2022)*"

abstract: "Iris presentation attack detection (PAD) is still an unsolved problem mainly due to the various spoof attack strategies and poor generalisation on unseen attackers. In this paper, the merits of both light field (LF) imaging and deep learning (DL) are leveraged to combine 2D texture and 3D geometry features for iris liveness detection. By exploring off-the-shelf deep features of planar-oriented and sequence-oriented deep neural networks (DNNs) on the rendered focal stack, the proposed framework excavates the differences in 3D geometric structure and 2D spatial texture between bona fide and spoofing irises captured by LF cameras. A group of pre-trained DL models are adopted as feature extractor and the parameters of SVM classifiers are optimised on a limited number of samples. Moreover, two-branch feature fusion further strengthens the framework's robustness and reliability against severe motion blur, noise, and other degradation factors. The results of comparative experiments indicate that variants of the proposed framework significantly surpass the PAD methods that take 2D planar images or LF focal stack as input, even recent state-of-the-art (SOTA) methods fined-tuned on the adopted database. Presentation attacks, including printed papers, printed photos, and electronic displays, can be accurately detected without fine-tuning a bulky CNN. In addition, ablation studies validate the effectiveness of fusing geometric structure and spatial texture features. The results of multi-class attack detection experiments also verify the good generalisation ability of the proposed framework on unseen presentation attacks."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Light Field Photography", "Iris-liveness-detection"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://ietresearch.onlinelibrary.wiley.com/doi/epdf/10.1049/bme2.12092"
url_code: "https://github.com/luozhengquan/LFLD"
url_dataset: "http://www.cripacsir.cn/dataset/"
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
projects: ["Iris Recognition", "Light Field Photography"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
