---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
---
{% include base_path %}

Education
======
* Ph.D in Computer Science, Arizona State University (2025 - Present)
* M.S. in Computer Science, Arizona State University (2023 - 2025)
* B.E. in Computer Science and Engineering, College of Engineering Guindy, Anna University (2018 - 2022)

Work experience
======
* Research Assistant (Dec 2023 - Present)
  * COGINT Lab, Arizona State University
  * Advisor: Prof. Chitta Baral

* Cloud Engineer (Jul 2022 - Jul 2023)
  * Searce Inc, Bangalore
  
<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Reviewer for EMNLP, AACL
