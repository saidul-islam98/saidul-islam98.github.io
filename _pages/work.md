---
layout: page
title: Work
permalink: /work/
description: Selected applied ML systems and research engineering work.
nav: true
nav_order: 2
---

<section class="project-section" aria-labelledby="industry-systems">
  <div class="project-section-heading">
    <p class="section-marker">Applied ML</p>
    <h2 id="industry-systems">Industry systems</h2>
    <p>Production-oriented systems for foundation-model evaluation, multimodal data, and efficient inference.</p>
  </div>
  <div class="project-grid">
    <article class="project-card">
      <p class="project-meta">Vector Institute · Foundation-model evaluation · 2026</p>
      <h3>Fine-Grained Benchmark Generation</h3>
      <p class="project-summary">An automated system for building grounded, technically demanding evaluation tasks from reference material.</p>
      <p class="project-impact">Built OCR ingestion and a multi-agent designer/verifier workflow with repair, validation, and semantic deduplication.</p>
      <div class="work-links"><a href="https://arxiv.org/abs/2605.18824">arXiv <span aria-hidden="true">↗</span></a></div>
    </article>

    <article class="project-card">
      <p class="project-meta">Vector Institute · Multimodal data · 2025</p>
      <h3>Open-PMC-18M data pipeline</h3>
      <p class="project-summary">A large-scale extraction and preprocessing workflow for compound medical figures and their textual context.</p>
      <p class="project-impact">Owned preprocessing and cut Qwen2.5-VL decoding from 4.0s to 1.2s and summary generation from 4.0s to 0.6s per sample.</p>
      <div class="work-links"><a href="https://arxiv.org/abs/2506.02738">arXiv <span aria-hidden="true">↗</span></a></div>
    </article>

  </div>
</section>

<section class="project-section" aria-labelledby="research-systems">
  <div class="project-section-heading">
    <p class="section-marker">Research engineering</p>
    <h2 id="research-systems">Research systems and benchmarks</h2>
    <p>Post-training, interactive agents, robust evaluation, and visualization intelligence.</p>
  </div>
  <div class="project-grid">
    <article class="project-card">
      <p class="project-meta">EACL 2026 Main · Post-training</p>
      <h3>RL-Text2Vis</h3>
      <p class="project-summary">A GRPO framework that evaluates text-to-visualization outputs after code execution.</p>
      <p class="project-impact">Improves code executability and chart quality over strong prompting and supervised baselines.</p>
      <div class="work-links"><a href="https://aclanthology.org/2026.eacl-long.317/">Paper <span aria-hidden="true">↗</span></a><a href="https://github.com/vis-nlp/RL-Text2Vis">Code <span aria-hidden="true">↗</span></a></div>
    </article>

    <article class="project-card">
      <p class="project-meta">EACL 2026 Findings · Multimodal agents</p>
      <h3>DashboardQA</h3>
      <p class="project-summary">A benchmark for agents answering questions through real interactive dashboards.</p>
      <p class="project-impact">Co-created it to expose failures in visual grounding, planning, GUI interaction, and multi-view reasoning.</p>
      <div class="work-links"><a href="https://aclanthology.org/2026.findings-eacl.177/">Paper <span aria-hidden="true">↗</span></a><a href="https://github.com/vis-nlp/DashboardQA">Project <span aria-hidden="true">↗</span></a></div>
    </article>

    <article class="project-card">
      <p class="project-meta">ACL 2025 Findings · Benchmarking</p>
      <h3>ChartQAPro</h3>
      <p class="project-summary">A challenging chart-question-answering benchmark designed around diverse real-world visualizations.</p>
      <p class="project-impact">Co-created 1,341 charts and 1,948 questions used to evaluate 21 open- and closed-source VLMs.</p>
      <div class="work-links"><a href="https://aclanthology.org/2025.findings-acl.978/">Paper <span aria-hidden="true">↗</span></a><a href="https://github.com/vis-nlp/ChartQAPro">Project <span aria-hidden="true">↗</span></a></div>
    </article>

    <article class="project-card">
      <p class="project-meta">ACL & EMNLP 2025 Industry Tracks · Evaluation</p>
      <h3>Large and tiny VLM judges</h3>
      <p class="project-summary">Reliable and efficient automated evaluation protocols for chart models.</p>
      <p class="project-impact">A 2B judge matched a 7B baseline while reducing inference latency.</p>
      <div class="work-links"><a href="https://aclanthology.org/2025.acl-industry.83/">ACL paper <span aria-hidden="true">↗</span></a><a href="https://aclanthology.org/2025.emnlp-industry.134/">EMNLP paper <span aria-hidden="true">↗</span></a></div>
    </article>

  </div>
</section>

<section class="project-section" aria-labelledby="earlier-research">
  <div class="project-section-heading">
    <p class="section-marker">Foundation</p>
    <h2 id="earlier-research">Earlier research</h2>
  </div>
  <div class="project-grid project-grid-single">
    <article class="project-card">
      <p class="project-meta">EMNLP 2024 Main · Agentic generation</p>
      <h3>DataNarrative</h3>
      <p class="project-summary">An Actor–Critic-style workflow for planning, reflecting on, and revising data-driven stories with visualizations.</p>
      <p class="project-impact">Introduced a benchmark of 1,449 real-world data stories for system and human evaluation.</p>
      <div class="work-links"><a href="https://aclanthology.org/2024.emnlp-main.1073/">Paper <span aria-hidden="true">↗</span></a></div>
    </article>
  </div>
</section>
