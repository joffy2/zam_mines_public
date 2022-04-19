# zam_mines_public

Code to acompany paper 'Quasi-experimental analysis indicates new mining developments have not increased deforestation in Zambia' (In Review)

Scripts are in jupyter notebooks running on a R kernal (R version 4.0.5)

Link to GEE script for colalting counfoudners https://code.earthengine.google.com/6397f9c7b5c1d30842425eb998aac3d4 

Link to GEE script for forest loss data https://code.earthengine.google.com/b5d989da4e01858ec92d9101f4a0e8c6 

The Confounders notebook compiles datasets from Google Earth Egnine with confoudners and forest loss varables and clacuates other confoudners. 

The mine_datasets notebook assigns treatment and control value to pixels and uses the counders dataset to create an unmatched dataset for each mine. 

The matching notebook applies stasticla amthcing to create matched dataset for each mine., including the PSM data used as the main analysis and three other datasets used to test the effect of matching set up on reuslts. 

The outcome_analysis notebook applies ststical models for each mine to esiamte the avergage treatment effect using R-INLA. 

Package versions used
 tidyverse_1.3.1 
  forcats 0.5.1
  stringr_1.4.0  
  dplyr_1.0.7     
  purrr_0.3.4     
  readr_2.1.1     
  tidyr_1.1.4    
  tibble_3.1.6    
  ggplot2_3.3.5   
 sf_1.0-5
 gstat_2.0-8
 sp_1.4-6
 raster_3.5-2 
 cowplot_1.1.1
 MetBrewer_0.1.0 
 repr_1.1.3      
 scales_1.1.1
 cem_1.1.29      
 MatchIt_4.3.3  
 INLA_21.11.22
 DHARMa_0.4.5             
