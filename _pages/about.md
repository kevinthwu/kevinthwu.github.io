---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

Hi! I am a 4th year Ph.D. candidate in the Department of Computer Science, University of Hong Kong, under the supervision of Prof. Ben Kao. My research interests include knowledge base, information extraction and data mining applications.

Publications
======
  <ul>{% for post in site.publications reversed %}
	{% include archive-single-cv.html %}
  {% endfor %}</ul>
