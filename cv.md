---
title: "CV"
layout: default
---

# My CV

<style>
  .cv-container {
    width: 100vw;
    max-width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .cv-frame {
    width: 100vw; /* Full viewport width */
    max-width: 100%;
    height: 90vh; /* Almost full height */
    border: none;
  }

  .download-link {
    margin-top: 15px;
    font-size: 18px;
    color: #007bff;
    text-decoration: none;
    font-weight: bold;
  }

  .download-link:hover {
    text-decoration: underline;
  }

  /* Override wrapper styles to allow full width */
  .cv-container .wrapper {
    max-width: 100% !important;
    width: 100vw;
    padding: 0;
  }
</style>

<div class="cv-container">
  <iframe 
    class="cv-frame" 
    src="{{ site.baseurl }}/cv/Satyam_Dubey_CV_MSDS.pdf">
  </iframe>

  <p>If the PDF does not load, you can <a class="download-link" href="{{ site.baseurl }}/cv/Satyam_Dubey.pdf" target="_blank">download it here</a>.</p>
</div>
