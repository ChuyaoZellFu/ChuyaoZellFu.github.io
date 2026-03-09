---
layout: default
title: Projects
permalink: /projects/
---

<div class="projects-container">
  <h1>Projects</h1>
  
  <div class="projects-intro">
    <p>
      A selection of my research projects and coursework. My projects span world models, 
      robot learning, and embodied AI, with a focus on practical implementations using 
      PyTorch, ROS, and simulation environments.
    </p>
  </div>

  <!-- Research Projects -->
  <section class="project-category">
    <h2>Research Projects</h2>
    
    <div class="project-grid">
      <!-- Project 1 -->
      <div class="project-card">
        <div class="project-header">
          <h3>Visual Token Space World Models</h3>
          <span class="project-status ongoing">Ongoing</span>
        </div>
        <p class="project-description">
          Developing a world model that predicts robot dynamics directly in the visual token 
          space of VLA models, achieving 15% better accuracy and 4× speedup.
        </p>
        <div class="project-tech">
          <span class="tech-tag">PyTorch</span>
          <span class="tech-tag">Transformers</span>
          <span class="tech-tag">VLA Models</span>
        </div>
        <div class="project-links">
          <a href="/publications/" class="project-link">Paper →</a>
        </div>
      </div>

      <!-- Project 2 -->
      <div class="project-card">
        <div class="project-header">
          <h3>Humanoid Robot RL with Isaac Sim</h3>
          <span class="project-status completed">Completed</span>
        </div>
        <p class="project-description">
          Implemented reinforcement learning algorithms for humanoid robot locomotion and 
          manipulation tasks in NVIDIA Isaac Sim simulation environment.
        </p>
        <div class="project-tech">
          <span class="tech-tag">Isaac Sim</span>
          <span class="tech-tag">RL</span>
          <span class="tech-tag">PyTorch</span>
        </div>
        <div class="project-links">
          <span class="project-link disabled">Code (Private)</span>
        </div>
      </div>

      <!-- Project 3 -->
      <div class="project-card">
        <div class="project-header">
          <h3>Robot Manipulation Benchmarks</h3>
          <span class="project-status completed">Completed</span>
        </div>
        <p class="project-description">
          Evaluated and benchmarked various robot manipulation policies on RoboTwin, LIBERO, 
          and RLBench datasets. Analyzed generalization across different tasks and environments.
        </p>
        <div class="project-tech">
          <span class="tech-tag">RoboTwin</span>
          <span class="tech-tag">LIBERO</span>
          <span class="tech-tag">RLBench</span>
        </div>
        <div class="project-links">
          <span class="project-link disabled">Report (Available upon request)</span>
        </div>
      </div>
    </div>
  </section>

  <!-- Course Projects -->
  <section class="project-category">
    <h2>Course Projects <span class="gpa-badge">GPA: 3.90/4.0</span></h2>
    
    <div class="project-grid">
      <!-- Course Project 1 -->
      <div class="project-card course">
        <div class="project-header">
          <h3>[Course Name] Final Project</h3>
          <span class="project-grade">Grade: A/A+</span>
        </div>
        <p class="project-description">
          [Description of a high-quality course project. You can customize this.]
        </p>
        <div class="project-tech">
          <span class="tech-tag">[Technology]</span>
        </div>
      </div>

      <!-- Course Project 2 -->
      <div class="project-card course">
        <div class="project-header">
          <h3>[Course Name] Final Project</h3>
          <span class="project-grade">Grade: A/A+</span>
        </div>
        <p class="project-description">
          [Description of another high-quality course project.]
        </p>
        <div class="project-tech">
          <span class="tech-tag">[Technology]</span>
        </div>
      </div>
    </div>
    
    <p class="course-note">
      <em>Note: Course projects demonstrate strong academic performance (GPA 3.90/4.0). 
      Detailed descriptions available upon request.</em>
    </p>
  </section>

  <!-- Skills Section -->
  <section class="skills-section">
    <h2>Technical Skills</h2>
    
    <div class="skills-grid">
      <div class="skill-category">
        <h3>Programming</h3>
        <div class="skill-tags">
          <span class="skill-tag expert">Python</span>
          <span class="skill-tag intermediate">C++</span>
          <span class="skill-tag intermediate">CUDA</span>
        </div>
      </div>
      
      <div class="skill-category">
        <h3>Machine Learning</h3>
        <div class="skill-tags">
          <span class="skill-tag expert">PyTorch</span>
          <span class="skill-tag expert">Transformers</span>
          <span class="skill-tag intermediate">JAX</span>
        </div>
      </div>
      
      <div class="skill-category">
        <h3>Robotics</h3>
        <div class="skill-tags">
          <span class="skill-tag expert">ROS</span>
          <span class="skill-tag expert">Isaac Sim</span>
          <span class="skill-tag intermediate">Gazebo</span>
        </div>
      </div>
      
      <div class="skill-category">
        <h3>Tools & Platforms</h3>
        <div class="skill-tags">
          <span class="skill-tag expert">Linux</span>
          <span class="skill-tag expert">Git</span>
          <span class="skill-tag intermediate">Docker</span>
        </div>
      </div>
    </div>
  </section>

</div>
