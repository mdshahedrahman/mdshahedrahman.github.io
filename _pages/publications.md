---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

<style>
/* ---------- Scope all styles to this page ---------- */
.pub-page {
  font-family: 'Georgia', serif;
  color: #333;
}

/* Main content container */
.pub-page .content {
  width: 100%;
  max-width: 1100px;
  margin: 30px auto;
  padding: 20px;
  background-color: #ffffff;
  border-radius: 15px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

/* Section headings */
.pub-page h1, .pub-page h2, .pub-page h3, .pub-page h4, .pub-page h5, .pub-page h6 {
  margin: 0 0 0.5em;
  line-height: 1.2;
  font-weight: bold;
}

.pub-page .content h2 {
  font-size: 20px;
  color: #1e3d8f;
  margin-bottom: 15px;
  text-align: center;
  position: relative;
}
.pub-page .content h2::after {
  content: '';
  display: block;
  width: 60%;
  height: 1px;
  background-color: #cccccc;
  margin: 10px auto;
}

/* Typography */
.pub-page p,
.pub-page li {
  font-size: 15.5px;
  line-height: 1.6;
  text-align: justify;
  margin-bottom: 13px;
}

.pub-page ul {
  list-style: disc;
  margin-left: 1px;
}
.pub-page ul li {
  text-align: justify;
  margin-bottom: 10px;
}
.pub-page ul li::marker {
  font-weight: bold;
}

/* Cards grid */
.pub-page .experience-container {
  display: grid;
  grid-template-columns: 1fr;
  gap: 20px;
}

/* Card */
.pub-page .experience-card {
  background-color: #f9f9f9;
  border-radius: 12px;
  padding: 15px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.05);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  border-left: 5px solid #1e3d8f;
}
.pub-page .experience-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 6px 15px rgba(0,0,0,0.1);
}
.pub-page .experience-card h3 {
  font-size: 18px;
  color: #1e3d8f;
  margin-bottom: 8px;
}

/* Row of links inside a card */
.pub-page .link-row {
  display: flex;
  gap: 16px;
  flex-wrap: wrap;
  align-items: center;
  margin: 8px 0 12px;
}
.pub-page .link-row a {
  font-weight: bold;
  white-space: nowrap; /* keep labels intact */
  color: #1e3d8f;
  text-decoration: none;
}
.pub-page .link-row a:hover {
  text-decoration: underline;
}
.pub-page .link-label {
  font-weight: bold;
  margin-right: 4px;
  color: #333;
}

/* Section header + content */
.pub-page .section-header {
  font-size: 16px;
  font-weight: bold;
  color: #1e3d8f;
  margin-bottom: 6px;
  border-bottom: 2px solid #cccccc;
  padding-bottom: 3px;
}
.pub-page .section-content {
  font-size: 14px;
  line-height: 1.6;
  color: #333;
  text-align: justify;
  margin-bottom: 13px;
}
</style>

<div class="pub-page">
  <div class="content">
    <h2>Selected Publications</h2>

    <div class="experience-container">

      <div class="experience-card">
        <h3>HuggingGraph: Understanding the Supply Chain of LLM Ecosystem</h3>

        <div class="link-row">
          <span class="link-label">Links:</span>
          <a href="https://dl.acm.org/doi/10.1145/3746252.3761510" target="_blank" rel="noopener noreferrer">Paper_CIKM</a>
          <a href="https://arxiv.org/abs/2507.14240" target="_blank" rel="noopener noreferrer">Paper_arXiv</a>
          <a href="https://github.com/SC-Lab-Go/HuggingGraph" target="_blank" rel="noopener noreferrer">Dataset</a>
          <a href="https://ai-supply-chain.github.io/" target="_blank" rel="noopener noreferrer">Simulator</a>
        </div>

        <div class="section-header">Overview</div>
        <div class="section-content">
          <p>HuggingGraph, the first work to systematically collect the LLM supply chain information and analyze it at scale.
📦 Systematically collect LLM supply chain data, 🔗 Construct an LLM supply chain graph, and 🔍 Perform rich graph analytics.</p>
        </div>
      </div>

      <!-- Duplicate .experience-card blocks here for additional publications -->

    </div>
  </div>
</div>
