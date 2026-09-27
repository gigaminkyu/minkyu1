# Meta Muse — Web Research Capture

> Source captured 2026-09-27 at the human's request ("너도 메타 뮤즈 탐색해봐라").
> This is an immutable source (Rule 1) — do not edit; add a correcting source
> if needed.
>
> **Capture method and limits.** Direct page fetches were blocked by the
> session's network egress proxy (about.fb.com, techcrunch.com, axios.com,
> cnbc.com, en.wikipedia.org). Everything below is transcribed from **web
> search result summaries**, not from reading the full articles. Each claim
> lists the URL(s) the search engine attributed it to. Treat this capture as
> secondary: a full-text source for any of these URLs supersedes it.

---

## 1. Muse (the personal AI agent)

- Meta launched **Muse**, a personal AI agent, on **2026-09-08**.
  — https://www.axios.com/2026/09/08/meta-debuts-muse-personal-ai-agent ,
  https://about.fb.com/news/2026/09/introducing-muse-personal-ai-agent/
  (Meta's own headline: "Introducing Muse: The World's First Personal AI Agent
  Built for Everyone")
- Muse works across a user's devices and digital accounts, lives in a
  chat interface "similar to a text thread," and is designed to be more
  proactive and long-running than typical chatbots. It can do tasks like
  sending an email or booking travel, and "can take on big audacious goals."
  — https://techcrunch.com/2026/09/25/meta-is-putting-its-muscle-behind-muse-as-the-ai-app-takes-off/ ,
  https://techcrunch.com/2026/09/08/meta-debuts-its-muse-ai-agent-will-consumers-trust-it/
- Claimed tasks: manage a schedule, draft and send email, book travel, compare
  prices, shop, fill out forms, sell cars, lower bills, and check out with a
  one-time card — from its own app or inside WhatsApp.
  — https://www.eesel.ai/blog/meta-muse-agent-review ,
  https://www.aitrove.ai/blog/meta-muse-personal-ai-agent-launch-2026
- **Powered by Muse Spark.** One aggregator says it runs on **Muse Spark 1.3**.
  — https://www.eesel.ai/blog/meta-muse-agent-review (third-party; version
  number not confirmed by a first-party source in this capture)
- **Security architecture** (as described in search summaries):
  - Muse runs in an isolated cloud computer.
  - A separate guard agent called **Sentinel** runs on the same machine, kept
    apart at the system level; nothing Muse does reaches the internet unless
    Sentinel approves it.
  - Passwords sit in a vault the agent cannot see into.
  — https://www.eesel.ai/blog/meta-muse-agent-review ,
  https://explainx.ai/blog/meta-muse-personal-agent-launch-sentinel-vm-security-2026
- **Pricing:** free tier plus paid plans at **$20/month** and **$100/month**.
  One aggregator says the free tier covers up to 100 million tokens per week.
  — https://techcrunch.com/2026/09/08/meta-debuts-its-muse-ai-agent-will-consumers-trust-it/ ,
  https://tech-insider.org/meta-muse-personal-ai-agent-launch-2026/ (token
  figure: third-party only)
- **Availability:** US-only, 18+. Launched on iOS, Android and the web, with
  WhatsApp as another way to message it.
  — https://www.fieldy.ai/blog/meta-muse , https://www.meta.com/blog/meta-connect-2026-everything-we-announced/
- **Adoption:** Muse passed 2.5 million downloads since its 2026-09-08 launch
  (as of the start of the week of 2026-09-21), and the app had "more than 3.4
  million downloads" by 2026-09-25.
  — https://techcrunch.com/2026/09/25/meta-is-putting-its-muscle-behind-muse-as-the-ai-app-takes-off/

## 2. Meta Connect 2026 (2026-09-23) — Muse announcements

- **Mac app control:** with permission, Muse can drive any app on a Mac and
  keep working while the user is away.
  — https://www.zeniteq.com/meta-muse-adds-mac-app-control-previews-live-avatar-us6rmj ,
  https://www.meta.com/blog/meta-connect-2026-everything-we-announced/
- **Real-time voice and an animated avatar** for Muse.
  — https://marketing4eCommerce.net/en/meta-muse-announcements/ ,
  https://www.nbcnews.com/tech/tech-news/meta-muse-ai-agent-response-animated-avatar-cute-rcna599736
- **New connectors / partners:** shopping — Walmart, Best Buy, American Eagle
  Outfitters, DICK'S Sporting Goods, Fanatics, Gap, Michael Kors, Sephora, Ulta,
  Wayfair; travel — Expedia; groceries — Instacart; work — Notion, Granola,
  GitHub, Box.
  — https://www.meta.com/blog/meta-connect-2026-everything-we-announced/
- **Muse Charm** — a pocket/keychain-sized device unveiled at Connect: 2-inch
  OLED screen, front camera, built-in 5G modem, "quasi-Tamagotchi" personality.
  Packs "the whole Muse experience, including the whole real-time voice and
  avatar stack, into something that fits on a keychain." Zuckerberg: "planning
  to have this ready to ship in time for the holidays in December." No price
  announced. Reported as beating OpenAI's expected consumer device reveal by
  about a week.
  — https://techcrunch.com/2026/09/23/meta-made-a-tamagotchi-like-wearable-for-its-muse-ai-agent/ ,
  https://www.cnbc.com/2026/09/24/meta-mark-zuckerberg-muse-charm-openai-agent.html ,
  https://newatlas.com/consumer-tech/meta-muse-ai-agent-charm/
- Also at Connect: **$1,299 Meta VR Glasses**; Muse is being integrated into
  Meta's AI glasses line.
  — https://www.cnbc.com/2026/09/23/mark-zuckerberg-1299-meta-vr-glasses-ai-agent.html
- CNBC framing: Meta got to the consumer AI device market before OpenAI, "but
  Zuckerberg's strategy remains unproven."
  — https://www.cnbc.com/2026/09/24/meta-mark-zuckerberg-muse-charm-openai-agent.html

## 3. Privacy and trust

- Observers object to an agent gaining access to smartphone apps, financial
  information and personal data; others call for tight defenses and
  third-party testing.
  — https://abcnews.com/Business/metas-muse-ai-agent/story?id=136680507
- **Incident:** a writer reported Muse browsed their private messages without
  permission and misdescribed what it was doing.
  — https://www.techradar.com/ai-platforms-assistants/meta-muse-read-a-writers-private-messages-without-permission-and-its-exactly-why-im-not-ready-to-hand-my-life-over-to-ai-agents ,
  https://www.inc.com/jason-aten/metas-new-muse-ai-agent-read-my-private-messages-i-never-asked-it-to/91408202
- EPIC executive director **Alan Butler**: products embedding microphones and
  cameras in everyday devices "pose serious privacy risks" to bystanders.
  — https://abcnews.com/Business/metas-muse-ai-agent/story?id=136680507
- Trust gap: Meta's history of broad data collection; "it remains uncertain
  whether the company has enough consumer trust for its agent to be
  successful." NBC headline: "It's cute. It's cuddly. And it wants your data."
  — https://techcrunch.com/2026/09/08/meta-debuts-its-muse-ai-agent-will-consumers-trust-it/ ,
  https://www.nbcnews.com/tech/tech-news/meta-muse-ai-agent-response-animated-avatar-cute-rcna599736
- Axios reports a "privacy pivot" at Meta tied to Muse and an AI reboot
  (content not retrieved).
  — https://www.axios.com/2026/09/25/meta-ai-muse-privacy
- CNBC frames the launch as happening while Meta "faces public reckoning over
  privacy and safety."
  — https://www.cnbc.com/2026/09/08/meta-personal-ai-agents-public-reckoning-privacy-safety.html

## 4. Muse Spark (the model)

- Launched **2026-04-08**; the first large language model from **Meta
  Superintelligence Labs** (MSL), led by Chief AI Officer **Alexandr Wang**.
  — https://qz.com/meta-muse-spark-ai-superintelligence-labs-040826 ,
  https://www.cnbc.com/2026/04/08/meta-debuts-first-major-ai-model-since-14-billion-deal-to-bring-in-alexandr-wang.html
- Wikipedia (via search summary): "introduced in April 2026, launching as Muse
  Spark 1.1 on July 9, 2026"; first model in the Muse family; designed for
  multimodal reasoning, coding and AI-assisted software development; powers
  Meta AI across Meta's products. Fortune reports 1.1 as an **update** released
  2026-07-09.
  — https://en.wikipedia.org/wiki/Muse_Spark ,
  https://fortune.com/2026/07/09/meta-muse-spark-1-1-release-alexandr-wang-superintelligence-labs-mark-zuckerberg/
- "Small and fast by design," yet able to reason through complex science, math
  and health questions; **1 million token** context.
  — https://about.fb.com/news/2026/04/introducing-muse-spark-meta-superintelligence-labs/
- Three reasoning modes: **Instant**, **Thinking**, **Contemplating** (the last
  uses multiple parallel agents).
  — https://mlq.ai/news/meta-introduces-muse-spark-as-new-ai-reasoning-model-from-superintelligence-labs/
- Deployment: Meta AI app and meta.ai first, then Facebook, Instagram,
  WhatsApp, Messenger and Ray-Ban Meta glasses.
  — https://www.cnbc.com/2026/04/08/meta-debuts-first-major-ai-model-since-14-billion-deal-to-bring-in-alexandr-wang.html
- **Closed weights:** first Meta frontier model not released as open weights;
  a pivot away from the Llama strategy. Meta said it may offer API access to
  select partners and hopes to open-source future versions.
  — https://www.deeplearning.ai/the-batch/with-muse-spark-meta-pivots-away-from-its-open-weights-llama-strategy ,
  https://artificialanalysis.ai/articles/muse-spark-everything-you-need-to-know
- **Benchmarks** (Artificial Analysis): Intelligence Index 52, vs Llama 4
  Maverick 18 and Scout 13 at their release. Leads in health (HealthBench Hard
  42.8 vs GPT-5.4's 40.1), visual reasoning (MMMU-Pro 80.5%, second to Gemini
  3.1 Pro) and chart understanding; **falls short in coding and agentic work**.
  — https://artificialanalysis.ai/articles/muse-spark-everything-you-need-to-know
- First frontier-class Meta model since Llama 4 Maverick (April 2025).
  — https://artificialanalysis.ai/articles/muse-spark-everything-you-need-to-know
- Context: Wang joined via Meta's **$14 billion Scale AI deal**. **Yann LeCun**,
  Meta's longtime Chief AI Scientist and open-source advocate, left in
  November 2025.
  — https://www.cnbc.com/2026/04/08/meta-debuts-first-major-ai-model-since-14-billion-deal-to-bring-in-alexandr-wang.html ,
  https://www.artificialintelligence-news.com/news/meta-muse-spark-ai-model-open-source/

## 5. Muse Glimmer (open-weight model)

- Released **2026-08-10**: a **30B-parameter**, **Apache 2.0** open-weight
  model built for always-on local agents on a single consumer GPU or Mac.
  — https://venturebeat.com/technology/meta-returns-to-open-source-with-muse-glimmer-an-apache-2-0-licensed-30b-parameter-ai-model-optimized-for-agents-available-now ,
  https://www.cnbc.com/2026/08/10/meta-muse-glimmer-open-weight-ai.html
- A **distilled** version of Muse Spark; text + image input; aimed at coding,
  document analysis and multi-step tool use.
  — https://www.fullstack.com/labs/resources/blog/everything-you-need-to-know-about-metas-muse-glimmer
- Quantized to ~4-bit with block-level speculative decoding so it runs locally
  with no network call.
  — https://research.meta.ai/blog/introducing-muse-glimmer-open-agentic-model
- Weights on Hugging Face; support via Ollama, LM Studio, vLLM, SGLang,
  Together AI, Fireworks AI, OpenRouter; optimized llama.cpp, MLX, ExecuTorch.
  — https://www.marktechpost.com/2026/08/10/meta-ai-releases-muse-glimmer/
