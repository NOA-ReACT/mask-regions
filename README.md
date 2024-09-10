# mask-regions
This directory contains 2 files:
1. timeseries_periphereies_cams_climatology_2003_clean.ipynb
2. periphereies.json

file 2 is a shape file for the Greek regions
file 1 is a notebook that reads monthly files with the ensemble mean of PM10 from the CAMS air quality reanalyses database (https://ads.atmosphere.copernicus.eu/cdsapp#!/dataset/cams-europe-air-quality-reanalyses?tab=overview)
Afterwards, the code finds the maximum number of dust events within that period.
The dust events are classified based on the WMO guidelines.

