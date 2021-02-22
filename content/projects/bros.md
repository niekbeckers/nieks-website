---
title: "BROS: the Bi-RObot Setup"
# date: 2021-02-09T21:26:01+01:00
draft: false
ShowBreadCrumbs: false
---

![BROS photo](/img/bros-photo-lowres.png)

During my PhD I studied and modeled how two people perform a task together through physical interaction: by interacting through forces for which I used a robot setup. Together with Koen from [Hankamp Rehab](https://www.hankamprehab.nl/), we designed and built our own robotic setup to perform my experiments. The setup consists of two identical high-performance planar robots, controlled by a real-time operating system (through EtherCAT and TwinCAT). We did multiple experiments on them, with over 140 participants and multiple Master theses 😃.

The robots make up typical teleoperation robots, through which someone can feel the forces occurring on the other side (like bumping into an object or another person pushing against it). To give you an impression, check out the robots in a compliant teleoperation mode:

![BROS teleoperation](/gif/bros-teleop.gif#center)

If you would like to have more information on the robot's design, capabilities, and technical validation, check out the [chapter](/bros-chapter-phdthesis-220221.pdf) I wrote for my thesis. You can check out the MATLAB/Simulink, TwinCAT project and visualization ([openFrameworks](https://openframeworks.cc/)) code [here](https://github.com/niekbeckers/bi-robot-setup). We will also upload the SolidWorks files to OSF.io soon (making the design fully open-source).

![And one more](/img/bros-render-overview.png)

We designed BROS to be multi-configurable, usable for different types of scientific experiments, for example for bi-manual experiments (so one robot per hand or arm):

![BROS in bi-manual mode](/img/bros-bimanual.jpg)

Or, the robots can be used to simulate 2D object manipulation between two fingers:

![BROS in bi-finger mode](/img/bros-bifinger.jpg)



