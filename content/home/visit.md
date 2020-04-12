+++
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 75  # Order that this section will appear.

title = "Visit"
subtitle = "Want to spend some time visiting?"

[content]
  # Page type to display. E.g. project.
  page_type = "visit"

  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.

  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0

  [[content.filter_button]]
    name = "All"
    tag = "*"

  [[content.filter_button]]
    name = "PhD students"
    tag = "PhD"

  [[content.filter_button]]
    name = "Established researchers"
    tag = "established"  

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false


+++

Visitors to the project are very welcome. Contact [Johannes Stern](mailto:johannes.stern@bristol.ac.uk).

Browse options for funding visits:
