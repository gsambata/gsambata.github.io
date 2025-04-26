---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
_I am a Postdoctoral researcher in Applied Mathematics at FAU, Friedrich-Alexander-Universität, Erlangen (Germany), where I collaborate with [Prof. E. Zuazua](https://dcn.nat.fau.eu/zuazua/).\
Before, I got a PhD in applied mathematics from the University of Bordeaux, (France) and I worked as a postdoctoral researcher at École Nationale des Ponts et Chaussées, Marne La Vallée, (France), in collaboration with [Prof. V. Ehrlacher](https://team.inria.fr/matherials/team-members/virginie-ehrlacher-galland/)._

## Research interests
<ul>
<li> Numerical methods for partial differential equations (especially model order reduction) </li>
<li>Data-based/simulation-based methods, machine learning techniques </li>
<li>Multiphysics coupled systems, domain decomposition </li>
<li>Variational inequalities describing problems in contact mechanics, crowd motion </li>
</ul> 

### Some research activities
### <span class="blue">Multi-physics problems: component-based model order reduction</span>
The application that motivated **my doctoral thesis** is the storage of high-level radioactive waste in geological media---I collaborated with [Andra](https://www.andra.fr)
---the French National Agency for Radioactive Waste Management.
The Thermo-Hydro-Mechanical (THM) equations model the behavior of temperature, interstitial water pressure, and solid displacement in the proximity of geological repositories, which contain radioactive waste and are responsible for a significant thermal flux toward the Earth's surface. 
From a mathematical perspective, the THM system we solve is a coupled, time-dependent, and highly nonlinear system. Furthermore, the solution to the problem depends on several parameters, which may be related to the geometric configuration (e.g. the number of repositories, their distance, or their size) or to the material properties of the medium. 
Changes in the position and/or number of radioactive waste repositories could lead to significant variations in predicted quantities of interest; the need to solve the numerical model multiple times for design and assessment justifies the application of component-based parametric model order reduction (CB-pMOR).
In [Iollo et al. 2023](https://www.sciencedirect.com/science/article/pii/S0045782522007423) I proposed a CB-pMOR formulation for stationary problems in nonlinear elasticity. 
Finally, in [Iollo et al. 2023](https://www.scipedia.com/wd/images/d/d9/Draft_Sanchez_Pinedo_755799274pap_193.pdf) and in my [PhD thesis](https://theses.hal.science/tel-04006932/document) I extended the CB formulation and methodology to time-dependent nonlinear problems with internal variables to solve the THM problem of interest.

<p align="center">
  <img src="files/radioactive_gif.gif" alt="Animazione" width="300">
</p>


### <span class="blue">Multi-particles systems: model order reduction and machine learning.</span>
**During my postdoc**, I adapted recent approaches in nonlinear model reduction to predict solutions for time-dependent, parameterized discrete contact problems: the model I adopted is a crowd motion in the presence of obstacles. I explored novel numerical approaches that combine the reduced-basis method with supervised machine learning techniques. In [this pre-print](https://hal.science/hal-04936941) I developed a hybrid method enabling more accurate and efficient predictions of particle velocities and contact forces compared to traditional methods.
<div style="text-align: center;">
<figure>
<video width="300" controls>
  <source src="files/nlRBvideo.mp4" type="video/mp4">
</video>
 <figcaption>Comparison between the nonlinear reduced basis (nlRB) reconstruction of the positions based on the employment of hyper-reduction---by Empirical Interpolation Method (EIM)---and the high-fidelity (HF) solutions.</figcaption>
</figure>
</div>


  
 


<!--\[ a^2 + b^2 = c^2 \]

Possiamo anche scrivere una formula inline, come \( E = mc^2 \), per rappresentare la famosa equazione di Einstein sulla relatività.


 -->
