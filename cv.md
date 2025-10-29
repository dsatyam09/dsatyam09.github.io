---
title: "CV"
layout: default
permalink: /cv/
---


# My CV

<style>
  .cv-container {
    width: 100%;
    max-width: 1200px;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 0 auto;
    padding: 0 16px;
  }

  .cv-frame {
    width: 100%;
    height: min(85vh, 1200px);
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

  /* Make sure the page wrapper doesn't constrain the iframe weirdly */
  .cv-container .wrapper {
    max-width: 100% !important;
    width: 100%;
    padding-left: 0;
    padding-right: 0;
  }

  @media (min-width: 1400px) {
    .cv-container { max-width: 1400px; }
  }

  @media (max-width: 768px) {
    .cv-frame { height: 70vh; }
  }
</style>

<div class="cv-container">
  <iframe 
    class="cv-frame" 
    src="{{ site.baseurl }}/cv/Satyam_Dubey_CV_MSDS.pdf">
  </iframe>

  <p>If the PDF does not load, you can <a class="download-link" href="{{ site.baseurl }}/cv/Satyam_Dubey_CV_MSDS.pdf" target="_blank">download it here</a>.</p>
</div>
