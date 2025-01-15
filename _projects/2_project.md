---
layout: page
title: Unity Simulation as a test bench for Robotics.
description: A unity based simulation for 2D-SLAM algorithms.
img: assets/img/unity_2d_project/unity2D.gif
importance: 3
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
        {% include figure.html path="assets/img/unity_2d_project/unity2D.gif" title="example image" class="img-fluid rounded z-depth-1" style="max-width: 100%; width: 500px;" %}
    </div>
</div>

<div class="caption">
    Unity 2D robot navigating in the playground!
</div>

While getting started with ROS, one might generally feel that there is a steep learning curve. For one to feel a little less overwhelmed, I have come up with this project.

The goal of this project is simple- Letting beginners play around with 2D SLAM algorithms and follow tutorials.
This project is a Unity based Simulation for a Differential Drive robot. This robot exposes topics like /cmd_vel, /odom, "tf" and 2D laser data.
And it is simple to use, just like a game. You double click on the game icon, run the launch files and voila!

For detailed explanation, checkout this <a href="https://github.com/tejasps28/Projects/tree/main/DiffBot_unitysim/Diffbot_2D">github repo.</a>

You can find the complete video <a href="https://drive.google.com/file/d/1Z67XVMsaffZgdrze6bd88lU2CNs8NRmZ/view?usp=drive_link">here.</a>
