---
layout: about
title: Home
permalink: /
subtitle: <strong>PhD researcher</strong> building machine learning and computational methods for subsurface systems.

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

Howdy, I'm **Dursun** — a PhD researcher at the
[University of Texas at Austin](https://www.utexas.edu/), under the supervision of
[Dr. Michael Pyrcz](https://michaelpyrcz.com/) and
[Dr. John T. Foster](https://johnfoster.pge.utexas.edu/).
I work as part of the [DIRECT Consortium](https://direct.pge.utexas.edu/) on bridging
**subsurface data** and **artificial intelligence** to build data-driven solutions for
reservoir modeling and management.

My work sits where three worlds meet. I'm a **geoscientist** by training, a
**computer scientist** by craft, and a **statistician** by research — and I like to build at
the overlap: physics-informed deep learning, latent-space methods for subsurface flow, and
tools that turn messy field data into decisions.

Currently working on **geostatistics** and **generative adversarial networks (GANs)** for
**inverse modeling and history matching** of the subsurface.
Before UT Austin, I spent two years as a **Reservoir Engineer / Data Analyst at BP** and
earned an MSc in Computer Science at **George Washington University**.

Outside research activities, I enjoy weightlifting, watching movies from different cultures,
and currently having fun learning the drums.

Take a look at my [research](/research/), [projects](/projects/), and
[teaching](/teaching/) — or [get in touch](/contact/).
