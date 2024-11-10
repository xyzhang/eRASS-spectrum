# Galaxy cluster spectral analysis

Tuesday 19.11.2024

Author: Xiaoyuan Zhang xzhang@mpe.mpg.de

## Requirements
- eSASS 
- HEASOFT
- Xspec & PyXspec
- Python >= 3.8
	- Astropy
	- BXA
	- Jupyter notebook/lab

## Contents
- `preparation.ipynb` 
Tutorial on data preparation and spectrum generation
- `spectral_analysis_basic.ipynb`
Introduction to PyXspec and a practice of spectral fitting
- `spectral_analysis_advanced.ipynb`
Background co-fitting and Bayesian inference with [BXA](https://johannesbuchner.github.io/BXA/index.html)
- `TM8_FWC_c010_mod_customized.dat`
Xspec model for TM8 FWC background
- `catalog/eRASS1_Main_around_HydraCluster.fits`
eRASS1 catalog of the Hydra Cluster field
- `data/`
eROSITA-DE DR1 event files of the Hydra Cluster field
- `static/`
Images used in Jupyter Notebooks
