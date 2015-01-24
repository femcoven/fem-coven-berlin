---
layout: archive
permalink: /schedule/
title: "Schedule"
date: {{ date }}
modified:
excerpt:
image:
  feature: 
  teaser: 
  thumb: 
---

## Upcoming events

<div class="tiles">
{% for post in site.categories.upcoming %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

## Past events

<div class="tiles">
{% for post in site.categories.past %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->