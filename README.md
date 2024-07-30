![](assets/Bottom_up.svg)



<!--   my-header-img -->
![](./src/header_.png)
<a href="https://www.python.org/"><img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" align="right" height="48" width="48" ></a>

## About Me
<!--   my-ticker -->    
[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&center=true&vCenter=true&width=600&lines=I+am+Currently+a+Ph.D+Student+in+Xiamen+University;+I+Received+My+M.S.+Degree+in+Telecom+from+UNSW;+My+Research+Interests+Include:;+Natural+Language+Processing,+Computer+Vision,+etc.)](https://git.io/typing-svg)




## My Location


<!-- Belarus - My Home-->
  
 ```geojson

{
 "type": "FeatureCollection",
 "features": [
   {
     "type": "Feature",
     "id": 1,
     "properties": {
       "ID": 0
     },
     "geometry": {
       "type": "Polygon",
       "coordinates": [
         [
             [118.084968, 24.435667],
             [118.308968, 24.608667]

         ]
       ]
     }
   }
 ]
}

```

<img src="/github-metrics.svg" alt="Metrics" width="100%">



![](assets/Bottom_up.svg)

![](./src/header_.png)
<a href="https://www.python.org/"><img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" align="right" height="48" width="48" ></a>

## About Me
[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&center=true&vCenter=true&width=600&lines=I+am+Currently+a+Ph.D+Student+in+Xiamen+University;+I+Received+My+M.S.+Degree+in+Telecom+from+UNSW;+My+Research+Interests+Include:;+Natural+Language+Processing,+Computer+Vision,+etc.)](https://git.io/typing-svg)

## My Location

<div id="map" style="width: 600px; height: 400px;"></div>

<script>
// Add Leaflet CSS
var link = document.createElement('link');
link.rel = 'stylesheet';
link.href = 'https://unpkg.com/leaflet/dist/leaflet.css';
document.head.appendChild(link);

// Add Leaflet JS
var script = document.createElement('script');
script.src = 'https://unpkg.com/leaflet/dist/leaflet.js';
script.onload = function() {
  var map = L.map('map').setView([24.522, 118.196], 12);

  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
  }).addTo(map);

  fetch('https://gist.githubusercontent.com/YOUR_GIST_URL/raw')
    .then(function(response) {
      return response.json();
    })
    .then(function(data) {
      L.geoJSON(data).addTo(map);
    });
};
document.body.appendChild(script);
</script>


