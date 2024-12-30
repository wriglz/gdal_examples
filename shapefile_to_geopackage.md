# Convert a Shapefile to a Geopackage

In a terminal, use:

`ogr2ogr -f GPKG your.gpkg firstfile.shp`

You can then add a second shapefile to the same geopackage using: 

`ogr2ogr -append -f GPKG your.gpkg secondfile.shp`
