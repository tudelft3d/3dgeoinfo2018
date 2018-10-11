---
layout: default_3dgi18
title: 3D GeoInfo 2018
permalink: /
---

<div class="alert text-center" style="background-color: #2c3e50; color: white;" role="alert">
	The conference has been a great success. Thanks for coming and see you in <a href="https://www.3dgeoinfo2019.com/" style="color: #30bfeb;">Singapore</a>!
</div>

<img class="image img-responsive" src="img/IMG-0199.JPG" />

<div class="well"><b>Recent news</b><br/><br/>
	{% assign sorted = site.data.news | sort: 'date' | reverse %}
  {% for news in sorted limit:3 %}
  	<p><small><span class="post-date">{{ news.date | date: "%b %d" }}</span></small> {{ news.news }}</p>
  {% endfor %}
  <a href="news.html">All news</a>
</div>

We were glad to host the 2018 3D GeoInfo Conference in Delft, Netherlands! Aiming to bring together international researchers from academia, industry and government in the field of 3D geoinformation, the conference offered an interdisciplinary forum to researchers in the fields of data collection, advanced modelling approaches, data analysis and visualisation.

The conference focused on developments and applications in advanced 3D data and technologies, as well as provided a platform for these topics to be discussed and for research ideas to be exchanged. There were also opportunities to promote international collaboration in geoinformation, 3D data analysis and visualisations. The conference was part of the joint event [Geo Delft 2018](https://www.tudelft.nl/geodelft2018/), which took place October 1-5, 2018.

<!-- In case of general questions, you can contact [us](mailto:info@3dgeoinfo2018.nl). -->

<!-- <img class="image img-responsive" src="img/Delft-Hall.jpg" /><br /> -->