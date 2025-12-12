---
layout: page
title: Generative Physical System Emulation
img: assets/img/pem.png
importance: 3
---

<!-- Hero section with Columbia Blue theme -->
<div style="
  background: linear-gradient(135deg, #E8F6FF 0%, #C9E8FF 100%);
  border-radius: 18px;
  padding: 36px 32px;
  margin-bottom: 36px;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 28px;
  border: 1px solid #9BDDFF88;
">

  <div style="flex: 1 1 300px; min-width: 280px;">
    <div style="font-size: 0.85rem; letter-spacing: 0.12em;
                text-transform: uppercase; color: #0055A4;
                font-weight: 600; margin-bottom: 8px;">
      Research Theme
    </div>

    <h1 style="margin-top: 0; margin-bottom: 14px;
               font-size: 2.1rem; line-height: 1.2; color:#0F172A;">
      Generative Physical System Emulation
    </h1>

    <p style="margin: 0 0 10px 0; font-size: 1rem; line-height: 1.6;">
      We build <strong>generative emulators of physical systems</strong> that discover
      <strong>minimal, closed representations</strong> of high-dimensional dynamics—linking
      mechanistic structure (balances, invariances, closures) with fast, controllable simulation.
    </p>

    <!-- Columbia Blue research tags -->
    <div style="display: flex; flex-wrap: wrap; gap: 10px; margin-top: 12px;">

      <span style="background:#9BDDFF; color:#003366;
                   border-radius:999px; padding:6px 14px;
                   font-size:0.82rem; font-weight:600;">
        Reduced-Order Dynamics
      </span>

      <span style="background:#B3E5FC; color:#004B87;
                   border-radius:999px; padding:6px 14px;
                   font-size:0.82rem; font-weight:600;">
        Data-Driven Closure
      </span>

      <span style="background:#D9F2FF; color:#003B66;
                   border-radius:999px; padding:6px 14px;
                   font-size:0.82rem; font-weight:600;">
        Physics Constraints
      </span>

      <span style="background:#E8F6FF; color:#003B66;
                   border-radius:999px; padding:6px 14px;
                   font-size:0.82rem; font-weight:600;">
        Uncertainty as Structure
      </span>

    </div>
  </div>

  <div style="flex: 0 0 260px; text-align: center; min-width: 240px;">
    <img src="/assets/img/generative-physical-system.png"
         alt="Generative Physical System Emulation"
         style="max-width: 240px; width: 100%; border-radius: 18px;
                box-shadow: 0 16px 30px rgba(0,85,164,0.28);" />
  </div>

</div>

---

### Why generative physical system emulation?

Classical surrogates often learn a mapping from inputs to outputs, but many scientific questions
require something stronger: an emulator that represents the <strong>system</strong>—its state space,
operators, and closures—rather than only point predictions.

<div style="
  background: #F1FAFF;
  border-left: 6px solid #0055A4;
  padding: 14px 18px;
  border-radius: 12px;
  margin: 18px 0;
  color:#0F172A;
">
Most high-dimensional physical systems admit <strong>low-dimensional structure</strong>.
The key challenge is to learn the <strong>minimal state representation</strong> and the
<strong>closed dynamics</strong> that evolve it—while preserving physical constraints.
</div>

In our view, uncertainty is not just “error bars”: it is the signature of unresolved scales,
structural mismatch, and regime dependence that must be represented in the emulator itself.

---

### Minimal dimension and closed representation

A central objective is to identify a <strong>minimal coordinate system</strong> that is still
<strong>closed</strong> under time evolution:

- **Dimension discovery:** learn reduced coordinates that capture the attractor/manifold  
- **Closure learning:** represent unresolved physics with data-driven closures that remain interpretable  
- **Structure preservation:** enforce balances (energy/water/mass), symmetries, and stability constraints  
- **Regime robustness:** remain valid across non-stationarity, boundary-condition shifts, and extremes  

This turns emulation into a scientific tool: a pathway to <strong>system identification</strong>,
not only acceleration.

---

### A framework for next-generation emulators

<div style="
  display:grid;
  grid-template-columns: repeat(auto-fit,minmax(240px,1fr));
  gap:20px;
  margin: 26px 0;
">

  <div style="background:#E8F6FF; border-radius:16px; padding:16px;">
    <div style="font-size:1.05rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      🧭 Minimal state discovery
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Learn reduced coordinates and effective variables that summarize multiscale dynamics
      without losing the mechanisms that matter.
    </p>
  </div>

  <div style="background:#F0FAFF; border-radius:16px; padding:16px;">
    <div style="font-size:1.05rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      🧩 Data-driven closure
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Replace unresolved terms with closures that are <strong>validated</strong>, uncertainty-aware,
      and consistent with governing budgets.
    </p>
  </div>

  <div style="background:#E7F3FF; border-radius:16px; padding:16px;">
    <div style="font-size:1.05rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      ⚡ Fast, controllable emulation
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Operator learning and generative modeling enable <strong>millisecond inference</strong>
      for ensembles, sensitivity, and scenario exploration.
    </p>
  </div>

</div>

---

### What this enables

- **Reduced-order emulators** that remain closed under evolution  
- **Validated closures** with confidence bounds and stability guarantees  
- **Regime-aware simulation** (including extremes and rare transitions)  
- **Real-time ensemble generation** for rapid stress testing and decision support  
- **Open benchmarks + APIs** for reproducible science and operational transition  

---

### Science → operations

We aim to deliver not only methods, but **transition-ready prototypes** co-developed with
agency and mission partners—designed for reliability, interpretability, and deployment.

<div style="
  background: #F1FAFF;
  border-left: 6px solid #0055A4;
  padding: 14px 18px;
  border-radius: 12px;
  margin: 18px 0;
  color:#0F172A;
">
Deliverable focus: <strong>validated closures</strong>, <strong>minimal representations</strong>, and
<strong>operational emulators</strong> that reduce compute cost per scenario by orders of magnitude
while preserving physical meaning.
</div>

---

<div style="margin:18px 0; padding:14px 16px; border-radius:14px; background:#1F4E79; color:white;">
  <div style="font-size:1.05rem; font-weight:800; margin-bottom:6px;">Outcome</div>
  A high-leverage platform for learning and emulating complex physical systems—revealing minimal structure,
  enabling fast simulation, and delivering decision-grade, physically grounded predictions and uncertainty.
</div>
