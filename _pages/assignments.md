---
layout: archive
title: "Assignments"
permalink: /assignments/
author_profile: true
---

{% include base_path %}

{% for post in site.assignments reversed %}
  {% include archive-single-assignment.html %}
{% endfor %}
