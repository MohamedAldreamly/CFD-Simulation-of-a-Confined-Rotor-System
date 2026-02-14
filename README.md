# CFD Analysis of an Axial Fan Using ANSYS Fluent

Project Overview
This project presents a detailed Computational Fluid Dynamics (CFD) analysis of a 3-blade axial fan operating inside a confined enclosure using ANSYS Fluent (2025 R2 Student Version).

The study investigates transient flow behavior using the Sliding Mesh technique to accurately capture blade rotation effects and rotating–stationary interface interaction.

---

 Objectives
- Analyze velocity distribution inside the enclosure
- Evaluate static pressure variation across the rotor
- Identify swirl intensity and recirculation zones
- Study transient blade–fluid interaction
- Assess aerodynamic performance under confined conditions

---

Software & Tools
- ANSYS Workbench
- ANSYS Fluent (2025 R2 – Student Version)
- MultiZone Meshing Method
- Sliding Mesh (Dynamic Mesh)

---

Simulation Setup

Domain Type

- 3D Transient Simulation
- Air as working fluid
- Confined enclosure domain

Rotational Parameters

- Rotational Speed: 500 RPM
- Time Step: 0.001 s
- Number of Time Steps: 500
- Iterations per Step: 20

Turbulence Model

- Reynolds Stress Model (RSM)

Boundary Conditions

- Pressure Inlet: 0 Pa
- Pressure Outlet: 0 Pa
- Walls: No-slip condition
- Turbulence Intensity: 5%
- Viscosity Ratio: 10

---

Mesh Information
- MultiZone structured mesh
- Hexahedral dominant elements
- Sliding mesh interface
- Optimized for rotating flow simulations

---

 Key Results

Velocity Distribution
- Maximum velocity: ~46–48 m/s
- Highest velocities at blade tips (V = ωr relationship)
- Formation of a strong axial jet downstream
- Low-velocity regions near hub and enclosure walls

Swirl & Recirculation
- Strong vortical structures near blade tips
- Wake asymmetry downstream
- Confined-domain recirculation zones

Pressure Behavior
- Pressure before rotor: -86.99 Pa
- Pressure after rotor: -364.61 Pa
- Pressure difference: ΔP ≈ -277.62 Pa

Pressure drop confirms kinetic energy dominance and wake-induced losses within confined domain.

---

Convergence Behavior
Transient residuals show periodic saw-tooth behavior typical for sliding mesh simulations, indicating stable periodic blade passage solution.

---

Engineering Interpretation
The fan successfully generates:
- Axial momentum transfer
- High-velocity jet formation
- Significant angular momentum (swirl)

However:
- Confinement increases turbulence
- Energy partially dissipates into vortical structures
- Domain size affects overall aerodynamic efficiency

---

Limitations
- Student version mesh limitations
- No experimental validation
- Domain confinement influence
- Possible mesh refinement near blade tips

---

Conclusion
The transient sliding mesh simulation successfully captured the aerodynamic behavior of a rotating axial fan inside a confined enclosure.

Results demonstrate realistic vortex structures, velocity acceleration, and periodic blade interaction effects, highlighting the importance of transient CFD modeling for rotating machinery analysis.

---
Author
Mohammed Ayman Aldreamly
hamoud14126@gmail.com
+970592171684
Mechatronics Engineering  
CFD & Fluid Dynamics Enthusiast
