---
title: TrenchR: an R package for microclimate and biophysical models
excerpt: Functions for assessing the impact of the environment of organisms.
tags:
  - Biophysical models
  - R Functions
---
We are currently developing an R package TrenchR, which can be installed from a [Github repository](https://github.com/trenchproject/TrenchR).  The package will encompass functions for assessing the impact of the environment of organisms and will serve to increase the transparency of microclimate and biophysical modelling.  While many users will use the package directly for their applications, the package will also drive an interactive online interface.

The package will provide the following categories and specific examples of functions:

* Utility functions
  * degree days: degree days available for development estimated from daily maximum and 
minimum temperatures
  * diurnal variation: hourly temperature estimates from daily maximum and minimum temperatures
  * utility functions for microclimate models: zenith angle, declination angle, etc. 
* Microclimate functions
  * microclimate calculation: implements dynamic model to estimate microclimate based on air and 
surface temperature, radiation, and windspeed
  * temperature profiles: estimates temperature at requested heights using temperature data at discrete 
heights, windspeed, and surface roughness  
  * radiation: estimates the intensity of incoming solar radiation at a specified elevation. 
  * radiation partitioning: partitions radiation into direct and diffuse components based on sky 
clearness
  * cloudiness modelling: models cloud cover based on atmospheric conditions.
* General biophysical models: provides generalized models of heat exchanges between organisms and their environment so that users can build custom biophysical models
  * radiative heat exchange: radiative heat exchange between organisms and their environments 
associated with solar and thermal radiation
  * convective heat exchange: heat exchange between organisms and their surrounding fluid (air or 
water) driven by fluid flow 
  * conductive heat exchange: heat exchange between organisms and the ground due to physical 
contact
  * evaporative heat exchange: heat exchange due to organisms’ evaporative water loss
  * energy balance: estimates the operative temperatures of an organism with specified physical 
properties based on the above components of heat exchange
  * operative temperature models: combines the heat exchange components above to estimate an 
ectothermic organism’s operative temperature based on microclimate input
  * water balance (tentative): models the water balance of an ectothermic organism based on 
microclimate inputs 
* Specific biophysical models: provides biophysical models that have been built for specific organisms based on their physical properties, behavior, environment, and life history. We tentatively plan to provide published biophysical models for the following taxa: lizards, butterflies, grasshoppers, mussels, and limpets. 

The functions will focus on ecothermic organisms, but we may subsequently expand the functions to include endothermic organisms.  We are currently creating ang documenting the functions and developing test cases for the functions. We have developed initial [vignettes](https://github.com/trenchproject/TrenchR/blob/master/vignettes/BioPhysicalUsecase.ipynb) illustrating function use. TrenchR provides related utility to the R package NicheMapR, but TrenchR aims to increase the transparency and reproducibility of microclimate and biophysical modelling with the code accessible and fully documented via Github. 
