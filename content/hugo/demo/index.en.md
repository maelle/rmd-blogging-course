---
title: Notes from the demo
menuTitle: Demo
weight: 5
slides: true
output: hugodown::md_document
rmd_hash: 3a35102882bfc554

---

-   install the remotes package, `install.packages("remotes)`

-   install the hugodown package, [`remotes::install_github("r-lib/hugodown")`](https://remotes.r-lib.org/reference/install_github.html)

-   install Hugo. new RStudio empty project.

-   `hugo new site . --force` from the command line in that new folder.

-   Download <a href="https://github.com/yihui/hugo-xmin" class="uri">https://github.com/yihui/hugo-xmin</a> and put into themes, remove "-master" from the folder name, delete example site.

-   Copy paste <a href="https://github.com/yihui/hugo-xmin/blob/master/exampleSite/config.toml" class="uri">https://github.com/yihui/hugo-xmin/blob/master/exampleSite/config.toml</a>

-   [`hugodown::hugo_start()`](https://rdrr.io/pkg/hugodown/man/hugo_start.html)

-   copy-paste from [hugodown setup vignette](https://hugodown.r-lib.org/articles/config.html)

-   create static/code.css from <a href="https://github.com/maelle/goodpress/blob/main/inst/css/code.css" class="uri">https://github.com/maelle/goodpress/blob/main/inst/css/code.css</a> and create layouts/partial/head\_custom.html according to <a href="https://xmin.yihui.org/about/" class="uri">https://xmin.yihui.org/about/</a> (one should read theme docs!)

-   create post in post and copy-paste from snippets page. knit, preview.

-   add maths, citations.

-   for mathjax copy paste from <a href="https://xmin.yihui.org/about/" class="uri">https://xmin.yihui.org/about/</a> and say one should always read the docs!

-   Netlify drag and drop

-   then something easier from the code point of view but more overwhelming!

-   create empty RStudio project (with git if it's available)

-   [`hugodown::hugo_install('0.66.0')`](https://rdrr.io/pkg/hugodown/man/hugo_install.html)

-   [`hugodown::create_site_academic()`](https://rdrr.io/pkg/hugodown/man/create_site_academic.html)

-   [`hugodown::hugo_start(render_to_disk = TRUE)`](https://rdrr.io/pkg/hugodown/man/hugo_start.html), open localhost in the browser.

-   Change site title in config/\_default/params.toml.

-   Mention academic docs, all the things one can change.

-   [`hugodown::use_post("post/new-rmd-post")`](https://rdrr.io/pkg/hugodown/man/use_post.html), knit, see post.

-   say there will probably be other themes later. show Hugo theme gallery and how I would choose themes.

