---
layout: page
title: Dont Grow!
permalink: /my-games/dont-grow/
---

<style>
  /* Scoped styles for the Dont Grow! page */
  /* Reduce default top spacing on this page so the game sits higher */
  .page-content .wrapper { padding-top: 0.5rem; }
  .game-embed-wrapper {
    /* Fit cleanly to the iframe with responsive scaling */
    display: block;
    width: 100%;
    max-width: 1280px;
    aspect-ratio: 1280 / 740;
    padding: 0;
    margin: 0 auto; /* center the game; remove auto if you prefer left-aligned */
    overflow: hidden; /* hide any scrollbars around the game container */
  }
  .game-embed-wrapper iframe {
    width: 100%;
    height: 100%;
    border: none;
    display: block;
  }
  /* Hide scrollbars across browsers if any would appear on the wrapper */
  .game-embed-wrapper { -ms-overflow-style: none; scrollbar-width: none; }
  .game-embed-wrapper::-webkit-scrollbar { display: none; }
  .game-note { color: var(--text-muted); margin-top: .75rem; }
</style>

<div class="game-embed-wrapper">
    <iframe
        frameborder="0"
        src="https://itch.io/embed-upload/16256347?color=327345"
        allow="autoplay; fullscreen"
        width="1280"
        height="740">
        <a href="https://moofys.itch.io/dont-grow">Play Dont Grow! on itch.io</a>
    </iframe>
</div>
