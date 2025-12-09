---
layout: page
title: About
permalink: /about/
---

<style>
  /* Scoped styles for the About page */
  .about-hero {
    display: grid;
    grid-template-columns: 1fr auto;
    gap: 2rem;
    align-items: center;
    margin-bottom: 2rem;
  }
  .about-name {
    font-size: clamp(2.2rem, 6vw, 4rem);
    font-weight: 800;
    line-height: 1.1;
    margin: 0;
  }
  .about-photo {
    width: min(220px, 35vw);
    height: min(220px, 35vw);
    border-radius: 16px;
    object-fit: cover;
    box-shadow: 0 10px 24px rgba(0,0,0,0.15);
  }
  .about-subtitle {
    color: var(--text-muted);
    font-size: 1rem;
    margin-top: .25rem;
  }
  .about-section {
    margin-top: 2.5rem;
  }
  .resume-title {
    font-size: clamp(1.4rem, 3vw, 2rem);
    font-weight: 700;
    margin-bottom: 1rem;
    border-bottom: 2px solid var(--border-strong);
    padding-bottom: .5rem;
  }
  .resume-list {
    list-style: none;
    padding: 0;
    margin: 0;
    display: grid;
    gap: .75rem 1.25rem;
  }
  .resume-item {
    display: flex;
    gap: .75rem;
  }
  .resume-item .dot {
    width: 8px;
    height: 8px;
    margin-top: .5rem;
    border-radius: 50%;
    background: var(--accent);
    flex: 0 0 8px;
  }
  @media (max-width: 680px) {
    .about-hero { grid-template-columns: 1fr; }
    .about-photo { justify-self: start; }
  }
</style>

<div class="about-hero">
  <div>
    <h1 class="about-name">Paolo Portugal</h1>
    <p class="about-subtitle">Engineering student • Game developer</p>
  </div>
  <img
    class="about-photo"
    src="{{ site.author.photo | default: '/assets/icon.svg' }}"
    alt="Photo of {{ site.title }}"
  />
  
</div>

<div class="about-section">
  <p></p>
  
</div>

<div class="about-section">
  <h2 class="resume-title">Resume</h2>
  <ul class="resume-list">
    <li class="resume-item">
      <span class="dot"></span>
      <div>Born December 12, 2005.</div>
    </li>
    <li class="resume-item">
      <span class="dot"></span>
      <div>Bachelor’s degree in Computer Engineering — 2024–Present.</div>
    </li>
  </ul>
</div>
