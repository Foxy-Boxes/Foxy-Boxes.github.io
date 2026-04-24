---
permalink: /
title: "Berk Aydogmus"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello, I am Berk Aydogmus, I am a CS Ph.D. student at Purdue University, advised by [Dr. Kazem Taram](https://mktrm.github.io/)


## Publications {#publications}


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
