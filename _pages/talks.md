---
layout: page
permalink: /talks/
title: talks
description: Slides and other material for the talks I have given.
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->
{%- for entry in site.data.talks %}
  <h2 class="year">{{entry.year}}</h2>
  {%- for talk in entry.talks %}
  - **{{talk.day}} {{talk.month}}:** <a href="{{talk.slides | prepend: '/talks/' | relative_url}}" target="_blank">{{talk.title}}</a>
    <br /> *{{talk.occasion}}*

  {% endfor %}
{% endfor %}