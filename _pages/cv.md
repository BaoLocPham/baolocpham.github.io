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
* B.S. in Software Engineering, FPT University, 2023

Work experience
======

* Mar 2024: AI Engineer
  * GreenNode AI
  * Duties included: Develope AI Platform, NLP Researcher

* Mar 2023: AI Engineer
  * FPT Software - DCI

* Sep 2022: Associate AI Engineer
  * FPT Software AI-Camp

Skills
======
* Software Engineering
* AI Engineering
  * Develope NLP: LLM, NER, Embedding models.
  * Deploying model on High performanced infrastructure.
* Researching:
  * Indepence research.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  