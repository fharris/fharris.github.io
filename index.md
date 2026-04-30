---
layout: default
title: Home
---

<style>
  .hero {
    background: linear-gradient(135deg, #0f172a 0%, #1d4ed8 60%, #38bdf8 100%);
    color: #fff;
    padding: 4rem 2rem;
    border-radius: 18px;
    box-shadow: 0 18px 45px rgba(15, 23, 42, 0.25);
    margin: 1.5rem 0 2rem;
  }

  .hero h1 {
    margin: 0 0 .75rem;
    font-size: 2.4rem;
    line-height: 1.15;
    letter-spacing: -0.02em;
  }

  .hero p {
    margin: 0;
    font-size: 1.08rem;
    max-width: 60ch;
    opacity: 0.95;
  }

  .cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1rem;
    margin: 2rem 0;
  }

  .card {
    background: #ffffff;
    border: 1px solid #e5e7eb;
    border-radius: 14px;
    padding: 1.1rem;
    box-shadow: 0 8px 20px rgba(2, 6, 23, 0.07);
  }

  .card h3 {
    margin-top: 0;
    margin-bottom: .5rem;
    color: #0f172a;
  }

  .card p {
    margin: 0;
    color: #334155;
  }

  .cta {
    background: #f8fafc;
    border: 1px solid #e2e8f0;
    border-radius: 14px;
    padding: 1.25rem;
    margin-top: 1.5rem;
  }

  .cta a {
    display: inline-block;
    margin-top: .75rem;
    background: #2563eb;
    color: #fff;
    text-decoration: none;
    padding: .65rem 1rem;
    border-radius: 10px;
    font-weight: 600;
  }

  .cta a:hover {
    background: #1d4ed8;
  }
</style>

<section class="hero">
  <h1>Hi, I’m Fran 👋</h1>
  <p>
    Welcome to my GitHub Pages site. I’ve refreshed the design with a modern hero section,
    cleaner cards, and stronger visual hierarchy to make the homepage feel more polished.
  </p>
</section>

<section class="cards">
  <article class="card">
    <h3>Modern UI</h3>
    <p>Gradient hero, soft shadows, and rounded corners for a contemporary aesthetic.</p>
  </article>
  <article class="card">
    <h3>Better Readability</h3>
    <p>Improved spacing, clearer typography, and concise content blocks.</p>
  </article>
  <article class="card">
    <h3>Responsive Layout</h3>
    <p>Cards adapt automatically across desktop and mobile screen sizes.</p>
  </article>
</section>

<section class="cta">
  <strong>Want to keep customizing?</strong>
  <p style="margin: .5rem 0 0;">
    Edit <code>index.md</code> to update sections and colors, or change theme settings in <code>_config.yml</code>.
  </p>
  <a href="https://github.com" target="_blank" rel="noopener noreferrer">Open GitHub</a>
</section>
