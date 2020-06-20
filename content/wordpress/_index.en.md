---
title: WordPress
weight: 3
chapter: true
slides: true
output: hugodown::md_document
rmd_hash: b6188ee88187119c

---

WordPress
=========

First of all, no shame!

{{< tweet 1259058742513012736 >}}

Our challenge
-------------

How to publish your R Markdown posts to a WordPress website without copy-pasting?[^1]

The only modern solution is to my knowledge, my [own WIP package `goodpress`](https://github.com/maelle/goodpress). I'll explain a few setup steps on your website, and how to organize your posts to publish them with [`goodpress::wp_post()`](https://rdrr.io/pkg/goodpress/man/wp_post.html), if you're brave enough for using my tool. :wink:

[^1]: Copy-pasting is ok, [the pros do it](https://twitter.com/gvwilson/status/1274324689322741760); it's just not the vibe of this course.

