# QGIS Tutorial

- Has anyone used GIS software?
- Has anyone used statistics software?

## Steps

1. Install [QGIS](https://qgis.org/).
2. Load OpenStreetMap and Satellite layers.
  1. Load [QuickMapServices](https://plugins.qgis.org/plugins/quick_map_services/) plugin.
  2. Load OpenStreetMap and Satellite layers.
  3. Make theme and explain themes.
3. Data for Mexico City can be downloaded [here](https://www.inegi.org.mx/app/areasgeograficas/?ag=09). [Descarga masiva](https://www.inegi.org.mx/app/descarga/?ag=09).
  1. From `702825218744_s.zip`, load layer _fm_ (frente de manzana).
    1. Explain embed layers
    2. Add street names.
    3. Make theme.
  2. Load `09_Manzanas_INV2016_shp.zip`.
    1. Color blocks.
    2. Make heatmap.
    3. Make theme.
4. Export to DXF and image
5. Create print layout
  1. Insert map
  3. Insert legend
  4. Insert scale
  5. Insert grid

## Files

|Filename|Contents|
|----|----|
|889463142607_s.zip|[Cartografía Geoestadística Urbana y Rural Amanzanada. Junio 2016. Ciudad de México](https://www.inegi.org.mx/app/biblioteca/ficha.html?upc=702825218744)|
|702825218744_s.zip|[Cartografía geoestadística urbana y rural amanzanada. Cierre de la Encuesta Intercensal 2015 (Distrito Federal)](https://www.inegi.org.mx/app/biblioteca/ficha.html?upc=702825209100)|
|702825004420_s.zip|[Cartografía geoestadística urbana, Cierre de los Censos Económicos 2014, DENUE 01/2015, Distrito Federal](https://www.inegi.org.mx/app/biblioteca/ficha.html?upc=702825004420)|
|09_Manzanas_INV2016_shp.zip|[INV Manzanas](https://www.inegi.org.mx/app/descarga/?ag=09)|

## Other things to look at

- Table merge ([tutorial](http://www.qgistutorials.com/en/docs/performing_table_joins.html)).
- Spatial join ([tutorial](http://www.qgistutorials.com/en/docs/performing_spatial_joins.html)).
