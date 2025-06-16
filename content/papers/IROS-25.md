---
title: "Least Commitment Planning for the Object Scouting Problem"
date: 2025-06-15
url: "/papers/iros25/"
tags: ["least commitment planning", "object scouting", "LOMDP", "locally observable Markov decision process"]
author: ["Max Merlin", "Ziyi Yang", "George Konidaris", "David Paulius"]
description: ""
summary: "TL;DR -- This paper introduces a new planning framework specifically designed for object scouting with LOMDPs called the Scouting Partial-Order Planner (SPOP), which exploits the characteristics of partial order and regression planning to plan around gaps in knowledge the robot may have about the existence, location, and state of relevant objects in its environment."
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
  + [Workshop Paper](https://openreview.net/forum?id=t3mtZQqwNS) (LEAP Workshop @ CoRL 2024)
  + Complete Paper Coming Soon!
---

#### NOTES

+ This paper introduces the _object scouting problem_: a way of tackling different types of uncertainty (spatial uncertainty and state uncertainty) related to mobile manipulation and long-horizon task execution.
+ The object scouting problem is modelled using the **locally observable Markov decision process (LOMDP)** previously introduced by [Merlin et al. 2024](https://ieeexplore.ieee.org/abstract/document/10610876).
+ We introduce a new planner specifically designed for object scouting known as **SPOP** (scouting partial-order planner).

---

#### Citation

M. Merlin, Z. Yang, G. Konidaris*, and D. Paulius* (2025). "Least Commitment Planning for the Object Scouting Problem". In:
Proceedings of the 2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS).

