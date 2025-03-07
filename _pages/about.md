---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a Postdoctoral researcher in Applied Mathematics at FAU, Friedrich-Alexander-Universität, Erlangen (Germany), where I collaborate with Prof. E. Zuazua.\
Before, I got a PhD in applied mathematics from the University of Bordeaux, (France) and I worked as a postdoctoral researcher at École Nationale des Ponts et Chaussées, Marne La Vallée, (France), in collaboration with Prof. V. Ehrlacher.

## Research interests
<ul>
<li> Numerical methods for partial differential equations (especially model order reduction) </li>
<li>Data-based/simulation-based methods, machine learning techniques </li>
<li>Multiphysics coupled systems, variational inequalities (contact mechanics) </li>
<li>Optimization </li>
</ul> 


<!-- Questo è un commento e non verrà visualizzato nella pagina -->

## Summary of research activities
# Multi-physics problems: component-based model order reduction
The application that motivated **my doctoral thesis** is the storage of high-level radioactive waste in geological environments.  
The work is driven by applications to thermo-hydro-mechanical (THM) systems---I collaborated with [Andra](https://www.andra.fr)
--- the French National Agency for Radioactive Waste Management.
THM equations model the behavior of temperature, interstitial water pressure, and solid displacement in the vicinity of geological repositories, which contain radioactive waste and are responsible for a significant thermal flux toward the Earth's surface. 
From a mathematical perspective, the THM system we solve is a coupled, time-dependent, and highly nonlinear system. Furthermore, the solution to the problem depends on several parameters, which may be related to the geometric configuration (e.g. the number of repositories, their distance, or their size) or to the material properties of the medium. 
For example, changes in the position and/or number of radioactive waste repositories could lead to significant variations in predicted quantities of interest; therefore, we would need to solve the numerical model multiple times. 
This represents a multi-query problem and requires the application of component-based parametric model order reduction (CB-pMOR). 
In [Iollo et al. 2023](https://www.sciencedirect.com/science/article/pii/S0045782522007423) I proposed a CB-pMOR formulation for stationary problems in nonlinear elasticity. 
Finally, in [Iollo et al. 2023](https://www.scipedia.com/wd/images/d/d9/Draft_Sanchez_Pinedo_755799274pap_193.pdf) and in my [PhD thesis](https://theses.hal.science/tel-04006932/document) I extended the CB formulation and methodology to time-dependent nonlinear problems with internal variables to solve the THM problem of interest.

# Multi-particles systems: model order reduction and machine learning

<!--\[ a^2 + b^2 = c^2 \]

Possiamo anche scrivere una formula inline, come \( E = mc^2 \), per rappresentare la famosa equazione di Einstein sulla relatività.


 -->
