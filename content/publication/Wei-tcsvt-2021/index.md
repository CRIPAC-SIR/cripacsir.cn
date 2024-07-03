---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Cross-spectral Iris Recognition by Learning Device-specific Band"
authors: ["Jianze Wei", "Yunlong Wang", "Yi Li", "Ran He", "Zhenan Sun"]
date: 2021-10-04T16:12:05+08:00
doi: "10.1109/TCSVT.2021.3117291"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-04T08:58:18+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "* IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)*"

abstract: "Cross-spectral recognition is still an open challenge in iris recognition. In cross-spectral iris recognition, there exist distinct device-specific bands between near-infrared (NIR) and visible (VIS) images, resulting in the distribution gap between samples from different spectra and thus severe degradation in recognition performance. To tackle this problem, we propose a new cross-spectral iris recognition method to learn spectral-invariant features by estimating device-specific bands. In the proposed method, Gabor Trident Network (GTN) first utilizes the Gabor function’s priors to perceive iris textures under different spectra, and then codes the device-specific band as the residual component to assist the generation of spectral-invariant features. By investigating the device-specific band, GTN effectively reduces the impact of device-specific bands on identity features. Besides, we make three efforts to further reduce the distribution gap. First, Spectral Adversarial Network (SAN) adopts a class-level adversarial strategy to align feature distributions. Second, Sample-Anchor (SA) loss upgrades triplet loss by pulling samples to their class center and pushing away from other class centers. Third, we develop a higher-order alignment loss to measures the distribution gap according to space bases and distribution shapes. Extensive experiments on five iris datasets demonstrate the efficacy of our proposed method for cross-spectral iris recognition."

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

url_pdf: "https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9557317"
url_code: https://github.com/weijianze/CSINv2
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
  caption: "Flexible Iris Matching Based on Spatial Feature Reconstruction"
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
