---
layout: default
title: Privacy Policies
---

# Privacy Policies

<ul>
  {% for page in site.pages %}
    {% if page.url contains '/privacy-policy/' %}
      <li><a href="{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>