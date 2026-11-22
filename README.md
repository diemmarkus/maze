# Jonas' Spiele

Comic-style phone games by Jonas. The start page (`index.html`) lets you pick a game:

| Game | Folder | Status |
|---|---|---|
| Irrgarten | [`irrgarten/`](irrgarten/) | playable |
| Skiing | [`skiing/`](skiing/) | playable |
| Halfpipe | [`halfpipe/`](halfpipe/) | playable |
| The Line | [`line/`](line/) | playable |

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

## The Line

A minimal jump and run. The background is one colour, the level is a single lighter line in the same colour — and you are a piece of that line.

- **Landscape:** the game always plays sideways. On Android it goes full screen and locks to landscape when you tap *Play*; on iPhone (where pages can't lock the screen) the game turns itself by 90° if the phone is held upright.
- **Start screen** keeps it short: the title, your total stars, *Play* (goes to the newest level you've reached) and *Levels*. If you don't touch the screen in the first moment of a level, a ghost joystick (knob sliding left and right) and a pulsing tap button show the controls until you've used them.
- **Levels overview:** every level as a tile in its own colour with its best stars; the next three locked levels are shown greyed out.
- **Stars:** up to 3 per level, filled in quarters. 1 for reaching the door; dots: 1 dot = ¼, 2 = ½, all 3 = a full star; falls: none = a full star, 1 = ½, 2 = ¼; and if you were very slow it takes off ¼ (slower than a generous par time), ½ (1.5× par) or ¾ (2× par) — never below ½ star in total. So 3 stars still means all dots, no falls and not too slow. The result card shows the stars popping in and says what's missing.
- **Kids mode** (smiley button on the start screen, remembered on the phone): every heart holds two hits. The first hit takes half a heart, plays a "dong" and the game goes on — you bounce up and blink for a moment, nothing hurts while you blink. Fall into the abyss with a whole heart and a little cloud flies in above you, lets down a fishing line, hooks you and reels you back onto the line (half a heart gone). Once a heart is half gone, the next hit or fall works exactly like in normal mode.
- **Three lives:** the three hearts at the top. Fall three times and the level starts over from the beginning (dots and checkpoints reset) — a skull appears on the blood screen, stays in the middle of the screen at the start of the level, and as soon as you start moving its lines blur and fade away.
- **Run:** put your left thumb anywhere on the left half and drag left or right (a ring shows the joystick; the further you drag, the faster you run).
- **Jump:** tap with the other finger (anywhere on the right half, or anywhere while the left thumb is on the joystick). The character lifts out of the line and leaves a hole that closes again; in the air both ends of the piece swing round and meet, so it becomes a round outline — a wobbly blob. It melts back into the line when it lands.
- **Double jump:** tap once more in the air to jump even higher — but a little drop splits off the blob and falls away (the blob is smaller until it lands, then it's whole again).
- **The line** has steps, slopes and stairs, gaps to jump over, zig-zag spikes (touching them = fall), floating pieces and pieces sliding back and forth over a gap (moving bridges).
- **Sharks:** swim back and forth under the line — you only see the fin, which is the line itself bending up. Touch the fin and you're gone, so jump over it — but when you fly over a shark a pointed shark head (drawn after a picture from home) grows up out of the line — its outline starts and ends on the line — with an eye at the back and snapping jaws with teeth on the swimming side, so jump high (or double jump).
- **Sand:** a stretch of line made of grains over a pit, with grains trickling down from it all the time. You walk at about half speed on it. Stand still (or crawl) too long in one spot and you sink in, more sand pours out under you, and then you fall through a hole — which fills up again after a couple of seconds. From level 12, some moving bridges are made of sand too: you can't just ride them standing still — stay too long and the whole bridge pours away under you.
- **Eyes:** a pair of eyes floats up and down over a row of spikes and watches you (the pupils follow you, and they blink). Jump over the spikes while the eyes are up high — touch them and they stare at you in shock (little shock lines above), a big round head pops up over them with a wide snout, two nostrils and two fangs (drawn after a picture from home), the snout gapes open and sucks you in — SNAP — then it chews with happy eyes and wiggling fangs, gulps, burps a bubble and winks, before the blood comes down.
- **Birds:** a few little birds sit on the line, bobbing and pecking. Walk up to them and they notice you and fly off flapping. But they need a moment to take off: storm in at (nearly) full speed and you crash into one — and explode. Slow down a bit or jump over them.
- **Live wires:** a spark of electricity races back and forth along a stretch of the line (the line goes jagged where it is, with little arcs jumping off) — nothing marks where the wire starts or ends. Touch it — on top or underneath — and you're fried: lifted off the line and shaking, flickering between your outline with bolts arcing down to the line and a lit-up x-ray (zigzag spine, crossed-out eyes), with flashes and crackles; then you char into a broken outline, smoke curls up, and you crumble into a little heap of ash that blows away before the blood comes down. Jump over it as it comes.
- **Water:** a pool in the line, its surface the line itself, gently waving. Fall in with a splash and you slowly sink, blowing bubbles — keep tapping to swim (each tap is a stroke upwards), you move slower under water. Tap right at the surface to jump out onto the bank. Stop tapping and you sink too deep and drown. Sometimes a dot waits under water.
- **Ghosts:** float above the line. While the character looks away from a ghost, it creeps towards it with its eyes open and mouth gaping; as soon as the character faces it (the way you last moved), it freezes, turns see-through, shuts its eyes and trembles. Touching one is a fall — so keep turning round to face ghosts behind you, especially while waiting for a bridge.
- **Gravity switch:** the line twists into a figure eight whose loops keep flipping from one side to the other. Walk through it and you're on the other side of the line, running upside down underneath it (jumps go down, falling goes up). Walk back through it to flip back. Jumping over it does nothing — you have to walk through it on the line.
- **The start of the line** also ends in a small ring: walk into it and you wrap round the end onto the other side of the line (and back again the next time). You can't walk off it.
- **Secret door:** in a few levels (about one in ten, from level 4 — the first ones are 7, 26, 36 and 39) there's a small hidden ledge with a door deep down in the abyss to the left of the start — you can't see it from the line. Only a brave, big jump gets there: jump off the start to the left (just before the ring) and double-jump late, near the top of the fall. The door finishes the level right away (with a "Secret door!" message), but you skip the dots, so it's never a 3-star finish.
- **The end of the line** is a small ring, just past the door. If you arrive upside down, walk to the end and you wrap round it onto the top, then walk back into the door. You can't walk off the end.
- **Dying:** on the line (spikes, fins, jaws) the character sinks back into the line and sends three big ripples running along it. Falling off the screen makes a splash of drops at the edge. Hit in the air, it swells up with crossed-out eyes and bursts. Each time the phone vibrates (not on iPhones), the screen shakes and blood in the line colour pours down from the top — a few wide runs with round ends and round arches between them, some long ones letting go of a round drop — until the whole screen is covered, then it fades and you're back at the checkpoint.
- **Falling into a gap:** once you're clearly below the line, you're gone — you can't climb back up from underneath (e.g. onto a moving bridge) with the double jump.
- **Checkpoints:** falling off the line, into spikes or into a shark sends you back to the last checkpoint: a pole with a ball on top. The ball fills when you pass one.
- **Little animations:** landing (and jumping off) sends small ripples along the line, the character blinks, spikes breathe, fins bob, checkpoint lollipops sway.
- **Everything is the line:** the character, spikes, shark fins and jaws, gravity switches, checkpoints and the door are all drawn as bends of the one line, in the same thickness.
- **Dots:** three per level to collect. **Goal:** the door at the end of the line. Walk in and it lights up, then its colour floods the whole screen — the result card is shown in the line colour.
- **New things come one at a time:** stairs (level 2), spikes (3), floating pieces (4), sharks (5), moving bridges (6), sand (7), eyes (8), ghosts (9), gravity switches (10), water (11), live wires (12), birds (13). In the level where something is new, it shows up about three times.
- **Levels** are generated from the level number (always the same layout for the same level), get longer and harder, and every level has its own colour. Reached levels can be picked in the level overview. A search bot checked that levels 1–14 can be finished.
- **Sound:** Commodore 64 style blips made with the SID chip's pulse wave — rising sweep for the jump, a higher one for the double jump, plus sounds for dots, checkpoints, falling and the door. The speaker button next to pause turns it off (remembered on the phone).
- **Music:** an original 90s Italo-dance track on a Commodore-64-style synth (136 BPM, G minor: SID pulse waves with sweeping pulse width, bouncing filter bass, the running arpeggio and catchy tune from the first version, off-beat chord stabs, echo). The song runs about 1½ minutes. First comes a breakdown where a flat, crunchy robot voice says "softer", "slower" and "blobber" and the groove does just that, answered by bits of the old tune, then a riser and the drop; later, over a bass heartbeat, the robot says "I walk the line" before a second drop with both tunes. Now and then the music powers down and only a heartbeat goes on, played on the bass and in time with the song; after a few seconds the next jump brings the music back, right on the beat. The song runs on through levels and menus and even continues where it was after the game is closed. If the phone puts the audio to sleep, the next touch wakes it. The note button at the top turns it off (remembered on the phone), separately from the sound effects.
- **Install as an app:** The Line has its own app manifest and works offline once opened. On Android (Chrome) an *Install as app* button appears on the start screen; on iPhone use Safari's Share button → *Add to Home Screen* (the start screen says so). The installed app opens full screen in landscape.
- Keyboard: ←/→ or A/D to run, Space/↑/W to jump (again in the air for the double jump), P or Esc to pause.

---

## Halfpipe

A pixel-art snowboard halfpipe contest in the same look as Skiing. Players take turns: 2 rounds, each run is 6 jumps (right wall, left wall, …). Most points wins.

- The start menu keeps it short: three one-line rules.
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
