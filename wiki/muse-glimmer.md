---
title: Muse Glimmer
type: tool
updated: 2026-09-27
sources: [raw/2026-09-27-meta-muse-web-research.md]
confidence: medium
---

# Muse Glimmer

An **open-weight**, **30B-parameter**, **Apache 2.0** model released by Meta on
**2026-08-10**. It is a distillation of [[Muse Spark]], built for always-on
**local agents** on one consumer GPU or a Mac, with no network call. It takes
text and images and targets coding, document analysis and multi-step tool
use.

- It is quantized to about 4-bit and uses block-level speculative decoding,
  which keeps it fast enough for an agent loop.
- Weights are on Hugging Face. It is supported by Ollama, LM Studio, vLLM,
  SGLang, Together AI, Fireworks AI and OpenRouter, with optimized llama.cpp,
  MLX and ExecuTorch builds.
- Coverage (VentureBeat) calls it Meta "returning to open source" after Muse
  Spark's closed release.

## Links
- [[Muse Spark]]: the parent model it is distilled from
- [[Meta Superintelligence Labs]]: the Muse family's maker
- [[Meta Muse]]: a contrast. Muse is a cloud-hosted agent; Glimmer is for local agents.

## Sources
- `raw/2026-09-27-meta-muse-web-research.md`: §5. Search-summary capture, not full text.
