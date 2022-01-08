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
...

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
