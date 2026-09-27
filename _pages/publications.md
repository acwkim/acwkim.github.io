---
layout: page
permalink: /Publications/
title: Publications
description: "*: Equal contribution; α–β: Alphabetical author order"
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<div class="publications">

<h2 class="publication-category">Preprints</h2>
{% bibliography --group_by year --query @*[publication_type=preprint]* %}

<h2 class="publication-category">Journal Papers (Including Under Revision)</h2>
{% bibliography --group_by year --query @*[publication_type=journal]* %}

<h2 class="publication-category">Conference Papers</h2>
{% bibliography --group_by year --query @*[publication_type=conference]* %}

<h2 class="publication-category">Workshop Papers</h2>
{% bibliography --group_by year --query @*[publication_type=workshop]* %}

</div>
