---
title: "Ditto Lab"
author: ["David Paulius"]
showToc: true
disableAnchoredHeadings: false
hideMeta: true
---

As of January 2027, I am an [Assistant Professor](https://engineering.nd.edu/faculty/david-paulius/) in the [Department of Computer Science and Engineering](https://cse.nd.edu/) at the [University of Notre Dame](https://nd.edu/). ☘️ 


I run the Ditto Lab (_**D**avid's **I**ntelligent **T**eam **T**ackling Aut**O**nomy_). This name takes inspiration from [Daphne Koller](https://web.archive.org/web/20250813110254/http://dags.stanford.edu/)'s and [Stephen Bach](https://cs.brown.edu/people/sbach/index.html#bats)'s group names (and [Pokémon]({{< ref "../etcetera/fun.md" >}}) of course). 
We are interested in enabling robots to do general-purpose tasks much like we humans do. <img style='float: right;' src="/imgs/ditto-lab/Spr_2c_Ditto_credits.png" alt="Ditto" title="Ditto" width="30"/>

***More about me***: [[Research Statement]]({{< ref "../research/index.md" >}}) [[Teaching Philosophy]]({{< ref "../teaching/index.md" >}}) [[Diversity Statement]]({{< ref "../diversity/index.md" >}})  


<div style="background-color: #0c2340ee; color: #ffffffff; padding: 15px; border-left: 10px solid #ae9142ff; border-radius: 4px; text-align: center;">
  <strong>NOTE:</strong> I am recruiting PhD students to work with me at Notre Dame in Fall 2027! Please mention my name in your <a href="https://cse.nd.edu/graduate/phd-in-computer-science-and-engineering/" target="_blank">application</a>.<br>Application deadline: <b>*Dec 15, <span id="year"></span><script>
  document.getElementById('year').textContent = new Date().getFullYear();
</script>*</b>
</div>

---

![Picture of Robotics@ND in front of the Golden Dome at Notre Dame](/imgs/ditto-lab/robotics_nd.jpg)
<p style="text-align: center;"><i>Pictured above: Group Photo of <a href="https://robotics.nd.edu/people/" target="_blank">Robotics@ND</a> faculty and students (some professors missing, taken in Fall 2026)</i></p>

---

## Research Interests 🔍

My lab focuses on the use and applications of AI methods for general-purpose robotics. Rather than building robots (like my [colleagues](https://robotics.nd.edu/people/) in other departments), we use commercially available robots (robot arms, humanoids, etc.) as platforms to test and evaluate our methods. Robotics is an exciting field for realizing _embodied AI_, as we focus on how artificially intelligent agents can perceive and interact with the physical world.

**Lab Mission:** To develop robots that can reason about their actions and the world around them while leveraging commonsense knowledge from text, images, and other modalities, as well as from prior experiences (now typically captured by [world models](https://en.wikipedia.org/wiki/World_model_(artificial_intelligence)) and [foundation models](https://en.wikipedia.org/wiki/Foundation_model)). Please see my [research statement]({{< ref "../research/index.md" >}}) for a brief overview of my research philosophy and long-term goals, and check out my [Google Scholar](https://scholar.google.com/citations?user=aMxXkWkAAAAJ&hl=en) for my papers.

<div style="background-color: var(--code-bg); color: var(--primary); padding: 15px; border-radius: 15px;">

Our research explores the following themes (<i>click each to expand</i>).

<details><summary style="cursor: pointer;"><em><b>Planning:</b></em> task and motion planning (TAMP), object-level planning, world models, foundation models, agentic AI for robotics.</summary>

<br>

<div style="background-color: var(--box-fill); padding: 10px; padding-left: 0px; padding-right: 40px; border-left: 10px solid var(--box-accent); border-radius: 4px;">

- How do we _formulate_ an instance of a planning problem often in the context of _hierarchical planning_—for instance, from [object-level to task- and motion-level planning]({{< ref "../papers/CoRL-WS-22.md" >}})?
- What _abstractions_ are useful when formulating such problems?
- What are essential components of a _world model_? How can we leverage image-based world models for imagining the consequences of actions or future states?
- How can we _bridge_ symbolic and latent structures?
- How can we make TAMP more _accessible_ (i.e., easy to use, reliable, and portable)?

</div>

</details> 
<br>
<details><summary style="cursor: pointer;"><em><b>Acting:</b></em> robot learning for skills (machine learning, foundation models, vision-language-action (VLA) models), parameterized skills, generalization, (inter)active perception, language grounding.</summary>

<br>

<div style="background-color: var(--box-fill); padding: 10px; padding-left: 0px; padding-right: 40px; border-left: 10px solid var(--box-accent); border-radius: 4px;">

Some core questions to think about:
- Given a plan (whether detailed or abstract), how does a robot execute and solve it with its skills?
- How can the robot _adapt_ when things go wrong (if skills fail, objects are missing, or the environment changes)?
- Where do robot skills come from? Are they _agent-designed_, _learned from demonstration and captured by machine learning models_, or _pre-programmed action primitives_?
- How can we specify or identify the characteristics of skills from the context of [_Markov decision processes_](https://en.wikipedia.org/wiki/Markov_decision_process) (MDPs) or higher-level [options](https://www.sciencedirect.com/science/article/pii/S0004370299000521)? For example, what are the initiation set (_preconditions_) and termination conditions (_effects/post-conditions_) of a skill?
- How can we use _existing_ policies or skills to learn more complex behaviours never seen before? How can we use knowledge from foundation models as a curriculum or scaffolding to do this?
- How can we leverage off-the-shelf models for _interactive perception_?

</div>

</details> 
<br>
<details><summary style="cursor: pointer;"><em><b>Interfaces and Applications:</b></em> human-robot collaboration (HRC), human-robot interaction (HRI), domestic robots, assistive robotics, human-in-the-loop (HITL), AI for Science, explainable AI (XAI).</summary>

<br>

<div style="background-color: var(--box-fill); padding: 10px; padding-left: 0px; padding-right: 40px; border-left: 10px solid var(--box-accent); border-radius: 4px;">

- How can robots _interact or collaborate with humans_? 
- How can hierarchical planning frameworks be adapted to different domains, such as our homes, labs, or in the wild?
- What roles can human _feedback_, _preferences_, and _values_ play in hierarchical planning and acting? How can we best communicate the robot's capabilities and limitations to humans?
- How can we realize the vision of an [autonomous generalist scientist](https://arxiv.org/abs/2503.22444) from the robotics perspective?

</div>

</details> 

</div>
<br>


If any of these things sound interesting to you, please continue reading to learn more about joining the lab!

---

## Joining the Lab 🦾

**Prospective PhD Students:** Note the following instructions.
1. Apply directly to the [Notre Dame PhD program](https://cse.nd.edu/graduate/phd-in-computer-science-and-engineering/). Please mention my name (David Paulius) as a potential advisor in your application.
2. Do note that the application deadline is December 15, and make sure you apply to CSE (Computer Science and Engineering).
3. _Optionally, only after submitting your application_, you may email me a CV and a brief description of your research interests. _Please also mention any papers I may have (co-)authored that you find interesting and any papers you may have written that connect to these ideas_. 
   - To signal that you've read this entire page and that you are serious about working with me, please include a frog emoji (🐸) in your email. 

**Prospective Postdoctoral Researchers:**
I currently do not have funding for postdocs. _HOWEVER_, Notre Dame offers fellowships that you may be eligible for, such as the [Provost's Postdoctoral Fellowship in Engineering](https://postdoc.nd.edu/fellowships/president-postdoctoral-fellowship/). If you apply for this fellowship, please contact me, as you must identify me as a primary mentor. I will do my best to help you with your application! 🫡

**BSc/MS Students at Notre Dame:**
I highly recommend first taking one of my courses if you want to learn about my research interests! Feel free to reach out via email with your CV and a short note about which part of our work interests you.

**BSc/MS Students outside of Notre Dame:**
Opportunities such as [E-SURE](https://academicweb.nd.edu/~skumar5/resources/Summer-Reu-Page/SummerEngineeringREU.html?utm_campaign=redirect&utm_medium=web&utm_source=www3.nd.edu) and [i-SURE](https://ndi-sa.nd.edu/_portal/tds-program-brochure?programid=10096) may be available to you! Read more [here](https://engineering.nd.edu/student-experience/undergraduate-student-experience/research-experiences-for-undergraduates/).