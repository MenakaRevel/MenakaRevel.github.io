---
title: "Menaka Revel - Products"
layout: pagelay
sitemap: false
permalink: /prod_hydroda/
---

## Data assimilation framework
A new global-scale data assimilation framework for hydrodynamic modeling to estimate river discharge. The framework was developed for the upcoming Surface Water and Ocean Topography Mission. The objective of the data assimilation framework is to estimate river discharge accurately on a global scale with low computational costs. The CaMa-Flood hydrodynamic model formed the core of our global data assimilation framework. A physically-based adaptive empirical localization method to utilize as many observations as possible.

<img src="{{ site.url }}{{ site.baseurl }}/images/prodpic/prod_hydroda.jpg" width="50%" height="50%"/>

### Data Assimilation Methods
Three types of data assimilation experiments were performed: direct assimilation (DIR), anomaly assimilation (ANO), and normalized assimilation (NOM). The ANO approach was used to address the errors associated with direct assimilation by transforming both simulated and observed water surface elevation (WSE) into anomalies. However, differences in flow dynamics between simulated and observed WSE could not be fully resolved using ANO. To further address these discrepancies, the NOM approach was conducted, in which both forecasts and observations were transformed into normalized values. These three assimilation strategies were tested to identify the most effective method for improving discharge estimation given the current capabilities of hydrodynamic models.

<img src="{{ site.url }}{{ site.baseurl }}/images/prodpic/prod_damethod.jpg" width="50%" height="50%"/>


### Global Data Assimilation
Assimilation was found to perform effectively in large rivers, particularly in downstream regions, due to the frequent correction of upstream discharge. Assimilation efficiency was strongly influenced by two primary factors: the correction of local state variables and the adjustment of upstream inflow. Higher efficiency was observed in rivers located at higher latitudes and in large continental-scale rivers.

<img src="{{ site.url }}{{ site.baseurl }}/images/prodpic/prod_globnseai.jpg" width="30%" height="30%"/>


<img src="{{ site.url }}{{ site.baseurl }}/images/prodpic/prod_bestdamethod.jpg" width="30%" height="30%"/>

