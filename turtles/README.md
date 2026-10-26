# Turtle Times (arcade)

An old-school arcade game for practicing multiplication, starring pixel-art turtles. It runs in Safari on an iPad, with nothing to install.

**Link:** https://applesandbeer.github.io/Octopus/turtles/ (open it in Safari → Share → **Add to Home Screen**. It shows up as "Turtle Times".)

## The arcade part

Chunky pixel graphics and a pixel font, a screen with scanlines like an old TV, chiptune music and sound effects, score with a 1UP counter, lives (hearts), combos up to ×5, a boss fight, "WARNING!" screens, and a top-5 high score table where he enters his 3 initials.

## The four stages (they repeat as rounds, and get harder)

| Stage | What happens | What it teaches |
|---|---|---|
| 1. **Shell Catch** | Turtles swim by, each carrying the same number of eggs. Tap turtles to fill the nest until it holds exactly the target ("Catch 15 eggs, 5 on each"). Catch one too many and it jumps back out. Gold turtles give bonus points. | **Equal groups** and **skip counting**. The nest shows the running count: 5, 10, 15. Eggs are laid out in rows of 5, like a ten-frame. |
| 2. **Turtle Invaders** | A Space Invaders formation of turtles, one color per row. Tap rows to count them, then tap the right number to fire. The rows explode one at a time while it counts: 10… 20… | **Arrays**: rows × how many in each row. |
| 3. **River Hop** | A Frogger-style river. Logs float by with numbers on them. Hop to the next number when counting by 2s, 5s or 10s. | **Skip counting = multiplying.** The path he took shows at the bottom: 0 2 4 6. |
| 4. **King Snapper** (boss) | A giant crowned turtle. Each right answer to a times fact (3 × 4 = ?) fires a turtle shell at him. Five hits beats him. | Recall of **times facts with the × sign**. HELP shows the groups as dots. |

Beating the boss starts the next round: everything gets a little faster, and new facts unlock.

## Why it's built this way

- **Meaning before memorizing.** The first three stages are pictures of multiplication (groups, rows and skip counting). The bare × fact only shows up in the boss fight, and HELP turns it back into a picture.
- **Every answer is shown both ways:** "3 rows of 5" and **3 × 5 = 15**.
- **Turn-around facts.** 7 × 2 can show up as 2 rows of 7, so he sees that the order doesn't change the answer.
- **Easiest facts first:** 2s, 10s, 5s, then 1s. Bigger 2s, 5s and 10s come next, then 3s and 4s. A new set unlocks each time he beats the boss.
- **Mixed practice.** The stages rotate, so he keeps switching between kinds of thinking. That helps learning stick better than doing one kind over and over.
- **Spaced repetition.** Facts he misses come back more often.
- **Mistakes teach.** A wrong answer costs a heart, then the game shows how to get it right: the rows light up and count, the right log blinks, or the nest re-counts.
- **No timer, ever.** The action is real (turtles swim, logs drift, the boss sways), but nothing makes him answer fast. Logs and turtles come back around.
- **Arcade rewards keep him coming back:** score, combos, bonus lives after each wave, gold turtles, and a high score to beat. Continuing is free, and fact progress is kept.

## Grown-ups

On the title screen, **press and hold "GROWN-UPS"** (bottom left) for one second. It shows his best round, how many fact sets are unlocked, and a chart of which facts he knows (gray = not seen, yellow = learning, green = knows it). You can also reset everything there.

During a game, the **II** button (top right) pauses. From there you can turn music and voice on or off, or quit.

## Technical notes

- Everything is in `index.html`: one canvas, plain older-style (ES5) JavaScript, no outside downloads. The sprites, font and music are all made in code.
- High scores and progress are saved only on that iPad.
