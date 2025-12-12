---
layout: page
title: Generative Physical System Emulation
img: assets/img/12.jpg
importance: 3
---

<div style="border-left:6px solid #1F4E79; background:linear-gradient(90deg, rgba(31,78,121,0.10), rgba(31,78,121,0.02)); padding:14px 16px; border-radius:12px; margin:18px 0;">
  <div style="font-size:1.05rem; font-weight:700; color:#1F4E79; margin-bottom:6px;">
    Generative AI for Physical System Emulation
  </div>
  <div style="color:#1b1f24;">
    We develop <b>generative emulators of physical systems</b> that learn <b>minimal, closed representations</b>
    of high-dimensional dynamics. Rather than approximating single trajectories or moments, our models
    emulate the <b>state space, operators, and uncertainty structure</b> of complex systems—enabling fast,
    physically consistent prediction, inference, and scenario exploration across scales.
  </div>
</div>

## Research vision

Many geophysical and engineered systems are governed by dynamics that evolve on a
<b>low-dimensional manifold</b>, despite being observed in extremely high-dimensional spaces.
A central scientific challenge is therefore not prediction alone, but
<b>identifying the minimal set of variables, operators, and closures</b> required to faithfully
represent system behavior.

Our research advances **generative physical system emulation** by learning models that:

- **Recover minimal representations:** identifying effective state variables and reduced coordinates  
- **Learn closed dynamics:** emulating unresolved processes through data-driven physical closures  
- **Preserve system structure:** respecting conservation laws, balances, and symmetries  
- **Scale across regimes:** remaining valid under non-stationarity, regime shifts, and extremes  

Probability enters naturally—not as an add-on—but as a reflection of unresolved scales,
structural uncertainty, and intrinsic variability in the governing dynamics.

## From distributions to dynamics

While extreme events and risk are a major application, the core objective is broader:
to emulate the **full dynamical system**, not just its output statistics.

Generative models allow us to move beyond mean-field or Gaussian assumptions and instead:

- Represent the **geometry of the system’s attractor**
- Capture **nonlinear responses and rare transitions**
- Resolve **tail behavior** as an emergent property of dynamics
- Attribute changes to physical drivers (forcing, boundary conditions, land–atmosphere coupling)

In this framework, probability distributions are diagnostics of the learned system,
not the system itself.

## Methodological approach

We combine **flow-based generative models**, **neural operators**, and **physics-informed constraints**
to emulate evolution operators in reduced state spaces.

<div style="display:grid; grid-template-columns:1fr 1fr; gap:14px; margin:12px 0 4px;">
  <div style="border:1px solid rgba(31,78,121,0.25); border-radius:14px; padding:14px;">
    <div style="font-weight:800; color:#1F4E79; margin-bottom:8px;">Core models</div>
    <ul style="margin:0; padding-left:18px;">
      <li>Generative flows for state-space and operator learning</li>
      <li>Neural operators for fast, resolution-invariant emulation</li>
      <li>Latent-variable models for minimal dimensional representation</li>
    </ul>
  </div>
  <div style="border:1px solid rgba(31,78,121,0.25); border-radius:14px; padding:14px;">
    <div style="font-weight:800; color:#1F4E79; margin-bottom:8px;">Physical constraints</div>
    <ul style="margin:0; padding-left:18px;">
      <li>Conservation of energy, mass, and water</li>
      <li>Physically motivated priors and invariances</li>
      <li>Stability, consistency, and closure diagnostics</li>
    </ul>
  </div>
</div>

Model fidelity is assessed not only through forecast skill, but through
<b>structural diagnostics</b>: reliability, closure error, attractor geometry,
and robustness under extrapolation.

## What we deliver (science → operations)

Our goal is not black-box prediction, but **usable emulators of physical systems** that
can transition into real workflows:

- **Minimal-order system emulators** with quantified uncertainty  
- **Validated physical closures** with confidence bounds  
- **Transition-ready prototypes** co-developed with agency partners  
- **Millisecond inference** enabling large ensemble and real-time applications  
- **Open benchmarks and APIs** for reproducibility and community uptake  

These emulators act as drop-in surrogates for expensive simulations while retaining
physical interpretability.

## Broader impacts

- **Climate and hazards:** fast emulation of extremes, compound events, and regime shifts  
- **Engineering and infrastructure:** uncertainty-aware stress testing and design  
- **Insurance and reinsurance:** physically grounded event sets and exceedance curves  
- **Public communication:** interpretable, uncertainty-aware system behavior rather than opaque forecasts  
- **Open science:** reusable tools for reduced-order modeling and system discovery  

<div style="margin:18px 0; padding:14px 16px; border-radius:14px; background:#1F4E79; color:white;">
  <div style="font-size:1.05rem; font-weight:800; margin-bottom:6px;">Outcome</div>
  A high-leverage platform for learning, emulating, and understanding complex physical systems—
  advancing basic science, enabling operational deployment, and clarifying risk and dynamics
  for decision makers and the public.
</div>
