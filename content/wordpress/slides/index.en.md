---
outputs:
- Reveal
title: R Markdown & WordPress
hidden: true
layout: list
weight: 1
reveal_hugo:
  theme: "solarized"
  margin: 0.2
output: hugodown::md_document
rmd_hash: 1c1b2dd2afa6e08f

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

