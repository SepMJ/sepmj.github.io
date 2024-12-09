# MICL @ USTB 

## Abstract

Vision-based autonomous navigation is pivotal in mobile robot technology, involving autonomous movement, path planning, obstacle avoidance, and target reaching in unknown environments. Reinforcement Learning (RL) offers a trial-and-error-driven learning method for autonomous navigation. However, training RL models directly on physical robots is time-intensive and poses potential risks. Simulators accelerate RL training efficiency and reduce costs, but they typically provide only approximate models of robot dynamics and their interactions with the environment. This leads to a simulation-to-reality gap (Sim2Real Gap), where strategies trained in simulation underperform in real-world applications, sometimes resulting in task failures. To address the issue of reducing the Sim2Real Gap in visual sampling training, this paper establishes a bridging plugin between the simulator and ROS, enabling the subscription to interaction data between the ROS-based robot and its real-world environment. We propose a Sim2Real domain adaptation method based on CycleGAN, which generates effective visual observations for autonomous navigation learning. The experimental results demonstrate that this domain adaptation-based method, by utilizing minimal real-world data, significantly reduces the Sim2Real Gap compared to approaches relying solely on simulation data, achieving a performance improvement of 62.38%.

## Contribution #1

![](https://github.com/SepMJ/sepmj.github.io/blob/main/images/sim2real.png)

The framework diagram of the Sim2Real platform.Through the Sim2Real migration platform, we can effectively collect real environment data, such as sensor readings, environment layout, and dynamic elements.

## 

