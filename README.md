# incidents-map

## Requirements
1. Internet access to following sites
	* https://darksky.net
	* http://gis.richmondgov.com/ArcGIS/rest/services/StatePlane4502/Ener/MapServer/0/query

2. npm
3. incident json file


## How to Run
```
$ npm install -g live-server
$ live-server
```

1. Click "choose file" to import your incident file.
2. Then it will automatically bring up the map.
3. Click on point to see incident detail + weather info.
4. Click on polygon area to see address info.

## Completed
YES.

## How much time did you spend?
4 hours

## Screenshots
First Page

![First Page](../master/screenshots/first_page.png)

Map Loaded

![Map Loaded](../master/screenshots/map_loaded.png)

Address Click

![Address Click](../master/screenshots/polygon_onclick.png)

Incident click

![Incident Click](../master/screenshots/point_onclick.png)