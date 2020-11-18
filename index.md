---
layout: single
author_profile: true
title: "The Trench Project"
header:
   overlay_image: assets/images/buckskin.jpg
   caption: "Photo Credit: [**Tony Cannistra**](http://www.anthonycannistra.com)"
   cta_label: "Jump to Tools."
   cta_url: /tools
---
# THIS IS AN ARCHIVED SITE. PLEASE VISIT OUR [CURRENT SITE](http://www.trenchproject.com)

**TrEnCh:** Tools for TRanslating ENvironmental CHange into organismal responses.

We build computational and visualization tools to translate environmental change into organismal responses.

**Driving question**: What impact will a X°C (e.g., 2°C) climate warming have on animals and ecosystems?

## Mission
Many efforts to forecast ecological responses to climate change are based on air temperatures at coarse spatial (degrees) and temporal (months) resolutions, but animals respond to multiple aspects of the environment at scales of minutes and meters.  We aim to improve ecological forecasts by providing computational and visualization tools to address these discrepancies.  Our suite of tools will enable extracting fine spatial and temporal scale microclimate data, translating microclimate (air and surface temperatures, radiation, and wind) conditions into animals body temperatures by calculating energy balances, and mapping body temperatures and regions of thermal stress.  We will also present case studies of how animals are impacted by climate and climate change.  We aim to improve ecological forecasting tools for education, policy, and research.

## Tools

***Extracting microclimate data***-  We are currently distributing microclimate (hourly, 36km resolution) [data](http://microclim.org/) covering the United States for past (1980-1999) and future (2080-2099) time periods.  The data were created by dynamic downscaling using the Weather Research and Forecasting (WRF) model.  We are working towards providing near real time microclimate data based on satellite observations.  We are also working to expand the geographic scope and time period of the available data.

***Translating microclimate into animal body temperatures***- [TrenchR](https://github.com/trenchproject/TrenchR) is an R package for transparent environmental and ecological biophysics. It offers microclimate models as well as accessible energy budget models to translate microclimate into estimates of animal body temperature.  We are developing our tools in collaboration with the [NicheMapR](https://twitter.com/nichemapr) initiative.

***Education and outreach***- We have created the [TrEnCh-ed](https://trench-ed.github.io/) website including interactive R Shiny applications and associated tutorials to allow students and others interested to explore the ecological and evolutionary impacts of climate change through interacting with data.

We’ve developed a series of [tutorials](https://bookdown.org/huckley/Physical_Processes_In_Ecosystems/) aimed at graduate students interested in biophysical ecology. The tutorials originate from a 1979 course at UW entitled "Physical Prcoesses in Ecosystems" and align with the TrenchR package.

***Mapping body temperatures and regions of thermal stress***- We are developing several interactive visualizations for exploring organismal responses to environmental conditions. [One](http://18.221.236.49:3838/myapp/) uses bioiphysical modelling to explore lizard body temperatures and regions of thermal stress. [Another](https://insectphenology.ml/) leverages a database of insect development traits to predict phenology.

***Case studies of how animals are impacted by climate and climate change***- We are developing case studies, informed by our empirical research, illustrating how climate change is impacting animals.

**Acknowledgements**: The TrEnCh project is primarily supported by a National Science Foundation (NSF) Advances in Biological Informatics CAREER grant (DBI-1349865).  The TrEnCh project has also benefited from additional NSF support (EF-1065638, DEB-1120062).

TrEnCh is open-source ([GitHub repository](https://github.com/trenchproject)) and built using open source software including Bootstrap, node.js, Travis CI, Express, and R.  

