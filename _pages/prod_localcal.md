---
title: "Menaka Revel - Products"
layout: pagelay
sitemap: false
permalink: /prod_localcal/
---
## Local Calibration of River Routing Model
Accurate representation of surface hydrology is crucial in lake-dominated Canadian Shield watersheds. Spatial heterogeneity of conditions (e.g., soil, geology, terrain, vegetation, etc.) is highly influential in predicting accurate water dynamics. Since observations are sparse, calibrating the models locally is challenging. Therefore, different types of regionalization methods were used to transfer parameters to ungauged basins. These methods primarily depend on various physical characteristics of the watershed to identify similar catchments, which leads to reduced performance. To effectively address these limitations, we have developed a calibration strategy that precisely defines a subregion, strategically considering the river topology. We implemented this calibration strategy in the Ottawa River basin, located in southeastern Ontario, Canada.

### Global Calibration
The predominant approach for calibrating regional river routing models involves leveraging multiple observations to derive a unified set of parameters applicable across entire regions. We utilized the Dynamically Dimensioned Search (DDS) algorithm to optimize the average evaluation metrics across all observations, enhancing the performance and reliability of our analysis.

### Local Calibration
Conversely, sub-regions specific to each gauge were calibrated independently, leading to the development of distinct parameter sets for each region. The sub-regions can be categorized as either upstream or intermediate. In the upstream sub-regions, simulations extend from headwater areas to the nearest downstream gauge. Meanwhile, for the intermediate sub-regions, the upstream boundary is established using observed data, whether that be discharge measurements or lake water levels.

### Effectiveness of the Parameters
The discharge is predominantly influenced by Baseflow parameters, leading to a 0.23 KGE improvement over the baseline. In addition, Bias correction also plays a crucial role, contributing a 0.15 KGE improvement from the baseline. However, when all the parameters are combined, the accuracy gains are maximized, yielding the best overall results. Conversely, the calibration of the lake crest width resulted in the most notable enhancement in KGE deviation from the baseline, measuring at 0.34. The improvement observed when employing solely the lake crest width, as opposed to calibrating all parameters, amounts to approximately 0.1 units of KGE deviation.
<img src="{{ site.url }}{{ site.baseurl }}/images/prodpic/prod_senspara.jpg" width="50%" height="50%"/>

### Local vs Global Calibration
Throughout the calibration period, all the calibration gauges either showed improvements or maintained consistent performance with local calibration when compared to global calibration. Specifically, 39 out of 44 gauges demonstrated a difference in the accuracy metric that was greater than 0.1. As anticipated during the validation process, certain gauges demonstrate a deterioration in local calibration both temporally and spatially. However, it is noteworthy that the majority of temporal validations indicate an enhancement in local calibration, with a percentage of 62.2%.
<img src="{{ site.url }}{{ site.baseurl }}/images/prodpic/prod_mapdiffkge.jpg" width="50%" height="50%"/>

- [Revel et al, (2025) in preparation]