Welcome to the Ground Water Data Mapper Documentation!
===================================

.. container:: twocol

   .. container:: leftside

      .. figure:: _statics/file_format.png

   .. container:: rightside

         This tool can be used to retrieve elevations for wells that are missing ground surface elevations.          These ground surface elevations are used for calculating Water Table Elevation (WTE) and are                included as well metadata in the app. It samples a global, 30-meter DEM for each well location,             providing a reasonable estimate for each missing GSE. Please note that its accuracy is limited              and that field-measured GSE measurements are preferable. A file with well locations (lat/long               coordinates) is required as input and a file with GSE’s generated for each well will be ouptut.


Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

To search on Google, visit `Google <https://www.google.com>`_.


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
