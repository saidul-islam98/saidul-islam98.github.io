---
layout: page
title: Work
permalink: /work/
description: Selected applied ML systems and research engineering work.
nav: true
nav_order: 2
---

<div class="publication-note">Each summary is grounded in my résumé or a linked public paper. Employer work is described only at a publicly disclosed level.</div>

<div class="work-grid">
  <article class="work-card">
    <p class="work-meta">Vector Institute · Foundation-model evaluation</p>
    <h2>Fine-Grained Benchmark Generation</h2>
    <p><strong>Problem.</strong> Foundation-model evaluations need grounded, technically demanding tasks with traceable quality controls.</p>
    <p><strong>Contribution.</strong> Built a reference-ingestion and OCR workflow and a multi-agent designer/verifier pipeline for generation, repair, trace-aware validation, and semantic deduplication.</p>
    <p><strong>Stack.</strong> Python, LLM agents, OCR, embeddings, semantic similarity, automated QA.</p>
    <div class="work-links"><a href="https://arxiv.org/abs/2605.18824">arXiv →</a></div>
  </article>

  <article class="work-card">
    <p class="work-meta">Vector Institute · Multimodal data</p>
    <h2>Open-PMC-18M data pipeline</h2>
    <p><strong>Problem.</strong> Compound medical figures require extraction of subfigures, captions, embedded subcaptions, and contextual summaries before they are useful for representation learning.</p>
    <p><strong>Contribution.</strong> Owned the extraction and preprocessing pipeline, optimized Qwen2.5-VL batched decoding from 4.0s to 1.2s per sample, and improved summary generation from 4.0s to 0.6s per sample.</p>
    <p><strong>Scale.</strong> The resulting pairs supported OpenCLIP training on 18M image–text pairs.</p>
    <p><strong>Stack.</strong> Python, Qwen2.5-VL, vLLM, A100 GPUs, multimodal QA.</p>
    <div class="work-links"><a href="https://arxiv.org/abs/2506.02738">arXiv →</a></div>
  </article>

  <article class="work-card">
    <p class="work-meta">EACL 2026 Main · Post-training</p>
    <h2>RL-Text2Vis</h2>
    <p><strong>Problem.</strong> Text-to-visualization systems can produce executable code while still generating semantically incorrect or visually poor charts.</p>
    <p><strong>Contribution.</strong> Co-developed a GRPO framework whose multi-objective reward evaluates the textual answer, code execution, and rendered visualization after execution.</p>
    <p><strong>Result.</strong> The public paper reports improved code executability and chart quality over strong prompting and supervised baselines.</p>
    <p><strong>Stack.</strong> GRPO, Qwen2.5, VLM feedback, code execution, visualization evaluation.</p>
    <div class="work-links"><a href="https://aclanthology.org/2026.eacl-long.317/">Paper →</a><a href="https://github.com/vis-nlp/RL-Text2Vis">Code →</a></div>
  </article>

  <article class="work-card">
    <p class="work-meta">EACL 2026 Findings · Multimodal agents</p>
    <h2>DashboardQA</h2>
    <p><strong>Problem.</strong> Static chart benchmarks do not capture the planning and GUI interactions required to answer questions over real dashboards.</p>
    <p><strong>Contribution.</strong> Co-created a benchmark covering real interactive dashboards and documented agent failures in grounding, planning, interaction, and visual reasoning.</p>
    <p><strong>Stack.</strong> GUI agents, VLM evaluation, multimodal reasoning, benchmark QA.</p>
    <div class="work-links"><a href="https://aclanthology.org/2026.findings-eacl.177/">Paper →</a><a href="https://github.com/vis-nlp/DashboardQA">Project →</a></div>
  </article>

  <article class="work-card">
    <p class="work-meta">ACL 2025 Findings · Benchmarking</p>
    <h2>ChartQAPro</h2>
    <p><strong>Problem.</strong> Existing chart QA benchmarks underrepresent the diversity and difficulty of real-world visualizations.</p>
    <p><strong>Contribution.</strong> Co-created a benchmark of 1,341 charts and 1,948 questions and evaluated 21 open- and closed-source vision-language models.</p>
    <p><strong>Stack.</strong> VLM evaluation, data curation, robustness testing, error analysis.</p>
    <div class="work-links"><a href="https://aclanthology.org/2025.findings-acl.978/">Paper →</a><a href="https://github.com/vis-nlp/ChartQAPro">Project →</a></div>
  </article>

  <article class="work-card">
    <p class="work-meta">ACL & EMNLP 2025 Industry Tracks · Efficient evaluation</p>
    <h2>Large and tiny VLM judges</h2>
    <p><strong>Problem.</strong> Automated chart-model evaluation must be reliable, unbiased, and affordable enough for practical deployment.</p>
    <p><strong>Contribution.</strong> Evaluated compact VLM judges in point-wise and pair-wise protocols and trained a 2B judge model that matched a 7B baseline while reducing inference latency.</p>
    <p><strong>Stack.</strong> VLM-as-judge, reward modeling, robustness analysis, transfer learning.</p>
    <div class="work-links"><a href="https://aclanthology.org/2025.acl-industry.83/">ACL paper →</a><a href="https://aclanthology.org/2025.emnlp-industry.134/">EMNLP paper →</a></div>
  </article>

  <article class="work-card">
    <p class="work-meta">EMNLP 2024 Main · Agentic generation</p>
    <h2>DataNarrative</h2>
    <p><strong>Problem.</strong> Producing coherent data stories requires understanding, planning, narration, visual grounding, and iterative verification.</p>
    <p><strong>Contribution.</strong> Built an Actor–Critic-style workflow for planning, reflection, narration, and revision and helped create a benchmark of 1,449 real-world data stories.</p>
    <p><strong>Stack.</strong> Multi-agent LLMs, data storytelling, benchmark construction, human evaluation.</p>
    <div class="work-links"><a href="https://aclanthology.org/2024.emnlp-main.1073/">Paper →</a></div>
  </article>
</div>
