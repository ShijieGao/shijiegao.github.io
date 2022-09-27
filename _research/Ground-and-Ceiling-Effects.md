---
title: "Exploiting Ground/Ceiling Effects on UAV Surfaces Detections and Motion Planning"
tease: "enabled"
layout: single-portfolio
excerpt: "<img src='/images/research/Ground-Effect-teaser.png' alt='drawing' width='800px' /> "
collection: research
order_number: 20
brief: 'When a multi-rotor aerial vehicle flies near ground or ceiling, it experiences an increase in lift (a.k.a. ground/ceiling effect). We propose a novel approach that leverages the flow dynamics near surfaces to 
1) sense the environment 
2) perform energy efficient motion plan (save up to 15%)'

---
<style>
    o { color: #ff8e14 }
</style>

<br/>

<img src="/images/research/Ground-Effect.png"
     alt="Markdown Monster icon"
     style="float: top; width = '80%';" />

## Motivation
When an aerial vehicle flies near <o>ground</o> or <o>ceiling</o>, it experiences an increase in lift due to the flow dynamic changes near the surfaces. This <o>lift increase</o> represents a decrease in the thrust required to keep the Unmanned Aerial Vehicle (UAV) aloft and thus a decrease in energy consumption. For example, in agriculture operations, a UAV could fly low to the ground to reduce energy consumption, especially over long distances. In indoor environments, a UAV could fly close to the ceiling, avoiding crowds and objects while also consuming less energy. 

A secondary desired effect is that by monitoring thrust, the UAV can <o>detect</o> the distance to nearby <o>surfaces</o> and <o>prevent collisions</o>. This latter effect is especially beneficial in environments where sensors may not be able to estimate the distance from the ground/ceiling. For example, in a dusty environment like a desert, a conventional camera, sonar, or lidar-based sensor may fail to detect obstacles, which may lead to crashes as a vehicle is landing.

## Goal
- **<o>Characterize</o>** the ground and ceiling effect for quadrotor.
- A framework for quadrotor to **<o>exploit ground and ceiling effects</o>** to **<o>detect</o>** surfaces and create **<o>energy efficient motion planning</o>**.

### More details
If you are interested and want to know more details about this work, you can check [my paper](/files/pdf/publications/Exploiting_Ground_and_Ceiling_Effects_on_Autonomous_UAV_Motion_Planning.pdf) or check my oral presentation [slides](/files/pdf/talks/ICUAS19_presentation_shijie_web.pdf) on ICUAS 2019 below.
<a name="SCM_youtube"></a>

<iframe src="/files/pdf/talks/ICUAS19_presentation_shijie_web.pdf" width="100%" height="500" frameborder="no" border="0" marginwidth="0" marginheight="0"></iframe>


You can find more videos and ROS bag data about this research [here](https://www.bezzorobotics.com/sg-icuas19)