+++
# Projects widget.
widget = "projects"
active = true
#date = 2016-04-20T00:00:00
date = ""

title = "Research Areas"
subtitle = "The core research activites of the group consist of applying whole-brain modelling techniques to a variety of research questions relating to ***brain stimulation***, ***brain rhythms***, and ***brain networks***. Most projects involve intersections of 2 or 3 of these, and have both basic science and clinical application components, such as therapeutic brain stimulation for depression. We also have a number of additional ongoing projects involving mobile EEG, fNIRS, sleep, neuroinformatics, and computational modelling methodology. See below for more info on each of these, as well as links to relevant publications and reproducible code."


# Order that this section will appear in.
weight = 2

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
#folder = "research"
folder = "project"

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards, 2 = showcase.
#view = 1
view = 1

# Widget layout
# Legend: 0 = two columns (default), 1 = single column
#widget_layout = 0
widget_layout = 1


# For Showcase view, flip alternate rows?
flip_alt_rows = true

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 1

# Add or remove as many filters (`[[filter]]` instances) as you like.
# To show all items, set `tag` to "*".
# To filter by a specific tag, set `tag` to an existing tag name.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.

[[filter]]
  name = "All"
  tag = "*"

[[filter]]
  name = "Primary Areas"
  tag = "primaryarea"

[[filter]]
  name = "Additional Projects"
  tag = "secondaryarea"

#[[filter]]
#  name = "Other"
#  tag = "Demo"

+++
