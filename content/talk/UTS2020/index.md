+++
title = "Composite likelihood and logistic regression models for aggregated data"
date = 2020-08-14T13:00:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
# time_start = 2030-06-01T13:00:00
# time_end = 2030-06-01T15:00:00
all_day = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["B. Beranger"]

# Abstract and optional shortened version.
abstract = "Symbolic data analysis (SDA) is an emerging technique for the analysis of large and complex datasets where individual level data are summarised into group-based distributional summaries (symbols) such as random rectangles or histograms.Likelihood-based methods have been recently developed, allowing to fit models for the underlying data while only observing distributional summaries. However, while powerful, when working with random histograms this approach rapidly becomes computationally intractable as the dimension of the underlying data increases. In this talk we first introduce a composite likelihood setting for the analysis of random histograms in K dimensions using lower-dimensional marginal histograms. We apply this approach to bypass the well known computational issues in the analysis of spatial extremes over large number of spatial locations, and show large computational savings compared to existing model fitting procedures. Logistic regression models are a popular method to predict the probability of categorical response data. However inference for these models can become computationally prohibitive for large datasets. The second part of the talk focuses on summarising a collection of predictor variables into histograms in order to perform inference. Based on composite likelihoods, we derive an efficient one-versus rest approximate composite likelihood model for histogram-value random variables. We demonstrate that this procedure can achieve comparable classification rates than state-of-the-art subsampling algorithms for logistic regression."
abstract_short = ""

# Name of event and optional event URL.
event = "University of Technology Sydney, Mathematics Colloquium"
event_url = "https://www.uts.edu.au/about/faculty-science/school-mathematical-and-physical-sciences/seminars-and-colloquia"

# Location of event.
location = "Online (Sydney, Australia)"

# Is this a featured talk? (true/false)
featured = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = "BB_UTS.pdf"

# Links (optional).
url_pdf = "pdf/BB_UTS.pdf"
url_slides = ""
url_video = "https://www.youtube.com/watch?v=Lg-l5f1gUkc&list=PLHjOMouVJ7UU0twTM2O_I5URNlTxUYUCm&index=11"
url_code = ""

# Does the content use math formatting?
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Right"
+++
 
 Recording of the seminar:
 
 {{<youtube Lg-l5f1gUkc >}}
