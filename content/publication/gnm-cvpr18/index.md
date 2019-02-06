+++
title = "Analytic Expressions for Probabilistic Moments of PL-DNN with Gaussian Input"
date = 2017-11-15T00:00:00  # date of submission
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Adel Bibi&ast;", "**Modar Alfadly**&ast;", "Bernard Ghanem"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "**[Oral]** In *The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*, 2018"
publication_short = "**[Oral]** In *CVPR*, 2018"

# Abstract and optional shortened version.
abstract = "The outstanding performance of deep neural networks (DNNs), for the visual recognition task in particular, has been demonstrated on several large-scale benchmarks. This performance has immensely strengthened the line of research that aims to understand and analyze the driving reasons behind the effectiveness of these networks. One important aspect of this analysis has recently gained much attention, namely the reaction of a DNN to noisy input. This has spawned research on developing adversarial input attacks as well as training strategies that make DNNs more robust against these attacks. To this end, we derive in this paper exact analytic expressions for the first and second moments (mean and variance) of a small piecewise linear (PL) network (Affine, ReLU, Affine) subject to general Gaussian input. We experimentally show that these expressions are tight under simple linearizations of deeper PL-DNNs, especially popular architectures in the literature (e.g. LeNet and AlexNet). Extensive experiments on image classification show that these expressions can be used to study the behaviour of the output mean of the logits for each class, the interclass confusion and the pixel-level spatial noise sensitivity of the network. Moreover, we show how these expressions can be used to systematically construct targeted and non-targeted adversarial attacks."
abstract_short = "We derive analytical expressions for the 1<sup>st</sup> and 2<sup>nd</sup> moments of ReLU on a Gaussian random variable to analyze PL-DNNs."

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["network moments"]

# Links (optional).
url_pdf = "http://openaccess.thecvf.com/content_cvpr_2018/papers/Bibi_Analytic_Expressions_for_CVPR_2018_paper.pdf"
url_preprint = ""
url_code = "https://github.com/ModarTensai/network_moments"
url_dataset = ""
url_project = ""
url_slides = "https://drive.google.com/file/d/1cu2jdYItdPblB_MJoWIL73n_tDtRy0xV/view?usp=sharing"
url_video = "https://www.youtube.com/watch?v=op9IBox_TTc&t=945s"
url_poster = "https://drive.google.com/file/d/1au9sd2NALWLrNZWFNDe4AkTRv7b9Z_kA/view?usp=sharing"
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "Supplementary", url = "http://openaccess.thecvf.com/content_cvpr_2018/Supplemental/0487-supp.pdf"}, {name = "CVF", url = "http://openaccess.thecvf.com/content_cvpr_2018/html/Bibi_Analytic_Expressions_for_CVPR_2018_paper.html"}]

# Digital Object Identifier (DOI)
doi = "10.1109/CVPR.2018.00948"

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""  # "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++

In CVPR18, a total of 3359 papers were submitted, 979 papers (29.1%) were accepted, 224 were *Spotlights* (6.7%), and 70 were **Orals** (2.1%) [[source](https://taniai.space/cvconf/)]