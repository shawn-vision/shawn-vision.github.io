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
      We design <strong>generative emulators of physical systems</strong> that learn
      <strong>minimal, closed representations</strong> of high-dimensional dynamics—
      enabling fast simulation, system identification, and physically interpretable inference.
    </p>

    <!-- Columbia Blue research tags -->
    <div style="display: flex; flex-wrap: wrap; gap: 10px; margin-top: 12px;">

      <span style="background:#9BDDFF; color:#003366; 
                   border-radius:999px; padding:6px 14px; 
                   font-size:0.82rem; font-weight:600;">
        Reduced-Order Modeling
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

    </div>
  </div>

  <div style="flex: 0 0 260px; text-align: center; min-width: 240px;">
    <img src="/assets/img/pem.png"
         alt="Generative Physical System Emulation"
         style="max-width: 240px; width: 100%; border-radius: 18px; 
                box-shadow: 0 16px 30px rgba(0,85,164,0.28);" />
  </div>

</div>

---

### Why generative physical system emulation?

Many physical systems—climate, turbulence, sediment transport, energy systems—are observed
in extremely high dimensions, yet evolve on much lower-dimensional structures.

Traditional surrogates focus on reproducing outputs.  
Our goal is to emulate the <strong>system itself</strong>.

<div style="
  background: #F1FAFF;
  border-left: 6px solid #0055A4;
  padding: 14px 18px;
  border-radius: 12px;
  margin: 18px 0;
  color:#0F172A;
">
The central challenge is to learn the <strong>minimal state representation</strong> and the
<strong>closed dynamics</strong> that evolve it—while preserving physical structure.
</div>

In this view, uncertainty is not an afterthought: it reflects unresolved scales, regime
dependence, and structural ambiguity that must be embedded in the emulator itself.

---

### A framework for minimal and closed representations

<div style="
  display:grid;
  grid-template-columns: repeat(auto-fit,minmax(240px,1fr));
  gap:20px;
  margin: 26px 0;
">

  <div style="background:#E8F6FF; border-radius:16px; padding:16px;">
    <div style="font-size:1.05rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      🧭 Minimal dimension discovery
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Learn reduced coordinates that capture the system’s attractor or manifold while
      retaining the mechanisms that govern evolution.
    </p>
  </div>

  <div style="background:#F0FAFF; border-radius:16px; padding:16px;">
    <div style="font-size:1.05rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      🧩 Closure learning
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Replace unresolved processes with data-driven closures that remain stable,
      interpretable, and physically consistent.
    </p>
  </div>

  <div style="background:#E7F3FF; border-radius:16px; padding:16px;">
    <div style="font-size:1.05rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      ⚡ Fast operator emulation
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Neural operators and generative flows enable millisecond-scale inference for
      ensembles, sensitivity analysis, and scenario exploration.
    </p>
  </div>

</div>

---

### What this framework enables

- **Reduced-order system emulators** that remain closed under evolution  
- **Validated physical closures** with uncertainty bounds  
- **Regime-aware simulation**, including extremes and rare transitions  
- **Real-time ensemble generation** for stress testing and decision support  
- **Interpretable system identification**, not black-box prediction  

---

### Science → operations

Generative emulators provide a pathway from fundamental modeling to operational use.

<div style="
  background: #F1FAFF;
  border-left: 6px solid #0055A4;
  padding: 14px 18px;
  border-radius: 12px;
  margin: 18px 0;
  color:#0F172A;
">
Our focus is on <strong>transition-ready emulators</strong>: minimal, validated, and physically
interpretable surrogates that reduce computational cost by orders of magnitude while
retaining scientific meaning.
</div>

---

<div style="margin:18px 0; padding:14px 16px; border-radius:14px; background:#1F4E79; color:white;">
  <div style="font-size:1.05rem; font-weight:800; margin-bottom:6px;">Outcome</div>
  A unified platform for learning, emulating, and understanding complex physical systems—
  revealing minimal structure, enabling fast simulation, and supporting decision-grade analysis.
</div>

---
