# DATA607_FINAL_PROJECT

This repository contains data and analyses for comparing players from The Ringer's Top 100 NBA Player list, to the relative presence of those same players in threads on Reddit's r/nba community.

**Reproducibility**

silver_final_project_analysis.RMD is meant to be the main interactive notebook of this analysis. It leverages the static data in the data folder to produce charts and wordclouds, allowing for exploration of the data collected during the course of this project's creation.

silver_final_project_reddit.Rmd may be used to repeat data collection, but **data collected through this notebook will not match the static data provided.** This is because Reddit's API does not allow collection of specifically timed data. It is all relative (ie. top posts of last year from the time of pull).

If you nonetheless want to repeat the analyis, make sure to add your keys into the **config.yml** file!
