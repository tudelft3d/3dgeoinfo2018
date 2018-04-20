---
layout: default_3dgi18
title: 3D GeoInfo 2018
permalink: /
---

<div class="well"><b>Recent news</b><br/><br/>
	{% assign sorted = site.data.news | sort: 'date' | reverse %}
  {% for news in sorted %}
  	<p><small><span class="post-date">{{ news.date | date: "%b %d" }}</span></small> {{ news.news }}</p>
  {% endfor %}
</div>

We are pleased to invite you to the 2018 3D GeoInfo Conference hosted in Delft, Netherlands! Aiming to bring together international researchers from academia, industry and government in the field of 3D geoinformation, the conference offers an interdisciplinary forum to researchers in the fields of data collection, advanced modelling approaches, data analysis and visualisation.

The conference will focus on developments and applications in advanced 3D data and technologies as well as provide a platform for these topics to be discussed and for research ideas to be exchanged. There will also be opportunities to promote international collaboration in geoinformation, 3D data analysis and visualisations. The conference is part of the joint event [Geo Delft 2018](https://www.tudelft.nl/geodelft2018/), taking place October 1-5.

In case of general questions, you can contact [us](mailto:info@3dgeoinfo2018.nl).

<img class="image img-responsive" src="img/Delft-Hall.jpg" /><br />