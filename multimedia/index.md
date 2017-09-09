---
layout: page
title: Multimedia
---

<div class="projects">
  {% for i in site.multimedia %}
  <div class="project post">
    <h2 class="project-title">
      <a href="{{ i.link }}">
        {{ i.title }}
      </a>
    </h2>
    <span class="project-tagline post-date">
        {{ i.tagline }}
    </span>

    {{ i.content }}


  </div>
  {% endfor %}
</div>
