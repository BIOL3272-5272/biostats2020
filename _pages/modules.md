---
layout: archive
title: "Detailed descriptions and resorouces for each class"
permalink: /modules/
author_profile: true
---

To access class slides and materials, please click on the links for each week below.

{% include base_path %}

{% for post in site.modules reversed %}
  {% include archive-single.html %}
{% endfor %}
