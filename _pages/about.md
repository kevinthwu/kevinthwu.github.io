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

Hi! I am a lecturer at the Tam Wing Fan Innovation Wing, Faculty of Engineering, HKU. I received my PhD degree from the University of Hong Kong under the supervision of Prof. Ben Kao. 
<!-- My research interests include knowledge-based systems, information extraction and legal technology applications. -->
 In my current role, I organize and lead out-of-classroom engineering learning activities. Opportunities for collaboration are welcomed, so please feel free to reach out!


Publications
======
  <ul>{% for post in site.publications reversed %}
	{% include archive-single-cv.html %}
  {% endfor %}</ul>
