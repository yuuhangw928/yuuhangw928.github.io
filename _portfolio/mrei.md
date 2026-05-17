---
title: "MREI"
collection: portfolio
permalink: /research/mrei/
excerpt: >-
  Mangrove Restoration Effectiveness Index research focused on restoration assessment and remote sensing evaluation.<br/><br/>
  Mangroves have been severely threatened by intensive human activities, so many countries and regions have carried out mangrove restoration projects. The evaluation of mangrove restoration effectiveness is of great significance for scientific decision-making for restoration engineering and wetland management. In this study, we proposed a remote-sensing-based Mangrove Restoration Effectiveness Index (MREI) to quantitatively evaluate mangrove restoration effectiveness using Landsat time-series imagery. The Guangxi Shankou Mangrove National Natural Reserve, a UNESCO Biosphere Reserve, was selected as the study area, where multiple phases of mangrove afforestation were implemented from 1990 to 2022. The MREI was developed by integrating changes in mangrove area and the Normalized Difference Vegetation Index (NDVI) during different restoration phases. Furthermore, the Persistence of Restoration Effectiveness (PRE) was introduced to characterize the temporal trajectory and long-term stability of restoration effectiveness, while the Process-based Restoration Effectiveness Index (PREI) was developed to assess restoration effectiveness at the village scale. The proposed framework effectively captured the spatiotemporal dynamics of mangrove restoration and provides a practical and transferable approach for evaluating restoration effectiveness in coastal wetland ecosystems.<br/>
  <img src='/files/MREI_result1.png' style='display:block; max-width:72%; border-radius:12px; margin: 1rem auto 0.8rem;'><br/>
  <img src='/files/MREI_results_2x2.png' style='display:block; max-width:76%; border-radius:12px; margin: 0.2rem auto 0.7rem;'>
author_profile: false
no_sidebar: true
---

<div style="margin: 0 0 1.4rem; padding: 1.35rem 1.5rem; border-radius: 18px; background: linear-gradient(135deg, rgba(214, 234, 248, 0.92) 0%, rgba(241, 248, 253, 0.96) 100%); border: 1px solid rgba(148, 163, 184, 0.22); box-shadow: 0 10px 28px rgba(15, 23, 42, 0.06);">
  <p style="margin: 0; line-height: 1.85; color: #1e293b;">
    China launched the National Coastal Shelterbelt System Construction Project (NCSSCP) in 1988, with mangrove planting and restoration identified as key components. Since 1990, multiple phases of the NCSSCP have been implemented to promote large-scale mangrove restoration and coastal ecological protection. The project has continuously expanded in both spatial extent and restoration objectives, with the latest phase aiming to restore approximately 48,650 ha of mangroves by 2025.
  </p>
</div>

<img src="/files/timeline.png" alt="MREI timeline" style="display:block; width:82%; border-radius:12px; margin: 0.2rem auto 1.3rem;" />

## Methods

The Landsat-series images were pre-processed, and land cover types in 1990, 2000, 2008, 2015, and 2022 were classified. At the same time, the maximum NDVI for each year was calculated to represent the growth condition of mangroves. Mangrove changes were then divided into four categories, and the area of each class was estimated using a stratified random sampling method.

Next, the Mangrove Restoration Effectiveness Index (MREI) was developed by considering both mangrove area change and NDVI change between the start year and the end year of each period. Since MREI only evaluates restoration effectiveness within a single period, a Process-based Restoration Effectiveness Index (PREI) was further developed based on the trajectory of MREI changes to assess the persistence of restoration effectiveness throughout the entire evaluation period (1990-2022).

<img src="/files/MREI_workflow.png" alt="MREI workflow" style="display:block; width:82%; border-radius:12px; margin: 0.9rem auto 1.25rem;" />

## Google Earth Engine App

<div style="margin: 1rem 0 0.5rem; padding: 1.4rem 1.5rem; border: 1px solid #dbe2ea; border-radius: 16px; background: linear-gradient(135deg, #f8fbff 0%, #ffffff 100%); box-shadow: 0 8px 24px rgba(15, 23, 42, 0.05);">
  <a href="https://2220902167.users.earthengine.app/view/mangroverestorationeffectivenessindex" style="display: inline-block; margin: 0 0 1rem; padding: 0.75rem 1.15rem; border-radius: 999px; background: #2563eb; color: #ffffff; text-decoration: none; font-weight: 600;">Interactive MREI Earth Engine App</a>
  <p style="margin: 0 0 1rem; line-height: 1.8; color: #334155;">
    China coastal MREI, 150*150m grid, 1984-2022
  </p>
  <img src="/files/MREI_APP.png" alt="MREI Earth Engine App preview" style="display:block; width:82%; border:1px solid #dbe2ea; border-radius:16px; margin: 0 auto 1rem; box-shadow: 0 10px 24px rgba(15, 23, 42, 0.08);" />
</div>
