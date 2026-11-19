# Wonder Island 🏝️

A 3D learning game for ages 5–13. Walk around a small island; each building is a school subject.
Step inside to enter a 3D "stage" with a quiz, hear questions read aloud, and earn stars.

**Play:** open `index.html` in any modern browser (works offline; Three.js is bundled). Or serve the folder, e.g. `python3 -m http.server`.

## Subjects (10 zones × 3 levels)
Math · Reading & Words · Science · Space · World & History · Art & Color · Music · Body & Health · Coding & Logic · **AI Lab** (what AI is, training data, bias, hallucinations, privacy)

Levels: **Sprout** (5–7), **Ranger** (8–10), **Pioneer** (11–13). Each round can be replayed at an easier or harder level. Math questions are generated fresh each time.

## Controls
Arrow keys / WASD, or drag on screen. Tap the ground to walk there. Press Enter/Space (or the button) to enter a building. In quizzes, keys 1–3 pick answers.

## Kid-friendly by design
No accounts, ads, or network calls. Progress is saved only in the browser's localStorage. Read-aloud uses the browser's built-in speech.

## Extending
Questions live in `SUBJECTS` in `index.html` as `Q(question, correct, wrong1, wrong2, funFact, viz3D)`. `viz3D` picks the 3D object shown on stage (see `vizBuild`).
