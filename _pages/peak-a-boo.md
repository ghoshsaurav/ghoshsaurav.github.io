---
layout: page
title: "Peak-a-Boo: Reviewing Chromatographic Peak Detections"
permalink: /projects/peak-a-boo/
description: "Peak-a-Boo is a visual analytics prototype for reviewing ambiguous chromatographic peak detections. Presented at IEEE VIS 2026."
---

**Saurav Ghosh, Saugat Pandey, and Alvitta Ottley** · IEEE VIS 2026 · Boston, MA

Automated peak detectors can miss small or overlapping peaks and mistake noise for a peak. Peak-a-Boo helps analysts decide which detections to review and inspect the evidence behind each one.

## How it works

The review queue prioritizes ambiguous detections. For each case, the interface shows the signal alongside evidence such as local contrast, noise, and stability under perturbation. An interactive sandbox lets analysts see how changing detector settings affects the results.

<figure>
  <svg viewBox="0 0 460 145" role="img" aria-labelledby="peak-figure-title" style="width:100%;max-width:460px;color:inherit">
    <title id="peak-figure-title">Illustrative chromatogram with a small peak beside a larger one</title>
    <path d="M25 12v105h415" fill="none" stroke="currentColor" opacity="0.55" />
    <path d="M25 105 C95 105 116 106 138 97 S166 75 184 95 S223 108 252 99 S276 24 298 24 S320 99 352 103 S413 105 440 105" fill="none" stroke="#008aa1" stroke-width="4" />
    <circle cx="167" cy="86" r="19" fill="none" stroke="#be6334" stroke-width="2" stroke-dasharray="4 3" />
    <text x="104" y="55" fill="currentColor" font-size="14">Candidate for review</text>
    <text x="410" y="137" fill="currentColor" font-size="13">Time</text>
  </svg>
  <figcaption>Illustration of a small peak that may warrant a closer look.</figcaption>
</figure>

The prototype was tested on synthetic chromatograms. Evaluation with analysts and industrial data is future work.

[Try the interactive demo](https://peakaboo.streamlit.app/) · [View the IEEE VIS poster](https://doi.org/10.13140/RG.2.2.26670.68164) · [Browse my research]({{ '/research/' | relative_url }})
