# AGENTS.md

## Project

Single-file static HTML app: `monopoly-bank.html`. No build system, no dependencies, no server required. Runs in any browser via `file://` or localhost.

## Commands

- **Open**: double-click `monopoly-bank.html` or serve with any static server.
- **No install, no build, no test runner.**

## Architecture

All HTML, CSS, and JavaScript live in one file. State is in-memory only (`players[]`, `logs[]`) — refresh resets everything. No persistence, no external APIs.

## Conventions

- Spanish UI text throughout.
- Currency amounts use `$` prefix with `toLocaleString()` formatting.
- No comments in code unless asked.
- Design style: vintage cartoon / classic Mickey Mouse aesthetic with warm brown/gold palette.
