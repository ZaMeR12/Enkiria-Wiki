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
  <video
    id="playlistVideo"
    controls
    allowfullscreen
    poster="/path/to/poster.png"
    muted
    autoplay
    class="radiusImg5"
    width="1500"
    height="562"
    style="max-width:100%;"
  >
    Your browser doesn't support media player.
  </video>
</div>
<script>
const playlist = [
  "assets/video/forms1-trailer.mp4",
  "assets/video/rick-roll.mp4"
];
let current = 0;
const video = document.getElementById('playlistVideo');

// Fonction pour charger et jouer la vidéo courante
function playCurrent() {
  video.src = playlist[current];
  video.load();
  video.play();
}

// Quand la vidéo se termine, passer à la suivante
video.addEventListener('ended', function() {
  current = (current + 1) % playlist.length;
  playCurrent();
});

// Démarrer la playlist au chargement de la page
document.addEventListener('DOMContentLoaded', playCurrent);
</script>

</br>

<div markdown class="outer">
<figure markdown class="img1 embed news">
  ![Spawn](spawn.png){.radiusImg15}
  <figcaption>Spawn</figcaption>
</figure>
</div>

## Useful links

[Discord :simple-discord:](https://discord.gg/RUjgy7wKXr){: .md-button .md-button--primary target="_blank"}
[Pixelmon Wiki :material-pokeball:](https://pixelmonmod.com/wiki/Main_Page){: .md-button .md-button--primary target="_blank"}
[Curse Forge :simple-curseforge:](https://www.curseforge.com/download/app){: .md-button .md-button--primary target="_blank"}

</br>

<span style="font-size:1.5rem">:material-server: enkiriapixelmon.mine.fun</span>