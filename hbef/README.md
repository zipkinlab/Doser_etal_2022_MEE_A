### HBEF

Contains all code and data for case study of the foliage-gleaning bird community in the Hubbard Brook Experimental Forest.

+ `hbef-spatial`: directory containing shapefiles of the Hubbard Brook Experimental Forest boundaries for creation of Figure 2 in the manuscript.
+ `hbef-msPGOcc-cross-val.R`: script to run nonspatial multispecies occupancy model with cross-validation.
+ `hbef-msPGOcc-int.R`: script to run nonspatial multispecies occupancy model with an intercept only model for occurrence.
+ `hbef-msPGOcc.R`: script to run nonspatial multispecies occupancy model.
+ `hbef-predict.R`: code to predict species-specific occurrence and species richness from a nonspatial multispecies occupancy model.
+ `hbef-spMsPGOcc-cross-val.R`: script to run spatial multispecies occupancy model with cross-validation.
+ `hbef-spMsPGOcc-int.R`: script to run spatial multispecies occupancy model with an intercept only model for occurrence.
+ `hbef-spMsPGOcc-nn.R`: script to compare spatial multispecies occupancy models fit with different numbers of nearest neighbors.
+ `hbef-spMsPGOcc.R`: script to run spatial multispecies occupancy model.
+ `pfile-1`, `pfile-2`, `pfile-3`, `pfile-sp-1`, `pfile-sp-2`, `pfile-sp-3`: files used to specify initial values when running files across multiple cores from the command line.
+ `summary-hbef.R`: script to perform summary analyses of all model results. Code to produce Figure 2, Table 3, Figure S1, and Figure S2 is in this script.
