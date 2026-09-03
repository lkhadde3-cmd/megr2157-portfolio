-# A2 – Truss Stress Analysis

## Objective
The objective of this assignment is to design, analyze, and document an optimized, lightweight planar steel truss capable of supporting opposing static loads within defined geometric boundaries.


## Analyze
PART 1:
Static analysis was done to find the support reactions and internal forces throughout the truss under the applied loads. Equilibrium equations were set up for the entire structure and each joint using simple geometric run-to-rise ratios. This determined the forces in all five members and identified Member CA as the most heavily loaded element.

Process:
Boundary & Load Setup: The truss spans a horizontal length of 1.2m (3a) and a vertical height of 0.3m (b). Equal and opposite point loads of P = 20 kN are applied at node C (upward) and node D (downward). 

Global Support Reactions: Moment and force balance on the entire frame determined that the roller at B pulls downward with R_By = 6.67 kN, while the pin at A pushes upward with R_Ay = 6.67 kN R_Ax = 0 kN. 

<img width="1400" height="1000" alt="Screenshot 2026-09-03 071316" src="https://github.com/user-attachments/assets/360c86f4-82a5-4edb-9d84-cd767c2fea90" />



Method of Joints: Equilibrium equations sum Fx = 0, sum Fy = 0 were solved joint by joint. Joint B was analyzed first which yields F_BC = -11.11 kN (Compression) and F_BA = +8.89 kN (Tension). Joint D was solved next which yields F_DA = +33.33 kN (Tension) and F_C = +26.67 kN (Tension). last joint to be solved was C which yields interior diagonal F_CA = -37.97 kN (Compression).

<img width="1400" height="1000" alt="Screenshot 2026-09-03 071331" src="https://github.com/user-attachments/assets/e7433d37-9870-45a7-bd1b-7f4ffc04d0f8" />

<img width="1400" height="1000" alt="Screenshot 2026-09-03 071340" src="https://github.com/user-attachments/assets/0daad3ae-2313-4883-97d4-40e132a02e46" />



Critical Design Load: Member CA carries the peak internal load of the entire truss at F_max = 37.97 kN, which dictates the required cross-sectional size.

PART 2: 
To determine the required cross-sectional area of the truss members and estimate overall frame weight. The minimum area was derived using the peak compressive force from Member CA, the yield strength of Alloy Steel, and a safety factor of 3.5. A practical rectangular cross-section was then selected to satisfy this limit, allowing the theoretical material volume and total mass to be calculated.

Process: 
The truss members were sized using the peak internal load of 37.97 kN from Member CA, a safety factor of 3.5, and the Alloy Steel yield strength of 620.42 MPa. These criteria yielded a minimum required cross-sectional area of 214.2 mm^2, for which a practical 10 mm times 25 mm profile was selected 250 mm^2. Combining this cross-section with the total member length of 3.4544 m and material density of 7700 kg/m^3 resulted in a calculated truss mass of 6.65 kg and weight of 65.2 N.
<img width="1400" height="1000" alt="Screenshot 2026-09-03 071349" src="https://github.com/user-attachments/assets/2e0364b2-c2be-4d40-937c-513bb428bdcb" />

PART 3: 

Pin sizing was conducted to prevent catastrophic connection failure under maximum direct shear across the joint interfaces. Hand calculations evaluated the peak shear load from the critical joint using a single shear model, a safety factor of 4.0, and the shear yield strength of hardened tool steel. This established the minimum allowable cross-sectional area of 129.6 mm^2 required for the connecting pins.

<img width="1400" height="1000" alt="image" src="https://github.com/user-attachments/assets/323cfa22-ac48-46af-abee-ddff05025c00" />


## Decide

the only thing i decided for the truss was for the CA diagonal member to be there which was primarily done for simplicity. 

## Communicate

Completing this assignment reinforced how to apply the method of joints to solve for internal member forces and identify critical axial loads within a loaded frame. Building on that foundation, I learned how to use material yield limits and safety factors to size the minimum required cross-sectional area and prevent structural failure.
i think its easy to see that my biggest mistake was not didicating enough time to fully complete and understand this assignment i will do my best to prevent such a mistake from future assignments and return to complete this one. the total time spent for this assignment is 3 hours.
