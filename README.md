# Tutorials on GEDI Science Data Products

**Author:** ORNL DAAC       
**Date:** August 26, 2021       
**Contact for the ORNL DAAC:** uso@daac.ornl.gov

**Keywords:** lidar, GEDI, AGBD, aboveground biomass

## Overview      
These tutorials demonstrate how to discover, access and use GEDI science data products archived at the ORNL DAAC. 

## GEDI L4A Jupyter Notebooks
1. [Searching and Downloading GEDI L4A Dataset](1_gedi_l4a_search_download.ipynb) ([script](scripts#1-gedi_l4a_search_downloadpy))
2. [Subsetting GEDI L4A Footprints](2_gedi_l4a_subsets.ipynb) ([script](scripts#2-gedi_l4a_subsetspy))
3. [Exploring GEDI L4A data structure](3_gedi_l4a_exploring_data.ipynb)
4. [Accessing GEDI L4A Dataset with NASA OPeNDAP in the Cloud](access_gedi_l4a_hyrax.ipynb) ([script](scripts#access_gedi_l4a_hyraxpy))
5. [Apply correction to AGBD estimates for selected L4A shots](correct_GEDI_L4A_V002_01.ipynb)

## Related Tutorials
More tutorials related to ORNL DAAC data and web services can be found at the [ORNL DAAC Learning](https://daac.ornl.gov/resources/learning/) page.

My notes:
package required: 
requests
datetime
pandas
shapely
geopandas
contextily
h5py
numpy
glob
os
tabulate
contextily
numpy
pandas
matplotlib
IPython
matplotlib_scalebar
scipy

the package of "contextily" cannot found and has not been installed.
The environment is mostly correctly install, although there is one error:
Pip subprocess output:
Pip subprocess error:
ERROR: Could not find a version that satisfies the requirement glob (from versions: none)
ERROR: No matching distribution found for glob 