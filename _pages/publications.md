---
layout: page
permalink: /publications/
title: Research
nav: true
nav_order: 2
description: "Working Papers, Conference Presentations, and Research Projects"
---

<div class="publications">

  <h2 class="year">Working Papers</h2>
  {% bibliography -q @*[journal=Working Paper]* %}

  <h2 class="year">Publications & Proceedings</h2>
  {% bibliography -q @*[journal!=Working Paper]* %}

</div>
