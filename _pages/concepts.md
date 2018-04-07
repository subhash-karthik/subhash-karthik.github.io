---
title: "Concepts"
layout: single
permalink: "/concepts/"
toc: true
toc_label: "Contents"
toc_icon: "folder-open"
---
## Statistics
{% for item in site.concepts %}
  {% if item.category=="Statistics" %}
  <h3><a href="{{ item.url }}">{{ item.title }}</a></h3>
  <p>{{ item.description }}</p>
  {% endif %}
{% endfor %}

## Machine Learning

{% for item in site.concepts %}
  {% if item.category=="Machine_Learning" %}
  <h3><a href="{{ item.url }}">{{ item.title }}</a></h3>
  <p>{{ item.description }}</p>
  {% endif %}
{% endfor %}
