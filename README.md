# Puzzle Practice

A practice app for young children getting ready for the **Naglieri General Ability Tests (NGAT)**, the abilities test Houston ISD uses for Gifted & Talented testing from Pre-K4 through 8th grade. It runs in the web browser on an iPad or phone, with nothing to install.

The goal is to make the child comfortable with the **touchscreen mechanics** and the **format of the real test**. Questions are made up fresh every time, so they can't be memorized.

## What's in it

**Your slide's three examples are built in exactly.** At the start of each part, the wordless how-to animation solves the example from HISD's parent presentation:
- **Verbal:** banana, pear, orange, **chair**, peach, apple. The chair doesn't belong.
- **Nonverbal:** the half-colored tiles. The top tile turns a quarter turn, so the answer is **1**.
- **Quantitative:** 6 7 8 9 ?, with answers 12, 10, 13, 9 and 11. The answer is **B (10)**.

### Topics covered

| Part | What the real test covers | Question types in this app |
|---|---|---|
| **Verbal** (blue) | Six pictures. Find the one that doesn't share the idea the other five share. | Ideas based on **groups** (fruit, animals, vehicles, clothes, tools, buildings…), **where things live** (land vs. water), **what things do** (fly, give light, make music, draw or write) and **how things look** (red, yellow, round, cold). |
| **Nonverbal** (purple) | Relationships among shapes: color, order and which way they face. The Naglieri Nonverbal test families are pattern completion, reasoning by analogy, serial reasoning and spatial visualization. | **Missing piece** (pattern completion)<br>**2×2 puzzles** (analogy), including the slide's half-colored tiles that turn, trade colors or change the inside shape<br>**3×3 grids** (serial reasoning: sizes, shapes, colors, counts, turning)<br>**Put together** (spatial: two pictures combine to make the third) |
| **Quantitative** (green) | Numbers and shapes in a pattern, using basic math. | **Number rows** (up or down by 1 or 2, repeating patterns)<br>**Dot and shape rows**<br>**Boxes of objects** (1 gift, 2 gifts…)<br>**Number pairs** (3→4, so 6→?)<br>**Dots ↔ numbers** (counting)<br>**3×3 number grids** (counting up, each row has one of each, adding) |

Questions get harder through each part, the way the real test does.

## Matches the real test

- **Same look as the slide:** each part's screen copies its example's layout and colors. The colored frame, gray panel, tile sizes and spacing, number strip, bold 1–5 and A–E labels and small gray arrows were measured from the screenshots and scaled up. The fruit example uses flat clip art like the slide.
- **40 questions** per part with a **30-minute** limit. Both can be changed in Grown-ups.
- **Wordless animated directions.** A hand shows how to pick an answer and touch the arrow.
- **3 practice questions** that she has to get right. If she picks wrong, the hand points to the right answer. Practice questions are the only place the app helps her.
- **No right or wrong feedback** during the real questions.
- **Skip and come back** with the arrows. A **review screen** at the end shows answered (blue) and skipped (white) questions.
- If time runs out, it goes straight to the review screen.
- **No voice in the test parts**, because the real test has no spoken words. A grown-up can turn on read-aloud. Touch Practice always talks.

## Grown-ups area

On the home screen, **press and hold "Grown-ups"** for one second. From there you can:
- Change the number of questions, the time limit, the practice questions and read-aloud.
- See results: the score and time for each part, and each question with her answer (blue) and the correct answer (green), plus a short explanation.

Results are saved only on that device. During a test, exiting requires **press and hold "Hold to exit,"** so she can't leave by accident.

## Putting it online (one time)

1. On github.com, open this repo → **Settings** → **Pages**.
2. Under "Build and deployment", set Source to **Deploy from a branch**. Pick the branch `claude/ipad-practice-app-brainstorm-posyda` and the **/ (root)** folder, then tap **Save**.
3. After a minute or two the site is live at **https://applesandbeer.github.io/Octopus/**

## Putting it on the iPad

1. Open the link in **Safari**.
2. Tap **Share**, then **Add to Home Screen**.
3. Open it from the new "Puzzles" icon. It runs full screen like an app.

Tips:
- **Keep her inside the app:** turn on Guided Access (Settings → Accessibility → Guided Access). Then triple-click the Home button (or the top button) while the app is open.
- **No voice in Touch Practice?** Turn the volume up and check that the iPad isn't muted.
- **On a phone,** turn it sideways for bigger pictures.

## Technical notes

- Everything is in `index.html`: plain HTML, CSS and older-style (ES5) JavaScript, so it also runs on older iPads. There are no outside downloads.
- The pictures are built-in emoji and drawn shapes.
- These are practice questions in the style of the test, not real test questions.
