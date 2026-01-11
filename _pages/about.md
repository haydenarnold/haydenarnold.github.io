---
permalink: /
title: "Hayden Arnold"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## About Me

Your about paragraph goes here... 

## Selected Publications

{% for pub_file in site.publications %}
  {% if pub_file. path contains "ICWSM2025.md" or pub_file.path contains "UndergraduateThesis.md" %}
    {% include archive-single.html post=pub_file %}
  {% endif %}
{% endfor %}

[View all publications →](/publications/)
