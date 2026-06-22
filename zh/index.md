---
layout: splash
permalink: /zh/
nav: main_zh
header:
  overlay_color: "#000"
  overlay_filter: "0.25"
  overlay_image: /assets/images/cover.jpg
  actions:
    - label: "项目 Projects"
      url: /projects/
    - label: "简历 CV (PDF)"
      url: /assets/cv/Haozhuang_Chi_CV.pdf
excerpt: >
  南洋理工大学博士生，研究自动驾驶与具身智能中的 **多模态 AI / Physical AI**、**世界模型**、**大模型** 与 **VLA**。
---

{% include langbar.html %}

## 您好，我是迟浩壮

<div class="intro-split">
  <div class="intro-text">
    <p>
      我目前是新加坡南洋理工大学机械与航空航天工程学院的博士生四年级，研究方向聚焦于自动驾驶与具身智能领域的多模态人工智能（Physical AI），尤其是世界模型、大模型、VLA 等在复杂动态场景中的感知、预测与决策应用。我在德国完成本科和硕士阶段学习，硕士毕业于慕尼黑工业大学机器人专业，并有奥迪、CARIAD、Continental 和 AUMOVIO 多家行业头部相关工作、实习与项目经历。
    </p>

    <p>
      我的长期目标是构建面向下一代智能交通、自动驾驶和机器人系统的多模态世界模型基础能力，推动 AI 从静态感知走向动态理解、风险推演和可靠决策。我希望将前沿大模型技术真正落地到复杂动态环境中，使系统不仅能够“看懂”场景，还能够理解风险、预测未来演化，并为后续决策提供可解释、可验证的依据。
    </p>

    <p>
      目前我主要围绕多模态世界模型、具身智能系统、内外协同感知、状态理解以及风险建模展开研究。长期关注模型的可解释性、鲁棒性和可复现性，也非常重视研究成果与真实产业需求之间的结合。
    </p>

    <div class="logo-strip">
      <a class="logo-pill" href="https://www.ntu.edu.sg/" target="_blank" rel="noopener"><img src="{{ '/assets/images/logos/automan.png' | relative_url }}" alt="Automan Lab"/></a>
      <a class="logo-pill" href="https://www.ntu.edu.sg/" target="_blank" rel="noopener"><img src="{{ '/assets/images/logos/NTU-Singapore-1024x368.png' | relative_url }}" alt="NTU"/></a>
      <a class="logo-pill" href="https://www.tum.de/" target="_blank" rel="noopener"><img src="{{ '/assets/images/logos/TUM-logo-1-e1646633307305-954x406.png' | relative_url }}" alt="TUM"/></a>
      <a class="logo-pill" href="https://www.uni-stuttgart.de/" target="_blank" rel="noopener"><img src="{{ '/assets/images/logos/Uni_stuttgart_logo.svg.png' | relative_url }}" alt="Uni Stuttgart"/></a>
    </div>

    <div class="logo-strip logo-strip--companies" aria-label="行业经历">
      <a class="logo-pill logo-pill--company" href="https://www.audi.com/" target="_blank" rel="noopener"><img src="{{ '/assets/images/logos/audi_logo.svg' | relative_url }}" alt="Audi"/></a>
      <a class="logo-pill logo-pill--company logo-pill--wide" href="https://cariad.technology/" target="_blank" rel="noopener"><img src="{{ '/assets/images/logos/cariad_logo.svg' | relative_url }}" alt="CARIAD"/></a>
      <a class="logo-pill logo-pill--company logo-pill--wide" href="https://www.aumovio.com/en.html" target="_blank" rel="noopener"><img src="{{ '/assets/images/logos/aumovio_logo.svg' | relative_url }}" alt="AUMOVIO"/></a>
      <a class="logo-pill logo-pill--company logo-pill--wide" href="https://www.continental.com/en/" target="_blank" rel="noopener"><img src="{{ '/assets/images/logos/continental_logo.svg' | relative_url }}" alt="Continental"/></a>
    </div>
  </div>

  <div class="headshot-wrap">
    <img class="headshot" src="{{ '/assets/images/avatar.jpg' | relative_url }}" alt="迟浩壮 个人照片"/>
  </div>
</div>


### Academic × Industry 的展示逻辑（2026–）
- **Academic：**强基线/消融/失败案例、协议清晰、可解释性  
- **Industry：**工程闭环、鲁棒性、成本/速度/部署约束  

## 🔥 News
<div class="news-panel" markdown="1">
- **2026.06：** 🎉🎉 我们的 **Driver-WM** 论文被 **ECCV 2026** 接收！
- **2025.03：** 🎉🎉 我们的 **VLM-DM** 论文被 **IEEE IV** 接收！
</div>

---

## 代表项目
<div class="card-grid">

  <div class="card card--highlight card--highlight-blue">
    <a href="{{ '/zh/projects/vlm-dm/' | relative_url }}"><img src="{{ '/assets/images/card_vlmdm.jpg' | relative_url }}" alt="VLM-DM" /></a>
    <div class="card-body">
      <div class="card-title">VLM-DM <span class="paper-badge paper-badge--blue">IEEE IV 2025</span></div>
      <p class="card-text">统一视觉语言模型实现多任务驾驶员监测（分心/情绪/疲劳），支持 LoRA 参数高效微调。已被 IEEE IV 2025 接收。</p>
      <p><a class="btn btn--primary" href="{{ '/zh/projects/vlm-dm/' | relative_url }}">项目页</a></p>
    </div>
  </div>

  <div class="card">
    <a href="{{ '/zh/projects/' | relative_url }}"><img src="{{ '/assets/images/card_vla.jpg' | relative_url }}" alt="VLA & World Models" /></a>
    <div class="card-body">
      <div class="card-title">VLA & 世界模型</div>
      <p class="card-text">面向安全关键推理的 video-language(-action) 与世界模型 rollout。</p>
      <p><a class="btn btn--primary" href="{{ '/zh/projects/' | relative_url }}">概览</a></p>
    </div>
  </div>

  <div class="card card--highlight">
    <a href="{{ '/driver-wm/' | relative_url }}"><img src="{{ '/assets/images/card_driverwm.jpg' | relative_url }}" alt="Driver-WM" /></a>
    <div class="card-body">
      <div class="card-title">Driver-WM <span class="paper-badge">ECCV 2026</span></div>
      <p class="card-text">交通条件驱动的潜在世界模型，用于车内驾驶员动态 rollout。已被 ECCV 2026 接收。</p>
      <p><a class="btn btn--primary" href="{{ '/driver-wm/' | relative_url }}">项目页</a></p>
    </div>
  </div>

  <div class="card">
    <a href="{{ '/zh/projects/' | relative_url }}"><img src="{{ '/assets/images/card_auttc.jpg' | relative_url }}" alt="AU-TTC" /></a>
    <div class="card-body">
      <div class="card-title">AU‑TTC</div>
      <p class="card-text">逐帧 TTC 回归 + 撞击目标预测（对话式提示）。</p>
      <p><a class="btn btn--primary" href="{{ '/zh/projects/' | relative_url }}">概览</a></p>
    </div>
  </div>

</div>

---

## 快速链接
- **简历（PDF）：** [Haozhuang_Chi_CV.pdf]({{ '/assets/cv/Haozhuang_Chi_CV.pdf' | relative_url }})
- **IV 2025 论文（PDF）：** [VLM-DM_IV2025.pdf]({{ '/assets/papers/VLM-DM_IV2025.pdf' | relative_url }})
- **LinkedIn：** https://www.linkedin.com/in/haozhuang-chi
