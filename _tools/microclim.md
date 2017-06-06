---
title: Microclim.org
excerpt: Interactive website to download downscaled microclimate data.
tags:
  - Microclimate data
  - WRF
---
We provide microclimatic data for ecological forecasting. We have developed a [web based system](http://www.microclim.org) to disseminate high spatial (36km) and temporal (1hr) resolution microclimate data for North America.  Data for 17 metrics are available as instantaneous, max, min, or mean values across various time intervals (1hr, 6hrs, 12hrs, daily, monthly, or yearly) for a past (1980-1999). The site hosts the downscaled microclim data generated in collaboration with Ofir Levy ([details here](http://onlinelibrary.wiley.com/doi/10.1002/ecy.1444/full)).

The site addresses the computational challenge of some users desiring high temporal resolution data for a limited area and others desiring high spatial resolution data for a limited time period.  Users can employ the system to export microclimate data by specifying variables for a given time frame for a geographic area of interest. Once the request is placed, we have a backend python process; which invokes a NCL script on the netCDF data files, deposits the files to Amazon S3, and sends an email to the user with the links to the subsetted files. Users can then download those files directly into their development environment

We are working towards providing near real time microclimate data based on satellite observations. We are also working to expand the geographic scope and time period of the available data.
