---
layout: page
permalink: /publications/
title: publications
years: [2021]
order: 3
---
[Google Scholar](https://scholar.google.com/citations?user=eL8onmAAAAAJ&hl=pt-PT)

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

<img src="../assets/img/IMG_1494.JPG" width="110%" style="float: center;">