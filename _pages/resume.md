---
layout: archive
title: "Resume"
permalink: /resume/
author_profile: true
# redirect_from:
#   - /cv
---

<!-- {% include base_path %} -->

<object
  data="{{ '/files/resume.pdf' | relative_url }}"
  type="application/pdf"
  width="100%"
  height="90vh">
  <!-- Fallback to an <embed> if the browser doesn’t support <object> PDFs -->
  <embed
    src="{{ '/files/resume.pdf' | relative_url }}"
    type="application/pdf"
    width="100%"
    height="90vh" />
  <!-- Final fallback if neither works -->
  <p>
    Your browser doesn’t support embedded PDFs.
    <a href="{{ '/files/resume.pdf' | relative_url }}">Download the PDF</a>.
  </p>
</object>