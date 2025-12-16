---
layout: project
title: Blade Design Project
description: Blade Design Project
technologies: [Autodesk Fusion, Matlab]
image: /assets/images/blade-image.jpg
---
**Project Overview:**
For a class, we were asked to design wind-turbine blades that would be tested in a wind tunnel and operate as a turbine. The project involved aerodynamic and structural design of wind-turbine blades for operation in a wind tunnel at a fixed angular velocity. The objective was to select blade geometry parameters, including airfoil selection, chord distribution, and twist profile, that would maximize the output power while also remaining within the torque, structural and geometric constraints provided. The project was evaluated in a low-Reynolds number environment, which required consideration of viscous effects and realistic operating conditions. 

**Design Process:**
The design process began as parameter driven, ensuring complaince with the required constraints, and then became iterative, with paramets increased or decreased to maximize predicted power output. Our team began by first defining geometric and operational constraints, conducting background research, and then developing an analytical model. Major decisions involved selecting airfoil profile, chord distribution, twist distributions, and optimal tip-speed ratio. We designed a MATLAB based model  to evalualte the effects of these parameters on predicted torque and power output. Based on the model results, the blade geometry was refined to balance aerodynamic effeicency with structural and torque limitations before finalizing a design for manufacturing and testing. 

Most curernt update  2
<div style="display:flex; gap:18px; flex-wrap:nowrap; align-items:flex-start; margin:1rem 0;">
  <!-- Image 1 -->
  <figure style="margin:0; width:240px;">
    <img src="{{ '/assets/images/blade-cad.jpg' | relative_url }}"
         alt="Final blade CAD model"
         style="width:100%; border-radius:10px;">
    <figcaption style="font-size:0.9rem; color:#555; margin-top:0.4rem; line-height:1.2;">
      Final blade CAD geometry (chord/twist distribution).
    </figcaption>
  </figure>

  <!-- Image 2 -->
  <figure style="margin:0; width:240px;">
    <img src="{{ '/assets/images/flow-power.jpg' | relative_url }}"
         alt="Power vs wind speed results"
         style="width:100%; border-radius:10px;">
    <figcaption style="font-size:0.9rem; color:#555; margin-top:0.4rem; line-height:1.2;">
      Predicted performance curves used to select the operating point.
    </figcaption>
  </figure>

  <!-- Image 3 -->
  <figure style="margin:0; width:240px;">
    <img src="{{ '/assets/images/testing-data.jpg' | relative_url }}"
         alt="Experimental results from wind tunnel testing"
         style="width:100%; border-radius:10px;">
    <figcaption style="font-size:0.9rem; color:#555; margin-top:0.4rem; line-height:1.2;">
      Wind-tunnel testing data used to validate the model.
    </figcaption>
  </figure>
</div>


**Testing Summary:**
The blades were tested in a wind tunnel across a range of freestream velocities at a fixed rotational speed. We measured output torque, rotatonal speed, and power output, which were used to create a power- angular velocity curve and determine the optimaml opperating point. Experimental results were then compared against the model predicitions to evaulate design performance and identify sources of failure. 

**Individual Contribution:**
In this project, I contributed both to the analytical and experimental aspects. I developed the MATLAB modeling code which was used to evaluate blade design parameters and generate performance predictions. I was responsible for generating and organizing plots used to present design outcomes and experimental results. I worked closely with my group throughout the design process to select key parameters and refine the blade geometry. I also participated in the wind-tunnel testing procedure, and evaluation of our design objectives on the day of testing.



