+++
# A Projects section created with the Portfolio widget.
widget = "featured"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "People"


[content]
  # Page type to display. E.g. project.
  page_type = "people"

    # Choose how much pages you would like to display (0 = all pages)
    count = 0

    # Choose how many pages you would like to offset by
    offset = 0

    # Page order. Descending (desc) or ascending (asc) date.
    order = "desc"

    # Filter posts by a taxonomy term.
    [content.filters]
      tag = ""
      category = ""
      publication_type = ""
      author = ""
      exclude_featured = false
      exclude_past = false
      exclude_future = false


[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  view = 2


  # For Showcase view, flip alternate rows?
  flip_alt_rows = false
+++
