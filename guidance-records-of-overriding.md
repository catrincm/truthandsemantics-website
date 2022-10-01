Overriding the theme:

# Event vs Talks

Theme only has `event` type. I have duplicated it to have a separte `talk`. Only did it with compact view, as that's what I'm using.

This involves the
- `layouts/partials/page_metadata.html`
- `layouts/partials/views/compact.html`
- `layouts/section/talk.html`
- `layouts/talk/single.html`

# People

To display list of people, i.e., research team. Not supported. I've used the compact list.

Added "people" instruction in `layouts/partials/views/compact.html` to not display date.


# Past People

I just did the people thing also for a past-people folder. Hacky solution, but fine for now. 
