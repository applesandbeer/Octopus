# Puzzle Practice

A practice app for young children getting ready for a picture-based abilities test, like the CogAT (Cognitive Abilities Test) that Houston ISD uses for Gifted & Talented testing. It runs in the web browser on an iPad or phone. There's nothing to install.

The main goal is to make the child comfortable with the **touchscreen mechanics**: tapping an answer, changing an answer, and using the gray arrows to move between questions. The questions are new each time, so they can't be memorized.

## What's in it

| Part | Looks like | What the child does |
|---|---|---|
| **Touch Practice** | Stars, then a practice page | Learns to tap, change an answer, and use the next and back arrows. The voice coaches each step. |
| **Verbal** (blue box) | 6 pictures, numbered 1–6 | Touches the one picture that doesn't belong. |
| **Nonverbal** (purple box) | 2×2 shape puzzle with a "?" and answers numbered 1–5 | Touches the shape that completes the pattern. |
| **Quantitative** (green box) | A row like `6 7 8 9 ?` with answers labeled A–E | Touches what comes next (numbers, dots or shapes). |

How it works, kept close to the real test:
- **No right or wrong feedback.** Choosing an answer only highlights it.
- The directions are read aloud by the iPad's built-in voice. The speaker button repeats them.
- Each part starts with one practice question. The voice explains its answer, the way the real test's practice questions do. You can turn this off.
- Questions get harder through each part. There's no time limit.
- A "Stop" screen appears at the end of each part.

## Grown-ups area

On the home screen, **press and hold "Grown-ups"** for one second. From there you can:
- Choose 6, 10, 14 or 18 questions per part.
- Turn read-aloud and the practice question on or off.
- See results: the score, the time taken, and each question with her answer (blue) and the correct answer (green).

Results are saved only on that device. During a test, the child can't leave by accident: exiting requires **press and hold "Hold to exit."**

## Putting it online (one time)

1. On github.com, open this repo → **Settings** → **Pages**.
2. Under "Build and deployment", set Source to **Deploy from a branch**. Pick this branch and the **/ (root)** folder, then tap **Save**.
3. After a minute or two the site is live at **https://applesandbeer.github.io/Octopus/**

## Putting it on the iPad

1. Open the link in **Safari**.
2. Tap the **Share** button, then **Add to Home Screen**.
3. Open it from the new "Puzzles" icon. It runs full screen like an app.

Tips:
- **No voice?** Turn the volume up and check that the iPad isn't muted.
- **Keep her inside the app:** turn on Guided Access (Settings → Accessibility → Guided Access). Then triple-click the Home button (or the top button) while the app is open.
- **On a phone,** turn it sideways for bigger pictures.

## Technical notes

- Everything is in `index.html`: plain HTML, CSS and older-style JavaScript, so it also runs on older iPads. There are no outside downloads.
- The pictures are built-in emoji and drawn shapes, so they show up even on older devices.
