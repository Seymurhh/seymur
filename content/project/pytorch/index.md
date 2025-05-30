---
title: Interface Strength Modeling in FGMs
date: 2025-05-30
external_link: ''
tags:
  - research
  - interface modeling
  - additive manufacturing
  - composite materials
---

This study focused on modeling and experimentally validating the interface strength of Functionally Graded Materials (FGMs) manufactured using the Fused Filament Fabrication (FFF) process. Interface zones in multi-material printed parts often experience stress concentrations, cracking, or delamination, especially with abrupt material changes. This project aimed to address those issues by using gradient transitions and multi-scale numerical modeling to improve reliability.

<!--more-->

### 🔍 Objectives
- Investigate how varying gradient transition lengths influence interface strength.
- Compare performance of direct vs. graded and interlocked transitions.
- Use simulation to predict stress fields and validate with experimental data.

### 🧪 Experimental Design
Tensile specimens made from ABS and CF/ABS were printed with different interface geometries:
- Direct transition
- Interlock pattern
- Gradient transitions with lengths of 5%, 10%, 30%, and 100%

All samples were printed using 0/90 layups and tested under standard ASTM D638 conditions.

📌 **Result**: Gradient transitions improved tensile strength by up to **84%** over direct interfaces and improved stiffness by up to **15%**. Interlock patterns offered moderate gains but also introduced additional stress points at geometry transitions.

### 🧠 Modeling Approach
A three-scale homogenization framework was developed:

- **Microscale**: Captured fiber morphology and orientation using representative volume elements (RVEs).
- **Mesoscale**: Modeled interbead voids and composite behavior across layers.
- **Macroscale**: FE simulations of tensile specimens using graded material properties.

📈 *See page 113, Fig. 6.8 in the dissertation*: Predicted stress distribution at various gradient lengths shows a clear reduction in interfacial stress concentrations in graded designs compared to sharp material transitions.

### ✅ Key Findings
- Gradient transitions reduced interface failures and improved load transfer.
- 10–30% transition length yielded optimal strength/stiffness trade-offs.
- Model predictions closely matched experimental results, validating the FE implementation.

### 🧪 Application
This research supports the use of voxel-based digital design and FFF printing for optimized FGM parts in **aerospace**, **automotive**, and **biomedical** applications where reliable multi-material bonding is critical.

![Stress Distribution Comparison](https://lh4.googleusercontent.com/GHDLp9R4BpZVhk7cIf-wu70I-Au3gOYwW0XKFUtayaK4TnFWEm8R_fYYWgyLmtV41CH9xa8fgVNJFuxdMquAZgo=w1280)

---

### 📚 References

Hasanov, S. (2021). *Numerical Modeling and Experimental Characterization of Functionally Graded Materials Manufactured by the Fused Filament Fabrication Process* [Doctoral dissertation, Tennessee Technological University]. ProQuest Dissertations Publishing.  
[https://www.proquest.com/openview/15651078a3e62aa678f8cf3af0811840/1](https://www.proquest.com/openview/15651078a3e62aa678f8cf3af0811840/1)
