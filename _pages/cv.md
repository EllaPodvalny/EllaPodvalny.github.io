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
* B.S. in Computational Neuroscience, Bar Ilan University, 2009
* Ph.D in Neuroscience, Weizmann Institute of Science (residence) and Bar Ilan University (award), Israel, 2016

Work experience
======
* 2008-2010: Software engineer 
  * Mellanox Technologies LTD. Tel Aviv, Israel
  
Skills
======
* Programming: Matlab, Python, C
* Data: MEG, ECoG, fMRI

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
