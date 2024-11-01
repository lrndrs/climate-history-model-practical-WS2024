# Climate History Model Practical


## Getting started

This project contains data and a python jupyter notebook for the climate model exercise of the course "Paleoclimate and Climate History", taught by Heather Stoll in WS2024 and this exercise developed by Laura Endres.

Regarding dependencies, everything you need should be provided by the moodle jupyterlab environment.
If you work on your own machine you need to install the libraries, which can be done using conda and pip.
With the terminal, you can

- install xarray, by typing:
```conda install -c conda-forge xarray dask netCDF4 bottleneck```

- install cartopy, by typing:
```conda install cartopy```

- other dependencies can be installed by typing:
```pip install -r requirements.txt```

The data used in the exercise stems from a model simulation of the following publication:

Vettoretti, G., Ditlevsen, P., Jochum, M., Rasmussen, S.O., 2022. Atmospheric CO2 control of spontaneous millennial-scale ice age climate oscillations. Nature Geoscience 15, 300–306. https://doi.org/10.1038/s41561-022-00920-7

For follow-up questions or if you find mistakes in the notebook, please write me an E-mail: endres@eaps.ethz.ch

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lrndrs/climate-history-model-practical-WS2024/HEAD)
