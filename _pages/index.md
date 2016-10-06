---
permalink: /
---

[News][About][Education][Tutorials][Documentation]

TRanslating ENvironmental CHange
--------------------------------

Tools for translating environmental change into organismal responses

**Driving question**: What impact will a X°C (e.g., 2°C) climate warming have on animals and ecosystems?

**Mission**
Many efforts to forecast ecological responses to climate change are based on air temperatures at coarse spatial (degrees) and temporal (months) resolutions, but animals respond to multiple aspects of the environment at scales of minutes and meters.  We aim to improve ecological forecasts by providing computational and visualization tools to address these discrepancies.  Our suite of tools will enable extracting fine spatial and temporal scale microclimate data, translating microclimate (air and surface temperatures, radiation, and wind) conditions into animals body temperatures by calculating energy balances, and mapping body temperatures and regions of thermal stress.  We will also present case studies of how animals are impacted by climate and climate change.  We aim to improve ecological forecasting tools for education, policy, and research.

**Tools**
***Extracting microclimate data***-  We are currently distributing microclimate (hourly, 36km resolution) [data](http://onlinelibrary.wiley.com/doi/10.1002/ecy.1444/full) covering the United States for past (1980-1999) and future (2080-2099) time periods.  The data were created by dynamic downscaling using the Weather Research and Forecasting (WRF) model.  We are working towards providing near real time microclimate data based on satellite observations.  We are also working to expand the geographic scope and time period of the available data.

***Translating microclimate into animal body temperatures***- We aim to develop transparent and accessible energy budget models to translate microclimate into estimates of animal body temperature.  We estimate body temperatures by balancing energy inputs and outputs associated with solar and thermal radiation, conduction (via contact with surfaces), and convection (via air flow).  Our models will be accessible via both an online interface and an R package. We are developing our tools in collaboration with the [NicheMapR](https://twitter.com/nichemapr) initiative.

***Mapping body temperatures and regions of thermal stress***- We are developing a mapping interface to integrate the output of the biophysical models with data on species distributions and regions where animal species are likely to experience thermal stress.  The interface will enable users to explore example species or choose the size, shape, and coloration of a generic ectotherm to model.

***Case studies of how animals are impacted by climate and climate change***- We are developing case studies, informed by our empirical research, illustrating how climate change is impacting animals.

**Acknowledgements**: The TrEnCh project is primarily supported by a National Science Foundation (NSF) Advances in Biological Informatics CAREER grant.  The TrEnCh project has also benefited from additional NSF support (EF-1065638, DEB-1120062).

TrEnCh is open-source ([GitHub repository](https://github.com/trenchproject)) and built using open source software including Bootstrap, node.js, Travis CI, Express, and R.  

