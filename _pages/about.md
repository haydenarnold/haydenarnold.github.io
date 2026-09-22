---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a predoctoral researcher at KAIST's [Center for Digital Humanities and Computational Social Sciences](https://dhcss.kaist.ac.kr/), having recently graduated with a Master of Science in Computational Social Science from the [School of Digital Humanities and Computational Social Sciences](https://ghss.kaist.ac.kr/), where I was advised by Prof. [Taegyoon Kim](https://taegyoon-kim.github.io/). I previously graduated with dual degrees from the University of Arizona in [Computer Science](https://www.cs.arizona.edu/) and [Political Science](https://sgpp.arizona.edu/) with a concentration in Foreign Affairs, where I was advised by Prof. [Yotam Shmargad](https://www.yotamshmargad.com/).

## Selected Publications

{% assign sorted_publications = site.publications | sort: 'date' | reverse %}
{% for post in sorted_publications %}
  {% if post.featured %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

[View all publications →](/publications/)
