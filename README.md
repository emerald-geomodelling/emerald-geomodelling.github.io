Open source projects published by [Emerald Geomodelling](https://www.emerald-geomodelling.com/)

## Data management
### Data format parsers

* [libsgfdata](https://github.com/emerald-geomodelling/libsgfdata) - Parser for data from geotechnical field investigations in the data format specified in Report 3:2012E from the Swedish Geotechnical Society, with support for additionally fields / extensions from [Geotech AB](https://static1.squarespace.com/static/565c5cc1e4b05079e4c0fcfb/t/587c984bbf629abac09d265f/1484560476906/6-SWE-CPT-LOG-v5.xx.pdf). This includes TOT and CPT files, used by e.g. [NADAG](http://geo.ngu.no/kart/nadag/). 
* [libgeosuitesnd](https://github.com/emerald-geomodelling/libgeosuitesnd) - Parser for the [Trimble](https://www.trimble.com/) GeoSuite[tm] SND export format
* [libgeosuiteprv](https://github.com/emerald-geomodelling/libgeosuiteprv) - Parser for the [Trimble](https://www.trimble.com/) GeoSuite[tm] PRV export format
* [libaarhusxyz](https://github.com/emerald-geomodelling/libaarhusxyz) Parser for the Aarhus Workbench XYZ format for geophysical data.

### Client libraries
* [libnadagclient](https://github.com/emerald-geomodelling/libnadagclient) Client library for the geotechnical database at https://geo.ngu.no/kart/nadag/ comforming to the [libsgfdata](https://github.com/emerald-geomodelling/libsgfdata) datamodel.
* [terrainy](https://github.com/emerald-geomodelling/terrainy) raster download utility library for map imagery and dtm:s. Extends the functionality of e.g. contextily.

### Database access
* [PandasIO](https://github.com/emerald-geomodelling/PandasIO) Reimplementation of pandas.DataFrame.to_sql and pandas.read_sql_query with more control over the SQL side of things such as adding support for primary and foreign keys as well serializing extra columns to JSON.


## Processing libraries
* [EmeraldTriangles](https://github.com/emerald-geomodelling/EmeraldTriangles) Transformations and manipulation of 2d triangle meshes, including refining and merging of meshes as well as import and export to various formats.
* [emerald-shapeutils](https://github.com/emerald-geomodelling/emerald-shapeutils) Varios tools for sampling along Shapely shapes

## GUI & plotting
* [BokehGarden](https://github.com/emerald-geomodelling/BokehGarden) A [Bokeh](https://bokeh.org/) based web application
framework focused on plotting heavy interactive applications. Additionally, it provides several improved widgets for Bokeh, that can
be used both within the framework and in a standalone bokeh app, such as an interactive colorbar, file download/upload buttons and an autocomplete input field.

# Contributions to existing open source projects

* [scikit-gstat](https://github.com/mmaelicke/scikit-gstat) A scipy-styled analysis module for geostatistics. We have contributed optimizations for processing large datasets.
