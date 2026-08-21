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

I am a Lecturer at the Innovation Academy, Faculty of Engineering at the University of Hong Kong. My work centers on leading out-of-classroom student development initiatives, empowering emerging engineers to translate theory into real-world impact through hands-on, multidisciplinary projects.

Beyond standard coursework, I design and mentor experiential learning programs, technical competitions, and collaborative engineering challenges. I actively welcome partnerships with educators, industry practitioners, and student teams. Please feel free to reach out to explore potential collaborations.


Publications
======
  <ul>{% for post in site.publications reversed %}
	{% include archive-single-cv.html %}
  {% endfor %}</ul>
