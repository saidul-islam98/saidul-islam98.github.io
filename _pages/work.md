---
layout: page
title: Work
permalink: /work/
description: Selected applied ML systems and research engineering work in agents, multimodal systems, post-training, and evaluation.
nav: true
nav_order: 2
---

{% assign projects = site.data.portfolio | sort: 'work_order' %}

<section class="project-section" aria-labelledby="agents-evaluation">
  <div class="project-section-heading">
    <p class="section-marker">Agents and evaluation</p>
    <h2 id="agents-evaluation">Agentic systems and reliable evaluation</h2>
    <p>Benchmarks, computer-use agents, and evaluation protocols for foundation models.</p>
  </div>
  <div class="project-grid">
    {% for project in projects %}
      {% if project.category == 'agents-evaluation' %}
        {% include portfolio/project-card.liquid project=project card_class="project-card" %}
      {% endif %}
    {% endfor %}
  </div>
</section>

<section class="project-section" aria-labelledby="multimodal-systems">
  <div class="project-section-heading">
    <p class="section-marker">Multimodal systems</p>
    <h2 id="multimodal-systems">Data pipelines and visual reasoning</h2>
    <p>Large-scale multimodal data preparation and rigorous chart understanding benchmarks.</p>
  </div>
  <div class="project-grid">
    {% for project in projects %}
      {% if project.category == 'multimodal-systems' %}
        {% include portfolio/project-card.liquid project=project card_class="project-card" %}
      {% endif %}
    {% endfor %}
  </div>
</section>

<section class="project-section" aria-labelledby="post-training-generation">
  <div class="project-section-heading">
    <p class="section-marker">Post-training and generation</p>
    <h2 id="post-training-generation">Executable and data-driven generation</h2>
    <p>Feedback-driven post-training and agentic workflows for visualization and narrative generation.</p>
  </div>
  <div class="project-grid">
    {% for project in projects %}
      {% if project.category == 'post-training-generation' %}
        {% include portfolio/project-card.liquid project=project card_class="project-card" %}
      {% endif %}
    {% endfor %}
  </div>
</section>
