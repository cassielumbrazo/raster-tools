# raster-tools
a place to store useful notebooks and functions for working with raster datasets 

ALL_NCALM_Sites_plots.ipynb 
* NCALM lidar data collected by a successful grant I wrote
* Link to the dataset info here: https://opentopography.org/news/new-ncalm-dataset-eastern-cascade-mountains-washington-now-available
* One of the sites is Fish Lake (FL) which I use throughout the rest of the notebooks in this repo. 

### Other notebooks in this folder
FL_create_netcdf.ipynb
* convert tif files to a tidy netcdf
* reproject_match them all to allign for future analysis 

FL_model_create_netcdf.ipynb
* similar to the previous, except for the entire Fish Lake domain
* most useful addition to this notebook is the *buffer* created around the distance to canopy edge (dce) raster using the erosion tool

FL_create_netcdf_resample.ipynb
* similar to the previous, except resampling the raster dataset from 1 meter resolution to 9 meter (or more) downsample. 

FL_plots.ipynb
* experimenting with visualizing the FL small domain raster dataset 

FL_model_plots.ipynb
* experimenting with visualizing the FL full domain raster dataset 

FL_xdem.ipynb
* creating variograms of the FL raster dataset to determine the extent of the spatial autocorrelation

FL_stats_subsample.ipynb
* subsampling the FL full domain raster to reduce the spatial autocorrelation
* subsampling from the extent determined by the variogram in FL_xdem.ipynb

FL_RandomForest.ipynb
* running the *sklearn* decision trees, random forest model, and partial dependence plots 
  
