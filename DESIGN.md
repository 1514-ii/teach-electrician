# Design System

## Direction

Use a PostHog-inspired warm retro browser-window style for all public HTML pages.
Do not copy PostHog brand assets, mascot, copy, or illustrations. Reuse only the general design language.

Reference:
https://styles.refero.design/style/56cd3725-3ff0-459e-894d-5da58d1fc549

## Core Rules

- Public pages use a warm beige desktop background.
- Main content sits inside a white browser-window frame.
- Use compact spacing, flat surfaces, thin borders, and 4px corners.
- Use cobalt blue only for links, focus states, and active accents.
- Use amber only for small tags and low-frequency emphasis.
- Keep study content readable first; decoration must not compete with formulas or quizzes.
- Do not use PostHog-specific characters, mascots, product copy, or trademarked visual assets.

## Tokens

- Background: `#e1d7c2`
- Browser surface: `#ffffff`
- Paper surface: `#fdfdf8`
- Linen surface: `#eeefe9`
- Border: `#d2d3cc`
- Heading: `#111827`
- Body: `#4d4f46`
- Muted text: `#65675e`
- Cobalt accent: `#2f80fa`
- Amber accent: `#f1a82c`
- Ember accent: `#f54e00`
- Fern accent: `#6aa84f`

## Implementation

- Source stylesheet: `assets/style.css`
- Public stylesheet: `docs/assets/style.css`
- Keep both stylesheets synchronized.
- Public HTML pages should wrap content with:
  - `.site-shell`
  - `.browser-window`
  - `.browser-titlebar`

## Lesson Guidance

- New HTML lessons should link to the shared stylesheet.
- New public lesson copies in `docs/lessons/` should use the browser-window wrapper.
- Quizzes should use `.quiz-options`, `.quiz-button`, and `.feedback`.
- Tables should use `.table-wrap`.
