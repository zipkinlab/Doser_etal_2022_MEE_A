### BBS

Contains all code and data for case study of the Black-throated Green Warbler distribution across the eastern USA. 

+ `data`: directory containing the raw BBS data used in the analysis. These data were downloaded directly from the USGS.
+ `bbs-PGOcc-cross-val.R`: script to run nonspatial single species occupancy model with cross-validation.
+ `bbs-PGOcc.R`: script to run nonspatial single species occupancy model.
+ `bbs-data-prep.R`: script to prepare the raw data in the `data` subdirectory for analysis in `spOccupancy`. 
+ `bbs-pred-data-prep.R`: script to prepare the raw data in the `data` subdirectory for prediction across the eastern US in `spOccupancy`.
+ `bbs-predict.R`: code to predict occurrence across the eastern US. 
+ `bbs-spPGOcc-GP-cross-val.R`: script to run spatial single species occupancy model using a full Gaussian process with cross-validation.
+ `bbs-spPGOcc-cross-val.R`: script to run spatial single species occupancy model using an NNGP with cross-validation.
+ `bbs-spPGOcc.R`: script to run spatial single species occupancy model using an NNGP.
+ `bbs-spPGOccGP.R`: script to run spatial single species occupancy model using a full Gaussian process.
+ `pfile-1`, `pfile-2`, `pfile-3`, `pfile-sp-1`, `pfile-sp-2`, `pfile-sp-3`: files used to specify initial values when running files across multiple cores from the command line.
+ `summary-bbs.R`: script to perform summary analyses of all model results. Code to produce Figure 1 and Table 2 is in this script.
