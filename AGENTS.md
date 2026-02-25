# AGENTS.md

Guidance for AI coding agents working in this repository.

## Repository overview

- This project is a static web app.
- Main app file: `index.html`.
- Docs and meta files: `README.md`, `LICENSE`, this `AGENTS.md`.

## Working agreement

- Keep changes minimal and easy to review.
- Prefer small, focused commits with clear messages.
- Do not add heavy frameworks or build tooling unless explicitly requested.
- Preserve accessibility-focused design choices (high contrast, large controls, simple interactions).

## Local validation

For documentation-only changes:

- Confirm markdown renders cleanly.
- Verify links, commands, and filenames are correct.

For app changes:

- Open `index.html` in a browser and verify interactions still work.
- Ensure swipe, play/pause, and pagination behaviors are not broken.

## Style notes

- Use clear, plain English in documentation.
- Keep README instructions copy-paste friendly.
- Keep JavaScript broadly compatible with older/mobile browsers when editing app logic.

## PR expectations

- Include a concise summary of what changed and why.
- List checks you ran.
- If UI changes are made, include a screenshot when possible.
