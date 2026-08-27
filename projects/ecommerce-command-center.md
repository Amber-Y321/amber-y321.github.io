---
layout: single
title: ""
permalink: /projects/ecommerce-command-center/
author_profile: true
classes: wide
description: "A repeatable workflow for detecting ecommerce issues, diagnosing drivers, and testing management decisions."
---

<section class="continuous-case-columns">
  <div class="narrative-column">
    <section class="column-block column-block--hero">
      <p class="feature-label"><span>CASE 01</span> ECOMMERCE ANALYTICS</p>
      <h1>From recurring analysis to a repeatable decision workflow.</h1>
      <p class="column-lead">I connected customer, order, product, marketing, and location data into a system that helps management detect performance issues, pinpoint likely drivers, and evaluate the next action.</p>
      <div class="hero-actions">
        <a class="button button--primary" href="https://ecommerceanalytics-mdjdkr9yopuaqjaddvujmg.streamlit.app/" target="_blank" rel="noopener">Explore live dashboard ↗</a>
      </div>
      <div class="operating-loop"><span>Detect</span><b>→</b><span>Diagnose</span><b>→</b><span>Decide</span><b>→</b><span>Repeat</span></div>
    </section>

    <section class="column-block narrative-block" id="executive-overview">
      <p class="analysis-number">01 / BUSINESS HEALTH</p>
      <h2>Where should leadership focus first?</h2>
      <p>The Executive Overview is the diagnostic entry point. It combines essential health indicators and surfaces exceptions before management opens another report.</p>
      <p>Instead of reviewing every metric, the owner can identify whether the next conversation should focus on revenue, marketing quality, margin protection, or operational simplification.</p>
      <dl class="analysis-result"><dt>Signal surfaced</dt><dd>76% of modeled revenue was concentrated in one category—making concentration the first management priority.</dd></dl>
    </section>

    <section class="column-block narrative-block" id="revenue-assortment">
      <p class="analysis-number">02 / ASSORTMENT</p>
      <h2>What should we protect, expand, or reduce?</h2>
      <p>The assortment analysis connects revenue contribution and gross profit with the effort required to source, size, return, and style each product group.</p>
      <p>This separates products that are merely popular from those that support profitable, operationally manageable growth.</p>
      <dl class="analysis-result"><dt>Action enabled</dt><dd>Test a gradual shift toward higher-profit, lower-effort products instead of making an all-or-nothing category exit.</dd></dl>
    </section>

    <section class="column-block narrative-block" id="marketing-investment">
      <p class="analysis-number">03 / MARKETING</p>
      <h2>Where should the next marketing dollar go?</h2>
      <p>The marketing analysis compares acquisition sources across the funnel and connects channel performance with customer behavior—not traffic volume alone.</p>
      <p>Management can distinguish channels that create purchase intent from those that mainly support discovery, then align each source with the right campaign role.</p>
      <dl class="analysis-result"><dt>Action enabled</dt><dd>Match channels to acquisition, discovery, or retention roles and concentrate effort where purchase intent is strongest.</dd></dl>
    </section>

    <section class="column-block narrative-block" id="relocation-scenario">
      <p class="analysis-number">04 / OPERATIONS</p>
      <h2>When would relocation improve the business?</h2>
      <p>The relocation model makes rent savings, local-customer loss, revenue exposure, and online recapture adjustable instead of presenting one forecast as certainty.</p>
      <p>The owner can test the exact retention and ecommerce conditions required before a move becomes financially defensible.</p>
      <dl class="analysis-result"><dt>Scenario result</dt><dd>In the default model, $60K in rent savings did not offset the estimated revenue risk.</dd></dl>
    </section>
  </div>

  <aside class="visual-column" aria-label="Dashboard evidence">
    <figure class="column-block column-block--hero visual-block browser-frame browser-frame--flat">
      <div class="browser-bar"><i></i><i></i><i></i><span>Executive Overview</span></div>
      <img src="/materials/ecommerce-command-center/executive-overview.png" alt="Executive Overview showing ecommerce KPIs and management priorities">
      <figcaption>One entry point surfaces the priority and routes the next analysis.</figcaption>
    </figure>

    <figure class="column-block visual-block"><img src="/materials/ecommerce-command-center/executive-03-concentration.png" alt="Revenue concentration analysis by category and subcategory"><figcaption><span>01</span> Executive diagnostic · concentration risk</figcaption></figure>

    <figure class="column-block visual-block"><img src="/materials/ecommerce-command-center/revenue-03-profit-effort.png" alt="Profit-to-effort assortment strategy matrix"><figcaption><span>02</span> Assortment strategy · profit-to-effort tradeoff</figcaption></figure>

    <figure class="column-block visual-block"><img src="/materials/ecommerce-command-center/marketing-02-conversion.png" alt="Marketing source conversion comparison"><figcaption><span>03</span> Marketing investment · source conversion quality</figcaption></figure>

    <figure class="column-block visual-block"><img src="/materials/ecommerce-command-center/relocation-02-breakeven.png" alt="Store relocation break-even scenario"><figcaption><span>04</span> Relocation decision · adjustable break-even analysis</figcaption></figure>
  </aside>
</section>

<section class="case-impact-simple">
  <div><p class="analysis-number">APPLIED BUSINESS IMPACT</p><h2>Analysis connected to commercial action.</h2><p>Segmentation-led recommendations were applied in the operating business. The public command center was rebuilt with realistically modeled data.</p></div>
  <p><strong>+43.1%</strong><span>observed year-over-year revenue growth</span></p>
  <p><strong>+49%</strong><span>observed year-over-year online-session growth</span></p>
  <small>Observed outcomes, not a controlled causal estimate.</small>
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
