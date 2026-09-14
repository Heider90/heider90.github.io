---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- TODO: Fill in your details. A PDF version can be placed in /files/cv.pdf and linked below. -->

Education
======
* Ph.D. in Economics, University Name, Year
* M.Sc. in Economics, University Name, Year
* B.Sc. in Economics, University Name, Year

Work experience
======
* Since Year: Economist
  * Austrian Institute of Economic Research (WIFO), Vienna

Skills
======
* Applied econometrics
* Stata, R, Python

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
