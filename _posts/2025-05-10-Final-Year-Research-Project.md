---
title: "Masters Year Research Project"
date: 2024-05-21
layout: post
---
**Design and Process Parameter Optimization for Improving the Mechanical Properties of LPBF Gyroid Lattices**

In this project, I developed neural network models to optimize the mechanical properties of triply periodic minimal surface (TPMS) gyroid lattice structures manufactured via laser powder bed fusion.
By integrating process and design parameters into a neural network, I successfully predicted Young’s modulus and yield strength in both network and sheet gyroids made from Ti-6Al-4V—a titanium alloy widely used in biomedical implants.

My research found that network gyroids exhibit simpler process-thermal-structure-property relationships, while sheet gyroids achieve superior mechanical performance, albeit with greater variability. 
I'm particularly proud that these findings have direct applications in the design of bone implants, where matching mechanical properties to surrounding bone is critical to prevent stress shielding—a common cause of implant failure.

To address the challenge of limited data, I implemented Stacked Autoencoder (SAE) pre-training, which significantly improved the model's predictive accuracy. 
While surface quality and dataset size remain limiting factors, this work establishes a framework for generating process maps to guide the design and fabrication of gyroid-based implants tailored to individual patients.

It also lays the groundwork for future research in physics-informed neural networks and real-time monitoring techniques.

Below is a brief overview of the SAE architecture used, along with some of the process maps developed during this work.


<div style="text-align: center;">
   <img src="https://alexdawes-01.github.io/AlexDawes-Engineering_Portfolio/assets/images/SAE.png" alt="Stacked Autoencoder Pre-Training" width="600" height="400"/>
</div>
<div style="text-align: center;">
 <b>Stacked Autoencoder pre-training network architecture</b>
</div>
 <br> <br>
<div style="display: flex; gap: 20px; align-items: center; justify-content: center;">
 <img src="https://alexdawes-01.github.io/AlexDawes-Engineering_Portfolio/assets/images/Process-Map-1.png" alt="P1" width="400" height="300" />
 <img src="https://alexdawes-01.github.io/AlexDawes-Engineering_Portfolio/assets/images/Process-Map-2.png" alt="P2" width="400" height="300" />
</div>
<div style="text-align: center;">
  <b>Process maps to select process parameters for a given gyroid design, to acheive desired mechanical properties</b>
</div>
 <br> <br>

This project enhanced my expertise in both LPBF manufacturing and applied machine learning, paticularly on the structure on neural networks and data pre-processing.

This project has since been adapted into the format of a journal paper and is currently under peer review by Progress in additive manufacturing, springer nature <a href="https://alexdawes-01.github.io/AlexDawes-Engineering_Portfolio/assets/files/Journal-Paper.pdf" download>Journal Correspondence and list of authors</a>.

Please feel free to download the original submission here. <a href="https://alexdawes-01.github.io/AlexDawes-Engineering_Portfolio/assets/files/Final-Report.pdf" download>Download the Original Submission</a>

<div style="display: flex; gap: 20px; align-items: center; justify-content: center;">
  <img src="https://alexdawes-01.github.io/AlexDawes-Engineering_Portfolio/assets/images/Crush-Lattice.png" alt="" width="400" height="200"/>
  <img src="https://alexdawes-01.github.io/AlexDawes-Engineering_Portfolio/assets/images/Gyroid-SEM.png" alt="" width="400" height="300"/>
</div>
<br>
<div style="text-align: center;">
  <b>Images of the lattices involved during the study, failure mechanisms and SEM imagery.</b>
</div>
