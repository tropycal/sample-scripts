# sample-scripts
Sample scripts for Tropycal usage

Click on a Binder button to open a Notebook.  Binder will start a Jupyter Lab starting at the chosen Notebook, but the other labs will also be available during the session.  (You can find them by clicking the folder icon in the grey left nav bar.)

## Tropycal: A Python Package for Analyzing Tropical Cyclones and More
AMS 34th Conference on Hurricanes and Tropical Meteorology, 10 – 14 May 2021 Virtual Meeting. Tomer Burg and Sam P. Lillo.
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tropycal/sample-scripts/HEAD?labpath=AMS_Tropical_Talk.ipynb)

## New in v0.3
- Storm Plotting Tools, with Michael(2018)
- Track composite of Katrina(2005) and Ida(2021)
- Tropical Cyclone Rainfall, with Harvey(2017)
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tropycal/sample-scripts/HEAD?labpath=tropycal_v0.3_sample.ipynb)

## New in v0.5
- Plot Ensemble and Model Tracks
- Recon Mission & Realtime
- Cross-Basin Storm Support
- Features Joaquin(2015), Michael(2018), and Cesar-Douglas(1996)
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tropycal/sample-scripts/HEAD?labpath=tropycal_v0.5_sample.ipynb)

## Notes
- In v0.5, Realtime Recon will give errors if there are no active missions.  Just click to the next cell.
- The tornados parts do not work as of July 20, 2023 because of deprecated pd.read argument.  The fix is coming soon.
- The **Tropycal, AMS** Notebook gets pretty close to Binder's limit of 4GB RAM, so it gets very slow.  We recommend using Jupyter Notebook locally by using miniconda to create an environment for tropycal+Notebook.  A YAML file for creating the environment is included in this repo: ***env_tropycal.yml***.
