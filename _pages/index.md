---
layout: default
title: Home
permalink: /
---

<div class="home-container">
  
  <!-- Header Section -->
  <section class="hero">
    <div class="profile-section">
      <div class="profile-image">
        <img src="/assets/images/profile.jpg" alt="Chuyao Fu" class="profile-photo" onerror="this.src='/assets/images/default-avatar.png'">
      </div>
      <div class="profile-info">
        <h1>Chuyao Fu</h1>
        <p class="tagline">PhD Applicant in Robot Learning</p>
        <p class="subtitle">World Models · Vision-Language-Action Models · Embodied AI</p>
        <div class="contact-links">
          <a href="mailto:12310306@mail.sustech.edu.cn" class="contact-btn">Email</a>
          <a href="https://github.com/ChuyaoZellFu" class="contact-btn" target="_blank">GitHub</a>
          <a href="/assets/cv.pdf" class="contact-btn">CV</a>
        </div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section class="about">
    <h2>About Me</h2>
    <p>
      I am a senior undergraduate student at <strong>Southern University of Science and Technology (SUSTech)</strong>, 
      majoring in Electronic Engineering with a GPA of <strong>3.90/4.0</strong>.
    </p>
    <p>
      My research focuses on <strong>world models for robot learning</strong>, particularly on developing 
      efficient visual representations for Vision-Language-Action (VLA) models. I am passionate about 
      enabling robots to develop broadly intelligent behavior through learning and interaction.
    </p>
    <p>
      I have hands-on experience with <strong>PyTorch, ROS, Isaac Sim</strong>, and various robot manipulation 
      benchmarks including RoboTwin, LIBERO, and RLBench.
    </p>
  </section>

  <!-- Research Highlights -->
  <section class="research-highlights">
    <h2>Research Highlights</h2>
    <div class="highlight-card">
      <div class="highlight-content">
        <h3>Visual Token Space World Models</h3>
        <p class="highlight-status">📝 Under Review at ECCV 2026</p>
        <p>
          Developed a novel world model that predicts dynamics directly in the <strong>Visual Token Space</strong> 
          of VLA models, bypassing the RGB bottleneck. Our approach achieves:
        </p>
        <ul>
          <li><strong>15% improvement</strong> in prediction accuracy</li>
          <li><strong>4× faster</strong> inference speed</li>
          <li>Better performance on VLA trajectory evaluation tasks</li>
        </ul>
        <p class="highlight-insight">
          <em>Key Insight:</em> Traditional world models predict RGB images, but VLA models encode RGB into 
          visual tokens anyway. By predicting directly in token space, we eliminate the information loss 
          from VAE encode/decode cycles.
        </p>
      </div>
    </div>
  </section>

  <!-- News Section -->
  <section class="news">
    <h2>News</h2>
    <ul class="news-list">
      <li>
        <span class="news-date">Mar 2026</span>
        <span class="news-content">Submitted my first-author paper to ECCV 2026</span>
      </li>
      <li>
        <span class="news-date">Feb 2026</span>
        <span class="news-content">Started applying for PhD programs in Robot Learning</span>
      </li>
      <li>
        <span class="news-date">2025</span>
        <span class="news-content">Research internship on humanoid robot RL using Isaac Sim</span>
      </li>
    </ul>
  </section>

  <!-- Quick Links -->
  <section class="quick-links">
    <h2>Explore</h2>
    <div class="link-cards">
      <a href="/publications/" class="link-card">
        <h3>📄 Publications</h3>
        <p>My research papers and submissions</p>
      </a>
      <a href="/projects/" class="link-card">
        <h3>🔬 Projects</h3>
        <p>Research and course projects</p>
      </a>
      <a href="/assets/cv.pdf" class="link-card">
        <h3>📋 CV</h3>
        <p>Download my full CV</p>
      </a>
    </div>
  </section>

</div>
