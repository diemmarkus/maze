# Jonas' Spiele

Comic-style phone games by Jonas. The start page (`index.html`) lets you pick a game:

| Game | Folder | Status |
|---|---|---|
| Irrgarten | [`irrgarten/`](irrgarten/) | playable |
| Skiing | [`skiing/`](skiing/) | playable |

At the bottom, **Mehr Spiele** links to Anna's start page ([Abenteuer](https://diemmarkus.github.io/danger-in-the-jungle/)).

Play: https://diemmarkus.github.io/maze/

---

## Skiing

A pixel-art ski race against the computer on a mogul run.

- **Tap** while going down a bump (yellow snow) to speed up. Perfect timing (early on the downslope) gives the biggest boost.
- **Tap uphill** and you slow down and wobble. Tap wrong again while wobbly and you fall — race over. Three good taps in a row get rid of the wobble.
- **Ramps:** tap on the orange part of the ramp to jump high. Not tapping gives only a small hop; tapping too early counts as a wrong tap.
- **Backflip:** keep your finger down in the air. Let go in time — the skier finishes the turn on its own — so you land straight, or it's a crash. Every flip gives a speed boost.
- **The computer** is the pale skier in the background. Reach the finish before it does. Each level the course gets longer and the computer gets better.
- Level select for every level you've reached. Keyboard: Space / arrow keys.
- Languages: EN, DE, FR, ES, IT, PT (shared with Irrgarten).

---

## Irrgarten

A comic-style tilt maze for the phone. Roll the ball through a hedge maze to the hole — but the bushes keep growing, and once the paths are as narrow as the ball, it's over.

- **Tilt** the phone (motion sensor) to roll the ball. Wherever you hold the phone when you start counts as level.
- No sensor (desktop)? Drag on the screen, or use the arrow keys / WASD.
- Each level the maze gets bigger and the hedges grow faster. Time left when you sink the ball is bonus points.
- **Difficulty:** Easy, Medium, Hard (Hard = the original speed). Best score is kept per difficulty.
- **Power-ups:** always in a dead end. Each level has either hedge shears, a caterpillar, or nothing — every three levels you get each once, in random order. At most 2 extras (power-up, wasp nest, teleporter) per level.
- **Hedge shears:** roll over them to cut the hedges back by 60 %.
- **Caterpillars:** roll over one and it bursts into a swarm of tiny caterpillars that crawl into the hedges all over the maze and munch — the bushes grow 35 % slower for the rest of the level.
- **Teleporter:** from level 2, every other level (shuffled) has a pair of portals — roll into one and you come out of the other with your speed.
- **Wasps:** from level 3, every other level (shuffled) has a wasp nest. Rolling over it stirs it up; once the ball has rolled off, three wasps come out and chase it for about 3 seconds, up to about 2 cells from the nest. If they catch the ball, the level is lost.
- **Green dot:** from level 2, every other level (shuffled, if there is room for an extra) has a green dot. Roll over it and the hole flies off to another spot far from the ball.
- **Black hole:** from level 2, every other level (shuffled, if there is room) has a hole without a flag. Fall in and the level is lost. It never lies on the real route to the goal — only off to the side, preferably in a dead end — also after a green dot has moved the goal.
- **Level select:** tap the LVL chip at the top to pause and pick difficulty and level.
- **Continue:** after a loss you can restart at any level you've reached on that difficulty. The restart button retries the current level.
- Languages: EN, DE, FR, ES, IT, PT.

Single self-contained `irrgarten/index.html` — no build step. Same look and tilt handling as [Don't Spill](https://github.com/diemmarkus/dont-spill).

Play: enable GitHub Pages (Settings → Pages → deploy from `main`) and open it on your phone. iOS asks for motion permission when you tap the start button.
