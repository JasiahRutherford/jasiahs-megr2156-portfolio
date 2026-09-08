# A3 – [Topic]

## Objectives
- Use axial deflection modeling to design its dimensions
- Use parametric design to determine a bars length
- Introduce you to FEA (Finite Element Analysis)
- Introduce you to linking dimensions to appropriate parameters in CAD.
- Compare and contrast the different analysis

<img width="630" height="251" alt="image" src="https://github.com/user-attachments/assets/1a0753d5-8e99-46b3-81f8-634a2b877903" />

## Decide

**Design Process**

<img width="794" height="593" alt="image" src="https://github.com/user-attachments/assets/f71596ee-33d7-498f-b228-727b99c8b45b" />

I first started using the beam description and given values. I was tasked with creating an aluminum beam that contains a circular cross section. Finding the optimal length that will satisfy a maximum axial deflection of **.009in** and withstand a tensile load of **400lbf.** I chose a **1.00in** diameter and then solved for the cross sectional area, **.785in^2.** After I calculated this area I was able to determine the beams bar length from the direct tension elongation equation. I really enjoy having the freedom to choose my diameter and E value from a range of values given in the initial problem statement, this makes me feel more involved and interested in the outcome of my beam.

**CAD Design**

<img width="445" height="539" alt="image" src="https://github.com/user-attachments/assets/9b3d6fbd-5842-4a3a-b98a-cd7cc5449c54" />

I designed this beam with the given specific parameters including the preferred material Aluminum. I chose to use Creo since this is the only CAD software I am familiar with. I learned as I progressed through the assignment on the more intricate details of the software including how to set parameters, change material, and run a FEA. First, I navigated to the parameters tab under the modification tab located at the top of Creo. This is where I entered my given values for force, axial deflection, elasticity for the material, and diameter. I discovered you were able to set equations in the Relations tab to further confirm my hand calculations.

<img width="700" height="494" alt="image" src="https://github.com/user-attachments/assets/365a77eb-b299-403e-8b14-7449a216fa04" />
<img width="607" height="568" alt="image" src="https://github.com/user-attachments/assets/2c7509b2-bd3e-46fc-a487-5374b2f3cda9" />

## Analyze

After these parameters were set, I created an extrude of a circle directly on the front plane and ensured they followed the applied parameters. As shown in the previous image I was able to set my length and diameter to directly follow my calculated values, using the Relations tab. I chose to set d0=length and d1=diameter to ensure complete accuracy within my beam. I then set the material of my beam to the mentioned material Aluminum by going to the file tab in the top left corner->prepare tab->model properties->and changed the material to Aluminum. This was my first time ever changing the material of any part I have created, it has been a year plus since I have interacted with Creo so there was a lot of learning and discovering that occurred. 

<img width="737" height="505" alt="image" src="https://github.com/user-attachments/assets/e5c6235b-1910-4c7c-a95b-60baba8183e1" />
<img width="1095" height="867" alt="image" src="https://github.com/user-attachments/assets/74be3929-f729-4718-ae0a-6d595f278908" />

After the beam was created with all the correct constraints applied, it was time to run the FEA. I switched into the live simulation mode to begin, applying a fixed constraint on the left side of the bar and a pulling force on the right side of the bar to mimic our design. This pulling force correctly matched my given force of **400lbf.** After setting these correct forces, I ran the analysis and created an axial deflection map and a Von Mises Stress Map. 

<img width="1165" height="606" alt="image" src="https://github.com/user-attachments/assets/2ea774f3-c8fd-43ac-9586-3e7eb6934311" />
<img width="1452" height="514" alt="image" src="https://github.com/user-attachments/assets/c2e5812e-33c1-4d8d-ac1b-c1847c59c1e3" />
<img width="1514" height="537" alt="image" src="https://github.com/user-attachments/assets/722925ae-1956-49b1-9168-c0c5a56bb515" />

**Design Reflection**

After running my simulation to calculate maximum stress, I discovered that the maximum stress was **0.5095ksi** which is below the **40ksi** yield strength of aluminum. The calculation that I derived from my simulation was **0.541ksi** which is a little higher than my calculated value. This can be accounted by the conservative nature of my hand calculations. Creo is able to account for a more detailed representation of the geometry, loading, and stress distribution. The percent difference came out to be **1.1%** and I calculated a safety factor of **73.9.** I would trust the results from Creo's calculations simply because the safety factor seems more reasonable given all our constraints. If we would have used my maximum stress the safety factor would be 80, which seems unreasonable high.

<img width="789" height="478" alt="image" src="https://github.com/user-attachments/assets/5e740e0c-3989-46cc-ad4b-15570f0bbc80" />

**Pin Hole Analysis**
According to Peterson's Stress Concentration Factors, a standard traverse hole in a tension bar yields a theoretical stress concentration factor of **Kt=2.5.** Using the value I was given, I calculated the peak stress which was **1.3ksi** which remains below the **40ksi** yield strength of Aluminum, which comes out to a safety factor of **30.78** meaning it would easily pass given all our constraints.

<img width="803" height="329" alt="image" src="https://github.com/user-attachments/assets/17ea4fdf-f61b-47a4-8c08-2e4e45b8b307" />

## Communicate
Before this assignment I had not had any experience with many features needed to complete this project. Running an FEA on a CAD part, changing a parts material, and implementing parameters. So there was a learning curve in discovering these functions and how they operate. I looked up a lot of these equations needed to find needed values to progress through this assignment which did add some time setbacks. I was a little lost about the cross sectional area as the assignment description talks about width, height, and length but I continued with keeping a circular rod for this part. This project took me 5 hours to complete. 

[CAD File:]<https://drive.google.com/file/d/1ilvBpvo5X-l_E6AZ4-OrubJ9jdrhY0ob/view?usp=sharing>











