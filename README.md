# SolAR-TS
A structured time-series data set of SHARP magnetograms for 24-hour Solar flare forecasting

## Overview
SolAR-TS is a pre-processed time-series dataset of SHARP LoS magnetograms for forecasting M- and X-class flares exactly 24 hours before the event. If Tf is the time for which the prediction is made, the individual time-series samples are in folders named `HARP_<Tf - 1h>`. Each sample-folder contains 6-hour data at a cadence of 12 minutes, constituting 31 files or "frames" (although some samples have < 31 frames due to missing files). All the individual samples are stored as FITS files of size (224 x 224), and normalized between -1 and 1. 

## Dataset Characteristics
- Data Source: SDO/HMI SHARP data product
- Modality: Line-of-sight magnetogram sequences
- Cadence: 12 minutes
- Prediction window: 24 hours
- Target Events: M- and X- class flares

## Data Access
The Data files are hosted on Zenodo:
DOI:
`https://doi.org/10.5281/zenodo.18814838`
