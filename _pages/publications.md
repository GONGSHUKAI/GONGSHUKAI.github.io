---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% assign categories = site.publications | map: "category" | uniq %}

{% for cat in categories %}
  <h1>{{ cat }}</h1>
  {% for post in site.publications reversed %}
    {% if post.category == cat %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
{% endfor %}
