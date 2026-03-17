# data/gdf directory in Florida Data Center Map repository
This `/data/gdf` directory contains the `GeoDataFrame` (GeoPandas DataFrame) data objects for each layer of the interactive map, saved as Python binary `.pkl` files. These data files are not saved in the GitHub repository because they exceed the GitHub file size limit for public repositories. But they can be created using the [`()`]() function in the [``]() module.
- `/data/gdf/available_gdf.pkl`: Python binary `.pkl` file of `GeoDataFrame` object for all available land area data for data center construction.
- `/data/gdf/fl_counties_.pkl`: Python binary `.pkl` file of `GeoDataFrame` object for Florida county boundaries and county information.
