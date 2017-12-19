---
layout: "page"
title: "Projects"
---

{% for project in site.data.projects %}
  <ul>
    <li> {{project.name}} - {{project.technologies}}</li>
  </ul>
{% endfor %}
