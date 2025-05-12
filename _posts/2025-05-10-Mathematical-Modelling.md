---
title: "Mathematical Modelling Experience"
date: 2024-10-30
layout: post
---
**My Experience developing Matehmatical models**

I have developed several mathematical models in my time as a student and an engineer, two I would like to highlight in paticular are a Finite difference approximation 
that I used to evaluate temperatures within an induction furnace. And a cylindrical stress calculator to calcaulate stresses within an arrangment of stacked cylinders 
undergoing thermal expansion.

<b>Model 1: FDM </b><br>

<br>
Initially, I discretised the 2-D radial heat conduction equastion with FDM, this sets up a matrix of nodes. Essentially points within the area of interest, and determine how
heat was transferred across these nodes across a given timeframe. Using experimentally derived source terms and appropriate boundary conditions, I used the method
to simulate the temporal behaviour of a graphite susceptor in an induction furnace encased in refractory materials. As seen in the contour plots below. These plots were then used to 
determine what furnace power was to selected for appropriate temperture control. Cylindrical and triangular graphite geometries were investigated. <br><br>
Please find the Colab File here CTRL+Click to stay on this page: [Open an IP compliant version of the FDM model in Google Colab (Runtime 2 mins)](https://colab.research.google.com/github/AlexDawes-01/AlexDawes-Engineering_Portfolio/blob/main/assets/files/Copy_of_Arch_IF_2D_model.ipynb)
<br><br>
<div style="display: flex; gap: 20px; align-items: center; justify-content: center;">
 <img src="https://alexdawes-01.github.io/AlexDawes-Engineering_Portfolio/assets/images/Cylinder.png" alt="Graphite cylinder" width="400" height="300" />
 <img src="https://alexdawes-01.github.io/AlexDawes-Engineering_Portfolio/assets/images/triangleFDM.png" alt="Graphite Triangles" width="400" height="300" />
</div>
<br><br>
<b>Model 2: Cylindrical thermal stresses </b><br><br>
Within a system a hollow graphite cylinder enacased on either side by different refractory material, graphite susceptors would crack, due to thermal stresses. 
These needed to be better understood in order to mitigate them,and aid the design of new susceptors which did not break during operation. 
I used an approach based on the fundamental theory of elasticity, in cylindrical co-ordinates, based on Lames equations.
I created a matrix system describing the interfaces of the different cylindrical elements, and implementing boundary conditions;
the matrix becomes solvable, leading to solutions to the differential equations describing the stress and strain of each element.
This allows the system stress to be plotted, allowing me to identify the appropriate thickness for a graphite susceptor.
This script was also coded in python. 
<br><br>
The google Colab file can be found here CTRL+click to stay on this page.<br><br>
[Open this model in Google Colab](https://colab.research.google.com/github/AlexDawes-01/AlexDawes-Engineering_Portfolio/blob/main/assets/files/Stress_Cylinders_script.ipynb)
<br><br>

<img src="https://alexdawes-01.github.io/AlexDawes-Engineering_Portfolio/assets/images/Stress-dist-cylinders.png" alt="Stress distribution in cylinders" width="600" height="400" />
<br>
