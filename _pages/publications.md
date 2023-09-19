---
layout: page
permalink: /publications/
title: Publications
years: [2022]
nav: false 
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography --template bib --group_by type,year --group_order ascending,descending %}
{% endfor %}

</div>
