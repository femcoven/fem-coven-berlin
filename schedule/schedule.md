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

<iframe src="https://www.google.com/calendar/embed?showTitle=0&amp;showPrint=0&amp;showTabs=0&amp;showCalendars=0&amp;height=300&amp;wkst=1&amp;bgcolor=%23ffffff&amp;src=femcoven%40gmail.com&amp;color=%2329527A&amp;ctz=Europe%2FBerlin" style=" border-width:0 " width="400" height="300" frameborder="0" scrolling="no"></iframe>

## Past events

<div class="tiles">
{% for post in site.categories.past %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->