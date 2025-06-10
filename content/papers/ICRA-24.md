---
title: "CAPE: Corrective Actions from Precondition Errors using Large Language Models"
date: 2024-01-01
url: "/papers/cape/"
tags: ["task planning", "large language models","LLM","re-planning", "few-shot planning"]
author: ["Shreyas Sundara Raman", "Vanya Cohen", "Ifrah Idrees", "Eric Rosen", "Ray Mooney", "Stefanie Tellex", "David Paulius"]
description: ""
summary: "TL;DR -- In this paper, we introduce CAPE: an approach to correct errors encountered during robot plan execution. We exploit the ability of large language models to generate high-level plans and to reason about causes of errors."
cover:
    image: "/imgs/ICRA24_CAPE_process.png"
    alt: "Rationing and frictional unemployment in the United States, 1964–2009"
    relative: false
# editPost:
#     URL: "https://davidpaulius.github.io/foon-lhpe/"
#     Text: "Webpage"
---

#### Related Links:

+ [Webpage with Supplementary Materials](https://shreyas-s-raman.github.io/CAPE/)
+ Paper:
  + [arXiv (best version)](https://arxiv.org/abs/2211.09935)
  + [Previous version (FMDM @ NeurIPS 2022)](https://openreview.net/forum?id=cMDMRBe1TKs)

---

#### NOTES

+ In this paper, we introduce CAPE: an approach to address errors encountered by a robot or agent when executing a plan.
  + We use large language models (LLM) to perform planning and to infer the causes of errors.
  + We assume that these errors lie in preconditions that are not being met by the agent.
  + This work builds upon a [submission made to the NeurIPS 2022 Workshop on Foundation Models for Decision Making](https://openreview.net/forum?id=cMDMRBe1TKs).
+ We showcase our method in simulation (AI2THOR) and with a real robot (Boston Dynamics Spot quadruped robot).
+ This paper is to appear at ICRA 2024!

---

#### Citation

S. Sundara Raman, V. Cohen, I. Idrees, E. Rosen, R. Mooney, S. Tellex, and D. Paulius (2024). "CAPE: Corrective Actions from Precondition Errors using Large Language Models". In: *2024 IEEE International Conference on Robotics and Automation (ICRA)*. IEEE.

