---
layout: single
title: "Business & Ecommerce Analytics"
permalink: /
author_profile: true
---

<style>
  /* ---------- Homepage foundations ---------- */

  .portfolio-home {
    --portfolio-navy: #17324d;
    --portfolio-accent: #176b68;
    --portfolio-text: #263238;
    --portfolio-muted: #64727d;
    --portfolio-border: #dce4e8;
    --portfolio-surface: #f4f7f8;
    --portfolio-white: #ffffff;
    color: var(--portfolio-text);
  }

  .portfolio-home *,
  .portfolio-home *::before,
  .portfolio-home *::after {
    box-sizing: border-box;
  }

  .portfolio-home section {
    margin: 0;
    padding: 3.5rem 0;
    border-bottom: 1px solid var(--portfolio-border);
  }

  .portfolio-home section:last-child {
    border-bottom: 0;
  }

  .portfolio-eyebrow {
    margin: 0 0 0.75rem;
    color: var(--portfolio-accent);
    font-size: 0.75rem;
    font-weight: 700;
    letter-spacing: 0.12em;
    line-height: 1.4;
    text-transform: uppercase;
  }

  .portfolio-home h1,
  .portfolio-home h2,
  .portfolio-home h3 {
    color: var(--portfolio-navy);
  }

  .portfolio-home h1 {
    max-width: 850px;
    margin: 0;
    font-size: clamp(2rem, 5vw, 3.75rem);
    line-height: 1.08;
  }

  .portfolio-home h2 {
    margin: 0;
    font-size: clamp(1.7rem, 3vw, 2.5rem);
    line-height: 1.15;
  }

  .portfolio-home h3 {
    margin-top: 0;
    font-size: 1.1rem;
  }

  .portfolio-lead {
    max-width: 760px;
    margin: 1.25rem 0 0;
    color: var(--portfolio-muted);
    font-size: 1.1rem;
    line-height: 1.7;
  }

  /* ---------- Buttons ---------- */

  .portfolio-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 0.8rem;
    margin-top: 1.75rem;
  }

  .portfolio-button {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    min-height: 46px;
    padding: 0.7rem 1.1rem;
    border: 1px solid var(--portfolio-navy);
    border-radius: 5px;
    font-size: 0.9rem;
    font-weight: 700;
    line-height: 1.2;
    text-decoration: none !important;
    transition:
      background-color 150ms ease,
      color 150ms ease,
      transform 150ms ease;
  }

  .portfolio-button:hover {
    transform: translateY(-1px);
  }

  .portfolio-button--primary {
    background: var(--portfolio-navy);
    color: var(--portfolio-white) !important;
  }

  .portfolio-button--primary:hover {
    background: #0f2539;
  }

  .portfolio-button--secondary {
    background: transparent;
    color: var(--portfolio-navy) !important;
  }

  .portfolio-button--secondary:hover {
    background: var(--portfolio-surface);
  }

  /* ---------- Featured case study ---------- */

  .case-study-intro {
    display: grid;
    grid-template-columns: minmax(0, 1.5fr) minmax(220px, 0.7fr);
    gap: 2rem;
    align-items: end;
  }

  .case-study-summary {
    margin: 1rem 0 0;
    max-width: 720px;
    color: var(--portfolio-muted);
    line-height: 1.7;
  }

  .case-study-role {
    margin: 0;
    padding: 1rem 1.1rem;
    border-left: 3px solid var(--portfolio-accent);
    background: var(--portfolio-surface);
    color: var(--portfolio-muted);
    font-size: 0.9rem;
    line-height: 1.6;
  }

  .case-study-role strong {
    color: var(--portfolio-navy);
  }

  /* ---------- Metrics ---------- */

  .metric-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 1rem;
    margin: 2rem 0 0;
  }

  .metric-card {
    min-height: 130px;
    padding: 1.25rem;
    border: 1px solid var(--portfolio-border);
    border-radius: 7px;
    background: var(--portfolio-white);
  }

  .metric-value {
    display: block;
    margin-bottom: 0.3rem;
    color: var(--portfolio-navy);
    font-size: clamp(1.8rem, 4vw, 2.7rem);
    font-weight: 750;
    line-height: 1;
  }

  .metric-label {
    color: var(--portfolio-muted);
    font-size: 0.88rem;
    line-height: 1.45;
  }

  .metric-note {
    margin: 0.85rem 0 0;
    color: var(--portfolio-muted);
    font-size: 0.76rem;
    line-height: 1.5;
  }

  /* ---------- Dashboard preview ---------- */

  .dashboard-preview {
    margin: 2rem 0 0;
  }

  .dashboard-frame {
    overflow: hidden;
    border: 1px solid var(--portfolio-border);
    border-radius: 8px;
    background: var(--portfolio-white);
    box-shadow: 0 14px 35px rgba(23, 50, 77, 0.1);
  }

  .dashboard-frame img {
    display: block;
    width: 100%;
    height: auto;
    margin: 0;
  }

  .dashboard-preview figcaption {
    margin-top: 0.75rem;
    color: var(--portfolio-muted);
    font-size: 0.78rem;
    line-height: 1.5;
    text-align: center;
  }

  /* ---------- Decision areas ---------- */

  .decision-grid {
    display: grid;
    grid-template-columns: repeat(4, minmax(0, 1fr));
    gap: 0.8rem;
    margin-top: 1.5rem;
  }

  .decision-card {
    padding: 1rem;
    border-top: 3px solid var(--portfolio-accent);
    background: var(--portfolio-surface);
  }

  .decision-number {
    display: block;
    margin-bottom: 0.35rem;
    color: var(--portfolio-accent);
    font-size: 0.7rem;
    font-weight: 700;
    letter-spacing: 0.08em;
  }

  .decision-title {
    display: block;
    color: var(--portfolio-navy);
    font-size: 0.88rem;
    font-weight: 700;
    line-height: 1.4;
  }

  /* ---------- Capabilities ---------- */

  .capability-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 1rem;
    margin-top: 1.75rem;
  }

  .capability-card {
    padding: 1.4rem;
    border: 1px solid var(--portfolio-border);
    border-radius: 7px;
    background: var(--portfolio-white);
  }

  .capability-card ul {
    margin: 0;
    padding-left: 1.1rem;
    color: var(--portfolio-muted);
    font-size: 0.88rem;
    line-height: 1.7;
  }

  /* ---------- Additional work ---------- */

  .project-card {
    display: grid;
    grid-template-columns: minmax(0, 1fr) auto;
    gap: 1.5rem;
    align-items: center;
    margin-top: 1.5rem;
    padding: 1.4rem;
    border: 1px solid var(--portfolio-border);
    border-radius: 7px;
  }

  .project-card h3 {
    margin-bottom: 0.5rem;
  }

  .project-card p {
    margin: 0;
    color: var(--portfolio-muted);
    font-size: 0.9rem;
    line-height: 1.65;
  }

  .project-link {
    white-space: nowrap;
    color: var(--portfolio-accent) !important;
    font-size: 0.88rem;
    font-weight: 700;
  }

  /* ---------- Contact ---------- */

  .contact-section {
    padding-bottom: 1rem !important;
  }

  .contact-panel {
    padding: 2rem;
    border-radius: 8px;
    background: var(--portfolio-navy);
    color: var(--portfolio-white);
  }

  .contact-panel h2 {
    color: var(--portfolio-white);
  }

  .contact-panel p {
    max-width: 650px;
    margin: 0.8rem 0 0;
    color: #d9e5ed;
    line-height: 1.7;
  }

  .contact-panel .portfolio-button--primary {
    border-color: var(--portfolio-white);
    background: var(--portfolio-white);
    color: var(--portfolio-navy) !important;
  }

  .contact-panel .portfolio-button--secondary {
    border-color: #b7c9d5;
    color: var(--portfolio-white) !important;
  }

  .contact-panel .portfolio-button--secondary:hover {
    background: rgba(255, 255, 255, 0.1);
  }

  /* ---------- Responsive layout ---------- */

  @media (max-width: 900px) {
    .decision-grid {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }

    .capability-grid {
      grid-template-columns: 1fr;
    }
  }

  @media (max-width: 650px) {
    .portfolio-home section {
      padding: 2.5rem 0;
    }

    .case-study-intro,
    .project-card {
      grid-template-columns: 1fr;
    }

    .metric-grid {
      gap: 0.5rem;
    }

    .metric-card {
      min-height: 105px;
      padding: 0.85rem;
    }

    .metric-value {
      font-size: 1.65rem;
    }

    .metric-label {
      font-size: 0.72rem;
    }

    .decision-grid {
      grid-template-columns: 1fr;
    }

    .portfolio-actions {
      flex-direction: column;
    }

    .portfolio-button {
      width: 100%;
    }

    .contact-panel {
      padding: 1.4rem;
    }
  }
</style>

<div class="portfolio-home">

  <!-- ======================================================
       HERO
       ====================================================== -->

  <section class="portfolio-hero" aria-labelledby="portfolio-title">
    <p class="portfolio-eyebrow">Business &amp; Ecommerce Analytics</p>

    <h1 id="portfolio-title">
      Turning commercial data into clearer business decisions.
    </h1>

    <p class="portfolio-lead">
      I analyze customer behavior, revenue performance, product assortment,
      marketing efficiency, and operational scenarios to help teams decide
      where to focus next.
    </p>

    <div class="portfolio-actions">
      <a
        class="portfolio-button portfolio-button--primary"
        href="/projects/ecommerce-command-center/"
      >
        View Featured Case Study
      </a>

      <a
        class="portfolio-button portfolio-button--secondary"
        href="/materials/Resume%20of%20Yahan_2025.pdf"
        target="_blank"
        rel="noopener"
      >
        Download Résumé
      </a>
    </div>
  </section>

  <!-- ======================================================
       FEATURED CASE STUDY
       ====================================================== -->

  <section id="selected-work" aria-labelledby="case-study-title">
    <div class="case-study-intro">
      <div>
        <p class="portfolio-eyebrow">Selected Case Study</p>

        <h2 id="case-study-title">
          Ecommerce Analytics Command Center
        </h2>

        <p class="case-study-summary">
          A decision-support system created for a boutique retailer balancing
          ecommerce growth, product strategy, marketing investment, and a
          potential store relocation.
        </p>
      </div>

      <p class="case-study-role">
        <strong>Role:</strong> Data Consultant<br>
        <strong>Focus:</strong> Commercial and operational analytics
      </p>
    </div>

    <!-- Replace or revise the figures if your final validated metrics differ. -->

    <div class="metric-grid" aria-label="Selected project results">
      <div class="metric-card">
        <span class="metric-value">+43.1%</span>
        <span class="metric-label">Year-over-year revenue lift</span>
      </div>

      <div class="metric-card">
        <span class="metric-value">+49%</span>
        <span class="metric-label">Growth in online sessions</span>
      </div>

      <div class="metric-card">
        <span class="metric-value">4</span>
        <span class="metric-label">Decision-focused analytical views</span>
      </div>
    </div>

    <p class="metric-note">
      Revenue and session results were observed during the period following
      the segmentation-led marketing strategy. They are presented as
      directional business outcomes rather than a controlled causal estimate.
    </p>

    <figure class="dashboard-preview">
      <div class="dashboard-frame">
        <!--
          TODO:
          Replace this source with the final Command Center hero screenshot.

          Suggested future path:
          /materials/ecommerce-command-center/hero.webp

          The existing GIF is used temporarily so the page renders immediately.
        -->
        <img
          src="/materials/GIF_Dashboard.gif"
          alt="Ecommerce analytics dashboard showing executive performance, revenue trends, and customer insights"
        >
      </div>

      <figcaption>
        A unified view of commercial performance, customer behavior, product
        strategy, marketing investment, and operational scenarios.
      </figcaption>
    </figure>

    <div class="decision-grid" aria-label="Dashboard decision areas">
      <div class="decision-card">
        <span class="decision-number">01</span>
        <span class="decision-title">Executive Overview</span>
      </div>

      <div class="decision-card">
        <span class="decision-number">02</span>
        <span class="decision-title">Revenue &amp; Assortment</span>
      </div>

      <div class="decision-card">
        <span class="decision-number">03</span>
        <span class="decision-title">Marketing Investment</span>
      </div>

      <div class="decision-card">
        <span class="decision-number">04</span>
        <span class="decision-title">Store Relocation</span>
      </div>
    </div>

    <div class="portfolio-actions">
      <a
        class="portfolio-button portfolio-button--primary"
        href="/projects/ecommerce-command-center/"
      >
        Read Full Case Study
      </a>

      <!-- TODO: Replace with the final dashboard URL if one exists. -->
      <a
        class="portfolio-button portfolio-button--secondary"
        href="https://github.com/amber-y321/Customer_Behavior_Dashboard"
        target="_blank"
        rel="noopener"
      >
        View Technical Repository
      </a>
    </div>
  </section>

  <!-- ======================================================
       CORE CAPABILITIES
       ====================================================== -->

  <section aria-labelledby="capabilities-title">
    <p class="portfolio-eyebrow">Core Capabilities</p>

    <h2 id="capabilities-title">
      Analysis designed around decisions—not just deliverables.
    </h2>

    <div class="capability-grid">
      <article class="capability-card">
        <h3>Business Analysis</h3>
        <ul>
          <li>Business-question framing</li>
          <li>KPI and reporting design</li>
          <li>Root-cause analysis</li>
          <li>Stakeholder-ready recommendations</li>
        </ul>
      </article>

      <article class="capability-card">
        <h3>Commercial Analytics</h3>
        <ul>
          <li>Revenue-driver analysis</li>
          <li>Customer segmentation</li>
          <li>Product and assortment analysis</li>
          <li>Marketing performance measurement</li>
        </ul>
      </article>

      <article class="capability-card">
        <h3>Decision-Support Systems</h3>
        <ul>
          <li>Executive dashboards</li>
          <li>Scenario analysis</li>
          <li>Automated reporting workflows</li>
          <li>Python, SQL, Streamlit, and Tableau</li>
        </ul>
      </article>
    </div>
  </section>

  <!-- ======================================================
       ADDITIONAL WORK
       ====================================================== -->

  <section aria-labelledby="additional-work-title">
    <p class="portfolio-eyebrow">Additional Work</p>

    <h2 id="additional-work-title">
      Analytical problem-solving across industries.
    </h2>

    <article class="project-card">
      <div>
        <h3>Healthcare Operations Simulation</h3>

        <p>
          Modeled emergency-department demand and capacity constraints to
          evaluate healthcare resource-allocation scenarios.
        </p>
      </div>

      <a
        class="project-link"
        href="https://github.com/amber-y321/Hospitalization-simulation"
        target="_blank"
        rel="noopener"
      >
        View project →
      </a>
    </article>
  </section>

  <!-- ======================================================
       CONTACT
       ====================================================== -->

  <section class="contact-section" aria-labelledby="contact-title">
    <div class="contact-panel">
      <p class="portfolio-eyebrow" style="color:#8fd2ce;">
        Let’s Connect
      </p>

      <h2 id="contact-title">
        Looking for an analyst who connects data to action?
      </h2>

      <p>
        I’m interested in Business Analyst, Ecommerce Analyst, Operations
        Analyst, and Analytics opportunities where clear thinking and
        practical recommendations matter.
      </p>

      <div class="portfolio-actions">
        <a
          class="portfolio-button portfolio-button--primary"
          href="mailto:yangyahan0321@gmail.com"
        >
          Email Me
        </a>

        <!-- TODO: Replace with your LinkedIn profile URL. -->
        <a
          class="portfolio-button portfolio-button--secondary"
          href="https://www.linkedin.com/"
          target="_blank"
          rel="noopener"
        >
          LinkedIn
        </a>

        <a
          class="portfolio-button portfolio-button--secondary"
          href="https://github.com/amber-y321"
          target="_blank"
          rel="noopener"
        >
          GitHub
        </a>
      </div>
    </div>
  </section>

</div>
