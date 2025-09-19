# Undergraduate Coursework Archive

This repository contains a collection of coursework projects completed during my undergraduate studies in Computer Science at the University of Liverpool.  
Most of the files are assignments or group projects submitted for different modules.

---

## COMP208 - Group Software Project
**File:** COMP208Group50Project.zip  
**Description:**  
A group project implementing a navigation system inspired by the A* search algorithm.  
Features include the ability to add stopovers and recommend optimal routes based on multiple factors such as dining, accommodation, travel time, or cost.  
- **Backend:** C++  
- **Frontend:** JavaScript, CSS, HTML  
- **Map API:** Google Maps public API  
- **Scale:** Large codebase developed collaboratively by the project team  

**Module Information:**  
- Code: COMP208  
- Credits: 15  
- Semester: 2  
- Aim: To provide students with the opportunity to complete a sizeable software development project as part of a team.  

---

## COMP201 - Software Engineering I
**File:** comp201.zip  
**Description:**  
Contains reports and code related to Software Engineering I. The work introduces different coding tasks, tools used, and explains their applications.  

**Module Information:**  
- Code: COMP201  
- Credits: 15  
- Semester: 1  
- Aim: To study analysis, design, implementation, and testing of significant computing systems (too large to be developed by a single person).  

---

## COMP285 - Computer Aided Software Development
**File:** comp285.zip  
**Description:**  
Contains coursework for COMP285, including two major assignments:  

1. **Assignment 2 (2022/2023)**  
   Development and testing of graphics routines in Java™ using Eclipse and JUnit.  
   - Focus: Test Driven Development, Unit Testing (JUnit4), Continuous Integration  
   - Tasks included debugging and completing implementations of shape classes (Point, Rectangle, Circle, RegularPolygon), writing unit tests, and adding a new RegularPolygon class.  

2. **Lab Coursework (COMP285/COMP220, 2024)**  
   Implementation of a `DateCalculator` class and automated tests.  
   - Tools: Ant build scripts, JUnit testing framework  
   - Deliverables: Ant build file, automated JUnit test cases (`DateCalculatorTest.java`), and structured build directories with XML/HTML reports.  
   - Focus: Automated Testing, Ant scripting, edge case testing, exception handling.  

**Module Information:**  
- Code: COMP285  
- Credits: 7.5  
- Semester: 2  
- Aim: To apply software development tools across the lifecycle, with emphasis on automated testing, continuous integration, and test-driven programming.  

---
#COMP390 Final Year Project
# Exploring Value Function Factorisation in Multi-Agent Actor-Critic Methods

## Project Overview
This repository contains the implementation and experimental results of my Honours Year Project (COMP390), which investigates the role of value function factorisation in Multi-Agent Reinforcement Learning (MARL), particularly in cooperative settings.

The project focuses on evaluating how different factorisation approaches impact learning efficiency, stability, and coordination in multi-agent actor-critic frameworks.

## Compliance Statement
- All data used in this project was collected via public APIs from social media platforms.
- The data is anonymous and human-related, but no human participants were directly involved in data collection or experimentation.

## Objectives
The main objective is to assess the benefits and limitations of applying value function factorisation in multi-agent actor-critic methods and to understand how such approaches affect performance in cooperative environments.

## Environments
Experiments were conducted in two representative environments:
- **Matrix Games**: Custom simulations to model strategic interactions.
- **Predator-Prey (PettingZoo)**: A cooperative pursuit–evasion scenario with partial observability.

## Algorithms Evaluated
1. **MAPPO (Multi-Agent Proximal Policy Optimization)**
   - Policy-gradient based actor-critic method.
   - Centralized training with decentralized execution.
   - High flexibility but sensitive to hyperparameters.

2. **VDN (Value Decomposition Networks)**
   - Linear additive value factorisation.
   - Stable and efficient in simple cooperative tasks.
   - Limited in representing complex agent interactions.

3. **QMIX**
   - Monotonic mixing network for nonlinear factorisation.
   - More expressive than VDN but structurally constrained.

## Key Results
- **Matrix Games**:
  - VDN and QMIX outperform MAPPO in cooperative coordination tasks.
  - MAPPO excels in non-monotonic (anti-coordination) scenarios where decomposition struggles.

- **Predator-Prey**:
  - VDN achieves the best convergence and stability.
  - MAPPO shows potential but is unstable under sparse rewards.
  - QMIX fails to learn effectively due to architectural limits.

## Limitations
- Training time was reduced (50k steps) due to computational constraints.
- Limited number of experiment runs affects statistical significance.

## Future Work
- Extend training duration for deeper convergence.
- Conduct multiple runs for stronger statistical robustness.
- Refine reward structures and exploration strategies.
- Explore advanced critics and more expressive mixing networks.

## Implementation
- All implementations are in **Python** using **PyTorch**.
- Based on the **PyMARL/ePyMARL** framework with custom extensions.

---

Author: **Leyan Li**  



## Notes
- These projects are archived for reference purposes only.  
- Code and reports reflect coursework completed between 2021–2024 during my undergraduate degree.  
