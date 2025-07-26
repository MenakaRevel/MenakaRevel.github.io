---
title: "Menaka Revel - Products"
layout: pagelay
sitemap: false
permalink: /products/
---

# Products
<!-- 
## Data assimilation framework(../hydroda/)
 
-->
  
## [Empirical Local Patches for Data Assimilation](../prod_emplp/)
Empirical local patches identify relevant areas of a river system for specific locations based on water level behavior. Instead of assuming all nearby points influence each other equally, this method analyzes actual patterns in simulated water surface elevation to pinpoint strong relationships. By eliminating trends and seasonal variations, it focuses on meaningful spatial connections to create custom patches. These patches can change in size depending on the river’s characteristics; for example, the Amazon has a broader influence than a smaller stream. This approach enhances the accuracy of river models and satellite data for predicting water levels. This method better reflects the actual correlations of the river network, moving beyond simplistic distance assumptions. In summary, empirical local patches strengthen the selection of observations, improving the precision of hydrologic data assimilation.

<img src="{{ site.url }}{{ site.baseurl }}/images/prodpic/prod_emplp.jpg" width="50%" height="50%"/>

[Further Reading ....](../prod_emplp/)

<br>

## [Altimetry Mapping Procedure for Global River Models](../prod_altimap/)
Satellite altimetry is an essential tool for monitoring river water levels and enhancing hydrodynamic models. However, linking satellite measurements, taken at specific points known as virtual stations (VSs), to river model grids can be difficult due to alignment issues. To address this, an Automated Altimetry Mapping Procedure was developed. This method automatically matches each virtual station (such as from the HydroWeb database)  to the nearest location in the river network map (e.g., MERIT Hydro), factoring in land cover and river structure. Stations are categorized based on their proximity to rivers, including flags for those directly on rivers, on nearby land, or within complex features like multi-channel rivers or the ocean. By utilizing AltiMaP, researchers can more accurately identify suitable satellite points for model evaluation, reducing mapping errors and improving the connection between satellite data and model simulations. This method builds on the work of Revel et al. and is available for wider use in the hydrology community.

<img src="{{ site.url }}{{ site.baseurl }}/images/prodpic/prod_altimap.jpg" width="50%" height="50%"/>

[Further Reading ....](../prod_altimap/)

<!--
- Calibration of the hydrological model using remote sensing data(../lakecal/)
- Innovative local calibration of the river routing model(../mulcal/)
-->
