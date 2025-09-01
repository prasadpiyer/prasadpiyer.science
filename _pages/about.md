---
permalink: /
title: "Autonomous&nbsp;Nanophotonics&nbsp;Lab&nbsp;@&nbsp;CINT"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
carousel_images:
  - banner/cint-buildings.jpg
  - Lab/liquid_crystal_steering.png
  - Lab/Photonic_Ising.png
  - Lab/Quantum_Dot.png
  - Lab/ultrafast_setups.png
  - Lab/self-driving_lab_2.png

carousel_durations:
  - 12000
  - 4000
  - 4000
  - 4000
  - 4000
  - 4000

carousel_titles:
  - "CINT Facility"
  - "Liquid Crystal Steering"
  - "Photonic Ising Machine"
  - "Quantum Dot Platform"
  - "Ultrafast Spectroscopy Setups"
  - "Self-Driving Lab"
---

{% include lab-news-scroll.html %}

{% include carousel.html id="lab-carousel" images=page.carousel_images durations=page.carousel_durations titles=page.carousel_titles interval=4000 %}

Our mission at the **Autonomous Nanophotonics Lab** is to uncover and harness unexplored regimes of light–matter interaction for next-generation information processing.

Machine-learning autonomy drives every aspect of our research: from orchestrating high-throughput nanophotonic experiments that reveal novel physical phenomena, to designing structured photonic systems that perform complex computations at speeds and energy-efficiencies far beyond traditional electronics.

In practice, we:

* deploy autonomous machine-learning framework at the intersection of structured light with ultrafast spectroscopy and structured materials thorugh nanofabrication workflows to discover novel nanoscale light-matter interactions,
* translate these discoveries into reconfigurable photonic hardware for optical and quantum computing, and
* make our adaptive instrumentation and data pipelines openly available to the global *Center for Integrated Nanotechnologies (CINT)* user community.

Whether you are a new CINT user, prospective student, or industry partner, we invite you to collaborate with us and accelerate your research through autonomous experimentation.

## Highlighted Publications

{% comment %} Assign highlighted papers {% endcomment %}
{% assign autoSci = site.publications | where: "title", "AutoSciLab: A Self-Driving Laboratory For Interpretable Scientific Discovery" | first %}
{% assign autoSciTalk = site.talks | where: "title", "AutoSciLab: A Self-Driving Laboratory For Interpretable Scientific Discovery" | first %}
{% assign beamSteer = site.publications | where: "title", "Sub-picosecond steering of ultrafast incoherent emission from semiconductor metasurfaces" | first %}
{% assign sdl = site.publications | where: "title", "Self-driving lab discovers principles for steering spontaneous emission" | first %}

<div class="publications-cards">
  <div class="publication-card">
    <h3><a href="{{ autoSciTalk.url | relative_url }}">{{ autoSciTalk.title }}</a></h3>
    <p class="archive__item-authors">{{ autoSciTalk.authors }}</p>
    <p><em>{{ autoSciTalk.venue }}</em>, {{ autoSciTalk.date | date: '%Y' }}</p>
  </div>

  <div class="publication-card">
    <h3><a href="{{ beamSteer.url | relative_url }}">{{ beamSteer.title }}</a></h3>
    <p class="archive__item-authors">{{ beamSteer.authors }}</p>
    <p><em>{{ beamSteer.venue }}</em>, {{ beamSteer.date | date: '%Y' }}</p>
  </div>

  <div class="publication-card">
    <h3><a href="{{ sdl.url | relative_url }}">{{ sdl.title }}</a></h3>
    <p class="archive__item-authors">{{ sdl.authors }}</p>
    <p><em>{{ sdl.venue }}</em>, {{ sdl.date | date: '%Y' }}</p>
  </div>
</div>
