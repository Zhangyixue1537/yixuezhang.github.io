---
layout: default
title: Home
header: Welcome to Yixue's personal page!
---

<style>
.bio-section p {
  margin-bottom: 20px; /* 调整段落间距，如需更大可改25px或30px */
}

.profile-img {
  width: 350px; /* 原来是300px，这里增大 */
  border-radius: 10px;
  box-shadow: 0 0 5px rgba(0,0,0,0.1);
}
</style>

<div style="display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap;">

  <!-- 左侧简介 -->
  <div style="flex: 1; min-width: 250px; margin-right: 20px;">
    <h3>About</h3>
    <p>I am a data scientist specializing in travel behaviour analysis, accessibility, and transportation equity. I hold a Ph.D. in Planning from the University of Toronto, where my research focused on understanding the travel behaviour of people using emerging transportation modes such as ride-sharing and on-demand transit, and evaluating the social impacts of these transportation services. I also hold a Master’s degree in Urban and Regional Planning and a Bachelor’s degree in Economics from Peking University</p>
    <p>My technical expertise includes machine learning, statistical modeling, and spatial analysis, applied to multi-million-record transportation datasets. I have extensive experience with Python, R, SQL, and spatial analysis tools such as QGIS. Currently, I work as a Research Analyst at the City of Toronto, applying advanced data analytics and predictive modeling to improve urban mobility systems and inform equitable transportation policies.</p>
    <p>I am passionate about leveraging data-driven insights to enhance user experience and mobility access, especially for underserved communities. My work combines rigorous quantitative analysis with a strong commitment to real-world impact.</p>

  </div>

  <!-- 右侧头像 -->
  <div style="flex: 0 0 350px; text-align: center;">
    <img src="{{ '/figures/profile1YZ.jpg' | relative_url }}"
         alt="Yixue Zhang"
         class="profile-img">
  </div>

</div>