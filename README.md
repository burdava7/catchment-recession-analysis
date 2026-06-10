# Catchment recession analysis
GIS and Python workflow for analysing the relationship between catchment land use and flood-wave recession.
# Overview

This project combines spatial analysis in QGIS with hydrological time-series processing in Python to evaluate how land use composition influences flood wave recession dynamics.

The workflow integrates:

+ catchment delineation (4th-order basins in the Czech Republic),
+ gauging station selection,
+ exclusion of reservoirs,
+ CORINE Land Cover analysis,
+ CHMI discharge time series processing,
+ flood event detection,
+ recession analysis (time to 50% peak discharge).
