---
title: Ingest Workflow
type: concept
updated: 2026-07-03
sources: [raw/2026-07-03-llm-wiki-field-notes.md]
confidence: high
---

# Ingest Workflow

How a single source becomes part of the graph (Rules 5, 6, 9).

**One source at a time** (Rule 5). Drop a single file into `raw/` and ingest it.
A good ingest is *not* one new page — it is tracing the implications of that
source across the graph, touching every page the new fact changes. Batch-importing
your whole digital life at once produces a dump, not a wiki, because nothing gets
linked while the pile is still forming.

**Link everything** (Rule 6). Every page connects to others through wikilinks,
and every wikilink is a visible edge. An entity that appears in five pages but
links to none signals a lazy ingest. The value is in the edges, not the nodes —
which is why a graph front-end (e.g. Obsidian) is useful for spotting clusters,
hubs, and orphans.

**Start small** (Rule 9). Begin with ~10 sources, not 10,000. The first few
ingests need supervision; naming conventions will change and early pages will be
messy, and that is normal. A small wiki you actually feed beats a beautiful
architecture abandoned in week three.

The concrete step-by-step procedure lives in the schema (`CLAUDE.md` →
*Ingest workflow*). Every ingest ends by updating the index and running
[[Linting the Wiki]].

## Links
- [[LLM-Maintained Knowledge Base]] — the system fed by ingestion
- [[Compile Not Retrieve]] — ingest is the compilation step
- [[The Three Layers]] — ingest moves content from `raw/` into `wiki/`
- [[Linting the Wiki]] — the check that closes every ingest

## Sources
- `raw/2026-07-03-llm-wiki-field-notes.md` — §V Ingest One Source at a Time; §VI Link Everything; §IX Start Small
