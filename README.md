# cd-nozzle-cfd-ansys
CFD simulation of compressible flow through a converging-diverging nozzle using ANSYS Fluent.
# CFD Simulation of Compressible Flow Through a Converging-Diverging Nozzle

## Overview

This project presents a Computational Fluid Dynamics (CFD) simulation of compressible flow through a two-dimensional converging-diverging (CD) nozzle using **ANSYS Fluent**.

The simulation was carried out to investigate the variation of **pressure, velocity, and Mach number** as the flow passes through the converging section, throat, and diverging section of the nozzle.

---

## Objectives

* Model a converging-diverging nozzle for compressible flow analysis.
* Generate a suitable computational mesh for the nozzle geometry.
* Set up the flow conditions and boundary conditions in ANSYS Fluent.
* Analyze the pressure, velocity, and Mach number distributions.
* Compare the observed flow behavior with the theoretical principles of compressible flow through a CD nozzle.

---

## Software Used

* **ANSYS Workbench**
* **ANSYS Fluent**
* **ANSYS SpaceClaim**
* **ANSYS Meshing**

---

## Geometry

A **2D converging-diverging nozzle** was modeled for the simulation.

### Geometry Parameters

| Parameter                 |       Value |
| ------------------------- | ----------: |
| Inlet height              |      100 mm |
| Throat height             |  28.7706 mm |
| Outlet height             | 172.3349 mm |
| Nozzle length             |   254.46 mm |
| Converging section length |  88.7366 mm |
| Diverging section length  | 165.4602 mm |

### Nozzle Geometry

---

## Mesh

The nozzle geometry was discretized using a **___ mesh** with approximately **___ elements** and **___ nodes**.

### Mesh Information

| Parameter                  | Value |
| -------------------------- | ----: |
| Number of elements         |   ___ |
| Number of nodes            |   ___ |
| Minimum orthogonal quality |   ___ |
| Maximum skewness           |   ___ |
| Mesh type                  |   ___ |

### Mesh

---

## CFD Setup

The simulation was performed using **ANSYS Fluent**.

### Solver Settings

| Parameter       | Setting      |
| --------------- | ------------ |
| Solver          | ___          |
| Flow            | Compressible |
| Fluid           | Air          |
| Energy equation | ___          |
| Viscous model   | SST K-omega  |
| Density model   | ___          |
| Solution method | ___          |

### Operating Conditions

| Parameter              |     Value |
| ---------------------- | --------: |
| Inlet pressure         | 500000 Pa |
| Inlet temperature      |      600K |
| Outlet pressure        |    101325 |
| Operating pressure     |       ___ |
| Specific heat ratio, γ |       ___ |

### Boundary Conditions

**Inlet:** ___

**Outlet:** ___

**Walls:** ___

---

## Convergence

The simulation was run for approximately 200** iterations**.

The solution was considered converged based on the residual behavior and monitoring of relevant flow parameters.

---

# Results

## Mach Number Distribution

The Mach number contour shows the variation of flow speed relative to the local speed of sound throughout the nozzle.

**Maximum Mach number:** ___

**Mach number at throat:** ___

---

## Pressure Distribution

The pressure contour illustrates the pressure variation as the flow passes through the converging-diverging nozzle.

**Maximum pressure: ** 500000 Pa

**Minimum pressure:**   21400 Pa

---

## Velocity Distribution

The velocity contour shows the acceleration and deceleration of the flow through different sections of the nozzle.

**Maximum velocity:**  846 m/s

---

## Quantitative Results

The following plot shows the variation of Velocity** along the nozzle centerline.**

### Key Values

| Location | Pressure | Velocity | Mach Number |
| -------- | -------: | -------: | ----------: |
| Inlet    |      ___ |      ___ |         ___ |
| Throat   |      ___ |      ___ |         ___ |
| Outlet   |      ___ |      ___ |         ___ |

---

## Observations

Based on the CFD results:

* The flow **___** through the converging section.
* The flow reaches a Mach number of approximately **___** at the throat.
* The pressure changes from approximately **___** at the inlet to **___** at the throat.
* The maximum velocity of approximately **___ m/s** occurs at **___**.
* In the diverging section, the flow **___**.
* The CFD results are **___** with the expected theoretical behavior of compressible flow through a CD nozzle.

##

|    |    |    |
| -: | -: | -: |

---

## Conclusion

The CFD simulation successfully demonstrated the behavior of compressible flow through a converging-diverging nozzle.

The results showed **___**, with the flow reaching a maximum Mach number of approximately **___** and a maximum velocity of approximately **___ m/s**.

The simulation provided practical experience in **CFD model preparation, mesh generation, compressible-flow setup, boundary-condition selection, convergence monitoring, and post-processing using ANSYS Fluent**.

---

## Skills Demonstrated

* Computational Fluid Dynamics (CFD)
* ANSYS Fluent
* Compressible Flow Analysis
* Mesh Generation
* Boundary Condition Setup
* CFD Post-Processing
* Flow Visualization
* Pressure and Velocity Analysis
* Mach Number Analysis
* Comparison of CFD Results with Theory

---

## Project Information

**Author:** Mohammed Sadman Adib

**Institution:** BUET

**Date:** 

**ANSYS Version:** 2021

---

## Repository Structure

```text
cd-nozzle-cfd-ansys/
│
├── README.md
│
├── geometry/
│   └── nozzle_geometry.png
│
├── mesh/
│   └── mesh.png
│
├── setup/
│   └── boundary_conditions.png
│
└── results/
    ├── mach_contour.png
    ├── pressure_contour.png
    ├── velocity_contour.png
    ├── residuals.png
    └── flow_distribution.png
```
