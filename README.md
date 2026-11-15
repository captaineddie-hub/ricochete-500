# Ricochet 500

A colorful, mobile-friendly arcade bank-shot game from Captain Eddie Games.

## Play

Play online at https://captaineddie-hub.github.io/ricochete-500/ or upload the HTML5 release ZIP to itch.io.

Pull the puck **back**, adjust your angle, and release to bank off the V-shaped rebound cushions into the scoring lane. Each player shoots four pucks per round; first to 500 wins.

**Modes:** four single-player challenge boards against the CPU, pass-and-play on one device, and private-room online multiplayer. Bonus stars occasionally appear in the left scoring lane.

## itch.io

GitHub Actions builds the playable ZIP automatically via **Build itch.io HTML5 release**. Download the most recent `Ricochet-500-itch-HTML5` artifact, extract the wrapper ZIP if necessary, and upload the inner `Ricochet-500-itch-HTML5.zip` to itch.io as a browser-playable HTML game. Set pricing to **free with optional donations** (suggested contribution $2.99).

The bundled PeerJS script is local to the release; peer signaling and WebRTC still require connectivity. Multiplayer rooms are intended for casual friendly games and are not server-authoritative.

## Project notes

The GitHub repository retains the historical spelling `ricochete-500` in its URL to avoid breaking existing links. The **displayed game title is Ricochet 500**.

Level-progress storage migrates from the old `ricotte500levels` key on existing devices. 
