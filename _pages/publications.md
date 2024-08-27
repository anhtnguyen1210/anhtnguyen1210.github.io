---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<div class="preprints">

{% preprints -f {{ site.scholar.preprint }} %}

</div>


<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>
