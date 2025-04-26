---
title: "A one-shot overlapping Schwarz method for component-based model reduction: application to nonlinear elasticity"
collection: publications
category: manuscripts
permalink: /publication/2015-10-01-paper-title-number-3
#excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2023-10-01
venue: 'Computer Methods in Applied Mechanics and Engineering 404, p. 115786'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0045782522007423'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
### Abstract <br>
We propose a component-based (CB) parametric model order reduction (pMOR) formulation for parameterized nonlinear elliptic partial differential equations (PDEs) based on overlapping subdomains. Our approach reads as a constrained optimization statement that penalizes the jump at the components’ interfaces subject to the approximate satisfaction of the PDE in each local subdomain. Furthermore, the approach relies on the decomposition of the local states into a port component – associated with the solution on interior boundaries – and a bubble component that vanishes at ports: since the bubble components are uniquely determined by the solution value at the corresponding port, we can recast the constrained optimization statement into an unconstrained statement, which reads as a nonlinear least-squares problem and can be solved using the Gauss–Newton method. We present thorough numerical investigations for a two-dimensional neo-Hookean nonlinear mechanics problem to validate our method; we further discuss the well-posedness of the mathematical formulation and the a priori error analysis for linear coercive problems.

**Key words.** Parameterized partial differential equations; Model order reduction; Overlapping domain decomposition; Alternating Schwarz method
