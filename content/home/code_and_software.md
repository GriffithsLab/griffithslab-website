+++
# Projects widget.
#widget = "research"
widget = "projects"
active = true
#date = 2016-04-20T00:00:00

title = "Code & Software"
subtitle = "Pointers to various code and software tools that we have either developed ourselves, or use extensively. Non-exhaustive list! See also the [grifflab github organization](https://github.com/griffithslab)."

# Order that this section will appear in.
weight = 6

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
#folder = "research"
folder = "code_and_software"

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards, 2 = showcase.
#view = 1
view = 1

# Widget layout
# Legend: 0 = two columns (default), 1 = single column
widget_layout = 0
#widget_layout = 1


# For Showcase view, flip alternate rows?
flip_alt_rows = false

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
  name = "Featured"
  tag = "Featured"

[[filter]] 
  name = "Papers"
  tag = "Papers"

[[filter]]
  name = "Education"
  tag = "Education"

[[filter]]
  name = "Software Libraries"
  tag = "Software_Libraries"


[[filter]]
  name = "Misc"
  tag = "Misc"
+++

