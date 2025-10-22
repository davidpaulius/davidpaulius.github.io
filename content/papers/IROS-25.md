---
title: "[IROS-25] Least Commitment Planning for the Object Scouting Problem"
date: 2025-10-19
url: "/papers/iros25/"
tags: ["least commitment planning", "object scouting", "LOMDP", "locally observable Markov decision process", "robot simulation"]
author: ["Max Merlin", "Ziyi Yang", "George Konidaris", "David Paulius"]
description: ""
summary: "TL;DR -- This paper introduces a new planning framework for object scouting called the Scouting Partial-Order Planner, which exploits partial order and regression planning to plan around gaps in knowledge the robot may have about the existence, location, and state of relevant objects in its environment."
#cover:
#    image: "/imgs/ICRA25_OLP.png"
#    alt: "Example of simple block stacking task performed in our LLM-OLP paper"
#    relative: false
# editPost:
#     URL: "https://davidpaulius.github.io/foon-lhpe/"
#     Text: "Webpage"
---

#### Related Links:

+ Paper:
  + [Workshop Paper](https://openreview.net/forum?id=t3mtZQqwNS) (Work-in-Progress Paper presented at LEAP Workshop (CoRL 2024))
  + [Paper](http://irl.cs.brown.edu/pubs/scouting_pop.pdf)
---

#### NOTES:

+ David Paulius and [George Konidaris](https://cs.brown.edu/~gdk/) are joint last authors (equal advising).
+ This paper introduces the _object scouting problem_: a way of tackling different types of uncertainty (_spatial uncertainty_ and _state uncertainty_) related to mobile manipulation and long-horizon task execution.
+ The object scouting problem is modelled using the **locally observable Markov decision process (LOMDP)** previously introduced by [Merlin et al. 2024](https://ieeexplore.ieee.org/abstract/document/10610876).
+ We introduce a new planner specifically designed for object scouting known as **SPOP** (scouting partial-order planner), which is based on the idea of least commitment planning by [Weld 1994](https://ojs.aaai.org/aimagazine/index.php/aimagazine/article/view/1109).
+ We show how this planner is better suited for planning to find task-relevant objects and resolve the plans to incorporate these objects than the previous LOMDP planner.
  + These are specifically highlighted in the AI2THOR simulator environment.


---

#### Citation:

M. Merlin, Z. Yang, G. Konidaris*, and D. Paulius* (2025). "Least Commitment Planning for the Object Scouting Problem". In: *Proceedings of the 2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*, pgs. 21004-21010, IEEE.

