---
title: "BROS: the Bi-RObot Setup"
# date: 2021-02-09T21:26:01+01:00
draft: false
ShowBreadCrumbs: false
---

![BROS photo](/img/bros-photo-lowres.png)

During my PhD I studied and modeled how two people perform a task together through physical interaction: by interacting through forces. We were interested in studying human-human interaction to develop better controllers for physical rehabilitation robots. Because we did not have a ready-made robot solution to research physical human-human interaction, we (Koen from [Hankamp Rehab](https://www.hankamprehab.nl/) and I) designed and built our own robotic setup from scratch. The robot setup consists of two identical high-performance robots. Participants held a handle on each robot which that could move in a 2D plane, and each robot could generate forces onto the participant's hand. The robots were controlled by a real-time operating system (EtherCAT and TwinCAT). 

The two robots make up a typical teleoperation setup, through which a person can feel the forces occurring on the other side (like bumping into an object or another person pushing against it). To give you an impression, check out the robots in a compliant teleoperation mode:

![BROS teleoperation](/gif/bros-teleop.gif#center)

We performed multiple experiments on them (for my own Ph.D., but also for student theses), counting over 140 participants working consistently (and they only needed maintenance once) 😃.

If you would like to read more information on the robot's design, capabilities, and technical validation, check out my dissertation [chapter](/bros-chapter-phdthesis-220221.pdf). You can check out the MATLAB/Simulink, TwinCAT project and visualization ([openFrameworks](https://openframeworks.cc/)) code [here](https://github.com/niekbeckers/bi-robot-setup). We will also upload the SolidWorks files to OSF.io soon. 

![And one more](/img/bros-render-overview.png)

We designed BROS to be multi-configurable, usable for different types of scientific experiments, for example for bi-manual experiments (so one robot per hand or arm):

![BROS in bi-manual mode](/img/bros-bimanual.jpg)

Or, the robots can be used to simulate 2D object manipulation between two fingers:

![BROS in bi-finger mode](/img/bros-bifinger.jpg)



