# Biomass_Estimation_2017
Scripts for Lidar Data Prep, Development of Regression Models, and Forest Biomass Prediction


These scripts represent a workflow from lidar .las files through biomass prediction on a 400m^2 grid.  

Lidar_Data_Prep uses Windows batch commands to execute LasTools functions.  21 overlapping las files are filtered by scan angle and converted to text for processing in GIS.

The other python scripts develop regression models based on lidar cloud metrics and biomass measurements on field plots.  They use those models to generate spatially variegated estimates of biomass.
