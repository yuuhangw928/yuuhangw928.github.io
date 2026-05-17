---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
  .home-hero {
    margin-bottom: 2rem;
    padding: 1.5rem 1.6rem;
    border: 1px solid #e5e7eb;
    border-radius: 18px;
    background:
      radial-gradient(circle at top right, rgba(59, 130, 246, 0.12), transparent 28%),
      linear-gradient(135deg, #f8fbff 0%, #ffffff 62%);
    box-shadow: 0 14px 34px rgba(15, 23, 42, 0.07);
  }

  .home-name {
    margin: 0 0 0.35rem;
    font-size: 2rem;
    line-height: 1.1;
  }

  .home-meta {
    margin: 0 0 0.9rem;
    color: #475569;
    font-size: 0.98rem;
  }

  .home-summary {
    margin: 0;
    line-height: 1.8;
    color: #1f2937;
  }

  .home-tags {
    margin-top: 1rem;
  }

  .home-tag {
    display: inline-block;
    margin: 0 0.5rem 0.45rem 0;
    padding: 0.38rem 0.75rem;
    border-radius: 999px;
    background: #f2f8ff;
    border: 1px solid #cfe5ff;
    font-size: 0.9rem;
    color: #1e3a5f;
  }

  .home-links {
    margin-top: 1.15rem;
  }

  .home-link {
    display: inline-block;
    margin: 0 0.55rem 0.45rem 0;
    padding: 0.5rem 0.9rem;
    border-radius: 999px;
    text-decoration: none;
    border: 1px solid #d1d5db;
    background: #fff;
    color: #111827;
    font-size: 0.92rem;
    box-shadow: 0 6px 16px rgba(15, 23, 42, 0.05);
  }

  .home-link:hover {
    background: #f8fafc;
    text-decoration: none;
  }

  .home-section {
    margin: 1.5rem 0 0;
    padding: 1.25rem 1.35rem;
    border: 1px solid #eceff3;
    border-radius: 16px;
    background: #fff;
    box-shadow: 0 8px 20px rgba(15, 23, 42, 0.04);
  }

  .home-section h2 {
    margin-top: 0;
    margin-bottom: 1rem;
    font-size: 1.25rem;
  }

  .home-entry {
    margin-bottom: 1.1rem;
  }

  .home-entry:last-child {
    margin-bottom: 0;
  }

  .home-entry-title {
    margin: 0 0 0.2rem;
    font-weight: 700;
    color: #0f172a;
  }

  .home-entry-meta {
    margin: 0;
    color: #64748b;
    font-size: 0.95rem;
  }

  .home-news {
    display: grid;
    gap: 0.8rem;
    max-height: 245px;
    overflow-y: auto;
    padding-right: 0.35rem;
    scrollbar-width: thin;
    scrollbar-color: #cbd5e1 #f8fafc;
  }

  .home-news::-webkit-scrollbar {
    width: 8px;
  }

  .home-news::-webkit-scrollbar-track {
    background: #f8fafc;
    border-radius: 999px;
  }

  .home-news::-webkit-scrollbar-thumb {
    background: #cbd5e1;
    border-radius: 999px;
  }

  .home-news-item {
    display: grid;
    grid-template-columns: 88px 1fr;
    gap: 0.9rem;
    align-items: start;
    padding-bottom: 0.8rem;
    border-bottom: 1px dashed #dbe4ee;
  }

  .home-news-item:last-child {
    padding-bottom: 0;
    border-bottom: none;
  }

  .home-news-date {
    display: inline-block;
    padding: 0.24rem 0.55rem;
    border-radius: 999px;
    background: #eef6ff;
    border: 1px solid #d3e6ff;
    color: #1d4f8c;
    font-size: 0.82rem;
    font-weight: 600;
    text-align: center;
  }

  .home-news-text {
    margin: 0;
    color: #1f2937;
    line-height: 1.75;
  }

  .home-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }

  .home-card {
    padding: 1rem 1.05rem;
    border: 1px solid #edf0f4;
    border-radius: 14px;
    background: #fbfdff;
  }

  .home-card h3 {
    margin-top: 0;
    margin-bottom: 0.7rem;
    font-size: 1rem;
  }

  .home-card ul {
    margin: 0;
  }

  .home-scroll-list {
    max-height: 245px;
    overflow-y: auto;
    padding-right: 0.35rem;
    scrollbar-width: thin;
    scrollbar-color: #cbd5e1 #f8fafc;
  }

  .home-scroll-list::-webkit-scrollbar {
    width: 8px;
  }

  .home-scroll-list::-webkit-scrollbar-track {
    background: #f8fafc;
    border-radius: 999px;
  }

  .home-scroll-list::-webkit-scrollbar-thumb {
    background: #cbd5e1;
    border-radius: 999px;
  }

  @media (max-width: 760px) {
    .home-hero,
    .home-section {
      padding: 1.1rem;
    }

    .home-grid {
      grid-template-columns: 1fr;
    }

    .home-name {
      font-size: 1.7rem;
    }

    .home-news-item {
      grid-template-columns: 1fr;
      gap: 0.5rem;
    }
  }
</style>

<div class="home-hero">
  <h1 class="home-name">Yuhang Wang</h1>
  <p class="home-meta">yuuhangww@gmail.com | +86 198-2916-8033 | Xi'an, China</p>
  <p class="home-summary">
    I am interested in coastal ecology, mangrove remote sensing, and wetland monitoring. My research work focuses on mangrove restoration assessment, time-series remote sensing, and geospatial applications for wetland monitoring.
  </p>
  <div class="home-links">
    <a class="home-link" href="/publications/">📚 Publications</a>
    <a class="home-link" href="/research/">🔬 Research</a>
    <a class="home-link" href="/work/">💼 Work</a>
    <a class="home-link" href="/meetings/">🎤 Conference</a>
  </div>
</div>

<div class="home-section">
  <h2>📰 News</h2>

  <div class="home-news">
    <div class="home-news-item">
      <span class="home-news-date">2026-05-16</span>
      <p class="home-news-text">The Google Earth Engine APP for spatial coupling visualization of wetland degradation and human activities in the Pearl River Delta was released. <a href="https://2220902167.users.earthengine.app/view/wetlandlosshumanactivitycoupling" style="display: inline-block; margin-left: 0.35rem; padding: 0.18rem 0.55rem; border-radius: 999px; background: #2563eb; color: #ffffff; text-decoration: none; font-size: 0.74rem; line-height: 1.15; font-weight: 600; vertical-align: middle;">Wetland Dynamic Driving App</a></p>
    </div>

    <div class="home-news-item">
      <span class="home-news-date">2026-04-15</span>
      <p class="home-news-text">The Google Earth Engine APP of the Mangrove Restoration Effectiveness Index (MREI) for China coastal regions during the period of coastal shelterbelt engineering construction was released. <a href="https://2220902167.users.earthengine.app/view/mangroverestorationeffectivenessindex" style="display: inline-block; margin-left: 0.35rem; padding: 0.18rem 0.55rem; border-radius: 999px; background: #2563eb; color: #ffffff; text-decoration: none; font-size: 0.74rem; line-height: 1.15; font-weight: 600; vertical-align: middle;">MREI GEE App</a></p>
    </div>

    <div class="home-news-item">
      <span class="home-news-date">2026-02-28</span>
      <p class="home-news-text">Joined Xi'an Envmap Digital Technology Co., Ltd. as a Remote Sensing Algorithm Engineer, focusing on lightning-caused wildfire monitoring.</p>
    </div>

    <div class="home-news-item">
      <span class="home-news-date">2026-01-30</span>
      <p class="home-news-text">The mangrove plantation monitoring (TRPMM) paper was accepted by <em>Wetland Science</em>.</p>
    </div>

    <div class="home-news-item">
      <span class="home-news-date">2024-09-07</span>
      <p class="home-news-text">Submitted the abstract and poster for the 4th International Forum on Big Data for Sustainable Development Goals (FBAS) in Beijing.</p>
    </div>
  </div>
</div>

<div class="home-section">
  <h2>🎓 Education</h2>

  <div class="home-entry">
    <p class="home-entry-title">Capital Normal University (CNU), Beijing, China</p>
    <p class="home-entry-meta">M.Sc. in Geographic Information Science and Remote Sensing | GPA: 90.50/100 | 09/2022-06/2025</p>
  </div>

  <div class="home-entry">
    <p class="home-entry-title">Xi'an University of Science and Technology (XUST), Xi'an, Shaanxi, China</p>
    <p class="home-entry-meta">B.Sc. in Geographic Information Science | GPA: 84.34/100 | 09/2018-06/2022</p>
  </div>
</div>

<div class="home-section">
  <h2>💼 Work Experience</h2>

  <div class="home-entry">
    <p class="home-entry-title">Xi'an Envmap Digital Technology Co., Ltd.</p>
    <p class="home-entry-meta">Remote Sensing Algorithm Engineer | 02/2026-Present</p>
  </div>

  <div class="home-entry">
    <p class="home-entry-title">Xi'an Innovative Aviation Technology Co., Ltd.</p>
    <p class="home-entry-meta">UAV Pre-sales Engineer | 06/2025-12/2025</p>
  </div>
</div>

<div class="home-grid">
  <div class="home-section home-card">
    <h3>🏆 Awards and Honors</h3>
    <ul class="home-scroll-list">
      <li>First Prize of the National College Student Mathematics Competition, Shaanxi Province Division (Top 5%)</li>
      <li>Excellent Oral Presentation Award of the 5th China Conference on Remote Sensing of Wetlands (Top 5%)</li>
      <li>First-Class Scholarship of CNU (Top 10%)</li>
      <li>Merit Student Award of CNU (Top 10%)</li>
      <li>Third Prize of the National English Competition for College Students, Shaanxi Province Division (Top 15%)</li>
      <li>Second-Class Scholarship of CNU (Top 20%)</li>
    </ul>
  </div>

  <div class="home-section home-card">
    <h3>🛠 Skills</h3>
    <ul>
      <li>Programming and Analysis: Python, R, MATLAB</li>
      <li>Remote Sensing and GIS: Google Earth Engine, ArcGIS Pro, QGIS, ENVI, SNAP</li>
      <li>Research Skills: Time-series remote sensing, machine learning, deep learning, change detection</li>
      <li>Languages: English (CET-6)</li>
    </ul>
  </div>
</div>
