---
title: "TRPMM"
collection: portfolio
permalink: /research/trpmm/
excerpt: "Time-series remote sensing analysis of mangrove plantation monitoring with dynamic visual examples from two study areas.<br/><br/>Artificial afforestation has become one of the primary drivers of rapid mangrove expansion in recent years. Accurate and timely monitoring of mangrove planting areas is therefore essential for evaluating restoration effectiveness and supporting wetland management. In this study, a &quot;detect-monitor-validate&quot; framework was proposed for dynamic monitoring of mangrove planting areas. The &quot;detect&quot; component integrated PlanetScope and Sentinel-2 imagery to identify the potential distribution of mangroves. The &quot;monitor&quot; component introduced a Threshold- and Rule-based Planted Mangrove Monitoring (TRPMM) method based on time-series PlanetScope imagery to track annual mangrove expansion. The threshold strategy was developed using time-series NDVI and NDWI, while the rule-based framework incorporated land-cover transition rules, intra-annual consistency rules, and inter-annual consistency rules to improve monitoring reliability. The &quot;validate&quot; component utilized high-spatial-resolution PlanetScope imagery and Google Earth data for validation and accuracy assessment. The proposed framework effectively captured the spatiotemporal dynamics of mangrove expansion and demonstrated strong capability for monitoring planted mangroves in restoration regions. The results further indicated that thresholds, optical imagery quality, and temporal consistency rules played important roles in influencing monitoring performance. Compared with conventional NDVI-based approaches, the TRPMM framework substantially improved the identification of mangrove planting expansion. This method has strong potential for large-scale and long-term monitoring of mangrove restoration under the context of global coastal ecosystem restoration initiatives.<br/><img src='/files/TRPMM_result1.png' style='display:block; max-width:76%; border-radius:12px; margin: 1rem auto 1rem;'><br/><img src='/files/TRPMM_result2.png' style='display:block; max-width:76%; border-radius:12px; margin: 0.1rem auto 0.5rem;'>"
author_profile: false
no_sidebar: true
---

<div style="margin: 0 0 1.4rem; padding: 1.35rem 1.5rem; border-radius: 18px; background: linear-gradient(135deg, rgba(214, 234, 248, 0.92) 0%, rgba(241, 248, 253, 0.96) 100%); border: 1px solid rgba(148, 163, 184, 0.22); box-shadow: 0 10px 28px rgba(15, 23, 42, 0.06);">
  <p style="margin: 0; line-height: 1.85; color: #1e293b;">
    Two study areas were selected in this study: the Zhanjiang Mangrove National Nature Reserve (ZMNNR) and the Lingshui Mangrove National Wetland Park (LMNWP), both of which experienced intensive mangrove planting activities during 2016-2023.
  </p>
</div>

<img src="/files/TRPMM_background.png" alt="TRPMM study areas" style="display:block; width:66%; border-radius:12px; margin: 0.2rem auto 1.35rem;" />

## Methods

In this study, the 3 m PlanetScope imageries were organized into a two-dimensional network structure to represent both intra-annual and interannual time series. Interannual changes were used to determine whether mangrove changes occurred, while intra-annual variations were incorporated to ensure monitoring reliability. Unlike conventional one-dimensional time-series analysis, this approach fully utilizes all imagery from both intra-annual and interannual time series.

To reduce the influence of other wetland vegetation on mangrove identification, the potential distribution range of mangroves was extracted prior to monitoring. Considering that mangroves are periodically inundated by water and therefore have growth environments different from terrestrial vegetation, monitoring based solely on NDVI time-series changes may lead to inaccuracies. Therefore, a threshold- and rule-based method, namely TRPMM, was developed by integrating time-series NDWI (Normalized Difference Water Index) and NDVI.

Finally, the accuracy of the proposed method for annual mangrove expansion monitoring in mangrove planting areas was evaluated, and the advantages and limitations of the method were further discussed.

<img src="/files/TRPMM_Workflw.png" alt="TRPMM workflow" style="display:block; width:82%; border-radius:12px; margin: 0.9rem auto 1.25rem;" />

## Annual Mangrove Dynamics

### LMNWP

<img src="/images/PS_vs_change_hn.gif" alt="TRPMM Hainan dynamic monitoring" style="display:block; width:72%; border-radius:12px; margin: 0.75rem auto 1.25rem;" />

### ZMNNR

<img src="/images/PS_vs_change_zj.gif" alt="TRPMM Zhanjiang dynamic monitoring" style="display:block; width:72%; border-radius:12px; margin: 0.75rem auto 1.25rem;" />

<div class="legend-card">
  <img src="/images/PS_vs_change_zj_legend.png" alt="TRPMM legend" style="max-width:100%; border-radius:12px; margin: 0;" />
</div>
