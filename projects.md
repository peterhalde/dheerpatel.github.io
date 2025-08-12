---
layout: default
title: Projects
---

# Projects

Here are some of my key projects in robotics, control systems, and machine learning.

<div class="project-grid">
{% for project in site.projects %}
  <div class="project-card">
    <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
    <p>{{ project.description }}</p>
    <div class="tech-tags">
      {% for tech in project.technologies %}
        <span class="tech-tag">{{ tech }}</span>
      {% endfor %}
    </div>
    {% if project.github %}
    <p><a href="{{ project.github }}">View on GitHub →</a></p>
    {% endif %}
  </div>
{% endfor %}
</div>
