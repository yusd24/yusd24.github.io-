---
layout: page
permalink: /publications/
title: Publications
description: Journal articles and preprints (in reversed chronological order).
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- {% include bib_search.liquid %}  -->

<div class="publications">
 
 {% bibliography --template bib --group_by type,year --group_order ascending,descending %}
 
</div>
