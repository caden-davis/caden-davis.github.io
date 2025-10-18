---
permalink: /resume/
title: "Resume"
author_profile: false
redirect_from:
  - /cv/
---

{% include base_path %}

<style>
  /* default for “laptop” and up */
  .resume-embed iframe {
    width: 100%;
    height: 80vh;
    border: none;
  }
  /* mobile: narrower than 925 px */
  @media only screen and (max-width: 925px) {
    .resume-embed iframe {
      height: 60vh !important;
    }
  }
</style>

<!-- <div class="resume-embed">
  <iframe
    src="https://docs.google.com/gview?url={{ site.url }}{{ '/files/resume.pdf' | relative_url }}&embedded=true"
    allowfullscreen>
  </iframe>
</div> -->

Looking for internships for Summer 2026 in Austin, TX focused on wireless communications, radar, or embedded systems!

<div class="resume-embed" style="border: 1px solid var(--global-border-color); border-radius: 0px; padding: 0px;">
  <iframe
    src="https://docs.google.com/gview?url={{ site.url }}{{ '/files/resume.pdf' | relative_url }}&embedded=true"
    allowfullscreen
    style="width: 100%; height: 600px; border: none;">
  </iframe>
</div>