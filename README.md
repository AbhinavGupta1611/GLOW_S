# GLObal river Width from Sentinel-2 (GLOW-S)

This repo contains the codes to analyze the river flow widths obtained using Sentinel-2 images and support the results in the paper "Quantifying Global River Width Seasonality using Sentinel-2 Images" by A. R. Bhattarai, A. Gupta ,  and D. Feng. 

The GLOW-S data are publicly available through zenodo


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14774136.svg)](https://doi.org/10.5281/zenodo.14774136)

The algorithm to estimate river flow widths using the remote sensing data is taken from Yang et al. (2021). The code provided by Yang et al. (2021) was adapted with minor changes and can be found at [this link](https://code.earthengine.google.com/e005ddf44502ff85964cde19ff26721a?accept_repo=users%2FeeProject%2FRivWidthCloudPaper).

### Instructions to run the python scripts:
(1) Setup the virtual environment

(2) Download the required python libraries listed in teh file requirements.txt

(3) Any of the scripts can be executed now. 

References:

Yang, X., Pavelsky, T. M., Allen, G. H., & Donchyts, G. (2019). RivWidthCloud: An automated Google Earth Engine algorithm for river width extraction from remotely sensed imagery. IEEE Geoscience and Remote Sensing Letters, 17(2), 217-221.
