# PULSE

## About

A radial rhythm game. Defend the core at the center of the screen from energy orbs flying in along four color-coded tracks. Match the beat, match the key, hold your combo.

## Play

Open `index.html` in a browser. That's it. No build step, no dependencies, no server needed.

## Controls

- Arrow keys or WASD to hit orbs as they cross the white ring
- Space or Enter to start and restart
- M to toggle sound

## Orb types

- **Standard** (colored circle): press the matching arrow
- **Star** (gold): press any arrow for bonus points
- **Inverse** (pink diamond): press the opposite arrow
- **Hold** (green hexagon with tail): press and hold the matching arrow until the tail burns away

## How it was made

This game was vibe coded using Anthropic's Claude chat web app in the browser. The entire thing lives in a single `index.html` file: HTML, CSS, and vanilla JavaScript with the Canvas API and Web Audio API. No frameworks, no assets beyond the favicon. The logo started as a screenshot captured during a moment of gameplay. It was cropped and trimmed using the Preview app on macOS, then further cleaned up with a small Python script using Pillow. Claude Code CLI was used to write this README, touch up the logo, and wire the logo in as the page favicon.

## License

This project is licensed under the [GNU General Public License v3.0](../../LICENSE).
