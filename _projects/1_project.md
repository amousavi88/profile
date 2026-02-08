---
layout: page
title: ULF Waves in the Ion Foreshock
description: Effect of 3D Morphology
img: assets/img/foreshock.png
importance: 1
category: work
related_publications: true
---

ion beams reflected from the Earth’s bow shock are a key driver of ultra-low frequency (ULF) waves in the ion foreshock, influencing particle acceleration and shock dynamics. Velocity dispersion of ion beams—as they propagate away from the bow shock—is observed in both spacecraft data and simulations. Two-dimensional (2D) global hybrid simulations capture the evolution of ion beam properties, including beam density and velocity profiles, but the role of three-dimensional (3D) geometry in shaping this evolution remains less explored. These simulations also reveal that ULF waves form discrete domains, where reduced scattering occurs at domain boundaries, influencing beam structure. However, it is not yet understood how the inclusion of a fully three-dimensional (3D) geometry modifies either the beam evolution or its interaction with ULF waves.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-6 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/B_tseries_LPF_x=1000.0_y=1500.0.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
#    <div class="col-sm mt-3 mt-md-0">
#        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
#    </div>
    <div class="col-sm mt-6 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/LIC.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bz3dvolume.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    3D Global Hybrid Simulations
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/bz1103d_slices.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/H3d_dispertions.png" title="example image" class="img-fluid rounded z-depth-1" %}
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
