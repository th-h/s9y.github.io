# s9y documentation (Github Pages)

This is the documentation for [Serendipity](http://s9y.org).

## Contributing

Documentation is maintained in [Markdown](https://daringfireball.net/projects/markdown/) (`.md`) files using the [kramdown](http://kramdown.gettalong.org) library to transform it to HTML though [Jekyll](http://jekyllrb.com) on [GitHub pages](https://pages.github.com).

### Markdown usage

* Some heading levels are reserved for other elements of the site layout. The first heading level you may use in Markdown files is `h3` (`###` in Markdown), so you have `h3` to `h6` available. If you feel that a section needs more structuring, it should probably be split up in two or more sections.
* Note that three backticks *only* introduce a code block in *GitHub* flavored Markdown. In generic Markdown (which is what we have in Jekyll), code blocks are generated by indenting the code 4 spaces or a tab (please use 4 space here).
* Also, a span of code in copy text (i.e. `<code>` within `<p>`, not within `<pre>`) is limited by single backticks, not three backticks.
* To set internal links (i.e. links to other pages of the docs), please use relative links starting with a `/`, and *always* link to the HTML version of the page; for example `/docs/faq/index.html`

### Jekyll usage

* Every Markdown file needs a [YAML front matter](http://jekyllrb.com/docs/frontmatter/) with at least a sensible title. Like this:

```
---
title: Documentation
---
```

* You can also set the layout for a page in the YAML front matter. See `_layouts` for available layouts.

```
---
layout: home
title: Serendipity
---
```
