---
outputs:
- Reveal
title: Workflows
hidden: true
layout: list
weight: 1
output: hugodown::md_document
rmd_hash: d72ca81ec9ad4774

---

Reproducibility?
================

Should your blog posts still be "knittable?"

------------------------------------------------------------------------

Reproducibility?
================

-   Be able to update your post short/medium term

-   Same for readers except for private data

{{% fragment %}} </br> But blog posts will **age**, which is fine, a blog is not a current docs website. {{% /fragment %}}

------------------------------------------------------------------------

All posts
=========

Need to re-knit posts for migration, tool updates?

{{% fragment %}} Or use the R Markdown output after a point (.md), potentially with YAML/other tweaks.

When I migrated from Jekyll to Hugo I used the .md, not .Rmd. {{% /fragment %}}

------------------------------------------------------------------------

Evergreen posts
===============

If you want a tutorial to be evergreen you'll need to ensure it works with the latest packages etc.

But are tutorials like package vignettes?

------------------------------------------------------------------------

Reproducible analyses
=====================

How to archive your computing environment?

It might be "easier" to archive the analysis elsewhere (tools for scientific articles) and link to that from the blog post.

------------------------------------------------------------------------

Transparency
============

For you, for readers.

-   Add session info to bottom of posts

-   Mention data origin (URL to data?)

------------------------------------------------------------------------

Common sense
============

-   Backup

-   Make note of anything that might be tricky (dev version of a package)

------------------------------------------------------------------------

What's your own take?
=====================

