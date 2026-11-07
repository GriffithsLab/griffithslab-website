+++
# Project title.
title = "Models & Theory"
weight = 2

# Date this page was created.
#date = 2016-04-27T00:00:00
date = 2019-01-03

# JG_ADD; c.f. hugo.io conversation
showFooter = false


# Project summary to display on homepage.
summary = "Whole-brain, neural mass and neural field models, and the mathematical and computational tools for fitting them to neuroimaging data."

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Optional external URL for project (replaces project detail page).
#external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides = "example-slides"
# slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  preview_only = true
#  # Caption (optional)
# caption = "transition from a clean alpha-frequency limit cycle to a multi-frequency regime with nested gamma oscillations in a thalamocortical mean field model of EEG activity" 
  
#  # Focal point (optional)
#  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "TopLeft"


+++

Computational modelling is the common thread running through almost all of our work. We develop and apply whole-brain (connectome-based) neural mass models, corticothalamic and neural field models, and detailed cortical microcircuit models, together with the mathematical theory needed to understand their behaviour. A major focus is methodology: fitting models to individual subjects' EEG, MEG and fMRI data using deep-learning-based parameter estimation tools such as [WhoBPyT](/code_and_software/whobpyt/), assessing how much individual-level information these models capture, and making whole-brain modelling more reproducible and accessible through open-source software, tutorials and courses.
