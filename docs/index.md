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






<div id="video-playlist-container" markdown style="text-align:center;">
## Trailers
<!-- Remplacement du lecteur vidéo par un iframe YouTube -->
  <iframe
    id="playlistIframe"
    width="1120"
    height="630"
    class="radiusImg5"
    style="max-width:100%;"
    src=""
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
  ></iframe>
</div>
<script>
const playlist = [
  "https://www.youtube.com/embed/M0yKRFDd3WA?enablejsapi=1&autoplay=1&mute=1",
  "https://www.youtube.com/embed/fC7oUOUEEi4?enablejsapi=1&autoplay=1&mute=1"
];
let current = 0;
let player;

// Fonction pour charger et jouer la vidéo courante
function playCurrent() {
  // Change l'URL de l'iframe pour la vidéo courante
  document.getElementById('playlistIframe').src = playlist[current];
}

// Fonction appelée par l'API YouTube quand le player est prêt
function onYouTubeIframeAPIReady() {
  player = new YT.Player('playlistIframe', {
    events: {
      'onStateChange': onPlayerStateChange
    }
  });
}

// Quand la vidéo se termine, passer à la suivante
function onPlayerStateChange(event) {
  if (event.data === YT.PlayerState.ENDED) {
    current = (current + 1) % playlist.length;
    player.loadVideoByUrl(playlist[current]);
  }
}

// Charger l'API YouTube Iframe
(function() {
  var tag = document.createElement('script');
  tag.src = "https://www.youtube.com/iframe_api";
  var firstScriptTag = document.getElementsByTagName('script')[0];
  firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);
})();

// Démarrer la playlist au chargement de la page
document.addEventListener('DOMContentLoaded', function() {
  playCurrent();
});
</script>

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