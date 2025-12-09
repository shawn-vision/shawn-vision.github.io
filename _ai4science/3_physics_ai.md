---
layout: page
title: Numerical Surrogate Model with Machine Learning
img: assets/img/mlm.png
importance: 3
---

<img src="/assets/img/mlm.png" alt="Numerical Surrogate Model with ML" style="max-width: 30%; display:block; margin:auto; padding: 20px 0;" />

This project aims to build a **generalizable, turbulence-aware surrogate modeling framework** that combines **machine learning with physical constraints** to predict geomorphic transport processes in rivers and coastal systems. The overarching goal is to move beyond empirical formulas and instead develop **first-principles-guided ML models** that learn how microscale turbulent structures drive landscape-scale sediment response.

At its core, the framework seeks to answer a fundamental question:

> **Can we use turbulence physics + machine learning to derive universal transport laws where theory alone has struggled?**

To pursue this goal, I integrate **turbulent kinetic energy budgets, shear-stress scaling, symbolic regression, and generative surrogate modeling** to infer process-level closure relations. These surrogates reveal governing dynamics that are not directly observable, offering a pathway to physically interpretable prediction instead of black-box fitting.

---

### Case Studies Demonstrating the Framework

**1. Suspended sediment transport in vegetated channels**  
A physics-informed ML surrogate infers sediment dispersion fluxes from turbulence statistics, linking canopy-scale mixing to cross-sectional concentration fields in laboratory channels. This resolves a long-standing gap between **microscale turbulent bursts** and **bulk suspended sediment transport capacity**.

**2. Pier scour formation in erodible beds**  
By coupling ML with **TKE + shear-stress budget closures**, the model predicts equilibrium scour depth using dominant turbulent eddy scales — something previously inaccessible through classical theory. **Symbolic regression** extracts analytical transport laws, translating turbulent signatures into geomorphic response.

---

Together, these examples demonstrate the broader ambition of this research program:  
**to unify fluid mechanics, geomorphology, and AI into a single modeling architecture capable of discovering new physical laws.**


### 📄 Representative Publications  

**1.** Li, S., Qu, Y., Zheng, T., & Gentine, P. (2024).  
**Machine‐assisted physical closure for coarse suspended sediments in vegetated turbulent channel flows.**  
*Geophysical Research Letters*, 51(20), e2024GL110475.  
🔗 [Read the paper](https://doi.org/10.1029/2024GL110475)

**2.** Li, S. (2025).  
**Integrated turbulence and machine learning models explain pier scour in erodible channels.**  
*Water Resources Research*, 61(9), e2024WR039088.  
🔗[Read the paper](https://agupubs.onlinelibrary.wiley.com/doi/pdf/10.1029/2024WR039088)

---
