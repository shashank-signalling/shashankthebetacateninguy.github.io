---
layout: page
title: Mechanisms of IL-10 mediated tumor immune evasion in colorectal cancer development <img width="600" height="248" alt="image" src="https://github.com/user-attachments/assets/f8a1c1dd-3cb6-471c-87d0-f42afd6d3e5e" />
description: #
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

Obesity-induced interleukin-6 (IL-6) shifts macrophage polarisation towards tumour-promoting macrophages that produce the chemokine CC-chemokine-ligand-20 (CCL-20) in the CAC microenvironment. 
  - CCL-20 promotes CAC progression by recruiting CC-chemokine-receptor-6 (CCR-6)-expressing B cells and γδ T cells via chemotaxis. 
  - So we knew that B cells are recruited to the TME, but we do not know whether they are protective or not. Although accumulative evidence suggests a pathological role of B cells in IBD as well as in CRC, causal and mechanistic studies to support this notion are still limited. 
  - To investigate the role of b cells in CRC We used  jht (b cell deficient)  in the aom/dss model of crc. Mice homozygous for the Igh-Jtm1Cgn targeted mutation fail to produce functional B-cells as they lack the gene for the heavy chain joining region. We aimed at investigating the role of B cells in the AOM-DSS model of colitis associated cancer. In this model mice are injected with AOM, which causes DNA alkylation in intestinal epithelia cells. This triggers activation of DNA damage response pathways resulting in DNA repair as well as apoptosis. DSS in the drinking water leads to epithelia barrier damage and subsequently to the development of tumors. 
  - In this model only adenoma. Invasive growth is rarely observed when tumors are induced by AOM in WT mice. We found that B cell deficiency protects mice from AOM/DSS induced CRC. As expected, analysis of the tumor colon showed significantly less immune cells as well as inflammation. Especially, T cells and macrophages were reduced in B cell deficient mice and the secretion of inflammatory cytokines was reduced as well.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
