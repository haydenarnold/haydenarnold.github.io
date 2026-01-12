---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Hayden, and I'm a second-year Master's student at KAIST's [School of Digital Humanities and Computational Social Sciences](https://ghss.kaist.ac.kr/), where I'm advised by Prof. [Taegyoon Kim](https://taegyoon-kim.github.io/).

## Selected Publications

{% for post in site.publications %}
  {% if post.featured %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

[View all publications →](/publications/)
