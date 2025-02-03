---
layout: page
permalink: /publications/
title: publications
description: My publications in reverse chronological order. Equal contribution is denoted by *.
years: [2025, 2024, 2023, 2022, 2020, 2016]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
