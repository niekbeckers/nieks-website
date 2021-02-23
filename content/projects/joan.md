---
title: "JOAN: a framework for human-automated vehicle experiments"
date: 2021-02-09T21:25:55+01:00
draft: false
---

The Human-Robot Interaction group of Cognitive Robotics at TU Delft does a lot of research on interactions between humans and automated vehicles (drivers, but also pedestrians and other road users). In order to facilitate this research, we need a high-fidelity and customizable virtual reality driving simulator.  

At the core of our virtual driving simulator is [CARLA](http://carla.org/), a driving simulator based on the Unreal gaming engine developed for autonomous vehicle-related research CARLA has been developed to support the development, training, and validation of autonomous vehicles, and contains a massive toolset for machine learning applications. Although CARLA is great, we were missing thorough support for human-in-the-loop experiments. That is why we developed JOAN (an acronym of the developer's first names). 

![JOAN](/img/joan-illustrative-example.png)

JOAN is a Python-based framework to support human-in-the-loop experiments in CARLA. The framework is inspired by DUECA (a software architecture developed at TU Delft to support low-latency, real-time control their flight simulators) and has ROS, but it is simpler to set up and use. Students can program their own experiments easily through JOAN's experiment manager, which handles data logging and any relevant conditions that need to be set during the experiment. In addition, we developed JOAN to support the use of haptic steering wheels (steering wheels that can generate torques, for example the SENSO Wheel); researchers can develop their own controllers and test them relatively quickly. To make developing with JOAN simple, we used Python (at the cost of very-soft real-time control of the steering wheel). 

JOAN is developed by a Joris, Andre, Olger and me, and we just released JOAN 2.0. Check the code on [GitHub](https://github.com/tud-hri/joan), or read more in the [JOAN documentation](https://joan.readthedocs.io).

We made a video explaining JOAN in more detail (including the VR goggle support):

{{< youtube xcGXE7rI61s >}}