---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Hayden, and I'm a second-year Master's student at KAIST's School of Digital Humanities and Computational Social Sciences, where I'm advised by Prof. Taegyoon Kim.

## Selected Publications

{% for pub_file in site.publications %}
  {% if pub_file.path contains "ICWSM2025.md" or pub_file.path contains "UndergraduateThesis.md" %}
    {% include archive-single.html post=pub_file %}
  {% endif %}
{% endfor %}

[View all publications →](/publications/)
