# hugo-apero-notes

Notes for editing and setting up a Hugo Apero website in R.


## Sections

Blog, projects, and other pages are called sections. Apéro provides unique layouts for three main content sections:

* blogs
* projects
* talks

### Renaming Sections

What happens if we need to rename a section? For example, if we were edting the Blog section

## Collections


This is a tricky area to navigate.

* Right now, use the `/collection/*/` format, where `/*/` is a section page. In that section apge, change the layout to `list-sidebar` to display a list of the entries as the landing page.
* Retain `layout: single-series` in the meta data if you want to create a unique landing page.

## Other

### `config.yaml` vs `config.toml`

Not sure why, but my website created a `.yaml` file instead of a `.toml` file. Here is [a gist explaining the syntax translation](https://gist.github.com/oconnor663/9aeb4ed56394cb013a20).
