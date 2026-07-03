---
title: Linting the Wiki
type: concept
updated: 2026-07-03
sources: [raw/2026-07-03-llm-wiki-field-notes.md]
confidence: high
---

# Linting the Wiki

Treat the wiki like code and run health checks (Rule 8). The model is asked to:

- **find contradictions** between pages;
- **surface low-confidence claims**;
- **flag entities that drifted into two spellings** (and merge them);
- keep the **index honest** so navigation stays fast (Rule 7).

A contradiction is **information, not an error** to paper over: it usually means
two sources disagree, and now you know where to look. Skipping the lint is how a
wiki quietly rots while the graph still looks impressive.

Linting is also what keeps [[Compile Not Retrieve]] viable: navigation by index
only works while the index reflects the territory. It is the closing step of
every [[Ingest Workflow]].

## Links
- [[LLM-Maintained Knowledge Base]] — the system this keeps trustworthy
- [[Ingest Workflow]] — lint runs at the end of each ingest
- [[Compile Not Retrieve]] — lint keeps the index (and thus navigation) honest

## Sources
- `raw/2026-07-03-llm-wiki-field-notes.md` — §VIII Lint the Knowledge; §VII Navigate by Index
