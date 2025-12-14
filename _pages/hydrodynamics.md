---
layout: page
title: Hydrodynamics
permalink: /hydrodynamics/
description: Physical Explanation and Modeling of Wind, Water and Sediment Dynamics
nav: true
nav_order: 3
horizontal: false
---

<style>
.hydrodynamics-page,
.hydrodynamics-page * {
  font-family: "Inter", "Helvetica Neue", Arial, sans-serif;
  color: #0F172A;
}

/* ===== Section titles (big-font, non-bold) ===== */
.hydrodynamics-page .section-title {
  font-size: 2.2rem;
  font-weight: 400;
  line-height: 1.3;
  margin: 32px 0 14px 0;
  color: #0F172A;
}

.hydrodynamics-page .section-title-sm {
  font-size: 1.75rem;
  font-weight: 400;
  line-height: 1.3;
  margin: 28px 0 12px 0;
  color: #0F172A;
}

/* Label style */
.hydrodynamics-page .section-label {
  font-size: 0.85rem;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: #0055A4;
  font-weight: 600;
  margin-bottom: 8px;
}

/* Card titles */
.hydrodynamics-page .card-title {
  font-size: 1.02rem;
  font-weight: 600;
  margin-bottom: 6px;
  color: #0055A4;
}

/* Body text */
.hydrodynamics-page p,
.hydrodynamics-page li {
  font-size: 0.95rem;
  line-height: 1.6;
}

.hydrodynamics-page strong {
  font-weight: 650;
  color: #0F172A;
}

.hydrodynamics-page a {
  color: #0055A4;
  text-decoration: none;
}
.hydrodynamics-page a:hover {
  color: #003B73;
  text-decoration: underline;
}

/* Divider */
.hydrodynamics-page .soft-hr {
  border: 0;
  height: 1px;
  background: linear-gradient(
    90deg,
    rgba(155,221,255,0.0),
    rgba(155,221,255,0.75),
    rgba(155,221,255,0.0)
  );
  margin: 26px 0;
}

/* Project cards */
.hydro-image-card {
  background: linear-gradient(135deg, rgba(232,246,255,0.92), rgba(243,251,255,0.92));
  border-radius:16px;
  padding:14px;
  border:1px solid rgba(155,221,255,0.40);
  box-shadow:0 10px 22px rgba(0,85,164,0.10);
  transition: transform 0.12s ease, box-shadow 0.12s ease;
  text-align:center;
  height:100%;
}
.hydro-image-card:hover {
  transform: translateY(-2px);
  box-shadow:0 14px 28px rgba(0,85,164,0.14);
}
.hydro-image-card img {
  width:100%;
  max-width:220px;
  border-radius:12px;
  box-shadow:0 6px 14px rgba(0,85,164,0.18);
}
.projects .row { row-gap:18px !important; }
</style>

<div class="hydrodynamics-page">

<!-- ===============================
     Hero
     =============================== -->
<div style="
  background: linear-gradient(135deg, #E8F6FF 0%, #C9E8FF 100%);
  border-radius: 18px;
  padding: 36px 32px;
  margin-bottom: 22px;
  border: 1px solid #9BDDFF88;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 26px;
">

  <div style="flex:1 1 330px; min-width:280px;">
    <div class="section-label">Research Theme</div>

    <h1 style="margin:0 0 14px 0; font-size:2.1rem; line-height:1.2; font-weight:650;">
      Wind–Water–Sediment Dynamics
    </h1>

    <p style="margin:0 0 12px 0; font-size:1rem; line-height:1.65;">
      We develop <strong>physics-first hydrodynamic models</strong> that connect
      <strong>turbulence, roughness, and multiscale transport</strong> to predict
      sediment suspension, scour/deposition, and flow–ecosystem interactions
      shaping rivers, coasts, and engineered channels.
    </p>

    <div style="display:flex; flex-wrap:wrap; gap:10px; margin-top:12px;">
      <span style="background:#9BDDFF; border-radius:999px; padding:6px 14px; font-size:0.82rem; font-weight:600; color:#003366;">
        Turbulence & Roughness
      </span>
      <span style="background:#B3E5FC; border-radius:999px; padding:6px 14px; font-size:0.82rem; font-weight:600; color:#004B87;">
        Sediment Transport
      </span>
      <span style="background:#D9F2FF; border-radius:999px; padding:6px 14px; font-size:0.82rem; font-weight:600; color:#003B66;">
        Scour & Deposition
      </span>
      <span style="background:#E0F2FE; border-radius:999px; padding:6px 14px; font-size:0.82rem; font-weight:600; color:#02416E;">
        Vegetated Flows
      </span>
    </div>
  </div>

  <div style="flex:0 0 260px; text-align:center;">
    <img src="/assets/img/turbulence-bulk-transport.png"
         alt="Hydrodynamics"
         style="max-width:240px; width:100%; border-radius:18px;
                box-shadow:0 16px 30px rgba(0,85,164,0.26);" />
  </div>

</div>

<hr class="soft-hr" />

<!-- ===============================
     Meaning
     =============================== -->
<div class="section-title">
  What does “Hydrodynamics” mean in our group?
</div>

<p>
  In our work, <strong>hydrodynamics is a bridge</strong> between turbulence physics and real-world transport:
  how momentum, energy, particles, and scalars move through rivers, wetlands, and coastal systems.
</p>

<ul>
  <li>deriving <strong>transport laws</strong> from turbulence budgets and spectra</li>
  <li>quantifying how <strong>roughness and vegetation</strong> reshape flow structure</li>
  <li>predicting <strong>suspension, settling, scour, and deposition</strong></li>
  <li>building models that are <strong>interpretable, scalable, and validated</strong></li>
</ul>

<p>
  Rather than relying on empirical correlations alone, we connect observations to mechanisms
  so models remain reliable under <strong>nonstationary forcing</strong> and
  <strong>climate-driven extremes</strong>.
</p>

<hr class="soft-hr" />

<!-- ===============================
     Projects
     =============================== -->
<div class="section-title-sm">
  What projects are we working on?
</div>

<div class="projects">
  {% assign sorted_projects = site.hydrodynamics | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
    <div class="col">
      <a href="{{ project.url | relative_url }}" style="text-decoration:none;">
        <div class="hydro-image-card">
          <img src="{{ project.img | relative_url }}" alt="{{ project.title }}">
        </div>
      </a>
    </div>
    {% endfor %}
  </div>
</div>

<hr class="soft-hr" />

<!-- ===============================
     Example questions
     =============================== -->
<div class="section-title-sm">
  Example questions we ask
</div>

<ul>
  <li>What is the minimal turbulence physics needed to predict <strong>bulk sediment transport</strong>?</li>
  <li>When do classical models break, and what replaces them?</li>
  <li>How do <strong>roughness and vegetation</strong> reorganize effective diffusivities?</li>
  <li>Can we derive <strong>universal scaling laws</strong> stable under climate change?</li>
  <li>How do we build models that are both <strong>field-validated</strong> and <strong>deployment-ready</strong>?</li>
</ul>

<hr class="soft-hr" />

<!-- ===============================
     Core directions
     =============================== -->
<div class="section-title-sm">
  Core research directions
</div>

<div style="
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:20px;
  margin:24px 0 10px 0;
">

  <div style="background:#E8F6FF; border-radius:16px; padding:16px;">
    <div class="card-title">🌀 Turbulence → bulk transport laws</div>
    <p style="margin:0;">First-principles links between turbulence energetics and sediment transport.</p>
  </div>

  <div style="background:#F0FAFF; border-radius:16px; padding:16px;">
    <div class="card-title">🧱 Walls, roughness, and dissipation</div>
    <p style="margin:0;">Mechanistic explanations of friction-factor transitions.</p>
  </div>

  <div style="background:#E7F3FF; border-radius:16px; padding:16px;">
    <div class="card-title">🌿 Vegetation–flow–transport coupling</div>
    <p style="margin:0;">From canopy-scale turbulence to field-scale outcomes.</p>
  </div>

  <div style="background:#F1FAFF; border-radius:16px; padding:16px;">
    <div class="card-title">⚗️ Settling, suspension, multiscale turbulence</div>
    <p style="margin:0;">When classical settling theories succeed or fail.</p>
  </div>

</div>

</div>