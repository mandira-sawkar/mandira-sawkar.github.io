---
layout: archive
title: "Curriculum vitae (CV)"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Downloadable PDF: Coming soon!

Cover Letter
------
I work at [Amazon International Machine Learning](https://www.amazon.science/working-at-amazon/how-rajeev-rastogis-machine-learning-team-in-india-develops-innovations-for-customers-worldwide), where I research and train models for AutoML and NLP projects. I helped build and currently lead Science efforts for an AutoML platform, EPS. EPS has been used by internal teams to deploy 1,000+ models across 14 Amazon websites, driving $550 million revenue for Amazon businesses like [Subscribe and Save](https://www.amazon.com/b?node=5856181011). My Science work has been published internally at [Amazon Machine Learning Conference (AMLC)](https://www.amazon.science/videos-webinars/amazons-annual-machine-learning-conference-featured-presentations-from-thought-leaders-within-academia) and adopted in external features like [AutoGluon's `infer_limit` feature](https://auto.gluon.ai/0.4.0/tutorials/tabular_prediction/tabular-indepth.html#inference-speed-as-a-fit-constraint). Since early 2022, I have been interested in NLP modeling for a task-oriented chatbot which answers factual product-related questions on [amazon.in](https://www.amazon.in/).


Education
------
* **B.Tech. in Information Technology, Veermata Jijabai Technological Institute, 2017**
  * Thesis: Machine Learning for Anomaly-based Network Intrusion Detection, supervised by Dr. Mahesh Shirole.
  * GPA: 8.74 on 10 ([Transcript](https://adivekar-utexas.github.io/files/Abhishek_Divekar_VJTI_BTech_Transcripts.pdf))
  * Coursework ("A" grades): Data Structures and Algorithms, Discrete Mathematics, Operating Systems, Data Mining, Embedded Systems.
* **M.S. in Computer Science, The University of Texas at Austin, 2023 (expected)**
  * GPA: 4.0 ([Latest Transcript](https://adivekar-utexas.github.io/files/Abhishek_Divekar_University_of_Texas_Unofficial_Transcripts.pdf))
  * Coursework ("A" grades): Deep Learning, Advanced Linear Algebra for Computing, Natural Language Processing, Machine Learning, Online Learning and Optimization, Case Studies in Machine Learning.

Work experience
------

* **Dec 2021 - Present: Applied Scientist II, Amazon.**
  * ML modeling for a task-oriented chatbot that answers factual questions about products on [amazon.in](https://www.amazon.in/). Responsibilities: Intent detection, information retrieval, and knowledge-base curation models.
  * Led product design, implementation and roadmap-planning for production launch of new AutoML platform (Litmus) aimed at accelerating AutoML experimentation for Scientists and Engineers ([Talk at AIMLSys 2022](https://adivekar-utexas.github.io/files/AIMLSys_2022_demo_vF.pdf)).
  * Designed and implemented APIs for Unified Task Framework, an extensible software framework which facilitates extreme interoperability and reuse at all levels: model artifacts, algorithm training/inference code, or entire ML pipelines.
  * Developed Litmus Scalable Dataframe, an efficient drop-replacement for Pandas dataframe which using heterogenous underlying datastructures (list of dicts, Pandas, Dask, cuDF, etc). Compared to native Pandas, LitSDF achieves 15.2x improvement in data-processing speed during realtime ML deployments and 27.7x during batch deployments. 

* **Oct 2020 - Nov 2021: Research Engineer II, Amazon.**
  * Used AmaBERT (BERT-Base pre-finetuned on Amazon product text), to classify products into 10,000+ browsable categories within the Amazon product taxonomy. Increased classification accuracy over existing multi-task FastText model by ~7% (62% to 69%).
  * Co-authored internal papers:
    * "Squeezing the last DRiP: AutoML for cost-constrained Product classification" (Poster at AMLC 2021) ([Talk at Amazon Research Days 2021](https://adivekar-utexas.github.io/files/Squeezing_the_last_DRiP_ARD_2021_slides.pdf)).
    * "CPP Multimodal AutoML Corpus and Benchmark" (Oral at AMLC 2021 Multi-modal workshop).
    * "LEAP: LEAf node Predictions in the wild" (2nd ASCS Applied Science Workshop).

* **Oct 2019 - Sep 2020: Research Engineer, Amazon.**
  * Designed and implemented of data-processing nodes for an internal AutoML platform, contributing 160K lines of Python code. 
  * Developed Docker containers to predict UNSPSC code for ~500MM products on Amazon.com. Developed Depth-first preprocessing which improved latency by 30-50%.
  * Co-authored "Entity Prediction Service: a configurable, end-to-end AutoML system" (Poster at AMLC 2020 AutoML workshop).

* **Aug 2017 - Sep 2019: Software Development Engineer, Amazon.**
  * Designed and implemented multi-device purchase flow used by all Kindle devices in Europe. Launched secure handoff from Kindle to another device using SMS/Email notifications, CSRF tokens and server-side caching, protecting Critical customer data.
  * Developed new REST APIs and integration test framework for worldwide Tier-1 payments service, used by internal businesses including Kindle, Alexa and Amazon Prime to carry out customer payment flows. Parallelized calls to downstream services using Java's ThreadPoolExecutor, reducing API latency by 25%.

* **Summer 2017: Research Assistant, Veermata Jijabai Technological Institute**
  * Supervisor: Mahesh Shirole.
  * Discovered vulnerabilities in ML models trained on popular network-intrusion KDDCUP99 dataset, and proposed hybrid dataset which mitigated these vulnerabilities.
  * First author on full-length paper which appeared in IEEE ICCCS-2018 conference: https://arxiv.org/abs/1811.05372

* **May - July 2016: Software Development Intern, Barclays**
  * Developed prototype to optimize Foreign Exchange transaction time from T+2 days to T+120 seconds (99.93% reduction). Used Ripple blockchain and Node.js.

Skills
------
* **Programming Languages**
  * Proficient (100,000+ lines of code in production): Python, Java
  * Familiar (used at work): SQL, C++, JavaScript/TypeScript
* **Tools**
  * Data Science: PyTorch, Keras, Ray, Pandas, NumPy, Dask, Apache Spark, HuggingFace Transformers.
  * Software Development: Git, Docker, Conda, Streamlit, Flask, JUnit, unittest.
  * Academic: LaTeX, ReadCube Papers, ResearchRabbit.ai.
  * Cloud: Amazon Web Services (Sagemaker, StepFunctions, Elastic Map Reduce, Batch, DynamoDB, EC2, S3).


Publications 
------
(➔<a href="https://adivekar-utexas.github.io/publications/">Abstracts</a>)
<ul>{% for post in site.publications reversed %}
  {% include archive-single-short.html %}
{% endfor %}</ul>
  
Talks and presentations
------
(➔<a href="https://adivekar-utexas.github.io/talks/">Slides and Recording</a>)
<ul>{% for post in site.talks reversed %}
  {% include archive-single-short-talk.html %}
{% endfor %}</ul>
  
Projects
------
(➔<a href="https://adivekar-utexas.github.io/talks/">Technical Reports, Code</a>)
<ul>{% for post in site.teaching %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
  

Service
------
* Reviewer for <i>Amazon Machine Learning Conference (AMLC)</i>, 2022 (NLP and ML Tools tracks).
* Reviewer for <i>2nd International Conference on AI-ML Systems (AIMLSys)</i>.
* Mentored Applied Science Interns: Mudit Agarwal (2021) and Kush Gupta (2022).
* Took ~90 interviews for Applied Science and Software Development Engineer roles.
* Instructor, Amazon ML Summer School 2022. [Press Coverage](https://timesofindia.indiatimes.com/gadgets-news/amazon-india-announces-second-edition-of-machine-learning-summer-school-how-to-apply-and-other-details/articleshow/92076056.cms).
  * I was an instructor at Amazon ML Summer School 2022, which enrolled ~3,000 Indian undergraduate students and helped them learn key ML technologies from Amazon Scientists, making them industry ready for science careers. My role involved teaching a 1-hour long module on Supervised Learning (Decision Trees, Bagging and Boosting algorithms), and a 3-hour Q&A session to clarify student questions on the content.
