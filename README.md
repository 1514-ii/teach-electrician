# Teach Electrician

HTML-first learning workspace for electrician practical-exam study with ChatGPT teach-lite support and Codex-generated lessons.

## Structure

- `MISSION.md`: learning mission and success criteria
- `SKILL.md`: workspace operating rules
- `RESOURCES.md`: trusted sources and private source notes
- `LEARNING_STATE.md`: current level, latest lesson, and next actions
- `NOTES.md`: teaching preferences and working notes
- `lessons/`: self-contained HTML lessons
- `reference/`: review cheat sheets
- `docs/`: GitHub Pages public HTML site
- `learning-records/`: demonstrated learning records
- `assets/`: reusable lesson assets
- `sync/`: mobile ChatGPT handoff files

## HTML-First Rule

The default learning output is `lessons/*.html`. Markdown is only a fallback or a compact helper for ChatGPT conversation.

Public pages live in `docs/` so the site can be viewed from company devices and mobile browsers through GitHub Pages.

Only public-safe content should be copied into `docs/`:

- problem summaries
- solution flow
- formulas
- wrong-answer points
- self-made variant questions

Do not publish PDF originals, paid textbook originals, full copied past-exam question sets, work documents, or personal information.

## Source Material Rule

Do not commit paid PDFs, private work materials, personal information, or raw copied source files.

Use ignored local folders for originals and describe only the source name, purpose, and location in `RESOURCES.md`.

## Next Steps

1. Clarify the learner's concrete electrician goal.
2. Add trusted resources to `RESOURCES.md`.
3. Create the first five-problem HTML lesson in `lessons/`.
4. Copy the public-safe version to `docs/lessons/`.
5. Add reusable cheat sheets to `reference/` and `docs/reference/`.
