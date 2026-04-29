---
title: "Kankai River Morphodynamics Analysis"
excerpt: "Using Google Earth Engine and Python to visualize and analyze river shifting in Eastern Nepal (2020–2025). <br/><img src='/images/Kankai_River_Morphology_2020_2025.gif'>"
collection: portfolio
---

In this project, I analyzed the morphodynamics of the Kankai River using the **Scientific Python Stack** and **Google Earth Engine (GEE)**. 

### Project Overview
The Kankai River in the Terai region of Nepal is known for significant lateral migration. By leveraging the GEE Python API, I processed multi-temporal satellite imagery to track how the river channel has moved over the last five years.

![Kankai River Shifting](/images/Kankai_River_Morphology_2020_2025.gif)

*The animation above shows the pre- and post-monsoon channel changes and bank erosion detected via satellite imagery.*

### Technical Focus:
* **Data Sources:** Sentinel-2 and Landsat 8/9 Top of Atmosphere (TOA) imagery.
* **Processing:** Automated cloud masking and NDWI (Normalized Difference Water Index) calculation to isolate water pixels.
* **Visualization:** Generation of time-lapse GIF animations to quantify river migration rates.

This type of analysis is vital for identifying communities at risk of bank erosion and informing local disaster risk reduction strategies.
