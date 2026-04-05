# Vibes Arcade

## About

A small collection of web games and visual experiments built with [vibe coding](https://en.wikipedia.org/wiki/Vibe_coding).

## Run

Open `index.html` in a browser, or serve the directory:

```bash
python3 -m http.server
```

## Structure

`index.html` is the landing page, `assets/` holds shared assets, and `games/` contains each game in its own directory, with `games/third-party/` reserved for external games (each entry is a folder with a thumbnail and a `game.json`).

## Adding a third-party game

Create `games/third-party/<slug>/` containing a thumbnail and `game.json`:

```json
{
  "title": "Game Name",
  "description": "One-sentence description.",
  "url": "https://example.com/game",
  "thumbnail": "logo.png"
}
```

Then add a matching `<li>` entry to `index.html`.

## License

This project is licensed under the GNU-GPL-v3 (see [LICENSE](LICENSE)). Each listed game is released under its own license, but every one of them uses either GNU-GPL-v3 or MIT, and all of them will stay and be open-source for the foreseeable future (hopefully forever).
