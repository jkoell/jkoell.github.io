---
title: Research
permalink: /research/
---

My primary research interests are at the intersection of ocean physics and biogeochemistry, using observations from [BGC-Argo](https://biogeochemical-argo.org), moorings, and hydrography to study how processes such as ocean currents and deep water formation influence the distribution and variability of dissolved gases in the ocean.

Check out this StoryMap for a summary of my most recent paper, or read on below for more details on some of my previous work!
<iframe src="https://storymaps.arcgis.com/stories/e2d422a61ea84eafb25faec7de2507d6" width="100%" height="500px" frameborder="0" allowfullscreen allow="geolocation"></iframe>
[Full screen link to StoryMap](https://ecco-group.org/storymaps.htm?id=119)

## Ocean ventilation

Ocean ventilation is the term generally used for the "breathing" of the ocean. Different authors define ventilation in different ways, but in my work I generally use the term to mean the uptake of oxygen from the atmosphere at the surface of the ocean, and its export away from the source region by physical transport. In a paper published in JGR: Oceans in October 2025 ([open access, available here](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2024JC022157); code available on [my Github](https://github.com/jkoell/SPNA-ventilation)), I use data from the [GOBAI-O2 product](https://www.pmel.noaa.gov/gobai/) to study ventilation in the subpolar North Atlantic Ocean. The main findings from the paper are summarized in the schematic below:

![SPNA ventilation schematic](/assets/images/Atlantic_O2_uptake_Map_3d_v13.png){: width="1200px"}

The figure shows the annual mean air-sea gas exchange (positive into the ocean) for the SPNA on the top face, and the mean oxygen concentration along 45N in purple colors on the front. The main results are that the low oxygen water that enters the SPNA with the North Atlantic Current **(1)** takes up oxygen throughout the path of the subpolar gyre **(2)**. A progressive modification from lighter into denser mode waters culminates in the formation of Labrador Sea Water, the densest, most oxygenated water mass formed in this region **(3)**. This water mass is then exported with the Deep Western Boundary Current, carrying the oxygen taken up in the SPNA to the rest of the ocean **(4)**. 

![Air-sea gas exchange in density space](/assets/images/flx_sig.jpg){: style="float: left" width="500px"}

One surprising result from this work is where this ventilation of subpolar gyre waters occurs: The figure on the left shows the seasonal cycle and annual mean air-sea flux of oxygen as a function of sea surface density. Overall, there is outgassing during the summer months when shallow mixed layers support productive phytoplankton blooms, and oxygen uptake during winter when mixed layers are deep and cold, and old water from the deep ocean is mixed up towards the surface. Integrated over the whole year (right panel), there is a net uptake of oxygen at densities above 26.7 kg m<sup>-3</sup>. Almost 90% of this uptake happens at densities corresponding to subpolar mode water, which is a precursor of Labrador Sea Water that is formed primarily in the eastern half of the basin. So, while Labrador Sea Water is the "final product" that exports the oxygen the ocean absorbs in this region to other parts of the ocean, this uptake of oxygen actually occurs primarily during the formation of SPMW, in the surface branch of the Overturning Circulation.

A different measure of ventilation in the subpolar North Atlantic is the wintertime increase in oxygen content in certain isopycnal layers, an animation of which can be found [here](/ventilation). Like the air-sea gas exchange, this "isopycnal oxygen change" is largest in the density ranges of subpolar mode water. 

Having studied these mean patterns of ocean ventilation in the SPNA, my current research focuses on the interannual variability of these different processes. Early results suggest that there variability is linked to phases of the North Atlantic Oscillation (NAO), an atmospheric mode that affects many aspects of ocean dynamics in the North Atlantic Ocean, with higher oxygen uptake and ventilation of deeper layers during positive NAO years, and the opposite during the negative phase of the NAO.

Some of my previous work focused on more specific aspects of ocean ventilation in the Labrador Sea, and is briefly summarized below.

#### Air-sea gas exchange
![Gas exchange parameterizations](/assets/images/gasex.png){: style="float: right" width="400px"}

Air-sea gas exchange is one of the most crucial processes for ocean ventilation, as it sets the amount of oxygen taken up at the ocean's surface. The way that it is typically calculated is by using a gas exchange parameterization, which in its simplest form is a function of wind speed and the difference in oxygen concentration between ocean and atmosphere. However, many gas exchange parameterizations have been tuned for carbon fluxes, and constrained by either global values, or measurements from field campaigns from specific regions. In [Koelling et al., 2017 (GRL)](https://doi.org/10.1002/2017GL073933), we show that there is a large spread in how well different gas exchange parameterizations reproduce the net wintertime flux of oxygen into the ocean in the Labrador Sea. We find that parameterizations that account for bubble dissolution perform better than those that do not, and also show that the choice of wind speed product can have a large effect on the calculated fluxes.

#### Oxygen export
![Oxygen export](/assets/images/export.png){: style="float: left" width="400px"}

Water is brought into the Labrador Sea through a boundary current entering from the Irminger Sea, which flows counterclockwise around the basin and exits at the southern end, flowing equatorward along the North American coast. Along its transit through the Labrador Sea, deep waters that form in the center of the basin "join" this boundary current, and are then exported southward. This is a major conduit for the oxygen that is taken up during deep water formation in the Labrador Sea to be exported out of the region, ventilating the global ocean. In [Koelling et al., 2022 (Biogeosciences)](https://doi.org/10.5194/bg-19-437-2022) we use moored oxygen measurements taken within the boundary current to show that this export associated with newly ventilated waters has a seasonal dependence, with most of it flowing out in the 4-5 months following deep convection. We also used the data to obtain a first estimate of the amount of oxygen exported each year through this pathway, which is 1.6 Terramoles, equivalent to up to half of what gets taken up in the interior. 
This research was also featured in a number of news stories, including on [CBC](https://www.cbc.ca/news/canada/nova-scotia/labrador-sea-research-oxygen-transfer-world-oceans-1.6340451) and [Forbes](https://www.forbes.com/sites/priyashukla/2022/02/08/why-the-labrador-sea-are-the-lungs-of-the-ocean/?sh=1d934eac4e3b), and on the YouTube channel SciShow in a video titled ["How Climate Change is Strangling our Oceans"](https://www.youtube.com/watch?v=rIvt4s7CX2M).