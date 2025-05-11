---
title: "Mathematical Modelling Experience"
date: 2024-05-21
layout: post
---
**My Experience developing Matehmatical models**

I have developed several mathematical models in my time as a student and an engineer, two i would like to highlight are a Finite difference approximation 
that i used to evaluate temperatures within an induction furnace. And a cylindrical stress calculator to calcaulate stresses within an arrangment of stacked cylinders 
undergoing thermal expansion, where thermal stress arise from different expansion co-efficients. 

<b>Model 1: FDM </b><br>

<div style="display: flex; gap: 20px; align-items: center; justify-content: center;">
 <img src="https://alexdawes-01.github.io/AlexDawes-Engineering_Portfolio/assets/images/Radial-heat-conduction-equation.png" alt="EQ1" width="300" height="80" />
 <img src="https://alexdawes-01.github.io/AlexDawes-Engineering_Portfolio/assets/images/Radial-FDM-equation.png" alt="EQ2" width="550" height="80" />
</div>
<br>
The above equations are the same, as in they are determining the same profile. Only the one on the right is the discretised version that
i used to implement on a computer, using python. With this method, i could assign points within the area of interest nodes, and determine how
heat was transferred across these nodes across a given timeframe. Using experimentally derived source terms and appropriate boundary conditions, I used the method
to simulate the temporal behaviour of a graphite susceptor in an induction furnace encased in refractory materials. Which was then used to 
determine what furnace power was to selected for appropriate tempertaure control. Several graphite gemoetries were investigated. 
<br><br>
<div style="display: flex; gap: 20px; align-items: center; justify-content: center;">
 <img src="https://alexdawes-01.github.io/AlexDawes-Engineering_Portfolio/assets/images/Cylinder.png" alt="Graphite cylinder" width="400" height="300" />
 <img src="https://alexdawes-01.github.io/AlexDawes-Engineering_Portfolio/assets/images/triangleFDM.png" alt="Graphite Triangles" width="400" height="300" />
</div>
<br><br>
<b>Model 2: Cylindrical thermal stresses </b><br><br>
Within a system a hollow graphite cylinder enacased on either side by different refractory material, graphite susceptors would crack, due to thermal stresses. 
These needed to be better understood in order to mitigate them,and aid the design of new susceptors which did not break during operation. 
I used an approach based on the fundamental theory of elasticity in cylindrical co-ordinates, based on Lames equations.
I created a matrix system describing the interfaces of the different cylindrical elements, and implementing boundary conditions;
the matrix becomes solvable, leading to solutions to the differential equations describing the stress and strain of each element.
This allows the system stress to be plotted, allowing me to identify the appropriate thickness for a graphite susceptor.
This was done in python. 
<br>
The google Colab file can be found here.
<br>

<img src="https://alexdawes-01.github.io/AlexDawes-Engineering_Portfolio/assets/images/Stress-dist-cylinders.png" alt="Stress distribution in cylinders" width="600" height="400" />
