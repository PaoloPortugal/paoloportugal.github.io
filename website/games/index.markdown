---
layout: page
title: My Games
permalink: /my-games/
---

<style>
  /* Scoped styles for the My Games page (Pico‑8 section) */
  .section {
    margin: 0 0 2rem 0;
  }
  .section-title {
    font-size: clamp(1.25rem, 3vw, 1.75rem);
    font-weight: 800;
    margin: 0 0 1rem 0;
    position: relative;
  }
  .section-title::after {
    content: "";
    position: absolute;
    left: 0; bottom: -6px;
    width: clamp(72px, 18vw, 180px);
    height: 6px;
    border-radius: 999px;
    background: linear-gradient(90deg, var(--accent), transparent);
    opacity: .85;
  }
  .games-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
    gap: 1rem;
  }
  .game-link {
    display: block;
    text-decoration: none;
    color: var(--text);
  }
  .game-card {
    position: relative;
    overflow: hidden;
    border-radius: 14px;
    background: var(--surface);
    border: 1px solid var(--border);
    transition: transform .16s ease, box-shadow .16s ease, border-color .16s ease;
  }
  .game-card:hover {
    transform: translateY(-2px);
    box-shadow: 0 12px 28px rgba(0,0,0,0.45);
    border-color: var(--border-strong);
  }
  .game-thumb {
    display: block;
    width: 100%;
    height: auto; /* let the image define the height */
    background: #0b0b0b;
  }
  .game-body {
    position: static; /* separate area under the image */
    padding: .6rem .8rem;
    background: var(--surface);
    border-top: 1px solid var(--border);
  }
  .game-title { font-weight: 800; margin: 0; color: #ffffff; }
  .game-link:hover .game-title { color: #ffffff; }
</style>

<section class="section">
  <h2 class="section-title">Pico‑8</h2>
  <div class="games-grid">
    <a class="game-link" href="/my-games/wumpus-world/" aria-label="Open Wumpus World">
      <article class="game-card">
        <img class="game-thumb" src="/website/assets/pictures/games/thumbnails/wumpus-world.p8.png" alt="Wumpus World thumbnail" />
        <div class="game-body">
          <h3 class="game-title">Wumpus World</h3>
        </div>
      </article>
    </a>
  </div>
  
</section>
