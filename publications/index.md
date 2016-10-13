---
layout: archive
title: "Publications"
date: 2014-05-30T11:39:03-04:00
modified:
#excerpt: "A collection of thoughts, inspiration, mistakes, and other minutia."
tags: []
image:
  feature: posts-1600-800.gif
  teaser: posts_400-250.jpg
  credit: Eduard Bukin
---

<div class="tiles">
{% for post in site.categories.publications %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

