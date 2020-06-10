---
outputs:
- Reveal
title: distill
hidden: true
layout: list
weight: 1
output: hugodown::md_document
rmd_hash: 38367cbccccd8d4f

---

Distill
=======

------------------------------------------------------------------------

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nf'>library</span>(<span class='s'><a href='https://rdrr.io/pkg/magick/man'>"magick"</a></span>)
<span class='c'>#&gt; Linking to ImageMagick 6.9.7.4</span>
<span class='c'>#&gt; Enabled features: fontconfig, freetype, fftw, lcms, pango, x11</span>
<span class='c'>#&gt; Disabled features: cairo, ghostscript, rsvg, webp</span>
<span class='nf'><a href='https://rdrr.io/pkg/magick/man/options.html'>channel_types</a></span>()
<span class='c'>#&gt;  [1] "Undefined"  "A"          "All"        "Alpha"      "B"         </span>
<span class='c'>#&gt;  [6] "Black"      "Blue"       "C"          "Cyan"       "Default"   </span>
<span class='c'>#&gt; [11] "G"          "Gray"       "Green"      "H"          "Hue"       </span>
<span class='c'>#&gt; [16] "Index"      "K"          "L"          "Lightness"  "Luminance" </span>
<span class='c'>#&gt; [21] "Luminosity" "Magenta"    "Matte"      "M"          "O"         </span>
<span class='c'>#&gt; [26] "Opacity"    "Red"        "R"          "Saturation" "S"         </span>
<span class='c'>#&gt; [31] "Sync"       "Y"          "Yellow"     "0"          "1"         </span>
<span class='c'>#&gt; [36] "2"          "3"          "4"          "5"</span></code></pre>

</div>

``` r
library("magick")
channel_types()
```

------------------------------------------------------------------------

[Distill](rstudio.github.io/distill/) is a nice framework and R package.

