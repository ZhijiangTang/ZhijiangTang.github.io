---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **M.S. in Artificial Intelligence**, University of Chinese Academy of Sciences — Hangzhou Institute for Advanced Study, 2024.09 – 2027.07 (expected)
  * Advisor: Prof. Jianqiang Huang (Computer Network Information Center, CAS)
  * GPA: 3.9/4.0 · Recommended admission (保研)
  * Honors: National Scholarship (2%), First-class Academic Scholarship (10%), Outstanding Teaching Assistant
* **B.S. in Data Science and Big Data Technology**, Nankai University, 2020.09 – 2024.07
  * GPA: 3.6/4.0 (3.84/4.0 in junior & senior years)
  * Honors: Outstanding Graduate (3%), Class Monitor leading the **12th Zhou Enlai Class** (highest honor at Nankai)

Industry experience
======
* **Algorithm Intern (Agent Post-training)**, Alibaba Group — Qwen Application Algorithm Team, Beijing, 2026.04 – present
  * Built automated agent evaluation pipeline (parsing, inference, metrics, Web GUI); delivered 8k+ train/eval samples at 97.8–100% accuracy, +10pp end-to-end eval usability
  * Designed rule-based + LLM-Judge layered rewards for agentic RL; +4pp parameter-call accuracy over SFT; supported Qwen3.5-122B launch (+1.96pp UV conversion in AB test)

* **Algorithm Intern (Long-video Evaluation)**, Bilibili — Multimodal Foundation Model Team, Shanghai, 2025.12 – 2026.03
  * Proposed DSA metric with MLLM scoring; Spearman 0.76 vs. human judgment (paper: Long-CODE, ACM MM 2026 under review)
  * GRPO with SDE rollout for Wan2.1-1.3B; DSA improved 0.12 → 0.18

* **Algorithm Intern (Multimodal Post-training)**, Shopee — Multimodal Foundation Model Team, Shanghai, 2025.06 – 2025.11
  * CompassVL-MoE-30B post-training via VeRL; OpenCompass 38.4 → 43.4, MathVista 77.9, OCRBench 83.2
  * Dual-reward RL for caption completeness & correctness; CCCaption-2B matches Qwen3-VL-32B (**CVPR 2026**, first author)

Research experience
======
* **Multimodal Captioning & Evaluation**, UCAS, 2025.03 – 2026.01
  * Semantic-equivalent image reconstruction for objective caption evaluation; unified multimodal model evaluation framework (2× NeurIPS 2026 under review)

* **ECG Time-Series Benchmark**, UCAS, 2024.10 – 2025.03
  * Built ECGPretrain (~15.9 GB) and 4-task benchmark (classification, detection, forecasting, generation); PSSM model with up to +67.2% over SOTA (**ACM MM 2025**)

Teaching
======
* Teaching Assistant, Natural Language Processing, UCAS, Fall 2024

Skills
======
* **ML/AI**: LLM SFT & RL (GRPO, DAPO), multimodal LLMs, agent evaluation, VeRL, vLLM, PyTorch, transformers
* **Languages**: Python, SQL, LaTeX
* **Tools**: Linux, Git, Claude Code

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Selected awards
======
* National Scholarship, UCAS (2024, top 2%)
* Challenge Cup National Second Prize (2023, top 1%)
* China Undergraduate Mathematical Contest in Modeling — National Second Prize (2022, top 2%)
* National College Student Innovation Training Program (top 10%), DSA medical imaging project
