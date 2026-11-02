# Irrgarten

A comic-style tilt maze for the phone. Roll the ball through a hedge maze to the hole — but the bushes keep growing, and once the paths are as narrow as the ball, it's over.

- **Tilt** the phone (motion sensor) to roll the ball. Wherever you hold the phone when you start counts as level.
- No sensor (desktop)? Drag on the screen, or use the arrow keys / WASD.
- Each level the maze gets bigger and the hedges grow faster. Time left when you sink the ball is bonus points.
- **Difficulty:** Easy, Medium, Hard (Hard = the original speed). Best score is kept per difficulty.
- **Power-ups:** always in a dead end. Each level has either hedge shears, a caterpillar, or nothing — every three levels you get each once, in random order.
- **Hedge shears:** roll over them to cut the hedges back by 60 %.
- **Caterpillars:** roll over one and it crawls into the hedge and munches — the bushes grow 35 % slower for the rest of the level.
- **Teleporter:** from level 2, every other level (shuffled) has a pair of portals — roll into one and you come out of the other with your speed.
- **Wasps:** from level 3, every other level (shuffled) has a wasp nest. Rolling over it stirs it up; once the ball has rolled off, three wasps come out and chase it for about 3 seconds, up to about 2 cells from the nest. If they catch the ball, the level is lost.
- **Continue:** after a loss you can restart at any level you've reached on that difficulty. The restart button retries the current level.
- Languages: EN, DE, FR, ES, IT, PT.

Single self-contained `index.html` — no build step. Same look and tilt handling as [Don't Spill](https://github.com/diemmarkus/dont-spill).

Play: enable GitHub Pages (Settings → Pages → deploy from `main`) and open it on your phone. iOS asks for motion permission when you tap the start button.
