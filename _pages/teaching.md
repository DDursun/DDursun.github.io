---
layout: page
permalink: /teaching/
title: Teaching
nav: true
nav_order: 4
description: Teaching, mentoring, and making technical knowledge accessible.
---

<style>
  /* Lecture photos: black-and-white by default, swap to color on hover */
  .lecture-swap {
    height: 170px;
    border-radius: 8px;
    overflow: hidden;
    background-size: cover;
    background-position: center;
  }
  .lecture-swap img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
    border-radius: 8px;
  }
  .lecture-swap:hover img {
    opacity: 0;
  }
  /* Uncropped variant: show the whole image; leftover space is filled with a
     per-image tone (set inline) sampled from the photo so the bars blend in */
  .lecture-swap.contain {
    background-size: contain;
    background-repeat: no-repeat;
  }
  .lecture-swap.contain img {
    object-fit: contain;
  }
</style>

I believe in the power of intuitive learning: the ability to truly understand how things work
under the surface. I've always admired educators who could teach complex subjects intuitively.
While still working toward that level, I conduct lectures and hands-on sessions aimed at
translating statistics, engineering, and code into something a learner can actually use,
learning a great deal myself along the way. You can also find some of my slides and notes,
along with recommended readings, below.

<div class="teaching-item" style="border:1px solid var(--global-divider-color,#e0e0e0);border-radius:12px;padding:1.25rem 1.5rem;margin:1.5rem 0;">
  <div style="display:flex;justify-content:space-between;flex-wrap:wrap;gap:.5rem;align-items:baseline;">
    <h3 style="margin:0;">Machine Learning Instructor</h3>
    <span style="color:var(--global-text-color-light,#828282);font-size:.9rem;">Feb. 2023 – Present</span>
  </div>
  <p style="margin:.4rem 0 0;color:var(--global-text-color-light,#828282);">BHOS SPE Student Chapter &amp; Youth Organization (non-profit)</p>
  <p style="margin:.7rem 0 0;">Lecturing on statistics, feature engineering, and machine learning algorithms with hands-on coding and derivations.</p>

  <div style="display:flex;gap:1rem;flex-wrap:wrap;margin-top:1.25rem;">
    <figure style="flex:1 1 200px;margin:0;">
      <div class="lecture-swap" style="background-image:url('/assets/img/teaching/lecture1.jpg');">
        <img src="/assets/img/teaching/lecture1_black.jpg" alt="Feature Engineering lecture" />
      </div>
      <figcaption style="margin-top:.45rem;font-size:.75rem;color:var(--global-text-color-light,#828282);line-height:1.35;">Feature Engineering, "AI and Machine Learning" course, BHOS Youth Organization</figcaption>
    </figure>
    <figure style="flex:1 1 200px;margin:0;">
      <div class="lecture-swap contain" style="background-color:#ada9a7;background-image:url('/assets/img/teaching/lecture2.jpg');">
        <img src="/assets/img/teaching/lecture2_black.jpg" alt="SQL for data science lecture" />
      </div>
      <figcaption style="margin-top:.45rem;font-size:.75rem;color:var(--global-text-color-light,#828282);line-height:1.35;">SQL for data science, "Datavision" course, SPE</figcaption>
    </figure>
    <figure style="flex:1 1 200px;margin:0;">
      <div class="lecture-swap contain" style="background-color:#bebcb9;background-image:url('/assets/img/teaching/lecture3.jpg');">
        <img src="/assets/img/teaching/lecture3_black.jpg" alt="Machine Learning for Subsurface Engineers lecture" />
      </div>
      <figcaption style="margin-top:.45rem;font-size:.75rem;color:var(--global-text-color-light,#828282);line-height:1.35;">"Machine Learning for Subsurface Engineers" course, in collab with SEG</figcaption>
    </figure>
  </div>
</div>

<div class="teaching-item" style="border:1px solid var(--global-divider-color,#e0e0e0);border-radius:12px;padding:1.25rem 1.5rem;margin:1.5rem 0;">
  <div style="display:flex;justify-content:space-between;flex-wrap:wrap;gap:.5rem;align-items:baseline;">
    <h3 style="margin:0;">Academic Content Creator</h3>
    <span style="color:var(--global-text-color-light,#828282);font-size:.9rem;">Jul. 2020 – Jan. 2021</span>
  </div>
  <p style="margin:.4rem 0 0;color:var(--global-text-color-light,#828282);">Khan Academy</p>
  <p style="margin:.6rem 0 0;">Translated and edited <strong>physics</strong> content to support free and accessible
  education for a wider audience.</p>
</div>

## Resources

A few things I've put together along the way — course materials, study notes, and project
collections. Click any card to open it on GitHub.

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:1.25rem;margin-top:1.25rem;">

  <div style="border:1px solid var(--global-divider-color,#e0e0e0);border-radius:12px;overflow:hidden;">
    <a href="https://github.com/DDursun/SubsurfaceML_course" target="_blank" rel="noopener">
      <img src="https://opengraph.githubassets.com/1/DDursun/SubsurfaceML_course" alt="SubsurfaceML_course preview" style="width:100%;display:block;" />
    </a>
    <div style="padding:.85rem 1rem;">
      <strong>Subsurface ML — Course</strong>
      <p style="margin:.3rem 0 .5rem;font-size:.85rem;color:var(--global-text-color-light,#828282);">Machine learning applied to subsurface problems across geology, geophysics, and petroleum engineering.</p>
      <a href="https://github.com/DDursun/SubsurfaceML_course" target="_blank" rel="noopener" style="font-size:.85rem;">View repository →</a>
    </div>
  </div>

  <div style="border:1px solid var(--global-divider-color,#e0e0e0);border-radius:12px;overflow:hidden;">
    <a href="https://github.com/DDursun/math_notes" target="_blank" rel="noopener">
      <img src="https://opengraph.githubassets.com/1/DDursun/math_notes" alt="math_notes preview" style="width:100%;display:block;" />
    </a>
    <div style="padding:.85rem 1rem;">
      <strong>Engineering Math Notes</strong>
      <p style="margin:.3rem 0 .5rem;font-size:.85rem;color:var(--global-text-color-light,#828282);">LaTeX notes on Linear Algebra, ODEs, PDEs, Laplace transforms, and vector analysis (after Kreyszig).</p>
      <a href="https://github.com/DDursun/math_notes" target="_blank" rel="noopener" style="font-size:.85rem;">View repository →</a>
    </div>
  </div>

  <div style="border:1px solid var(--global-divider-color,#e0e0e0);border-radius:12px;overflow:hidden;">
    <a href="https://github.com/DDursun/machine-learning-projects" target="_blank" rel="noopener">
      <img src="https://opengraph.githubassets.com/1/DDursun/machine-learning-projects" alt="machine-learning-projects preview" style="width:100%;display:block;" />
    </a>
    <div style="padding:.85rem 1rem;">
      <strong>Machine Learning Projects</strong>
      <p style="margin:.3rem 0 .5rem;font-size:.85rem;color:var(--global-text-color-light,#828282);">Assignments and mini-projects spanning fundamental algorithms, EDA, optimization, and regression/classification workflows.</p>
      <a href="https://github.com/DDursun/machine-learning-projects" target="_blank" rel="noopener" style="font-size:.85rem;">View repository →</a>
    </div>
  </div>

</div>
