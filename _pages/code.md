---
layout: page
permalink: /code/
title: Code
description:
contact: true
---


This page contains some mathematical software projects. Most recent code should be available on my [github]({{ 'https://github.com/' | append: site.github_username }}). Much of the code I publish is written in python, but I do use other languages for fun. I taught a [course]({{site.data.links.pycourse.url}}) on python at the [University of Luxembourg]({{site.data.links.Luxembourg.url}}), which some may find useful.

#### [Circle packing convex projective structures]({{site.data.links.circle-pack.url}})
<img class="col half" align="right" src="{{'/assets/img/circle_pack_demo.png' | prepend: site.baseurl | prepend: site.url }}">This little program lets you visualize the image of the developing map of projective tori that admit the specific "square" 2-circle packing. The full parameter space is drawn on the right and the red point indicates your position. The coordinates are two shearing parameters for an associated punctured torus hyperbolic structure. On the right, you can see the holonomy traces and the underlying upper halfp-lane parameter for the conformal structure of the torus.

#### [Horoball necklaces, variety words, and boxes]({{site.data.links.lcv.url}})
<img class="col half" align="right" src="{{'/assets/img/cusp_nbd_arrows.pdf' | prepend: site.baseurl | prepend: site.url }}">This is a visualization program for the maximal horoball neighborhood of a hyperbolic 3-manifold given by a box parameter and a variety word (see **_Hyperbolic 3-manifolds of low cusp volume_**, once available). The github repository for the full project can be found [here]({{site.data.links.momsearch.url}}).

#### [Computing quasiconformal constant for Sullivan's Theorem]({{ site.data.papers.kqc.code | prepend: site.baseurl | prepend: site.url }})
   This code is used in **_A new bound for Sullivan’s Theorem for simply connected domains_** to find a bound on the quasiconformal constant in Sullivan's Theorem.
Requires MATLAB and the Schwarz-Christoffel Toolbox by Toby Driscoll.
