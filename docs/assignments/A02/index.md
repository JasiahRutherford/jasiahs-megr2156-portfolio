# A2 – Truss Stress Analysis

## Objective
The objective of this assignment is to design a lightweight planar truss using A500 steel or a suitable alternative. This is done by including free-body diagrams of the joints and critical pins, calculations of the required cross-sectional areas and pin sizes using appropriate safety factors, and symbolic and numerical solutions for both truss members and pins. I will estimate the total weight of the truss and pins, develop an accurately dimensioned CAD model with realistic connections, compare the CAD-based weight predictions with hand calculations, and finally document the key engineering lessons learned throughout the design process.
<img width="317" height="215" alt="image" src="https://github.com/user-attachments/assets/9c61565e-d30a-44c1-af53-5e9de7c16d29" />

## Analyze
I analyzed the given geometric constraints and information I was given with a=0.4, b=0.3, safety factor of 3.5, a pin support at A, and a roller support at B. The given loads, P act at points C and D, so I deduced that the truss needed members that transfer these forces safely to the following supports. Below I will show calculations, findings, and conclusions to showcase the simple triangulated design that allows the truss to remain stable and lightweight.



## Decide
I decided to use P=25 kN as my forces and create a simple triangular truss connecting A, B, C, and D. I selected this geometry because triangles provide stability while keeping the number of members and overall weight low. This design also makes it easier to calculate the member forces and transfer the loads at C and D to the supports.

<img width="591" height="609" alt="image" src="https://github.com/user-attachments/assets/5426fa6f-97a9-4a14-b0c0-9c3a8c0bbeab" />

I decided to use this final truss geometry which I believe to be the best based on structural stability and simplicity. The geometry I have presented meets all the required dimensions and support conditions, I have provided a FBD and calculations of all reaction forces on this truss. This final design was used for all the remaining calculations. I initially had some trouble calculating these forces as I did not notice that each load P was pointing in a different direction. This geometry came to me fairly quickly, it was the first design that came to mind when attempting this truss problem.

<img width="593" height="800" alt="image" src="https://github.com/user-attachments/assets/49b3e2c6-83d4-4458-a114-c19da1a97848" />
<img width="585" height="517" alt="image" src="https://github.com/user-attachments/assets/da681446-9368-4df0-8eaf-2bdbed5b70f8" />

I then solved and sketched a FBD for each joint of my truss, numerically solving for each internal force. I also provided a section where I symbolically solved for each internal force. This was something that did confuse me at first. It became a lot easier when I became more clear on what variables were assigned to what sections of my joint. I am much better with numbers than symbols. 

<img width="474" height="622" alt="image" src="https://github.com/user-attachments/assets/a37f0b08-c0bf-41c9-8aa3-7fba54766e02" />

I was then tasked with using the largest internal force to calculate the required cross-sectional area of the elements using a provided safety factor of 3.5, and the yield strength. The yield strength was not provided and I found a commonly used yield strength of 269MPa for carbon steel structural tubing on this [website](https://www.amerpipe.com/products/welded-pipe/a500-specifications-page/0) After listing all my knowns and unknowns I solved for the cross sectional area symbolically and numerically to arrive at the approximate weight of the truss. This section felt the easiest for me personally, though I am still a little unsure about total length calculation. 

<img width="428" height="605" alt="image" src="https://github.com/user-attachments/assets/6af8c11d-4e9c-411f-9529-9c72c6fe4269" />

As shown above I then was tasked with determining the cross-sectional area of the connecting pins which are made of hardened tool steel with a yield shear strength of 170 ksi and a density of 0.278 lb/in3. While assuming that the elements that are in compression won’t fail in buckling. Again listing all my knowns and unknowns to make the process of solving this step much smoother. I provided the symbolic and numerical formulas and solutions to this step. I also provided a FBD of the pin and included the largest reaction load at a pin which happens to be 25kN. Most of these calculations were met with reworkings and tweaks until I felt comfortable with the results.





## Communicate

