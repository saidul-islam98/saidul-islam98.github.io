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
      <p class="project-impact">Reference ingestion, generation, verification, repair, and semantic deduplication in one traceable workflow.</p>
      <dl class="project-details">
        <div><dt>Problem</dt><dd>Foundation-model evaluations need difficult tasks with reliable source grounding and quality controls.</dd></div>
        <div><dt>Contribution</dt><dd>Built OCR-based ingestion and a multi-agent designer/verifier workflow with iterative repair and trace-aware validation.</dd></div>
        <div><dt>Stack</dt><dd>Python, LLM agents, OCR, embeddings, semantic similarity, automated QA.</dd></div>
      </dl>
      <div class="work-links"><a href="https://arxiv.org/abs/2605.18824">arXiv <span aria-hidden="true">↗</span></a></div>
    </article>

    <article class="project-card">
      <p class="project-meta">Vector Institute · Multimodal data · 2025</p>
      <h3>Open-PMC-18M data pipeline</h3>
      <p class="project-summary">A large-scale extraction and preprocessing workflow for compound medical figures and their textual context.</p>
      <p class="project-impact">Reduced batched decoding from 4.0s to 1.2s and summary generation from 4.0s to 0.6s per sample.</p>
      <dl class="project-details">
        <div><dt>Problem</dt><dd>Medical figures must be decomposed into subfigures, captions, embedded subcaptions, and useful contextual summaries.</dd></div>
        <div><dt>Contribution</dt><dd>Owned the preprocessing pipeline and optimized Qwen2.5-VL inference supporting OpenCLIP training on 18M pairs.</dd></div>
        <div><dt>Stack</dt><dd>Python, Qwen2.5-VL, vLLM, A100 GPUs, multimodal QA.</dd></div>
      </dl>
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
      <dl class="project-details">
        <div><dt>Problem</dt><dd>Executable visualization code can still produce semantically incorrect or visually poor charts.</dd></div>
        <div><dt>Contribution</dt><dd>Co-developed a multi-objective reward covering textual answers, execution, and rendered visualizations.</dd></div>
        <div><dt>Stack</dt><dd>GRPO, Qwen2.5, VLM feedback, code execution, visualization evaluation.</dd></div>
      </dl>
      <div class="work-links"><a href="https://aclanthology.org/2026.eacl-long.317/">Paper <span aria-hidden="true">↗</span></a><a href="https://github.com/vis-nlp/RL-Text2Vis">Code <span aria-hidden="true">↗</span></a></div>
    </article>

    <article class="project-card">
      <p class="project-meta">EACL 2026 Findings · Multimodal agents</p>
      <h3>DashboardQA</h3>
      <p class="project-summary">A benchmark for agents answering questions through real interactive dashboards.</p>
      <p class="project-impact">Reveals failures in visual grounding, planning, GUI interaction, and multi-view reasoning.</p>
      <dl class="project-details">
        <div><dt>Problem</dt><dd>Static chart benchmarks miss the planning and interaction required by real dashboards.</dd></div>
        <div><dt>Contribution</dt><dd>Co-created the benchmark and analyzed agent behavior across the complete interaction loop.</dd></div>
        <div><dt>Stack</dt><dd>GUI agents, VLM evaluation, multimodal reasoning, benchmark QA.</dd></div>
      </dl>
      <div class="work-links"><a href="https://aclanthology.org/2026.findings-eacl.177/">Paper <span aria-hidden="true">↗</span></a><a href="https://github.com/vis-nlp/DashboardQA">Project <span aria-hidden="true">↗</span></a></div>
    </article>

    <article class="project-card">
      <p class="project-meta">ACL 2025 Findings · Benchmarking</p>
      <h3>ChartQAPro</h3>
      <p class="project-summary">A challenging chart-question-answering benchmark designed around diverse real-world visualizations.</p>
      <p class="project-impact">1,341 charts, 1,948 questions, and evaluation of 21 open- and closed-source VLMs.</p>
      <dl class="project-details">
        <div><dt>Problem</dt><dd>Existing chart QA benchmarks underrepresent real-world chart diversity and difficulty.</dd></div>
        <div><dt>Contribution</dt><dd>Co-created the dataset, evaluation protocol, and systematic model error analysis.</dd></div>
        <div><dt>Stack</dt><dd>VLM evaluation, data curation, robustness testing, error analysis.</dd></div>
      </dl>
      <div class="work-links"><a href="https://aclanthology.org/2025.findings-acl.978/">Paper <span aria-hidden="true">↗</span></a><a href="https://github.com/vis-nlp/ChartQAPro">Project <span aria-hidden="true">↗</span></a></div>
    </article>

    <article class="project-card">
      <p class="project-meta">ACL & EMNLP 2025 Industry Tracks · Evaluation</p>
      <h3>Large and tiny VLM judges</h3>
      <p class="project-summary">Reliable and efficient automated evaluation protocols for chart models.</p>
      <p class="project-impact">A 2B judge matched a 7B baseline while reducing inference latency.</p>
      <dl class="project-details">
        <div><dt>Problem</dt><dd>Model evaluation must be accurate, unbiased, and affordable enough for practical use.</dd></div>
        <div><dt>Contribution</dt><dd>Evaluated compact judges in point-wise and pair-wise settings and trained an efficient 2B judge.</dd></div>
        <div><dt>Stack</dt><dd>VLM-as-judge, reward modeling, robustness analysis, transfer learning.</dd></div>
      </dl>
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
      <dl class="project-details">
        <div><dt>Problem</dt><dd>Coherent data stories require coordinated understanding, narration, visual grounding, and verification.</dd></div>
        <div><dt>Contribution</dt><dd>Built the multi-agent planning and revision workflow and helped create the evaluation benchmark.</dd></div>
        <div><dt>Stack</dt><dd>Multi-agent LLMs, data storytelling, benchmark construction, human evaluation.</dd></div>
      </dl>
      <div class="work-links"><a href="https://aclanthology.org/2024.emnlp-main.1073/">Paper <span aria-hidden="true">↗</span></a></div>
    </article>
  </div>
</section>
