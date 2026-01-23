---
layout: page
permalink: /publications/
title: Publications
description: Publications by category in reverse chronological order.
nav: true
nav_order: 4
---

<!-- ===============================
     Publications — Page-scoped typography/color unification + hero header
     =============================== -->
<style>
.publications-page,
.publications-page * {
  font-family: "Inter", "Helvetica Neue", Arial, sans-serif;
  color: #0F172A;
}

/* Headings */
.publications-page h1,
.publications-page h2,
.publications-page h3 {
  font-weight: 650;
  color: #0F172A;
}

/* Section label (small caps) */
.publications-page .section-label {
  font-size: 0.85rem;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: #0055A4;
  font-weight: 600;
  margin-bottom: 8px;
}

/* Section title (big, lighter weight — consistent with your preference) */
.publications-page .section-title {
  font-size: 2.2rem;
  font-weight: 400;
  line-height: 1.3;
  margin: 0 0 8px 0;
  color: #0F172A;
}

/* Lead text */
.publications-page .lead {
  margin: 0;
  font-size: 1rem;
  line-height: 1.65;
}

/* Nice divider */
.publications-page .soft-hr {
  border: 0;
  height: 1px;
  background: linear-gradient(
    90deg,
    rgba(155,221,255,0.0),
    rgba(155,221,255,0.75),
    rgba(155,221,255,0.0)
  );
  margin: 24px 0;
}

/* Links */
.publications-page a {
  color: #0055A4;
  text-decoration: none;
}
.publications-page a:hover {
  color: #003B73;
  text-decoration: underline;
}

/* Bibsearch box + inputs (best-effort, robust selectors) */
.publications-page input,
.publications-page select,
.publications-page textarea {
  font-family: inherit;
  color: #0F172A;
  border-radius: 12px;
  border: 1px solid rgba(155,221,255,0.55);
  background: linear-gradient(135deg, rgba(232,246,255,0.72), rgba(243,251,255,0.72));
  padding: 10px 12px;
  outline: none;
  box-shadow: 0 8px 18px rgba(0,85,164,0.06);
}
.publications-page input:focus,
.publications-page select:focus,
.publications-page textarea:focus {
  border-color: rgba(0,85,164,0.45);
  box-shadow: 0 10px 22px rgba(0,85,164,0.10);
}

/* Publications container card */
.publications-page .pub-card {
  background: linear-gradient(135deg, rgba(232,246,255,0.55), rgba(243,251,255,0.55));
  border: 1px solid rgba(155,221,255,0.45);
  border-radius: 16px;
  padding: 18px 18px;
  box-shadow: 0 10px 22px rgba(0,85,164,0.08);
}

/* jekyll-scholar output — best-effort styling across common classnames */
.publications-page .bibliography,
.publications-page .publications,
.publications-page ol.bibliography {
  margin: 0;
  padding-left: 0;
  list-style: none;
}

.publications-page .bibliography li,
.publications-page ol.bibliography > li {
  background: rgba(255,255,255,0.62);
  border: 1px solid rgba(155,221,255,0.40);
  border-radius: 14px;
  padding: 14px 14px;
  margin: 0 0 12px 0;
  box-shadow: 0 8px 18px rgba(0,85,164,0.05);
}

/* Title/author lines (varies by theme; keep readable) */
.publications-page .bibliography .title,
.publications-page .bibliography .pub-title,
.publications-page .bibliography .entry-title {
  font-weight: 650;
  color: #0F172A;
}

.publications-page .bibliography .author,
.publications-page .bibliography .authors {
  color: #0F172A;
  opacity: 0.92;
}

/* Year / venue often appear in small spans */
.publications-page .bibliography .year,
.publications-page .bibliography .journal,
.publications-page .bibliography .venue {
  color: #0F172A;
  opacity: 0.85;
}

/* Buttons / links inside each entry (PDF, DOI, code, etc.) */
.publications-page .bibliography a {
  color: #0055A4;
}
</style>

<div class="publications-page">

<div style="
  background: linear-gradient(135deg, #E8F6FF 0%, #C9E8FF 100%);
  border-radius: 18px;
  padding: 28px 26px;
  margin-bottom: 18px;
  border: 1px solid #9BDDFF88;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 16px;
">
  <div style="flex: 1 1 420px; min-width: 280px;">
    <div class="section-label">In Preparation</div>

    <ul style="
      margin: 0;
      padding-left: 18px;
      font-size: 0.95rem;
      line-height: 1.55;
    ">
      <li style="margin-bottom:8px;">
        <strong> [1] Li, S.</strong>,  Katul, G., Zheng, T., Gentine, P.
        “Universality of Daily Variability and Annual Extreme Heat in Global Summer Temperatures”, to be submitted (2026).
      </li>

      <li style="margin-bottom:8px;">
        <strong> [2] Li, S.</strong>, Katul, G., Zheng, T., Gentine, P.
        “Landcover structure explains shift of heat extreme under climate change”, under review (2025).
      </li>

      <li style="margin-bottom:0;">
        <strong> [3] Li, S.</strong>, Pathz, T., Katul, G.
        “Suspended sediment transport in turbulence: From eddy energetics to bulk flow.”
        <em>Physical Review Letters</em>, under review (2nd round, 2025).
      </li>

      <li style="margin-bottom:8px;">
        <strong> [4] Hou, Z.</strong>, Sun, J., Jin, P., <strong>Li, S.</strong><sup>*</sup>, Zheng, T.
        “Calibrating Geophysical Predictions under Constrained Probabilistic Distributions via Kernelized Stein Discrepancy.”
        <em> ARC: Geophysical Research</em>, submitted (2025).
      </li>
    </ul>
  </div>
</div>

<hr class="soft-hr" />

<!-- ===============================
     Bibsearch Feature
     =============================== -->
{% include bib_search.liquid %}

<hr class="soft-hr" />

<!-- ===============================
     Bibliography
     =============================== -->
<div class="pub-card">
  <div class="publications">
    {% bibliography %}
  </div>
</div>

</div>