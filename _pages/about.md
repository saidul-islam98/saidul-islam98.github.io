---
layout: default
title: Home
permalink: /
description: Applied ML specialist building reliable systems for multimodal and agentic AI.
nav: false
---

<div class="portfolio-home">
  <section class="portfolio-hero" aria-labelledby="hero-title">
    <div class="hero-copy">
      <p class="hero-kicker">Mohammed Saidul Islam · Vector Institute</p>
      <h1 id="hero-title">Building reliable ML systems for multimodal and agentic AI.</h1>
      <p class="hero-lede">I design scalable data pipelines, automated evaluation systems, multimodal workflows, and efficient model-inference infrastructure.</p>
      <div class="hero-actions">
        <a class="portfolio-button primary" href="{{ '/work/' | relative_url }}">View selected work</a>
        <a class="portfolio-button secondary" href="{{ '/assets/pdf/resume.pdf' | relative_url }}">Download résumé</a>
      </div>
    </div>
    <div class="hero-portrait">
      <img src="{{ '/assets/img/saidul-profile-hero.webp' | relative_url }}" alt="Mohammed Saidul Islam wearing a graduation cap and gown" width="960" height="1200" fetchpriority="high">
    </div>
  </section>

  <section class="portfolio-section" aria-labelledby="about-heading">
    <div class="section-intro reading-width">
      <p class="section-marker">Expertise</p>
      <h2 id="about-heading">What I work on</h2>
      <p>I am an Associate Applied Machine Learning Specialist at the Vector Institute, working across modular Python systems, large-scale preprocessing, agentic LLM/VLM workflows, post-training, evaluation, and reproducible inference on Linux and HPC.</p>
      <p>My research interests include multimodal reasoning, visualization intelligence, trustworthy model evaluation, and agentic AI. I am currently exploring <strong>mechanistic interpretability in vision-language models</strong>.</p>
    </div>
    <div class="expertise-grid">
      <article class="expertise-card">
        <h3>ML systems engineering</h3>
        <p>Scalable Python pipelines, automated data quality, profiling, reproducibility, and deployment-oriented GPU inference.</p>
      </article>
      <article class="expertise-card">
        <h3>Agentic and multimodal AI</h3>
        <p>LLM/VLM workflows, multimodal data processing, planning and reflection, post-training, and tool-augmented generation.</p>
      </article>
      <article class="expertise-card">
        <h3>Evaluation and reliability</h3>
        <p>Benchmark construction, robustness testing, model-as-judge protocols, error analysis, and failure-mode tracking.</p>
      </article>
    </div>
  </section>

  <section class="portfolio-section" aria-labelledby="featured-heading">
    <div class="section-heading">
      <div>
        <p class="section-marker">Selected work</p>
        <h2 id="featured-heading">Featured systems</h2>
      </div>
      <p>Applied ML and research systems spanning foundation-model evaluation, multimodal agents, and visualization intelligence.</p>
    </div>
    <div class="work-grid">
      <article class="work-card">
        <p class="work-meta">Vector Institute · 2026 preprint</p>
        <h3>Fine-Grained Benchmark Generation</h3>
        <p>A reference-grounded multi-agent pipeline for generating, verifying, repairing, and deduplicating technically demanding evaluation tasks.</p>
        <p class="work-impact">Trace-aware quality control from source ingestion through final benchmark validation.</p>
        <div class="work-links"><a href="https://arxiv.org/abs/2605.18824">Paper <span aria-hidden="true">↗</span></a></div>
      </article>
      <article class="work-card">
        <p class="work-meta">EACL 2026 · Main</p>
        <h3>RL-Text2Vis</h3>
        <p>A GRPO post-training framework using post-execution feedback across textual correctness, code executability, and visualization quality.</p>
        <p class="work-impact">Improves executable code generation and rendered chart quality over strong baselines.</p>
        <div class="work-links"><a href="https://aclanthology.org/2026.eacl-long.317/">Paper <span aria-hidden="true">↗</span></a><a href="https://github.com/vis-nlp/RL-Text2Vis">Code <span aria-hidden="true">↗</span></a></div>
      </article>
      <article class="work-card">
        <p class="work-meta">EACL 2026 · Findings</p>
        <h3>DashboardQA</h3>
        <p>A benchmark for multimodal agents that must ground questions, plan interactions, operate real dashboards, and reason across views.</p>
        <p class="work-impact">Surfaces practical failures in grounding, planning, interaction, and visual reasoning.</p>
        <div class="work-links"><a href="https://aclanthology.org/2026.findings-eacl.177/">Paper <span aria-hidden="true">↗</span></a><a href="https://github.com/vis-nlp/DashboardQA">Project <span aria-hidden="true">↗</span></a></div>
      </article>
    </div>
    <div class="section-action"><a class="text-link" href="{{ '/work/' | relative_url }}">Explore all technical work <span aria-hidden="true">→</span></a></div>
  </section>

  <section class="portfolio-section" aria-labelledby="career-heading">
    <div class="section-heading">
      <div>
        <p class="section-marker">Career</p>
        <h2 id="career-heading">Experience</h2>
      </div>
      <p>A path from teaching software fundamentals to building applied multimodal ML systems.</p>
    </div>
    <div class="portfolio-timeline">
      <article class="timeline-item"><p class="timeline-date">Sep 2025 — present</p><div><h3>Vector Institute</h3><p>Associate Applied Machine Learning Specialist · Toronto</p></div></article>
      <article class="timeline-item"><p class="timeline-date">Sep 2023 — Aug 2025</p><div><h3>Intelligent Visualization Lab, York University</h3><p>Graduate Research Assistant · Toronto</p></div></article>
      <article class="timeline-item"><p class="timeline-date">Jul 2021 — Aug 2023</p><div><h3>Islamic University of Technology</h3><p>Lecturer · Bangladesh</p></div></article>
    </div>
    <div class="section-action"><a class="text-link" href="{{ '/experience/' | relative_url }}">View full experience <span aria-hidden="true">→</span></a></div>
  </section>

  <section class="portfolio-section updates-section" aria-labelledby="updates-heading">
    <div class="section-heading">
      <div>
        <p class="section-marker">Milestones</p>
        <h2 id="updates-heading">Recent updates</h2>
      </div>
      <p>Selected career and publication milestones.</p>
    </div>
    {% include news.liquid limit=true %}
  </section>

  <section class="portfolio-section contact-section" aria-labelledby="contact-heading">
    <div class="contact-panel">
      <div><p class="section-marker">Contact</p><h2 id="contact-heading">Let’s connect</h2><p>Email is the best way to reach me. You can also explore my work on GitHub and Google Scholar.</p></div>
      <div class="hero-actions">
        <a class="portfolio-button primary" href="mailto:saidulislam143.si@gmail.com">Email me</a>
        <a class="portfolio-button secondary" href="https://scholar.google.com/citations?user=3Pb203IAAAAJ&hl=en">Google Scholar</a>
      </div>
    </div>
  </section>
</div>
