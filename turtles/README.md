# Turtle Times (arcade)

An old-school arcade game for practicing multiplication, starring pixel-art turtles. It runs in Safari on an iPad, with nothing to install.

**Link:** https://applesandbeer.github.io/Octopus/turtles/ (open it in Safari → Share → **Add to Home Screen**. It shows up as "Turtle Times".)

## The arcade part

Chunky pixel graphics and a pixel font, a screen with scanlines like an old TV, chiptune music and sound effects, score with a 1UP counter, lives (hearts), combos up to ×5, a boss fight, "WARNING!" screens, and a top-5 high score table where he enters his 3 initials.

## The stages (they repeat each round and get harder)

| Stage | What happens | What it teaches |
|---|---|---|
| 1. **Shell Catch** | Turtles swim by, each carrying the same number of eggs. Tap turtles to fill the nest until it holds exactly the target ("Catch 15 eggs, 5 on each"). Catch one too many and it jumps back out. Gold turtles give bonus points. | **Equal groups** and **skip counting**. The nest shows the running count: 5, 10, 15. Eggs are laid out in rows of 5, like a ten-frame. |
| 2. **Turtle Invaders** | A Space Invaders formation of turtles, one color per row. Tap rows to count them, then tap the right number to fire. The rows explode one at a time while it counts: 10… 20… | **Arrays**: rows × how many in each row. |
| 3. **River Hop** | A Frogger-style river. Logs float by with numbers on them. Hop to the next number when counting by 2s, 5s or 10s. A wrong log means a splash, a lost heart, and starting the river over. The right log is never shown. | **Skip counting = multiplying.** The path he took shows at the bottom: 0 2 4 6. |
| 4. **Shell Racer** | A top-down race. Tap a lane to steer and grab golden eggs. At each gate the kart stops and waits, then he drives through the right answer. Right answers give a turbo boost; wrong ones spin him out. | **Connecting different ways of showing multiplication.** Gates mix 4 kinds of questions: a picture of groups → "2×10", turn-around facts ("same as 3×4?" → 4×3), "what comes next" counting (5 10 15 ?) and plain facts. |
| 5. **Boss** | A giant crowned turtle. Each right answer to a times fact fires a turtle shell at him. There's a different boss each round: King, Ice, Lava, Robo and Shadow Snapper. Each round's boss has more health. From round 3 he also asks missing-number questions (3 × ? = 12). | Recall of **times facts with the × sign**, and starting to think backwards (the start of division). HELP shows the groups as dots. |
| ★ **Egg Builder** (bonus) | "Make 12!" Use + and − to set the number of rows and how many eggs are in each row. Every way that makes the number earns points, and finding all of them is PERFECT. There are no hearts to lose. | **Open-ended thinking**: one number can be built many ways (2×6, 3×4, 4×3, 6×2). A tip nudges him to "turn it around." |

After the bonus stage, the next round starts. Everything gets a little faster, and new facts unlock.

## Heroes

Beating bosses unlocks new turtle heroes. Pick one with the **HEROES** button on the title screen: Shelly, Dash, Pirate Pete, Robo, Lava, Cosmo and Goldie. The chosen hero appears in every stage.

## Why it's built this way

- **Meaning before memorizing.** The first three stages are pictures of multiplication (groups, rows and skip counting). The bare × fact only shows up in the boss fight, and HELP turns it back into a picture.
- **Every answer is shown both ways:** "3 rows of 5" and **3 × 5 = 15**.
- **Turn-around facts.** 7 × 2 can show up as 2 rows of 7, so he sees that the order doesn't change the answer.
- **Easiest facts first:** 2s, 10s, 5s, then 1s. Bigger 2s, 5s and 10s come next, then 3s and 4s. A new set unlocks each time he beats a boss.
- **Mixed practice.** The stages rotate, so he keeps switching between kinds of thinking. That helps learning stick better than doing one kind over and over.
- **Spaced repetition.** Facts he misses come back more often.
- **Mistakes teach.** A wrong answer costs a heart, then the game shows how to get it right: the rows light up and count, or the nest re-counts. River Hop is the exception: a wrong log sends him back to the start to count again on his own.
- **No timer, ever.** The action is real (turtles swim, logs drift, the boss sways), but nothing makes him answer fast. Logs and turtles come back around.
- **Arcade rewards keep him coming back:** score, combos, bonus lives after each wave, gold turtles, and a high score to beat. Continuing is free, and fact progress is kept.

## Grown-ups

On the title screen, **press and hold "GROWN-UPS"** (bottom left) for one second. It shows his best round, how many fact sets are unlocked, and a chart of which facts he knows (gray = not seen, yellow = learning, green = knows it). You can also reset everything there.

During a game, the **II** button (top right) pauses. From there you can turn music and voice on or off, or quit.

## Sound

Music and sound effects start after the first tap. They play even when the iPad's silent switch is on (a newer iPad lets the page request this; older ones use a silent background track). If there's still no sound, turn up the volume, and check MUSIC in the pause menu (II) or on the title screen.

## Technical notes

- Everything is in `index.html`: one canvas, plain older-style (ES5) JavaScript, no outside downloads. The sprites, font and music are all made in code.
- High scores and progress are saved only on that iPad.
