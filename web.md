---
layout: page
title: WEB DEVELOPMENT
caption: WEB DEVELOPMENT
permalink: /web/
---

<ul class="post-list project-item">
	{% for project in site.projects %}
      <a class="project-item__title" href="{{ project.url | relative_url }}"><img class='project-item__image' src= "/assets/{{ project.name }}.png" ></a>
  {% endfor %}
</ul>
