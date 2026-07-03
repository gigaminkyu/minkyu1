# LLM-WIKI.md

A personal knowledge base that **maintains itself**. You curate sources and ask
questions; the model files, links, summarizes, and reconciles. The wiki is a
*compiled artifact* that compounds — not a pile of notes that grows.

This repo is an implementation of the pattern described in *LLM-WIKI.md: Field
Notes on a Knowledge Base That Maintains Itself* (Karpathy, 2026). The full
manifesto is ingested as the first source at
[`raw/2026-07-03-llm-wiki-field-notes.md`](raw/2026-07-03-llm-wiki-field-notes.md).

## How it works

Three layers, three owners:

- **`raw/`** — immutable sources. You drop files here; they are never edited.
- **`wiki/`** — compiled pages. The model owns and regenerates these.
- **`CLAUDE.md`** — the schema (rules). Shared. This is what turns a folder of
  markdown into a self-maintaining system; open it to see the full ruleset.

It is **not RAG.** Sources are compiled once into structured, linked pages, and
questions are answered from that built artifact rather than re-derived from raw
chunks every time. `raw/` is source code, the model is the compiler, `wiki/` is
the executable.

## Using it

Open this repo in Claude Code (or any agent that reads `CLAUDE.md`) and:

- **Add knowledge** — drop a file into `raw/` and say *"ingest the new source."*
  The model traces it across the whole graph, not just one page.
- **Ask a question** — the model starts at [`wiki/index.md`](wiki/index.md),
  follows the relevant links, and synthesizes an answer.
- **Keep it healthy** — say *"lint the wiki"* to surface contradictions, orphan
  pages, entity drift, and a stale index.

## Start small

Begin with ~10 sources, not 10,000. Get ingest, query, and lint to feel natural
before adding a search engine or an elaborate schema. A small wiki you actually
feed beats a beautiful architecture you abandon in week three.

## Layout

```
CLAUDE.md          # the schema / rules (read this)
raw/               # immutable sources you add
wiki/
  index.md         # navigation hub — every query starts here
  <entity>.md      # one compiled page per entity/topic
```
