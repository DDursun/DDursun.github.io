---
layout: about
title: Home
permalink: /
subtitle: <strong>PhD researcher</strong> · The University of Texas at Austin

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # rectangular image
  more_info: >
    <p style="font-family:'Roboto',-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;font-size:.72rem;line-height:1.35;color:var(--global-text-color-light,#828282);">Picture taken at UT Energy AI Hackathon, 2026</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  /* al-folio renders the "selected publications" heading lowercase; capitalize its first letter */
  #content h2::first-letter,
  .post h2::first-letter {
    text-transform: uppercase;
  }

  /* Profile photo: black version by default, swap to color instantly on hover.
     Black is the <img> (prof_pic.jpg); color sits behind as the figure background
     (prof_pic_color.jpg) and shows the moment the img is hidden. */
  .profile figure {
    margin: 0;
    border-radius: 4px;
    background-image: url("{{ '/assets/img/prof_pic_color.jpg' | relative_url }}");
    background-size: cover;
    background-position: center;
  }
  .profile img {
    border-radius: 4px;
  }
  .profile:hover img {
    opacity: 0;
  }
</style>

<div style="text-align:center;margin-bottom:1.5rem;">
  <span style="display:inline-block;border:1px solid var(--global-theme-color);border-radius:999px;padding:.25rem 0.9rem;color:var(--global-theme-color);font-size:.75rem;letter-spacing:.04em;text-transform:uppercase;">Website under construction</span>
</div>

Hi, I'm **Dursun** — a PhD researcher in Petroleum Engineering at the
[University of Texas at Austin](https://www.utexas.edu/), where I work with the
[DIRECT Consortium](https://github.com/GeostatsGuy) on bridging **subsurface data** and
**artificial intelligence** to build data-driven solutions for reservoir modeling and management.

My work sits where three worlds meet. I'm a **reservoir engineer** by training, a
**software engineer** by craft, and a **machine learning / statistics** practitioner by
research — and I like to build at the overlap: physics-informed deep learning, latent-space
methods for subsurface flow, and tools that turn messy field data into decisions.

Currently developing **Physics-Informed Neural Networks (PINNs)** and **GANs** to model
subsurface flow by enforcing physical consistency inside deep learning architectures.
Before UT Austin, I spent two years as a **Reservoir Engineer / Data Analyst at BP** and
earned an MSc in Computer Science at **George Washington University**.

Take a look at my [research](/research/), [projects](/projects/), and
[teaching](/teaching/) — or [get in touch](/contact/).
