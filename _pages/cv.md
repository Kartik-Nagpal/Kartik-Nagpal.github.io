---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[PDF Version](https://github.com/Kartik-Nagpal/Kartik-Nagpal.github.io/blob/master/files/Resume%20-%20Kartik%20Nagpal%20-%20Spring%202022.pdf)

Education
======
* High School Diploma, Westwood High School, 2018
* B.S. in Computational Engineering, University of Texas at Austin, 2022
* Certificate in Applied Statistical Modeling, University of Texas at Austin, 2022
* Certificate in Scientific Computation, University of Texas at Austin, 2022


Research Experience
======
* Aug 2021 to Present - Undergraduate Researcher in Controls and Autonomy - UT Autonomous - Dr. Ufuk Topcu
  * Developing a specialized solver for autonomous path optimization problems with many convex constraints
  * Translating mathematical algorithm to MATLAB CVX, YALMIP, JUMP code to develop ground truth models
  * Reframing mathematical algorithm to optimized parallel C/C++ code to allow for planning of Unmanned Drone pathing in real time
  * Separately, designed scripts to autogenerate high poly simulation environments to test self-driving car pathing

* Aug 2018 to Present - Undergraduate Researcher in Orbital Mechanics and Policy - ASTRIA - Dr. Moriba Jah
  * Revised current research group’s codebase on Orbital Determination and computational estimation algorithms
  * Integrated database inputs to localize orbital profile information to illustrate homogenous data values, calculations, path accuracies
  * Employed a series of numerical approximations for orbit prediction, followed by thorough residual calculation and corrections
  * Utilized Python for data extraction, data organization, NLP analysis for studying UN registration of international satellite objects
  * Presented publication (http://dx.doi.org/10.26153/tsw/11754) at the 7th Annual Space Traffic Management Conference

Work Experience
======
* October 2019 to June 2021: GNC CFD-SIMULINK Responsible Engineer, Texas Rocket Engineering Labratory
  * Oversaw a team of 6-7 members which carries out all kinds of analysis for other teams within the organization
  * Utilize construct dynamics and control models in MATLAB/Simulink to simulate trajectories and resource usage (1DOF, 4DOF, 6DOF)
  * Employ ANSYS Fluent to perform CFD simulations on the rocket body and fin designs to find aerodynamic and thermal characteristics
  * Advised and helped implement a NASA Trick 6 degree of freedom (6DOF) rocket propagation simulation

* Summer 2021: Senior Automation and Computer System Engineering Intern, CACI International
  * Designed, built, and documented entire software package for Boeing P-8 Poseidon aircraft’s logging and communication systems
  * Became the subject matter expert on WILMA US Navy product, and oversaw code revisions & deployment of new versions

* Summer 2020: Automation and Computer System Engineering Intern, CACI International
  * Wrote, reviewed, and documented a series of build-automation scripts, utilizing bash scripts and git
  * Rebuilt a user control application in C, maximizing for compute speed while adhering to UI/UX guidelines


Skills
======
* Programming Languages: C++, C, Python, MATLAB, Simulink, Java, FORTRAN, HTML, CSS, JavaScript
* Technical Tools: CVX, YALMIP, MOSEK, GUROBI, NASA Trick, Git, OpenFOAM, Orekit, Android Dev, SQL, NoSQL, Docker, NumPy, SciPy, SciKit-Learn, Theano, TensorFlow, VMs, Bash, Vim, WSL, Linux, Google Cloud Services, Microsoft Cognitive Services, Azure, Neo4j, Cypher
* Engineering Technical Skills: Autodesk Inventor, Solidworks, LabVIEW, ANSYS, Fluent
* Certifications: Certification in Microsoft Word, PowerPoint, Excel, Access, and Adobe Photoshop; AGI STK Level 1 Certification
* Additional Characteristics: US Citizen, Co-founder of EconBusters.org, Google Local Guide, Member of SIAM, ACM, ISSS, and UT-ICPC

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>