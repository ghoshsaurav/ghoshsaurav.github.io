---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: /assets/pdf/example_pdf.pdf
description: Curriculum vitae of Saurav Ghosh.
---

<script>
  window.location.replace("{{ page.cv_pdf | relative_url }}");
</script>

<meta http-equiv="refresh" content="0; url={{ page.cv_pdf | relative_url }}">

<p>
  Opening CV PDF.
  <a href="{{ page.cv_pdf | relative_url }}">Click here if it does not open automatically.</a>
</p>
