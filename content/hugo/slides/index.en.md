---
outputs:
- Reveal
title: Hugo & hugodown
hidden: true
layout: list
weight: 1
output: hugodown::md_document
rmd_hash: 96e2b429e87643ba

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

No syntax highlighting

<pre><code>ggplot2::ggplot()
</code></pre>

Chroma

```r
ggplot2::ggplot()
```

downlit

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='k'>ggplot2</span>::<span class='nf'><a href='https://ggplot2.tidyverse.org/reference/ggplot.html'>ggplot</a></span>()</code></pre>

</div>

------------------------------------------------------------------------

{{< figure src="/images/highlight.jpg" alt="A meme to explain why downlit is great" height="550" >}}

Inspired by [Mara Averick](https://twitter.com/dataandme/status/1255510799273132032)

------------------------------------------------------------------------

hugodown syntax highlighting
============================

-   downlit for R :tada:

-   Chroma for other languages :sparkles:

------------------------------------------------------------------------

:mountain_cableway: Time for a demo!

[Notes on the course website](/hugo/demo/)

------------------------------------------------------------------------

Scientific Rmd Blog Checklist

-   [x] R Markdown
-   [x] Syntax highlighting (for all knitr-supported languages)
-   [x] Modern
-   [x] .bib
-   [x] Citation for posts
-   [x] Equations

------------------------------------------------------------------------

Sustainability
==============

Created by:

<div class="highlight">

Hadley Wickham \[aut, cre\]

</div>

Used for [tidyverse.org](https://tidyverse.org), in particular.

Active development.

------------------------------------------------------------------------

Limitations?
============

-   hugodown is a WIP package

-   Hugo changes a lot (but hugodown helps protect your projects from that)

------------------------------------------------------------------------

Further resources
=================

[Listed on the course website](/hugo/further-resources/) :ledger:

------------------------------------------------------------------------

Questions, comments?
====================

Write them in the pad!

------------------------------------------------------------------------

Time for a break :tea:
======================

<!--html_preserve-->

<div id="timer_5ee3a3da" class="countdown" style="top:100;left:0;" data-warnwhen="0">

<code class="countdown-time"><span class="countdown-digits minutes">05</span><span class="countdown-digits colon">:</span><span class="countdown-digits seconds">00</span></code>

</div>

<!--/html_preserve-->

