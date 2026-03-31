# Sine Runner

A browser-based platformer where every move you make shapes the music. Player movement, health, enemy proximity, and coin collection all drive real-time audio synthesis — creating a unique soundtrack for every playthrough.

## Features

- **5 Levels** with procedurally generated platforms, coins, and enemies
- **Dynamic Audio Engine** — melody oscillator tracks vertical position, tension layer responds to enemy proximity, drum sequencer tempo scales with speed
- **BPM (80–180)** driven by horizontal velocity
- **Filter Cutoff** shaped by health and coin collection ratio
- **One-Shot Effects** — jump kicks, landing snares, coin blips, damage noise
- **Parallax Scrolling** — 3-layer depth with dynamic color themes per level

## Tech Stack

- Vanilla JavaScript — single `index.html` file, no dependencies
- HTML5 Canvas for rendering
- Web Audio API for synthesis and effects

## Running

Open `index.html` in any modern browser. Click to start.

```bash
# Or use a local server
python3 -m http.server 8000
```

## Controls

| Key | Action |
|-----|--------|
| Arrow Keys / WASD | Move |
| Space / Arrow Up / W | Jump |
