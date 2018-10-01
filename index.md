---
layout: default_3dgi18
title: 3D GeoInfo 2018
permalink: /
---

<!-- <div class="alert alert-blue text-center" role="alert">
	We are organising a pre-conference workshop on 3D city models construction and manipulation software. <a href="workshop.html#workshop" class="alert-link">More information</a>
</div> -->

<div class="well"><b>Recent news</b><br/><br/>
	{% assign sorted = site.data.news | sort: 'date' | reverse %}
  {% for news in sorted limit:2 %}
  	<p><small><span class="post-date">{{ news.date | date: "%b %d" }}</span></small> {{ news.news }}</p>
  {% endfor %}
  <a href="news.html">All news</a>
</div>

<div class="table-responsive">
	<table class="table table-bordered table-hover table-condensed">
	  <thead>
	    <tr>
	      <th class="col-xs-2">Day</th>
	      <th class="col-xs-2">Time</th>
	      <th class="col-xs-2 info">ISPRS</th>
	      <th class="col-xs-2 success">3D GeoInfo</th>
	      <th class="col-xs-2 danger">3D Cadastres</th>
	      <th class="col-xs-2 warning">SDSC</th>
	    </tr>
	  </thead>
	  <tbody>
	  	<tr>
				<th>Sun 30 Sep</th>
				<td>9:00 - 17:00</td>
				<td></td>
				<td class="success"><a href="workshop.html">Pre-conference workshop</a></td>
				<td></td>
				<td></td>
	    </tr>
	    <tr>
				<th rowspan="10">Mon 1 Oct</th>
				<td>9:00 - 10:30</td>
				<td colspan="4" class="active">Keynote: Dorine Burmanje<br />Special session: Best of the Netherlands</td>
	    </tr>
	    <tr>
				<td>10:30 - 11:00</td>
				<td colspan="4" class="active">Coffee break ☕ (Foyer)</td>
	    </tr>
			<tr>
				<td>11:00 - 12:30</td>
	      <td class="info"><div class="text-info">X</div></td>
	      <td class="success"><a href="programme.html#vd">Visualisation & dissemination</a></td>
	      <td></td>
	      <td></td>
	    </tr>
	    <tr>
				<td>12:30 - 13:30</td>
				<td colspan="4" class="active">Lunch 🥪 (Foyer)</td>
	    </tr>
			<tr>
	      <td>13:30 - 15:00</td>
	      <td class="info"><div class="text-info">X</div></td>
	      <td class="success"><a href="programme.html#ar">Acquisition & reconstruction</a></td>
	      <td></td>
	      <td></td>
	    </tr>
	    <tr>
				<td>15:00 - 15:30</td>
				<td colspan="4" class="active">Coffee break ☕ (Foyer)</td>
	    </tr>
	    <tr>
	      <td>15:30 - 16:55</td>
	      <td class="info" rowspan="2"><div class="text-info">X</div></td>
	      <td class="success"><a href="programme.html#nmas1">NMAs I (EuroSDR/Volta)</a></td>
	      <td></td>
	      <td></td>
	    </tr>
	    <tr>
				<td>16:55 - 17:00</td>
				<td class="active">Short break</td>
				<td></td>
				<td></td>
	    </tr>
	    <tr>
	      <td>17:00 - 18:00</td>
	      <td></td>
	      <td class="success"><a href="programme.html#nmas2">NMAs II (EuroSDR/Volta)</a></td>
	      <td></td>
	      <td></td>
	    </tr>
	    <tr>
	      <td>18:30 - 20:30</td>
	      <td colspan="4" class="active">Welcome reception 🥂 (Foyer)</td>
	    </tr>
			<tr>
	      <th rowspan="12">Tue 2 Oct</th>
	      <td>8:00 - 9:00</td>
	      <td></td>
	      <td class="success"><a href="programme.html#m1">Modelling I</a></td>
	      <td></td>
	      <td></td>
	    </tr>
	    <tr>
				<td>9:00 - 9:05</td>
				<td class="info" rowspan="2"><div class="text-info">X</div></td>
				<td class="active">Short break</td>
				<td></td>
				<td></td>
	    </tr>
	    <tr>
	      <td>9:05 - 10:30</td>
	      <td class="success"><a href="programme.html#a1">Applications I</a></td>
	      <td></td>
	      <td></td>
	    </tr>
	    <tr>
				<td>10:30 - 11:00</td>
				<td colspan="4" class="active">Coffee break ☕ (Foyer)</td>
	    </tr>
	    <tr>
				<td>11:00 - 12:30</td>
	      <td class="info"><div class="text-info">X</div></td>
	      <td class="success"><a href="programme.html#a2">Applications II</a></td>
	      <td></td>
	      <td></td>
	    </tr>
	    <tr>
				<td>12:30 - 13:30</td>
				<td colspan="4" class="active">Lunch 🥪 (Foyer)</td>
	    </tr>
	    <tr>
	      <td>13:30 - 15:00</td>
	      <td colspan="4" class="active">Keynote: Claus Nagel<br />Keynote: Rod Thompson<br />Announcement: 3D GeoInfo 2019 in Singapore 🇸🇬</td>
	    </tr>
	    <tr>
				<td>15:00 - 15:30</td>
				<td colspan="4" class="active">Coffee break ☕ (Foyer)</td>
	    </tr>
	    <tr>
	    	<td>15:30 - 16:55</td>
	      <td class="info" rowspan="2"><div class="text-info">X</div></td>
	      <td class="success"><a href="programme.html#p">Processing</a></td>
	      <td class="danger" rowspan="2"><div class="text-danger">X</div></td>
	      <td></td>
	    </tr>
	    <tr>
				<td>16:55 - 17:00</td>
				<td class="active">Short break</td>
				<td></td>
	    </tr>
	    <tr>
	      <td>17:00 - 18:00</td>
	      <td></td>
	      <td class="success"><a href="programme.html#m2">Modelling II</a></td>
	      <td></td>
	      <td></td>
	    </tr>
	    <tr>
	      <td>19:00 - </td>
	      <td colspan="4" class="active"><a href="practicalinfo.html#dinner">Conference dinner 🍽️</a></td>
	    </tr>
			<tr>
	      <th rowspan="7">Wed 3 Oct</th>
	      <td>9:00 - 10:30</td>
	      <td class="info"><div class="text-info">X</div></td>
	      <td></td>
	      <td class="danger"><div class="text-danger">X</div></td>
	      <td></td>
	    </tr>
	    <tr>
				<td>10:30 - 11:00</td>
				<td colspan="4" class="active">Coffee break ☕ (Foyer)</td>
	    </tr>
	    <tr>
	      <td>11:00 - 12:30</td>
	      <td class="info"><div class="text-info">X</div></td>
	      <td></td>
	      <td class="danger"><div class="text-danger">X</div></td>
	      <td></td>
	    </tr>
	    <tr>
				<td>12:30 - 13:30</td>
				<td colspan="4" class="active">Lunch 🥪 (Foyer)</td>
	    </tr>
	    <tr>
	      <td>13:30 - 15:00</td>
	      <td class="info"><div class="text-info">X</div></td>
	      <td></td>
	      <td class="danger"><div class="text-danger">X</div></td>
	      <td></td>
	    </tr>
	    <tr>
				<td>15:00 - 15:30</td>
				<td colspan="4" class="active">Coffee break ☕ (Foyer)</td>
	    </tr>
	    <tr>
	      <td>15:30 - 17:00</td>
	      <td class="info"><div class="text-info">X</div></td>
	      <td></td>
	      <td class="danger"><div class="text-danger">X</div></td>
	      <td></td>
	    </tr>
	    <tr>
	      <th rowspan="8">Thu 4 Oct</th>
	      <td>9:00 - 10:30</td>
	      <td class="info"><div class="text-info">X</div></td>
	      <td></td>
	      <td class="danger"><div class="text-danger">X</div></td>
	      <td class="warning"><div class="text-warning">X</div></td>
	    </tr>
	    <tr>
				<td>10:30 - 11:00</td>
				<td colspan="4" class="active">Coffee break ☕ (Foyer)</td>
	    </tr>
	    <tr>
	    	<td>11:00 - 12:30</td>
	      <td colspan="4" class="active">Keynote: Antonio Jara<br />Keynote: Ruizhi Chen</td>
	    </tr>
	    <tr>
				<td>12:30 - 13:30</td>
				<td colspan="4" class="active">Lunch 🥪 (Foyer)</td>
	    </tr>  
	    <tr>
	      <td>13:30 - 15:00</td>
	      <td class="info"><div class="text-info">X</div></td>
	      <td></td>
	      <td></td>
	      <td class="warning"><div class="text-warning">X</div></td>
	    </tr>
	    <tr>
				<td>15:00 - 15:30</td>
				<td colspan="4" class="active">Coffee break ☕ (Foyer)</td>
	    </tr>
	    <tr>
	      <td>15:30 - 17:00</td>
	      <td class="info"><div class="text-info">X</div></td>
	      <td></td>
	      <td></td>
	      <td class="warning"><div class="text-warning">X</div></td>
	    </tr>
	    <tr>
	      <td>19:00 - </td>
	      <td colspan="4" class="active">Conference dinner 🍽️ (X - Mekelweg 8-10)</td>
	    </tr>
	    <tr>
	      <th rowspan="7">Fri 5 Oct</th>
	      <td>9:00 - 10:30</td>
	      <td class="info"><div class="text-info">X</div></td>
	      <td></td>
	      <td></td>
	      <td class="warning"><div class="text-warning">X</div></td>
	    </tr>
	    <tr>
				<td>10:30 - 11:00</td>
				<td colspan="4" class="active">Coffee break ☕ (Foyer)</td>
	    </tr>
	    <tr>
	      <td>11:00 - 12:30</td>
	      <td class="info"><div class="text-info">X</div></td>
	      <td></td>
	      <td></td>
	      <td class="warning"><div class="text-warning">X</div></td>
	    </tr>
	    <tr>
				<td>12:30 - 13:30</td>
				<td colspan="4" class="active">Lunch 🥪 (Foyer)</td>
	    </tr>
	     <tr>
	      <td>13:30 - 15:00</td>
	      <td class="info"><div class="text-info">X</div></td>
	      <td></td>
	      <td></td>
	      <td class="warning"><div class="text-warning">X</div></td>
	    </tr>
	    <tr>
				<td>15:00 - 15:30</td>
				<td colspan="4" class="active">Coffee break ☕ (Foyer)</td>
	    </tr>
	    <tr>
	    	<td>15:30 - 17:00</td>
	      <td colspan="4" class="active">Closing session</td>
	    </tr>
	  </tbody>
	</table>
</div>

We are pleased to invite you to the 2018 3D GeoInfo Conference hosted in Delft, Netherlands! Aiming to bring together international researchers from academia, industry and government in the field of 3D geoinformation, the conference offers an interdisciplinary forum to researchers in the fields of data collection, advanced modelling approaches, data analysis and visualisation.

The conference will focus on developments and applications in advanced 3D data and technologies as well as provide a platform for these topics to be discussed and for research ideas to be exchanged. There will also be opportunities to promote international collaboration in geoinformation, 3D data analysis and visualisations. The conference is part of the joint event [Geo Delft 2018](https://www.tudelft.nl/geodelft2018/), taking place October 1-5.

In case of general questions, you can contact [us](mailto:info@3dgeoinfo2018.nl).

<img class="image img-responsive" src="img/Delft-Hall.jpg" /><br />