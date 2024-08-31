---
layout: page
title: <b> Teleoperated Rescue Robot, ROFA </b>
description: Teleoperated Rescue Robot, ROFA, for Mini Darpa Robotics Challenge (Undergraduate Project, 2015)
img: assets/img/rofa/rofa.jpg
importance: 1
category: work
related_publications: einstein1956investigations, einstein1950meaning
---

<p><b>1. Project Description:</b> Mini Darpa robotics challenge is a robotics competition inspired by the DARPA Robotics Challenge that evaluates robotic capabilities needed in disaster situations. All participants should creatively design and build a robot to complete the mission using only the provided platform, which includes components like a Raspberry Pi, Dynamixel motors, a camera, and other resources supplied by the competition organizers. </p>
<p><b>2. Project Period:</b> May 2015 ~ Oct 2015 </p>
<p><b>3. Team Members:</b> Yitaek Kim, <b>Donghoon Baek</b>, Byungha Kim, Hyeongon Kim </p>
<p><b>4. Advisor: </b> Prof. Juhoon Back </p>
<p><b>5. Required Skills </b>: CAD design (Solidworks), Rasberry Pi (Linux), Serial Communication (RS-485), Motor Control (Dynamixels), C++ </p>

<p><b> Team ROMANSA formed: </b></p>
<p> During my third year of college, we formed Team ROMANSA with like-minded students interested in building and operating real robots. Instead of joining an official club, we created our own team to conduct independent research, re-organizing a long-unused department storage room into our research lab. </p>


<div class="row justify-content-sm-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.html path="assets/img/rofa/office.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    All of our team's journeys started in a messy 'warehouse-like' small room. Our team member: (from left) Hyeongon Kim, me, Byungha Kim, and Yitaek Kim.
</div>


<p><b> ROmansa First Avenger (ROFA) </b></p>
<p> ROFA is a teleoperated rescue robot designed for disaster response, capable of tasks like jumping over hurdles, climbing ladders, opening doors, turning valves, and lifting victims. It features two caterpillar wheels and rear legs for traversing uneven terrain, while the front legs lift victims and raise the main body. Powered by a Raspberry Pi as its main controller and Dynamixel motors for actuation. ROFA operates by remotely connecting to the Raspberry Pi via Wi-Fi. The user assesses the environment through the camera view and controls the robot via teleoperation. ROFA's key feature is its ability to transform into terrain-specific modes to effectively navigate diverse terrains.  </p>


<div class="row justify-content-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rofa/up.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rofa/up2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rofa/down.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Three transformation modes to effectively pass through specific terrain features.
</div>

<p> ROFA can adapt its style to perform different tasks more efficiently, inspired by the movie 'Transformer.' We created a motion library that allows users to switch states via teleoperation. </p>


<div class="row justify-content-sm-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.html path="assets/img/rofa/rofa_map.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    In mini Darpa Robotics Challenge, contest missions include jumping over hurdles, climbing ladders, opening doors, lowering valves, and lifting people down stairs.  
</div>

<p> ROFA can adapt its style to perform different tasks more efficiently, inspired by the movie 'Transformer.' We created a motion library that allows users to switch states via teleoperation. </p>

<div class="row justify-content-center">
    <div class="col-sm-6 mt-3">
        {% include figure.html path="assets/img/rofa/rofa_f1.JPG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3">
        {% include figure.html path="assets/img/rofa/rofa_f4.JPG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3">
        {% include figure.html path="assets/img/rofa/rofa_f3.JPG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3">
        {% include figure.html path="assets/img/rofa/rofa_f2.JPG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


<p> Depending on the terrain, the ROFA can be narrowed down in size or operated while standing up. For safe rescues, the internal structure of the body is designed to unfold using a "hinge" mechanism. This structure, along with two arms, supports the person from the floor, while a cover enhances safety. When climbing a ladder, the caterpillar wheels, arm hooks, and the moment of inertia of the hind legs work together for stability. </p>


<div class="row justify-content-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rofa/rofa1.gif" title="Rescue Robot Challenge" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A rescue robot, ROFA, jumped over the huddles.
</div>

<div class="row justify-content-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rofa/rofa2.gif" title="Rescue Robot Challenge" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A rescue robot, ROFA, climbed up to the middle height of a ladder using two arms and caterpillar wheels.
</div>

The system, initially operated remotely via Wi-Fi, was highly vulnerable to communication failures at the competition site. We addressed this issue by upgrading to 5G Wi-Fi modules to increase communication bandwidth. Additionally, we attached an extension lens to the camera to compensate for the limited field of view.

<div class="row justify-content-sm-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.html path="assets/img/rofa/rofa_award.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Out of the 10 teams that advanced to the finals, we got <b>second prize</b>. Only top three teams were selected to showcase a robot demo at the IEEE Humanoids Conference 2015, held in Seoul, Korea. 
</div>



