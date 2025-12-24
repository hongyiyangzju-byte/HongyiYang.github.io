---
layout: archive
title: "Research Projects"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

Here is a collection of my research projects.

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
