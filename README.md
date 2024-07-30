![](assets/Bottom_up.svg)

![](./src/header_.png)
<a href="https://www.python.org/"><img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" align="right" height="48" width="48" ></a>

## About Me
[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&center=true&vCenter=true&width=600&lines=I+am+Currently+a+Ph.D+Student+in+Xiamen+University;+I+Received+My+M.S.+Degree+in+Telecom+from+UNSW;+My+Research+Interests+Include:;+Natural+Language+Processing,+Computer+Vision,+etc.)](https://git.io/typing-svg)

## My Location

<div id="map" style="width: 800px; height: 600px;"></div>

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
  var map = L.map('map').setView([24.522, 118.186], 12);

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

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3237.5774861352344!2d118.0849683150303!3d24.43566728428854!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMjTCsDI2JzA4LjQiTiAxMTjCsDA1JzA1LjciRQ!5e0!3m2!1sen!2s!4v1597822389101!5m2!1sen!2s&zoom=10" width="600" height="450" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>


<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3237.5774861352344!2d118.097558!3d24.437251!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMjTCsDI2JzA4LjQiTiAxMTjCsDA1JzA1LjciRQ!5e0!3m2!1sen!2s!4v1597822389101!5m2!1sen!2s" width="600" height="450" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>

