---
layout: page
title: Pick and Place Robot arm for Stacking Application.
description: A simulation of a pick-and-place robot arm using ROS2 and Moveit2.
img: assets/img/pnp_stacking_robot_project/pnp_setup_conv_pallet.png
importance: 2
category: Simulation
---

<!-- Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    --- -->


<div class="row justify-content-center">
    <div class="col-sm-12 col-md-6 mt-3 mt-md-0 text-center">
        {% include figure.html path="assets/img/pnp_stacking_robot_project/pnp_setup_conv_pallet.png" title="conveyor pallet image" class="img-fluid rounded z-depth-1" style="max-width: 100%; width: 500px;" %}
    </div>
</div>

<div class="caption">
    Pick and Place robot arm used for Palletization!
</div>

This was a consultation project I took up in collaboration with <a href="https://www.linkedin.com/in/lentinjoseph/">Mr. Lentin Joseph.</a>, for a stealth startup in Belgium.

The goal of this project was to implement a Pick-and-Place strategy for the robot arm, for palletization of boxes.
My role was to develop the stacking pattern as per customer requirements, and the robot arm should follow the same.
We used Moveit2's  <a href="https://moveit.picknik.ai/humble/doc/tutorials/pick_and_place_with_moveit_task_constructor/pick_and_place_with_moveit_task_constructor.html">Moveit Task Constructor (MTC)</a> for achieving this.
The stacking pattern would depend on the number of boxes per layer to be stacked, size of boxes, and whether they needed to be in a specific orientation.



<div class="row justify-content-center">
    <div class="col-sm-12 col-md-6 mt-3 mt-md-0 text-center">
        {% include figure.html path="assets/img/pnp_stacking_robot_project/4x4_pnp_cropped.gif" title="pnp gif" class="img-fluid rounded z-depth-1" style="max-width: 100%; width: 500px;" %}
    </div>
</div>

<div class="caption">
    Robot performing pick and place in a stacking pattern using MTC!
</div>

You can find the complete video <a href="https://drive.google.com/file/d/1hSX68V6WXo9nTTo0_UU0n5mtZCldMdum/view?usp=sharing">here.</a>


