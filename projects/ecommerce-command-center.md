---
layout: single
title: "Ecommerce Analytics Command Center"
permalink: /projects/ecommerce-command-center/
author_profile: false
classes: wide
description: "A decision-support analytics case study connecting business health, assortment strategy, marketing investment, and store relocation."
---

<section class="case-hero">
  <p class="eyebrow">ECOMMERCE ANALYTICS CASE STUDY</p>
  <h1>Four management decisions. One transparent operating view.</h1>
  <p class="hero-summary">I translated a boutique retailer's recurring questions about performance, product mix, marketing, and location strategy into a decision-support command center.</p>
  <div class="hero-actions">
    <a class="button button--primary" href="https://ecommerceanalytics-mdjdkr9yopuaqjaddvujmg.streamlit.app/" target="_blank" rel="noopener">Explore the live dashboard ↗</a>
    <a class="button button--secondary" href="https://github.com/Amber-Y321/Ecommerce_Analytics" target="_blank" rel="noopener">View repository ↗</a>
  </div>
</section>

<figure class="case-hero-image">
  <img src="/materials/ecommerce-command-center/executive-overview.png" alt="Executive Overview page of the Ecommerce Analytics Command Center">
  <figcaption>Executive Overview · live Streamlit dashboard</figcaption>
</figure>

<section class="portfolio-section">
  <div class="case-facts">
    <div><span>ROLE</span><strong>Data Consultant</strong><small>Problem framing, analysis, scenario design, dashboard UX</small></div>
    <div><span>BUSINESS CONTEXT</span><strong>Boutique omnichannel retailer</strong><small>Growth, assortment complexity, limited marketing resources</small></div>
    <div><span>DELIVERABLE</span><strong>Four-page decision system</strong><small>Python, Streamlit, Plotly, customer segmentation</small></div>
  </div>
  <div class="data-disclosure"><strong>Data disclosure:</strong> The public dashboard uses realistically modeled ecommerce data based on operating patterns. The commercial results shown later come from the applied business engagement and are reported separately.</div>
</section>

<section class="portfolio-section">
  <p class="eyebrow">THE BUSINESS PROBLEM</p>
  <h2>The owner had dashboards. What was missing was decision structure.</h2>
  <p class="section-lead">Sales, customer, product, traffic, and location questions were being evaluated separately. That made it difficult to see tradeoffs—especially when a revenue opportunity could also increase operational effort or commercial risk.</p>
  <div class="tension-grid">
    <article><strong>Growth vs. concentration</strong><p>Was growth broad-based, or dependent on a narrow set of categories and customers?</p></article>
    <article><strong>Revenue vs. operational effort</strong><p>Which products generated attractive profit without adding disproportionate sourcing, sizing, return, or styling complexity?</p></article>
    <article><strong>Traffic vs. conversion quality</strong><p>Which channels produced purchase intent—not simply visits?</p></article>
    <article><strong>Rent savings vs. local revenue risk</strong><p>Could lower occupancy cost compensate for customers potentially lost after relocation?</p></article>
  </div>
</section>

<section class="portfolio-section">
  <p class="eyebrow">DECISION ARCHITECTURE</p>
  <h2>Each page ends with a management decision—not another chart.</h2>

  <article class="decision-case" id="executive-overview">
    <div class="decision-copy">
      <span class="decision-index">01 · BUSINESS HEALTH</span>
      <h3>Where should leadership focus first?</h3>
      <p><strong>Analysis:</strong> Combined revenue, orders, customers, AOV, conversion, returns, time trends, geography, and product concentration into an executive diagnostic.</p>
      <p><strong>Signal surfaced:</strong> The leading category represented <strong>76.0%</strong> of modeled revenue and the top five subcategories represented <strong>85.6%</strong>, making concentration an operating priority.</p>
      <p class="decision-enabled"><strong>Decision enabled:</strong> Route the next management conversation toward revenue growth, marketing quality, margin protection, or operational simplification.</p>
    </div>
    <div class="dashboard-gallery">
      <figure><a href="/materials/ecommerce-command-center/executive-overview.png" target="_blank"><img src="/materials/ecommerce-command-center/executive-overview.png" alt="Executive dashboard with revenue, order, customer, conversion, and return KPIs"></a><figcaption>Overview and executive KPIs</figcaption></figure>
      <figure><a href="/materials/ecommerce-command-center/executive-02-health-trend.png" target="_blank"><img src="/materials/ecommerce-command-center/executive-02-health-trend.png" alt="Business health trends in revenue, orders, and average order value"></a><figcaption>Business health trends</figcaption></figure>
      <figure><a href="/materials/ecommerce-command-center/executive-03-concentration.png" target="_blank"><img src="/materials/ecommerce-command-center/executive-03-concentration.png" alt="Revenue concentration analysis by category and subcategory"></a><figcaption>Revenue concentration risk</figcaption></figure>
      <figure><a href="/materials/ecommerce-command-center/executive-04-alerts.png" target="_blank"><img src="/materials/ecommerce-command-center/executive-04-alerts.png" alt="Traffic conversion and margin alerts"></a><figcaption>Traffic, conversion, and margin alerts</figcaption></figure>
    </div>
  </article>

  <article class="decision-case" id="revenue-assortment">
    <div class="decision-copy">
      <span class="decision-index">02 · GROWTH LEVERS</span>
      <h3>What should the retailer protect, expand, test, or reduce?</h3>
      <p><strong>Analysis:</strong> Connected current revenue contribution, recent growth signals, gross profit, and an owner-defined operational-effort score at category and subcategory level.</p>
      <p><strong>Signal surfaced:</strong> High-revenue apparel remained important, but selected jewelry, handbags, scarves, and cardigans offered a credible path toward a higher-profit, lower-effort mix.</p>
      <p class="decision-enabled"><strong>Decision enabled:</strong> Test a gradual assortment pivot instead of making a risky all-or-nothing category exit.</p>
    </div>
    <div class="dashboard-gallery">
      <figure><a href="/materials/ecommerce-command-center/revenue-growth.png" target="_blank"><img src="/materials/ecommerce-command-center/revenue-growth.png" alt="Current category and subcategory revenue drivers"></a><figcaption>Current revenue drivers</figcaption></figure>
      <figure><a href="/materials/ecommerce-command-center/revenue-02-trend.png" target="_blank"><img src="/materials/ecommerce-command-center/revenue-02-trend.png" alt="Revenue driver trends over time"></a><figcaption>Current drivers and evolving trends</figcaption></figure>
      <figure><a href="/materials/ecommerce-command-center/revenue-03-profit-effort.png" target="_blank"><img src="/materials/ecommerce-command-center/revenue-03-profit-effort.png" alt="Profit-to-effort assortment strategy matrix"></a><figcaption>Profit-to-effort tradeoff</figcaption></figure>
      <figure><a href="/materials/ecommerce-command-center/revenue-04-scenario.png" target="_blank"><img src="/materials/ecommerce-command-center/revenue-04-scenario.png" alt="Focused assortment scenario analysis"></a><figcaption>Gradual assortment-pivot scenario</figcaption></figure>
    </div>
  </article>

  <article class="decision-case" id="marketing-investment">
    <div class="decision-copy">
      <span class="decision-index">03 · CAPITAL ALLOCATION</span>
      <h3>Where should the next marketing dollar—and hour—go?</h3>
      <p><strong>Analysis:</strong> Compared traffic trends and source-level add-to-cart, checkout, and order conversion, then connected channel performance with behavioral customer segments.</p>
      <p><strong>Signal surfaced:</strong> Modeled order conversion was similar across the selected sources, reinforcing that allocation should consider intent, funnel friction, and campaign role—not traffic volume alone.</p>
      <p class="decision-enabled"><strong>Decision enabled:</strong> Use high-intent channels for direct response, visual channels for discovery, and segments for targeted retention rather than broad discounting.</p>
    </div>
    <div class="dashboard-gallery">
      <figure><a href="/materials/ecommerce-command-center/marketing-investment.png" target="_blank"><img src="/materials/ecommerce-command-center/marketing-investment.png" alt="Marketing Investment dashboard with traffic trends and conversion funnel"></a><figcaption>Traffic trend and source funnel</figcaption></figure>
      <figure><a href="/materials/ecommerce-command-center/marketing-02-conversion.png" target="_blank"><img src="/materials/ecommerce-command-center/marketing-02-conversion.png" alt="Conversion comparison across marketing sources"></a><figcaption>Source-level conversion quality</figcaption></figure>
      <figure><a href="/materials/ecommerce-command-center/marketing-03-ai-support.png" target="_blank"><img src="/materials/ecommerce-command-center/marketing-03-ai-support.png" alt="Customer segments and AI-assisted campaign planning"></a><figcaption>Segment-led campaign decision support</figcaption></figure>
    </div>
  </article>

  <article class="decision-case" id="relocation-scenario">
    <div class="decision-copy">
      <span class="decision-index">04 · STRATEGIC SCENARIO</span>
      <h3>When would relocating improve the business?</h3>
      <p><strong>Analysis:</strong> Built an adjustable break-even model using rent savings, local revenue dependency, expected local-customer loss, and online recapture.</p>
      <p><strong>Signal surfaced:</strong> In the default modeled scenario, <strong>$60K</strong> in rent savings did not offset local revenue risk, producing an estimated <strong>-$387K net effect</strong>.</p>
      <p class="decision-enabled"><strong>Decision enabled:</strong> Define the exact retention and online-recapture conditions required before relocation becomes financially defensible.</p>
    </div>
    <div class="dashboard-gallery">
      <figure><a href="/materials/ecommerce-command-center/relocation-scenario.png" target="_blank"><img src="/materials/ecommerce-command-center/relocation-scenario.png" alt="Local versus non-local revenue dependency"></a><figcaption>Local-customer revenue dependency</figcaption></figure>
      <figure><a href="/materials/ecommerce-command-center/relocation-02-breakeven.png" target="_blank"><img src="/materials/ecommerce-command-center/relocation-02-breakeven.png" alt="Adjustable rent-saving break-even scenario"></a><figcaption>Adjustable relocation break-even model</figcaption></figure>
    </div>
  </article>
</section>

<section class="portfolio-section">
  <p class="eyebrow">HOW I BUILT IT</p>
  <h2>From modeled operating data to repeatable decision logic.</h2>
  <div class="method-grid">
    <article><span>01</span><strong>Prepare</strong><p>Structured customer, order, product, and session data; engineered time, margin, location, funnel, and behavioral features.</p></article>
    <article><span>02</span><strong>Diagnose</strong><p>Built KPI logic, concentration measures, trend comparisons, K-means segments, and profit-to-effort views.</p></article>
    <article><span>03</span><strong>Model</strong><p>Converted assortment and relocation questions into adjustable scenarios with visible assumptions.</p></article>
    <article><span>04</span><strong>Operationalize</strong><p>Designed four Streamlit pages that move from business question to evidence to recommended next action.</p></article>
  </div>
  <ul class="tech-list">
    <li>Python</li><li>Pandas</li><li>Plotly</li><li>Streamlit</li><li>scikit-learn</li><li>Scenario modeling</li><li>Responsible AI assistance</li>
  </ul>
</section>

<section class="portfolio-section">
  <p class="eyebrow">APPLIED BUSINESS IMPACT</p>
  <h2>The analysis also supported a live segmentation-led marketing strategy.</h2>
  <div class="impact-grid">
    <div class="metric-card"><strong>+43.1%</strong><span>year-over-year revenue lift observed during the applied strategy period</span></div>
    <div class="metric-card"><strong>+49%</strong><span>year-over-year growth in online sessions during the same period</span></div>
  </div>
  <div class="note"><strong>Interpretation:</strong> These are observed results, not a controlled causal estimate. Seasonality, baseline growth, campaign timing, and other operating changes may also have contributed.</div>
</section>

<section class="portfolio-section takeaway-section">
  <p class="eyebrow">WHAT THIS PROJECT DEMONSTRATES</p>
  <h2>Business analysis that connects evidence, tradeoffs, and action.</h2>
  <div class="takeaway-grid">
    <p><strong>Structured problem solving</strong><br>Turned four ambiguous owner questions into testable analytical frameworks.</p>
    <p><strong>Commercial judgment</strong><br>Balanced revenue growth with margin, effort, concentration, and risk.</p>
    <p><strong>Scenario thinking</strong><br>Made assumptions adjustable instead of presenting forecasts as certainty.</p>
    <p><strong>Stakeholder communication</strong><br>Designed every view around the decision a nontechnical owner needs to make.</p>
  </div>
</section>

<section class="contact-band">
  <p class="contact-label">EXPLORE</p>
  <h2>See the decision system in action.</h2>
  <p><a href="https://ecommerceanalytics-mdjdkr9yopuaqjaddvujmg.streamlit.app/" target="_blank" rel="noopener">Live dashboard ↗</a> · <a href="https://github.com/Amber-Y321/Ecommerce_Analytics" target="_blank" rel="noopener">Repository ↗</a> · <a href="/">Return home</a></p>
</section>
