---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: page
title: Home
permalink: /
---

<style>
  /* Scoped styles for the landing page */
  .landing-wrapper {
    position: relative;
    min-height: calc(100vh - 8rem); /* account for header/footer padding in Minima */
    display: grid;
    align-items: center;
  }
  .landing-hero {
    display: grid;
    grid-template-columns: 1.2fr 0.8fr;
    gap: 2rem;
    align-items: center;
  }
  .landing-title {
    font-size: clamp(2.6rem, 7vw, 5rem);
    font-weight: 900;
    line-height: 1.05;
    margin: 0 0 .5rem 0;
  }
  .landing-aka {
    font-size: clamp(1rem, 2.4vw, 1.25rem);
    color: var(--text-muted);
    margin: 0 0 1rem 0;
  }
  .landing-logo {
    justify-self: end;
    max-width: min(260px, 35vw);
    opacity: 0.95;
    filter: drop-shadow(0 10px 24px rgba(0,0,0,0.12));
  }

  @media (max-width: 860px) {
    .landing-hero { grid-template-columns: 1fr; }
    .landing-logo { justify-self: start; margin-top: .5rem; }
  }
</style>

<div class="landing-wrapper">
  <div class="landing-hero">
    <div>
      <h1 class="landing-title">Paolo Portugal</h1>
      <p class="landing-aka">AKA: moofys</p>
    </div>

    <!-- Logo on the right of the name -->
    <img class="landing-logo" src="assets/pictures/me/logo.svg" alt="Site logo" />
  </div>
</div>
