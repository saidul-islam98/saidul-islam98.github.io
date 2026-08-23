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
      <p class="hero-kicker">Applied machine learning</p>
      <h1 id="hero-title">Building reliable AI agents, multimodal systems, and model evaluation infrastructure.</h1>
      <p class="hero-lede">At the Vector Institute, I turn applied ML research into production-ready systems, from benchmark design and model training to deployment and evaluation.</p>
      <div class="hero-links" aria-label="Professional links">
        <a class="portfolio-button primary" href="{{ '/assets/pdf/resume.pdf' | relative_url }}">Résumé</a>
        <a href="https://github.com/saidul-islam98">GitHub</a>
        <a href="https://scholar.google.com/citations?user=3Pb203IAAAAJ&hl=en">Scholar</a>
        <a href="https://www.linkedin.com/in/mohammed-saidul-islam-0331b2135">LinkedIn</a>
        <a href="mailto:saidulislam143.si@gmail.com">Email</a>
      </div>
      <ul class="hero-proof" aria-label="Areas of expertise">
        <li>Efficient Inference</li>
        <li>LLM Evaluation</li>
        <li>AI Agents</li>
        <li>Post-Training</li>
        <li>Multimodal AI</li>
      </ul>
    </div>
    <div class="hero-portrait">
      <img src="{{ '/assets/img/saidul-profile-hero.webp' | relative_url }}" alt="Portrait of Mohammed Saidul Islam" width="960" height="1200" fetchpriority="high">
    </div>
    <article class="hero-latest" aria-labelledby="latest-work-title">
      <p class="hero-latest-label">Latest <span>EMNLP 2026 Main</span></p>
      <div>
        <h2 id="latest-work-title">DSAgentBench</h2>
        <p>Can agents automate end-to-end data-science workflows in real computer environments?</p>
      </div>
      <p class="hero-latest-stats">275 tasks <span aria-hidden="true">·</span> 15 models <span aria-hidden="true">·</span> deterministic evaluators <span aria-hidden="true">·</span> 56.70% best result</p>
      <div class="work-links">
        <a href="https://arxiv.org/abs/2608.10366">Paper <span aria-hidden="true">↗</span></a>
        <a href="https://github.com/vis-nlp/DSAgentBench">Code <span aria-hidden="true">↗</span></a>
      </div>
    </article>
  </section>

  <section class="portfolio-section selected-work-section" aria-labelledby="featured-heading">
    <div class="section-heading">
      <div>
        <p class="section-marker">Selected work</p>
        <h2 id="featured-heading">Selected systems and benchmarks</h2>
      </div>
      <p>Projects across agent evaluation, multimodal learning, post-training, and visualization.</p>
    </div>
    {% assign selected_projects = site.data.portfolio | where: 'homepage', true | sort: 'homepage_order' %}
    <div class="work-grid">
      {% for project in selected_projects %}
        {% include portfolio/project-card.liquid project=project card_class="work-card" home=true %}
      {% endfor %}
    </div>
    <div class="section-action"><a class="text-link" href="{{ '/work/' | relative_url }}">Explore all technical work <span aria-hidden="true">→</span></a></div>
  </section>

  <section class="portfolio-section home-publications-section" aria-labelledby="publications-heading">
    <div class="section-heading">
      <div>
        <p class="section-marker">Research</p>
        <h2 id="publications-heading">Selected publications</h2>
      </div>
      <p>Recent work on AI agents, multimodal evaluation, data storytelling, and reliable generation.</p>
    </div>
    {% include selected_papers.liquid %}
    <div class="section-action"><a class="text-link" href="{{ '/publications/' | relative_url }}">All publications <span aria-hidden="true">→</span></a></div>
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
      <article class="timeline-item"><p class="timeline-date">2025-Present</p><div><h3>Vector Institute</h3><p>Associate Applied Machine Learning Specialist · Toronto</p></div></article>
      <article class="timeline-item"><p class="timeline-date">2023-2025</p><div><h3>Intelligent Visualization Lab, York University</h3><p>Graduate Research Assistant · Toronto</p></div></article>
      <article class="timeline-item"><p class="timeline-date">2021-2023</p><div><h3>Islamic University of Technology</h3><p>Lecturer · Bangladesh</p></div></article>
    </div>
    <div class="education-snapshot"><span>MSc Computer Science - York University</span><span>BSc Computer Science and Engineering - Islamic University of Technology</span></div>
    <div class="section-action"><a class="text-link" href="{{ '/experience/' | relative_url }}">View full experience <span aria-hidden="true">→</span></a></div>
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

  <section class="portfolio-section service-section" aria-labelledby="service-heading">
    <div class="section-heading">
      <div>
        <p class="section-marker">Service</p>
        <h2 id="service-heading">Leadership and reviewing</h2>
      </div>
      <p>President of the Bangladeshi Graduate Student Association at York and reviewer for NeurIPS, ACL, EMNLP, COLM, NAACL, and ACL Rolling Review.</p>
    </div>
    <div class="section-action"><a class="text-link" href="{{ '/experience/' | relative_url }}">Experience and service details <span aria-hidden="true">→</span></a></div>
  </section>

  <section class="portfolio-section contact-section" aria-labelledby="contact-heading">
    <div class="contact-panel">
      <div><p class="section-marker">Contact</p><h2 id="contact-heading">Get in touch about applied AI, agents, evaluation, or multimodal systems.</h2></div>
      <div class="hero-links">
        <a class="portfolio-button primary" href="mailto:saidulislam143.si@gmail.com">Email</a>
        <a href="https://www.linkedin.com/in/mohammed-saidul-islam-0331b2135">LinkedIn</a>
        <a href="https://github.com/saidul-islam98">GitHub</a>
        <a href="https://scholar.google.com/citations?user=3Pb203IAAAAJ&hl=en">Scholar</a>
      </div>
    </div>
  </section>
</div>
