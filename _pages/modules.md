---
layout: archive
title: "Detailed descriptions and resources for each class"
permalink: /modules/
author_profile: true
---

This is the location of the most comprehensive guide to each class / week / homework. A one stop shop. Click on the links for each week below.

{% include base_path %}

{% for post in site.modules reversed %}
  {% include archive-single.html %}
{% endfor %}
