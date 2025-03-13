---
title: "Perturbation Resilient Central Pattern Generator (PR-CPG) on a Hybrid Bipedal-Wheeled Robot"
excerpt: "Developed PR-CPG algorithm on bio-inspired robot to realize robust and adaptive locomotion control against various external disturbance. <br/>  <img src='https://zhuonan-hao.github.io/Homepage/images/central.png'>   <img src='https://zhuonan-hao.github.io/Homepage/images/Minitaur.jpeg'>"
collection: 
youtubeId1: yMS-1M50nEM
youtubeId2: l8UlMAGnlDI
---

<i class='fas fa-university'></i> Platform: [Gravish Lab](http://gravishlab.ucsd.edu/)   <br>
<i class='fas fa-calendar-alt'></i> Time: Jan. 2020 -- Mar. 2020   <br>
<i class='fas fa-address-book'></i> Advisor: [Prof. Nichlas Gravish](https://scholar.google.com/citations?user=AEWTj-4AAAAJ&hl=zh-CN)

Given that the classical locomotion control through PID controller failed to respond effectively to external disturbance and build connections between legs, we developed a
perturbation resilient algorithm with central pattern generator (CPG) configuration to empower each leg with the ability to modulate locomotion trajectory by local coupling with nearby legs taking account of actual road profile. 

The idea originated from the asymptotic stability of rhythmic neural circuits. By introducing phase-radius coordinate, each single joint could easily sense individual state in the general system and utilized the information to communicate with other actuated jointsthorough phase feedback. When the robot encountered obstacles and the joint angles deviated the designed trajectory, the controller guaranteed the system autonomously converged back to the origin trajectory with a gentle and stable transition instead of a hard manner.

Pertubation resistance demo: 
<br>
<p align="center">
  <img src="https://zhuonan-hao.github.io/Homepage/files/PR.gif?raw=true" alt="Photo" style="width:400px;"/>
</p>

Experiment - leg locomotion without self-organization (no/low coupling case or PID case)
{% include youtubePlayer.html id=page.youtubeId1 %} <br/>

Experiment - leg locomotion with self-organization (strong coupling case)
{% include youtubePlayer.html id=page.youtubeId2 %} <br/>

