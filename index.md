---
layout: page
title: "About Me"
permalink: /
---
<br>
 <table style="width:100%">
  <tr>
    <td><img src="images/Michael_Lutter_circle.png" alt="drawing" width="350"/></td>
    <td style='text-align: left;;vertical-align: text-top;padding-left:3em'>
    <b><span style="font-size:12mm">Michael Lutter</span></b><br>
    <b><span style="font-size:4mm">Research Scientist & Technical Lead</span></b><br>
    <b><span style="font-size:4mm">at Boston Dynamics</span></b><br><br>
    <b>Contact:</b><br>mail(at)mlutter.eu <br>
    <a href="https://www.linkedin.com/in/michaellutter/">LinkedIn</a> | 
    <a href="https://twitter.com/_mlutter">Twitter</a> |
    <a href="https://scholar.google.com/citations?user=Wvdo5bYAAAAJ&hl=en">Google Scholar</a><br><br>
    <b>Sections:</b><br>
    <a href="#research">Research</a> |
    <a href="#bio">Bio</a> |
    <a href="#boston-dynamics">Boston Dynamics</a> |
    <a href="#news">News</a> 
    </td>
  </tr>
</table> 
<br>


## Research Interests {#research}
<p style='text-align: justify;'>
<b>Dexterous Manipulation:</b><br>
I am excited to work on contact-rich and dexterous manipulation tasks that are essential
for reliable real-world deployments. Current methods are often not applicable to such tasks.

<br><br><b>Reinforcement Learning:</b><br>
I use reinforcement learning to reduce the reliance on real-world demonstrations. 
RL requires less human demonstrations and works with sub-optimal demonstrations.

<br><br><b>Large-Scale Physics Simulation:</b><br>
I leverage large-scale physics simulation to scale robot data. 
Only synthetic data allows us to truly scale data for humanoid robots in an cost effective way.

<br><br><b>Sim-to-real for Manipulation:</b><br>
I am driven to prove that sim-to-real can work for dexterous manipulation. 
This approach became the norm for whole-body control in recent years and 
I think the same is possible for manipulation.
</p>

## Bio {#bio}
<p style='text-align: justify;'>
I lead the Atlas Dexterous Manipulation team at 
<a href="https://www.bostondynamics.com/">Boston Dynamics</a>. 
This team works on developing vision-based dexterous manipulation policies for humanoids with reinforcement learning and 
synthetic data. Previously, I worked on learning reactive quadruped locomotion over slippery terrain 
with Spot using reinforcement learning.</p>

<p style='text-align: justify;'>
Before Boston Dynamics, I completed his Ph.D.
supervised by <a href="https://www.ias.informatik.tu-darmstadt.de/Team/JanPeters">Jan Peters</a> at 
<a href="https://www.ias.informatik.tu-darmstadt.de/">TU Darmstadt</a>. My research focused on inductive biases 
for robot learning.
I completed a research internship at Google DeepMind, NVIDIA Research and received multiple awards including the 
<a href="https://en.wikipedia.org/wiki/Georges_Giralt_PhD_Award">George Giralt Ph.D. Award (2022)</a>
for the best robotics Ph.D. thesis in Europe and the <a href="https://ki50.de/ki-newcomer/">AI newcomer award (2019)</a> 
of the German computer science foundation. In addition, my Ph.D. thesis was published as a book within the 
<a href="https://link.springer.com/book/10.1007/978-3-031-37832-4">Springer STAR series</a>.
</p>

<p style='text-align: justify;'>
I completed a Bachelors in Engineering Management at 
<a href="https://www.uni-due.de/en/">University of Duisburg Essen</a> and a Masters 
in Electrical Engineering at <a href="https://www.tum.de/">TU Munich</a>. 
During my undergraduate studies I spent one semester abroad at 
<a href="https://www.mit.edu/">MIT</a> 
studying electrical engineering and computer science. Within my studies, I received 
multiple scholarships for academic excellence and ranked among the top three students 
within my graduation year.</p>


## Boston Dynamics {#boston-dynamics}
<span style="font-family:'Courier New', monospace"><b>02/25-present</b></span> - Technical Manager of the Atlas RL Manipulation Team<br>
<span style="font-family:'Courier New', monospace"><b>03/24-02/25</b></span> - Tech Lead for Reinforcement Learning<br>
<span style="font-family:'Courier New', monospace"><b>05/22-02/25</b></span> - Senior Staff Research Scientist


### Dexterous Manipulation
<p style='text-align: justify;'>
Solving dexterous manipulation with behavioral cloning is challenging as demonstrations are 
rarely optimal for such tasks. To leverage sub-optimal demonstrations, I use reinforcement learning and 
simulation to improve these demonstrations and train vision-based manipulation policies. 
I am excited to show that sim-2-real for manipulation can be as successful as for whole-body
control.</p>


<p style='text-align: justify;'>
Besides leading this project, I am deeply involved in the day to day technical work within this project. 
I have specifically developed the reinforcement learning training infrastructure, setup the physics simulation 
and trained policies for insertion & extraction tasks. In addition, I was part of the BD & NVIDIA 
collaboration on object grasping <a href="https://www.youtube.com/watch?v=dFObux6mfTc">[video]</a> 
<a href="https://developer.nvidia.com/blog/r2d2-adapting-dexterous-robots-with-nvidia-research-workflows-and-models">[blog]</a>.
</p>

### Quadruped Locomotion
<p style='text-align: justify;'>
As one of the first reinforcement learning hires at Boston Dynamics, I worked on learning quadruped locomotion on 
challenging slippery terrain. This initial prototype was so convincing that we shipped a reinforcement learning 
policy to thousands of customer robots. 
Nowadays, reinforcement learning is the core technology for whole-body control at Boston Dynamics.  
</p>

<p style='text-align: justify;'>
Within this project, I led the development of a policy that can traverse slippery terrain where the existing 
model-based controller struggled. I trained the policies using sim-2-real reinforcement learning and 
deployed these policies to Spot. This work was presented at multiple conference workshops including 
RSS, CoRL and IROS. In addition, I contributed to the reinforcement learning and 
physics simulation infrastructure. I also worked on the Spot controller selection policy that got integrated into the 
Spot release <a href="https://bostondynamics.com/blog/starting-on-the-right-foot-with-reinforcement-learning/">[blog]</a>
and consulted on the 2025 Spot performance on America got Talent
<a href="https://www.youtube.com/watch?v=LMPxtcEgtds&t=14s">[video]</a>.
</p>


## News {#news}
 <ul>
<li><span style="font-family:'Courier New', monospace"><b>(07.Feb 25)</b></span> - Invited Talk at the <a href="https://www.mitaimlconference.com/">MIT Sloan AI Conference</a> on RL for robotics</li>
<li><span style="font-family:'Courier New', monospace"><b>(29.Dec 24)</b></span> - New preprint on the diminishing returns of value expansion <a href="https://arxiv.org/abs/2412.20537">[Arxiv]</a></li>
<li><span style="font-family:'Courier New', monospace"><b>(09.Nov 24)</b></span> - Invited Talk at CoRL WS on <a href="https://www.locolearn.robot-learning.net/">Learning for Locomotion</a></li>
<li><span style="font-family:'Courier New', monospace"><b>(15.Jul 24)</b></span> - Invited Talk at RSS WS on <a href="https://earl.robot-learning.net/">Embodiement-Aware Robot Learning</a></li>
<li><span style="font-family:'Courier New', monospace"><b>(15.Jul 24)</b></span> - Invited Talk at RSS WS on <a href="https://sites.google.com/alora.tech/priors4robots24">Structural Priors for Robot Learning</a></li>
<li><span style="font-family:'Courier New', monospace"><b>(15.Jul 24)</b></span> - Invited Talk at the <a href="https://frobio.wordpress.com/">Freiburg Robotics and Biology</a> conference</li>
<li><span style="font-family:'Courier New', monospace"><b>(01.Oct 23)</b></span> - Invited Talk at IROS WS on <a href="rlconform-workshop.github.io">Reinforcement Learning</a></li>
 <li><span style="font-family:'Courier New', monospace"><b>(01.Aug 23)</b></span> - Published my Ph.D. thesis in the Springer STAR series  <a href="https://link.springer.com/book/10.1007/978-3-031-37832-4">[Springer]</a></li>
 <li><span style="font-family:'Courier New', monospace"><b>(19.Apr 23)</b></span> - Accepted IJRR Journal Paper on Deep Lagrangian Networks <a href="https://journals.sagepub.com/doi/10.1177/02783649231169492">[IJRR]</a><a href="https://arxiv.org/pdf/2110.01894.pdf">[Arxiv]</a></li>
<li><span style="font-family:'Courier New', monospace"><b>(22.Jan 23)</b></span> - Accepted ICLR Paper Diminishing Return of Value Expansion <a href="https://arxiv.org/abs/2303.03955">[Arxiv]</a></li>
<li><span style="font-family:'Courier New', monospace"><b>(14.Dec 22)</b></span> - Invited Talk CoRL WS on <a href="https://sites.google.com/view/corl-2022-inductive-bias-ws/home">Inductive Bias in Robot Learning</a></li>
<li><span style="font-family:'Courier New', monospace"><b>(19.Oct 22)</b></span> - Accepted TPAMI Journal Paper on Value Iteration <a href="https://ieeexplore.ieee.org/document/9925102">[IEEE]</a><a href="https://arxiv.org/pdf/2110.01954.pdf">[Arxiv]</a></li>
<li><span style="font-family:'Courier New', monospace"><b>(29.Jun 22)</b></span> - Received the George Giralt Award for best robotics Ph.D. thesis in Europe</li>
<li><span style="font-family:'Courier New', monospace"><b>(23.May 22)</b></span> - Joined the Boston Dynamics Atlas team to work on RL for locomotion</li>
<li><span style="font-family:'Courier New', monospace"><b>(19.Nov 21)</b></span> - Defended my Ph.D. on Robot Learning :mortar_board: :tada: :robot: <a href="https://tuprints.ulb.tu-darmstadt.de/20048/1/Phd_Thesis_Michael_Lutter.pdf">[Thesis]</a></li>
<li><span style="font-family:'Courier New', monospace"><b>(29.Sep 21)</b></span> - New pre-print on learning dynamics models for MPC <a href="https://arxiv.org/pdf/2109.14311.pdf">[Arxiv]</a></li>
<li><span style="font-family:'Courier New', monospace"><b>(10.May 21)</b></span> - Accepted RSS Paper Robust Value Iteration for Continuous Control <a href="https://arxiv.org/pdf/2105.12189.pdf">[Arxiv]</a></li>
<li><span style="font-family:'Courier New', monospace"><b>(08.May 21)</b></span> - Accepted ICML Paper Value Iteration in continuous space and time <a href="https://arxiv.org/pdf/2105.04682.pdf">[Arxiv]</a></li>
<li><span style="font-family:'Courier New', monospace"><b>(01.Apr 21)</b></span> - Accepted ICRA Paper Model-Learning for offline RL <a href="https://arxiv.org/abs/2011.01734">[Arxiv]</a></li>
<li><span style="font-family:'Courier New', monospace"><b>(14.Jan 21)</b></span> - Started my Research Internship with the DeepMind Robotics Team</li>
<li><span style="font-family:'Courier New', monospace"><b>(11.Dec 20)</b></span> - Organizing NeurIPS WS on <a href="https://inductive-biases.github.io/">Inductive Biases and Physically Structured Learning</a></li>
<li><span style="font-family:'Courier New', monospace"><b>(25.Oct 20)</b></span> - Invited Talk IROS WS on <a href="http://www.iros-ar2020.lissi.fr/doku.php/start">Trends and Advances in ML and Automated Reasoning</a></li>
<li><span style="font-family:'Courier New', monospace"><b>(14.Oct 20)</b></span> - Robot Juggling paper accepted at CoRL 2020  <a href="https://arxiv.org/abs/2010.13483">[Arxiv]</a></li>
<li><span style="font-family:'Courier New', monospace"><b>(01.Oct 20)</b></span> - My Homepage is finally live :)</li>
</ul> 




