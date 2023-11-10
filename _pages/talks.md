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
  - **{{talk.day}} {{talk.month}}:** &nbsp; 
  {%- if talk.slides -%}
  <a href="{{talk.slides | prepend: '/talks/' | relative_url}}" target="_blank">{{talk.title}}</a>
  {%- elsif talk.recording -%}
  <a href="{{talk.recording}}" target="_blank">{{talk.title}}</a>
  {%- else -%}
  {{talk.title}}
  {%- endif -%}
  <br />*{{talk.occasion}}* {%if talk.slides and talk.recording %} <br /> <a href="{{talk.recording}}" target="_blank" style="font-weight:500;">Recording</a> {% endif %}
  {% endfor %}
{% endfor %}