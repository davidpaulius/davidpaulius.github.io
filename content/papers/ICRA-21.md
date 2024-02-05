---
title: "Task Planning with a Weighted Functional Object-Oriented Network"
date: 2021-05-01
url: "/papers/foon_cobot/"
tags: ["task planning", "human-robot collaboration","cobots","functional object-oriented networks", "FOON"]
author: ["David Paulius", "Kelvin Sheng Pei Dong", "Yu Sun"]
description: ""
summary: "TL;DR -- In this paper, we attempt to execute task plan sequences extracted from FOONs. However, these sequences may contain actions that are not executable by a robot. Therefore, a human is introduced in the planning and execution loop, and both the robot and human assistant work together to solve the task."
# cover:
#     image: "/1.png"
#     alt: "Rationing and frictional unemployment in the United States, 1964–2009"
#     relative: false
# editPost:
#     URL: "https://davidpaulius.github.io/foon-lhpe/"
#     Text: "Webpage"
---

#### Related Links:

+ Paper:
  + [arXiv (best version)](https://arxiv.org/abs/1905.00502)
  + [IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/9561680/)

---

#### NOTES

+ In this paper, we attempt to execute task plan sequences extracted from FOONs. However, these sequences may contain actions that are not executable by a robot. A human is introduced in the planning and execution loop, and both the robot and human assistant work together to solve the task.
+ This was my first attempt at robot execution directly from a FOON. However, I believe a better solution to this problem lies in [task and motion planning bootstrapped by FOONs]({{< ref "RAL-23.md" >}}). [Hierachical planning]({{< ref "CoRL-WS-22.md" >}}) is the way to go!

---

#### Citation

D. Paulius, K. S. P. Dong, and Y. Sun (2021). "Task Planning with a Weighted Functional Object-Oriented Network". In: *2021 IEEE International Conference on Robotics and Automation (ICRA)* (pp. 3904-3910). IEEE.

