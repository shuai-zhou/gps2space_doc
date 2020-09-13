Overview
========

.. note::
   An accurate and appropriate GIS database depends on the geographic coordinate system (sometimes is used interchangeably with datum) your are using. For example, in the North America, commonly used datums are NAD37, NAD83, and WGS84. Throughout our package, we are using WGS84 datum because WGS84 is commonly used all over the world and it is the default geographic coordinate system for the Global Positioning System (GPS).

   Although the differences between those datums are usually not discernible, we recommend you to check what datum you are using with your data vendor for accurate spatial measures. If your datum is not WGS84, please transform it to WGS84 datum before you using this package.

   This package is released under the MIT License, which exempts the authors and copyright holders from any claim, damages or other liability. We will do our best to guarantee the reliability and validity of our package, but users are responsible for their own work. See Tips for some of our suggestions in using this package to conduct reliable and replicable research.
   
The following shows the available functions of the package:

- ``geodf.df_to_gdf``: This function builds unprojected GeoDataFrame from DataFrame with Lat/Long coordinate pairs
- ``space.buffer_space``: This function calculates buffer-based activity space with user-defined level of aggregation, buffer distance, and projection
- ``space.convex_space``: This function calculates convex hull-based activity space with user-defined level of aggregation and projection
- ``dist.dist_to_point``: This function calculates nearest Point-Point distance with user-defined projection