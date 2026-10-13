# Repository Guidelines

## Project Purpose

This repository supports a 15-day IELTS Academic preparation plan targeting an overall band of 5.5. The learner has a TOEIC score of 960 and previous IELTS practice. Prioritize restoring test familiarity, assessing current performance, and improving Writing and Speaking alongside timed Listening and Reading practice.

## Project Structure & Organization

The repository contains Markdown study materials and has no application code or automated tests. Use the following structure when adding content; create directories only as needed:

- `plan/`: the 15-day schedule and daily checklists.
- `practice/YYYY-MM-DD/`: exercises, written responses, and feedback grouped by the actual practice date (Korea Standard Time).
- `notes/`: skill-specific strategies, vocabulary, and recurring mistakes.
- `progress/`: practice scores, timing, and review logs.
- `materials/`: local books, PDFs, and audio; excluded from Git.
- `assets/`: original or authorized supporting images and recordings.

Keep this guide in the repository root. Add a `README.md` when study materials need an entry point.

## Development & Review Commands

No build system, package manager, or automated test framework is configured. Useful commands are:

- `git status --short`: inspect changed and untracked files.
- `git diff`: review edits to tracked files.
- `git diff --check`: detect whitespace errors in staged or unstaged tracked changes.
- `rg --files`: list repository content.

Preview Markdown before submitting changes. If code is introduced, document its setup and verification commands alongside it.

## Style & Naming Conventions

Use Markdown for plans, notes, and feedback. Use descriptive headings, short paragraphs, and actionable checklists. Use lowercase, hyphenated filenames, such as `writing-task-2.md`, and ISO date directories, such as `practice/2026-10-12/`. Record study-day numbers inside files when useful. Use two spaces for nested list indentation. No formatter or linter is currently configured.

Communicate with the learner in Vietnamese in chat. Write all repository content in English, including documentation, instructions, feedback, headings, and comments.

## Validation Guidelines

Check exercise instructions, answer keys, links, and score calculations. Distinguish estimated practice bands from official results. Cite authoritative sources for IELTS scoring and test requirements. No automated coverage requirement applies.

## Commit & Pull Request Guidelines

There is no commit history or established message convention. Use short, imperative messages, such as `Add day 01 diagnostic exercises`. Keep changes focused. Pull requests should describe the learning objective, changed materials, and validation performed. Link relevant issues when available; include screenshots only for visual changes.

## Content & Privacy

Do not commit credentials, exam registration details, or personal identification. Link to copyrighted practice resources rather than copying complete tests without permission.
