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

.. raw:: html
<div class="row">
		<div class="col-md-4">
			<img class="img-responsive " style="max-height:200px; align-items: center" src="images_scripts/usgs_logo.png" alt="USGS logo"/>
		</div>
		
		<div class="col-md-8">
			<p>
				This tool is meant for retrieving groundwater data files from the USGS National Water Information 
				System (NWIS) data repository. The data from NWIS is only available for areas maintained by USGS. This tool: 
			</p> 
			<ul>
				<li>queries the NWIS database for wells and time series measurements that meet the user-specified time and place parameters</li>
				<li>assigns aquifers to each well</li>
				<li>drops wells that fall outside the aquifer boundary</li>
			</ul>
			<p>The tool requires an aquifers file as input and produces a formatted wells file and time series file (ready for import into the GWDM app). </p>
			<p>To practice using this tool, download and open the attached set of files and locate the UtahMajorAquifers geojson file. </p>
			<a href="https://colab.research.google.com/gist/mdstev1/8086be08d3c7c753dad2ada31aafb85f/nwis-file-retriever.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open NWIS File Retriever In Colab"/></a>
		</div>
	</div>
    
    
    
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
