---
layout: page
title: Hydrodynamics
permalink: /hydrodynamics/
description: Physical Explanation and Modeling of Wind, Water and Sediment Dynamics
nav: true
nav_order: 3
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
      Hydrodynamics: Wind–Water–Sediment Dynamics
    </h1>

    <p style="margin: 0 0 12px 0; font-size: 1rem; line-height: 1.65;">
      We develop <strong>physics-first hydrodynamic models</strong> that connect
      <strong>turbulence, roughness, and multiscale transport</strong> to predict
      sediment suspension, scour/deposition, and the flow–ecosystem interactions that
      shape rivers, coasts, and engineered channels.
    </p>

    <!-- Columbia Blue Tags -->
    <div style="display:flex; flex-wrap:wrap; gap:10px; margin-top:12px;">

      <span style="background:#9BDDFF; color:#003366;
                   border-radius:999px; padding:6px 14px;
                   font-size:0.82rem; font-weight:600;">
        Turbulence & Roughness
      </span>

      <span style="background:#B3E5FC; color:#004B87;
                   border-radius:999px; padding:6px 14px;
                   font-size:0.82rem; font-weight:600;">
        Sediment Transport
      </span>

      <span style="background:#D9F2FF; color:#003B66;
                   border-radius:999px; padding:6px 14px;
                   font-size:0.82rem; font-weight:600;">
        Scour & Deposition
      </span>

      <span style="background:#E0F2FE; color:#02416E;
                   border-radius:999px; padding:6px 14px;
                   font-size:0.82rem; font-weight:600;">
        Vegetated Flows
      </span>

    </div>
  </div>

  <div style="flex:0 0 260px; text-align:center; min-width:240px;">
    <img src="/assets/img/turbulence-bulk-transport.png"
         alt="Hydrodynamics"
         style="
           max-width: 240px;
           width: 100%;
           border-radius: 18px;
           box-shadow: 0 16px 30px rgba(0,85,164,0.26);
         " />
  </div>

</div>

---

## What does “Hydrodynamics” mean in our group?

In our work, <strong>hydrodynamics is a bridge</strong> between turbulence physics and real-world transport:
how momentum, energy, particles, and scalars move through rivers, wetlands, and coastal systems.

We focus on:

- deriving <strong>transport laws</strong> from turbulence budgets and spectra  
- quantifying how <strong>roughness and vegetation</strong> reshape flow structure and mixing  
- predicting <strong>suspension, settling, scour, and deposition</strong> across regimes  
- building models that remain <strong>interpretable</strong>, <strong>scalable</strong>, and <strong>validated</strong>  

Rather than relying only on empirical correlations, we aim to connect observations to mechanisms—so models
remain reliable under <strong>nonstationary forcing</strong> and <strong>climate-driven extremes</strong>.

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
      🌀 Turbulence → bulk transport laws
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      First-principles links between turbulence energetics (TKE, stress budgets, spectra) and
      bulk sediment transport—yielding <strong>universal scaling</strong> across datasets.
    </p>
  </div>

  <div style="background:#F0FAFF; border-radius:16px; padding:16px;">
    <div style="font-size:1.02rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      🧱 Walls, roughness, and dissipation
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Mechanistic models of wall friction and roughness transitions that explain classical
      friction-factor diagrams from turbulence theory.
    </p>
  </div>

  <div style="background:#E7F3FF; border-radius:16px; padding:16px;">
    <div style="font-size:1.02rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      🌿 Vegetation–flow–transport coupling
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      How structured roughness (canopies, wetlands) reorganizes velocity, stresses, and mixing—linking
      microscale turbulence to <strong>field-scale contaminant and sediment outcomes</strong>.
    </p>
  </div>

  <div style="background:#F1FAFF; border-radius:16px; padding:16px;">
    <div style="font-size:1.02rem; font-weight:600; margin-bottom:6px; color:#0055A4;">
      ⚗️ Settling, suspension, and multiscale turbulence
    </div>
    <p style="margin:0; font-size:0.95rem; line-height:1.55;">
      Theory for particle settling and suspension in turbulence, clarifying when classical
      assumptions (e.g., still-water settling, Rouse limits) succeed or fail.
    </p>
  </div>

</div>

---

## Hydrodynamics Projects

<style>
/* Shrink the project cards */
.hydro-project-box {
  padding: 12px !important;
  border-radius: 14px !important;
  background: #E8F6FF !important;  /* Columbia Blue light */
  border: 1px solid #9BDDFF55;
  margin-bottom: 16px;
}

/* Make project titles smaller & cleaner */
.hydro-project-title {
  font-size: 0.95rem !important;
  margin-bottom: 6px;
  color: #0055A4;
  font-weight: 600;
}

/* Compact descriptive text */
.hydro-project-text {
  font-size: 0.88rem !important;
  line-height: 1.45 !important;
  margin: 0 !important;
}

/* Compact thumbnails */
.hydro-project-thumb img {
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

{% assign sorted_projects = site.hydrodynamics | sort: "importance" %}

{% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
      {% for project in sorted_projects %}
        <div class="col">
          <div class="hydro-project-box">
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
        <div class="hydro-project-box">
          {% include projects.liquid %}
        </div>
      </div>
    {% endfor %}
  </div>
{% endif %}

</div>

---

## Example Questions We Ask

- What is the minimal turbulence physics needed to predict <strong>bulk sediment transport</strong> across regimes?  
- When do classical models (e.g., mixing-length closures, Rouse theory) break, and what replaces them?  
- How do <strong>roughness and vegetation</strong> reorganize flow structure and effective diffusivities?  
- Can we derive <strong>universal scaling laws</strong> that remain stable under climate-driven changes in forcing?  
- How do we build models that are both <strong>field-validated</strong> and <strong>deployment-ready</strong> for infrastructure resilience?  