---
layout: page
title: Gantry Robot Arm for Car-Painting application in ROS2
description: A simulation of a gantry robot-arm for car painting using ROS2,Gazebo and Moveit2.
img: assets/img/gantry_project/gantry_gif.gif
importance: 1
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
        {% include figure.html path="assets/img/gantry_project/gantry_gif.gif" title="example image" class="img-fluid rounded z-depth-1" style="max-width: 100%; width: 500px;" %}
    </div>
</div>

<div class="caption">
    Car Painting in action.!
</div>

This project was done in collaboration with <a href="https://www.linkedin.com/in/lentinjoseph/">Mr. Lentin Joseph.</a>   
In this project we have explored how to automate the car painting process using a gantry design and robot arm manipulator.

Firstly, we set up a multi-camera system to surround the car , to cover maxiumum angles of the car.
The purpose of this is, to get a 3D reconstructed version of the car, in only pointcloud format.

We use this pointclouds to then create an octomap, for the arm to avoid collision with the car,
while painting. Using the images from the camera, we segment out the parts that are to be painted.
Then using openCV and PCL libraries, we compute the pose from points that are overlapping on the segmented
image, and it's corresponding depth from the pointcloud.
Using Moveit2 ROS API, we use these poses to compute Cartesian motion plan.

You can find the complete video <a href="https://drive.google.com/file/d/1jfwVAd0tfL2s9PvaNSDgQvgnOZTc--cP/view?usp=sharing">here.</a>


