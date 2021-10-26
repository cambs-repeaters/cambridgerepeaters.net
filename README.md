Cambridgeshire Repeater Group website
-------------------------------------

This repository hosts the CRG website, cambridgerepeaters.net.

It's hosted on GitHub Pages, and uses Jekyll to build a static site from content in this repository.

https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-content-to-your-github-pages-site-using-jekyll has some useful notes for the Git workflow, and the Jekyll docs at https://jekyllrb.com/docs/pages/ provide more details.

Metadata for our repeaters is defined using Jekyll frontmatter, and the various status tables are built up from that. For example, to change the status of GB3PX, edit `status: Operational` in `_repeaters/gb3px.md`. This will automatically update both the site homepage, and the repeater details page.

Documentation for our users should go in `_docs`, and will automatically be added to the table of contents under the Documentation section of the site.

Relevant additional information for each repeater should be listed in the `findoutmore` frontmatter, with a title and link. This will be rendered in a call-out box on the repeater's details page.