---
layout: default
title: Publications
permalink: /publications/
---

<div class="publications-container">
  <h1>Publications</h1>
  
  <div class="publication-filters">
    <button class="filter-btn active" data-filter="all">All</button>
    <button class="filter-btn" data-filter="under-review">Under Review</button>
    <button class="filter-btn" data-filter="published">Published</button>
  </div>

  <!-- Under Review -->
  <section class="publication-section" data-category="under-review">
    <h2>Under Review</h2>
    
    <div class="publication-card featured">
      <div class="pub-badge">First Author</div>
      <h3 class="pub-title">Token-World: Native Latent Dynamic World Model for Vision-Language-Action Models</h3>
      <p class="pub-authors"><strong>Chuyao Fu</strong>, [Co-author names]</p>
      <p class="pub-venue">Under Review at ECCV 2026</p>
      
      <div class="pub-abstract">
        <h4>Abstract</h4>
        <p>
          Current world models for robot learning typically predict future RGB images, which are then 
          encoded into visual tokens by Vision-Language-Action (VLA) models. This RGB-centric approach 
          creates an information bottleneck: VAE encoding/decoding introduces errors and inefficiencies.
        </p>
        <p>
          We propose <strong>Token-World</strong>, a native latent dynamic world model that predicts 
          directly in the <strong>Visual Token Space</strong> of VLA models. By bypassing the RGB 
          representation entirely, our model achieves superior prediction accuracy and computational 
          efficiency.
        </p>
      </div>
      
      <div class="pub-highlights">
        <h4>Key Contributions</h4>
        <ul>
          <li>
            <strong>Novel Representation:</strong> First world model to operate natively in VLA visual 
            token space, eliminating the RGB bottleneck
          </li>
          <li>
            <strong>Superior Performance:</strong> 15% improvement in prediction accuracy over RGB-based 
            baselines
          </li>
          <li>
            <strong>Efficiency Gains:</strong> 4× faster inference, enabling real-time robot control
          </li>
          <li>
            <strong>VLA Integration:</strong> Demonstrated effectiveness on VLA trajectory evaluation 
            tasks
          </li>
        </ul>
      </div>
      
      <div class="pub-links">
        <a href="#" class="pub-link disabled">Paper (Coming Soon)</a>
        <a href="#" class="pub-link disabled">Code (Coming Soon)</a>
        <a href="#" class="pub-link disabled">Project Page (Coming Soon)</a>
      </div>
    </div>
  </section>

  <!-- Published -->
  <section class="publication-section" data-category="published">
    <h2>Published</h2>
    <p class="empty-message">More publications coming soon...</p>
  </section>

  <!-- Research Statement -->
  <section class="research-statement">
    <h2>Research Interests</h2>
    <div class="interest-tags">
      <span class="interest-tag">World Models</span>
      <span class="interest-tag">Vision-Language-Action Models</span>
      <span class="interest-tag">Robot Learning</span>
      <span class="interest-tag">Embodied AI</span>
      <span class="interest-tag">Imitation Learning</span>
      <span class="interest-tag">Reinforcement Learning</span>
    </div>
    <p>
      I am broadly interested in enabling robots to develop intelligent behavior through learning and 
      interaction. My current focus is on developing efficient world models that can predict future 
      states in a compact latent space, enabling real-time robot planning and control.
    </p>
  </section>

</div>

<script>
// Simple filter functionality
document.querySelectorAll('.filter-btn').forEach(btn => {
  btn.addEventListener('click', function() {
    document.querySelectorAll('.filter-btn').forEach(b => b.classList.remove('active'));
    this.classList.add('active');
    
    const filter = this.dataset.filter;
    document.querySelectorAll('.publication-section').forEach(section => {
      if (filter === 'all' || section.dataset.category === filter) {
        section.style.display = 'block';
      } else {
        section.style.display = 'none';
      }
    });
  });
});
</script>
