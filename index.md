# Adelyn O'Reilly

GIS Portfolio

## City of Minneapolis Surface Water and Sewers Intern Projects
- Using ArcGIS Pro, ArcGIS Online, and Python scripting with the ArcPy library, I created custom geoprocessing toolboxes to automate spatial analysis tasks such as identifying relationships between event points and stormwater mains and calculating stormwater subcatchment capacity using hydrologic model outputs from PCSWMM.
- I also created ArcGIS Online web applications for internal use including web maps visualizing bridge clearances and emergency shelter locations.

## Course Projects

### Interactive Tsunami Hazard Web Map
#### Interactive web map visualizing tsunami events and associated runups from 2020–2025. Pop-ups display event attributes such as water height, location, timestamp, and number of recorded runups. Built using JavaScript and the ArcGIS Maps SDK, developed and tested locally before deployment.
Using JavaScript, HTML/CSS, local host server, and <span>ArcGIS Maps SDK for JavaScript</span>.

<a href="https://github.com/oreil149/Tsunami-Webmap">3D Tsunami Visualization and Associated Runups (2020–2025)</a>


### Interactive Map of Modes of Transportation to Work by U.S. State (2023)
#### Interactive web map visualizing commuting patterns across the United States using 2023 census data. The map allows users to explore how different transportation modes vary geographically across states.
Using JavaScript, HTML/CSS, local host server, and <span>ArcGIS Maps SDK for JavaScript</span>.

<a href="https://github.com/oreil149/Modes-of-Transportation-US">Modes of Transportation Interactive Map Repo</a>

### U.S. Imports and Exports Flow Map
#### Cartographic visualization of U.S. foreign trade relationships
Using ArcGIS Pro geoprocessing tools such as XY Table to Point, XY Table to Line, attribute table joins, and geodesic line creation.

<figure>
  <img src="https://github.com/oreil149/adelyn-oreilly.github.io/raw/main/ExportUSD.png" width="100%" alt="U.S. Exports Flow Map">
</figure>

<figure>
  <img src="https://github.com/oreil149/adelyn-oreilly.github.io/raw/main/ImportUSD.png" width="100%" alt="U.S. Imports Flow Map">
</figure>

#### Created an origin–destination flow map visualizing 2024 trade relationships between the United States and its top 43 international partners using data from the United States Census Bureau and IPUMS International. Applies cartographic principles through clear visual hierarchy: line thickness, color differentiation, and layout separation to improve readability. 

### Census Block Group Choropleth Map
Spatial analysis of demographic patterns using census data.

### Glacial Maps
#### Assessing Hydrological Risks of Hydraulic Fracking Near Glaciers in Alaska 1990 - 2020
Applied spatial analysis and hydrologic modeling in ArcGIS Pro, including buffer analysis, near analysis, flow direction, and watershed delineation using Raster and Vector data.

<figure>
  <img src="https://github.com/oreil149/adelyn-oreilly.github.io/raw/main/Ovrlaid1986and2020.png" width="100%" alt="1986 and 2020 Comparison">
</figure>
Visualizes the NOAA and AOGCC Glacial Area change from 1986 to 2020 shown as single symbols overlaid with Fracking Well Data sites.

<figure>
  <img src="https://github.com/oreil149/adelyn-oreilly.github.io/raw/main/PecentChangeTotal.png" width="100%" alt="Percent Change in Area 1986 - 2020">
</figure>
Visualizes the NOAA and AOGCC Glacial Area change from 1986 to 2020 shown using unclassified symbols of the Percent Change in Area (0-100) overlaid with Fracking Well Data sites.

<figure>
  <img src="https://github.com/oreil149/adelyn-oreilly.github.io/raw/main/FrackingBuffers.png" width="100%" alt="Fracking Buffers">
</figure>
Fractured Well Buffers for 5km, 20km, 50km, and 100km shown with the NOAA and AOGCC Glacial Area change from 1986 to 2020 shown as single symbols.

<figure>
  <img src="https://github.com/oreil149/adelyn-oreilly.github.io/raw/main/PercentChangeAK.png" width="100%" alt="Percent Change in Area using Buffer">
</figure>
Percent Change in Area Within and Outside of the 50km Buffer and 100km Buffer Zones around Fracturd Wells

<figure>
  <img src="https://github.com/oreil149/adelyn-oreilly.github.io/raw/main/PercentChangeNear.png" width="100%" alt="Percent Change in Area using Near">
</figure>
Percent Change in Area Near and Outside of the 50km and 100km radii around Fracturd Wells

#### GIS analysis of potential environmental risks of hydraulic fracturing activity in Alaska from 1990–2020. Using datasets from the National Oceanic and Atmospheric Administration and the Alaska Oil and Gas Conservation Commission. Results showed no direct correlation between proximity to fracking sites and glacial decline, but meltwater pathways could flow toward watersheds supplying nearby communities.
You can view the detailed [Glacier Report](Glacier_Report.pdf).

### Visualizing Flow of Travel Behavior - Twin Cities Metropolitan Area - 2021
#### This project analyzed and visualized travel patterns across the Twin Cities metropolitan area using the 2021 Travel Behavior Inventory survey dataset, Census 2020 Geography, and Census 2020 Demographic and Housing Characteristics File (DHC). 
Using spatial analysis tools in ArcGIS Pro along with data cleaning and statistical analysis in Excel and Python.

<figure>
  <img src="https://github.com/oreil149/adelyn-oreilly.github.io/raw/main/StPaulALL.png" width="100%" alt="St. Paul Combined Modes of Transportation">
</figure>

<figure>
  <img src="https://github.com/oreil149/adelyn-oreilly.github.io/raw/main/StPaulActive.png" width="100%" alt="St. Paul Active Modes and Frequency">
</figure>

<figure>
  <img src="https://github.com/oreil149/adelyn-oreilly.github.io/raw/main/StPaulPV.png" width="100%" alt="St. Paul Private Vehicle">
</figure>

<figure>
  <img src="https://github.com/oreil149/adelyn-oreilly.github.io/raw/main/StPaulTransit.png" width="100%" alt="St. Paul Public Transit">
</figure>

#### The line features connecting origins and destinations to visualize transportation movement across the region. The analysis found that personal vehicles dominate regional travel, while public transit, and active transportation are more common in dense urban areas. 
You can view the detailed [Transit Report](Transit Report.pdf).

### Map of Differenced Normalized Burn Ratio (dNBR) Symbolized by Severity
#### Conducted Wildfire Severity Analysis using Landsat 5 imagery to evaluate vegetation loss from the Bastrop wildfire in Texas. 
Using raster analysis and map algebra to calculate the Normalized Burn Ratio (NBR) for pre-fire and post-fire imagery and derived the Differenced Normalized Burn Ratio (dNBR) to quantify burn severity across the landscape. 

<figure>
  <img src="https://github.com/oreil149/adelyn-oreilly.github.io/raw/main/Bastrop.png" width="100%" alt="Wildfire Burn Severity in Bastrop, Texas">
</figure>

#### The resulting map classified burn severity into five categories using equal-interval classification: enhanced regrowth, unburned, low, moderate, and high severity. Results showed that most of the study area remained unburned (~705 km²), while approximately 23.8 km² experienced high-severity burn, indicating significant vegetation loss. 

## QGIS Maps 

<figure>
  <img src="https://github.com/oreil149/adelyn-oreilly.github.io/raw/main/FireRoutes.png" width="100%" alt="Fire Routes and Service Areas Accross Minneapolis, MN">
</figure>
Network Analysis Determining Fire Station Service Area (Minneapolis, Minnesota)

<figure>
  <img src="https://github.com/oreil149/adelyn-oreilly.github.io/raw/main/Utah.png" width="100%" alt="Utah Cubic TIN and IDW Interpolation">
</figure>
Utah Cubic Triangulated Irregular Network (TIN) and Inverse Distance Weighting (IDW) Interpolation

<figure>
  <img src="https://github.com/oreil149/adelyn-oreilly.github.io/raw/main/Voronoi.png" width="100%" alt="Voronoi Polygons of Utah">
</figure>
Voronoi Polygon Interpolation of Utah Elevation

## Skills
ArcGIS Pro
ArcGIS Online
Python
GIS Analysis  
Cartographic Principles
QGIS
