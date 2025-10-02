---
layout: page
title: Comparative Analysis of Casini Mission Trajectory
description: Calculated and compared predicted trajectory including frame transformation to propagate the trajectory of the Cassini spacecraft and model it graphically.
img: assets/img/cassini1.png
importance: 2
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

The bulk of the work consisted of generating several key plots that would determine things like departure and arrival date, total delta V (and thus fuel expenditure), and others.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/porkchop-plot.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Cassini_interplanet_trajectory.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    1. "Porkchop plot" showing the relationship between departure and arrival dates between Earth and Mars (notional - unreleated to Cassini mission) 2. Plot of Cassini mission trajectory (courtesy of NASA.)
</div>
