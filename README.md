# NEON SMASH

A neon-arcade stress-relief game. Shoot glowing targets before their countdown ring runs out and watch them shatter into light. No installs, no dependencies — it's a single HTML file. Aimed towards be played with in VR. Use your Oculus and get he most of the game.

## Play

- **Hold or drag** to rapid-fire at wherever your crosshair is.
- Every target has a **countdown ring**. Smash it before the ring drains.
- Miss the timer and the target **explodes for zero points** and breaks your combo.
- Multi-hit targets (orbs, blocks) show a **life counter** that ticks down with each hit.

## Levels

1. **Glass Grid**
2. **Cube Crush**
3. **Orb Overload**
4. **Meltdown**
5. **Chaos Storm** — endless waves

Pick any level from the **Select Level** menu, and use **Main Menu** to jump back out whenever you're done.

## Run it

Just open `index.html` in any modern browser — that's it.

### Play it online (GitHub Pages)

If this repo is hosted on GitHub, enable Pages:

1. Go to the repo's **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Choose branch **main** and folder **/ (root)**, then **Save**.
4. After a minute, your game is live at `https://<your-username>.github.io/<repo-name>/`.

## Tech

Plain HTML, CSS, and vanilla JavaScript on an HTML5 canvas. Sound is synthesized live with the Web Audio API, so there are no asset files. Fully responsive and works on desktop and mobile.
