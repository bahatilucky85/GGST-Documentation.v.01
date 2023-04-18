Welcome to the Ground Water Data Mapper Documentation!
===================================

Water managers in Western Africa and around the world face the daunting task of managing freshwater resources in the face of increased demand from industry, agriculture, climate change, and population growth. As surface water resources become fully allocated, groundwater is increasingly targeted to make up surface water deficits, particularly during periods of drought. As a result, many of our aquifers are not being managed in a sustainable fashion, resulting in reduced water quality, land subsidence, increased pumping costs, and in some cases, the complete exhaustion of an aquifer and the loss of groundwater as a buffer during times of drought.

Mapping Algorithm
algorithm
==========
Even when water managers have access to large data sets of historical groundwater level measurements, at any individual well these measurements often exhibit significant time gaps. Aggregating and synthesizing these well measurements to provide information that supports a holistic assessment of aquifer level sustainability can be a challenging task. In partnership with NASA SERVIR, we have developed a series of algorithms that use these existing well measurements combined with Earth Observation data to analyze changes in water tables and characterize aquifer storage over time. Our approach involves collecting data describing well locations and any historical water level measurements in an aquifer. To evaluate aquifer behavior, we need to impute missing data at each well location so that we have data at each time step for analysis. To impute these data, we use a machine learning approach, to train models to use Earth Observation data to impute (or estimate) missing measurements at each well. Using this approach, we generate a time series for each well and use these data to spatially interpolate the water table at each time step.

These interpolated water table maps can be used to evaluate the sustainability of the aquifer by looking at the changes to aquifer storage over time. We have shown that our approach can deal with gaps resulting from long periods with no measurements at wells, our machine learning algorithms build correlations between existing water level measurements and Earth observations such as water storage changes from the NASA Gravity Recovery and Climate Experiment (GRACE) mission, soil moisture from the Global Land Data Assimilation System (GLDAS), or the Palmer Drought Severity Index (PDSI). These machine learning methods have shown to be remarkably accurate for data imputation and extrapolation. The product of this process is a series of time-varying rasters that can be animated to allow water managers to visualize how the water levels are changing over time and where the aquifer is being stressed. The rasters can also be analyzed to assess the change in aquifer water volume or storage over time – a key indicator of aquifer health and sustainability.


Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

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
