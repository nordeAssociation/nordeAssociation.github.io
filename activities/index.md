---
layout: archive
title: "Activities"
date: 2016-10-10
modified:
#excerpt: ""
tags: []
image:
  feature: posts-1600-600.gif
  teaser: posts-400-250.gif
---

<div class="tiles">
{% for post in site.categories.activities %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

