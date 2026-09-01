---
title: "Latest News & Timeline"
description: "My Latest Updates"
aliases: /updates/
author: ["David Paulius"]
hideMeta: true
disableAnchoredHeadings: false
---

<b>Note:</b> Check out [this link]({{< ref "./papers/_index.md" >}}) for paper updates!

<style>
/* ── News Tab System ── */
.news-tabs {
    margin-top: 1.5rem;
}

.news-tab-list {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
    margin-bottom: 1.25rem;
    border-bottom: 2px solid var(--border);
    padding-bottom: 10px;
}

.news-tab-btn {
    padding: 6px 16px;
    border: none;
    border-radius: var(--radius);
    cursor: pointer;
    font-size: 14px;
    font-weight: 600;
    font-family: inherit;
    transition: background 0.2s ease, color 0.2s ease, transform 0.1s ease;
    background: var(--tertiary);
    color: var(--primary);
    opacity: 0.55;
}

.news-tab-btn:hover {
    opacity: 0.8;
    transform: translateY(-1px);
}

.news-tab-btn.active {
    opacity: 1;
    transform: translateY(-1px);
    box-shadow: 0 2px 8px rgba(0,0,0,0.12);
}

/* Per-year accent colours that match the existing CSS variables */
.news-tab-btn[data-year="2026"].active { background: var(--2026); }
.news-tab-btn[data-year="2025"].active { background: var(--2025); }
.news-tab-btn[data-year="2024"].active { background: var(--2024); }
.news-tab-btn[data-year="2023"].active { background: var(--2023); }
.news-tab-btn[data-year="2022"].active { background: var(--2022); }
.news-tab-btn[data-year="2021"].active { background: var(--2021); }

.news-tab-panel {
    display: none;
}

.news-tab-panel.active {
    display: block;
    animation: fadeInTab 0.25s ease;
}

@keyframes fadeInTab {
    from { opacity: 0; transform: translateY(6px); }
    to   { opacity: 1; transform: translateY(0); }
}

/* Make the news tables cleaner inside tabs */
.news-tab-panel table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 0 !important;
}

.news-tab-panel table tr td {
    border-bottom: 1px solid var(--border);
    padding: 10px 6px !important;
    vertical-align: top;
}

.news-tab-panel table tr:last-child td {
    border-bottom: none;
}
</style>

<div class="news-tabs">

  <!-- Tab buttons -->
  <div class="news-tab-list" role="tablist" aria-label="News by year">
    <button class="news-tab-btn active" data-year="2026" role="tab" aria-selected="true"  aria-controls="panel-2026" id="tab-2026">2026</button>
    <button class="news-tab-btn"        data-year="2025" role="tab" aria-selected="false" aria-controls="panel-2025" id="tab-2025">2025</button>
    <button class="news-tab-btn"        data-year="2024" role="tab" aria-selected="false" aria-controls="panel-2024" id="tab-2024">2024</button>
    <button class="news-tab-btn"        data-year="2023" role="tab" aria-selected="false" aria-controls="panel-2023" id="tab-2023">2023</button>
    <button class="news-tab-btn"        data-year="2022" role="tab" aria-selected="false" aria-controls="panel-2022" id="tab-2022">2022</button>
    <button class="news-tab-btn"        data-year="2021" role="tab" aria-selected="false" aria-controls="panel-2021" id="tab-2021">2021 &amp; Earlier</button>
  </div>

  <!-- 2026 -->
  <div class="news-tab-panel active" id="panel-2026" role="tabpanel" aria-labelledby="tab-2026">
    <table>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2026)">2026-09-01</span>
            </td>
            <td>
                <span>I am excited to start as a postdoctoral researcher at the <a href="https://www.cse.nd.edu" target="_blank">University of Notre Dame</a>!</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2026)">2026-08-15</span>
            </td>
            <td>
                <span>I am honoured to serve as a Associate Editor for the Humanoids 2026 conference.</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2026)">2026-07-20</span>
            </td>
            <td>
                <span>I am honoured to serve as an organizer for the <a href="https://leap-workshop.github.io/" target="_blank">4th Workshop on Learning Effective Abstractions for Planning (LEAP)</a>, which has been accepted to CoRL 2026!</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2026)">2026-05-20</span>
            </td>
            <td>
                <span>I am honoured to serve as a program committee member for the <a href="https://worldmodelworkshop.github.io/" target="_blank">1st Workshop on Bridging the Gap between Neural and Symbolic World Models for Robot Planning, Reasoning, and Action</a>, which has been accepted to IROS 2026!</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2026)">2026-04-14</span>
            </td>
            <td>
                <span>I gave a guest lecture on <i>Object-level Planning</i> as part of the <a href="https://cs.brown.edu/courses/cs1952d/" target="_blank">Brown University CSCI1952D: Intelligent Robotics</a> course!</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2026)">2026-04-12</span>
            </td>
            <td>
                <span>I am honoured to serve as an Area Chair for <a href="https://www.corl.org/" target="_blank">CoRL (Conference on Robot Learning) 2026</a>.</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2026)">2026-03-09</span>
            </td>
            <td>
                <span> I gave a research talk at the the University of Bristol!</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2026)">2026-01-13</span>
            </td>
            <td>
                <span> I gave a research talk at the <a href="https://cse.nd.edu/events/object-level-planning-bridging-human-knowledge-and-task-and-motion-planning/" target="_blank">University of Notre Dame</a>!</span>
            </td>
        </tr>
    </table>
  </div>

  <!-- 2025 -->
  <div class="news-tab-panel" id="panel-2025" role="tabpanel" aria-labelledby="tab-2025">
    <table>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2025)">2025-12-31</span>
            </td>
            <td>
                <span> I have completed my postdoctoral research at Brown University! 🐻</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2025)">2025-11-18</span>
            </td>
            <td>
                <span> I gave a research talk at Williams College!</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2025)">2025-09-25</span>
            </td>
            <td>
                <span>I am honoured to serve as an Associate Editor for <a href="https://2026.ieee-icra.org/" target="_blank">ICRA (IEEE International Conference on Robotics and Automation) 2026</a>.</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2025)">2025-06-25</span>
            </td>
            <td>
                <span>I attended RSS 2025 in Los Angeles, CA!
                <ul style="margin-bottom:0px">
                    <li><a href="https://dyalab.mines.edu/2025/icra-workshop/16.pdf" target="_blank">SkillWrapper: Autonomously Learning Interpretable Skill Abstractions with Foundation Models</a> was presented at the <a href="https://rss25-roboreps.github.io/" target="_blank">RSS Workshop on Learned Robot Representations (RoboReps)</a>!
                    </li>
                    <li>
                    <a href='{{< ref "./papers/IROS-24.md" >}}"' target="_blank">Lang2LTL-2: Grounding Spatiotemporal Navigation Commands Using Large Language and Vision-Language Models</a> and <a href='{{< ref "./papers/ICRA-25.md" >}}"' target="_blank">Bootstrapping Object-level Planning with Large Language Models</a> were presented at the <a href="https://sites.google.com/brown.edu/fm4roboplan/home?authuser=0" target="_blank">RSS Workshop on Robot Planning in the Era of Foundation Models (FM4RoboPlan)</a>!
                    </li>
                </ul>
                </span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2025)">2025-06-15</span>
            </td>
            <td>
                <span>Our paper entitled <a href='{{< ref "./papers/IROS-25.md" >}}"' target="_blank">Least Commitment Planning for the Object Scouting Problem</a> has been accepted to IROS 2025!
                <ul style="margin-bottom:0px"><li>This paper expands our <a href="https://openreview.net/forum?id=t3mtZQqwNS" target="_blank">workshop paper</a> submitted to the LEAP workshop at CoRL 2024.</li></ul></span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2025)">2025-05-20</span>
            </td>
            <td>
                <span> I attended ICRA 2025 in Atlanta, GA, USA!
                <ul style="margin-bottom:0px">
                    <li>I attended the <a href="https://dyalab.mines.edu/2025/icra-workshop/" target="_blank">ICRA 2025 Workshop on the Language and Semantics of Task and Motion Planning</a>, where we presented our recent work on <a href='{{< ref "./papers/ICRA-25.md" >}}"' target="_blank">language models for object-level planning</a> and <a href="https://dyalab.mines.edu/2025/icra-workshop/16.pdf" target="_blank">SkillWrapper</a>!</li>
                    <li><a href="https://dyalab.mines.edu/2025/icra-workshop/16.pdf" target="_blank">SkillWrapper: Autonomously Learning Interpretable Skill Abstractions with Foundation Models</a> received the <b>Best Poster Award</b> (sponsored by Symbotic Inc.) at the ICRA 2025 TAMP workshop!
                    </li>
                </ul>
                </span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2025)">2025-05-05</span>
            </td>
            <td>
                <span> I gave a research talk at McGill University!</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2025)">2025-04-20</span>
            </td>
            <td>
                <span> I gave a research talk at the University of Illinois Chicago (UIC) and the University of Bristol (UK)!</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2025)">2025-03-21</span>
            </td>
            <td>
                <span> I am honoured to serve as a organizer for the <a href="https://sites.google.com/view/rss2025-reliable-robotics/" target="_blank">1st Workshop on Reliable Robotics: Safety and Security in the Face of GenAI</a>, which has been accepted to RSS 2025!</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2025)">2025-03-15</span>
            </td>
            <td>
                <span>I am honoured to serve as an Area Chair for <a href="https://www.corl.org/" target="_blank">CoRL (Conference on Robot Learning) 2025</a>.</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2025)">2025-01-27</span>
            </td>
            <td>
                <span>Our paper entitled <a href='{{< ref "./papers/ICRA-25.md" >}}"' target="_blank">Bootstrapping Object-level Planning with Large Language Models</a> has been accepted to ICRA 2025!
                <ul style="margin-bottom:0px"><li>This paper will be featured at several upcoming workshops (<a href="https://llmforplanning.github.io/" target="_blank">LM4Plan 2025</a> and <a href="https://aair-lab.github.io/genplan25/" target="_blank">GenPlan 2025</a>).</li></ul></span>
            </td>
        </tr>
    </table>
  </div>

  <!-- 2024 -->
  <div class="news-tab-panel" id="panel-2024" role="tabpanel" aria-labelledby="tab-2024">
    <table>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2024)">2024-11-06</span>
            </td>
            <td>
                <span>I attended CoRL 2024 in Munich, Germany! Das war sehr toll und ich hatte viel Spaß gemacht.<br>A special thank you to everyone who attended and/or contributed submissions to LEAP 2024!</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2024)">2024-09-01</span>
            </td>
            <td>
                <span>Our paper entitled <a href='{{< ref "./papers/IROS-24.md" >}}"' target="_blank">Lang2LTL-2: Grounding Spatiotemporal Navigation Commands Using Large Language and Vision-Language Models</a> has been accepted to IROS 2024!
                <ul style="margin-bottom:0px"><li>This paper will be featured at several upcoming workshops (<a href="https://semrob.github.io/" target="_blank">SemRob 2024</a>, <a href="https://sites.google.com/view/aaai-ur-rad-symposium/home" target="_blank">URAD 2024</a>, <a href="https://leap-workshop.github.io/" target="_blank">LEAP 2024</a>, <a href="https://aair-lab.github.io/genplan25/" target="_blank">GenPlan 2025</a>).</li></ul></span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2024)">2024-08-20</span>
            </td>
            <td>
                <span> The <a href="https://leap-workshop.github.io/" target="_blank">2nd Workshop on Learning Effective Abstractions for Planning (LEAP)</a> has been accepted to CoRL 2024!</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2024)">2024-06-14</span>
            </td>
            <td>
                <span>I gave a research talk at <a href="https://cs.gmu.edu/events/detail/633/" target="_blank">George Mason University</a>.</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2024)">2024-05-13</span>
            </td>
            <td>
                <span>Together with <a href="https://jasmineberry.github.io/" target="_blank">Dr. Jasmine Berry</a>, we authored two position papers, which we presented at the <a href="https://dracothraxus.github.io/responsiblerobotics/index" target="_blank">IROS 2024 Workshop on Responsible Robotics</a>. We won 1st and 2nd place for both submissions!</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2024)">2024-05-13</span>
            </td>
            <td>
                <span>I attended IROS 2024 in Yokohama, Japan! In addition to <a href='{{< ref "./papers/ICRA-24.md" >}}"' target="_blank">CAPE</a>, I presented our paper entitled <a href="https://davidpaulius.github.io/foon-lhpe" target="_blank">Long-Horizon Planning and Execution with FOONs</a>.</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2024)">2024-04-05</span>
            </td>
            <td>
                <span>I served as an Associate Editor for the  <a href="https://2024.ubiquitousrobots.org/" target="_blank">Ubiquitous Robots (UR) 2024</a> conference.</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2024)">2024-03-13</span>
            </td>
            <td>
                <span>I gave a research talk at <a href="https://www.cis.fiu.edu/lectures/object-level-planning-bridging-the-gap-between-human-knowledge-and-task-and-motion-planning/" target="_blank">Florida International University</a>.</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2024)">2024-02-15</span>
            </td>
            <td>
                <span>I gave a research talk at the University of Michigan Robotics Department.</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2024)">2024-01-30</span>
            </td>
            <td>
                <span>Our paper entitled <a href='{{< ref "./papers/ICRA-24.md" >}}"' target="_blank">CAPE: Corrective Actions from Preconditions Errors using Large Language Models</a> has been accepted to ICRA 2024!</span>
            </td>
        </tr>
    </table>
  </div>

  <!-- 2023 -->
  <div class="news-tab-panel" id="panel-2023" role="tabpanel" aria-labelledby="tab-2023">
    <table>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2023)">2023-11-04</span>
            </td>
            <td>
                <span>I attended CoRL 2023 in Atlanta, GA, USA.
                <ul style="margin-bottom:0px"><li>I co-organized the <a href="https://leap-workshop.github.io/leap2023.html" target="_blank">1st Workshop on Learning Effective Abstractions for Planning</a>.</li></ul></span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2023)">2023-10-05</span>
            </td>
            <td>
                <span>I attended IROS 2023 in Detroit, MI, USA. I was a co-author on a submission entitled <a href='{{< ref "./papers/IROS-23.md" >}}' target="_blank">Skill Generalization with Verbs</a>.</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2023)">2023-06-30</span>
            </td>
            <td>
                <span> Our workshop on <a href="https://leap-workshop.github.io/leap2023.html" target="_blank">Learning Effective Abstractions for Planning (LEAP)</a> has been accepted to CoRL 2023!</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2023)">2023-06-13</span>
            </td>
            <td>
                <span>
                    Our paper entitled <a href="https://davidpaulius.github.io/foon-lhpe" target="_blank">Long-Horizon Planning and Execution with FOONs</a> has been accepted to RA-L!
                </span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2023);">2023-05-01</span>
            </td>
            <td>
                <span>
                    I attended the NSF FRR-NRI workshop in Arlington, VA, USA, with a travel award (Aspiring PI)!
                </span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2023)">2023-04-05</span>
            </td>
            <td>
                <span>I served as an Associate Editor for the <a href="http://2023.ubiquitousrobots.org/" target="_blank">Ubiquitous Robots (UR) 2023</a> conference.</span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2023)">2023-01-11</span>
            </td>
            <td>
                <span>
                    I am serving as Social Media &amp; Publicity Chair for the <a href="https://sites.google.com/view/rsspioneers2023/" target="_blank">RSS Pioneers 2023 Workshop</a>! Follow our page <a href="https://twitter.com/RSSPioneers" target="_blank">@RSSPioneers</a> on Twitter for more details!
                </span>
            </td>
        </tr>
    </table>
  </div>

  <!-- 2022 -->
  <div class="news-tab-panel" id="panel-2022" role="tabpanel" aria-labelledby="tab-2022">
    <table>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2022);">2022-12-18</span>
            </td>
            <td>
                <span>
                    I attended CoRL 2022 in Auckland, New Zealand! <ul style="margin-bottom:0px"><li>I gave a presentation on my <a href="https://openreview.net/forum?id=YfjoSxZekWW" target="_blank">position paper about the benefits of object-level planning</a>, at the <a href="https://gjstein.github.io/corl2022wkshp-long-horizon-planning/" target="_blank">CoRL 2022 Workshop on Long-Horizon Planning</a>!</li></ul>
                </span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2022);">2022-07-01</span>
            </td>
            <td>
                <span>
                    I attended RSS 2022, held at Columbia University, NY, USA. <ul style="margin-bottom:0px"><li>I participated in the <a href="https://sites.google.com/view/rsspioneers2022/" target="_blank">RSS Pioneers 2022 Workshop</a>: I was selected as an RSS Pioneer (34.8% acceptance rate)!</li></ul>
                </span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2022)">2022-06-11</span>
            </td>
            <td>
                <span>
                    I attended RLDM 2022, held at Brown University, RI, USA.
                </span>
            </td>
        </tr>
    </table>
  </div>

  <!-- 2021 & Earlier -->
  <div class="news-tab-panel" id="panel-2021" role="tabpanel" aria-labelledby="tab-2021">
    <table>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2021)">2021-11-01</span>
            </td>
            <td>
                <span>
                    I started a new position as Postdoctoral Researcher at Brown University, RI, USA!
                    I am jointly mentored by Profs. George Konidaris and Stefanie Tellex.
                </span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2021)">2021-07-21</span>
            </td>
            <td>
                <span>
                    I served as Lead Volunteer for the <a href="https://humanoids-2020.org/" target="_blank">Humanoids 2020</a> conference!
                </span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2021)">2021-03-21</span>
            </td>
            <td>
                <span>
                    I organized the Advanced Seminar (<i>Hauptseminar</i>) and Project Laboratory (<i>Projektpraktikum</i>) courses during the Summer 2021 semester at TUM!
                </span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2020);">2020-10-01</span>
            </td>
            <td>
                <span>
                    I started a new position as Postdoctoral Researcher at Technical University of Munich (TUM), Germany, as a member of the Human-centered Assistive Robotics (HCR) group.
                </span>
            </td>
        </tr>
        <tr style="vertical-align:top;">
            <td>
                <span class="date" style="background:var(--2020);">2020-05-31</span>
            </td>
            <td>
                <span>
                    I officially graduated from the University of South Florida! I'm <i>#PhDone</i>!
                </span>
            </td>
        </tr>
    </table>
  </div>

</div>

<script>
(function () {
    var btns   = document.querySelectorAll('.news-tab-btn');
    var panels = document.querySelectorAll('.news-tab-panel');

    btns.forEach(function (btn) {
        btn.addEventListener('click', function () {
            var target = btn.getAttribute('aria-controls');

            // Deactivate all
            btns.forEach(function (b) {
                b.classList.remove('active');
                b.setAttribute('aria-selected', 'false');
            });
            panels.forEach(function (p) {
                p.classList.remove('active');
            });

            // Activate clicked
            btn.classList.add('active');
            btn.setAttribute('aria-selected', 'true');
            var panel = document.getElementById(target);
            if (panel) panel.classList.add('active');
        });
    });
})();
</script>
