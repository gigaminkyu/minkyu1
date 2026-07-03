---
title: Compile Not Retrieve
type: concept
updated: 2026-07-03
sources: [raw/2026-07-03-llm-wiki-field-notes.md]
confidence: high
---

# Compile Not Retrieve

The defining design choice (Rule 4): this is **not RAG**. Retrieval-augmented
generation re-derives an answer from raw chunks on every query and accumulates
nothing. Here, sources are compiled **once** into structured, linked pages, and
questions are answered from that built artifact.

The compiler analogy:

- `raw/` is **source code** — see [[The Three Layers]]
- the model is the **compiler**
- `wiki/` is the **executable**
- queries are **runtime**

Knowledge that is compiled *compounds*; knowledge that is retrieved is
*rediscovered* each time. Because answers come from the compiled artifact, the
model navigates by reading the index and following a few pages rather than
loading the whole vault (Rule 7 — see [[Linting the Wiki]] for keeping the index
honest). Compilation happens through the [[Ingest Workflow]].

## Links
- [[LLM-Maintained Knowledge Base]] — the system this principle powers
- [[The Three Layers]] — supplies the source/compiler/executable mapping
- [[Ingest Workflow]] — the act of compiling a source into pages

## Sources
- `raw/2026-07-03-llm-wiki-field-notes.md` — §IV Compile, Don't Retrieve; §VII Navigate by Index
