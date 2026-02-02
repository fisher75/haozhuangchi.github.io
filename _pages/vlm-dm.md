---
title: "VLM-DM (IEEE IV 2025)"
permalink: /projects/vlm-dm/
---

**Paper (PDF):** [VLM-DM: Visual Language Models for Multitask Domain Adaptation in Driver Monitoring](/assets/papers/VLM-DM_IV2025.pdf)  
**Authors:** Haozhuang Chi, Haohan Yang, Lie Yang, Chen Lv

---

## Problem
Driver monitoring systems often train **separate models** for different driver states (e.g., distraction, drowsiness, emotion).
This increases maintenance cost and makes the overall system less interpretable and less scalable across datasets/domains.

## Key idea
Build a unified **Visual Language Model (VLM)** pipeline that can **execute multiple driver monitoring tasks simultaneously** by:
- using **text prompts** to specify the task,
- leveraging a **vision encoder** for visual tokens,
- using an **LLM** for reasoning / output generation,
- applying **LoRA** (parameter-efficient fine-tuning) + **dynamic prompt tuning** to adapt efficiently.

## Contributions (as stated in the paper)
- A cohesive multitask framework aligning task-specific requirements for distraction, emotion, and drowsiness.  
- Parameter-efficient fine-tuning via **LoRA** without sacrificing performance.  
- Extensive evaluation on **three benchmark datasets**, achieving better multitask accuracy than several baselines.

## Datasets (3 tasks)
- **SAM-DD**: distracted driving behaviors (10 classes)  
- **KMU-FED**: driver facial expressions (6 classes)  
- **NTHU-DDD**: drowsiness (2 classes)

## Results (key numbers)
### Backbone comparison (Table II in paper)
Using the same multitask setting, **ViT** backbone shows the best overall performance:
- **Overall accuracy / F1 (ViT): 0.964 / 0.963**

### Multitask framework comparison (Table III in paper, ViT backbone)
**VLM-DM** achieves:
- SAM-DD: **0.973 acc / 0.987 F1**  
- KMU-FED: **0.976 acc / 0.988 F1**  
- NTHU-DDD: **0.979 acc / 0.979 F1**  
- **Overall: 0.976 acc / 0.985 F1**

It outperforms several multitask baselines reported in the paper (e.g., CrossStitch, MTAN, MoE, TaskMoE).

## Artifacts
- Paper PDF: **[VLM-DM_IV2025.pdf](/assets/papers/VLM-DM_IV2025.pdf)**

## How to cite (BibTeX)
```bibtex
@inproceedings{chi2025vlm_dm,
  title     = {VLM-DM: Visual Language Models for Multitask Domain Adaptation in Driver Monitoring},
  author    = {Chi, Haozhuang and Yang, Haohan and Yang, Lie and Lv, Chen},
  booktitle = {IEEE Intelligent Vehicles Symposium (IV)},
  year      = {2025}
}
```
