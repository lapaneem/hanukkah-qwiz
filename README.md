# Hanukkah Qwiz — Light Up My Menorah

A small, self-contained Hanukkah quiz. Build a quiz about yourself, share the link with friends, and watch scores light up a 3D fireside menorah leaderboard.

## Running it

It's a single static page with no build step or dependencies. Open `index.html` in a browser, or serve the folder with any static host (e.g. GitHub Pages).

## How it works

- **Make your own quiz:** pick your favorite answer for each of 8 Hanukkah questions. Friends try to guess your choices.
- **Share link:** the quiz is encoded into the URL hash (`#quiz=...`), so no server is needed. Friends open the link, enter their name and answer your questions.
- **Creators can't take their own quiz:** each link carries a random quiz ID, and the browser that made the quiz remembers it. Opening the link there shows "This is your quiz" and the leaderboard instead of the quiz.
- **Leaderboard:** the top score is the shamash, the next eight are candles, and everyone else appears as a dreidel on the rug. Drag the menorah to look around.

## Project layout

- `index.html` — the whole app (HTML, CSS and JS inline)

## Origin

Started as a Codex project (`hanukkah-quiz.html`) and moved into this repository.
