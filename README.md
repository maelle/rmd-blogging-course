
# Scientific blogging with R Markdown

<!-- badges: start -->
[![Netlify Status](https://api.netlify.com/api/v1/badges/87a90f80-f65e-4bac-9e50-2ffa6ab8936a/deploy-status)](https://app.netlify.com/sites/scientific-rmd-blogging/deploys)
<!-- badges: end -->

Source of the website of a short course.

It is powered by [Hugo](https://gohugo.io/) and the following theme:

* [Hugo theme learn](https://github.com/matcornic/hugo-theme-learn)
* [Hugo theme reveal-hugo](https://github.com/dzello/reveal-hugo)

Slides for each section are listed in the menu and opened in a new tab (thanks to a [custom menu layout](/blob/master/layouts/partials/menu.html), compared to the original Hugo learn theme).

Some Markdown content is generated with [R Markdown](https://rmarkdown.rstudio.com/), using [hugodown](https://github.com/r-lib/hugodown/).

The website is deployed by [Netlify](https://www.netlify.com/).

Slides could be printed to PDF using Decktape which I [have done in a concept](https://github.com/maelle/test-course-site) but I am not pursuing it further.

### Why these tools?

Why use Hugo for both the website and slidedecks, and not, say Hugo+hugodown for pages and xaringan for slides?
This way the source of slides is html produced by Hugo from Markdown content.
It allows me to use:

* downlit syntax highlighting for slides created from R Markdown with hugodown output format;
* Chroma syntax highlighting for other languages;
* emojis! `:grin:` works in slides;
* Shortcodes in slides, should I choose to.

Also, because slides are in the content, they are indexed by the Hugo learn theme so searchable!

