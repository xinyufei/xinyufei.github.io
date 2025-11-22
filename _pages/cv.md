---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
======
* **Ph.D. in Operations Research and Scientific Computing**  
  *University of Michigan*  
  - GPA: 4.0/4.0
  - Focus: Mixed-integer & stochastic optimization, reinforcement learning
  - Advisor: Prof. Siqian Shen

* **B.S. in Computational and Applied Mathematics**  
  *University of Science and Technology of China (USTC), School for the Gifted Young*

## Work Experience
======
* **Applied Scientist II**  
  *Amazon.com - Scalable Optimization System for Real-Time Labor Planning*  
  - Develop and maintain a Java-based mixed-integer optimization model with a custom enumeration + optimization heuristic for real-time staffing in Amazon fulfillment centers, improving plan acceptance by 15% and generating $38M in annual savings.
  - System was adopted as a production-executed service and expanded across business teams, contributing an additional $40M in yearly savings.
  - Enhance the algorithm with ML classification, improving simulated performance by 4.9% within the same runtime; prototype is pending production integration.

* **Applied Scientist II (Side Project) - LLM-Based Explanation for Optimization Models**  
  *Amazon.com*  
  *Jul 2025 – Present*  
  - Design a general-purpose LLM agent to interpret and explain results from optimization models by parsing given model files (e.g., MIP, LP).
  - Prototype in development; targeting generalizability across problem types and integration with production systems.

* **Research Scientist Intern - Machine Learning Based Ergonomics Stowing Assistance**  
  *Amazon.com*  
  *May 2023 – Aug 2023*  
  - Built an end-to-end pipeline on AWS using SageMaker, developing a decision tree-based prediction model for product dwell time estimation.
  - Designed and integrated an ergonomics-aware stowing recommendation algorithm based on the predictions, reducing dwell time by 80% with sub-0.2s execution latency.

* **Research Scientist Intern - Decomposition Algorithm for Large-scale Resource Planning Problems**  
  *Amazon.com*  
  *May 2022 – Aug 2022*  
  - Developed a dual-decomposition algorithm in Java for large-scale resource planning in transportation networks, achieving up to 17× speed-up over baseline solvers.
  - Improved total planning cost by up to 3% through better convergence and model scalability.

## Technical Focus
======
* **Optimization**: Integer optimization, stochastic optimization, large-scale optimization
* **Machine Learning**: ML-integrated optimization, GenAI agents, reinforcement learning (ongoing research)

## Technical Skills
======
* **Programming Languages**: Python, Java, C++, SQL, Matlab, R
* **Solvers & Tools**: Xpress, Gurobi, AWS (S3, SageMaker, Lambda)

## Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
