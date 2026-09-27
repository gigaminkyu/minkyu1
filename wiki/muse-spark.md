---
title: Muse Spark
type: tool
updated: 2026-09-27
sources: [raw/2026-09-27-meta-muse-web-research.md]
confidence: medium
---

# Muse Spark

The first large language model from [[Meta Superintelligence Labs]], launched
**2026-04-08**. It heads Meta's **Muse** model family and powers Meta AI across
the Meta AI app, meta.ai, Facebook, Instagram, WhatsApp, Messenger and the
Ray-Ban Meta glasses. It also runs the [[Meta Muse]] agent.

- **Design:** "small and fast by design," multimodal, with a **1M-token**
  context.
- **Reasoning modes:** Instant, Thinking, and Contemplating. Contemplating
  runs multiple agents in parallel.
- **Versions:** 1.0 in April 2026, then **1.1** on 2026-07-09 (Fortune). A
  third party reports **1.3** behind Muse, which is unconfirmed.
- **Closed weights:** this is the first Meta frontier model *not* released as
  open weights, a pivot away from the Llama strategy. Meta said it may offer
  API access to select partners and hopes to open-source later versions.
  [[Muse Glimmer]] later filled that open-weight gap in part.
- **Benchmarks (Artificial Analysis):** Intelligence Index **52**, compared
  with Llama 4 Maverick at 18 and Scout at 13 on their release. It leads on
  health (HealthBench Hard 42.8 vs GPT-5.4's 40.1) and is strong on visual
  reasoning (MMMU-Pro 80.5%, second to Gemini 3.1 Pro).

## Contradiction ⚠
- Wikipedia (via search summary) says it was **designed for coding and
  AI-assisted software development**.
- Artificial Analysis says it **falls short in coding and agentic work**.

These may both be true, since design intent is not measured result. Either
way, a model that benchmarks weak on agentic work powers Meta's flagship
*agent*. Flagged, not resolved.

Wikipedia's wording ("introduced in April 2026, launching as Muse Spark 1.1 on
July 9") also blurs the launch date with the 1.1 update. Fortune treats 1.1 as
an update, and this page follows Fortune.

## Links
- [[Meta Superintelligence Labs]]: the lab that built it
- [[Meta Muse]]: the agent it powers
- [[Muse Glimmer]]: the open-weight model distilled from it

## Sources
- `raw/2026-09-27-meta-muse-web-research.md`: §4. Search-summary capture, not full text.
