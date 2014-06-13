Staticbl
========

staticbl - yet another simple static blog generator, using jinja2 and creole wiki-syntax. Supports russian transliteraion in urls.

You can use it with [Git Pages](https://pages.github.com/)

How to setup
========
All system files are in `_staticbl`, pages are in `_staticbl/_data/` by default

See settings dict in `_staticbl/staticbl.py`. You can set menu links at `_staticbl/templates/menu.html`

Change `_staticbl/templates/base.html` for a new design.

How to use
========
*Posting* - creates a .wiki file at `_staticbl/_data/`
`python staticbl.py post "Your post title"`

*Building* - creates .html files ready for upload
`python staticbl.py build`

*Serving* - for testing site at localhost
`python staticbl.py serve`

