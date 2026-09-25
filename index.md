---
layout: default
title: pizzodev — publications
---

# Publications

<ul class="pub-list">
{% assign pubs = site.publications | sort: 'date' | reverse %}
{% for pub in pubs %}
  <li class="pub-item">
    <a href="{{ pub.url | relative_url }}">{{ pub.title }}</a>
    <div class="pub-meta">
      <span class="category">{{ pub.category }}</span>
      <span>{{ pub.date | date: "%B %-d, %Y" }} }}</span>
    </div>
    {% if pub.description %}
    <div class="pub-description">{{ pub.description }}</div>
    {% endif %}
  </li>
{% endfor %}
</ul>
