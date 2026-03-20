---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
description:
---

<div class="pub-list">

  <div class="pub-row">
    <div class="pub-thumb">
      <img src="/assets/img/gr.png" alt="Global Resolution teaser" data-zoomable>
    </div>
    <div class="pub-text">
      <div class="pub-title">Global Resolution: Optimal Multi-Draft Speculative Sampling via Convex Optimization</div>
      <div class="pub-authors"><u>Rahul Thomas</u>, Arka Pal</div>
      <div class="pub-venue"><em>International Conference on Learning Representations (ICLR), 2026. <strong> Oral.</strong></em></div>
      <div class="pub-links">
        <a class="pub-link-btn" href="https://openreview.net/forum?id=gpsczXOsHn">Paper</a>
        <a class="pub-link-btn" href="https://arxiv.org/abs/2511.15898">arXiv</a>
      </div>
    </div>
  </div>

  <div class="pub-row">
    <div class="pub-thumb">
      <img src="/assets/img/dyn.png" alt="Dynamic Delayed Tree Expansion teaser" data-zoomable>
    </div>
    <div class="pub-text">
      <div class="pub-title">Dynamic Delayed Tree Expansion for Improved Multi-Path Speculative Decoding</div>
      <div class="pub-authors"><u>Rahul Thomas</u>*, Teo Kitanovski*, Micah Goldblum, Arka Pal</div>
      <div class="pub-venue"><em>Preprint (under review), 2026.</em></div>
      <div class="pub-links">
        <a class="pub-link-btn" href="https://arxiv.org/abs/2602.16994">arXiv</a>
      </div>
    </div>
  </div>

  <div class="pub-row">
    <div class="pub-thumb">
      <img src="/assets/img/gbv.png" alt="Greedy Multi-Path Block Verification teaser" data-zoomable>
    </div>
    <div class="pub-text">
      <div class="pub-title">Greedy Multi-Path Block Verification for Faster Decoding in Speculative Sampling</div>
      <div class="pub-authors"><u>Rahul Thomas</u>, Arka Pal</div>
      <div class="pub-venue"><em>Preprint (under review), 2026.</em></div>
      <div class="pub-links">
        <a class="pub-link-btn" href="https://arxiv.org/abs/2602.16961">arXiv</a>
      </div>
    </div>
  </div>

  <div class="pub-row">
    <div class="pub-thumb">
      <img src="/assets/img/vma.png" alt="Hidden No More teaser" data-zoomable>
    </div>
    <div class="pub-text">
      <div class="pub-title">Hidden No More: Attacking and Defending Private Third-Party LLM Inference</div>
      <div class="pub-authors"><u>Rahul Thomas</u>, Louai Zahran, Erica Choi, Akilesh Potti, Micah Goldblum, Arka Pal</div>
      <div class="pub-venue"><em>International Conference on Machine Learning (ICML), 2025.</em></div>
      <div class="pub-links">
        <a class="pub-link-btn" href="https://proceedings.mlr.press/v267/thomas25b.html">Paper</a>
        <a class="pub-link-btn" href="https://arxiv.org/abs/2505.18332">arXiv [Attack]</a>
        <a class="pub-link-btn" href="https://arxiv.org/abs/2507.05228">arXiv [Defense]</a>
      </div>
    </div>
  </div>

  <div class="pub-row">
    <div class="pub-thumb">
      <img src="/assets/img/cad.png" alt="Img2CAD teaser" data-zoomable>
    </div>
    <div class="pub-text">
      <div class="pub-title">Img2CAD: Reverse Engineering 3D CAD Models from Images through VLM-Assisted Conditional Factorization</div>
      <div class="pub-authors">Yang You, Mikaela Angelina Uy, Jiaqi Han, <u>Rahul Thomas</u>, Haotong Zhang, Yi Du, Hansheng Chen, Francis Engelmann, Suya You, Leonidas Guibas</div>
      <div class="pub-venue"><em>SIGGRAPH Asia, 2025.</em></div>
      <div class="pub-links">
        <a class="pub-link-btn" href="https://dl.acm.org/doi/full/10.1145/3757377.3763891">Paper</a>
        <a class="pub-link-btn" href="https://qq456cvb.github.io/projects/img2cad">Project Page</a>
        <a class="pub-link-btn" href="https://arxiv.org/abs/2408.01437">arXiv</a>
      </div>
    </div>
  </div>

  <div class="pub-row">
    <div class="pub-thumb">
      <img src="/assets/img/nerf.png" alt="NeRF Revisited teaser" data-zoomable>
    </div>
    <div class="pub-text">
      <div class="pub-title">NeRF Revisited: Fixing Quadrature Instability in Volume Rendering</div>
      <div class="pub-authors">Mikaela Angelina Uy, Kiyohiro Nakayama, Guandao Yang, <u>Rahul Thomas</u>, Leonidas Guibas, Ke Li</div>
      <div class="pub-venue"><em>Conference on Neural Information Processing Systems (NeurIPS), 2023.</em></div>
      <div class="pub-links">
        <a class="pub-link-btn" href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/5301c49207917c5c870131959971851c-Abstract-Conference.html">Paper</a> 
        <a class="pub-link-btn" href="https://pl-nerf.github.io/">Project Page</a>
        <a class="pub-link-btn" href="https://arxiv.org/abs/2310.20685">arXiv</a>
      </div>
    </div>
  </div>

</div>

<style>
.pub-list {
  margin-top: 1rem;
}

.pub-row {
  display: flex;
  align-items: flex-start;
  gap: 1.25rem;
  margin-bottom: 1.75rem;
}

.pub-thumb {
  width: 180px;
  height: 120px;
  flex: 0 0 180px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: white;
}

.pub-thumb img {
  max-width: 100%;
  max-height: 100%;
  width: auto;
  height: auto;
  object-fit: contain;
  display: block;
}

.pub-text {
  flex: 1 1 auto;
  min-width: 0;
}

.pub-title {
  font-weight: 400;
  margin-bottom: 0.2rem;
}

.pub-authors {
  margin-bottom: 0.15rem;
}

.pub-venue {
  margin-bottom: 0.25rem;
}

.pub-desc {
  margin-bottom: 0.25rem;
}

/* .pub-links {
  margin-bottom: 0;
} */

.pub-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.45rem;
  margin-top: 0.2rem;
}

.pub-link-btn {
  display: inline-block;
  padding: 0.18rem 0.55rem;
  border: 1px solid #d0d0d0;
  border-radius: 6px;
  text-decoration: none;
  font-size: 0.92rem;
  line-height: 1.2;
}

.pub-link-btn:hover {
  text-decoration: none;
  border-color: #999;
}

@media (max-width: 700px) {
  .pub-row {
    flex-direction: column;
    gap: 0.75rem;
  }

  .pub-thumb,
  .pub-thumb img {
    width: 100%;
    max-width: 320px;
    height: auto;
  }
}
</style>