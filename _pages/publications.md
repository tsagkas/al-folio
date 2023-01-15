---
layout: page
permalink: /publications/
title: publications
description:
years: [2023, 2019]
nav: true
navigation_weight: 20
---
<!-- _pages/publications.md -->
<div class="publications">

<!-- <h2 class="year">preprints</h2>
{% bibliography -f papers -q @*[preprint=true]* %} -->

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
