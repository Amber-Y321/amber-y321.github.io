---
layout: single
title: ""
permalink: /projects/ecommerce-command-center/
author_profile: true
classes: wide
description: "A repeatable workflow for detecting ecommerce issues, diagnosing drivers, and testing management decisions."
---

<section class="case-stage">
  <div class="case-stage__copy">
    <p class="feature-label"><span>CASE 01</span> ECOMMERCE ANALYTICS</p>
    <h1>From recurring analysis to a repeatable decision workflow.</h1>
    <p>I connected customer, order, product, marketing, and location data into a system that helps management detect performance issues, pinpoint likely drivers, and evaluate the next action.</p>
    <div class="hero-actions">
      <a class="button button--light" href="https://ecommerceanalytics-mdjdkr9yopuaqjaddvujmg.streamlit.app/" target="_blank" rel="noopener">Explore live dashboard ↗</a>
      <a class="feature-link" href="#decisions">See the decisions ↓</a>
    </div>
  </div>
  <div class="case-stage__visual">
    <div class="browser-frame browser-frame--hero">
      <div class="browser-bar"><i></i><i></i><i></i><span>Executive Overview</span></div>
      <img src="/materials/ecommerce-command-center/executive-overview.png" alt="Executive Overview showing ecommerce KPIs and priorities">
    </div>
    <p>One entry point surfaces the priority and routes the next analysis.</p>
  </div>
</section>

<section class="transformation-line" aria-label="Project transformation">
  <div><span>BEFORE</span><strong>Separate questions. Manual investigation. Hidden assumptions.</strong></div>
  <b aria-hidden="true">→</b>
  <div><span>AFTER</span><strong>One diagnostic entry point. Clear analytical routes. Testable actions.</strong></div>
</section>

<section class="case-intro">
  <p class="section-index">01 / THE SYSTEM</p>
  <div>
    <h2>Start with the signal.<br>Go directly to the decision.</h2>
    <p>The Executive Overview identifies the management priority. Instead of reviewing every report, the user moves directly to the relevant diagnostic or scenario.</p>
  </div>
</section>

<section class="route-map" aria-label="Command center decision routes">
  <div class="route-map__origin"><small>MONITOR + PINPOINT</small><strong>Executive<br>Overview</strong><span>What deserves attention?</span></div>
  <div class="route-map__line" aria-hidden="true"></div>
  <div class="route-map__destinations">
    <div><small>REVENUE + PRODUCTS</small><strong>Assortment Strategy</strong></div>
    <div><small>CUSTOMERS + CHANNELS</small><strong>Marketing Investment</strong></div>
    <div><small>OPERATING RISK</small><strong>Relocation Scenario</strong></div>
  </div>
</section>

<section class="decision-showcase" id="decisions">
  <div class="case-intro case-intro--compact">
    <p class="section-index">02 / THE DECISIONS</p>
    <div><h2>Four views.<br>Four clear next moves.</h2></div>
  </div>

  <article class="decision-story">
    <div class="decision-story__image"><img src="/materials/ecommerce-command-center/executive-03-concentration.png" alt="Revenue concentration dashboard"></div>
    <div class="decision-story__copy"><span>01 · BUSINESS HEALTH</span><h3>Where should leadership focus first?</h3><p>Detect performance exceptions and concentration risk before opening another report.</p><strong>Signal surfaced</strong><p>76% of modeled revenue was concentrated in one category.</p></div>
  </article>

  <article class="decision-story decision-story--reverse">
    <div class="decision-story__image"><img src="/materials/ecommerce-command-center/revenue-03-profit-effort.png" alt="Profit-to-effort assortment strategy matrix"></div>
    <div class="decision-story__copy"><span>02 · ASSORTMENT</span><h3>What should we protect, expand, or reduce?</h3><p>Balance profit potential against the effort required to operate each category.</p><strong>Action enabled</strong><p>Test a gradual shift toward higher-profit, lower-effort products.</p></div>
  </article>

  <article class="decision-story">
    <div class="decision-story__image"><img src="/materials/ecommerce-command-center/marketing-02-conversion.png" alt="Marketing source conversion comparison"></div>
    <div class="decision-story__copy"><span>03 · MARKETING</span><h3>Where should the next dollar go?</h3><p>Compare channel quality across the funnel—not traffic volume alone.</p><strong>Action enabled</strong><p>Match channels to acquisition, discovery, or retention roles.</p></div>
  </article>

  <article class="decision-story decision-story--reverse">
    <div class="decision-story__image"><img src="/materials/ecommerce-command-center/relocation-02-breakeven.png" alt="Store relocation break-even scenario"></div>
    <div class="decision-story__copy"><span>04 · OPERATIONS</span><h3>When would relocation improve the business?</h3><p>Test occupancy savings against customer loss and revenue exposure.</p><strong>Scenario result</strong><p>$60K in rent savings did not offset the modeled revenue risk.</p></div>
  </article>
</section>

<section class="impact-editorial">
  <div><p class="section-index">03 / APPLIED IMPACT</p><h2>Analysis connected<br>to commercial action.</h2></div>
  <div class="impact-editorial__metrics"><p><strong>+43.1%</strong><span>observed YoY revenue growth</span></p><p><strong>+49%</strong><span>observed YoY online-session growth</span></p></div>
  <p class="impact-note">Observed outcomes, not a controlled causal estimate. The public dashboard uses realistically modeled data; commercial outcomes are reported separately.</p>
</section>

<details class="case-deep-dive editorial-details">
  <summary><span>Want the methodology?</span> Explore the analytical build <b>+</b></summary>
  <div class="deep-dive-content">
    <div class="method-grid">
      <article><span>01</span><strong>Prepare</strong><p>Structured customer, order, product, and session data; engineered time, margin, location, funnel, and behavioral features.</p></article>
      <article><span>02</span><strong>Diagnose</strong><p>Built KPI logic, concentration measures, trend comparisons, K-means segments, and profit-to-effort views.</p></article>
      <article><span>03</span><strong>Model</strong><p>Converted assortment and relocation questions into adjustable scenarios with visible assumptions.</p></article>
      <article><span>04</span><strong>Operationalize</strong><p>Designed four Streamlit pages that move from business question to evidence to recommended action.</p></article>
    </div>
    <ul class="tech-list"><li>Python</li><li>Pandas</li><li>Plotly</li><li>Streamlit</li><li>scikit-learn</li><li>Segmentation</li><li>Scenario modeling</li></ul>
  </div>
</details>

<section class="contact-band">
  <p class="contact-label">EXPLORE</p>
  <h2>See the decision system in action.</h2>
  <p><a href="https://ecommerceanalytics-mdjdkr9yopuaqjaddvujmg.streamlit.app/" target="_blank" rel="noopener">Live dashboard ↗</a> · <a href="https://github.com/Amber-Y321/Ecommerce_Analytics" target="_blank" rel="noopener">Repository ↗</a> · <a href="/">Return home</a></p>
</section>
