---
layout: default
title: Home
permalink: /
description: Applied ML specialist building reliable systems for foundation-model evaluation and multimodal AI.
nav: false
---

<div class="portfolio-home">
  <section class="portfolio-hero" aria-labelledby="hero-title">
    <div>
      <p class="eyebrow">Associate Applied Machine Learning Specialist · Vector Institute</p>
      <h1 id="hero-title">Building reliable, scalable ML systems for foundation models and multimodal AI.</h1>
      <p class="hero-lede">I build end-to-end machine learning systems—from large-scale data and OCR pipelines to agentic LLM/VLM workflows, model evaluation, and optimized GPU inference.</p>
      <div class="hero-actions">
        <a class="portfolio-button primary" href="{{ '/work/' | relative_url }}">View technical work</a>
        <a class="portfolio-button secondary" href="{{ '/publications/' | relative_url }}">Publications</a>
        <a class="portfolio-button secondary" href="{{ '/assets/pdf/resume.pdf' | relative_url }}">Download résumé</a>
      </div>
    </div>
    <div class="hero-portrait">
      <img src="{{ '/assets/img/saidul-profile.webp' | relative_url }}" alt="Portrait of Mohammed Saidul Islam" width="680" height="850" fetchpriority="high">
    </div>
  </section>

  <section class="portfolio-section" aria-labelledby="about-heading">
    <div class="section-heading">
      <h2 id="about-heading">What I work on</h2>
      <div>
        <p>I am an Associate Applied Machine Learning Specialist at the Vector Institute. I work across modular Python systems, large-scale preprocessing, agentic LLM/VLM workflows, post-training and evaluation, and reproducible inference on Linux/HPC.</p>
        <p>My research interests include multimodal reasoning, visualization intelligence, trustworthy model evaluation, and agentic AI. I am currently exploring <strong>mechanistic interpretability in vision-language models</strong>.</p>
      </div>
    </div>
    <div class="expertise-grid">
      <article class="expertise-card">
        <h3>ML systems engineering</h3>
        <p>Modular Python, scalable pipelines, automated data quality checks, profiling, reproducibility, and deployment-oriented inference.</p>
      </article>
      <article class="expertise-card">
        <h3>Generative and agentic AI</h3>
        <p>LLM/VLM workflows, planning and reflection, tool-augmented generation, SFT, DPO, GRPO, and human-in-the-loop evaluation.</p>
      </article>
      <article class="expertise-card">
        <h3>Evaluation and reliability</h3>
        <p>Benchmark construction, robustness testing, model-as-judge protocols, error analysis, regression comparisons, and failure-mode tracking.</p>
      </article>
      <article class="expertise-card">
        <h3>Multimodal data and inference</h3>
        <p>OCR, medical image-text processing, semantic deduplication, PyTorch, Hugging Face, DeepSpeed, vLLM, Slurm, and Vertex AI.</p>
      </article>
    </div>
  </section>

  <section class="portfolio-section" aria-labelledby="impact-heading">
    <div class="section-heading">
      <h2 id="impact-heading">Engineering impact</h2>
      <p>Selected outcomes from work described in my résumé and public research.</p>
    </div>
    <div class="metric-row">
      <div class="metric"><strong>70%</strong><span>faster batched subcaption inference on A100s</span></div>
      <div class="metric"><strong>85%</strong><span>faster multimodal summary generation</span></div>
      <div class="metric"><strong>18M</strong><span>medical image–text pairs supported for OpenCLIP training</span></div>
    </div>
  </section>

  <section class="portfolio-section" aria-labelledby="featured-heading">
    <div class="section-heading">
      <h2 id="featured-heading">Featured systems</h2>
      <p>Applied ML and research systems spanning foundation-model evaluation, multimodal agents, visualization, and efficient inference.</p>
    </div>
    <div class="work-grid">
      <article class="work-card">
        <p class="work-meta">Vector Institute · 2026 preprint</p>
        <h3>Fine-Grained Benchmark Generation</h3>
        <p>An automated multi-agent pipeline that grounds evaluation tasks in technical references, performs trace-aware verification and iterative repair, and removes near-duplicates using semantic filtering.</p>
        <div class="work-links"><a href="https://arxiv.org/abs/2605.18824">Paper →</a></div>
      </article>
      <article class="work-card">
        <p class="work-meta">EACL 2026 · Main</p>
        <h3>RL-Text2Vis</h3>
        <p>A GRPO-based post-training framework using post-execution feedback across textual correctness, code executability, and visualization quality.</p>
        <div class="work-links"><a href="https://aclanthology.org/2026.eacl-long.317/">Paper →</a><a href="https://github.com/vis-nlp/RL-Text2Vis">Code →</a></div>
      </article>
      <article class="work-card">
        <p class="work-meta">EACL 2026 · Findings</p>
        <h3>DashboardQA</h3>
        <p>A benchmark for evaluating multimodal agents on interactive dashboard question answering, including grounding, planning, GUI interaction, and multi-view reasoning.</p>
        <div class="work-links"><a href="https://aclanthology.org/2026.findings-eacl.177/">Paper →</a><a href="https://github.com/vis-nlp/DashboardQA">Project →</a></div>
      </article>
      <article class="work-card">
        <p class="work-meta">ACL 2025 · Findings</p>
        <h3>ChartQAPro</h3>
        <p>A diverse chart-question-answering benchmark with 1,341 charts and 1,948 questions, used to evaluate 21 open- and closed-source models.</p>
        <div class="work-links"><a href="https://aclanthology.org/2025.findings-acl.978/">Paper →</a><a href="https://github.com/vis-nlp/ChartQAPro">Project →</a></div>
      </article>
    </div>
    <div class="hero-actions"><a class="portfolio-button secondary" href="{{ '/work/' | relative_url }}">Explore all technical work</a></div>
  </section>

  <section class="portfolio-section" aria-labelledby="career-heading">
    <div class="section-heading">
      <h2 id="career-heading">Experience</h2>
      <p>A path from teaching software fundamentals to building applied multimodal ML systems.</p>
    </div>
    <div class="portfolio-timeline">
      <article class="timeline-item"><p class="timeline-date">Sep 2025 — present</p><div><h3>Vector Institute</h3><p>Associate Applied Machine Learning Specialist · Toronto</p></div></article>
      <article class="timeline-item"><p class="timeline-date">Sep 2023 — Aug 2025</p><div><h3>Intelligent Visualization Lab, York University</h3><p>Graduate Research Assistant · Toronto</p></div></article>
      <article class="timeline-item"><p class="timeline-date">Jul 2021 — Aug 2023</p><div><h3>Islamic University of Technology</h3><p>Lecturer · Bangladesh</p></div></article>
    </div>
    <div class="hero-actions"><a class="portfolio-button secondary" href="{{ '/experience/' | relative_url }}">Full experience</a></div>
  </section>

  <section class="portfolio-section" aria-labelledby="updates-heading">
    <div class="section-heading"><h2 id="updates-heading">Recent updates</h2><p>Selected career and publication milestones.</p></div>
    {% include news.liquid %}
  </section>

  <section class="portfolio-section">
    <div class="contact-panel">
      <div><h2>Let’s connect</h2><p>Email is the best way to reach me. You can also find my work on GitHub and Google Scholar.</p></div>
      <div class="hero-actions">
        <a class="portfolio-button primary" href="mailto:saidulislam143.si@gmail.com">Email me</a>
        <a class="portfolio-button secondary" href="https://scholar.google.com/citations?user=3Pb203IAAAAJ&hl=en">Google Scholar</a>
      </div>
    </div>
    <p style="margin-top: 1.5rem; color: var(--p-muted);">Outside work, I enjoy technical and general-interest podcasts, reading articles, and playing video games.</p>
  </section>
</div>
