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
  {% bibliography --template bib --group_by type --group_order ascending,descending %}
{% endfor %}

</div>
