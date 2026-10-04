# A4 – [Topic]

## Objective
The objective of this project was to design a motor mount for a 24 V DC gear motor. The mount must attach the motor to a rigid wall represented by A and be able to support the 300 N force applied to the motor shaft. The design is divided into two distinct structural features. Feature 1 supports the motor and is treated like a cantilever beam. Feature 2 attaches the mount to the rigid wall and is analyzed based on the bending moment produced by Feature 1.

The mount must be designed using a safety factor of 3 and must have a maximum allowable deflection of 0.30 mm at the free end. The motor's weight is neglected. The final goal is to create a practical motor mount that satisfies the calculated stress and deflection requirements and can be manufactured as a parametric CAD model.

## Analyze
After reviewing the project requirements, Appendix A, and Appendix B to understand the loading conditions, motor dimensions, and expected design approach. Appendix A was used to obtain the actual motor dimensions, including the Ø28 mm gearbox, Ø27.7 mm motor body, Ø6 mm shaft, Ø22 mm mounting-hole pattern, and four M3 mounting holes.

The project let us choose from the allowed choices ABS, PETG, or PLA. I compared the available materials and then selected PLA for my design. I decided to choose PLA because it provides sufficient strength and stiffness for the calculated loading conditions. I used the following parameters:

E = 3500 MPa

Sy = 48 MPa

σ_allow = 48 / 3 = 16

σ_allow = 16 MPa

I researched motor-mount designs to understand common features, shapes, and intricacies in this specific part. Some of these designs included motor mounting plates, L-shaped brackets, and brackets with reinforcing gussets. After looking at multiple sites and concluding my research I decided that an L-shaped mount would be appropriate for this project.

Links used:

[Website 1](https://www.pololu.com/product/1084)

[Website 2](https://www.rpmrubberparts.com/6-considerations-for-engine-mount-design/)

## Feature 1
I have added a photo that includes all calculations and dimensions used for the first feature of the motor mount, being a fixed cantilever beam connected at wall A. Including applied force, length, and maximum bending moment. I used beam equations to calculate required thickness keeping in mind stress and deflection. After finding the respected values I chose a deflection requirement which was a centerpiece for this first feature being 18mm. These calculations yielded values for stress and deflection as shown below. 

<img width="2168" height="2928" alt="CamScanner 10-3-26 19 34_1" src="https://github.com/user-attachments/assets/40a2b2ec-b080-47b9-9c5f-6ed6a3425098" />

## Feature 2
I have attached a photo that includes all calculations and dimensions used for the second feature of the motor mount, analyzed as the vertical member attached to rigid wall A. Similarly to Feature 1 I included the forces, length, maximum bending moment, and moment produced by the first feature as well. Using appendix B, I calculated the stress and deflection calculations as shown. Using the previously selected deflection requirement of 18mm. These calculations yielded values for stress and deflection as shown below. 

<img width="2152" height="2932" alt="37CBE26A-F6E5-490A-9F2A-8EAB71C9238D" src="https://github.com/user-attachments/assets/e472d169-fe2e-45c8-9694-5abc1d76329f" />


## Decide
Material Selection: I chose PLA because it is lightweight, inexpensive, easy to 3D print, and strong enough to handle the expected loads.

Feature 1 Design: From my calculations I discovered that a minimum thickness of 15.29 mm was needed for deflection. An 18 mm thickness was chosen to provide additional stiffness.

Feature 2 Design: These calculations showed that a minimum thickness of 17.50 mm was needed for deflection. An 18 mm thickness was selected to meet the requirement.

Overall Geometry: The mount was designed with a 40 mm width, a 50 mm Feature 1 length, and a 50 mm Feature 2 height.

Mounting Features: The design includes four Ø3.4 mm motor clearance holes on a Ø22 mm bolt circle and a Ø7 mm shaft clearance.

## Concept Sketch 
Before I created any CAD models, I wanted to create a isometric sketch that shows all calculated and given dimensions of my motor mount. This showcases the basic L shape and the mounting holes as well. 

<img width="1512" height="1064" alt="21237AFF-B1A2-4D65-948F-4E4536E061D3" src="https://github.com/user-attachments/assets/c9890e6d-db46-4172-9fb1-b90d2c0ee3b9" />




## Communicate

