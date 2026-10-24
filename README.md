# Wonder Quest Party Arcade v5.0

A touch-first arcade pack designed for a large classroom display and small-group rotation. This is a complete multi-file project, not a standalone HTML mock-up.

## Included

- `index.html` — application shell and navigation
- `css/style.css` — responsive arcade UI, cards, overlays and game layout
- `js/data.js` — 30 game descriptions, instructions, categories and scene mapping
- `js/games.js` — self-contained touch/pointer game engine and gameplay logic
- `js/app.js` — game catalogue, team scores, party mode, controls and sound
- `assets/scenes/` — six bundled scene images
- `assets/gallery/` — ten bundled world-art images
- `assets/audio/` — locally bundled sound effects and an original synthesized arcade loop in OGG format
- `.nojekyll`, `VERSION.txt`, `HOW_TO_PUBLISH_GITHUB_PAGES.txt`

## Play offline from USB

1. Extract the entire ZIP into one folder on the computer or USB drive.
2. Keep the folder structure unchanged: `index.html`, `css/`, `js/`, and `assets/` must sit side by side.
3. Open `index.html` in current Chrome or Edge.
4. Tap **Start Party** or choose any game card. Enter full screen for the classroom display.

The games do not call external sites or load remote libraries. First-time audio playback may need one touch/click because browsers block autoplay until the user interacts.

## Publish to GitHub Pages

1. Extract this ZIP.
2. Upload the *contents* of this folder into the root of the `wonder-quest-arcade` repository (not the folder itself and not the ZIP alone).
3. Ensure `index.html` appears at the repository root beside `css/`, `js/`, and `assets/`.
4. In **Settings → Pages**, choose **Deploy from a branch → main → /(root)**.
5. Visit `https://xxxtire.github.io/wonder-quest-arcade/` after deployment.

## Game list (32)

Meteor Mayhem, Bubble Pop Frenzy, Fruit Frenzy, Brick Breaker, Space Shooter, Monster Whack, Stack Tower, Star Catcher, Laser Reflex, Candy Match Party, Ball Sort Party, Parking Escape, Maze Runner, Memory Flip, Simon Says, Cannon Carnival, Puck Slam, Penalty Shootout, Balloon Burst, Dino Hop Run, Dodge the Fall, Fishing Frenzy, Bubble Shooter, Paper Plane, Treasure Dig, Color Flood, Frog Hop Tactics, Rhythm Tap, Boss Rush, Pinball Party, Traffic Panic and Paint Splash.

## Notes

- Team scores and personal bests are saved in the local browser profile. They are not synced across different computers.
- This pack uses custom JavaScript gameplay and bundled game art; it is not a real-time 3D engine.
- All generated/synthesized arcade sounds are shipped locally as OGG files; no network is needed during play.
