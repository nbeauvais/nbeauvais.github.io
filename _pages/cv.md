---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
  .page__title {
    text-align: center;
  }
  .cv-download {
    margin: 1em auto;
    display: inline-block;
  }
</style>

<!-- Centered Download Button -->
<p style="text-align: center;">
  <a class="btn btn-primary btn-lg cv-download" 
     href="{{ '/files/CV_Nicolas_Beauvais.pdf' | relative_url }}" 
     target="_blank">
    <i class="fa-solid fa-file-arrow-down"></i>&ensp;Download current CV
  </a>
</p>

<!-- Scrollable PDF viewer -->
<style>
  .pdf-wrap { max-height: 92vh; }
  .pdf-frame {
    width: 100%;
    aspect-ratio: 1 / 1.414; /* A4 portrait ratio */
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
