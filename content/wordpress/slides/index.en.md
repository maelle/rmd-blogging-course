---
outputs:
- Reveal
title: R Markdown & WordPress
hidden: true
layout: list
weight: 1
output: hugodown::md_document
rmd_hash: c69b623340e1a452

---

WordPress
=========

------------------------------------------------------------------------

Why use WordPress?
==================

-   Clicking to design the interface

-   Internationalization

-   Open Source

------------------------------------------------------------------------

Why NOT use WordPress
=====================

-   Performance?

-   Security?

If you use WordPress, read the docs.

------------------------------------------------------------------------

Do you use WordPress?
=====================

------------------------------------------------------------------------

Workarounds for no WordPress
============================

-   Use a subdomain for your R Markdown blog, linked from your main WordPress website.

-   [Netlify CMS](https://www.netlifycms.org/) and other CMS as an user-friendly interface on static websites (like Hugo).

------------------------------------------------------------------------

Now, Rmd and WordPress!
=======================

-   [`knitr::knit2wp()`](https://rdrr.io/pkg/knitr/man/knit2wp.html) is now too dated (it uses `RCurl` and `XML`)

-   I made a package using WordPress REST API v2!

So your choice is between a too old tool and my WIP package. :joy:

------------------------------------------------------------------------

wordpress.com vs wordpress.org
==============================

-   Free/cheap wordpress.com: no plugin (so no API)

-   Business wordpress.com: \$\$\$

-   Your own local server: efforts

-   Paid service hosting+domain name+ WordPress install: a few \$ a month

------------------------------------------------------------------------

From Rmd to website
===================

Under the hood

{{<mermaid align="left">}}
graph LR;
    A[Rmd] --> |"R ( hugodown :package:, </br> downlit :package:) </br> & Pandoc"| B{md}
    B --> |"R (xml2 :package: ) </br> & Pandoc"| C[HTML]
    C --> |"WordPress"| D[HTML]
{{< /mermaid >}}

------------------------------------------------------------------------

From Rmd to website
===================

What you do

{{<mermaid align="left">}}
graph LR;
    A[Rmd] --> |":large_blue_circle: knit button"| B{md}
    B --> |"run wp_post()"| C[HTML]
    C --> |"Wait"| D[HTML]
{{< /mermaid >}}

------------------------------------------------------------------------

Setup for goodpress (0/2)
=========================

Have a WordPress website that's not a free/cheap plan from wordpress.com :wink:

------------------------------------------------------------------------

Setup for goodpress (1/2)
=========================

-   Install the [Application Passwords plugin](https://wordpress.org/plugins/application-passwords/)

-   Edit [.htaccess](https://github.com/WordPress/application-passwords/wiki/Basic-Authorization-Header----Missing) (with a plugin?)

-   Create an user with limited rights, and an application password for them

------------------------------------------------------------------------

Setup for goodpress (2/2)
=========================

For R syntax highlighting :sparkles:

-   Find [my code.css](https://github.com/maelle/goodpress/blob/main/inst/css/code.css) and copy it to your clipboard.

-   From your WordPress admin dasbhoard, go to Appearance &gt; Customize &gt; Additional CSS. Paste the CSS there and click on publish.

