Welcome to the Ground Water Data Mapper Documentation!
===================================

.. image:: _statics/file_format.png 
    :align: left
    
   
This tool can be used to retrieve elevations for wells that are missing ground surface elevations. These ground surface elevations are used for calculating Water Table Elevation (WTE) and are included as well metadata in the app. It samples a global, 30-meter DEM for each well location, providing a reasonable estimate for each missing GSE. Please note that its accuracy is limited and that field-measured GSE measurements are preferable. A file with well locations (lat/long coordinates) is required as input and a file with GSE's generated for each well will be ouptut.

To use this tool, you will need to register your Google account with Google Earth Engine to be able to utilize this service. You can do this at: https://signup.earthengine.google.com/#!/

To practice using this script, download and open the attached set of files (top of the page) and locate the ut_2015-2020_wells csv file.



.. figure:: _statics/file_format.png
   :align:: left
   :figwidth: 85%
   :target: images/navegacion_d.png


tool can be used to retrieve elevations for wells that are missing ground surface elevations. These ground surface elevations are used for calculating Water Table Elevation (WTE) and are included as well metadata in the app. It samples a global, 30-meter DEM for each well location, providing a reasonable estimate for each missing GSE. Please note that its accuracy is limited and that field-measured GSE measurements are preferable. A file with well locations (lat/long coordinates) is required as input and a file with GSE's generated for each well will be ouptut.

To use this tool, you will need to register your Google account with Google Earth Engine to be able to utilize this service. You can do this at: https://signup.earthengine.google.com/#!/

To practice using this script, download and open the attached set of files (top of the page) and locate the ut_2015-2020_wells csv file.
.. note::

   This project is under active development.

Contents
--------

.. toctree::
    :caption: Table of Contents
    :name: mastertoc
    :maxdepth: 1

    api-documentation
    dev-notes
    license

   Background
   Funding
   Application
   Interface
