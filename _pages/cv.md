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
* System Analysis and Development degree, Federal Institute of Education, Science and Technology of São Paulo, Brazil, 2012
* M.S. in Computer Science, Federal University of São Carlos, Brazil, 2014
* Ph.D in Computer Science and Computational Mathematics, University of São Paulo, Brazil, 2019 (expected)

Work experience
======
* Summer 2015: Teaching Assistant
  * University of São Paulo
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
