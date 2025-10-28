---
layout: page
title: SATYR - An open-source mesh plant monitoring system
description: A diy plant health monitoring and management tool.
img: assets/img/plant-icon.png
importance: 1
category: Personal
giscus_comments: true
---

Satyr was a planned personal project I had worked on for some time. The overall idea was to create 3 main parts: On device firmware for the plant sensors that was open source and extensible to enable customizability. Back end, server code that could be open sourced to enable compatibility with many types of sensors. an intuitive front end, comprised of a mobile client and web app to allow intuitive monitoring, configuration, and maintenance of a user's devices.

Below is a graphic representation of the notional system architecture.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/satyr-system-diagram.png" title="plant icon" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 1: Notional system architecture for the SATYR project.
</div>

With a flexible, open source skeleton, the plan was to also build a robust set of analytics on top of the collected data. Using freely available data for many plant species about their water usage, growth rates, and nutrient intake, a complex picture could be painted of an individual plant being sensed and what might need to be changed to optimize its growth. This has obvious use for personal applications like keeping plants alive in the home, but could easily be extended to enable management of large clusters of plants on a commercial scale like in a plant nursery.

Plans were also made for the development of a more rugged outdoor sensor that might be used in agricultural settings for the management of large crops of plants.



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
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


