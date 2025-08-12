---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Full CV can be found here](https://docs.google.com/document/d/1tx__Lh2zrB0vW8Mtqh1QXvuawEudY_IaRh7UmJ7Y_VY/edit?usp=sharing)

Education
======
* Ph.D in English, University of Missouri, 2020
* M.A. in English, California State University-Fullerton, 2015
* B.A. in English, California State University-Fullerton, 2012



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
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
