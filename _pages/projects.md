---
layout: page
title: Projects
permalink: /projects/
description: Selected projects across reservoir engineering, software, and machine learning — full details inline.
nav: true
nav_order: 5
---

<style>
  .proj-list { margin-top: 1.5rem; }
  .proj-card {
    display: flex;
    gap: 1.5rem;
    align-items: stretch;
    border: 1px solid var(--global-divider-color, #e0e0e0);
    border-radius: 14px;
    padding: 1.25rem;
    margin-bottom: 1.5rem;
    background: var(--global-card-bg-color, transparent);
    transition: box-shadow .2s ease, transform .2s ease;
  }
  .proj-card:hover { box-shadow: 0 6px 22px rgba(0,0,0,.08); transform: translateY(-2px); }
  .proj-media {
    flex: 0 0 240px;
    border-radius: 10px;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 170px;
    background: var(--global-bg-color, #f7f7f7);
  }
  .proj-media img { width: 100%; height: 100%; object-fit: cover; }
  .proj-media.placeholder {
    border: 2px dashed var(--global-divider-color, #cfcfcf);
    color: var(--global-text-color-light, #888);
    font-size: .82rem;
    text-align: center;
    padding: .5rem;
  }
  .proj-body { flex: 1 1 320px; min-width: 260px; }
  .proj-body h3 { margin: 0 0 .35rem; font-size: 1.2rem; }
  .proj-details { margin: .5rem 0 .75rem; }
  .proj-chips { display: flex; flex-wrap: wrap; gap: .4rem; margin: .4rem 0; }
  .chip {
    font-size: .72rem;
    padding: .15rem .55rem;
    border-radius: 999px;
    background: var(--global-theme-color, #b509ac);
    color: #fff;
    opacity: .9;
  }
  .chip.tech {
    background: transparent;
    color: var(--global-text-color-light, #555);
    border: 1px solid var(--global-divider-color, #ccc);
  }
  .proj-links a { font-size: .85rem; margin-right: 1rem; }
  @media (max-width: 600px) {
    .proj-card { flex-direction: column; }
    .proj-media { flex-basis: auto; width: 100%; }
  }
</style>

<div class="proj-list">
{% assign sorted_projects = site.projects | sort: "importance" %}
{% for project in sorted_projects %}
  <div class="proj-card">
    {% capture imgexists %}{% if project.img %}{% file_exists project.img %}{% else %}false{% endif %}{% endcapture %}
    {% if imgexists == "true" %}
      <div class="proj-media"><img src="{{ project.img | relative_url }}" alt="{{ project.title }}"></div>
    {% else %}
      <div class="proj-media placeholder">image:<br>{{ project.img }}</div>
    {% endif %}
    <div class="proj-body">
      <h3>{{ project.title }}</h3>
      {% if project.tags %}
      <div class="proj-chips">
        {% for tag in project.tags %}<span class="chip">{{ tag }}</span>{% endfor %}
      </div>
      {% endif %}
      <p class="proj-details">{{ project.details | default: project.description }}</p>
      {% if project.tech %}
      <div class="proj-chips">
        {% for t in project.tech %}<span class="chip tech">{{ t }}</span>{% endfor %}
      </div>
      {% endif %}
      {% if project.github %}
      <div class="proj-links">
        <a href="{{ project.github }}" target="_blank" rel="noopener">View code →</a>
      </div>
      {% endif %}
    </div>
  </div>
{% endfor %}
</div>
