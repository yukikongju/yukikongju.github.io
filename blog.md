---
layout: default
title: "Blog Page"
---

{% if site.show_excerpts %}
  {% include blog.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
