---
layout: page
permalink: /research/
title: research
description: Research organized by category.
nav: true
nav_order: 2
---

## Works in Progress

{% bibliography --group_by none --query @unpublished %}

## Publications

{% include bib_search.liquid %}

<div class="publications">

{% bibliography --group_by none --query @article[selected=true] %}

</div>
