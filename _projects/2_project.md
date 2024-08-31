---
layout: page
title: <b> Teleoperated Rescue Robot, ROSA </b>
description: Teleoperated Rescue Robot, ROSA, for RoboCup Rescue robot league (Undergraduate Project, 2016)
img: assets/img/rosa/rosa.jpg
importance: 1
category: work
related_publications: einstein1956investigations, einstein1950meaning
---

<p><b>1. Project Description:</b> RoboCup Rescue Robot Challenge aims to create autonomous and semi-autonomous robots capable of assisting in disaster response and rescue missions. The challenge emphasizes real-world scenarios where robots can help locate and rescue victims, assess damage, and navigate hazardous environments. </p>

<p>For more details about a RoboCup Rescue Robot Challenge, visit: <a href="https://www.nist.gov/el/intelligent-systems-division-73500/robocuprescue-league-2016">Link to competition</a></p>

<p><b>2. Project Period:</b> 2016.01 ~ 2016.07 </p>
<p><b>3. Team Members:</b> <b>Donghoon Baek</b>, Yitaek Kim, Hansoul Kim, SuYeon Lee, Hyeongon Kim, Hyeonseok Lee, Taemin Hwang </p>
<p><b>4. Advisor: </b> Prof. Juhoon Back and Prof. Hwang Jo</p>
<p><b>5. My Role: </b> I was primarily responsible for 1) designing and controlling the 6-DOF manipulator, 2) controlling the four legs equipped with caterpillar tracks, and 3) developing the GUI for motor control. After RoboCup, I took on the role of team leader, guiding the team to participate in the IT Challenge at Kwangwoon University and submit an academic paper to the Korea domestic conference (KROC2017). Luckily, we got the best paper award at the academic conference. </p>

<p><b>6. New Members are joined to Team ROMANSA: </b></p>


<div class="row justify-content-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rosa/romansa1.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rosa/romansa2.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    (From left) Hansoul Kim, Hyeonseok Lee, <b>Donghoon Baek</b>, SuYeon Lee, Hyeongon Kim, Taemin Hwang, and Yitaek Kim. 
</div>

<p><b> ROmansa Second Avenger (ROSA) </b></p>
<p> We developed ROSA, an advanced version of the teleoperated rescue robot ROFA (see another project). ROSA features two main caterpillar tracks on its body and four additional tracks on its legs for enhanced mobility. It includes a 6-DOF manipulator, CO2 sensors, IMU, a microphone, and an onboard laptop PC that can be accessed via Wi-Fi for teleoperation. A custom, user-friendly graphical interface was developed to facilitate remote control of the robot. </p>


<div class="row justify-content-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rosa/rosa.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rosa/rosa2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    ROFA (left) is designed to explore harsh terrain and assist in rescuing victims. Its small size allows it to navigate rescue areas, map the environment, and gather critical information.
</div>

<div class="row justify-content-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rosa/maindriving.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rosa/stabilizer.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    ROSA features four modular caterpillar wheels, allowing it to flexibly adjust its body size. A small size ROSA can stabilize its radar sensor. 
</div>

<div class="row justify-content-center">
    <div class="col-sm mt-5 mt-md-0 text-center">
        {% include figure.html path="assets/img/rosa/driving_whole.gif" title="ROSA driving capability test" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption text-center">
    The rescue robot ROSA can climb stairs and traverse uneven terrain.
</div>


<div class="row justify-content-center">
    <div class="col-sm mt-8 mt-md-0 text-center">
        {% include figure.html path="assets/img/rosa/manipulator.gif" title="ROSA driving capability test" class="img-fluid rounded z-depth-1 mx-auto d-block" %}
    </div>
</div>
<div class="caption text-center">
    The rescue robot ROSA can push a button, rotate lib, and open a door. To enable more intuitive control of the manipulator, we implemented numerical inverse kinematics, allowing the manipulator to track the desired task-space reference.   
</div>



<div class="row justify-content-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rosa/gui.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rosa/system_architecture.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rosa/teleop.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    We developed a user-friendly GUI for easy robot operation and real-time monitoring of key data. The system flow is shown in the figure on the right. ROSA is fully controlled through remote teleoperation.
</div>


<div class="row justify-content-center">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.html path="assets/img/rosa/vision.gif" title="ROSA driving capability test" class="img-fluid rounded z-depth-1 mx-auto d-block" %}
    </div>
</div>
<div class="caption">
    A small ROSA is capable of recognizing human faces, intended for identifying victims.
</div>

<div class="row justify-content-center">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.html path="assets/img/rosa/slam.gif" title="ROSA driving capability test" class="img-fluid rounded z-depth-1 mx-auto d-block" %}
    </div>
</div>
<div class="caption">
    We developed a SLAM function to generate real-time maps of unknown environments by customizing ROS1's open-source SLAM package..
</div>



<div class="row justify-content-center">
    <div class="col-sm-6 mt-3">
        {% include figure.html path="assets/img/rosa/poster.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    I had the opportunity to explain our robot, ROSA, to the University President in the IT competition at Kwangwoon University, South Korea.
</div>

<div class="row justify-content-center">
    <div class="col-sm-6 mt-3">
        {% include figure.html path="assets/img/rosa/quix.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The poster we made to show all functions of ROSA.
</div>



<div class="row justify-content-center">
    <div class="col-sm-6 mt-3">
        {% include figure.html path="assets/img/rosa/robocup.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3">
        {% include figure.html path="assets/img/rosa/romansa.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3">
        {% include figure.html path="assets/img/rosa/travel.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3">
        {% include figure.html path="assets/img/rosa/othersrobot.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
In RoboCup, we were the only team composed entirely of undergraduate students, competing against teams with graduate-level or higher members. Lacking financial resources to build a robot, we visited schools, professors, and companies to borrow expensive equipment like motors and drivers. Despite these challenges, we placed 11th out of 24 teams in the finals and won the Best Student Paper Award at a domestic robotics academic conference in Korea.
</div>