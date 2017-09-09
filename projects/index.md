---
layout: page
title: Projects
---

<div class="projects">
  {% for project in site.projects %}
  <div class="project post">
    <h2 class="project-title ">
      <a href="{{ project.website }}">
        {{ project.title }}
      </a>
    </h2>
    <span class="project-tagline post-date">
        {{ project.tagline }}
    </span>
    <h4>Tools Used</h4>
    {%for skill in project.skills%}
    <li>{{skill}}</li>
    {%endfor%}
    <br>
    {{ project.content }}


  </div>
  {% endfor %}
</div>
