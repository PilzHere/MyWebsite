---
title: "Play SteamBoy DIG"
date: 2021-08-02T00:15:17+02:00
draft: false
weight: 3
# aliases: ["/first"]
tags: [""]
author: "PilzHere"
hidden: true
showToc: false
TocOpen: false
draft: false
hidemeta: false
comments: true
description: ""
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true

cover:
    image: ""
    alt: "<alt text>"
    caption: "<text>"
    relative: false # when using page bundles set this to true
    hidden: false # only hide on current single page

editPost:
    URL: "mailto:pilzhere.net@gmail.com?subject=Suggesting changes for "
    #Text: "Suggest changes"
    #appendFilePath: true # to append file path to Edit link
---

{{< rawhtml >}}
<div class="game-container">
  <div id="embed-html"></div>
</div>

<script src="soundmanager2-setup.js"></script>
<script src="soundmanager2-jsmin.js"></script>
<script type="text/javascript" src="html/html.nocache.js"></script>

<script>
  const gameArea = document.getElementById("embed-html");

  window.addEventListener("keydown", function(e) {
    const keysToBlock = ["ArrowUp", "ArrowDown", "ArrowLeft", "ArrowRight", " ", "W", "A", "S", "D"];
    const isGameFocused = document.activeElement === document.body || gameArea.contains(document.activeElement);

    if (isGameFocused && keysToBlock.includes(e.key)) {
      e.preventDefault();
    }
  }, { passive: false });
</script>

<style>
html, body {
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
}

.game-container {
  display: flex;
  justify-content: center; /* Center the game horizontally */
  align-items: center;     /* Center the game vertically */
  width: 100%;
  height: 100%;
  position: relative;
  overflow: hidden; /* Ensure no scrollbars */
  
}

#embed-html {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden; /* Hide any overflow */
  position: relative;
}

table {
  width: 100% !important;
  height: 100% !important;
  overflow: hidden; /* Prevent scrollbars */
  border-collapse: collapse; /* Removes extra spacing */
}

canvas {
  max-width: 100%;
  max-height: 100%; /* Adjust height to viewport */
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  object-fit: cover; /* Cover the area without distortion */
  display: block;
}
</style>

<script>
  function handleMouseDown(evt) {
    evt.preventDefault();
    evt.stopPropagation();
    evt.target.style.cursor = 'default';
    window.focus();
  }

  function handleMouseUp(evt) {
    evt.preventDefault();
    evt.stopPropagation();
    evt.target.style.cursor = '';
  }

  document.getElementById('embed-html').addEventListener('mousedown', handleMouseDown, false);
  document.getElementById('embed-html').addEventListener('mouseup', handleMouseUp, false);
</script>
{{< /rawhtml >}}
