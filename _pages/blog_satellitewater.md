---
title: "Menaka Revel - Blog"
layout: pagelay
sitemap: false
permalink: /blog_satellitewater/
---

## Remote Sensing of Terrestrial Waters
The availability of an in-situ global monitoring system is often hampered by the unavailability of accurate, complete, and freely accessible data. In the age of satellite big data, a wealth of information gathered from space is accessible for monitoring terrestrial waters. Satellite data serves as a crucial supplement to the limited in-situ gauging networks, particularly in developing countries where ground-level monitoring may be insufficient. We observe several types of satellite data available, including satellite altimetry, water surface extent, soil moisture, total water storage, and more.

### Satellite altimetry
Understanding water surface elevation is essential for comprehending the dynamics of surface water in hydrology. An alternative approach to measuring water surface elevations, aside from conventional gauging methods, is satellite altimetry. While satellite altimetry was not initially designed for inland water surveying, it has been effectively adapted for this purpose. This technology enables precise measurement ranging from a few centimeters to a few decimeters of water surface elevation, allowing for accurate monitoring of changes in lakes, rivers, and reservoirs. Satellite altimeters gauge water surface elevations by analyzing the difference in travel time of radar or laser signals sent from the satellite to the water surface. By comparing the satellite's orbital position with the altimetry range measurements, which are calculated from the travel time of radar or laser, we can accurately assess the height of the water surface. Also, this measurement process incorporates adjustments for various atmospheric conditions, including effects from the dry and wet troposphere, the ionosphere, and solid Earth tides. Using radar echoes and modified retracking techniques, the water surface elevations were obtained at the point where the satellite ground track intersected a body of water. Different satellite altimetry missions use different characteristics for estimating water surface elevations for hydrology, resulting in various re-teackers, altimetric waveform description, specific correction, associated biases and errors, and different acquisition modes (low-resolution mode, synthetic aperture radar, synthetic aperture radar interferometric).

A variety of radar altimetry missions have been utilized to monitor lakes and major rivers, which include the Topography Experiment (TOPEX)/Poseidon; European Remote Sensing (ERS)-1 and ERS-2; the Joint Altimetry Satellite Oceanography Network (Jason)-1, Jason-2, and Jason-3; GEOSTAT Follow On (GFO); Environmental Satellite (ENVISAT); the Satellite with ARGOS and ALTIKA (SARAL)-AltiKa; as well as Sentinel-3A, Sentinel-3B, Sentinel-6MF, and the Surface Water and Ocean Topography Mission (SWOT). Several groups or institutions around the world provided time series of surface water elevations for a variety of water bodies and applications.

<br>

#### Table 1: List of major databases providing surface water elevation time series over inland water bodies from radar altimetry.
<div style="overflow-x:auto;"> <table style="width:100%; border-collapse:collapse; margin:1.5em 0; font-size:0.95em;"> <thead style="background-color:#f7f7f7; font-weight:600;"> <tr> <th style="border:1px solid #ddd; padding:8px 12px; text-align:left;">Name of the Database</th> <th style="border:1px solid #ddd; padding:8px 12px; text-align:left;">Types of Water Body</th> <th style="border:1px solid #ddd; padding:8px 12px; text-align:left;">Producer</th> </tr> </thead> <tbody> <tr> <td style="border:1px solid #ddd; padding:8px 12px;"><a href="https://altimetry.esa.int/riverlake/shared/main.html" target="_blank">River &amp; Lake</a></td> <td style="border:1px solid #ddd; padding:8px 12px;">Rivers, Lakes, Reservoirs</td> <td style="border:1px solid #ddd; padding:8px 12px;">De Montfort University</td> </tr> <tr style="background-color:#fafafa;"> <td style="border:1px solid #ddd; padding:8px 12px;"><a href="https://hydroweb.next.theia-land.fr/" target="_blank">Hydroweb</a></td> <td style="border:1px solid #ddd; padding:8px 12px;">Rivers, Lakes, Reservoirs</td> <td style="border:1px solid #ddd; padding:8px 12px;">IRD/LEGOS, CNES (French Space Agency), Universidade do Estado de Amazonas</td> </tr> <tr> <td style="border:1px solid #ddd; padding:8px 12px;"><a href="https://dahiti.dgfi.tum.de/en/" target="_blank">DAHITI</a></td> <td style="border:1px solid #ddd; padding:8px 12px;">Rivers, Lakes, Reservoirs</td> <td style="border:1px solid #ddd; padding:8px 12px;">German Geodetic Research Institute</td> </tr> <tr style="background-color:#fafafa;"> <td style="border:1px solid #ddd; padding:8px 12px;"><a href="https://ipad.fas.usda.gov/cropexplorer/global_reservoir/" target="_blank">G-REALM</a></td> <td style="border:1px solid #ddd; padding:8px 12px;">Lakes and Reservoirs</td> <td style="border:1px solid #ddd; padding:8px 12px;">USDA NASA</td> </tr> <tr> <td style="border:1px solid #ddd; padding:8px 12px;"><a href="http://research.bpcrc.osu.edu/grrats" target="_blank">GRRATS</a></td> <td style="border:1px solid #ddd; padding:8px 12px;">Rivers</td> <td style="border:1px solid #ddd; padding:8px 12px;">Ohio State University</td> </tr> <tr style="background-color:#fafafa;"> <td style="border:1px solid #ddd; padding:8px 12px;"><a href="https://hydrosat.gis.uni-stuttgart.de/php/index.php" target="_blank">HydroSat</a></td> <td style="border:1px solid #ddd; padding:8px 12px;">River</td> <td style="border:1px solid #ddd; padding:8px 12px;">Institute of Geodesy, University of Stuttgart</td> </tr> </tbody> </table> </div>

<br>

### Surface Water Extent
The surface area of water bodies and their variation are important in assessing water availability, biogeochemical responses, and biodiversity around them. Surface water extent measurements are unique because measuring them over a wide area is nearly impossible. A variety of remote sensing techniques have been developed for observing surface waters, including observations across the electromagnetic spectrum at visible, infrared, and microwave wavelengths. Measuring scales range from a few meters to about 50 kilometers. Depending on the sensor or the application for which it was designed, there is a tradeoff between temporal and spatial coverage and sampling. For example, while SARs are capable of observing water extent at high spatial resolution (e.g., 10-100 m), they frequently have a short temporal revisit time, making it difficult to observe changing hydrological processes on a daily scale.

<br>

#### Table 2: List of available satellites to measure surface water extent.
<div style="overflow-x:auto;">
<table style="width:100%; border-collapse:collapse; margin:1.5em 0; font-size:0.95em;">
<thead style="background-color:#f7f7f7; font-weight:600;">
<tr>
<th style="border:1px solid #ddd; padding:8px 12px; text-align:left;">Satellite / Product</th>
<th style="border:1px solid #ddd; padding:8px 12px; text-align:left;">Sensor / Instrument</th>
<th style="border:1px solid #ddd; padding:8px 12px; text-align:left;">Spectral Domain</th>
<th style="border:1px solid #ddd; padding:8px 12px; text-align:left;">Spatial Resolution</th>
<th style="border:1px solid #ddd; padding:8px 12px; text-align:left;">Temporal Resolution</th>
</tr>
</thead>
<tbody>
<tr><td>JERS-1</td><td>L-band SAR</td><td>Microwave (Active)</td><td>~100 m</td><td>Limited</td></tr>
<tr><td>ALOS / PALSAR</td><td>L-band SAR</td><td>Microwave (Active)</td><td>10–100 m</td><td>Low (multi-temporal)</td></tr>
<tr><td>Sentinel-1</td><td>C-band SAR</td><td>Microwave (Active)</td><td>10 m</td><td>6–12 days</td></tr>
<tr><td>SSM/I</td><td>Passive microwave radiometer</td><td>Microwave (Passive)</td><td>10–50 km</td><td>Daily</td></tr>
<tr><td>AMSR-E</td><td>Microwave Radiometer</td><td>Microwave (Passive)</td><td>10–50 km</td><td>Daily</td></tr>
<tr><td>SMOS</td><td>L-band Radiometer</td><td>Microwave (Passive)</td><td>~50 km</td><td>Weekly</td></tr>
<tr><td>SWAMPS</td><td>Multi-satellite (microwave)</td><td>Microwave (Passive)</td><td>~25 km</td><td>Near-real-time</td></tr>
<tr><td>GIEMS / GIEMS-2</td><td>Multi-satellite (microwave &amp; others)</td><td>Multi-spectral</td><td>25 km</td><td>Monthly</td></tr>
<tr><td>GIEMS-D15 / D3</td><td>Downscaled GIEMS</td><td>Multi-spectral</td><td>500 m / 90 m</td><td>Static / Derived</td></tr>
<tr><td>MODIS (Terra/Aqua)</td><td>Moderate Resolution Imaging Spectroradiometer</td><td>Optical &amp; Infrared</td><td>250–500 m</td><td>Daily–Weekly</td></tr>
<tr><td>Landsat 7/8/9</td><td>ETM+ / OLI / OLI-2</td><td>Optical &amp; IR</td><td>30 m</td><td>16 days</td></tr>
<tr><td>Sentinel-2A/B</td><td>MSI (Multispectral Instrument)</td><td>Optical &amp; IR</td><td>10–20 m</td><td>5 days (combined)</td></tr>
<tr><td>AVHRR</td><td>Advanced Very High Resolution Radiometer</td><td>Optical &amp; IR</td><td>1 km</td><td>Daily</td></tr>
<tr><td>SWOT</td><td>KaRIn (Ka-band Radar Interferometer)</td><td>Microwave (Active)</td><td>~100 m</td><td>21 days (global)</td></tr>
<!-- <tr><td>NISAR (upcoming)</td><td>L- &amp; S-band SAR</td><td>Microwave (Active)</td><td>3–30 m</td><td>12 days</td></tr>
<tr><td>SMASH (planned)</td><td>Radar Altimeter constellation</td><td>Microwave (Active)</td><td>~100 m (TBD)</td><td>Frequent</td></tr>
<tr><td>Sentinel-3 Topo NG (planned)</td><td>Radar Altimeter (SRAL NG)</td><td>Microwave (Active)</td><td>~300 m (nadir)</td><td>27 days</td></tr> -->
</tbody>
</table>
</div>
