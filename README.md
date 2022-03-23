# zam_mines_public

Code to acompany paper 'Quasi-experimental analysis indicates new mining developments have not increased deforestation in Zambia' (In Review)

Scripts are in jupyter notebooks running on a R kernal (R version 4.0.5)

The Confounders notebook compiles datasets from Google Earth Egnine with confoudners and forest loss varables and clacuates other confoudners. 

The mine_datasets notebook assigns treatment and control value to pixels and uses the counders dataset to create an unmatched dataset for each mine. 

The matching notebook applies stasticla amthcing to create matched dataset for each mine., including the PSM data used as the main analysis and three other datasets used to test the effect of matching set up on reuslts. 

The outcome_analysis notebook applies ststical models for each mine to esiamte the avergage treatment effect using R-INLA. 

other attached packages:
 [1] raster_3.5-2    sp_1.4-6        forcats_0.5.1   stringr_1.4.0  
 [5] dplyr_1.0.7     purrr_0.3.4     readr_2.1.1     tidyr_1.1.4    
 [9] tibble_3.1.6    ggplot2_3.3.5   tidyverse_1.3.1


other attached packages:
 [1] rgeos_0.5-8     raster_3.5-2    rgdal_1.5-27    sp_1.4-6       
 [5] sf_1.0-5        forcats_0.5.1   stringr_1.4.0   dplyr_1.0.7    
 [9] purrr_0.3.4     readr_2.1.1     tidyr_1.1.4     tibble_3.1.6   
[13] ggplot2_3.3.5   tidyverse_1.3.1

 [1] cowplot_1.1.1   MetBrewer_0.1.0 GGally_2.1.2    gridExtra_2.3  
 [5] repr_1.1.3      cem_1.1.29      lattice_0.20-45 MatchIt_4.3.3  
 [9] forcats_0.5.1   stringr_1.4.0   dplyr_1.0.7     purrr_0.3.4    
[13] readr_2.1.1     tidyr_1.1.4     tibble_3.1.6    ggplot2_3.3.5  
[17] tidyverse_1.3.1


other attached packages:
 [1] DHARMa_0.4.5    MetBrewer_0.1.0 scales_1.1.1    cowplot_1.1.1  
 [5] VGAM_1.1-5      GGally_2.1.2    repr_1.1.3      gridExtra_2.3  
 [9] broom_0.7.10    spdep_1.1-12    spData_2.0.1    sf_1.0-5       
[13] gstat_2.0-8     INLA_21.11.22   sp_1.4-6        foreach_1.5.1  
[17] Matrix_1.3-4    forcats_0.5.1   stringr_1.4.0   dplyr_1.0.7    
[21] purrr_0.3.4     readr_2.1.1     tidyr_1.1.4     tibble_3.1.6   
[25] ggplot2_3.3.5   tidyverse_1.3.1
