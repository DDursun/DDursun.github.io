---
layout: page
title: Contact
permalink: /contact/
nav: true
nav_order: 6
---

I’m always happy to talk about energy, subsurface modeling and machine learning, or collaborations/opportunities.

Best way to reach me is email:

<style>
  .contact-wrap {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 1.5rem 2.5rem;
    margin: 1.5rem 0;
  }
  .contact-links {
    flex: 1 1 300px;
    max-width: 400px;
    display: flex;
    flex-direction: column;
    gap: 0.6rem;
  }
  .contact-links > * {
    display: flex;
    align-items: center;
    gap: 0.75rem;
    padding: 0.7rem 1rem;
    border: 1px solid var(--global-divider-color, #e0e0e0);
    border-radius: 10px;
    text-decoration: none;
    font-size: 0.95rem;
  }
  .contact-links i {
    width: 1.4rem;
    text-align: center;
    color: var(--global-theme-color);
  }
  /* The globe sizes itself to its parent's width (100-400px), so this width sets its size. */
  .contact-globe-area {
    flex: 1 1 240px;
    display: flex;
    justify-content: center;
  }
  .contact-globe {
    position: relative;
    flex: 0 0 230px;
    width: 230px;
  }
  /* Transparent overlay: sends every click on the globe to the stats page, whatever link the widget sets. */
  .contact-globe .globe-link {
    position: absolute;
    inset: 0;
    z-index: 2000;
  }
</style>

<div class="contact-wrap">

  <div class="contact-links">
    <a href="mailto:dursun.dashdamirov@utexas.edu">
      <i class="fa-solid fa-envelope"></i>
      <span><strong>Email</strong> — dursun.dashdamirov@utexas.edu</span>
    </a>

    <a href="https://www.linkedin.com/in/dursun-dashdamirov/" target="_blank" rel="noopener">
      <i class="fa-brands fa-linkedin"></i>
      <span><strong>LinkedIn</strong> — linkedin.com/in/dursun-dashdamirov</span>
    </a>

    <a href="https://github.com/DDursun" target="_blank" rel="noopener">
      <i class="fa-brands fa-github"></i>
      <span><strong>GitHub</strong> — github.com/DDursun</span>
    </a>

    <div>
      <i class="fa-solid fa-location-dot"></i>
      <span><strong>Location</strong> — Austin, TX, USA</span>
    </div>

    <a href="{{ '/assets/pdf/DursunD_CV.pdf' | relative_url }}" target="_blank">
      <i class="fa-solid fa-file-pdf"></i>
      <span><strong>Curriculum Vitae</strong> — download PDF</span>
    </a>

  </div>

  <div class="contact-globe-area">
  <div class="contact-globe">
    <script type="text/javascript" id="mmvst_globe" src="//mapmyvisitors.com/globe.js?d=dKvkZCx43U3VSWbYsaH_Cc8zemvXyDNJ1ilUiwXIqrA"></script>
    <a class="globe-link" href="https://mapmyvisitors.com/web/1c8vk" target="_blank" rel="noopener" title="View visitor statistics" aria-label="View visitor statistics"></a>
  </div>
  </div>

</div>
