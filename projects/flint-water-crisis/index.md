---
title: High-Risk Areas for Water Contamination in Flint, Michigan
layout: default
---

# Identifying High-Risk Areas for Water Contamination  
### Flint, Michigan GIS Analysis

## The Project
For this project, we were asked to analyze drinking water contamination risks in Flint, Michigan by identifying areas where multiple environmental hazards overlap. Using buffer analysis and multi-criteria suitability techniques, we located neighborhoods within 0.3 miles of high-pollution TRI facilities, 0.3 miles of a river, and 0.2 miles of lead service lines—three factors that together heighten the probability of unsafe water exposure. The results revealed two primary high-risk zones concentrated along Flint’s river corridors. These areas represent communities facing the greatest potential harm from polluted water, including risks from toxic releases, lead infiltration, and riverborne contaminants. This spatial pattern highlights the importance of environmental, infrastructural, and industrial vulnerabilities in public health risks among residents. 


## Map (Overview)
<p align="center">
  <img src="Flint_Overview_Map.png" alt="Overview map of high-risk water contamination areas in Flint, Michigan" width="900">
</p>

## Map (Detail View)
<p align="center">
  <img src="Flint_Detail_Map.png" alt="Detailed map of high-risk zones in Flint, Michigan" width="900">
</p>

## GIS Tools & Skills Used
- Reprojected datasets using NAD 1983 StatePlane Michigan South  
- Joined TRI pollution tables and selected facilities emitting >10,000 tons of water pollution  
- Selected pure lead service lines based on attribute queries  
- Clipped Michigan rivers to Flint boundaries for efficiency  
- Created buffer zones (0.3 mi TRI & rivers; 0.2 mi lead lines)  
- Intersected all three buffers to identify high-risk contamination zones  
- Created overview and detail maps to visualize results  
