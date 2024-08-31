---
layout: page
title: <b>Teleoperated Rescue Robot, ROFA </b>
description: Teleoperated Rescue Robot, ROFA, for Mini Darpa Robotics Challenge (Undergraduate Project, 2015)
img: assets/img/rofa/rofa.jpg
importance: 1
category: work
related_publications: einstein1956investigations, einstein1950meaning
---

<p><b>1. Project Description:</b> Mini Darpa robotics challenge is a robotics competition inspired by the DARPA Robotics Challenge that evaluates robotic capabilities needed in disaster situations. All participants should creatively design and build a robot to complete the mission using only the provided platform, which includes components like a Raspberry Pi, Dynamixel motors, a camera, and other resources supplied by the competition organizers. </p>
<p><b>2. Project Period:</b> May 2015 ~ Oct 2015 </p>
<p><b>3. Team Members:</b> Yitaek Kim, <b>Donghoon Baek</b>, Byungha Kim, Hyeongon Kim </p>
<p><b>4. Advisor: Prof. Juhoon Back
<p><b>5. Required Skills: CAD design (Solidworks), Rasberry Pi (Linux), Serial Communication (RS-485), Motor Control (Dynamixels), C++ </b></p>

ROFA is a teleoperated rescue robot designed for disaster response, capable of tasks like jumping over hurdles, climbing ladders, opening doors, turning valves, and lifting victims. It features two caterpillar wheels and rear legs for traversing uneven terrain, while the front legs lift victims and raise the main body. Powered by a Raspberry Pi as its main controller and Dynamixel motors for actuation. ROFA is remotely operated through a camera feed from the robot’s perspective. 


<div class="row">
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


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/rofa/rofa_map.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/rofa/rofa_function.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    In mini Darpa Robotics Challenge, contest missions include jumping over hurdles, climbing ladders, opening doors, lowering valves, and lifting people down stairs.  
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rofa/rofa.gif" title="Rescue Robot Challenge" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A rescue robot, ROFA, climbed up to the middle height of a ladder using two arms and caterpillar wheels.
</div>

The system, initially operated remotely via Wi-Fi, was highly vulnerable to communication failures at the competition site. We addressed this issue by upgrading to 5G Wi-Fi modules to increase communication bandwidth. Additionally, we attached an extension lens to the camera to compensate for the limited field of view.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/rofa/rofa_award.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Out of the 10 teams that advanced to the finals, we got <b>second prize</b>. Only top three teams were selected to showcase a robot demo at the IEEE Humanoids Conference 2015, held in Seoul, Korea. 
</div>



