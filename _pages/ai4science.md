---
layout: page
title: AI for Science
permalink: /ai4science/
description: Generative AI with applications to mechanical and Earth systems
nav: true
nav_order: 2
horizontal: false
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

  <div style="flex: 1 1 330px; min-width: 280px;">
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
      AI for Science: Generative Models for Physical Systems
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

      <span style="background:#D9F2FF; color:#003B66;
                   border-radius:999px; padding:6px 14px;
                   font-size:0.82rem; font-weight:600;">
        Sediment & Geomorphology
      </span>

      <span style="background:#E0F2FE; color:#02416E;
                   border-radius:999px; padding:6px 14px;
                   font-size:0.82rem; font-weight:600;">
        Probabilistic ML
      </span>

    </div>
  </div>

  <div style="flex:0 0 260px; text-align:center; min-width:240px;">
    <img src="/assets/img/climate-da.png"
         alt="AI for Science"
         style="
           max-width: 240px;
           width: 100%;
           border-radius: 18px;
           box-shadow: 0 16px 30px rgba(0,85,164,0.26);
         " />
  </div>

</div>

---

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
    <div style="font-size:1.02rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      🌀 Turbulence & Flow Surrogates
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Generative surrogates and operator-learning architectures that emulate turbulent 
      flow fields and boundary-layer dynamics at a fraction of the computational cost.
    </p>
  </div>

  <div style="background:#F0FAFF; border-radius:16px; padding:16px;">
    <div style="font-size:1.02rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      ❄️ Heat Transfer & Data-Center Cooling
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      ML-enhanced models of conjugate heat transfer for <strong>AI and HPC data clusters</strong>, 
      linking cooling efficiency, flow control, and thermal reliability.
    </p>
  </div>

  <div style="background:#E7F3FF; border-radius:16px; padding:16px;">
    <div style="font-size:1.02rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      ⛰️ Sediment Transport & Morphodynamics
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Symbolic and generative models that connect turbulence physics with bedform 
      evolution, transport capacity, and landscape change.
    </p>
  </div>

  <div style="background:#F1FAFF; border-radius:16px; padding:16px;">
    <div style="font-size:1.02rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      📊 Probabilistic Modeling & Extremes
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Normalizing flows, diffusion models, and other generative tools for learning 
      distributions, tail behavior, and uncertainty in mechanical and climate systems.
    </p>
  </div>

</div>


---

## AI for Science Projects

<style>
/* Shrink the project cards */
.ai4s-project-box {
  padding: 12px !important;
  border-radius: 14px !important;
  background: #E8F6FF !important;  /* Columbia Blue light */
  border: 1px solid #9BDDFF55;
  margin-bottom: 16px;
}

/* Make project titles smaller & cleaner */
.ai4s-project-title {
  font-size: 0.95rem !important;
  margin-bottom: 6px;
  color: #0055A4;
  font-weight: 600;
}

/* Compact descriptive text */
.ai4s-project-text {
  font-size: 0.88rem !important;
  line-height: 1.45 !important;
  margin: 0 !important;
}

/* Compact thumbnails */
.ai4s-project-thumb img {
  width: 70px !important;
  border-radius: 8px;
  box-shadow: 0 6px 14px rgba(0,85,164,0.18);
}

/* Make layout spacing nice */
.projects .row {
  row-gap: 16px !important;
}
</style>

<div class="projects">

{% assign sorted_projects = site.ai4science | sort: "importance" %}

{% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
      {% for project in sorted_projects %}
        <div class="col">
          <div class="ai4s-project-box">
            {% include projects_horizontal.liquid %}
          </div>
        </div>
      {% endfor %}
    </div>
  </div>
{% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      <div class="col">
        <div class="ai4s-project-box">
          {% include projects.liquid %}
        </div>
      </div>
    {% endfor %}
  </div>
{% endif %}

</div>


---

## Example Questions We Ask

- How can generative ML <strong>replace or augment ensembles</strong> for turbulent flows and heat transfer?  
- Can <strong>symbolic ML</strong> recover interpretable transport and scaling laws from large simulation or experimental datasets?  
- How do we combine <strong>data assimilation, generative models, and physical constraints</strong> to estimate unobserved states?  
- What is the most efficient way to use AI to <strong>design and operate cooling strategies</strong> for large data clusters?  
