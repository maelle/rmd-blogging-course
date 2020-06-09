---
outputs:
- Reveal
title: Another deck
hidden: true
layout: list
weight: 1
reveal_hugo:
  theme: "solarized"
  margin: 0.2
output: hugodown::md_document
rmd_hash: 880f43ee3642a5f7

---

downlit
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

To create a reveal-hugo presentation from the `index.md` file of a leaf page bundle, you need to specify the layout manually.

``` toml
layout = "bundle"
```

------------------------------------------------------------------------

Why? By default, reveal-hugo doesn't create pages for single template types (foo.md), only for list template types (\_index.md).

------------------------------------------------------------------------

This technique can also be used to output an HTML file for any section of a presentation, should you need to.

