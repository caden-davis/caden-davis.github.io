---
layout: archive
title: ""
permalink: /resume/
author_profile: true
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
  /* mobile: narrower than 768px */
  @media only screen and (max-width: var(--sidebar-bp)) {
    .resume-embed iframe {
      height: 60vh;
    }
  }
</style>

<div class="resume-embed">
  <iframe
    src="https://docs.google.com/gview?url={{ site.url }}{{ '/files/resume.pdf' | relative_url }}&embedded=true"
    allowfullscreen>
  </iframe>
</div>