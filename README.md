# Drone-Mounted Robotic Arm — Structural & Dynamic Analysis

**Finite Element Analysis | Rigid Body Dynamics | Mechanical Design**

## Project Overview

This project focuses on the design and simulation-based validation of a lightweight, three-degree-of-freedom (3-DOF) robotic manipulator intended for drone-mounted payload handling. The engineering challenge was to balance payload capacity and structural integrity against the mass constraints of an aerial platform, while assessing the arm's behavior under static and dynamic loading.

## Objectives

- Develop a mass-efficient 3-DOF robotic arm assembly suitable for aerial manipulation applications.
- Evaluate structural stresses, deformation, and joint integrity under payload loading.
- Estimate a safe payload capacity using a specified factor of safety.
- Simulate joint motion and dynamic scenarios to identify critical loading conditions.

## Engineering Approach

### Mechanical Design

The robotic arm was designed and assembled in **SolidWorks**, with attention to mass-efficient geometry and articulated motion for payload handling.

### Static Structural Analysis

**ANSYS Static Structural** was used to investigate the arm's response to applied payload loads, including deformation and critical joint loading. The analysis supported a payload-capacity assessment using a **factor of safety of 2.0**.

### Rigid Dynamics Simulation

**ANSYS Rigid Dynamics** was used to study coordinated joint actuation, free-fall behavior, contact response, and motion stability. These simulations helped identify demanding loading scenarios, particularly at the elbow joint, to inform potential design improvements.

## Results & Outcomes

- **Estimated safe payload capacity:** **4.29 kg**, based on the structural analysis with a **factor of safety of 2.0**.
- Assessed deformation and load-bearing behavior to evaluate structural performance.
- Simulated coordinated joint motion and additional dynamic operating scenarios.
- Identified the **elbow joint** as a critical region under demanding dynamic loads, providing direction for future structural optimization.

> **Scope:** The reported capacity and performance are simulation-based findings; this repository does not claim physical flight or experimental payload validation.

## Tools & Methods

- **SolidWorks** — 3D CAD modeling and assembly design
- **ANSYS Static Structural** — Finite element analysis, deformation, and structural safety assessment
- **ANSYS Rigid Dynamics** — Multibody motion and loading simulations
- **Engineering methods** — Rigid body dynamics, joint-load assessment, and payload-capacity evaluation

## Potential Future Work

Further work could include refining the elbow-joint design, reducing structural mass, investigating coupled drone–manipulator dynamics, and experimentally validating the simulated payload capacity.
