---
title: "SkillWrapper: Generative Predicate Invention for Skill Abstraction"
date: 2025-11-30
url: "/papers/skill-wrapper/"
tags: ["abstractions", "planning", "abstractions", "task planning", "predicate invention", "foundation models", "large language models", "LLM", "robot simulation"]
author: ["Ziyi Yang", "Benned Hedegaard", "Ahmad Jaafar", "Yichen Wei", "Skye Thompson", "Shreyas Sundara Raman", "Haotian Fu", "Stefanie Tellex", "George Konidaris", "David Paulius", "Naman Shah"]
description: ""
summary: "TL;DR -- This paper introduces SkillWrapper, a system for creating abstract representations of skills using foundation models."
cover:
    image: "/imgs/skill-wrapper.png"
    alt: "Overview of the SkillWrapper architecture."
    relative: false
editPost:
    URL: "https://yzylmc.github.io/skill-wrapper/"
    Text: "Project Website"
---

#### Related Links:

+ [Website](https://yzylmc.github.io/skill-wrapper/)
+ [GitHub Repository](https://github.com/YzyLmc/skill_wrapper)
+ Paper:
  + [arXiv](https://arxiv.org/abs/2511.18203)
---

#### NOTES:

+ This work introduces **SkillWrapper**: a system for creating abstract representations of skills using foundation models.
  + Unlike related work that assume predefined predicates for skill representations, our system solely relies on a foundation model to propose (or _invent_) predicates.
  + The foundation model also proposes a set of execution traces from which our system actively collects data for deriving skill abstractions.
+ David Paulius and [Naman Shah](https://www.namanshah.net/) are joint final authors (equal advising).

---

#### Citation:

Z. Yang, B. Hedegaard, A. Jaafar, Y. Wei, S. Thompson, S. S. Raman, H. Fu, S. Tellex, G. Konidaris, D. Paulius*, and N. Shah*. "SkillWrapper: Generative Predicate Invention for Skill Abstraction.", arXiv preprint arXiv:2511.18203.
