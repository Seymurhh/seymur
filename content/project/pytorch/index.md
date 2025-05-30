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

This study focused on modeling and experimentally validating the interface strength of Functionally Graded Materials (FGMs) manufactured using the Fused Filament Fabrication (FFF) process. Interface regions in multi-material parts are typically prone to stress concentrations and delamination, especially when abrupt transitions are used. This project aimed to reduce these weaknesses through graded transitions and computational modeling.

<!--more-->

### 🔍 Objective
- Evaluate how gradient transition length impacts interfacial strength in FGMs.
- Compare experimental outcomes with FE-based predictions.
- Analyze the effects of fiber reinforcement on interface performance.

### 🧪 Experimental Setup
Tensile specimens with different transition types—direct, interlock, and continuous gradient—were fabricated using ABS and CF/ABS composites. Gradients were varied from 5% to 100% of the gauge length.

- **Key Result**: Gradient transitions outperformed direct interfaces by up to **84% in tensile strength** and **15% in stiffness**:contentReference[oaicite:1]{index=1}.

### 🧠 Computational Modeling
A three-scale homogenization framework was implemented:
- **Microscale**: Fiber orientation and morphology modeled using Representative Volume Elements (RVEs).
- **Mesoscale**: Captured interbead voids and material distributions.
- **Macroscale**: Applied graded material properties in a finite element solver to simulate stress and deformation.

> 📈 *See page 113, Fig. 6.8 in the dissertation*: Predicted stress distribution at various gradient lengths shows clear reduction in stress concentrations in graded designs compared to sharp interfaces.

### 📊 Summary of Achievements
- Developed a multi-scale modeling pipeline that accurately predicts interface strength.
- Demonstrated **optimal gradient transition (~10–30%)** for maximizing strength while minimizing stress buildup.
- Confirmed through microstructural analysis that mechanical interlocking between beads enhances adhesion at interfaces.

### 🏁 Outcome
This modeling approach provides a validated method for designing stronger, more reliable FGMs—particularly useful for high-performance applications in aerospace, biomedical, and automotive industries.

![Stress Distribution Comparison]([https://lh4.googleusercontent.com/GHDLp9R4BpZVhk7cIf-wu70I-Au3gOYwW0XKFUtayaK4TnFWEm8R_fYYWgyLmtV41CH9xa8fgVNJFuxdMquAZgo=w1280](https://lh3.googleusercontent.com/JJkLIAQE5nPRbuSHaRMmz1zgrbJN0zhO-1fbr3hr419IDspcQH-zXcYUXrWNmMPuD9Jo6TVJqVHqXzDebUGKw4uy_5Ac7u0Y2yTUNJaiCOE9tK9uoQ5qBkWeprGRduyiiTliNZWMUSi8S4erU7iDuGtfOGRYu69MR7ngAlCR4NnTYnTNa231-A=w1280))
