---
layout: page
title: Privacy Policies
---

# Privacy Policies

<ul>
  {% for page in site.pages %}
    {% if page.url contains '/privacy-policy/' and page.url != '/privacy-policy/' %}
      <li><a href="{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>