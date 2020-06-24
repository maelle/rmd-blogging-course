---
outputs:
- Reveal
title: Hugo & hugodown
hidden: true
layout: list
weight: 1
output: hugodown::md_document
rmd_hash: d0d5952faca4bf8f

---

Hugo and hugodown
=================

A powerful static generator, a handy WIP package

------------------------------------------------------------------------

Hugo
====

Powerful and fast static generator

Only an .exe to install :tada:

------------------------------------------------------------------------

hugodown
========

R :package:

-   An R Markdown output format

-   Handy helpers

Experimental but the best bet in my opinion.

------------------------------------------------------------------------

From Rmd to website
===================

Under the hood

{{<mermaid align="left">}}
graph LR;
    A[Rmd] --> |"R ( hugodown :package:, </br> downlit :package:) </br> & Pandoc"| B{md}
    B --> |"Hugo (Goldmark, Chroma)"| C[HTML]
{{< /mermaid >}}

<small>Inspired by [Emi Tanaka's post](https://emitanaka.org/r/posts/2018-12-12-scientific-and-technical-blogging-radix-vs-blogdown/)</small>

------------------------------------------------------------------------

From Rmd to website
===================

What you do

{{<mermaid align="left">}}
graph LR;
    A[Rmd] --> |":large_blue_circle: knit button"| B{md}
    B --> |"hugo build (locally or cloud)"| C[HTML]
{{< /mermaid >}}

------------------------------------------------------------------------

{{< figure src="/images/highlight.jpg" alt="A meme to explain why downlit is great" height="550" >}}

Inspired by [Mara Averick](https://twitter.com/dataandme/status/1255510799273132032)

------------------------------------------------------------------------

