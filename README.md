### Howdy 👋

I'm Julie Padilla (she/her) and I’m currently a data scientist with the USGS Data Science Branch at US Geological Survey.In my role I spend about half of my time working on data science projects and the other half on management and process improvement tasks for the branch.

Examples of my USGS work available on GitHub include:
* [lake-temperature-model-prep](https://github.com/usgs-r/lake-temperature-model-prep) - This a [scipiper](https://github.com/USGS-R/scipiper) modeling data prep repo that has been a long running project in the Data Science Branch. My primary contributions to this pipeline were primarily focused on cleaning and munging raw temperature profile data from project cooperators ([here](https://github.com/USGS-R/lake-temperature-model-prep/blob/main/7a_temp_coop_munge/src/data_parsers/parse_mo_usace.R), [here](https://github.com/USGS-R/lake-temperature-model-prep/blob/650df79facc23dc438f447fa305e69c0b15342c5/7a_temp_coop_munge/src/data_parsers/parse_missouri_files.R#L56-L75), and [here](https://github.com/USGS-R/lake-temperature-model-prep/blob/main/7a_temp_coop_munge/src/data_parsers/parse_norfork_files.R) are three examples). As part of that work, I also love to [find and fix bugs](https://github.com/USGS-R/lake-temperature-model-prep/issues?q=is%3Aissue+author%3Apadilla410+) all along the way.
* [lake-temperature-missouri-models](https://github.com/usgs-r/lake-temperature-missouri-models) - This is a small, under-development, modeling project that is part of the larger body lake temperature modeling work at USGS. This `targets` pipeline creates and calibrates [GLM 3.0 models](https://aed.see.uwa.edu.au/research/models/glm/) for eight reservoirs in Missouri. I am the primary author on this repo, but I have borrowed heavily from pre-existing code bases ([here](https://github.com/USGS-R/lake-temperature-process-models) and [here](https://github.com/USGS-R/lake-temperature-process-models-old)) to speed development.

Examples of my work under previous affilitations:
* [SWMPrExtension](https://github.com/NOAA-OCM/SWMPrExtension) - I served as project manager and technical lead on this project, leading a team of two staff. This was my initial entry into working with the [National Estuarine Research Reserve System](https://coast.noaa.gov/nerrs/). Working together we defined a series of data analyses and reporting templates that can be used to quickly develop custom annual status reports for each of the 29 reserves in the system. This project is currently maintained by Dr Dave Eslinger.
* [SWMPrStorm](https://github.com/StormStories/SWMPrStorm) - I served as project manager and technical lead on this project, leading a team of three staff. I worked with the Southeast Atlantic NERRs to scope this work, and to develop and finalize this initial suite of data analyses. This project was "in progress" during my transition over to USGS, so the work was completed by Ben Crary, Amanda Flynn, and Shanna Rucker.

I also have a few projects on [`code.usgs.gov`](https://code.usgs.gov/)++:
* [NAWQA Pesticide National Synthesis Project Update](https://code.usgs.gov/wma/iidd/pnsp-pipeline/) - This repo was a test project between the Data Assembly Function and the USGS staff behind the [NAWQA Pesticide National Synthesis Project](https://water.usgs.gov/nawqa/pnsp/usage/maps/show_map.php?year=2019&map=ATRAZINE&hilo=L&disp=Atrazine). With this project we wanted to refactor a pre-existing pipeline and give the final plots a style update. We refactored the pipeline using `R` and `targets` which accomplished two things: (1) decreased the number of programming languages from 3 to 1, and (2) removed a dependency on proprietary GIS software and related python libraries. After updating the code, the VizLab took a crack at updating the design aesthetic while considering [accessiblity](https://www.section508.gov/blog/Universal-Design-What-is-it/) and acknowledging the previous years of design.
* [National IWAAs](https://code.usgs.gov/wma/national-iwaas/NWAA) - It's pretty early days for this project, but much of the work related to the National Water Availability Assessment will reside in this repo. I am working with junior data scientists to scope and manage this body of work.
* [Data Science Practitioners' Manual](https://dsp-manual.wma.chs.usgs.gov/) - This manual is an outgrowth of the Data Science Practitioners' Meeting - a monthly meeting for data scientists' from a variety of USGS branches and Water Science Centers to come together and discuss strategy, programming patterns, and thorny data problems. The manual serves as a central location for documentation related to data science and computing practices. The repo is [here](https://code.usgs.gov/wma/wp/dsp-manual) and is jointly managed by me and Jesse Ross.

++ You will only have access to these repos if you are a USGS employee on VPN

