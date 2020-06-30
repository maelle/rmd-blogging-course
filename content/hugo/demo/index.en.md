---
title: Notes from the demo
menuTitle: Demo
weight: 5
slides: true
output: hugodown::md_document
rmd_hash: b8ce566e1116baf4

---

-   install the remotes package, `install.packages("remotes)`

-   install the hugodown package, [`remotes::install_github("r-lib/hugodown")`](https://remotes.r-lib.org/reference/install_github.html)

-   [`hugodown::hugo_install()`](https://rdrr.io/pkg/hugodown/man/hugo_install.html)

-   new RStudio empty project.

-   `hugo new site . --force` from the command line in that new folder.

-   Download <a href="https://github.com/yihui/hugo-xmin" class="uri">https://github.com/yihui/hugo-xmin</a> and put into themes, remove "-master" from the folder name, delete example site.

-   Copy paste <a href="https://github.com/yihui/hugo-xmin/blob/master/exampleSite/config.toml" class="uri">https://github.com/yihui/hugo-xmin/blob/master/exampleSite/config.toml</a>

-   Create `_hugodown.yaml` with `hugo_version: 0.73.0`

-   [`hugodown::hugo_start()`](https://rdrr.io/pkg/hugodown/man/hugo_start.html)

-   add about.md

-   copy-paste from [hugodown setup vignette](https://hugodown.r-lib.org/articles/config.html)

-   create [static/css/code.css](/snippets/#codecss) from and create [layouts/partial/head\_custom.html](/snippets/#head_customhtml) (one should read [theme docs](https://xmin.yihui.org/about/)!)

-   for mathjax create [layouts/partial/foot\_custom.html](/snippets/#head_customhtml)

-   create post in content/post/2020-06-25-cool/index.Rmd and copy-paste from snippets page. knit, preview.

-   add citations.

-   [`hugodown::hugo_stop()`](https://rdrr.io/pkg/hugodown/man/hugo_start.html), [`hugodown::hugo_start(render_to_disk = TRUE)`](https://rdrr.io/pkg/hugodown/man/hugo_start.html)

-   Netlify drag and drop

-   then something easier from the code point of view but more overwhelming!

-   create empty RStudio project (with git if it's available)

-   [`hugodown::hugo_install('0.66.0')`](https://rdrr.io/pkg/hugodown/man/hugo_install.html)

-   [`hugodown::create_site_academic()`](https://rdrr.io/pkg/hugodown/man/create_site_academic.html). Be happy to see everything happening automatically :sparkles:

-   [`hugodown::hugo_start(render_to_disk = TRUE)`](https://rdrr.io/pkg/hugodown/man/hugo_start.html), open localhost in the browser.

-   Change site title and [theme](https://sourcethemes.com/academic/themes/) in config/\_default/params.toml. Yes a theme for a theme!

-   Mention [academic docs](https://sourcethemes.com/academic/), all the things one can change.

-   [`hugodown::use_post("post/new-rmd-post")`](https://rdrr.io/pkg/hugodown/man/use_post.html), knit, see post.

-   say there will probably be other themes later. show [Hugo theme gallery](https://themes.gohugo.io/) and how I would choose themes.

-   [`usethis::use_github()`](https://usethis.r-lib.org/reference/use_github.html), [`hugodown::use_netlify_toml()`](https://rdrr.io/pkg/hugodown/man/use_netlify_toml.html), go to Netlify interface.

