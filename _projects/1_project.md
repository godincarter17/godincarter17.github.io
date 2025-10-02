---
layout: page
title: Comparative Analysis of Casini Mission Trajectory
description: Calculated and compared predicted trajectory including frame transformation to propagate the trajectory of the Cassini spacecraft and model it graphically.
img: assets/img/cassini1.png
importance: 1
category: Academic
related_publications: true
---

As part of our capstone design project, my team was tasked with developing a software tool set that would enable the visualization of various aspects of our spacecraft's intended trajectory.
With our goal being to enable our vehicle to closely follow the Martian moon Deimos, our flight path was shaping up to be rather complex. So as a proof of concept, We took it upon ourselves
To develop Matlab based visualization tools to help with mission planning.

As a test case, we decided to take the flight trajectory of the Cassini Huygens spacecraft. Cassini was a complex robotic vehicle that performed an extended science mission among Saturn's family of moons. With a wide array of instrumentation, it was able to capture breathtaking data about the methane seas and ice jets of bodies never before seen. To learn more about the Cassini Huygens mission, follow this [link](https://en.wikipedia.org/wiki/Cassini%E2%80%93Huygens) to Wikipedia.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cassini-insertion.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cassini-destinations.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Artists concept of Cassini's orbit insertion around Saturn, and selected destinations of the mission ordered Largest to Smallest (but not to scale). Both images courtesy of Wikipedia.
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
