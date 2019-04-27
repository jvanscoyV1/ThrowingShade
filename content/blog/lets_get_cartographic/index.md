---
title: Let's Get Cartographic
date: '2019-03-19T18:57:03.284Z'
subtitle: 
---

I've implemented a simple procedural texture!

My CheckerboxMaterial class stores two materials and a box size value.

When a ray intersects a 3D shape wearing the CheckerboxMaterial, the shape must provide the material with the corresponding 2D texture coordinates (u, v) normalized between -1 and 1. 




<div class="img_w_caption">

The coordinates are divided by the given box size to get a row / column of the texture map. Then, using a simple variable logical statement (in this case: checking whether the row and column are odd or even) we can decide which material the intersected point should have assigned.

![mapping checkerbox](./texture_mapping.PNG)


(photo from Joe Geigel's CSCI-711 "Global Illumination" slides on texture mapping)

</div>


<div class="img_w_caption">

Here is a screen shot of my system's implementation:

![procedural texture shot](./s_shot_5.png)

</div>

<div class="img_w_caption">

And here is a neat little GIF of my system in motion:

![animation](./out.gif)

</div>