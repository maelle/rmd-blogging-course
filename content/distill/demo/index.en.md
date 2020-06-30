---
title: Notes from the demo
menuTitle: Demo
weight: 5
slides: true
output: hugodown::md_document
rmd_hash: 56c6444412ac02ba

---

-   show the RStudio IDE, ask whether anyone is unfamiliar with it.

-   install the distill package, [`install.packages("distill")`](https://rdrr.io/r/utils/install.packages.html)

-   create blog (from RStudio Create New Project, not [`distill::create_blog()`](https://rdrr.io/pkg/distill/man/create_website.html)).

-   what's in the folder now?

-   show website in local browser.

-   [`usethis::use_git()`](https://usethis.r-lib.org/reference/use_git.html)

-   change site but not URL, and about. change citations: true!!!

-   rebuild the site via RStudio build button or [`rmarkdown::render_site()`](https://rdrr.io/pkg/rmarkdown/man/render_site.html).

-   show website in local browser.

-   edit and knit welcome. including author info!!

-   look what changed, commit

-   show website in local browser.

-   look at post html in \_posts and \_site. mention navbar

-   commit

-   add a post with [`distill::create_post()`](https://rdrr.io/pkg/distill/man/create_post.html). knit, look what changed this time.

-   add references

-   add latex, mention JavaScript

-   add footnote and aside

-   put website online via Netlify drag and drop.

-   add base\_url to site config, show citations metadata is added.

-   Netlify drag and drop.

-   Some minimal styling. Introduce the web developer console.

-   Netlify drag and drop

-   GitHub repo [`usethis::use_github()`](https://usethis.r-lib.org/reference/use_github.html)

-   mention git checkout -b and [the distill docs about blog post workflows](https://rstudio.github.io/distill/blog_workflow.html).

-   Other options for deployment (Netlify link to repo, [distill docs](https://rstudio.github.io/distill/publish_website.html))

-   add Twitter&GitHub

