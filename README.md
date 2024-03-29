# Analayis of the deforestation impact of new mines in Zambia

Code to accompany paper 'Quasi-experimental analysis indicates new mining developments have not increased deforestation in Zambia'

Morley, J., Buchanan, G., Mitchard, E.T.A. et al. Quasi-experimental analysis of new mining developments as a driver of deforestation in Zambia. Sci Rep 12, 18252 (2022). [https://doi.org/10.1038/s41598-022-22762-4](https://doi.org/10.1038/s41598-022-22762-4) 

Scripts are in jupyter notebooks (in the 'code' folder) running on a R kernel (R version 4.0.5)

  * The 'confounders' notebook compiles datasets from Google Earth Engine and other sources, including forest loss data. 
  * The 'mine_datasets' notebook assigns treatment and control value to pixels and uses the confounders dataset to create an unmatched dataset for each mine. 
  * The 'matching' notebook applies statistical matching to create matched dataset for each mine. 
  * The 'outcome_analysis' notebook applies statistical models for each mine to estimate the average treatment effect using R-INLA.

Google Earth Engine scripts

- Link to GEE script for confounders https://code.earthengine.google.com/b3b44530ead94da990f9d9796e20199c
- Link to GEE script for forest loss data https://code.earthengine.google.com/e1eb59baefbc5989ff6e42a0f4077c19

The 'mines_active_from' csv file details the active from year attributed to all issued large scale mining leases (at February 2020). 

Links to data sources are in the 'data_sources.md' file  

```
# Package versions used
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
```
