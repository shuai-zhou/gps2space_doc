.. GPS2space documentation master file, created by
   sphinx-quickstart on Fri Jul 24 15:51:12 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

GPS2space v0.1.1
=================

Many data are not readily in spatial format. For example, data from wearable devices, surveys, and social media platform such as Facebook and Twitter have GPS location information, but usually in raw Lat/Long format. For social scientist who do not have strong background in GIS, compiling and analyzing spatial data from the aforementioned sources can be tedious and error-prone. ``GPS2space`` is an open source solution to this issue and can ease the processes of compiling and calculating activity spaces based on raw Lat/Long coordinate pairs.


Description
-----------

The primary goals of ``GPS2space`` are: 1) to build spatial data from raw Lat/Long coordinate pairs and make the process less painful for social scientist with little GIS background; 2) to build minimum bounding geometry from Point using buffer, convex hull methods, and use activity space as building box to calculate shared space at different scales; 3) to calculate the nearest distance from user-defined landmarks (currently only support Point-Point nearest distance query).

.. toctree::
   :maxdepth: 2
   :caption: Getting Started

   Installation <installation>

.. toctree::
  :maxdepth: 1
  :caption: User Guide
  
  Overview <overview>
  Building Spatial Data <building_spatial_data>
  Measuring Activity Space <measuring_activity_space>
  Measuring Distance <measuring_distance>
  Tips <tips>

.. toctree::
  :maxdepth: 1
  :caption: Useful Links

  Useful Links <useful_links>

.. toctree::
  :maxdepth: 1
  :caption: Contributing

  Contributing <contributing>

.. toctree::
  :maxdepth: 1
  :caption: Credits

  Authors <authors>
  
  
  
  
  
  



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
