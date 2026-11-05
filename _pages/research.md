---
layout: page
title: research
permalink: /research/
description: my research projects, papers, and code.
nav: true
nav_order: 2
---

<style>
  .research-grid .proj-box {
    border: 1px solid var(--global-divider-color);
    background-color: var(--global-card-bg-color);
    border-radius: 8px;
    padding: 1.5rem;
    height: 100%;
  }
  .research-grid .proj-box h3 {
    margin-top: 0;
    margin-bottom: 0.5rem;
    font-size: 1.15rem;
    font-weight: 600;
  }
  .research-grid .proj-head {
    display: flex;
    flex-wrap: wrap;
    align-items: baseline;
    gap: 0.25rem 0.6rem;
    margin-bottom: 0.5rem;
  }
  .research-grid .proj-head h3 {
    margin-bottom: 0;
  }
  .research-grid .proj-venue {
    font-size: 0.78rem;
    font-style: italic;
    color: var(--global-theme-color);
    white-space: nowrap;
  }
  .research-grid .proj-box .proj-meta {
    color: var(--global-text-color-light, #828282);
    font-size: 0.85rem;
    margin-bottom: 0.6rem;
  }
  .research-grid .proj-box p {
    font-size: 0.95rem;
    margin-bottom: 0.75rem;
  }
  .research-grid .proj-links a {
    margin-right: 1rem;
    font-size: 0.9rem;
    font-weight: 600;
  }
  .research-grid h2.area {
    margin-top: 2rem;
    margin-bottom: 1rem;
  }
</style>

<div class="research-grid">

<h2 class="area">Algebra &amp; Cryptography</h2>
<div class="row row-cols-1 row-cols-md-2">

  <div class="col mb-4">
    <div class="proj-box">
      <h3>Kaiburr: ML-KEM at (much) higher security</h3>
      <div class="proj-meta">MPI-SP · with <a href="https://cryptojedi.org/peter/index.shtml">Peter Schwabe</a> &amp; <a href="https://vadimlyubash.github.io/">Vadim Lyubashevsky</a> · cryptographic engineering</div>
      <p>Generalized ML-KEM's noise distribution to scale module rank past the decryption-failure limit, keeping its ring arithmetic and simple, constant-time sampling. Defined three parameter sets reaching up to 1717 bits of classical Core-SVP security within FrodoKEM-640's communication budget, with decryption-failure bounds formally verified in EasyCrypt. Implemented in C, in Jasmin with machine-checked constant-time verification, and for Pavona's ACC, and benchmarked on three Intel microarchitectures.</p>
      <div class="proj-links">
        <a href="https://eprint.iacr.org/2026/2730">ePrint</a>
        <a href="https://github.com/cryptojedi/kaiburr">Code</a>
      </div>
    </div>
  </div>

  <div class="col mb-4">
    <div class="proj-box">
      <h3>Monogenic Fields of Cryptographic Size</h3>
      <div class="proj-meta">BYU · supervised by <a href="https://mathdept.byu.edu/~kpratt/">Kyle Pratt</a> &amp; <a href="https://mathdept.byu.edu/~nick/">Nick Andersen</a> · Ring-LWE / lattice-based cryptography</div>
      <p>Explicit number-field constructions via polynomial transformations for Ring-LWE schemes. Designed and analyzed algebraic number fields in SageMath, computing discriminants, Galois groups, and ramification, to identify cryptographically secure parameters, with proofs of irreducibility and monogenicity.</p>
      <div class="proj-links">
        <a href="https://arxiv.org/abs/2609.22374">arXiv</a>
      </div>
    </div>
  </div>

  <div class="col mb-4">
    <div class="proj-box">
      <div class="proj-head">
        <h3>Tolerants</h3>
        <span class="proj-venue">PCMI proceedings, to appear, 2026</span>
      </div>
      <div class="proj-meta">BYU · algebraic geometry/topology</div>
      <p>Developed the <em>tolerant</em>, a novel invariant that extends and strengthens classical discriminant theory. Proved a closed-form formula via discriminants and resultants, resolved an open question in prior work, and established its structural and algebraic properties.</p>
      <div class="proj-links">
        <a href="https://arxiv.org/abs/2506.22897">arXiv</a>
      </div>
    </div>
  </div>

</div>

<h2 class="area">AI &amp; Language Models</h2>
<div class="row row-cols-1 row-cols-md-2">

  <div class="col mb-4">
    <div class="proj-box">
      <div class="proj-head">
        <h3>EduQuest</h3>
        <span class="proj-venue">ACM SIGDOC proceedings, to appear, 2026</span>
      </div>
      <div class="proj-meta"><a href="https://dragn.ai/">BYU DRAGN Labs</a> · advisor: Nancy Fulda</div>
      <p>A multi-agent LLM system that generates personalized, curriculum-aligned weekly homework by integrating vector-store retrieval, goal planning, and automated grading. Evaluated via an IRB-approved teacher focus group.</p>
    </div>
  </div>

  <div class="col mb-4">
    <div class="proj-box">
      <h3>Informational Sufficiency in LLMs</h3>
      <div class="proj-meta"><a href="https://dragn.ai/">BYU DRAGN Labs</a> · advisor: Nancy Fulda</div>
      <p>A framework measuring when a model has "enough" information to reason well, extending the notion of underspecification. Building a benchmark to detect insufficient inputs, analyze model stability, and identify the minimum information needed for reliable LLM reasoning.</p>
      <div class="proj-links">
        <!-- TODO: add paper link when available -->
      </div>
    </div>
  </div>

</div>

</div>
