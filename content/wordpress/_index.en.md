---
title: Advanced
weight: 10
chapter: true
slides: true
output: hugodown::md_document
rmd_hash: d94fd0f768175333

---

Advanced
========

Yay so we can use R Markdown.

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='k'>tibble</span><span>::</span><span class='nf'><a href='https://tibble.tidyverse.org/reference/tibble.html'>tibble</a></span>(a = <span class='nf'>c</span>(<span class='m'>1</span>, <span class='m'>2</span>))
<span class='c'>#&gt; # A tibble: 2 x 1</span>
<span class='c'>#&gt;       a</span>
<span class='c'>#&gt;   &lt;dbl&gt;</span>
<span class='c'>#&gt; 1     1</span>
<span class='c'>#&gt; 2     2</span></code></pre>

</div>

or

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nf'>library</span>(<span class='s'><a href='https://tibble.tidyverse.org/reference'>"tibble"</a></span>)
<span class='nf'><a href='https://tibble.tidyverse.org/reference/tibble.html'>tibble</a></span>(a = <span class='nf'>c</span>(<span class='m'>1</span>, <span class='m'>2</span>))
<span class='c'>#&gt; # A tibble: 2 x 1</span>
<span class='c'>#&gt;       a</span>
<span class='c'>#&gt;   &lt;dbl&gt;</span>
<span class='c'>#&gt; 1     1</span>
<span class='c'>#&gt; 2     2</span></code></pre>

</div>

Chroma no downlit

``` r
tibble::tibble(a = c(1, 2))
```

