# AGENTS.md

This repository is a personal markdown wiki. The repo itself is the durable artifact.

## Purpose

Maintain a lightweight, expressive, personal knowledge base for 孙浩然. The goal is not exhaustive documentation. The goal is to preserve a small number of stable entrypoints, keep them readable, and let them grow over time.

## Core structure

- `README.md`: homepage / personal dashboard
- `wiki/now.md`: current action-oriented snapshot answering "我最近在做什么"
- `wiki/timeline.md`: chronological index of life stages and turning points
- `wiki/sections/life.md`: life notes and themes
- `wiki/sections/learning.md`: learning topics, sources, and synthesis
- `wiki/sections/work.md`: work projects, responsibilities, and reflections
- `wiki/sections/thinking.md`: longer-form ideas, questions, and worldview notes
- `wiki/index.md`: catalog of wiki pages
- `wiki/log.md`: append-only maintenance log
- `raw/`: immutable raw source materials

## Writing principles

1. Prefer small markdown files over large monoliths.
2. Keep the homepage expressive but stable.
3. `Now` should stay lightweight. A paragraph is enough.
4. Timeline is an index, not the main storage layer.
5. The four section pages are the main trunks that can branch into more notes later.
6. Preserve mixed Chinese-English naming when it improves readability.
7. When adding new pages, update `wiki/index.md` and append a short note to `wiki/log.md`.

## Maintenance workflow

### Ingest

When adding new source material:

1. Store the raw material under `raw/` if it should be preserved.
2. Extract the useful ideas into one or more wiki pages.
3. Update cross-links from relevant section pages.
4. Update `wiki/index.md`.
5. Append an entry to `wiki/log.md`.

### Query

When answering questions from the wiki:

1. Start from `README.md` and `wiki/index.md`.
2. Follow links into the most relevant section pages.
3. Prefer synthesizing into durable markdown when the result feels reusable.

### Lint

Periodically check for:

- orphan pages without links
- stale summaries in section pages
- timeline items that should link into deeper notes
- repeated ideas that deserve their own dedicated page

## Style

- Keep prose calm, direct, and readable.
- Avoid over-engineering the taxonomy early.
- Favor durable headings and low-maintenance structure.
- Treat this repo like a living wiki, not a static document dump.
