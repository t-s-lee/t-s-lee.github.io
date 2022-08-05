---
layout: archive
title: "CV" 
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Here is a 1 page overview: [Tia S. Lee CV PDF](http://b-shields.github.io/files/Benjamin_Shields_CV_2021.pdf)

Education
======

* B.Sc., Mathematics, University of Toronto, 2011
* B.Sc., Chemical Physics, University of Toronto, 2011
* M.A., Chemistry, Princeton University, 2015
* Ph.D., Chemistry, Princeton University, 2019

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Select Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
