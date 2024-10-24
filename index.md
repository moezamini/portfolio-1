---
layout: default
title: [Your Name]
---

## Title Placeholder

This is a simple portfolio template to showcase your projects and skills.

## About Me

[Your one paragraph pitch].

## Portfolio

<div class="project-gallery">
  <ul>
    {% for project in site.projects %}
      <li class="project-item">
        <a href="{{ project.url }}">
          <img src="{{ project.image }}" alt="{{ project.title }}">
          <h3>{{ post.title }}</h3>
        </a>
        <p>{{ post.description }}</p>
      </li>
    {% endfor %}
  </ul>
</div>