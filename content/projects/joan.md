---
title: "JOAN: a software framework for human-automated vehicle experiments"
date: 2021-02-09T21:25:55+01:00
draft: false
---

The Human-Robot Interaction group of Cognitive Robotics at TU Delft does a lot of research on interactions between humans and automated vehicles (drivers interacting with their automated car, but also with pedestrians and other road users). We developed a high-fidelity and customizable virtual reality driving simulator that makes performing experiments as easy and repeatable as possible.   

At the core of our virtual driving simulator is [CARLA](http://carla.org/), a driving simulator based on the Unreal game engine developed for autonomous vehicle-related research. One of the reasons why we use CARLA because it has been developed to support the development, training, and validation of autonomous vehicles, and contains a great toolset for machine learning applications. However, CARLA does not yet provide full support for human-in-the-loop experiments, which is why we developed JOAN (an acronym of the developers' first names: Joris, Olger, Andre, and me). 

![JOAN](/img/joan-illustrative-example.png)

JOAN is a Python-based framework to support human-in-the-loop experiments with CARLA. The framework is inspired by DUECA (a software architecture developed at TU Delft to support low-latency, real-time control their flight simulators) and has ROS, but it is simpler to set up and use. Students can program their own experiments easily through JOAN's experiment manager, which handles data logging and any setting the experiment conditions. 

In addition, we developed JOAN to support the use of haptic steering wheels (steering wheels that can generate torques, for example the SENSO Wheel). Researchers can develop their own controllers to optimize the interaction between the driver in iterative design cycles. 

We just released JOAN 2.0. Check out the code on [GitHub](https://github.com/tud-hri/joan) or read more in the [JOAN documentation](https://joan.readthedocs.io).

We made a video explaining JOAN in more detail (including VR goggle support):

{{< youtube xcGXE7rI61s >}}