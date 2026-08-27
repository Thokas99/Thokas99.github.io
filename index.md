---
layout: single
author_profile: true
classes: wide home-page
title: "Thomas Sirchi"
excerpt: "Cancer genomics, transcriptomics, single-cell analysis, and multi-omics."
---

<div class="home-hero">
  <p class="home-hero__subtitle">Computational Biologist · Cancer Genomics · Single-Cell &amp; Multi-Omics</p>
</div>

## About me

I am a **computational biologist working in cancer genomics**, using
high-dimensional molecular data to investigate how tumour cells change state,
interact with their microenvironment, and respond to treatment.

My work combines **transcriptomics, single-cell biology, multi-omics
integration, statistics, and machine learning**, with experience across
**lung cancer and haematological malignancies** and an emphasis on
**reproducible analysis and biologically interpretable results**.

### Research focus

<div class="focus-grid">
  <article class="focus-card">
    <h3>Cancer ecosystems &amp; plasticity</h3>
    <p>Tumour heterogeneity, malignant state transitions, metastatic progression, treatment response, and tumour–microenvironment interactions.</p>
  </article>
  <article class="focus-card">
    <h3>Single-cell, spatial &amp; multi-omics</h3>
    <p>Single-cell transcriptomics, spatial molecular data, and integration of transcriptomic, genomic, and epigenomic measurements.</p>
  </article>
  <article class="focus-card">
    <h3>Computational methodology</h3>
    <p>Statistical genomics, machine learning, explicit quality control, batch-effect modelling, and reproducible computational workflows.</p>
  </article>
</div>

### Computational toolkit

<div class="toolkit-grid">
  <section class="toolkit-group">
    <h4>Languages &amp; workflows</h4>
    <div class="toolkit__tags" aria-label="Languages and workflow tools">
      <span class="tech-tag">R</span>
      <span class="tech-tag">Python</span>
      <span class="tech-tag">Bash</span>
      <span class="tech-tag">Nextflow</span>
    </div>
  </section>
  <section class="toolkit-group">
    <h4>Data analysis</h4>
    <div class="toolkit__tags" aria-label="Data analysis approaches">
      <span class="tech-tag">scRNA-seq</span>
      <span class="tech-tag">Spatial transcriptomics</span>
      <span class="tech-tag">Bulk RNA-seq</span>
      <span class="tech-tag">miRNA-seq</span>
      <span class="tech-tag">Multi-omics</span>
      <span class="tech-tag">Differential expression</span>
      <span class="tech-tag">Pathway analysis</span>
      <span class="tech-tag">Immune deconvolution</span>
    </div>
  </section>
  <section class="toolkit-group">
    <h4>Approach</h4>
    <div class="toolkit__tags" aria-label="Computational approaches">
      <span class="tech-tag">Reproducible workflows</span>
      <span class="tech-tag">Statistical modelling</span>
      <span class="tech-tag">Machine learning</span>
      <span class="tech-tag">Data visualisation</span>
      <span class="tech-tag">Biological interpretation</span>
    </div>
  </section>
</div>

I build reproducible computational workflows for sequencing QC, statistical
analysis, integrative modelling, and biological interpretation.

> **Current focus:** tumour heterogeneity, cell-state plasticity, and metastatic progression through single-cell and multi-omic approaches.

<nav class="home-actions" aria-label="Site sections">
  <a class="btn btn--primary" href="{{ '/research/' | relative_url }}">Explore research</a>
  <a class="btn" href="{{ '/software/' | relative_url }}">View software</a>
  <a class="btn" href="{{ '/cv/' | relative_url }}">CV</a>
</nav>

## Software

<div class="project-grid project-grid--home">
  <article class="project-card">
    <h3>veryMAD</h3>
    <p>Explicit MAD-based quality control and diagnostic visualisation for high-dimensional biological data.</p>
    <div class="project-card__tags" aria-label="Technologies and domains">
      <span class="tech-tag">R</span>
      <span class="tech-tag">QC</span>
      <span class="tech-tag">MAD</span>
    </div>
    <a class="project-card__link" href="https://github.com/Thokas99/veryMAD" rel="noopener">View repository<span class="visually-hidden">: veryMAD</span> <span aria-hidden="true">↗</span></a>
  </article>
  <article class="project-card">
    <h3>veryMADpy</h3>
    <p>Python/AnnData implementation of explicit MAD-based quality control for modern single-cell workflows.</p>
    <div class="project-card__tags" aria-label="Technologies and domains">
      <span class="tech-tag">Python</span>
      <span class="tech-tag">AnnData</span>
      <span class="tech-tag">Scanpy</span>
    </div>
    <a class="project-card__link" href="https://github.com/Thokas99/veryMADpy" rel="noopener">View repository<span class="visually-hidden">: veryMADpy</span> <span aria-hidden="true">↗</span></a>
  </article>
  <article class="project-card">
    <h3>ComBat-refQL</h3>
    <p>Reference-batch adjustment for bulk RNA-seq count data using quasi-likelihood modelling and explicit diagnostics.</p>
    <div class="project-card__tags" aria-label="Technologies and domains">
      <span class="tech-tag">R</span>
      <span class="tech-tag">edgeR</span>
      <span class="tech-tag">RNA-seq</span>
    </div>
    <a class="project-card__link" href="https://github.com/Thokas99/ComBat-refQL" rel="noopener">View repository<span class="visually-hidden">: ComBat-refQL</span> <span aria-hidden="true">↗</span></a>
  </article>
  <article class="project-card">
    <h3>simple-nextflow-salmon</h3>
    <p>Lightweight reproducible Nextflow workflow for RNA-seq quantification with Salmon and integrated QC.</p>
    <div class="project-card__tags" aria-label="Technologies and domains">
      <span class="tech-tag">Nextflow</span>
      <span class="tech-tag">Salmon</span>
      <span class="tech-tag">RNA-seq</span>
    </div>
    <a class="project-card__link" href="https://github.com/Thokas99/simple-nextflow-salmon" rel="noopener">View repository<span class="visually-hidden">: simple-nextflow-salmon</span> <span aria-hidden="true">↗</span></a>
  </article>
</div>

[See all software projects]({{ '/software/' | relative_url }}){: .btn .btn--inverse}

## What I care about

<div class="research-principle" role="group" aria-label="Research workflow">
  <div class="research-principle__steps">
    <span class="research-principle__step">Biological question</span>
    <span class="research-principle__arrow" aria-hidden="true">→</span>
    <span class="research-principle__step">Statistical evidence</span>
    <span class="research-principle__arrow" aria-hidden="true">→</span>
    <span class="research-principle__step">Interpretable biology</span>
  </div>
  <p>I am particularly interested in computational approaches that connect <strong>molecular measurements with tumour cell state, evolutionary dynamics and phenotype</strong>, rather than treating high-dimensional data as an endpoint by itself.</p>
</div>
