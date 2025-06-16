---
title: "Bootstrapping Object-level Planning with Large Language Models"
date: 2025-05-20
url: "/papers/olp-icra25/"
tags: ["object-level planning", "task planning", "motion planning", "task and motion planning", "TAMP", "large language models", "LLM", "robot simulation"]
author: ["David Paulius", "Alejandro Agostini", "Benedict Quartey", "George Konidaris"]
description: ""
summary: "TL;DR -- This paper formalizes the concept of object-level planning and discusses how this level of planning naturally integrates with large language models (LLMs)."
cover:
    image: "/imgs/ICRA25_OLP.png"
    alt: "Example of simple block stacking task performed in our LLM-OLP paper"
    relative: false
editPost:
    URL: "https://davidpaulius.github.io/olp_llm/"
    Text: "Project Website"
---

#### Related Links:

+ [Website](https://davidpaulius.github.io/olp_llm/)
+ [GitHub Repository](https://github.com/davidpaulius/olp_llm)
+ Paper:
  + [arXiv (best version)](https://arxiv.org/abs/2409.12262)
---

#### NOTES

+ This paper builds upon our prior work on [FOON-bootstrapped task and motion planning]({{< ref "RAL-23.md" >}}) by naturally interfacing hierarchical planning with large language models (LLMs).
  + Language models are all the rage nowadays and are excellent at doing few-shot learning and deployment.
  + For this reason, we use them to construct [object-level plans]({{< ref "CoRL-WS-22.md" >}}) (in the form of a FOON), thus overcoming the limitation we have encountered before in hand-crafting FOONs from video.
+ We demonstrate how leveraging automated solving with language models enables better performance on table-top block manipulation tasks.

---

#### Citation

D. Paulius, A. Agostini, B. Quartey, G. Konidaris (2025). "Bootstrapping Object-level Planning with Large Language Models". In: *Proceedings of the 2025 IEEE International Conference on Robotics and Automation (ICRA)*. IEEE.

