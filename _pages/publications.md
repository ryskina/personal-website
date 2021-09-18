---
layout: page
permalink: /publications/
title: publications
description: <span style="color:var(--global-theme-color)">*</span> denotes equal contribution
years: [2021, 2020, 2019, 2017]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
