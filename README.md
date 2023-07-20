# sample-scripts
Sample scripts for Tropycal usage

Click on the Binder button to open the Notebook:

## v0.3
- Storm Plotting Tools, with Michael(2018)
- Track composite of Katrina(2005) and Ida(2021)
- Tropical Cyclone Rainfall, with Harvey(2017)
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tropycal/sample-scripts/HEAD?labpath=tropycal_v0.3_sample.ipynb)

## v0.5
- Plot Ensemble and Model Tracks
- Recon Mission & Realtime
- Cross-Basin Storm Support
- Features Joaquin(2015), Michael(2018), and Cesar-Douglas(1996)
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tropycal/sample-scripts/HEAD?labpath=tropycal_v0.5_sample.ipynb)

**Note:** Realtime Recon will give errors if there are no active missions.  Just click to the next cell.


## Tropycal: A Python Package for Analyzing Tropical Cyclones and More
AMS 34th Conference on Hurricanes and Tropical Meteorology, 10 – 14 May 2021 Virtual Meeting. Tomer Burg and Sam P. Lillo.
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tropycal/sample-scripts/HEAD?labpath=AMS_Tropical_Talk.ipynb)

**Changes from original**:
- `plot_gefs_ensembles` to `plot_ensembles`
- `rcon.plot`s with `rcon.hdobs.plot`s

**Error**:
- The tornados parts do not work because of deprecated pd.read argument, but I submitted a pull request with the fix.

**Warning**:
- This last Notebook gets pretty close to Binder's limit of 4GB RAM, so it gets very slow.  We recommend using Jupyter Notebook locally by using miniconda to create an environment for tropycal+Notebook.  A YAML file for creating the environment is included in this repo: ***env_tropycal.yml***.
