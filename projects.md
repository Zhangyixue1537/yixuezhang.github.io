---
layout: page
title: Projects
tagline: A list of my projects
permalink: /projects/
ref: projects
order: 3
---
<style>
.project-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
  box-shadow: 0 0 5px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card img:hover {
  transform: scale(1.05);
  box-shadow: 0 0 15px rgba(0,0,0,0.3);
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 20px;
}

.project-card {
  text-align: center;
}

.project-card img {
  width: 100%;
  height: 180px; /* 统一高度裁切 */
  object-fit: cover; /* 保持图片比例，超出部分裁切 */
  border-radius: 10px;
  box-shadow: 0 0 5px rgba(0,0,0,0.1);
}

.project-card-title {
  font-weight: bold;
  margin-top: 10px;
}

.project-card-desc {
  font-size: 0.95em;
  color: #555;
  margin-top: 5px;
}
</style>

<div class="project-grid">

  <div class="project-card">
    <a href="/projects/taxi1/">
      <img src="/figures/taxi.jpg" alt="Toronto's Accessible Taxi (I)">
    </a>
    <div class="project-card-title">Toronto's Accessible Taxi (I)</div>
    <div class="project-card-desc">Multi-level regression of accessible taxi ridership</div>
  </div>

  <div class="project-card">
    <a href="/projects/taxi2/">
      <img src="/figures/cluster.jpg" alt="Toronto's Accessible Taxi (II)">
    </a>
    <div class="project-card-title">Toronto's Accessible Taxi (II)</div>
    <div class="project-card-desc">Cluster analysis of accessible taxi users before and during COVID-19</div>
  </div>

  <div class="project-card">
    <a href="/projects/vfh/">
      <img src="/figures/vfh.jpg" alt="Toronto's Vehicle-for-hire services">
    </a>
    <div class="project-card-title">Toronto's Vehicle-for-hire services</div>
    <div class="project-card-desc">Analyzing the impacts of Uber/Lyft on Toronto's transport network (2024)</div>
  </div>

  <div class="project-card">
    <a href="/projects/odt/">
      <img src="/figures/odt.jpg" alt="Belleville On-Demand Transit">
    </a>
    <div class="project-card-title">Belleville On-Demand Transit</div>
    <div class="project-card-desc">Identifying barriers to nighttime activity participation</div>
  </div>

  <div class="project-card">
    <a href="/projects/teoz/">
      <img src="/figures/teoz.jpg" alt="Transportation Opportunity Zones">
    </a>
    <div class="project-card-title">Transportation Equity Opportunity Zones (TEOZ)</div>
    <div class="project-card-desc">Identifying Toronto's transportation equity zones</div>
  </div>

  <div class="project-card">
    <a href="/projects/sem_bicycle/">
      <img src="/figures/sc_bicycle.jpg" alt="Bicycle">
    </a>
    <div class="project-card-title">Factors Influencing Utilitarian and Recreational Cycling </div>
    <div class="project-card-desc">Factors Influencing Utilitarian and Recreational Cycling</div>
  </div>

  <!-- 可以继续添加其他项目 -->
</div>