---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<br>   ; this is used as empty line

EDUCATION 
======
* M.S. in Astrophysics, Ludwig-Maximilians-Universität München  <span style="float: right;">_2022 - present_</span>
* B.S. in Physics, Jilin University <span style="float: right;"> _2018 - 2022_ </span> 

RESEARCH EXPERIENCE
======
**Scattering Transform Pipeline on Cosmological Constraints**
* Master thesis, University Observatory Munich   <span style="float: right;"> Nov 2023 - present </span>
  * Utilized Morlet wavelet filters of varying scales and orientations to perform wavelet convolution on cosmological convergence square maps. Calculated the modulus of the convolved fields and used the scattering coefficients (mean value of the convolved map) to quantify the field’s fluctuations.
  * Applied Fisher Forecast analysis to derive cosmological constraints based on the scattering coefficients, providing insights into the relationship between field fluctuations and cosmological parameters.
  * Developed neural network-based emulators trained on cosmological simulations to predict scattering coefficients for different cosmologies. Used these emulators to perform MCMC sampling and obtain posterior distributions, thereby deriving precise cosmological constraints.
  * Implemented the emulators trained in different tomographic bins to conduct a tomographic analysis and ran MCMC again to obtain refined cosmological constraints across on cosmological parameters.
  * Supervisors: [Dr.Stella Seitz](https://www.usm.uni-muenchen.de/~stella/stella.html) & Laurence(Zhengyangguang) Gong

**Time-dependent Kinetic Analysis of Positron-Hydrogen Collision Process**
* Bachelor thesis, Jilin University  <span style="float: right;"> Dec 2021 - May 2022 </span>
  * Investigated the scattering problem of positron and hydrogen through time-dependent wave function evolution for both particles. Applied the five-point formula to obtain the hydrogen atom’s ground state wave function and expressed the system’s Hamiltonian on a position grid.
  * Used five-point formula to express kinetic energy term and got the Hydrogen atom ground state wave function
  * Expressed the Hamiltonian of Hydrogen and positron in momentum space
  * Brought the initial wave function of the whole positron and hydrogen into evolution function, used split operator to evolve and got final wave function
  * Supervisor: [Prof.Liguang Jiao](https://teachers.jlu.edu.cn/lgjiao)

 **Influence of Target Membrane Material on Neutron Tube and Its Service Life**
* Research intern, Jilin University <span style="float: right;"> May 2020 - Oct 2020 </span>
  * Explored the influence of the target membrane material and its surface layer Deuterium-Tritium on the neutron yield and the service life of the neutron tube
  * Mixed rare earth elements which can improve the alloy properties and possess good hydrogen storage effect into the titanium membrane material, used SRIM to figure out energy loss, calculated the neutron yield, compared with the performance of scandium, and found the most suitable doping metal
  * Got the conclusion that the neutron yield of lutetium-titanium alloy is the highest when the doping mass ratio is 0.2
  * Supervisor: [Prof.Jingbin Lu](https://teachers.jlu.edu.cn/LuJingbin)

**Materials Physics and Battery**
* Research intern, Jilin University <span style="float: right;"> Oct 2019 - Jan 2020 </span>
  * Prepared chlorophyll films of different thicknesses by the spin-coating method in a nitrogen environment, produced chlorophyll cells, and tested the conductivity of different film thicknesses
  * Analyzed the influence of rotation speeds on the chlorophyll film from collected data, and generalized the conductivity of the chlorophyll cell under different rotation speeds
  * Supervisor: [Prof.Xiaofeng Wang](https://teachers.jlu.edu.cn/WangXiaofeng/zh_CN/index.htm)


COURSE PROJECTS
======
**Gravitational Dynamics**
* Ludwig-Maximilians-Universität München  <span style="float: right;"> Jul 2023 - Aug 2023 </span>
  * Explored the possibility of capturing a meteorite at Lagrangian 4 Point of Sun: set the initial state of the particle so that it is just transported to the Lagrangian point so that it is in that position, rotating around the sun like Jupiter
  * Conclusion: circular motion is possible only when the minimum effective potential energy is equal to the total energy, which means there is no radial motion. A little deviation from that state will not lead to a perfect circular motion.
  * [Course Report](../files/course_project/gravitational_dynamics/Gravitational_Dynamics_Sijin.pdf)


**Hydrodynamics**
* Ludwig-Maximilians-Universität München <span style="float: right;"> Jan 2023 - Feb 2023 </span>
  * Nozzle Shape’s Influence on Acceleration: explore the influence of the shape of the nozzle throat on the effect of the nozzle, and the change of the speed of the particles before and after.
  * Conclusion: the shape of the obstacle in nozzle phenomena has little effects on the profile of velocity increase and internal energy, pressure and density distribution profile. But the width of the nozzle gap width will have visible effects on velocity acceleration. And if the gap is too narrow and the path is long, it will probably cause choking, which will not have nozzle acceleration effect


**Computational Physics**
* Jilin University  <span style="float: right;"> Sept 2021 - Nov 2021 </span>
  * Derived the algebraic expression of the electromagnetic field excited by the magnetic dipole source in the homogeneous medium and the corresponding integral expression from Maxwell equations and Hertz formula
  * Used the cubic spline fitting integration method and Gauss-Legendre integration method separately and combined them to calculate the integral expression of the electric field and magnetic field in cylindrical coordinates with MATLAB
  * Compared the accuracy of the results of these three calculations with the results of algebraic calculations


****

EXTRA CURRICULAR ACTIVITIES
======
**Cambridge Winder Academic Program**  <span style="float: right;"> Jan 2022 - Feb 2022 </span>
* Grasped Machine Learning and basic knowledge of Quantum Computing, and took Grover’s Algorithm as an example to research what is QC good for and why

**Statistical Physics and Complex Systems Summer School**  <span style="float: right;"> Aug 2021 </span>
* Studied the application of statistical physics in molecular simulation, biophysical neural network, economics, finance

**Cambridge Summber Academic Program**    <span style="float: right;"> Jul 2021 </span>
* Learned Random-field Ising model, Random-field Ising model, Synergy and Bifurcations in Epidemics

**MIT Quantum Physics Online Project-Based Learning Program**  <span style="float: right;"> Oct 2020 - Dec 2020 </span>
* Studied quantum mechanics and the development of quantum theory, earning grade A
* Calculated the expression of finite potential well with the Schrodinger equation, and showed the form of the final solution in graphs



COMPUTER SKILLS
=====
* Python: 4 and a half years experience including master thesis project. Numerical course projects, data handling in Astrophys-
ical Lab, and statistical analysis including Bayesian analysis.
* C/C++: 2 years of experience with bachelor’s course project and simulations in gravitational dynamics course.
* MATLAB: 1 year of experience utilizing MATLAB for computational physics coursework and bachelor thesis project.
* Other computational skills: LaTeX, Mathematica, Origin, MS packages
* Often-used Packages: PyTorch, emcee, ChainConsumer

  
Skills and Awards
======
* Language: English (Fluent), Chinese (Native)
* Computer skills: Python, MATLAB, LaTeX, C, C++, Linux
* Awards: Canada Mitacs Globalink Research Internship Scholarship in 2021


<!--
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams    -->

