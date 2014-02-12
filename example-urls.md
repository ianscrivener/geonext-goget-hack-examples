#URL Examples



###URL 1 - get a png map image of Bondi Beach suburb (WMS)

http://goget.ianscrivener.com:8080/geoserver/goget/wms?LAYERS=goget:suburb&STYLES=&FORMAT=image/png&SERVICE=WMS&VERSION=1.1.1&REQUEST=GetMap&SRS=EPSG:4283&CQL_FILTER=SSC_NAME%20%3D%20%27Bondi%20Beach%27&BBOX=151.25282221076,-33.899718637133,151.28810969864,-33.880114477198&WIDTH=594&HEIGHT=330

**Demonstrates:**

- CQL Filter/Query (CQL_FILTER)
- Bounding Box (BBOX)




---
###URL 2 - get geo-json data of GoGet pods in NSW (WFS)


http://goget.ianscrivener.com:8080/geoserver/ows?service=WFS&version=1.1.0&request=GetFeature&typeName=goget:pods&outputFormat=text/javascript&CQL_FILTER=state=%27NSW%27&maxfeatures=5


**Demonstrates:**

- geo-json (JSONP)
- CQL Filter/Query (CQL_FILTER)
- Limit records/features returned (maxfeatures)


---
###URL 3 - get map image of GoGet pods in Sydney (WMFS)

http://goget.ianscrivener.com:8080/geoserver/goget/wms?service=WMS&version=1.1.0&request=GetMap&layers=goget:pods&styles=&width=512&height=369&srs=EPSG:4326&format=image/svg+xml&bbox=151.09028579075,-33.947852301991,151.3157818845,-33.785336562551

**Demonstrates:**

- geo-json (JSONP)
- Bounding Box (BBOX)


AJKnXv84fjrb0KIHawS0Tg
---
### URL 4 - HERE map of Sydney

http://image.maps.cit.api.here.com/mia/1.6/mapview?app_id=DemoAppId01082013GAL&app_code=AJKnXv84fjrb0KIHawS0Tg&nord=&c=-33.869059029843946%2C151.1875109355978&z=11&w=800&h=500&f=1