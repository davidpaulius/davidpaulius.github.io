---
title: "[IROS-24] Lang2LTL-2: Grounding Spatiotemporal Navigation Commands Using Large Language and Vision-Language Models "
date: 2024-09-01
url: "/papers/IROS24_spatiotemp/"
tags: ["linear temporal logic", "LTL", "spatiotemporal grounding", "natural language", "foundation models", "vision-language models", "VLM", "large language models", "LLM", "word embedding", "language grounding", "grounding"]
author: ["Jason Xinyu Liu", "Ankit Shah", "George Konidaris", "Stefanie Tellex", "David Paulius"]
description: "IROS-24"
summary: "TL;DR -- Building on prior work (Lang2LTL - CoRL 2023), this paper introduces a modular system that enables robots to follow natural language commands with spatiotemporal referring expressions. This system leverages multi-modal foundation models as well as linear temporal logic."
cover:
    image: "/imgs/IROS24_overview.png"
    alt: "Overview of Lang2LTL-2 system"
    relative: false
---

##### Related Links:

+ [Website](https://spatiotemporal-ground.github.io/)
+ [Lang2LTL ver. 1](https://lang2ltl.github.io/) (CoRL 2023)

---

#### NOTES:

+ This work extends [Lang2LTL](https://lang2ltl.github.io/): a modular system that leverages language models for grounding concepts or referrents in natural language commands to a formal logic known as [linear temporal logic](https://en.wikipedia.org/wiki/Linear_temporal_logic) (LTL).
    + Lang2LTL version 1 [(Liu and Yang et al. 2023)](https://arxiv.org/abs/2302.11649) only worked on grounding commands with _temporal_ constraints.
    + Lang2LTL version 2 (i.e., this paper) added the capability of grounding spatiotemporal commands, where there may be reasoning required to understand spatial relations between referrents while also accounting for temporal ordering constraints.
+ Our system combines the modalities of text and images to perform language grounding.
+ We perform experiments in both simulated and real-robot experiments (see videos on our [website](https://spatiotemporal-ground.github.io/)).

---

#### Citation:

J. X. Liu, A. Shah, G. Konidaris, S. Tellex, and D. Paulius (2024). "Lang2LTL-2: Grounding Spatiotemporal Navigation Commands Using Large Language and Vision-Language Models". In: *Proceedings of the 2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*.