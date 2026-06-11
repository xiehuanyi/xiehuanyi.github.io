---
layout: about
title: about
permalink: /
custom_home: true
subtitle: MS/PhD Student at <a href='https://www.kaust.edu.sa/'>King Abdullah University of Science and Technology (KAUST)</a>.

profile:
  align: right
  image: prof_pic_color.png
  image_circular: false
  more_info: >
    <p>KAUST, Saudi Arabia</p>
    <p>huanyi.xie@kaust.edu.sa</p>

selected_papers: true
social: true

announcements:
  enabled: false
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

<section class="home-hero" aria-label="Introduction">
  <div class="home-hero__copy">
    <p class="eyebrow">Computer Science MS/PhD Student at KAUST</p>
    <h1>Huanyi Xie</h1>
    <p class="home-hero__lead">
      I work on efficient training and inference for large language models, with a focus on LLM serving,
      memory-efficient fine-tuning, and data attribution.
    </p>
    <div class="home-hero__actions">
      <a class="button button-primary" href="{{ '/cv/' | relative_url }}">View CV</a>
      <a class="button button-secondary" href="https://github.com/xiehuanyi">GitHub</a>
      <a class="button button-secondary" href="mailto:huanyi.xie@kaust.edu.sa">Email</a>
    </div>
    <div class="home-hero__meta" aria-label="Research areas">
      <span>LLM serving</span>
      <span>Memory-efficient fine-tuning</span>
      <span>Data influence</span>
    </div>
  </div>

  <div class="home-hero__portrait">
    {% include figure.liquid loading="eager" path="assets/img/prof_pic_color.png" class="home-portrait" sizes="(min-width: 768px) 340px, 90vw" alt="Huanyi Xie" cache_bust=true %}
    <div class="portrait-caption">
      <strong>KAUST CS</strong>
      <span>Advised by Prof. Di Wang</span>
    </div>
  </div>
</section>

<section class="home-section">
  <div class="section-heading">
    <p class="eyebrow">Focus</p>
    <h2>Research and systems work</h2>
  </div>
  <div class="focus-grid">
    <article>
      <span class="focus-icon"><i class="fa-solid fa-server"></i></span>
      <h3>LLM serving</h3>
      <p>High-throughput inference systems with continuous batching, paged KV cache, streaming APIs, and request-level metrics.</p>
    </article>
    <article>
      <span class="focus-icon"><i class="fa-solid fa-memory"></i></span>
      <h3>Memory-efficient training</h3>
      <p>Zeroth-order and distributed fine-tuning methods for large language models under limited GPU memory.</p>
    </article>
    <article>
      <span class="focus-icon"><i class="fa-solid fa-diagram-project"></i></span>
      <h3>Data influence</h3>
      <p>Influence functions, selective annotation, and representation analysis for understanding data quality and model behavior.</p>
    </article>
  </div>
</section>

<section class="home-section">
  <div class="section-heading">
    <p class="eyebrow">Selected Work</p>
    <h2>Open-source projects</h2>
  </div>
  <div class="work-list">
    <article class="work-item">
      <div>
        <p class="work-kicker">LLM Serving Engine</p>
        <h3><a href="https://github.com/xiehuanyi/nanoSGLang">nanoSGLang</a></h3>
        <p>
          A compact Python/PyTorch serving engine implementing continuous batching, chunked prefill,
          paged attention, prefix-sharing radix cache, and streaming inference.
        </p>
      </div>
      <span class="work-metric">3469 tok/s on RTX A5000</span>
    </article>
    <article class="work-item">
      <div>
        <p class="work-kicker">Distributed Training Framework</p>
        <h3><a href="https://github.com/xiehuanyi/nanoMegatron">nanoMegatron</a></h3>
        <p>
          An educational distributed-training stack covering DDP, ZeRO, tensor parallelism,
          sequence parallelism, pipeline parallelism, and expert parallelism.
        </p>
      </div>
      <span class="work-metric">DDP / ZeRO / TP / PP / EP</span>
    </article>
  </div>
</section>

<section class="home-section home-timeline">
  <div class="section-heading">
    <p class="eyebrow">Path</p>
    <h2>Education</h2>
  </div>
  <ol>
    <li>
      <span>2025 - Present</span>
      <strong>KAUST</strong>
      <p>MS/PhD in Computer Science, advised by Prof. Di Wang.</p>
    </li>
    <li>
      <span>2024 - 2025</span>
      <strong>KTH Royal Institute of Technology</strong>
      <p>M.Sc. in Data Science.</p>
    </li>
    <li>
      <span>2020 - 2024</span>
      <strong>Harbin Institute of Technology, Weihai</strong>
      <p>B.Eng. in Artificial Intelligence.</p>
    </li>
  </ol>
</section>
