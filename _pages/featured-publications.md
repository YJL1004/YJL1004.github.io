---
layout: archive
title: "Selected Publications"
permalink: /featured-publications/
author_profile: true
---

<style>
  .featured-publications,
  .featured-publications h2,
  .featured-publications h3,
  .featured-publications p,
  .featured-publications a {
    font-family: "Times New Roman", Times, serif;
  }

  .featured-publications {
    color: #23384d;
    font-size: 18px;
    line-height: 1.45;
  }

  @media (min-width: 925px) {
    #main {
      max-width: 1640px;
    }

    .page {
      width: 84%;
      padding-left: 1.5%;
      padding-right: 0;
    }
  }

  .featured-intro {
    margin: 0.8em 0 1.4em;
    padding: 0.9em 1.1em;
    border-left: 5px solid #2f9be8;
    border-radius: 8px;
    background: #eaf5ff;
    color: #183653;
  }

  .featured-publications h2 {
    margin: 1.35em 0 0.85em;
    padding-bottom: 0.28em;
    border-bottom: 2px solid #2f9be8;
    color: #23384d;
    font-size: 1.45em;
    font-weight: 700;
  }

  .featured-paper {
    display: grid;
    grid-template-columns: minmax(220px, 34%) 1fr;
    margin: 0 0 1.35em;
    border: 1px solid #e6edf5;
    border-radius: 10px;
    background: #fff;
    box-shadow: 0 8px 24px rgba(31, 79, 149, 0.08);
    overflow: hidden;
  }

  .featured-paper__visual {
    position: relative;
    display: flex;
    flex-direction: column;
    padding: 0.95em;
    background: #f1f7ff;
    border-right: 1px solid #e1ebf7;
  }

  .featured-paper__image {
    display: block;
    width: 100%;
    max-height: 260px;
    margin: auto;
    border-radius: 6px;
    object-fit: contain;
    background: #fff;
  }

  .featured-paper__placeholder {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100%;
    min-height: 188px;
    margin: auto 0;
    border: 2px dashed #9fc7ee;
    border-radius: 8px;
    color: #2b6aa0;
    font-size: 0.92em;
    text-align: center;
  }

  .featured-paper__badge {
    align-self: flex-start;
    margin: 0 0 0.65em;
    padding: 0.25em 0.75em;
    border-radius: 999px;
    background: #2f9be8;
    color: #fff;
    font-size: 0.78em;
    font-weight: 700;
  }

  .featured-paper__body {
    padding: 1.1em 1.35em;
  }

  .featured-paper h3 {
    margin: 0 0 0.52em;
    color: #073b76;
    font-size: 1.18em;
    font-weight: 700;
    line-height: 1.25;
  }

  .featured-paper__authors {
    margin: 0 0 0.45em;
    color: #203e5f;
    font-weight: 700;
  }

  .featured-paper__venue {
    margin: 0 0 0.8em;
    color: #203e5f;
    font-style: italic;
  }

  .featured-paper__summary {
    margin: 0 0 1em;
    color: #23384d;
  }

  .featured-paper__links a {
    display: inline-flex;
    align-items: center;
    gap: 0.28em;
    margin: 0 0.45em 0.35em 0;
    padding: 0.24em 0.68em;
    border: 1px solid #d7e4f4;
    border-radius: 5px;
    background: #f7fbff;
    color: #1f4f95;
    font-size: 0.9em;
    font-weight: 700;
    text-decoration: none;
  }

  .featured-paper__links a:hover {
    background: #eaf3ff;
  }

  .featured-paper__links .pdf-link i {
    color: #b21f2d;
  }

  @media (max-width: 760px) {
    .featured-paper {
      grid-template-columns: 1fr;
    }

    .featured-paper__visual {
      border-right: 0;
      border-bottom: 1px solid #e1ebf7;
    }
  }
</style>

<div class="featured-publications">
  <div class="featured-intro">
    Selected papers are grouped by research area, with representative figures and links to the corresponding papers.
  </div>

  <h2>Multimodal Sentiment Analysis</h2>
  <article class="featured-paper">
    <div class="featured-paper__visual">
      <span class="featured-paper__badge">Information Fusion 2026</span>
      <img class="featured-paper__image" src="/images/Salience-Guided.png" alt="Salience-Guided paper figure">
    </div>
    <div class="featured-paper__body">
      <h3>Salience-Guided Counterfactual Framework for Multimodal Sentiment Analysis</h3>
      <p class="featured-paper__authors"><strong>Jiali You</strong>, Haoran Li, Jiawen Deng, Wei Li, Yuanyuan He, Fuji Ren</p>
      <p class="featured-paper__venue">Information Fusion 2026 (JCR Q1, IF=15.5)</p>
      <p class="featured-paper__summary">This work introduces a salience-guided counterfactual framework to strengthen multimodal sentiment understanding by focusing on informative cross-modal evidence.</p>
      <p class="featured-paper__links"><a class="pdf-link" href="https://www.sciencedirect.com/science/article/abs/pii/S1566253526004653"><i class="fas fa-file-pdf" aria-hidden="true"></i> PDF</a></p>
    </div>
  </article>

  <h2>Multi-view Clustering</h2>
    <article class="featured-paper">
    <div class="featured-paper__visual">
      <span class="featured-paper__badge">TNNLS 2024</span>
            <img class="featured-paper__image" src="/images/LVSC.png" alt="LVSC paper figure">
    </div>
    <div class="featured-paper__body">
      <h3>LSVC: A lifelong learning approach for stream-view clustering</h3>
      <p class="featured-paper__authors">Haoran Li, Zhenwen Ren, Yifan Guo, <strong>Jiali You</strong>, Xiaojian You</p>
      <p class="featured-paper__venue">IEEE Transactions on Neural Networks and Learning Systems 2024 (JCR Q1, IF=8.9)</p>
      <p class="featured-paper__summary">This study addresses stream-view clustering under evolving views and lifelong learning settings.</p>
      <p class="featured-paper__links"><a class="code-link" href="https://github.com/haoranli50/LSVC"><i class="fab fa-github" aria-hidden="true"></i> Code</a><a class="pdf-link" href="https://doi.org/10.1109/TNNLS.2024.3439394"><i class="fas fa-file-pdf" aria-hidden="true"></i> PDF</a></p>
    </div>
  </article>



  <article class="featured-paper">
    <div class="featured-paper__visual">
      <span class="featured-paper__badge">TNNLS 2023</span>
      <img class="featured-paper__image" src="/images/One-stage.png" alt="One-stage paper figure">
    </div>
    <div class="featured-paper__body">
      <h3>One-stage shifted Laplacian refining for multiple kernel clustering</h3>
      <p class="featured-paper__authors"><strong>Jiali You</strong>, Zhenwen Ren, F. Richard Yu, Xiaojian You</p>
      <p class="featured-paper__venue">IEEE Transactions on Neural Networks and Learning Systems 2023 (JCR Q1, IF=8.9)</p>
      <p class="featured-paper__summary">This work develops a one-stage shifted Laplacian refining strategy to improve multiple kernel clustering with a more compact optimization process.</p>
      <p class="featured-paper__links"><a class="pdf-link" href="https://ieeexplore.ieee.org/abstract/document/10091844"><i class="fas fa-file-pdf" aria-hidden="true"></i> PDF</a></p>
    </div>
  </article>


  <article class="featured-paper">
    <div class="featured-paper__visual">
      <span class="featured-paper__badge">AAAI 2023</span>
         <img class="featured-paper__image" src="/images/Priori-Anchor.png" alt="Priori-Anchor paper figure">
    </div>
    <div class="featured-paper__body">
      <h3>Priori anchor labels supervised scalable multi-view bipartite graph clustering</h3>
      <p class="featured-paper__authors"><strong>Jiali You</strong>, Zhenwen Ren, Xiaojian You, Haoran Li, Yuancheng Yao</p>
      <p class="featured-paper__venue">AAAI 2023 (CCF-A)</p>
      <p class="featured-paper__summary">This work introduces priori anchor label supervision into scalable multi-view bipartite graph clustering for efficient and effective multi-view learning.</p>
      <p class="featured-paper__links"><a class="pdf-link" href="https://ojs.aaai.org/index.php/AAAI/article/view/26300"><i class="fas fa-file-pdf" aria-hidden="true"></i> PDF</a></p>
    </div>
  </article>
