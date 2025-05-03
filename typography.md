---
layout: page
title: Resume
permalink: /resume/
main_nav: true
---

<div class="resume-page">

  <h1>{{ page.title }}</h1>
  <p>You can download or view my résumé inline below.</p>

  <!-- Download/View button -->
  <p>
    <a href="{{ '/assets/Zou_Kuangyu_Resume.pdf' | relative_url }}"
       class="button"
       target="_blank"
       rel="noopener">
      📄 Download Résumé (PDF)
    </a>
  </p>

  <!-- Inline PDF viewer -->
  <div style="margin-top:2em;">
    <object
      data="{{ '/assets/Zou_Kuangyu_Resume.pdf' | relative_url }}"
      type="application/pdf"
      width="100%"
      height="800px">
      <p>Your browser doesn’t support embedded PDFs.
         <a href="{{ '/assets/Zou_Kuangyu_Resume.pdf' | relative_url }}">Download the PDF</a>.
      </p>
    </object>
  </div>

</div>

