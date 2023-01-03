+++

title = "Deep-learning based parameter estimation for neurophysiological models of neuroimaging data"
date = 2022-10-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["John D. Griffiths", "Zheng Wang", "Andrew Clappison", "Syed Hussain Ather", "Davide Momi", "Scott Rich", "Andreea Diaconescu", "Anthony Randal McIntosh", "Kelly Shen"]


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
publication = "BioRXiv"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Connectome-based neural mass modelling is the emerging computational neuroscience paradigm for simulating large-scale network dynamics observed in whole-brain activity measurements such as fMRI, M/EEG, and related techniques. Estimating physiological parameters by fitting these models to empirical data is challenging however, due to large network sizes, often physiologically detailed fast-timescale system equations, and the need for long (e.g. tens of minutes) simulation runs. Here we introduce a novel approach to connectome-based neural mass model parameter estimation by employing optimization tools developed for deep learning. We cast the system of differential equations representing both neural and haemodynamic activity dynamics as a deep neural network, implemented within a widely used machine learning programming environment (PyTorch). This allows us to use robust industry-standard optimization algorithms, automatic differentiation for computation of gradients, and other useful functionality. The approach is demonstrated using a connectome-based network with nodal dynamics specified by the two-state RWW mean-field neural mass model equations, which we use here as a model of fMRI-measured activity and correlation fluctuations. Additional optimization constraints are explored and prove fruitful, including restricting the model to domains of parameter space near a bifurcation point that yield metastable dynamics. Using these techniques, we first show robust recovery of physiological model parameters in synthetic data and then, as a proof-of-principle, apply the framework to modelling of empirical resting-state fMRI data from the Human Connectome Project database. For resting state activity, the system can be understood as a deep net that receives uncorrelated noise on its input layer, which is transformed into network-wide modelled functional connectivity on its output layer. This is consistent with the prevailing conception in theoretical neuroscience of resting-state functional connectivity patterns as an emergent phenomenon that is driven by (effectively) random activity fluctuations, which are then in turn spatiotemporally filtered by anatomical connectivity and local neural dynamics."


abstract_short = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project''s folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["brain_networks", "brain_rhythms"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
#tags = ['selected']

# Links (optional).
url_pdf = "https://www.biorxiv.org/content/10.1101/2022.05.19.492664v1.full.pdf"
url_preprint = "https://www.biorxiv.org/content/10.1101/2022.05.19.492664v1.abstract"
url_code = "https://github.com/GriffithsLab/dl-paramest-for-neurophys-models"
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
doi = "10.1101/2022.05.19.492664"
# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page`s folder. 
[image]
#  # Caption (optional)
#  #caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
#  Focal point (optional)
#  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "BottomLeft"
+++
