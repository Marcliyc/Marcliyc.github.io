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
* **University of Pennsylvania**, Philadelphia, PA, US *(Aug 2025 – May 2027 expected)*  
  MSE in Data Science, GPA: 4.0/4.0  
  Courses: Observational Studies, Big Data Analytics, AI for Science, Computer Vision, Data-Driven Modeling
* **New York University Shanghai**, Shanghai, China *(Aug 2021 – May 2025)*  
  Bachelor of Science in Data Science with Honors  
  Second Major: Computer Science, Minor: Mathematics  
  GPA: 3.87/4.0
* **New York University**, New York, NY, US *(Aug 2023 – May 2025)*  
  Study Away Program  
  Courses: Machine Learning, NLP, Statistical Learning Theory, Optimization, Algorithms, Databases, Operating Systems, Probability, Statistics, Stochastic Processes, PDE, Real Analysis, Numerical Analysis, Reinforcement Learning

Work experience
======
* **Research Assistant, Han Lab, Penn Medicine**, Philadelphia, PA *(Nov 2025 – Present)*
  * Analyze medical imaging data and apply modern ML methods (CVIT, diffusion, GAN) to large-model development.
  * Refined the GRPO-GR method for visual question answering on blood smear microscopy images, improving Qwen-2.5-VL-3B’s accuracy by 40% with visual reasoning grounding provided in bounding boxes.
* **Research Intern, NYU Center for Data Science**, New York, NY *(Jun 2024 – Mar 2025)*
  * Conducted research on LLM knowledge distillation, AI alignment, and domain adaptation to improve training and inference efficiency.
  * Developed efficient PyTorch experimental frameworks on Linux-based remote clusters.
  * Published one paper at ICML 2025.
* **Teaching Assistant – CIS5200 Machine Learning, UPenn**, Philadelphia, PA *(Aug 2025 – Dec 2025)*
* **Data Engineer Intern, OCBridge**, San Jose, CA *(Oct 2025 – Dec 2025)*
* **Data Analyst Intern, Wison Engineering**, Shanghai, China *(May 2025 – Aug 2025)*

Research interests
======
* Medical imaging and multimodal learning
* PINNs and neural operators for scientific computing
* LLM for Math, Programming, and Reasoning
* Efficient and robust machine learning (distillation, adaptation, alignment)
* Data-driven modeling for AI for Science

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
