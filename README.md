hoodie-plugin-overpass
=========================

Draft of hoodie plugin to get openstreetmap data from the overpassapi

Dreamcode API
---

Every call promise to return a geoJSON doc.
```js
overpass.findBbox(selector, [bbox]);
overpass.findBbox('highway=primary', [-0.489, 51.28, 0.236, 51.686]);

overpass.findAround(selector, [lat, lng], dist);
overpass.findAround('building=yes', [51.4, 6.4], 500);

overpass.findIn(areaSelector, selector);
overpass.findIn('name=België - Belgique - Belgien', 'place=town');
```
