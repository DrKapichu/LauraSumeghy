
# Software
The software to use for this project is [QGis](https://www.qgis.org/fr/site/) and with Ubuntu it can be readily installed thanks to **Ubuntu Software**.

# Data sources

 - [Marine Protected Areas in Coral Reef Regions of the World](https://datasets.wri.org/dataset/marine-protected-areas-in-coral-reef-regions-of-the-world)
 - [Reefs at Risk Revisited: Climate-Related Threats Data](https://datasets.wri.org/dataset/reefs-at-risk-revisited)
 - [Reefs at Risk in the Caribbean](https://www.wri.org/research/reefs-risk-caribbean)
 - [Reefs at Risk Revisited](https://www.wri.org/research/reefs-risk-revisited)



Couche non valide: GDAL provider Cannot open GDAL dataset /home/craftdata/LauraSumeghy/QGis/data/ReefsAtRiskRevisitedClimate-RelatedThreatsData/reefsatriskrevisited2030.kmz: `/home/craftdata/LauraSumeghy/QGis/data/ReefsAtRiskRevisitedClimate-RelatedThreatsData/reefsatriskrevisited2030.kmz' not recognized as a supported file format. Raster layer Le fournisseur de données n'est pas valide (prestataire : gdal, URI : /home/craftdata/LauraSumeghy/QGis/data/ReefsAtRiskRevisitedClimate-RelatedThreatsData/reefsatriskrevisited2030.kmz



# Issues
After a meeting with Laulau, I have more clues about the files and directories of interest.

File of interest:
 - .adf
 - .adj
 - .aux
 - .lyr

Directories of interest:
 - ReefsAtRiskInTheCaribbean/Lambert
 - ReefsAtRiskRevisited/Global_Threats/Acidification
 - ReefsAtRiskRevisited/Global_Threats/Future_Thermal_Stress


# Proposed solutions

## Fix for .lyr files
The proposed fixes essentially come from the [SLYR Community Edition](https://plugins.qgis.org/planet/tag/lyr/) plugin for which I got a [full tutorial on YouTube](https://www.youtube.com/watch?v=mpdw-gXm7KI).  
The plugin serves the purpose to convert the proprietary **.lyr** format into a QGis-compatible format that is **.qml**.



