---
layout: default
title: Miejsce konferencji
column: 3
index: 3
---

<div id="mapid"></div>
<script>
	var mymap = L.map('mapid').setView([51.107319, 17.062096], 15);
	L.tileLayer('https://api.tiles.mapbox.com/v4/{id}/{z}/{x}/{y}.png?access_token=pk.eyJ1IjoibWFwYm94IiwiYSI6ImNpejY4NXVycTA2emYycXBndHRqcmZ3N3gifQ.rJcFIG214AriISLbB6B5aw', {
		maxZoom: 18,
		id: 'mapbox.streets'
	}).addTo(mymap);
  var marker = L.marker([51.107319, 17.062096]).addTo(mymap);
  marker.bindPopup("<b>Politechnika Wrocławska</b>").openPopup();
</script>
