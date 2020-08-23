# QGIS Installation
QGIS is a powerful geospatial data processing software that is open source and relatively easy to use.  More information can be found at [QGIS](https://qgis.org/en/site/). Installation is quick with a download link being provided on the main page of the QGIS website. After installation, a project can be created that will be used for the demo at the end of this page. Data sets will be generated from both EarthExplorer and overpass-turbo. These sources contain a vast amount of geospatial data sets that can be accessed for free.

## EarthExplorer
USGS EarthExplorer is an online repository of geospatial data sets. These sets range from topology and weather patterns, to high quality aerial imagery. Data for the example project below will be captured from the NAIP or National Agriculture Imagery Program. This data is for use in agriculture settings but it also contains high resolution imagery which will be a great starting point for an example project. A free account can be created at [EarthExplorer](https://earthexplorer.usgs.gov/). The panel on the left side of the screen allows the user to query various data sets and see the results. First NAIP is selected, and then result option is selected. Under show results controls, the option to show all footprints can be selected to show how individual data files are tiled over the selected area. These files can then be downloaded and used in QGIS

![](https://github.com/hughest6/CSE620B/blob/QGIS-Installation/earth%20explorer%20export.PNG)

## overpass-turbo
Overpass-turbo hosts vector data in an easy to access environment [overpass-turbo](https://overpass-turbo.eu/). An easy to use wizard is offered at the top of the screen which the user can use to find various vector data sets for the displayed map area.  For the example project, highway data is pulled for the Dayton Ohio area. To complete this, the wizard is selected and "motorway" is typed and selected. This will return vector information for the highways within the screen area.

![](https://github.com/hughest6/CSE620B/blob/QGIS-Installation/overpass_motorway_screenshot.PNG)

## Example Project
