---
title: "Projects"
permalink: /projects/
nav: main
---

{% include langbar.html %}

Selected projects around multimodal AI, autonomous driving, driver monitoring, and world-model-based reasoning.

<div class="card-grid project-grid">
  <div class="card card--highlight-blue" id="vlm-dm">
    <a href="{{ '/projects/vlm-dm/' | relative_url }}"><img src="{{ '/assets/images/card_vlmdm.jpg' | relative_url }}" alt="VLM-DM project card" /></a>
    <div class="card-body">
      <div class="card-title">VLM-DM <span class="paper-badge paper-badge--blue">IEEE IV 2025</span></div>
      <p class="card-text">Unified visual-language model for multitask driver monitoring, covering distraction, emotion, and drowsiness recognition with parameter-efficient LoRA adaptation.</p>
      <p class="project-links">
        <a class="btn btn--primary" href="{{ '/projects/vlm-dm/' | relative_url }}">Project page</a>
        <a class="btn" href="{{ '/assets/papers/VLM-DM_IV2025.pdf' | relative_url }}">Paper PDF</a>
      </p>
    </div>
  </div>

  <div class="card" id="vla-world-models">
    <a href="#vla-world-models"><img src="{{ '/assets/images/card_vla.jpg' | relative_url }}" alt="VLA and world models project card" /></a>
    <div class="card-body">
      <div class="card-title">VLA & World Models</div>
      <p class="card-text">Video-language(-action) interfaces and world-model rollouts for safety-critical perception, planning, and decision support in dynamic driving scenes.</p>
      <p class="project-links"><a class="btn btn--primary" href="#vla-world-models-details">Overview</a></p>
    </div>
  </div>

  <div class="card card--highlight" id="driver-wm">
    <a href="{{ '/driver-wm/' | relative_url }}"><img src="{{ '/assets/images/card_driverwm.jpg' | relative_url }}" alt="Driver-WM project card" /></a>
    <div class="card-body">
      <div class="card-title">Driver-WM <span class="paper-badge">ECCV 2026</span></div>
      <p class="card-text">Traffic-conditioned latent world model for driver-centric in-cabin dynamics rollout, enabling controlled interventions and counterfactual driver-state prediction.</p>
      <p class="project-links">
        <a class="btn btn--primary" href="{{ '/driver-wm/' | relative_url }}">Project page</a>
        <a class="btn" href="https://arxiv.org/abs/2605.05092">arXiv</a>
      </p>
    </div>
  </div>

  <div class="card" id="au-ttc">
    <a href="#au-ttc"><img src="{{ '/assets/images/card_auttc.jpg' | relative_url }}" alt="AU-TTC project card" /></a>
    <div class="card-body">
      <div class="card-title">AU-TTC</div>
      <p class="card-text">Frame-based TTC regression and impact-object prediction through prompting-based video-frame reasoning for safety-oriented driving assistance.</p>
      <p class="project-links"><a class="btn btn--primary" href="#au-ttc-details">Overview</a></p>
    </div>
  </div>
</div>

## Project Notes

<a id="vla-world-models-details"></a>
### VLA & World Models
This thread explores video-language(-action) models and latent world models as interfaces for safety-aware planning, scene understanding, and future-state reasoning.

<a id="au-ttc-details"></a>
### AU-TTC
AU-TTC focuses on prompting-based time-to-collision regression and impact-object prediction from video frames, with an emphasis on interpretable risk cues.
