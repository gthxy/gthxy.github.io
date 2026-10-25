---
layout: page
permalink: /cv/
title: cv
nav: true
nav_order: 5
nav_pdf: true
cv_pdf: Xinyue_Huang_CV.pdf
description: Curriculum vitae of Xinyue Huang.
---

{% assign cv_url = page.cv_pdf | prepend: '/assets/pdf/' | relative_url %}

<p>
  <a class="btn btn-outline-primary mr-3 mb-3" href="{{ cv_url }}" download="Xinyue_Huang_CV.pdf">
    <i class="fa-solid fa-file-pdf mr-1" aria-hidden="true"></i>
    Download CV (PDF)
  </a>
  <a href="{{ cv_url }}" target="_blank" rel="noopener noreferrer">View PDF in a new tab</a>
</p>
