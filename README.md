# Maize-spartial-data-analysis

# Overview
Agricultural productivity can vary across geographic regions due to differences in environmental conditions, agricultural practices, and spatial relationships between neighbouring areas. This project investigates the spatial patterns of maize yields across Kenyan counties using R. It applies spatial models to examine whether maize yields exhibit geographic dependence and whether accounting for spatial relationships provides additional insight into regional agricultural productivity.

# Problem Statement
Do maize yields across Kenyan counties exhibit spatial dependence, and how can spatial  models help explain geographic patterns in agricultural productivity?

# Objectives
Explore the geographic distribution of maize yields across Kenyan counties.

Identify spatial patterns in agricultural productivity.

Construct spatial neighbourhood relationships between geographic regions.

Apply and compare Spatial Lag and Spatial Error models.

Interpret the findings in the context of regional agricultural analysis.

# Tools and Technologies
R — Statistical computing and spatial analysis.

tidyverse — Data manipulation and analysis.

sf — Handling and processing spatial data.

spdep — Spatial neighbourhood structures and spatial statistical modelling.

readxl — Importing Excel datasets.

# Methodology

The analysis followed these main steps:

Data Preparation: Imported and prepared maize yield data and geographic boundary files for analysis.

Exploratory Spatial Analysis: Examined the distribution of maize yields across Kenyan counties.

Spatial Data Integration: Combined agricultural data with geographic boundaries.

Neighbourhood Construction: Defined spatial relationships between neighbouring regions.

Spatial Econometric Modelling: Estimated Spatial Lag and Spatial Error models to investigate spatial dependence.

Model Interpretation: Examined model results to understand geographic relationships in maize productivity.

# Models Used
Spatial Lag Model -  It helps investigate whether maize yields are associated with yields in neighbouring regions.

Spatial Error Model - The Spatial Error model accounts for spatial dependence in the error term, allowing for spatially correlated influences not fully captured by the explanatory variables.

Comparing these models provides different perspectives on the spatial structure of maize productivity.

