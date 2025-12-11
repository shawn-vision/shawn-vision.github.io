---
layout: page
title: Numerical Surrogate Model with Machine Learning
img: assets/img/mlm.png
importance: 3
---

<!-- Hero section with Columbia Blue theme -->
<div style="
  background: linear-gradient(135deg, #E8F6FF 0%, #C9E8FF 100%);
  border-radius: 18px;
  padding: 36px 32px;
  margin-bottom: 32px;
  border: 1px solid #9BDDFF88;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 26px;
">

  <div style="flex: 1 1 320px; min-width: 280px;">
    <div style="
      font-size: 0.85rem;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: #0055A4;
      font-weight: 600;
      margin-bottom: 8px;
    ">
      Research Theme
    </div>

    <h1 style="
      margin-top: 0;
      margin-bottom: 14px;
      font-size: 2.1rem;
      line-height: 1.2;
      color: #0F172A;
    ">
      Numerical Surrogate Models with Machine Learning
    </h1>

    <p style="margin: 0 0 10px 0; font-size: 1rem; line-height: 1.6;">
      We develop <strong>turbulence-aware, physics-guided surrogate models</strong> that
      combine machine learning with first-principles constraints to predict
      geomorphic transport processes in rivers and coastal systems.
    </p>

    <div style="display:flex; flex-wrap:wrap; gap:10px; margin-top:12px;">

      <span style="
        background:#9BDDFF;
        color:#003366;
        border-radius:999px;
        padding:6px 14px;
        font-size:0.82rem;
        font-weight:600;
      ">
        Turbulent Surrogates
      </span>

      <span style="
        background:#B3E5FC;
        color:#004B87;
        border-radius:999px;
        padding:6px 14px;
        font-size:0.82rem;
        font-weight:600;
      ">
        Physics-Guided ML
      </span>

      <span style="
        background:#D9F2FF;
        color:#003B66;
        border-radius:999px;
        padding:6px 14px;
        font-size:0.82rem;
        font-weight:600;
      ">
        Sediment & Geomorphology
      </span>

      <span style="
        background:#E0F2FE;
        color:#02416E;
        border-radius:999px;
        padding:6px 14px;
        font-size:0.82rem;
        font-weight:600;
      ">
        Symbolic Regression
      </span>

    </div>
  </div>

  <div style="flex:0 0 260px; text-align:center; min-width:240px;">
    <img src="/assets/img/mlm.png"
         alt="Numerical Surrogate Model with ML"
         style="
           max-width: 240px;
           width: 100%;
           border-radius: 18px;
           box-shadow: 0 16px 30px rgba(0,85,164,0.26);
         " />
  </div>

</div>

---

### From empirical formulas to physics-guided surrogates

This project aims to build a <strong>generalizable, turbulence-aware surrogate modeling framework</strong> that combines
<strong>machine learning with physical constraints</strong> to predict geomorphic transport processes in rivers and coastal
systems. The overarching goal is to move beyond empirical formulas and instead develop
<strong>first-principles-guided ML models</strong> that learn how microscale turbulent structures drive landscape-scale
sediment response.

At its core, the framework seeks to answer a fundamental question:

<div style="
  background: #F1FAFF;
  border-left: 6px solid #0055A4;
  padding: 14px 18px;
  border-radius: 12px;
  margin: 18px 0;
  color:#0F172A;
">
<strong>Can we use turbulence physics + machine learning to derive universal transport laws where theory alone has struggled?</strong>
</div>

To pursue this goal, we integrate:

- turbulent kinetic energy (TKE) budgets  
- shear-stress scaling and covariance closures  
- symbolic regression for interpretable laws  
- generative surrogate modeling for fast emulation  

These surrogates reveal governing dynamics that are not directly observable, offering a pathway to
<strong>physically interpretable prediction</strong> instead of black-box fitting.

---

### Framework components

<div style="
  display:grid;
  grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
  gap:20px;
  margin: 24px 0 10px 0;
">

  <div style="background:#E8F6FF; border-radius:16px; padding:16px;">
    <div style="font-size:1.02rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      🌀 Turbulence-aware feature design
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Use <strong>TKE budgets, Reynolds stresses, and coherent structures</strong> to define
      physically meaningful inputs to ML models, ensuring that surrogates “see”
      the right turbulent scales.
    </p>
  </div>

  <div style="background:#F0FAFF; border-radius:16px; padding:16px;">
    <div style="font-size:1.02rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      📉 Generative & numerical surrogates
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Replace expensive numerical solvers with <strong>ML surrogates</strong> that emulate
      transport fluxes and concentration fields while respecting conservation
      and scaling constraints.
    </p>
  </div>

  <div style="background:#E7F3FF; border-radius:16px; padding:16px;">
    <div style="font-size:1.02rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      🧮 Symbolic regression for laws
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Extract <strong>closed-form transport laws</strong> from trained models, bridging
      data-driven surrogates with interpretable, physics-based expressions.
    </p>
  </div>

</div>

---

### Case studies

#### 1. Suspended sediment transport in vegetated channels

A physics-informed ML surrogate infers sediment dispersion fluxes from turbulence statistics, linking
canopy-scale mixing to cross-sectional concentration fields in laboratory channels. This resolves a
long-standing gap between:

- <strong>microscale turbulent bursts</strong> near and within the canopy, and  
- <strong>bulk suspended sediment transport capacity</strong> at the reach scale.

The surrogate connects turbulence metrics directly to transport closures, providing a physically
consistent alternative to ad hoc mixing-length formulas.

---

#### 2. Pier scour formation in erodible beds

By coupling ML with <strong>TKE and shear-stress budget closures</strong>, the framework predicts equilibrium scour depth
using dominant turbulent eddy scales — a quantity previously inaccessible to classical theory.

Here, <strong>symbolic regression</strong> is used to:

- distill learned relationships into <strong>analytical transport laws</strong>  
- translate turbulent signatures into <strong>geomorphic response</strong>  
- clarify which scales and statistics exert primary control on scour depth  

---

Together, these examples demonstrate the broader ambition of this research program:  
<strong>to unify fluid mechanics, geomorphology, and AI into a single modeling architecture capable of discovering new physical laws.</strong>

---

### 📄 Representative Publications  

<ol style="padding-left: 1.2rem;">

  <li style="margin-bottom: 16px;">
    Li, S., Qu, Y., Zheng, T., &amp; Gentine, P. (2024).  
    <strong>Machine-assisted physical closure for coarse suspended sediments in vegetated turbulent channel flows.</strong>  
    <em>Geophysical Research Letters</em>, 51(20), e2024GL110475.  
    <a href="https://doi.org/10.1029/2024GL110475" target="_blank" style="font-size:0.92rem; color:#0055A4;">
      🔗 Read the paper
    </a>
  </li>

  <li style="margin-bottom: 12px;">
    Li, S. (2025).  
    <strong>Integrated turbulence and machine learning models explain pier scour in erodible channels.</strong>  
    <em>Water Resources Research</em>, 61(9), e2024WR039088.  
    <a href="https://agupubs.onlinelibrary.wiley.com/doi/pdf/10.1029/2024WR039088" target="_blank" style="font-size:0.92rem; color:#0055A4;">
      🔗 Read the paper
    </a>
  </li>

</ol>

---