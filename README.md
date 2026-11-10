# Jonas' Spiele

Comic-style phone games by Jonas. The start page (`index.html`) lets you pick a game:

| Game | Folder | Status |
|---|---|---|
| Irrgarten | [`irrgarten/`](irrgarten/) | playable |
| Skiing | [`skiing/`](skiing/) | playable |
| Halfpipe | [`halfpipe/`](halfpipe/) | playable |

There's also a secret one: the tiny glider under the language buttons opens **Leben** ([`life/`](life/)).

At the bottom, **Mehr Spiele** links to Anna's start page ([Abenteuer](https://diemmarkus.github.io/danger-in-the-jungle/)) and to the [WebAR experiments](https://diemmarkus.github.io/WebAR/) (Skiing AR lives there).

Play: https://diemmarkus.github.io/maze/

---

## Leben (Game of Life) — secret

Conway's Game of Life in the pixel look of Skiing. Not on the game list: tap the faint glider under the language buttons on the start page.

- **Touch to bring cells to life:** tap and drag to draw living cells. Start on a living cell and you erase instead. Several fingers work at once, also while it's running.
- **Yellow button = touch tool:** pen, glider, spaceship or boom (a random burst). With the last three, every tap drops that pattern, pointing in a random direction.
- **Buttons:** play/pause, one step, speed 1×/2×/4×, clear. It starts with a random fill.
- **Black & white** is the default: white cells on black. The half-black button switches to colour (remembered on the phone).
- **Eye button:** hides all buttons and chips, the grid fills the whole screen. Tap the faint eye in the bottom-right corner to bring them back.
- **+ / − (top right):** + doubles the number of cells (smaller cells), − halves it. What's alive stays in the middle.
- In colour mode, cells change colour as they age (white newborn → gold → orange → red → purple, blue for cells that stay put); dying cells leave a short shadow. The edges wrap around.
- Keyboard: Space = play/pause, → = one step, T = next tool, +/− = more/fewer cells, B = black & white, H = hide buttons.

---

## Halfpipe

A pixel-art snowboard halfpipe contest in the same look as Skiing. Players take turns: 2 rounds, each run is 6 jumps (right wall, left wall, …). Most points wins.

- **Jump:** tap while riding up the wall. The jump height depends only on how close to the edge you tap. A bar at the top of the screen fills as you ride up (red = too early, yellow = ok, green = big air), and the edge of the wall flashes green at the best moment. No tap = only a tiny hop.
- **Tricks:** swipe in the air (or on the way up after tapping) — left/right = a 360 spin, up = front flip, down = backflip. One swipe = one trick, however long it is (swipe twice for two). Swipes queue up and run one after another, so you can combine them. Arrows above the rider show the queue: green = done, gold = doing, white = coming, red = won't finish before landing.
- **Height:** the height counts up next to the rider; at the top it pops (white, gold from 3 m, orange from about 5 m) and stays a moment after the landing.
- **Mega jumps** are only possible after a good jump (tapped in the green and landed clean) — a blinking star next to the jump bar shows it. Otherwise the jump tops out at about 4.7 m.
- **Slow motion:** mega jumps (about 5 m and more — only with a tap right at the edge) go into slow motion around the top, with black bars and a *MEGA AIR!* banner. Tricks slow down too, so you get more time to swipe.
- **Finale:** after the last run the winner rides a victory run with fanfare, confetti and fireworks and the crowd cheering (tap to skip), then a trophy and a score board with both runs and the totals counting up.
- **Animation:** spins turn the rider through side, front and back views; flips are done tucked with a grab; big airs get a grab; crouch before the jump, stretch on take-off, squash on landing, and a short motion trail during tricks.
- **Landing:** if a trick isn't finished when you land you fall on your face — and the whole run is over with 0 points. Almost finished = a wobbly landing with half trick points.
- **Points:** height (60 per metre) plus tricks (spin 100, flip 150), multiplied for combos (×1.5 for 2 tricks, ×2 for 3, …) and ×1.25 for mixing spins and flips.
- **1 player:** against the computer, which rides its runs in between yours (tap *Watch* or wait; **Fast forward** speeds it up 4×). Who starts round 1 alternates from game to game; in round 2 the leader goes first. Beat it to unlock the next level — the computer gets better and the scenery rotates (day, sunset, forest, night). **2 players:** Red and Blue take turns on one phone.
- Your snowboarder uses the same colours as your skier in Skiing (picker on the start screen; helmet and board share a colour). Keyboard: Space = jump, arrow keys / WASD = tricks.

---

## Skiing

A pixel-art ski race against the computer on a mogul run.

- **Tap** while going down a bump (yellow snow) to speed up. Perfect timing (early on the downslope) gives the biggest boost.
- **Tap uphill** and you slow down and wobble. Tap wrong again while wobbly and you fall — race over. Three good taps in a row get rid of the wobble.
- **Ramps** come in three sizes — small (single flip), medium (double), big (triple, marked with three gold dots on the edge pole). Tap on the upper part of the ramp, just before the edge, to jump high (the snow is white, no colour hint). Not tapping gives only a small hop; tapping too early counts as a wrong tap.
- **Backflip:** keep your finger down in the air. Let go in time — the skier finishes the turn on its own — so you land straight, or it's a crash. Every flip gives a speed boost.
- **Hurdles (from level 3):** fences, snowmen, log piles, barriers, cows and goats — and very rarely a yeti — on white snow. Tap just before a hurdle to jump off the ground and clear it — each clean jump gives a little boost. Hitting one slows you down and makes you wobble; hitting another while wobbly is a fall.
- **The computer** is the pale skier on its own lane, shifted up behind yours, so you see both racing side by side. Reach the finish before it does.
- **Levels look different:** level 1 is short, then every level gets longer. Level types rotate — more bumps, more ramps, more hurdles, or a mix — and so does the scenery: day, sunset, forest, night. The computer gets better every level.
- **Your skier:** tap **Your skier** on the start screen to open the picker and choose the colours: helmet, skis and poles (always matching), sweater, pants and skin (saved on the phone; until you pick, every visit gives a random skier). In 2-player mode the skiers stay red and blue so you can tell them apart.
- Level select for every level you've reached, in its own dialog (tap **Level** on the start screen). Keyboard: Space / arrow keys.
- **2-player mode** (optional, pick it in the menu): two players on one phone, no computer, each in their own window — stacked in portrait, side by side in landscape. Blue taps in the top/left window, Red in the bottom/right one; both can tap at the same time. In each window your skier is in front and the other one rides on the back lane. First at the finish wins; a fall only ends your own race. Keyboard: A = Blue, L = Red.
- Languages: EN, DE, FR, ES, IT, PT — chosen on the start page, shared by all games.

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
- Languages: EN, DE, FR, ES, IT, PT — chosen on the start page.

Single self-contained `irrgarten/index.html` — no build step. Same look and tilt handling as [Don't Spill](https://github.com/diemmarkus/dont-spill).

Play: enable GitHub Pages (Settings → Pages → deploy from `main`) and open it on your phone. iOS asks for motion permission when you tap the start button.
