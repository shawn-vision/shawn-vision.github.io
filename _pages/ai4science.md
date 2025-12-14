---
layout: page
title: AI for Science
permalink: /ai4science/
description: Generative AI with applications to mechanical and Earth systems
nav: true
nav_order: 2
horizontal: false
---

<!-- ===============================
     AI for Science — Page-scoped typography/color unification
     =============================== -->
<style>
.ai4science-page,
.ai4science-page * {
  font-family: "Inter", "Helvetica Neue", Arial, sans-serif;
  color: #0F172A; /* uniform dark blue */
}

/* Headings */
.ai4science-page h1,
.ai4science-page h2,
.ai4science-page h3 {
  color: #0F172A;
  font-weight: 650;
}

/* Section titles */
.ai4science-page h2 {
  margin-top: 36px;
  margin-bottom: 14px;
}

/* Label style */
.ai4science-page .section-label {
  font-size: 0.85rem;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: #0055A4;
  font-weight: 600;
  margin-bottom: 8px;
}

/* Card titles */
.ai4science-page .card-title {
  font-size: 1.02rem;
  font-weight: 600;
  margin-bottom: 6px;
  color: #0055A4;
}

/* Body text */
.ai4science-page p,
.ai4science-page li {
  font-size: 0.95rem;
  line-height: 1.6;
}

/* Strong emphasis */
.ai4science-page strong {
  color: #0F172A;
  font-weight: 650;
}

/* Links */
.ai4science-page a {
  color: #0055A4;
  text-decoration: none;
}
.ai4science-page a:hover {
  color: #003B73;
  text-decoration: underline;
}
</style>

<div class="ai4science-page">

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

  <div style="flex: 1 1 330px; min-width: 280px;">
    <div class="section-label">Research Theme</div>

    <h1 style="
      margin-top: 0;
      margin-bottom: 14px;
      font-size: 2.1rem;
      line-height: 1.2;
    ">
      Generative Models for Physical Systems
    </h1>

    <p style="margin: 0 0 12px 0; font-size: 1rem; line-height: 1.65;">
      We build <strong>physics-grounded generative models</strong> to accelerate discovery
      in fluid mechanics, heat transfer, sediment transport, and Earth-system
      dynamics — using AI not as a black box, but as a <strong>partner to theory and simulation</strong>.
    </p>

    <!-- Columbia Blue Tags -->
    <div style="display:flex; flex-wrap:wrap; gap:10px; margin-top:12px;">

      <span style="background:#9BDDFF; color:#003366;
                   border-radius:999px; padding:6px 14px;
                   font-size:0.82rem; font-weight:600;">
        Turbulence & Flows
      </span>

      <span style="background:#B3E5FC; color:#004B87;
                   border-radius:999px; padding:6px 14px;
                   font-size:0.82rem; font-weight:600;">
        Heat Transfer & Cooling
      </span>

      <span style="background:#E0F2FE; color:#02416E;
                   border-radius:999px; padding:6px 14px;
                   font-size:0.82rem; font-weight:600;">
        Probabilistic ML
      </span>

    </div>
  </div>

  <div style="flex:0 0 260px; text-align:center; min-width:240px;">
    <img src="/assets/img/pem.png"
         alt="AI for Science"
         style="
           max-width: 240px;
           width: 100%;
           border-radius: 18px;
           box-shadow: 0 16px 30px rgba(0,85,164,0.26);
         " />
  </div>

</div>

## What does “AI for Science” mean in our group?

In our work, <strong>AI is tightly coupled to physical reasoning</strong>.  
We use generative and probabilistic models to:

- learn <strong>distributions</strong> of fields (velocity, temperature, concentration)  
- emulate and accelerate <strong>high-fidelity simulators</strong>  
- quantify <strong>uncertainty and extremes</strong> in mechanical and Earth systems  
- inform <strong>design and control</strong> for engineered systems such as data-center cooling  

Rather than “replacing equations,” we aim to <strong>embed physics inside machine learning</strong> and use AI to explore regimes that are too expensive, noisy, or high-dimensional for classical tools alone.

---

## Core Research Directions

<div style="
  display:grid;
  grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
  gap:20px;
  margin: 24px 0 10px 0;
">

  <div style="background:#E8F6FF; border-radius:16px; padding:16px;">
    <div class="card-title">🌀 Turbulence & Flow Surrogates</div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Generative surrogates and operator-learning architectures that emulate turbulent
      flow fields and boundary-layer dynamics at a fraction of the computational cost.
    </p>
  </div>

  <div style="background:#F0FAFF; border-radius:16px; padding:16px;">
    <div class="card-title">❄️ Heat Transfer & Data-Center Cooling</div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      ML-enhanced models of conjugate heat transfer for <strong>AI and HPC data clusters</strong>,
      linking cooling efficiency, flow control, and thermal reliability.
    </p>
  </div>

  <div style="background:#E7F3FF; border-radius:16px; padding:16px;">
    <div class="card-title">⛰️ Sediment Transport & Morphodynamics</div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Symbolic and generative models that connect turbulence physics with bedform
      evolution, transport capacity, and landscape change.
    </p>
  </div>

  <div style="background:#F1FAFF; border-radius:16px; padding:16px;">
    <div class="card-title">📊 Probabilistic Modeling & Extremes</div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Normalizing flows, diffusion models, and other generative tools for learning
      distributions, tail behavior, and uncertainty in mechanical and climate systems.
    </p>
  </div>

</div>

---

## AI for Science Projects

<div style="
  background:#E8F6FF;
  border-radius:16px;
  padding:16px 18px;
  margin: 24px 0 18px 0;
  border: 1px solid #9BDDFF66;
">
  <div class="card-title" style="margin:0;">🧠 AI for Science Projects</div>
</div>

<style>
.ai4s-image-card {
  background: linear-gradient(
    135deg,
    rgba(232, 246, 255, 0.92) 0%,
    rgba(243, 251, 255, 0.92) 100%
  );
  border-radius: 16px;
  padding: 14px;
  border: 1px solid rgba(155, 221, 255, 0.40);
  box-shadow: 0 10px 22px rgba(0,85,164,0.10);
  transition: transform 0.12s ease, box-shadow 0.12s ease;
  text-align: center;
  height: 100%;
}

.ai4s-image-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 14px 28px rgba(0,85,164,0.14);
}

.ai4s-image-card img {
  width: 100%;
  max-width: 220px;
  height: auto;
  border-radius: 12px;
  box-shadow: 0 6px 14px rgba(0,85,164,0.18);
}

.projects .row {
  row-gap: 18px !important;
}
</style>

<div class="projects">
  {% assign sorted_projects = site.ai4science | sort: "importance" %}

  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      <div class="col">
        <a href="{{ project.url | relative_url }}" style="text-decoration:none;">
          <div class="ai4s-image-card">
            <img src="{{ project.img | relative_url }}" alt="{{ project.title }}">
          </div>
        </a>
      </div>
    {% endfor %}
  </div>
</div>

---

## Example Questions We Ask

- How can generative ML <strong>replace or augment ensembles</strong> for turbulent flows and heat transfer?  
- Can <strong>symbolic ML</strong> recover interpretable transport and scaling laws from large simulation or experimental datasets?  
- How do we combine <strong>data assimilation, generative models, and physical constraints</strong> to estimate unobserved states?  
- What is the most efficient way to use AI to <strong>design and operate cooling strategies</strong> for large data clusters?  

</div>