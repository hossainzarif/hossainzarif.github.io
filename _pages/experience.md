---
layout: page
title: Experience
permalink: /experience/
description: Professional experience and research positions
nav: true
nav_order: 2
---

<div class="experience-page">
  <div class="container">
    <div class="row">
      <div class="col-lg-12">
        <!-- <h1 class="experience-title">Experience</h1> -->
        <!-- <p class="experience-subtitle">Professional journey and research positions</p> -->
      </div>
    </div>
    
    <div class="experience-content">
      {% include experience.liquid %}
    </div>
  </div>
</div>

<style>
.experience-page {
  padding: 2rem 0;
}

.experience-title {
  font-size: 4rem;
  font-weight: bold;
  color: #333;
  margin-bottom: 1rem;
  text-align: center;
}

.experience-subtitle {
  font-size: 1.5rem;
  color: #666;
  text-align: center;
  margin-bottom: 3rem;
}

.experience-content {
  margin-top: 2.5rem;
}

/* Responsive design */
@media (max-width: 768px) {
  .experience-title {
    font-size: 3.5rem;
  }
  
  .experience-subtitle {
    font-size: 1.1rem;
  }
}
</style> 