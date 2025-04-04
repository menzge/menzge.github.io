---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

My updated CV can be found on [Linkedin](https://www.linkedin.com/in/gesina-menz-61932a320/).

Some information can be found below:

Education
======
* PhD in Scientific Computing, Uppsala Universitet, 2027 (expected)
* MSc in Mathematical Biology, Ecology and Medicine, Heriot-Watt University, 2021
* BSc (Hons) in Mathematics and Biology, University of Edinburgh, 2020


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
  

