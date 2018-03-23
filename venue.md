---
layout: default_3dgi18
title: Venue | 3D GeoInfo 2018
permalink: /venue
---

## Venue

The conference will be held at the Aula Congress Centre and at the Faculty of Architecture and the Built Environment within the Delft University of Technology. Both buildings are just south of the city centre of Delft and a 5-minute walk from each other.

<div class="row">
	<div class="col-xs-8"><img class="image img-responsive" src="img/csm_Aula_99825cc2fd.jpg" /></div>
	<div class="col-xs-4">
		<strong><a href="https://www.tudelft.nl/en/about-tu-delft/contact-and-accessibility/map-and-buildings/building-20/">Aula Congress Centre</a></strong>
		<address>
			Mekelweg 5 <br />
			2628 CC Delft <br />
		</address>
	</div>
</div>
<br />

<div class="row">
	<div class="col-xs-8"><img class="image img-responsive" src="img/csm_Gebouw8_Hoofdingang_BK_34ebcc9dcf.jpg" /></div>
	<div class="col-xs-4">
		<strong><a href="https://www.tudelft.nl/en/about-tu-delft/contact-and-accessibility/map-and-buildings/building-8/">Faculty of Architecture and the Built Environment</a></strong>
		<address>
			Julianalaan 134 <br />
			2628 BL Delft <br />
		</address>
	</div>
</div>
<br />

<style>
.marker {
    display: block;
    border: solid red;
    border-radius: 50%;
    cursor: pointer;
    padding: 0;
}
</style>
<div class="row">
  <div class="col-md-12" id="venuemap" style="height: 350px"></div>
</div>
<script>
  mapboxgl.accessToken = 'pk.eyJ1Ijoia2Vub2hvcmkiLCJhIjoiTlQyblc2ayJ9.cxdc2HKXV1ZsDL5A-GSHFA';
  var venuemap = new mapboxgl.Map({
    container: 'venuemap',
    style: 'mapbox://styles/kenohori/civ755tht00282il15wzp492x',
    center: [4.3720975, 52.007],
    zoom: 13.0
  });
  var markers = {
    "type": "FeatureCollection",
    "features": [{
      "type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [4.37076537084954, 52.00558317932635],
      },
      "properties": {
        "title": "Faculty of Architecture and the Built Environment",
        "description": "Julianalaan 134",
        "icon": "bk.jpg"
      }
    },
    {
    	"type": "Feature",
      "geometry": {
        "type": "Point",
        "coordinates": [4.373491558788913, 52.002213201776584],
      },
      "properties": {
        "title": "Aula Congress Centre",
        "description": "Mekelweg 5",
        "icon": "aula.jpg"
      }
    }]
  }
  // add markers to map
  markers.features.forEach(function(marker) {
    // create a DOM element for the marker
    var el = document.createElement('div');
    el.className = 'marker';
    el.style.backgroundImage = 'url(img/' + marker.properties.icon + ')';
    el.style.width = '50px';
    el.style.height = '50px';

    // add marker to map
    new mapboxgl.Marker(el, {offset: [-25, -25]})
      .setLngLat(marker.geometry.coordinates)
      .setPopup(new mapboxgl.Popup({ offset: 25 })
      .setHTML('<strong>' + marker.properties.title + '</strong><p>' + marker.properties.description + '</p>'))
      .addTo(venuemap);
  });
</script>
<br />

### About Delft

Delft is a small university city located about 50 km south-west of Amsterdam, very close to The Hague and Rotterdam.
It is a lovely city with a rich history, famous for its canals, Delft Blue pottery (Delftware), painter Johannes Vermeer, and its association with the Dutch royal family.
You can read more about the city and its attractions in the [website](https://www.delft.com) of the municipality of Delft.

<img class="image img-responsive" src="img/Delft-Hall.jpg" /><br />

### Getting to Delft

Delft is well connected to the rest of the Netherlands by frequent trains.
From other countries, it is very easy to get to Delft by flying to Amsterdam Schiphol Airport (AMS) or Rotterdam The Hague Airport (RTM).
It is also close to the ferry terminal in Hoek van Holland (for ferries to United Kingdom).
Other less convenient options include the airports in Brussels (BRU) and Eindhoven (EIN).

<div class="row">
	<div class="col-md-12" id="regionmap" style="height: 350px"></div>
</div>
<script>
  mapboxgl.accessToken = 'pk.eyJ1Ijoia2Vub2hvcmkiLCJhIjoiTlQyblc2ayJ9.cxdc2HKXV1ZsDL5A-GSHFA';
  var regionmap = new mapboxgl.Map({
    container: 'regionmap',
    style: 'mapbox://styles/kenohori/civ755tht00282il15wzp492x',
    center: [4.7, 52.15],
    zoom: 8.0
  });
</script>
<br />

<!-- https://www.connexxion.nl/data/upload/Lijnennetkaart%20Delft.pdf -->

### Visa

If you need an invitation letter for a visa application, you can contact <a href="mailto:info@3dgeoinfo2018.nl">us</a>.

<img class="image img-responsive" src="img/0359_2-23.jpg" /><br />