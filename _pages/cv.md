---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
  /* Keep the viewer within the viewport and respect A4-ish aspect */
  .pdf-wrap { max-height: 92vh; }
  .pdf-frame {
    width: 100%;
    /* A4 portrait ≈ 1 : 1.414  (width : height) */
    aspect-ratio: 1 / 1.414;
    max-height: 92vh;
    border: 0;
    display: block;
  }
</style>

<div class="pdf-wrap">
  <iframe
    class="pdf-frame"
    src="{{ '/files/CV_Nicolas_Beauvais.pdf#view=FitH&toolbar=0&navpanes=0' | relative_url }}">
  </iframe>
</div>




