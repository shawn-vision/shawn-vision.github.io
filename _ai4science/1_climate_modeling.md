---
layout: page
title: Probabilistic Data Assimilation
img: assets/img/climate-da.png
importance: 1
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
      Probabilistic Data Assimilation for Climate Extremes
    </h1>

    <p style="margin: 0 0 10px 0; font-size: 1rem; line-height: 1.6;">
      We design <strong>distribution-aware, physics-grounded</strong> data assimilation
      frameworks that learn how full probability distributions — not just single
      trajectories — evolve in a changing climate.
    </p>

    <!-- Columbia Blue research tags -->
    <div style="display: flex; flex-wrap: wrap; gap: 10px; margin-top: 12px;">

      <span style="background:#9BDDFF; color:#003366; 
                   border-radius:999px; padding:6px 14px; 
                   font-size:0.82rem; font-weight:600;">
        Generative ML
      </span>

      <span style="background:#B3E5FC; color:#004B87; 
                   border-radius:999px; padding:6px 14px; 
                   font-size:0.82rem; font-weight:600;">
        Bayesian Inference
      </span>

      <span style="background:#D9F2FF; color:#003B66; 
                   border-radius:999px; padding:6px 14px; 
                   font-size:0.82rem; font-weight:600;">
        Extremes & Tails
      </span>

    </div>
  </div>

  <div style="flex: 0 0 260px; text-align: center; min-width: 240px;">
    <img src="/assets/img/climate-da.png"
         alt="Probabilistic Data Assimilation"
         style="max-width: 240px; width: 100%; border-radius: 18px; 
                box-shadow: 0 16px 30px rgba(0,85,164,0.28);" />
  </div>

</div>

---

### Why probabilistic data assimilation?

Traditional data assimilation in weather and climate science focuses on improving
<strong>short-term state estimation</strong> — for example, updating a model trajectory with daily temperature observations.

But long-term climate questions demand something deeper:

<div style="
  background: #F1FAFF;
  border-left: 6px solid #0055A4;
  padding: 14px 18px;
  border-radius: 12px;
  margin: 18px 0;
  color:#0F172A;
">
We are rarely concerned with the exact state on a single future day — we care about how <strong>full probability distributions</strong> evolve, especially their <strong>tails</strong> that govern extreme events.
</div>

Our work introduces a <strong>distribution-aware assimilation framework</strong> built on
<strong>Bayesian generative modeling</strong> to learn, update, and propagate the probability
distributions of climate variables.

---

### A framework for next-generation climate inference

<div style="
  display:grid;
  grid-template-columns: repeat(auto-fit,minmax(240px,1fr));
  gap:20px;
  margin: 26px 0;
">

  <div style="background:#E8F6FF; border-radius:16px; padding:16px;">
    <div style="font-size:1.05rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      📈 Parameter inference
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      <strong>Uncertainty-aware</strong> inference of climate parameters consistent with
      both physics and observational constraints.
    </p>
  </div>

  <div style="background:#F0FAFF; border-radius:16px; padding:16px;">
    <div style="font-size:1.05rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      🌡️ Extreme-event behavior
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Tail-resolving characterization of extremes beyond Gaussian or linear assumptions.
    </p>
  </div>

  <div style="background:#E7F3FF; border-radius:16px; padding:16px;">
    <div style="font-size:1.05rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      🌀 Stable long-range projections
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      More stable climate projections under <strong>noisy, sparse, or biased</strong> observations.
    </p>
  </div>

</div>

---

### What this framework enables

- **Probabilistic long-range climate estimation**  
- **Quantile-based risk and extreme-value analysis**  
- **Physics-informed generative surrogates for ensembles**  
- **Flexible coupling of ML models with dynamical systems**

---

## 📄 Representative Publications

<ol style="padding-left: 1.2rem;">

  <li style="margin-bottom: 16px;">
    <strong>Li, S.</strong>, Zheng, T., Farchi, A., Bocquet, M., & Gentine, P. (2025).  
    <strong>Probabilistic data assimilation for ensemble distribution projections with generative machine learning: A Lorenz’96 proof-of-concept.</strong>  
    <em>Geophysical Research Letters</em>.  
    <a href="https://doi.org/10.1029/2024GL112523" target="_blank" style="font-size:0.92rem; color:#0055A4;">
      🔗 Read the paper
    </a>
  </li>

  <li style="margin-bottom: 12px;">
    Qu, Y., Nathaniel, J., <strong>Li, S.</strong>, & Gentine, P. (2024).  
    <strong>Deep generative data assimilation in multimodal setting.</strong>  
    <em>CVPR 2024</em>.  
    <a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Qu_Deep_Generative_Data_Assimilation_in_Multimodal_Setting_CVPR_2024_paper.pdf"
       target="_blank" style="font-size:0.92rem; color:#0055A4;">
      📄 PDF on CVF OpenAccess
    </a>
  </li>

</ol>

---