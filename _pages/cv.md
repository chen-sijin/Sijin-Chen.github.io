---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in astrophysics, Ludwig-Maximilians-Universität München, 2022-present
* B.S. in physics, Jilin University, 2018-2022

Research experience
======
* November, 2023 - present: Master thesis
  * University Observatory Munich
  * Utilized Morlet wavelet filters of varying scales and orientations to perform wavelet convolution on cosmological convergence square maps. Calculated the modulus of the convolved fields and used the scattering coefficients (mean value of the convolved map) to quantify the field’s fluctuations.
  * Applied Fisher Forecast analysis to derive cosmological constraints based on the scattering coefficients, providing insights into the relationship between field fluctuations and cosmological parameters.
  * Developed neural network-based emulators trained on cosmological simulations to predict scattering coefficients for different cosmologies. Used these emulators to perform MCMC sampling and obtain posterior distributions, thereby deriving precise cosmological constraints.
  * Implemented the emulators trained in different tomographic bins to conduct a tomographic analysis and ran MCMC again to obtain refined cosmological constraints across on cosmological parameters.
  * Supervisors: Dr.Stella Seitz & Laurence(Zhengyangguang) Gong

* December, 2021 - May, 2022: Bachelor thesis
  * Jilin University
  * Investigated the scattering problem of positron and hydrogen through time-dependent wave function evolution for both particles. Applied the five-point formula to obtain the hydrogen atom’s ground state wave function and expressed the system’s Hamiltonian on a position grid.
  * Used five-point formula to express kinetic energy term and got the Hydrogen atom ground state wave function
  * Expressed the Hamiltonian of Hydrogen and positron in momentum space
  * Brought the initial wave function of the whole positron and hydrogen into evolution function, used split operator to evolve and got final wave function
  * Supervisor: Prof.Liguang Jiao
 
* May, 2020 - October, 2020: Research intern
  * Jilin University
  * Explored the influence of the target membrane material and its surface layer Deuterium-Tritium on the neutron yield and the service life of the neutron tube
  * Mixed rare earth elements which can improve the alloy properties and possess good hydrogen storage effect into the titanium membrane material, used SRIM to figure out energy loss, calculated the neutron yield, compared with the performance of scandium, and found the most suitable doping metal
  * Got the conclusion that the neutron yield of lutetium-titanium alloy is the highest when the doping mass ratio is 0.2
  * Supervisor: Prof.Jingbin Lu


* October, 2019 - January, 2020: Research intern
  * Jilin University
  * Prepared chlorophyll films of different thicknesses by the spin-coating method in a nitrogen environment, produced chlorophyll cells, and tested the conductivity of different film thicknesses
  * Analyzed the influence of rotation speeds on the chlorophyll film from collected data, and generalized the conductivity of the chlorophyll cell under different rotation speeds
  * Supervisor: Prof.Xiaofeng Wang
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
* Currently signed in to 43 different slack teams

