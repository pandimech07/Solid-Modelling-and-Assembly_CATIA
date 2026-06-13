<img width="1600" height="899" alt="output" src="https://github.com/user-attachments/assets/2c4cef11-41e1-4c6a-a070-2a48c18c1ba6" /># Design a compact consumer product by creating a detailed 3D solid model that balances strength, weight, and aesthetics; then develop a complete assembly with proper constraints and clearances to ensure functional fit; perform simulations to evaluate structural integrity and durability under real-world operating conditions; finally, prepare the model for prototyping using suitable manufacturing methods and document the entire process and improvements for presentation.
Screw Spindle Design, Modeling and Simulation

## Pandikumar S (212223080036)
## ABSTRACT

The Screw Spindle is an important mechanical component used in clamping, power transmission, and linear motion applications. This project focuses on the design, 3D modeling, material selection, simulation, and prototype development of a Screw Spindle manufactured from Mild Steel. The component was modeled using 3DEXPERIENCE (CATIA) and analyzed through Finite Element Analysis (FEA) to evaluate stress distribution and deformation under loading conditions.

## TITLE OF THE PRODUCT

Screw Spindle


## DESCRIPTION

The Screw Spindle is a mechanical power transmission element designed to convert rotational motion into linear motion. It is commonly used in machine vices, screw jacks, clamping devices, and machine tool feed mechanisms.

## Specifications

- Overall Length: 240 mm
- Thread Type: SQ38 × 7 Square Thread
- Head Diameter: 65 mm
- Through Hole Diameter: 12 mm
- Stud Thread: M12
- Material: Mild Steel

## Mechanical Properties

Property| Value
Tensile Strength| 400–500 MPa
Yield Strength| 250 MPa
Modulus of Elasticity| 200 GPa
Density| 7850 kg/m³
Poisson Ratio| 0.30

## Reasons for Selection

- Excellent machinability
- Good strength and toughness
- Cost-effective manufacturing
- Suitable for threaded power transmission components
- Easily available engineering material

## SOLID MODEL

The 3D model was developed using CATIA 3DEXPERIENCE following a feature-based parametric modeling approach.

## Main Features

- Shaft Revolve
- Hexagonal Head Pocket
- Through Hole Creation
- Thread Definition (M12 & SQ38×7)
- Chamfer Application

## Solid Model

<img width="1600" height="899" alt="solid" src="https://github.com/user-attachments/assets/45955ff5-cc70-4a6f-9351-fb29af61bce4" />

## MESH GENERATION

Finite Element Meshing was performed using tetrahedral elements to improve simulation accuracy.

## Mesh Features

- Fine mesh near thread roots
- Refined mesh around through-hole regions
- Improved stress concentration prediction

<img width="1600" height="899" alt="mesh" src="https://github.com/user-attachments/assets/5a2e3d79-4768-4e2c-9930-387d10d6fc3e" /> 

## SIMULATION RESULTS

Finite Element Analysis (FEA) was performed to evaluate structural performance under loading conditions.

## Results

- Maximum stress observed near square thread roots
- Secondary stress concentration near through-hole
- Stress values remained below material yield strength
- Safe deformation levels achieved

Factor of Safety

Factor of Safety > 2

## Simulation Output

<img width="1600" height="899" alt="output" src="https://github.com/user-attachments/assets/f096d65a-48a5-44e1-9e61-d499f4cc932b" />

## Applied Load

- Axial compressive loading
- Manual operating torque representation


## CHALLENGES FACED

Square Thread Modeling

Creating the SQ38×7 square thread profile required careful geometric definition and parameter control.

Through-Hole Positioning

Maintaining dimensional accuracy and alignment of the 12 mm hole was challenging.

Feature Dependency Management

Changes in parent features affected dependent features, requiring proper constraint handling.

Simulation Setup

Proper meshing and boundary condition assignment were necessary to obtain accurate results.

## PROTOTYPE DEVELOPMENT

Manufacturing Process

1. Facing and Centering
2. Turning Operations
3. Hexagonal Head Milling
4. Through-Hole Drilling
5. M12 Thread Cutting
6. SQ38×7 Square Thread Machining
7. Chamfering
8. Final Inspection

## Quality Inspection

- Vernier Caliper Measurement
- Micrometer Inspection
- Thread Gauge Verification
- Dimensional Accuracy Check


## INFERENCE

The Screw Spindle was successfully designed, modeled, and analyzed using CAD and FEA tools. The simulation results confirmed that the component operates safely within the mechanical limits of Mild Steel. The design is manufacturable using conventional machining processes and satisfies the intended functional requirements.

## CONCLUSION

The project successfully completed the entire product development cycle including design, modeling, material selection, simulation, and prototype planning of a Screw Spindle. The CAD model accurately represents the required geometry, and FEA results demonstrate structural reliability with a factor of safety greater than 2. The component is suitable for practical clamping and power transmission applications.
