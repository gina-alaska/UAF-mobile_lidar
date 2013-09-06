UAF Mobile Lidar
================

See the [project website: http://gina-alaska.github.io/UAF-mobile_lidar/](http://gina-alaska.github.io/UAF-mobile_lidar/) for details.

Project to track possible route for a mobile LiDAR collection on UAF campus.

Proposed route: [westridge.geojson](https://github.com/gina-alaska/UAF-mobile_lidar/blob/master/west_ridge.geojson) by [Aerometric](http://www.aerometric.com/)


Actual route: [westridge.geojson](https://github.com/gina-alaska/UAF-mobile_lidar/blob/master/actual_loop.geojson) by [Aerometric](http://www.aerometric.com/)

Notes
=====

Converted Proposed Loop (Alaska Albers EPSG:3338) shapefile to GeoJSON using:

```shell
ogr2ogr -t_srs crs:84 -f GeoJSON west_ridge.geojson paths/west_ridge-mobile_lidar.shp
```
