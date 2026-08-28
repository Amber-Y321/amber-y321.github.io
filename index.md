---
layout: single
title: ""
permalink: /
author_profile: true
classes: wide
---

<section class="portfolio-hero">
  <h1>Analytics for clearer commercial and operational decisions.</h1>
  <p class="hero-summary">Hi, I'm Yahan. With 5 years of experience across ecommerce and healthcare, I turn recurring questions and fragmented data into priorities leaders can act on.</p>
  <a class="hero-text-link" href="#selected-work">View featured work <span>↓</span></a>
</section>

<section class="project-feature" id="selected-work">
  <div class="project-feature__copy">
    <p class="feature-label"><span>01</span> FEATURED CASE STUDY</p>
    <h2>Ecommerce Analytics<br>Command Center</h2>
    <p class="feature-statement">A repeatable management workflow that makes it easier to spot what changed, find the cause, and decide what to do next.</p>
    <div class="feature-actions">
      <a class="button button--light" href="/projects/ecommerce-command-center/">View the 90-second case</a>
      <a class="feature-link" href="https://ecommerceanalytics-mdjdkr9yopuaqjaddvujmg.streamlit.app/" target="_blank" rel="noopener">Open live dashboard ↗</a>
    </div>
  </div>

  <div class="project-feature__visual">
    <div class="feature-dashboard-grid feature-dashboard-grid--autoplay" role="region" aria-label="Command center analysis views rotating every two seconds" tabindex="0">
      <figure class="feature-dashboard-card feature-dashboard-card--overview">
        <img src="/materials/ecommerce-command-center/Overview.png" alt="Executive Overview showing ecommerce KPIs and operating priorities">
        <figcaption>Overview</figcaption>
      </figure>
      <figure class="feature-dashboard-card">
        <img src="/materials/ecommerce-command-center/executive-04-alerts.png" alt="Sessions, conversion, and return-rate monitoring" loading="lazy">
        <figcaption>Sessions</figcaption>
      </figure>
      <figure class="feature-dashboard-card">
        <img src="/materials/ecommerce-command-center/revenue-03-profit-effort.png" alt="Profit-to-effort assortment tradeoff analysis" loading="lazy">
        <figcaption>Tradeoff</figcaption>
      </figure>
      <figure class="feature-dashboard-card">
        <img src="/materials/ecommerce-command-center/marketing-03-ai-support.png" alt="Customer segmentation for campaign planning" loading="lazy">
        <figcaption>Segmentation</figcaption>
      </figure>
      <figure class="feature-dashboard-card">
        <img src="/materials/ecommerce-command-center/relocation-scenario.png" alt="Store relocation break-even scenario" loading="lazy">
        <figcaption>Scenario</figcaption>
      </figure>
    </div>
  </div>

  <div class="process-ribbon" aria-label="Decision workflow">
    <div><span>01</span><strong>Detect</strong><small>Surface the exception</small></div>
    <div><span>02</span><strong>Diagnose</strong><small>Trace the driver</small></div>
    <div><span>03</span><strong>Decide</strong><small>Compare the action</small></div>
    <div><span>04</span><strong>Repeat</strong><small>Reuse next cycle</small></div>
  </div>
</section>

<section class="proof-strip" aria-label="Project proof">
  <div><strong>4</strong><span>management decisions<br>in one operating view</span></div>
  <div><strong>+43.1%</strong><span>observed YoY<br>revenue growth</span></div>
  <div><strong>+49%</strong><span>observed YoY<br>online-session growth</span></div>
  <p>Dashboard findings use realistically modeled data. Commercial outcomes come from the applied engagement.</p>
</section>

<section class="contact-band" id="contact">
  <p class="contact-label">CONTACT</p>
  <h2>Let's connect.</h2>
  <p>For analytics opportunities and project conversations: <a href="mailto:yangyahan0321@gmail.com">yangyahan0321@gmail.com</a> · <a href="https://github.com/amber-y321">GitHub</a></p>
</section>

<script>
  (() => {
    const initializeCarousel = () => {
      const carousel = document.querySelector('.feature-dashboard-grid--autoplay');
      if (!carousel) return;

      const slides = Array.from(carousel.querySelectorAll('.feature-dashboard-card'));
      if (slides.length < 2) return;

      let currentIndex = 0;
      let intervalId;
      let scrollUpdateId;

      const stop = () => {
        if (intervalId) window.clearInterval(intervalId);
        intervalId = undefined;
      };

      const show = (index) => {
        currentIndex = (index + slides.length) % slides.length;
        carousel.scrollTo({ left: slides[currentIndex].offsetLeft, behavior: 'smooth' });
      };

      const start = () => {
        stop();
        intervalId = window.setInterval(() => show(currentIndex + 1), 2000);
      };

      carousel.addEventListener('mouseenter', stop);
      carousel.addEventListener('mouseleave', start);
      carousel.addEventListener('focusin', stop);
      carousel.addEventListener('focusout', (event) => {
        if (!carousel.contains(event.relatedTarget)) start();
      });
      carousel.addEventListener('scroll', () => {
        window.clearTimeout(scrollUpdateId);
        scrollUpdateId = window.setTimeout(() => {
          currentIndex = slides.reduce((closest, slide, index) => {
            const currentDistance = Math.abs(slides[closest].offsetLeft - carousel.scrollLeft);
            const nextDistance = Math.abs(slide.offsetLeft - carousel.scrollLeft);
            return nextDistance < currentDistance ? index : closest;
          }, 0);
        }, 120);
      }, { passive: true });
      document.addEventListener('visibilitychange', () => {
        if (document.hidden) stop();
        else if (!carousel.matches(':hover')) start();
      });

      show(0);
      start();
    };

    if (document.readyState === 'loading') {
      document.addEventListener('DOMContentLoaded', initializeCarousel, { once: true });
    } else {
      initializeCarousel();
    }
  })();
</script>
