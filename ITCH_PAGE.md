# itch.io page kit: Hand Platformer

## Cover image (630x500)
- Background: flat #070B0E with a soft radial glow of #00D4E8 at about 15% opacity behind the center.
- Center: a large open hand outline in #00D4E8 (thin neon stroke, 21 small joint dots like the MediaPipe skeleton). The index finger points at the small character.
- Bottom third: a teal (#0B5965) platform strip with a bright #00D4E8 top edge. The pale (#B9DCE5) square character stands on it, mid-jump pose.
- Floating around: 4 gold coins (#FFD166), one red spike row, one red enemy block.
- Title at the top, bold, #00D4E8: "HAND PLATFORMER". Tagline under it in #B9DCE5: "No controller. Just your hand."
- Keep the key art inside the central 80% so itch's crops don't cut it.

## Short description
A platformer you play with your bare hand through your webcam. No controller needed.

## Description (paste into the itch page)
**Hand Platformer** is a 5-level platformer controlled by your hand in the air. Your camera tracks your hand, and your character runs, jumps, and fights through the levels. Everything runs locally in your browser; no video is ever uploaded.

### How to play
1. Press **Start with camera** and allow camera access.
2. Hold your hand up in front of the camera, with good light.
3. Collect every coin to open the exit door, then walk into it.
4. Stomp on enemies, avoid spikes and pits. You have 3 lives.
5. Finish all 5 levels and enter your name on the leaderboard.

### Controls
| Input | Hand | Keyboard | Touch |
|---|---|---|---|
| Move | Move your hand left / right of center (farther = faster) | Arrows or A / D | Drag in the left 30% of the screen |
| Jump | Close your fist (hold = higher) | Space / W / Up | Tap in the right 30% |
| Restart | Fist on the end screen | R | Tap the end screen |

### Features
- 5 handcrafted levels with moving enemies, spikes, and gaps
- Real-time hand tracking (MediaPipe), analog speed control, smooth input
- Touch controls for phones and tablets
- Local top-5 leaderboard
- Battery saver mode and automatic pause when your hand leaves the camera or the tab is hidden
- Installable and playable offline (from the web version)

### Tips
- Plain background and good front light make tracking much better.
- Drag the small camera preview anywhere, or hide it.
- If the camera does not start, check the browser permission and the laptop's camera shutter.

## Upload steps
1. Publish `index.html` (+ manifest, service worker, icons) on GitHub Pages. This is the real game.
2. For itch.io, zip **only `itch-wrapper/index.html`** and upload it as an HTML project. It embeds your GitHub Pages game with camera permission (`allow="camera"`).
3. Embed options: "Click to launch in fullscreen" or a viewport of 800x480, tick **Mobile friendly** and **Fullscreen button**.
4. Add the cover image, the description above, and the tags: platformer, hand-tracking, webcam, 2d, singleplayer.
