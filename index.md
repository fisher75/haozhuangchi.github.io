---
layout: splash
permalink: /
nav: main
header:
  overlay_color: "#000"
  overlay_filter: "0.25"
  overlay_image: /assets/images/cover.jpg
  actions:
    - label: "Projects"
      url: /projects/
    - label: "Publications"
      url: /publications/
    # - label: "CV (PDF)"
      # url: /assets/cv/Haozhuang_Chi_CV.pdf
excerpt: >
  PhD (Autonomous Driving & Embodied AI) working on **Multimodal LLMs**, **VLA**, and **World Models** for safety-critical perception, prediction, and decision-making.
---

{% include langbar.html %}

## Hi, I'm Haozhuang 👋

<div class="intro-split">
  <div class="intro-text">
    <p>
      I am a fourth-year Ph.D. candidate at the School of Mechanical and Aerospace Engineering, Nanyang Technological University (NTU), Singapore.
      My research is based in the Automated Driving and Human-Machine System (AutoMan) Lab, led by Prof. Chen Lyu, and I have also been involved in research and industry collaboration through the AUMOVIO-NTU Corporate Lab (ANCL) on campus.
      My work focuses on multimodal artificial intelligence for autonomous driving and embodied intelligence (Physical AI), especially world models, large models, and visual-language(-action) models for perception, prediction, and decision-making in complex dynamic scenes.
    </p>

    <p>
      My long-term goal is to build foundational multimodal world-model capabilities for next-generation intelligent transportation, autonomous driving, and robotic systems.
      I want to help AI move beyond static perception toward dynamic understanding, risk-aware future rollout, and reliable decision support, so that systems can not only recognize a scene but also reason about risks, forecast future evolution, and provide interpretable and verifiable evidence for downstream decisions.
      I currently work on multimodal world models, embodied AI systems, in-cabin/out-cabin collaborative perception, state understanding, risk modeling, and reliable evaluation protocols, with a strong emphasis on interpretability, robustness, reproducibility, and alignment with real industrial needs.
    </p>

    <p>
      I aim to turn fast-moving ideas into measurable, reproducible systems: end-to-end pipelines from data and training to robust benchmarking and demo-ready deliverables.
      Previously, I completed my B.Sc. at the University of Stuttgart and my Robotics, Cognition, Intelligence (RCI) M.Sc. at the Technical University of Munich (TUM), with work, internship, and project experience across Audi, CARIAD, Continental, and AUMOVIO.
    </p>

    <div class="logo-strip">
      <a class="logo-pill" href="https://www.ntu.edu.sg/" target="_blank" rel="noopener">
        <img src="{{ '/assets/images/logos/automan.png' | relative_url }}" alt="Automan Lab"/>
      </a>
      <a class="logo-pill" href="https://www.ntu.edu.sg/" target="_blank" rel="noopener">
        <img src="{{ '/assets/images/logos/NTU-Singapore-1024x368.png' | relative_url }}" alt="NTU"/>
      </a>
      <a class="logo-pill" href="https://www.tum.de/" target="_blank" rel="noopener">
        <img src="{{ '/assets/images/logos/TUM-logo-1-e1646633307305-954x406.png' | relative_url }}" alt="TUM"/>
      </a>
      <a class="logo-pill" href="https://www.uni-stuttgart.de/" target="_blank" rel="noopener">
        <img src="{{ '/assets/images/logos/Uni_stuttgart_logo.svg.png' | relative_url }}" alt="University of Stuttgart"/>
      </a>
    </div>

    <div class="logo-strip logo-strip--companies" aria-label="Industry experience">
      <a class="logo-pill logo-pill--company" href="https://www.audi.com/" target="_blank" rel="noopener">
        <img src="{{ '/assets/images/logos/audi_logo.svg' | relative_url }}" alt="Audi"/>
      </a>
      <a class="logo-pill logo-pill--company logo-pill--wide" href="https://cariad.technology/" target="_blank" rel="noopener">
        <img src="{{ '/assets/images/logos/cariad_logo.svg' | relative_url }}" alt="CARIAD"/>
      </a>
      <a class="logo-pill logo-pill--company logo-pill--wide" href="https://www.aumovio.com/en.html" target="_blank" rel="noopener">
        <img src="{{ '/assets/images/logos/aumovio_logo.svg' | relative_url }}" alt="AUMOVIO"/>
      </a>
      <a class="logo-pill logo-pill--company logo-pill--wide" href="https://www.continental.com/en/" target="_blank" rel="noopener">
        <img src="{{ '/assets/images/logos/continental_logo.svg' | relative_url }}" alt="Continental"/>
      </a>
    </div>
  </div>

  <div class="headshot-wrap">
    <img class="headshot" src="{{ '/assets/images/avatar.jpg' | relative_url }}" alt="Haozhuang Chi portrait"/>
  </div>
</div>

### Open for Jobs globally (2027–)
**Graduation:** before Jan 2027.

## 🔥 News
<div class="news-panel" markdown="1">
- **2026.06:** 🎉🎉 Our **Driver-WM** paper has been accepted by **ECCV 2026**. Cheers!
- **2025.03:** 🎉🎉 Our **VLM-DM** paper has been accepted by **IEEE IV**. Cheers!
</div>

### Academic × Industry positioning (2026–)
- **Academic:** rigorous experiments, publications, interpretability, failure-case analysis  
- **Industry:** end-to-end pipelines (data → training → eval → demo), robustness, deployment constraints  



---

## Featured Projects
<div class="card-grid">

  <div class="card card--highlight card--highlight-blue">
    <a href="{{ '/projects/vlm-dm/' | relative_url }}"><img src="{{ '/assets/images/card_vlmdm.jpg' | relative_url }}" alt="VLM-DM" /></a>
    <div class="card-body">
      <div class="card-title">VLM-DM <span class="paper-badge paper-badge--blue">IEEE IV 2025</span></div>
      <p class="card-text">Unified VLM for multitask driver monitoring with LoRA (distraction / emotion / drowsiness). Accepted by IEEE IV 2025.</p>
      <p><a class="btn btn--primary" href="{{ '/projects/vlm-dm/' | relative_url }}">Project page</a></p>
    </div>
  </div>

  <div class="card">
    <a href="{{ '/projects/' | relative_url }}#vla-world-models"><img src="{{ '/assets/images/card_vla.jpg' | relative_url }}" alt="VLA & World Models" /></a>
    <div class="card-body">
      <div class="card-title">VLA & World Models</div>
      <p class="card-text">Video-language(-action) interfaces and world-model rollouts for safety & planning.</p>
      <p><a class="btn btn--primary" href="{{ '/projects/' | relative_url }}#vla-world-models">Overview</a></p>
    </div>
  </div>

  <div class="card card--highlight">
    <a href="{{ '/driver-wm/' | relative_url }}"><img src="{{ '/assets/images/card_driverwm.jpg' | relative_url }}" alt="Driver-WM" /></a>
    <div class="card-body">
      <div class="card-title">Driver-WM <span class="paper-badge">ECCV 2026</span></div>
      <p class="card-text">Traffic-conditioned latent world model for in-cabin driver dynamics rollout. Accepted by ECCV 2026.</p>
      <p><a class="btn btn--primary" href="{{ '/driver-wm/' | relative_url }}">Project page</a></p>
    </div>
  </div>

  <div class="card">
    <a href="{{ '/projects/' | relative_url }}#au-ttc"><img src="{{ '/assets/images/card_auttc.jpg' | relative_url }}" alt="AU-TTC" /></a>
    <div class="card-body">
      <div class="card-title">AU‑TTC</div>
      <p class="card-text">Frame-based TTC regression + impact object prediction via prompting.</p>
      <p><a class="btn btn--primary" href="{{ '/projects/' | relative_url }}#au-ttc">Overview</a></p>
    </div>
  </div>

</div>

---

## Quick links
- **CV (PDF):** [Haozhuang_Chi_CV.pdf]({{ '/assets/cv/Haozhuang_Chi_CV.pdf' | relative_url }})
- **IV 2025 paper (PDF):** [VLM-DM_IV2025.pdf]({{ '/assets/papers/VLM-DM_IV2025.pdf' | relative_url }})
- **LinkedIn:** https://www.linkedin.com/in/haozhuang-chi
