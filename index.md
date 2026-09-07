---
layout: default
title: pizzodev — publications
---

# Publications

<ul class="pub-list">
{% for pub in site.data.publications %}
  <li class="pub-item">
    <a href="{{ pub.file | relative_url }}">{{ pub.title }}</a>
    <div class="pub-meta">
      <span class="category">{{ pub.category }}</span>
      <span>{{ pub.date }}</span>
    </div>
    {% if pub.description %}
    <div class="pub-description">{{ pub.description }}</div>
    {% endif %}
  </li>
{% endfor %}
</ul>
