# sample-scripts
Sample scripts for Tropycal usage

Click on the Binder button to open the Notebook:

v0.3
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lisaleorelowe/sample-scripts/HEAD?labpath=tropycal_v0.3_sample.ipynb)

## v0.5
- Plot Ensemble and Model Tracks
- Recon Mission & Realtime
- Cross-Basin Storm Support
- Feature Joaquin(2015), Michael(2018), and Cesar-Douglas(1996)
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lisaleorelowe/sample-scripts/HEAD?labpath=tropycal_v0.5_sample.ipynb)

*Note: Realtime Recon did not work when I tested because number of active mission was zero (list index out of range). Maybe add an error check, to check for an empty list.*


## Tropycal: A Python Package for Analyzing Tropical Cyclones and More
AMS 34th Conference on Hurricanes and Tropical Meteorology, 10 – 14 May 2021 Virtual Meeting. Tomer Burg and Sam P. Lillo.
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lisaleorelowe/sample-scripts/HEAD?labpath=AMS_Tropical_Talk.ipynb)

Notes:
```
#Change doInterp to interpolate_data
#storms = basin.filter_storms(thresh={'dv_min':90,'dt_window':36},doInterp=True)
storms = basin.filter_storms(thresh={'dv_min':90,'dt_window':36},interpolate_data=True)
```
This Notebook gets pretty close to Binder's limit of 4GB RAM, It because of that it gets slow.


```
#storm.plot_gefs_ensembles(forecast = dt(2018,9,7,12), fhr = [84])
storm.plot_ensembles(forecast = dt(2018,9,7,12), fhr = [84])
```

This repo does not have the file `delta_recon`, and it didn't recognize `read_path` anyway.
```
storm = basin.get_storm(('Delta',2020))
#storm.get_recon(read_path="delta_recon") #Here we are reading from a saved file to save time
storm.get_recon()
```


