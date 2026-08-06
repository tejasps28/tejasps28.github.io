---
layout: page
title: Getting Started with ROS
description: A turtlesim project that draws shapes.
img: assets/img/turtlesim_shapes_project/turtle_shapes.gif
importance: 2
category: Learnings
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
        {% include figure.html path="assets/img/turtlesim_shapes_project/turtle_shapes.gif" title="turtle image" class="img-fluid rounded z-depth-1" style="max-width: 100%; width: 500px;" %}
    </div>
</div>

<div class="caption">
    Turtle draws shapes.!
</div>

This project was one of my very first ones, when I started learning ROS! 

Did this project to learn core concepts about ROS topics, ROS services etc., and what better playground to do so than the turtlesim!
This project helped me learn about writing clean code in C++ using ROS.
Basically, I wrote a ROS node which hosts a service, and based on the integer input it will draw either a square, circle, or triangle.


You can find more details <a href="https://github.com/tejasps28/Projects/tree/main/TurtleSim_Projects/turtle_shapes">here.</a>
