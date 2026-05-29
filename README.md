# Glacier Projections for arid, tropical and temperate Andean Glaciers— Dissertation Code

Repository containing all major code used throughout the BSc dissertation:
*"Assessing the Impacts of Climate Change on Glaciers in the Tropical, Arid 
and Temperate Andes using GIS and the Open Global Glacier Model (OGGM)"*

## Overview

Code for historical simulations, future projections, regional runoff analysis,
and climate anomaly analysis was run in Jupyter Notebooks on the OGGM Hub 
(hub.oggm.org) and is provided here as .py files with included commenting.

OGGM v1.6.2 was used for all simulations.
OGGM documentation: https://docs.oggm.org/en/stable/

## Repository Structure

- Python scripts for all simulations and analyses
- Input Data: — RGI 6.0 glacier ID lists for each climate zone

## Glacier Complexes

Individual glacier simulations cover three case study complexes:
- **Coropuna** (tropical, RGI region 16, 26 entities)
- **Guanaco** (arid, RGI region 17, 2 entities)
- **Osorno** (temperate, RGI region 17, 5 entities)

RGI IDs for each glacier are hardcoded in the respective scripts.
RGI IDs for the three climate zone populations (tropical n=591, 
arid n=691, temperate n=479) are provided in InputData/.

## Notes

- All simulations were run on the OGGM Hub (hub.oggm.org)
- Climate forcing: W5E5 v2.0 (historical), 9-GCM CMIP6 ensemble (future)
- Scenarios: SSP1-2.6, SSP2-4.5, SSP3-7.0, SSP5-8.5
- Minor differences may exist between figure outputs and 
  final dissertation figures due to formatting changes
