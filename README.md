# Bells Break

**Surfing an Australian point break: floaters, aerials and deep barrels, then real heats against rivals who hold priority and steal your favourite wave.**

<p align="center">
  <img src="assets/screenshot-title.png" alt="Bells Break — title screen" width="820">
</p>

<p align="center">
  <a href="https://ai-llm-2030.github.io/TrueMarch_Games_Bells_Break/"><b>▶ Play Bells Break in your browser</b></a>
</p>

## Gameplay

<p align="center">
  <img src="assets/screenshot-play.png" alt="Bells Break — gameplay" width="820">
</p>

## Controls

| Keys | Action |
|---|---|
| Space / click | Paddle in · pump · snap · cutback · floater · stomp an air |
| Esc | Back |
| P | Pause |
| M | Mute |

## Run it yourself

No install, no build step, no server code, no network. The game runs entirely in your browser and keeps your progress in the browser's local storage.

```bash
git clone https://github.com/ai-llm-2030/TrueMarch_Games_Bells_Break.git
cd TrueMarch_Games_Bells_Break
python3 -m http.server 8000
# open http://localhost:8000
```

Opening `index.html` directly works too in most browsers; a local server is the most reliable way.

## What's inside

```
TrueMarch_Games_Bells_Break/
├── index.html        the whole game: one file, plain JavaScript and <canvas>
├── assets/           the pictures in this README
├── LICENSE
└── README.md
```

Written from scratch in vanilla JavaScript: every sprite, background and sound is drawn or synthesised in code (Canvas 2D and the Web Audio API). No libraries, no frameworks, no third-party assets.

## About

**Bells Break** is one of the 120+ games made by **[TrueMarch](https://truemarch.com)**. This repository is the standalone single-player edition of the game.

## License

© 2026 TrueMarch. All rights reserved. The source is published so you can read it, learn from it and play the game; see [LICENSE](LICENSE).
