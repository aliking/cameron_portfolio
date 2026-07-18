---
layout: page
---

home page
{% for project in site.projects %}
  <h2> {{ project.title }} </h2>
  <a href="{{ project.url }}">View Project</a>
{% endfor %}
