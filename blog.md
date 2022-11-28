---
layout: default
title: My Blog
---

{% if site.show_excerpts %}
  {% include blog.html %}
{% else %}
  {% include archive.html title="Blog Posts" %}
{% endif %}
