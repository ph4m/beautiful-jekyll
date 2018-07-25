---
layout: post
title: Experimental force-torque dataset for robot learning of multi-shape insertion
subtitle: G. De Magistris, A. Munawar, T.-H. Pham, T. Inoue, P. Vinayavekhin, R. Tachibana, 36th Annual Conference of the Robotics Society of Japan (RSJ), 2018
image: /img/papers/rsj2018.jpg
tags: [research]
---

The accurate modeling of real-world systems and physical interactions is a common challenge towards the resolution of robotics tasks. Machine learning approaches have demonstrated significant results in the modeling of complex systems (e.g., articulated robot structures, cable stretch, fluid dynamics), or to learn robotics tasks (e.g., grasping, reaching) from raw sensor measurements without explicit programming, using reinforcement learn- ing. However, a common bottleneck in machine learning techniques resides in the availability of suitable data. While many vision-based datasets have been released in the recent years, ones involving physical interactions, of particular interest for the robotic community, have been scarcer. In this paper, we present a public dataset on peg-in-hole insertion tasks containing force-torque and pose information for multiple variations of convex-shaped pegs. We demonstrate how this dataset can be used to train a robot to insert polyhedral pegs into holes using only 6-axis force/torque sensor measurements as inputs, as well as other tasks involving contact such as shape recognition.

### Video

[![YouTube](http://img.youtube.com/vi/6rLc9fAtzAQ/0.jpg)](http://www.youtube.com/watch?v=6rLc9fAtzAQ)

### Reference

[[pdf](https://arxiv.org/abs/1807.06749)], [[video](https://www.youtube.com/watch?v=6rLc9fAtzAQ)]

~~~
@inproceedings{rsj:demagistris:2018,
    Author       = {De Magistris, Giovanni and Munawar, Asim and Pham, Tu-Hoa and Inoue, Tadanobu and Vinayavekhin, Phongtharin and Tachibana, Ryuki},
    Title        = {Experimental Force-Torque Dataset for Robot Learning of Multi-Shape Insertion},
    Booktitle    = {36th Annual Conference of the Robotics Society of Japan (RSJ)})},
    Year         = {2018},
    URL = {https://arxiv.org/abs/1807.06749},
    Abstract     =  {The accurate modeling of real-world systems and physical interactions is a common challenge towards the resolution of robotics tasks. Machine learning approaches have demonstrated significant results in the modeling of complex systems (e.g., articulated robot structures, cable stretch, fluid dynamics), or to learn robotics tasks (e.g., grasping, reaching) from raw sensor measurements without explicit programming, using reinforcement learn- ing. However, a common bottleneck in machine learning techniques resides in the availability of suitable data. While many vision-based datasets have been released in the recent years, ones involving physical interactions, of particular interest for the robotic community, have been scarcer. In this paper, we present a public dataset on peg-in-hole insertion tasks containing force-torque and pose information for multiple variations of convex-shaped pegs. We demonstrate how this dataset can be used to train a robot to insert polyhedral pegs into holes using only 6-axis force/torque sensor measurements as inputs, as well as other tasks involving contact such as shape recognition.}
}
~~~
