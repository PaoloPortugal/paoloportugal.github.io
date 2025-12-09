---
layout: page
title: Wumpus World
permalink: /my-games/wumpus-world/
---

<style>
  /* Scoped styles for the Wumpus World page */
  /* Reduce default top spacing on this page so the game sits higher */
  .page-content .wrapper { padding-top: 0.5rem; }
  .game-embed-wrapper {
    /* Fit exactly to the iframe without any extra chrome */
    display: block;
    width: 621px;
    height: 513px;
    padding: 0;
    margin: 0 auto; /* center the game; remove auto if you prefer left-aligned */
    overflow: hidden; /* hide any scrollbars around the game container */
  }
  /* Hide scrollbars across browsers if any would appear on the wrapper */
  .game-embed-wrapper { -ms-overflow-style: none; scrollbar-width: none; }
  .game-embed-wrapper::-webkit-scrollbar { display: none; }
  .game-note { color: var(--text-muted); margin-top: .75rem; }
  </style>

<div class="game-embed-wrapper">
  <iframe src="https://www.lexaloffle.com/bbs/widget.php?pid=wumpusworld" allowfullscreen scrolling="no" width="621" height="513" style="border:none; overflow:hidden; display:block;"></iframe>
</div>
