+++
title = "TMS-Evoked Responses Are Driven by Recurrent Large-Scale Network Dynamics"
date = 2023-04-21T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Davide Momi", "Zheng Wang", "John D. Griffiths"]

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
publication = "eLife"
#publication_short = ""

# Abstract and optional shortened version.
abstract = "A major question in systems and cognitive neuroscience is to what extent neurostimulation responses are driven by recurrent activity. This question finds sharp relief in the case of TMS-EEG evoked potentials (TEPs). TEPs are spatiotemporal waveform patterns with characteristic inflections at ∼50ms, ∼100ms, and ∼150-200ms following a single TMS pulse that disperse from, and later reconverge to, the primary stimulated regions. What parts of the TEP are due to recurrent activity? And what light might this shed on more general principles of brain organization? We studied this using source-localized TMS-EEG analyses and whole-brain connectome-based computational modelling. Results indicated that recurrent network feedback begins to drive TEP responses from ∼100ms post-stimulation, with earlier TEP components being attributable to local reverberatory activity within the stimulated region. Subject-specific estimation of neurophysiological parameters additionally indicated an important role for inhibitory GABAergic neural populations in scaling cortical excitability levels, as reflected in TEP waveform characteristics."

abstract_short = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project''s folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["neurostimulation", "network_structure_dynamics", "models_and_theory"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["brain stimulation", "brain networks"]

# Links (optional).
#url = "https://elifesciences.org/articles/83232"
url_pdf = "https://raw.githubusercontent.com/GriffithsLab/griffithslab-papers/main/Momi%20et%20al.%202023%20-%20TMS-evoked%20responses%20are%20driven%20by%20recurrent%20large-scale%20network%20dynamics.pdf"

#url_preprint = "https://www.biorxiv.org/content/10.1101/2022.06.09.494069v1"
url_code = "https://github.com/GriffithsLab/PyTepFit"

#url_dataset = "#"
#url_project = ""
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"



# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]
#url_custom = [{name = "url", url = "https://www.frontiersin.org/articles/10.3389/fams.2018.00031/full"}]
#url_custom = [{name = "PDF", url = "https://tinyurl.com/4etcdste"}]

# Digital Object Identifier (DOI)
doi = "10.7554/eLife.83232"

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page`s folder. 
[image]
#  # Caption (optional)
#  #caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
#  Focal point (optional)
#  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"

# Key figures from the paper, shown after the abstract (paraphrased captions).
[[key_figures]]
  number = 2
  file = "keyfig2.jpg"
  caption = "Simulated versus empirical TMS-EEG: the personalised models reproduce each subject's evoked potentials and scalp topographies, with high correlations across subjects."

[[key_figures]]
  number = 4
  file = "keyfig4.jpg"
  caption = "Virtual lesions: cutting recurrent connections from the stimulated region early on (20 and 50 ms after the pulse) suppresses later evoked activity, showing that late TMS-evoked potentials depend on network recurrence."

[[key_figures]]
  number = 6
  file = "keyfig6.jpg"
  caption = "Workflow for subject-specific connectome-based modelling of TMS-EEG: tractography-based connectome, neural mass model, forward model to EEG, and gradient-based fitting to each subject's evoked responses."

+++
