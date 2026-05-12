---
layout: page
permalink: /research/
title: Research
description: Refereed, non-refereed publications, in-preparation work, and highlight videos in reverse chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>

---

## Research Video Highlights

Selected short video highlights connected to my research projects.

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1.5rem; margin-top: 1.5rem; margin-bottom: 2rem;">

  <div>
    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; border-radius: 8px;">
      <iframe
        src="https://www.youtube.com/embed/VeN9_g5q4xg"
        title="CyberSecurity Research Highlight"
        style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen>
      </iframe>
    </div>
    <h3 style="margin-top: 0.8rem; text-align: center;">CyberSecurity</h3>
    <p style="text-align: justify;">
      Research on detecting vulnerabilities in distributed networks using tools i.e., Nmap & CVE mapping. Focused on building lightweight, automated frameworks for on-site threat detection.
    </p>
  </div>

  <div>
    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; border-radius: 8px;">
      <iframe
        src="https://www.youtube.com/embed/7DjSxm9RX_I"
        title="Machine Learning Research Highlight"
        style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen>
      </iframe>
    </div>
    <h3 style="margin-top: 0.8rem; text-align: center;">Machine Learning</h3>
    <p style="text-align: justify;">
      Applied deep learning and transfer learning to diagnose prostate cancer from MRI scans. Combined medical imaging with neural networks to improve early-stage detection accuracy.
    </p>
  </div>

  <div>
    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; border-radius: 8px;">
      <iframe
        src="https://www.youtube.com/embed/UvLN-YP3xQM"
        title="Systems Research Highlight"
        style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen>
      </iframe>
    </div>
    <h3 style="margin-top: 0.8rem; text-align: center;">Systems</h3>
    <p style="text-align: justify;">
      Designed blockchain-based access control systems for peer-to-peer networks. Worked with smart contracts, consensus protocols, and governance models for secure decentralized architecture.
    </p>
  </div>

</div>
