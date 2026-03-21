---
layout: archive
title: "Tutorials"
permalink: /tutorials/
author_profile: true
---

<style>
.tutorial-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.tutorial-card {
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 20px;
  background: #fff;
  box-shadow: 0 2px 6px rgba(0,0,0,0.08);
  transition: transform 0.2s, box-shadow 0.2s;
  text-decoration: none;
  color: inherit;
  display: block;
}

.tutorial-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 6px 16px rgba(0,0,0,0.15);
  text-decoration: none;
  color: inherit;
}

.tutorial-card h3 {
  margin-top: 0;
  color: #2a6496;
}

.tutorial-card .tags {
  margin-top: 12px;
}

.tutorial-card .tag {
  display: inline-block;
  background: #eef4fb;
  color: #2a6496;
  border-radius: 4px;
  padding: 2px 8px;
  font-size: 0.8em;
  margin-right: 4px;
}
</style>

<div class="tutorial-grid">

  <a class="tutorial-card" href="https://nbviewer.org/github/nsharma3150/nsharma3150.github.io/blob/master/files/Normative_Modeling_Tutorial_8th_Feb_2026_Jena.ipynb" target="_blank">
    <h3>🧠 Normative Modeling Tutorial</h3>
    <p>Hands-on workshop taught at Friedrich-Schiller-University Jena (Feb 2026). Covers why ML fails for brain data, Z-scores, GAMLSS, centile curves, and patient detection.</p>
    <div class="tags">
      <span class="tag">Neuroimaging</span>
      <span class="tag">GAMLSS</span>
      <span class="tag">Python</span>
    </div>
  </a>

  <!-- COPY THE BLOCK ABOVE TO ADD A NEW TUTORIAL -->

</div>
