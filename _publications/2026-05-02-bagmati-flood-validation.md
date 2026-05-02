---
title: "Validating the July 2020 Bagmati Flood: Linking Rainfall to Inundation Using Satellite Data"
collection: publications
permalink: /publication/2026-05-02-bagmati-flood-validation
date: 2026-05-02
venue: 'Technical Research Note'
paperurl: 'https://khemupreti-hydromet.github.io/publication/2026-05-02-bagmati-flood-validation'
citation: 'Upreti, K. R. (2026). &quot;Validating the July 2020 Bagmati Flood: Linking Rainfall to Inundation Using Satellite Data.&quot; <i>Technical Research Note</i>.'
---

# Introduction
Floods in the Himalayan region are often sudden, destructive, and difficult to predict. In river basins like the Bagmati, where steep terrain meets densely populated floodplains, even a short period of intense rainfall can trigger widespread inundation.

One of the biggest challenges in such regions is the lack of dense ground-based observations. This study uses satellite data to answer a critical question: **How long does it take for rainfall to turn into flooding?**

In this study, I use satellite data to answer that question for the July 2020 flood event in the Bagmati Basin. By combining precipitation data from GPM with flood observations from Sentinel-1 SAR, I estimate both the timing (hydrological lag) and the triggering conditions of the flood.

## 1. Understanding the Basin: Why Bagmati is Flood-Prone
The Bagmati River Basin spans from the mountainous regions in the north to low-lying plains in the south. This variation in topography plays a major role in flood dynamics.

![LULC Map](/images/lulc_map_bagmati_1.png)
*Figure 1: Land Use and Land Cover (LULC) of the Bagmati Basin. Forested areas dominate the upper catchment, while agricultural and urban regions are concentrated downstream. © 2026 Khem Raj Upreti*

## 2. The Trigger: Extreme Monsoon Rainfall
Using satellite-based rainfall data (GPM IMERG V07), I analyzed precipitation patterns during the 2020 monsoon.

![Rainfall Validation](/images/event_validation_4.png)
*Figure 2: Cumulative rainfall during July 2020. A sharp increase around July 20–22 indicates an extreme monsoon rainfall event across the basin. Data: GPM IMERG V07*

The basin received more than ~400 mm of rainfall over a short period—an intensity high enough to trigger flooding in vulnerable regions.

## 3. The Key Question: How Fast Does the Basin Respond?
To quantify the hydrological response delay, I applied a cross-correlation analysis between rainfall and flood extent.

![Lag Analysis](/images/lag_analysis_2.png)
*Figure 3: Cross-correlation between rainfall and flood extent. The peak at −4 days indicates that rainfall leads flooding by approximately four days. © 2026 Khem Raj Upreti*

This **4-day delay** represents the time required for runoff generation in the upper catchment, soil saturation processes, and river flow routing toward downstream areas.

## 4. Validation: Does This Match Reality?
To validate the results, I compared satellite findings with real-world observations and time-series data.

![Event Validation](/images/visual_validation_3.png)
*Figure 4A: Rainfall (blue) vs. flood extent (red). Rainfall peaks consistently precede increases in inundation area. © 2026 Khem Raj Upreti*

### Ground-Truth Verification
Reports from *The Himalayan Times* confirm that extreme rainfall triggered widespread flooding exactly within the window identified by this analysis.

> **"Most parts of Rautahat submerged"**  
> "Continuous rainfall since Sunday night has submerged most parts of the district... The Bagmati and Lal Bakaiya rivers have crossed the danger mark, inundating dozens of villages."  
> — [The Himalayan Times, July 21, 2020](https://thehimalayantimes.com/nepal/most-parts-of-rautahat-submerged)

This external report aligns with the **July 20–22** peak rainfall intensity captured by GPM and the subsequent inundation captured by SAR imagery.

### Visual Flood Evidence
![SAR Flood Animation](/images/rautahat_flood_inudation_5.gif)
*Figure 4B: Sentinel-1 SAR imagery showing flood expansion from pre-flood conditions (June) to peak inundation (July). © 2026 Khem Raj Upreti*

## 5. Key Finding: A 4-Day Early Warning Window
By combining satellite rainfall (GPM) and flood observations (SAR), this study identifies a consistent lead time that can be used for:
* **Advance Warning:** Providing critical preparation time for downstream communities.
* **Emergency Response:** Better planning for resource allocation during monsoon extremes.

## Conclusion
This study demonstrates a complete flood event chain: **Extreme Rainfall → Basin Response → Flood Inundation**. The agreement between satellite data and real-world reports provides strong confidence in using integrated approaches to bridge the gap between data scarcity and decision-making in complex Himalayan terrains.

---
© 2026 Khem Raj Upreti
