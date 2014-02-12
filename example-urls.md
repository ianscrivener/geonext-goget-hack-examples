#URL Examples



---
##URL 1 - get a png map image of Bondi Beach suburb (WMS)

http://goget.ianscrivener.com:8080/geoserver/goget/wms?LAYERS=goget:suburb&STYLES=&FORMAT=image/png&SERVICE=WMS&VERSION=1.1.1&REQUEST=GetMap&SRS=EPSG:4283&CQL_FILTER=SSC_NAME%20%3D%20%27Bondi%20Beach%27&BBOX=151.25282221076,-33.899718637133,151.28810969864,-33.880114477198&WIDTH=594&HEIGHT=330

**Demonstrates:**

- CQL Filter/Query (CQL_FILTER)
- Bounding Box (BBOX)




---
##URL 2 - get geo-json data of GoGet pods in NSW (WFS)


http://goget.ianscrivener.com:8080/geoserver/ows?service=WFS&version=1.1.0&request=GetFeature&typeName=goget:pods&outputFormat=text/javascript&CQL_FILTER=state=%27NSW%27&maxfeatures=5


**Demonstrates:**

- geo-json (JSONP)
- CQL Filter/Query (CQL_FILTER)
- Limit records/features returned (maxfeatures)

