# Teach Workspace Skill: Electrician

This repository is a stateful learning workspace for ChatGPT teach-lite study and Codex-generated HTML lessons.

## Mission First

Before creating lessons, read `MISSION.md`, `LEARNING_STATE.md`, `RESOURCES.md`, `NOTES.md`, and recent files in `learning-records/`.

If the mission is vague, ask the learner one short question before teaching. Every lesson should trace back to the mission.

## Workspace Map

- `MISSION.md`: why this course exists and what success looks like.
- `RESOURCES.md`: trusted source list. Do not store paid PDFs, work documents, or personal source material in Git.
- `LEARNING_STATE.md`: current level, next step, and active learning thread.
- `NOTES.md`: teaching preferences and short working notes.
- `lessons/`: self-contained HTML lessons.
- `reference/`: review cheat sheets and printable quick references.
- `docs/`: public GitHub Pages site. Only public-safe HTML belongs here.
- `learning-records/`: short records of demonstrated understanding.
- `assets/`: reusable lesson CSS, scripts, diagrams, and images.
- `sync/`: compact mobile summaries for ChatGPT.

## Lesson Rules

1. Create one small lesson at a time.
2. Save HTML lessons in `lessons/NNNN-dash-case-title.html`.
3. Link shared CSS or scripts from `assets/`; avoid build steps.
4. Include quick retrieval practice, not only explanation.
5. Link to relevant reference sheets in `reference/`.
6. Cite trusted resources from `RESOURCES.md`.
7. Update `LEARNING_STATE.md` and `sync/CHATGPT_PROJECT_UPDATE.md` after meaningful progress.
8. Treat Markdown lesson files as fallback or ChatGPT conversation helpers only.
9. For electrician practical-exam study, build lessons around five problems per day.
10. Include button-style quizzes and immediate feedback in each lesson.

## Public Site Rules

Use `docs/` for GitHub Pages. The public site should mirror only content that is safe to publish.

- Author lessons in `lessons/*.html`.
- Author cheat sheets in `reference/*.html`.
- Copy public-safe lessons to `docs/lessons/`.
- Copy public-safe references to `docs/reference/`.
- Keep shared styles in both `assets/style.css` and `docs/assets/style.css`.
- Do not publish full original problems, paid source text, PDF originals, or private materials.
- Public HTML can include problem summaries, solution flow, formulas, wrong-answer points, and self-made variant questions.

## Reference Rules

Create cheat sheets in `reference/` when knowledge will be reused across lessons.

Good reference files are short, printable, and practical:

- formulas
- safety rules
- process checklists
- glossary-style term maps
- troubleshooting flowcharts

## Learning Records

Write `learning-records/NNNN-dash-case-title.md` only when the learner demonstrates understanding, corrects a misconception, or changes the mission.

Do not use learning records as a session diary.

## Source Material Safety

Do not commit paid PDFs, private work material, personal data, screenshots with private data, or copied source archives.

Keep raw material outside Git or in ignored folders such as:

- `source-materials/`
- `raw-materials/`
- `private-materials/`
- `paid-pdfs/`

In `RESOURCES.md`, record only the material name, purpose, and local/private location description.

## ChatGPT Mobile Sync

`sync/CHATGPT_PROJECT_UPDATE.md` is the handoff file for mobile ChatGPT. Keep it short:

- mission
- current level
- latest lesson/reference
- next 1-3 actions
- restrictions on source materials

`sync/mobile_lesson.md` is for a compact text-only lesson or review prompt that can be used on mobile.
