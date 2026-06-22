---
title: "项目"
permalink: /zh/projects/
nav: main_zh
---

{% include langbar.html %}

这里汇总我围绕多模态人工智能、自动驾驶、驾驶员监测与世界模型推理开展的代表性项目。

<div class="card-grid project-grid">
  <div class="card card--highlight-blue" id="vlm-dm">
    <a href="{{ '/zh/projects/vlm-dm/' | relative_url }}"><img src="{{ '/assets/images/card_vlmdm.jpg' | relative_url }}" alt="VLM-DM 项目卡片" /></a>
    <div class="card-body">
      <div class="card-title">VLM-DM <span class="paper-badge paper-badge--blue">IEEE IV 2025</span></div>
      <p class="card-text">统一视觉语言模型实现多任务驾驶员监测，覆盖分心、情绪与疲劳识别，并结合 LoRA 实现参数高效适配。</p>
      <p class="project-links">
        <a class="btn btn--primary" href="{{ '/zh/projects/vlm-dm/' | relative_url }}">项目页</a>
        <a class="btn" href="{{ '/assets/papers/VLM-DM_IV2025.pdf' | relative_url }}">论文 PDF</a>
      </p>
    </div>
  </div>

  <div class="card" id="vla-world-models">
    <a href="#vla-world-models"><img src="{{ '/assets/images/card_vla.jpg' | relative_url }}" alt="VLA 与世界模型项目卡片" /></a>
    <div class="card-body">
      <div class="card-title">VLA & 世界模型</div>
      <p class="card-text">面向动态驾驶场景的 video-language(-action) 接口与世界模型 rollout，用于安全关键感知、规划和决策支持。</p>
      <p class="project-links"><a class="btn btn--primary" href="#vla-world-models-details">概览</a></p>
    </div>
  </div>

  <div class="card card--highlight" id="driver-wm">
    <a href="{{ '/driver-wm/' | relative_url }}"><img src="{{ '/assets/images/card_driverwm.jpg' | relative_url }}" alt="Driver-WM 项目卡片" /></a>
    <div class="card-body">
      <div class="card-title">Driver-WM <span class="paper-badge">ECCV 2026</span></div>
      <p class="card-text">交通条件驱动的驾驶员中心潜在世界模型，用于车内动态 rollout、受控干预和反事实驾驶员状态预测。</p>
      <p class="project-links">
        <a class="btn btn--primary" href="{{ '/driver-wm/' | relative_url }}">项目页</a>
        <a class="btn" href="https://arxiv.org/abs/2605.05092">arXiv</a>
      </p>
    </div>
  </div>

  <div class="card" id="au-ttc">
    <a href="#au-ttc"><img src="{{ '/assets/images/card_auttc.jpg' | relative_url }}" alt="AU-TTC 项目卡片" /></a>
    <div class="card-body">
      <div class="card-title">AU-TTC</div>
      <p class="card-text">基于视频帧提示推理的 TTC 回归与撞击目标预测，强调面向驾驶安全的可解释风险线索。</p>
      <p class="project-links"><a class="btn btn--primary" href="#au-ttc-details">概览</a></p>
    </div>
  </div>
</div>

## 项目说明

<a id="vla-world-models-details"></a>
### VLA & 世界模型
这一方向关注 video-language(-action) 模型与潜在世界模型如何作为安全规划、场景理解和未来状态推理的接口。

<a id="au-ttc-details"></a>
### AU-TTC
AU-TTC 聚焦于基于视频帧提示的 time-to-collision 回归与撞击目标预测，强调可解释的风险判断依据。
