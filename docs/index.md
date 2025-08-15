---
description: Enkiria pixelmon server's wiki.
title: Home
hide:
  - navigation
  - toc
  - title
---

!!! tip
    This wiki is best enjoyed on PC, but is still functional on mobile.
    

![Enkiria logo](logo.png){width=350; align=left}

<div markdown >
<h2 style="color:DarkViolet">Welcome to the Enkiria Region</h2>

A land where mythology, minerals, and modern marvels converge.

Step into Enkiria, a vibrant and mysterious region forged in the heart of legend and stone. From high-tech cities built atop ancient ruins to deep caverns glowing with mystical gems, Enkiria is a land where the past and future intertwine — and where Pokémon are more than just companions; they are woven into the very fabric of the world.

Trainers who journey here will uncover forgotten myths, **_encounter unique regional forms_**, and face challenges shaped by Enkiria's rich lore and rugged beauty. Whether you're researching arcane relics, battling in high-tech arenas, or exploring crystal-lined mountains, the region offers a truly immersive roleplay experience unlike any other.

_Forge your story. Uncover the truth. Welcome to Enkiria._

</div>

</br>


<div id="video-playlist-container" style="text-align:center;" markdown>
## Trailers

<iframe id="playlistIframe" width="1120" height="630" class="radiusImg5"
    style="max-width:100%;"
    src="https://www.youtube.com/embed/videoseries?enablejsapi=1&mute=1&si=nC4Cp4oaMWr1FAAG&list=PLwHbMn91xq3V-uFNL1JNSEAOAGcU9v4gt&autoplay=1&loop=1&playlist=PLwHbMn91xq3V-uFNL1JNSEAOAGcU9v4gt&controls=0"
    title="YouTube video player"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    referrerpolicy="strict-origin-when-cross-origin"
    allowfullscreen>
</iframe>
<button id="muteBtn" class="mute-btn" onclick="toggleMute()">🔇 Unmute</button>
</div>

<style>
.mute-btn {
  margin-top:10px;
  font-size:1.2rem;
  padding: 0.5em 1.5em;
  border: 2px solid #8a2be2;
  border-radius: 8px;
  background: linear-gradient(90deg,#e0d6ff 0%,#c7b6ff 100%);
  color: #4b0082;
  cursor: pointer;
  transition: background 0.2s, color 0.2s, box-shadow 0.2s;
  box-shadow: 0 2px 8px rgba(138,43,226,0.08);
}
.mute-btn:hover {
  background: #d1c4e9;
  color: #2e0854;
}
</style>
<script>
  let muted = true; // playlist démarrera en mute
  toggleMute = () => {
    const muteBtn = document.getElementById('muteBtn');
    const iframe = document.getElementById('playlistIframe');
    if (iframe) {
      iframe.contentWindow.postMessage(JSON.stringify({
        event: 'command',
        func: muted ? 'unMute' : 'mute',
        args: []
      }), '*');
      muted = !muted;
      muteBtn.textContent = muted ? '🔇 Unmute' : '🔊 Mute';
    }
  };
</script>

!!! bug "Preview"
    Some trailers were made before the opening of the server. Some visuals can be outdated or inaccurate.

</br>

<div markdown class="outer">
<figure markdown class="img1 embed news">
  ![Spawn](spawn.png){.radiusImg15 width=1120}
  <figcaption>Spawn</figcaption>
</figure>
</div>

## Useful links

[Discord :simple-discord:](https://discord.gg/RUjgy7wKXr){: .md-button .md-button--primary target="_blank"}
[Pixelmon Wiki :material-pokeball:](https://pixelmonmod.com/wiki/Main_Page){: .md-button .md-button--primary target="_blank"}
[Curse Forge :simple-curseforge:](https://www.curseforge.com/download/app){: .md-button .md-button--primary target="_blank"}

</br>

<span style="font-size:1.5rem">:material-server: enkiriapixelmon.mine.fun</span>