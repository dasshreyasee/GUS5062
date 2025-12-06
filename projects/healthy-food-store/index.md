---
title: Site Suitability for a Healthy Food Store (Philadelphia)
layout: default
---

<h1 align="center">Site Suitability Analysis for a Healthy Food Store</h1>
<h3 align="center">Philadelphia GIS Analysis</h3>

## Project Narrative
This project identifies the most suitable locations for developing a new healthy food store in Philadelphia using a multi-criteria site suitability analysis. I combined empowerment zones, transit accessibility, and proximity to existing healthy food sources to find areas that align with the city’s investment and public health goals. By buffering transit stations and intersecting those areas with empowerment zones, I identified where a store *should* be located, and then excluded all areas within 1,200 feet of farmers markets or Healthy Corner Stores. The final analysis revealed eight candidate areas, with one large contiguous zone standing out as the optimal location due to its size, accessibility, and distance from existing healthy food options. This project demonstrates how spatial analysis can support equitable urban planning and improve healthy food access in underserved neighborhoods.


## Map (Final Candidate Areas)
<p align="center">
  <img src="Healthy_Food_Store_Map.png" alt="Site suitability map highlighting optimal areas for a healthy food store in Philadelphia" width="900">
</p>

## GIS Tools & Skills Used
- Projected all datasets to NAD 1983 StatePlane Pennsylvania South  
- Buffered subway and regional rail stations (2,000 ft) and dissolved overlaps  
- Intersected inclusive criteria to find eligible zones  
- Buffered farmers markets and Healthy Corner Stores (1,200 ft) to create exclusion zones  
- Used Erase to remove unsuitable areas from eligible areas  
- Applied Multipart-to-Singlepart and calculated area to rank candidate sites  

