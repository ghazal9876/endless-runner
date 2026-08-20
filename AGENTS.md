# Endless Runner

This is a dependency-free browser game. `index.html` is the Space Mission landing page and `level1.html` contains the playable Level 1 canvas game.

- Keep Level 1 gameplay and rendering in the existing canvas loop in `level1.html`.
- Preserve the three-lane controls: Left/Right arrow keys change lanes one step at a time.
- Keep visuals night-sky themed and preserve clear contrast for the jet, enemies, and enemy fire.
- Test changes by opening `index.html` in a modern browser.
- Do not add a framework or build step unless explicitly requested.

## Components

- [x] Player jet — moves between three hidden lanes with Left/Right arrows and fires with Space.
- [x] Forward flight view — a perspective path, parallax stars, comets, and moving planet sets create the sense of forward motion.
- [x] Enemy system — meteors and cartoon UFOs enter from the distance, grow as they approach, and leave the screen after being passed.
- [x] Enemy attacks — UFOs fire aimed laser bursts that the player can dodge.
- [x] Player shots — shots follow the player’s flight path and destroy enemies.
- [x] Collision and game over — contact with an enemy or enemy laser ends the flight.
- [x] Score counter — awards points for dodging enemies, late lane changes, and destroying enemies.
- [x] Game-over screen and restart button — displays the distance score and starts a new run.
- [ ] Difficulty scaling — gradually increase enemy speed, frequency, and firing pressure.
- [ ] Visual feedback — add explosion effects, hit flashes, and score popups.
- [ ] Audio — add firing, explosion, and ambient space sound effects.
- [ ] High-score persistence — save the best score in browser storage.
