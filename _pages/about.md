---
layout: default
title: Home
seo_title: Mohammed Saidul Islam - Applied ML Systems
permalink: /
description: Applied ML specialist at the Vector Institute building computer-use agents, LLM/VLM evaluation systems, multimodal data pipelines, post-training systems, and efficient model inference.
keywords: applied machine learning, computer-use agents, data-science workflows, multimodal evaluation, ML systems
nav: false
---

<div class="portfolio-home">
  <section class="portfolio-hero" aria-labelledby="hero-title">
    <div class="hero-copy">
      <p class="hero-kicker">Applied ML Specialist · Vector Institute · Toronto</p>
      <h1 id="hero-title">Building AI agents and efficient multimodal systems.</h1>
      <p class="hero-lede">I build evaluation pipelines, multimodal data systems, and optimized GPU inference for foundation models.</p>
      <div class="hero-actions" aria-label="Contact and résumé">
        <a class="portfolio-button primary" href="{{ '/assets/pdf/resume.pdf' | relative_url }}">View résumé</a>
        <a class="portfolio-button secondary" href="mailto:saidulislam143.si@gmail.com">Email me</a>
      </div>
      <div class="hero-links hero-professional-links" aria-label="Professional profiles">
        <a href="https://github.com/saidul-islam98">GitHub <span aria-hidden="true">↗</span></a>
        <a href="https://www.linkedin.com/in/mohammed-saidul-islam-0331b2135">LinkedIn <span aria-hidden="true">↗</span></a>
        <a href="https://scholar.google.com/citations?user=3Pb203IAAAAJ&hl=en">Scholar <span aria-hidden="true">↗</span></a>
      </div>
    </div>
    <div class="hero-portrait">
      <img src="{{ '/assets/img/saidul-profile-hero.webp' | relative_url }}" alt="Portrait of Mohammed Saidul Islam" width="960" height="960" fetchpriority="high">
    </div>
    <dl class="hero-results" aria-label="Selected engineering results">
      <div><dt>VLM extraction latency</dt><dd>4.0s <span aria-label="reduced to">→</span> 1.2s<span class="result-context">per sample · <span class="result-model">Qwen2.5-VL</span></span></dd></div>
      <div><dt>Summary generation latency</dt><dd>4.0s <span aria-label="reduced to">→</span> 0.6s<span class="result-context">per sample · batched inference</span></dd></div>
      <div><dt>Multimodal training data</dt><dd>18M<span class="result-context">image-text pairs · OpenCLIP</span></dd></div>
    </dl>
    <article class="hero-latest" aria-labelledby="latest-work-title">
      <p class="hero-latest-label">Latest <span>NeurIPS 2026 E&amp;D Track</span></p>
      <div>
        <h2 id="latest-work-title">FLAME</h2>
        <p>Fine-Grained Benchmark Generation for Comprehensive Evaluation of Foundation Models.</p>
      </div>
      <div class="work-links">
        <a href="https://arxiv.org/abs/2605.18824">Paper <span aria-hidden="true">↗</span></a>
      </div>
      <p class="hero-latest-stats">Accepted at NeurIPS 2026 <span aria-hidden="true">·</span> Evaluations &amp; Datasets Track</p>
    </article>
  </section>

  <section class="portfolio-section updates-section" aria-labelledby="updates-heading">
    <div class="section-heading">
      <div>
        <p class="section-marker">Now</p>
        <h2 id="updates-heading">Recent milestones</h2>
      </div>
      <p>Recent publication and career updates.</p>
    </div>
    {% include news.liquid limit=true %}
    <div class="section-action"><a class="text-link" href="{{ '/news/' | relative_url }}">View all news <span aria-hidden="true">→</span></a></div>
  </section>

  <section class="portfolio-section selected-work-section" aria-labelledby="featured-heading">
    <div class="section-heading">
      <div>
        <p class="section-marker">Selected work</p>
        <h2 id="featured-heading">Selected engineering work</h2>
      </div>
      <p>What I built, how it works, and the results.</p>
    </div>
    {% assign selected_projects = site.data.portfolio | where: 'homepage', true | sort: 'homepage_order' %}
    <div class="work-grid">
      {% for project in selected_projects %}
        {% include portfolio/project-card.liquid project=project card_class="work-card" home=true %}
      {% endfor %}
    </div>
    <div class="section-action"><a class="text-link" href="{{ '/work/' | relative_url }}">Explore all technical work <span aria-hidden="true">→</span></a></div>
  </section>

  <section class="portfolio-section career-section" aria-labelledby="career-heading">
    <div class="section-heading">
      <div>
        <p class="section-marker">Career</p>
        <h2 id="career-heading">Experience and education</h2>
      </div>
      <p>Roles in applied ML research, engineering, and teaching.</p>
    </div>
    <div class="portfolio-timeline">
      <article class="timeline-item"><p class="timeline-date">2025-Present</p><div><h3>Vector Institute</h3><p>Associate Applied Machine Learning Specialist · Toronto</p><p class="timeline-detail">Foundation-model evaluation, multimodal data pipelines, and GPU inference.</p></div></article>
      <article class="timeline-item"><p class="timeline-date">2023-2025</p><div><h3>Intelligent Visualization Lab, York University</h3><p>Graduate Research Assistant · Toronto</p><p class="timeline-detail">Agent workflows, chart reasoning, and interactive dashboard evaluation.</p></div></article>
      <article class="timeline-item"><p class="timeline-date">2021-2023</p><div><h3>Islamic University of Technology</h3><p>Lecturer · Bangladesh</p></div></article>
    </div>
    <div class="education-snapshot"><span>MSc Computer Science - York University</span><span>BSc Computer Science and Engineering - Islamic University of Technology</span></div>
    <div class="section-action"><a class="text-link" href="{{ '/experience/' | relative_url }}">View full experience <span aria-hidden="true">→</span></a></div>
  </section>

  <section class="portfolio-section home-publications-section" aria-labelledby="publications-heading">
    <div class="section-heading">
      <div>
        <p class="section-marker">Research</p>
        <h2 id="publications-heading">Selected publications</h2>
      </div>
      <p>Recent work on AI agents, multimodal evaluation, data storytelling, and reliable generation.</p>
    </div>
    {% include selected_papers.liquid compact=true %}
    <div class="section-action"><a class="text-link" href="{{ '/publications/' | relative_url }}">All publications <span aria-hidden="true">→</span></a></div>
  </section>

  <section class="portfolio-section contact-section" aria-labelledby="contact-heading">
    <div class="contact-panel">
      <div><p class="section-marker">Contact</p><h2 id="contact-heading">Let’s talk about ML engineering.</h2></div>
      <div class="hero-links">
        <a class="portfolio-button primary" href="mailto:saidulislam143.si@gmail.com">Email me</a>
        <a href="https://www.linkedin.com/in/mohammed-saidul-islam-0331b2135">LinkedIn</a>
        <a href="https://github.com/saidul-islam98">GitHub</a>
        <a href="https://scholar.google.com/citations?user=3Pb203IAAAAJ&hl=en">Scholar</a>
      </div>
    </div>
  </section>
</div>
