---
layout: page
title: ai4science
permalink: /ai4science/
description: Climate Modeling with Generative AI
nav: true
nav_order: 3
horizontal: false
---

<!-- pages/ai4science.md -->
<div class="projects">

<!-- Display projects without categories -->

{% assign sorted_projects = site.ai4science | sort: "importance" %}

  <!-- Generate cards for each project -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
</div>
