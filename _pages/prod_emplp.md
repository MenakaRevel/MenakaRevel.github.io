---
title: "Menaka Revel - Products"
layout: pagelay
sitemap: false
permalink: /prod_emplp/
---

## Adaptive Empirical Local Patches
The preparation of empirical local patches involved the following steps:
1. Data transformation: To calculate a semi-variogram, the data were transformed into a normally distributed, seasonality-removed time series.
2. Semi-variogram analysis: A semi-variogram summarizes the spatial dependence structure by a one-dimensional spatially averaged semi-variance.

### Data Transform
WSE was simulated using the CaMa-Flood hydrodynamic model. 
Remove the linear trend from the simulated WSE. 
Remove seasonality from the detrended time series. 
Standardize by dividing by the standard deviation.

<img src="{{ site.url }}{{ site.baseurl }}/images/prodpic/prod_datatrans.jpg" width="50%" height="50%"/>

### Semi-Variogram Analysis
A semi-variogram was calculated for each pixel using the average squared difference between all pairs of values separated by the spatial distance lag.

<img src="{{ site.url }}{{ site.baseurl }}/images/prodpic/prod_semivar.jpg" width="50%" height="50%"/>

### Preparing Empirical Local Patch
Semi-variogram fitting was conducted for each upstream location. 
Spatial dependency weights were calculated for each tributary corresponding to each target pixel. 
A threshold of 0.6 was defined to delineate the extent of the empirical local patch.
Convert semi-variance data into an empirical weighting function
Inverting standardized semi-variances using the sill value (C)

<img src="{{ site.url }}{{ site.baseurl }}/images/prodpic/prod_spatialwgt.jpg" width="50%" height="50%"/>

<img src="{{ site.url }}{{ site.baseurl }}/images/prodpic/prod_mapemplp.jpg" width="50%" height="50%"/>


### Characteristics Empirical Local Patch
Empirical Local Patch: follow river hydrodynamics, consider significant correlation areas, remove nonsignificant correlations, remove error covariance.
The size of each empirical local patch is determined by the river hydrodynamics. The empirical local patches created for different river pixels vary in size. Small rivers have relatively smaller local patches, while large rivers have larger ones.

<img src="{{ site.url }}{{ site.baseurl }}/images/prodpic/prod_wgtalongriver.jpg" width="50%" height="50%"/>

<img src="{{ site.url }}{{ site.baseurl }}/images/prodpic/prod_maplocalpatch.jpg" width="50%" height="50%"/>

- [Revel et al (2019)](https://doi.org/10.2208/jscejhe.74.5_I_157)
