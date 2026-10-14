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
* MS in Artificial Intelligence, Rochester Institute of Technology, 2026
* Post Graduate Certification in Data Science, IIIT- Hyderabad, 2023
* Bachelor of Computer Applications, Indira Gandhi National Open University, 2020

Work experience
======
* Aug 2025 - May 2026: Research Assistant (Advised by Dr. Ashiqur R. Khudabukhsh) | RIT
  * Co-first author paper accepted to EMNLP 2026 Main conference.
  * Built end-to-end LLM-as-judge evaluation pipeline to detect offensive rhetoric in long-context speeches, reaching 83.3% agreement with expert consensus (Cohen’s κ=0.711). Owned prompt optimization and cross-LLM validation to discover argument-sexism across ~94M tokens of multi-turn debate.
  * Released HuggingFace Dataset of 6.7M crawled UK Parliament speeches. Developed psychology-grounded taxonomy for hierarchical classification of speeches conditioned on crawled gender allocations. 
  * Owned evals of LLM: conducted expert-label validation of judge outputs. 

* Apr 2023 - Jul 2024: Machine Learning Engineer | Kloud9.nyc
  * Built a feature engineering and model evaluation pipeline for ghost inventory prediction across 50+ features and multimillion-row datasets, reducing stock discrepancies by 10% and achieving 92% accuracy. 
  * Improved model generalization across diverse store environments by evaluating approximately 10 large datasets, increasing prediction stability by 15%.
  * Reduced analysis runtime from 3 hours to 20 minutes per batch by developing an automated data insights pipeline for production workloads. 
  * Partnered with cross-functional data engineering and business teams to streamline production deployment, and mentored 5+ interns on feature engineering, evaluation and ML best practices, leading to 3 full-time hires.

* Oct 2020 - Apr 2023: Software Engineer | WSP Global
  * Designed and deployed an end-to-end CLI tool that automated onboarding for 60,000+ employees annually, saving 2.5 human-months per year.
  * Reduced operations overhead by 71% by building a PowerShell + SharePoint pipeline for automated project archival notifications and clean-up.
  * Increased database reliability by detecting and resolving duplicate/inconsistent records across 80,000+ employees per month with a Python + Pandas validation system.

  
Skills
======
* Programming Languages: Python, C++, SQL, C, R, Java.
* Natural Language Processing (NLP) and Deep Learning: Hugging Face Transformers, BERT-family models, Fine-tuning, Prompt Engineering, NLI, RAG, Model Evaluation & Calibration, Bias/Fairness Analysis.
* Machine Learning (ML) and Data Science: PyTorch, TensorFlow, scikit-learn, Weights & Biases | Regression, Classification, Time Series Forecasting, Optimization, Statistics.
* Data Engineering and Distributed Systems: Spark, Dask, Pandas, NumPy, Matplotlib.
Cloud Infrastructure and Production: GCP, AWS, Azure, Docker, Flask, Git.


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
