ALADIM: Automatic LAndslide Detection and Inventory Mapping from S2 multispectral data 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


# ALADIM: Automatic LAndslide Detection and Inventory Mapping

.. image:: assets/tuto_aladim_icon.png 

**ALADIM**

This service is developped by CNRS-EOST (Strasbourg, France). It allows to detect and map new landslides triggered by large forcing events (earthquake, heavy rains) from the analysis of pre- and post-event imagery, and is based on change detection methods. It allows the processing of High Resolution multispectral data (Sentinel-2 SAFE files). Another version of the code (ALADIM-VHR) allows the processing of Very-High Resolution multispectral data (typically Pléiades and Spot 6/7). The set of pre- and post-image should be accurately co-registered to be able to use the service. A training dataset of manually mapped landslides (by digitalization) and the extent of the region of interest (ROI) should be provided as inputs (ESRI shape file-format) by the user. The outputs consist in a database of landslide polygons than can be assimilated to an Earth Observation derived landslide inventory. ALADIM builds on the change detection methodology partially described in Stumpf et al. [2011](#Stumpf2011) and in Stumpf et al. [2014](#Stumpf2014). 


**EO sources supported**:

    - ALADIM-S2 : Sentinel-2 MSI LIC (SAFE file format), retrieved from the GEP catalogue (using OpenSearch queries)
    - ALADIM-VHR: Pléiades and Spot6/7 ortho-images, uploaded manually by the user (using the Upload function)

**Output specifications**

    - xxx
    - xxx
    - xxx
