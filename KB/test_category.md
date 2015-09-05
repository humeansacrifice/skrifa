---
layout: page
title: topics
---

##Getting started pages:
<ul>
{% for page in site.pages %}
  {% for topic in page.topics %}
    {% if topic == "Cats" %}
      <li><a href="{{page.url | replace: '/',''}}">{{page.title}}</a></li>
      {% endif %}
  {% endfor %}
{% endfor %}
</ul>
