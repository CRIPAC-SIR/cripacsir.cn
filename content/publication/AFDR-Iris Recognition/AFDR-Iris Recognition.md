---
title: "Alignment Free and Distortion Robust Iris Recognition"
authors:
- Min Ren
#- Robert Ford
date: "2020-08-20T07:42:58Z"
doi: "10.1109/ICB45273.2019.8987369"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-20T07:42:58Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1","2"]

# Publication name and optional abbreviated publication name.
publication: In *2019 International Conference on Biometrics*
publication_short: In *ICB*

abstract: Iris recognition is a reliable personal identification method but there is still much room to improve its accuracy especially in less-constrained situations. For example, free movement of head pose may cause large rotation difference between iris images. And illumination variations may cause irregular distortion of iris texture. To match intra-class iris images with head rotation robustly, the existing solutions usually need a precise alignment operation by exhaustive search within a determined range in iris image preprosessing or brute-force searching the minimum Hamming distance in iris feature matching. In the wild enviroments, iris rotation is of much greater uncertainty than that in constrained situations and exhaustive search within a determined range is impracticable. This paper presents a unified feature-level solution to both alignment free and distortion robust iris recognition in the wild. A new deep learning based method named Alignment Free Iris Network (AFINet) is proposed, which utilizes a trainable VLAD (Vector of Locally Aggregated Descriptors) encoder called NetVLAD [18] to decouple the correlations between local representations and their spatial positions. And deformable convolution [5] is leveraged to overcome iris texture distortion by dense adaptive sampling. The results of extensive experiments on three public iris image databases and the simulated degradation databases show that AFINet significantly outperforms state-of-art iris recognition methods.


# Summary. An optional shortened abstract.
summary: Alignment Free, Iris Recognition, Preprocessing.

tags:
- Source Themes
featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8987369
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'featured.png'
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/# academic/docs/writing-markdown-latex/). -->

