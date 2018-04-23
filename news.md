---
layout: default_3dgi18
title: 3D GeoInfo 2018
permalink: /news
---

## News

{% assign sorted = site.data.news | sort: 'date' | reverse %}
{% for news in sorted %}
<p><small><span class="post-date">{{ news.date | date: "%b %d" }}</span></small> {{ news.news }}</p>
{% endfor %}

