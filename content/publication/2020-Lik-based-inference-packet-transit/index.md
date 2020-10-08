+++
title = "Likelihood-based inference for modelling packet transit from thinned flow summaries"
date = 2020-08-31T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Prosha A. Rahman", "B. Beranger", "M. Roughan","S.A. Sisson"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Submitted"
# publication_short = ""

# Abstract and optional shortened version.
abstract = "The substantial growth of network traffic speed and volume presents practical challenges to network data analysis. Packet thinning and flow aggregation protocols such as NetFlow reduce the size of datasets by providing structured data summaries, but conversely this impedes statistical inference.  Methods which aim to model patterns of traffic propagation typically do not account for the packet thinning and summarisation process into the analysis, and are often simplistic, e.g.~method-of-moments. As a result, they can be of limited practical use. We introduce a likelihood-based analysis which fully incorporates packet thinning and NetFlow summarisation into the analysis. As a result, inferences can be made for models on the level of individual packets while only observing thinned flow summary information. We establish consistency of the resulting maximum likelihood estimator, derive bounds on the volume of traffic which should be observed to achieve required levels of estimator accuracy, and identify an ideal family of models. The robust performance of the estimator is examined through simulated analyses and an application on a publicly available trace dataset containing over 36m packets over a 1 minute period."

abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides = "example-slides"

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/pdf/2008.13424.pdf"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "Coming soon"

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Figure 1"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

