---
layout: post
title: OptLayer - practical constrained optimization for deep reinforcement learning in the real world
subtitle: T.-H. Pham, G. De Magistris, R. Tachibana, IEEE International Conference on Robotics and Automation (ICRA), 2018
image: /img/papers/icra2018-optlayer_cropped.jpg
tags: [research]
---

While deep reinforcement learning techniques have recently produced considerable achievements on many decision-making problems, their use in robotics has largely been limited to simulated worlds or restricted motions, since unconstrained trial-and-error interactions in the real world can have undesirable consequences for the robot or its environment. To overcome such limitations, we propose a novel reinforcement learning architecture, OptLayer, that takes as inputs possibly unsafe actions predicted by a neural network and outputs the closest actions that satisfy chosen constraints. While learning control policies often requires carefully crafted rewards and penalties while exploring the range of possible actions, OptLayer ensures that only safe actions are actually executed and unsafe predictions are penalized during training. We demonstrate the effectiveness of our approach on robot reaching tasks, both simulated and in the real world.

### Video

[![YouTube](http://img.youtube.com/vi/7liBbk3VjWQ/0.jpg)](http://www.youtube.com/watch?v=7liBbk3VjWQ)

### Reference

[[pdf](https://arxiv.org/abs/1709.07643)], [[video](http://www.youtube.com/watch?v=7liBbk3VjWQ)]

~~~
@inproceedings{icra:pham:2018,
    Author       = {Pham, Tu-Hoa and De Magistris, Giovanni and Tachibana, Ryuki},
    Title        = {OptLayer - Practical Constrained Optimization for Deep Reinforcement Learning in the Real World},
    Booktitle    = {Proceedings of the IEEE International Conference on Robotics and Automation ({ICRA})},
    Year         = {2018},
    Organization = {IEEE},
    URL = {https://arxiv.org/abs/1709.07643},
    Abstract     =  {While deep reinforcement learning techniques have recently produced considerable achievements on many decision-making problems, their use in robotics has largely been limited to simulated worlds or restricted motions, since unconstrained trial-and-error interactions in the real world can have undesirable consequences for the robot or its environment. To overcome such limitations, we propose a novel reinforcement learning architecture, OptLayer, that takes as inputs possibly unsafe actions predicted by a neural network and outputs the closest actions that satisfy chosen constraints. While learning control policies often requires carefully crafted rewards and penalties while exploring the range of possible actions, OptLayer ensures that only safe actions are actually executed and unsafe predictions are penalized during training. We demonstrate the effectiveness of our approach on robot reaching tasks, both simulated and in the real world.}
}
~~~
