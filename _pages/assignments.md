---
layout: archive
title: "Assignments"
permalink: /assignments/
author_profile: true
---

Links to all assignments (including classwork and quizzes) organized by class. All assignments can be accessed through this page and will be submitted either in class or through Canvas (linked within each assignments page). This information can be gleaned from other bits of the course website, but go here to just find the assignments.

The general schedule for assignments is that there is:
- A small homework based on course material due every class (graded for effort, turned in on paper).
- A low stakes quiz based on the readings  in the beginning of each class (turned in on canvas).
- Tuning in your efforts from class, due at the end of each class (graded for effort).
- A more substantial evaluation (problem set, test, midterm, project) about every two weeks.

---

 {% include base_path %}

{% for post in site.assignments reversed %}
  {% include archive-single-assignment.html %}
{% endfor %}
