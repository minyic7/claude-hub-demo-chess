# claude-hub-demo-chess — Vision

## Goal

A playable chess game in the browser. Single HTML file, zero dependencies. Deployed to GitHub Pages. Built entirely by Claude Code — assets, rules, UI design, and gameplay all self-contained.

Phase 2: Add a single-player mode with a basic AI opponent, keeping the zero-dependency single-file architecture.

## Scope

### In Scope
- Single `index.html` — all HTML, CSS, JS in one file, zero dependencies, zero build step
- Standard chess rules — all piece movements, check, checkmate, stalemate
- Two-player local mode — human vs human on the same screen
- Chess pieces rendered in Unicode or SVG — no external image files
- GitHub Pages deployment — push to main → live
- AI opponent — minimax search with 3–4 move lookahead, single difficulty level, integrated into the existing single-file architecture (promoted from Out of Scope)

### Out of Scope
- AI opponent
- Online multiplayer
- Move history export
- Chess clock

## Milestones

- [ ] Playable chess board with all pieces rendered
- [ ] Full chess rules implemented (movement, check, checkmate)
- [ ] Two-player local gameplay working end to end
- [ ] Deployed and live on GitHub Pages

---

<!-- KANBAN_CC_RULES:
  - Goal and Scope are the source of truth for all ticket planning.
  - In writable mode, CC may APPEND to Goal and Scope sections only.
  - CC must NEVER modify or remove existing content in any section.
  - CC must NEVER touch Milestones — only the user manages milestones.
  - In readonly mode, CC proposes amendments in the Step 10 report.
-->
