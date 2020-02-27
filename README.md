# incidents-map

## Requirements
1. Internet access to following sites
	* https://darksky.net
	* http://gis.richmondgov.com/ArcGIS/rest/services/StatePlane4502/Ener/MapServer/0/query

2. npm
3. incident json file


## How to Run
Accessing local files from chrome browser was blocked. So I had to use live-server to host the incident data file.
[Reference](https://stackoverflow.com/questions/18586921/how-to-launch-html-using-chrome-at-allow-file-access-from-files-mode)

```
$ npm install -g live-server
$ live-server
```
1. Make sure you put your incident file inside ../data/
2. Click "choose file" to import your incident file.
3. Then it will automatically bring up the map.
4. Click on point to see incident detail + weather info.
5. Click on polygon area to see address info.

## Screenshots
First Page

![First Page](../master/screenshots/first_page.png)

Map Loaded

![Map Loaded](../master/screenshots/map_loaded.png)

Address Click

![Address Click](../master/screenshots/polygon_onclick.png)
