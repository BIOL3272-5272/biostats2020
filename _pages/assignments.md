---
layout: archive
title: "Assignments"
permalink: /assignments/
author_profile: true
---

All assignments can be accessed through this page and will be submitted either in class or through Canvas (linked within each assignments page).

{% include base_path %}

{% for post in site.assignments reversed %}
  {% include archive-single-assignment.html %}
{% endfor %}
