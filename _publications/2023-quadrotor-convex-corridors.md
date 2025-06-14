---
title: "Real-time quadrotor trajectory optimization with time-triggered corridor constraints"
collection: publications
permalink: /publication/2023-quadrotor-convex-corridors
excerpt: "<br/><img src='/images/paper_images/PIPG-Results.png'><br/>One of the challenges for flying quadrotors in cluttered envi-ronments is to optimize their trajectories subject to collision avoidance constraints in real time. Along such a trajectory, the position of the quadrotor must stay within a set of collision-free corridors. Each corridor is a bounded convex flight space."
date: 2023-06-01
venue: 'AIAA Journal of Guidance, Control, and Dynamics'
paperurl: 'https://doi.org/10.2514/1.G007218'
---

One of the challenges for flying quadrotors in cluttered environments is to optimize their trajectories subject to collision-avoidance constraints in real time. Along such a trajectory, the position of the quadrotor must stay within a set of collision-free corridors. Each corridor is a bounded convex flight space. The union of all these corridors forms a nonconvex pathway connecting the quadrotor’s current position to its target position.

Traditional trajectory optimization methods treat the flight corridor constraints using either mixed-integer programming or sequential convex programming. These methods are either computationally expensive for real-time applications or lack guarantees for constraint satisfaction. For example, the mixed-integer programming uses binary variables to represent the union of all corridors, and then it optimizes quadrotor trajectories together with these binary variables. The drawback of mixed-integer programming is that the worst-case computation time of mixed-integer programming increases exponentially as the number of integer variables (which depends on the number of corridors and the trajectory length) increases. An alternative is to replace the corridor constraints with equivalent collision-avoidance constraints, and then approximate the resulting nonconvex trajectory optimization using a sequence of convex ones, such as second-order cone programs or semidefinite programs. The drawback of sequential convex programming methods is that they either require careful initializations to ensure convergence or can violate collision-avoidance constraints when terminated in finite time. When terminated after a finite number of iterations, the iterates of these methods converge to a local optimal solution that may violate the rank constraints, and consequently the collision-avoidance constraints.

[Download paper here](https://doi.org/10.2514/1.G007218)

[Citation Bibtex](https://scholar.googleusercontent.com/scholar.bib?q=info:X34YyH22RbYJ:scholar.google.com/&output=citation&scisdr=ClE48TDzEJD2rC8NKrk:AFWwaeYAAAAAZ5MLMrm7eCIZ89xWxYnJ9l7luZc&scisig=AFWwaeYAAAAAZ5MLMjx8EXmLiv_KDSwFZZP5VJ0&scisf=4&ct=citation&cd=-1&hl=en&scfhb=1)