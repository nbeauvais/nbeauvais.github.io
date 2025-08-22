---
layout: archive
title: "CV"
permalink: /cv-json/
author_profile: false
redirect_from:
  - /resume-json
---

{% include base_path %}

{% include cv-template.html %}
<!-- Inline, scrollable PDF -->
<object 
  data="{{ '/files/CV_Nicolas_Beauvais.pdf' | relative_url }}" 
  type="application/pdf" 
  width="100%" 
  height="900px">
  <p>
    Your browser can't display PDFs inline.
    <a href="{{ '/files/CV_Nicolas_Beauvais.pdf' | relative_url }}" target="_blank" rel="noopener">
      Open the CV in a new tab
    </a>.
  </p>
</object>


<div class="cv-download-links">
  <a href="{{ base_path }}/files/CV_Nicolas_Beauvais.pdf" class="btn btn--primary">Download CV as PDF</a>
  <a href="{{ base_path }}" class="btn btn--inverse">View Markdown CV</a>
</div>
