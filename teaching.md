---
layout: page
title: teaching
---
{% for course in site.courses reversed %}
  {{ course.term }} - <a href="{{ course.url }}"> {{ course.title }}</a>
  <br>
{% endfor %}
