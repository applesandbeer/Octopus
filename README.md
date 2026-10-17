# Puzzle Practice

A practice app for young children getting ready for the **Naglieri General Ability Tests (NGAT)**, the abilities test Houston ISD uses for Gifted & Talented testing from Pre-K4 through 8th grade. It runs in the web browser on an iPad or phone, with nothing to install.

The goal is to make the child comfortable with the **touchscreen mechanics** and the **format of the real test**. Questions are made up fresh every time, so they can't be memorized.

## What's in it

| Part | Question types |
|---|---|
| **Touch Practice** | Spoken coaching: tap stars, use the next and back arrows, change an answer. |
| **Verbal** (blue box) | Six pictures numbered 1–6. Five share an idea (fruit, things that fly, cold things…) and she touches the one that doesn't belong. |
| **Nonverbal** (purple box) | Three types, answers numbered 1–5:<br>• **Missing piece:** a big pattern with a square cut out.<br>• **2×2 puzzle:** the top pair changes in some way, and the bottom pair should change the same way.<br>• **3×3 grid:** for example, each row has a small, a medium and a big circle. |
| **Quantitative** (green box) | Answers labeled A–E:<br>• **Rows:** numbers, dots, shapes or boxes of objects (1 gift, 2 gifts, 3 gifts…) where she picks what comes next.<br>• **Number pairs:** 3 goes to 4, so 6 goes to ?<br>• **3×3 number grids.** |

## Matches the real test

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
