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

Hi! I am a post-doctoral fellow at the Law and Technology Centre, University of Hong Kong. I received my PhD degree from the University of Hong Kong under the supervision of Prof. Ben Kao. My research interests include knowledge-based systems, information extraction and legal technology applications.

Publications
======
  <ul>{% for post in site.publications reversed %}
	{% include archive-single-cv.html %}
  {% endfor %}</ul>
