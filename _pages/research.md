---
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 3
description: Deep learning–based latent-space methods for subsurface resource modeling — interests and publications.
toc:
  sidebar: left
---

<h2 style="display:inline-block;background:var(--global-theme-color);color:#fff;padding:.15rem .6rem;border-radius:6px;font-size:1.1rem;">University of Texas at Austin</h2>

**Deep learning–based latent-space methods for subsurface resource modeling.**

At the [DIRECT Consortium](https://github.com/GeostatsGuy) I work on enforcing physical
consistency inside deep learning models so that data-driven subsurface predictions stay
faithful to the physics of flow. My research spans four connected directions.

## Research Interests

<!-- Each direction can take a supporting figure on the right.
     Drop images in assets/img/research/ and replace the placeholder divs. -->

<div class="research-item" style="display:flex;gap:1.5rem;align-items:flex-start;flex-wrap:wrap;margin:1.5rem 0;">
  <div style="flex:1 1 320px;min-width:280px;">
    <h3 style="margin-top:0;">1. Convolutional–Recurrent proxy for spatiotemporal CO₂ monitoring</h3>
    <ul>
      <li>Image-to-video forecasting for geologic CO₂ sequestration.</li>
      <li>Well placement and control optimization.</li>
      <li>Data assimilation and uncertainty quantification.</li>
    </ul>
  </div>
  <div style="flex:0 0 240px;display:flex;align-items:center;justify-content:center;height:170px;border:2px dashed var(--global-divider-color,#cfcfcf);border-radius:10px;color:var(--global-text-color-light,#888);font-size:.85rem;text-align:center;padding:.5rem;">
    figure: CO₂ plume forecast<br>(assets/img/research/co2.png)
  </div>
</div>

<div class="research-item" style="display:flex;gap:1.5rem;align-items:flex-start;flex-wrap:wrap;margin:1.5rem 0;">
  <div style="flex:1 1 320px;min-width:280px;">
    <h3 style="margin-top:0;">2. Latent geologic inversion from multiscale, multi-source dynamic data</h3>
    <ul>
      <li>Reconstruction of 2D/3D fluvial geologic models from production- and observation-well data.</li>
      <li>Closed-loop forward &amp; inverse modeling.</li>
    </ul>
  </div>
  <div style="flex:0 0 240px;display:flex;align-items:center;justify-content:center;height:170px;border:2px dashed var(--global-divider-color,#cfcfcf);border-radius:10px;color:var(--global-text-color-light,#888);font-size:.85rem;text-align:center;padding:.5rem;">
    figure: geologic model<br>(assets/img/research/geomodel.png)
  </div>
</div>

<div class="research-item" style="margin:1.5rem 0;">
  <h3>3. Dimensionality reduction and parameter estimation from fiber-optic data</h3>
  <ul>
    <li>Estimate injection location and multiphase relative flowrates from fiber-optic measurements.</li>
  </ul>
</div>

<div class="research-item" style="margin:1.5rem 0;">
  <h3>4. Physics-Informed Anisotropic Resistivity Inversion</h3>
  <ul>
    <li>Fast inversion algorithm for parallel- and perpendicular-to-bedding-plane resistivity logs.</li>
  </ul>
</div>

## Publications

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
