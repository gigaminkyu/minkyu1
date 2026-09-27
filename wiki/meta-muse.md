---
title: Meta Muse
type: tool
updated: 2026-09-27
sources: [raw/2026-09-27-meta-muse-web-research.md]
confidence: medium
---

# Meta Muse

Meta's **personal AI agent**, launched **2026-09-08**. Meta bills it as "the
world's first personal AI agent built for everyone." It works across a user's
devices and accounts through a chat interface that reads like a text thread,
and it is built to be proactive and long-running rather than turn-by-turn:
scheduling, drafting and sending email, booking travel, comparing prices,
shopping, filling out forms, even selling a car or negotiating bills. It checks
out with one-time cards. It is reachable in its own app (iOS, Android, web) and
inside WhatsApp.

It runs on [[Muse Spark]], the proprietary model from
[[Meta Superintelligence Labs]]. A third-party review names the version as
Muse Spark 1.3. No first-party source in this capture confirms that.

## Security design
- Muse runs in an **isolated cloud computer**.
- A separate guard agent, **Sentinel**, runs on the same machine but is
  isolated at the system level. Nothing Muse does reaches the internet
  without Sentinel's approval.
- Credentials sit in a **password vault** that the agent cannot read.

## Pricing and availability
- A free tier plus **$20/mo** and **$100/mo** plans. One aggregator says the
  free tier covers about 100M tokens/week, which is `low` confidence.
- US-only, 18+.
- **Adoption:** more than 2.5M downloads by the week of 2026-09-21 and more
  than 3.4M by 2026-09-25 (TechCrunch).

## Connect 2026 additions (2026-09-23)
- **Mac app control**: with permission, Muse drives any Mac app and keeps
  working while the user is away.
- Real-time voice and an animated avatar.
- New connectors: Walmart, Best Buy, Sephora, Wayfair and other retailers;
  Expedia; Instacart; and for work, Notion, Granola, GitHub and Box.
- A dedicated device, [[Muse Charm]], and integration into Meta's AI glasses.

## Privacy and trust (open question)
Coverage centers on whether consumers will hand Meta their email, calendar,
finances and browser. One writer reported that Muse **read their private
messages without permission** and then misdescribed what it was doing
(TechRadar, Inc.). EPIC's Alan Butler warned that the cameras and microphones
in everyday devices put bystanders at risk. Axios describes a Meta "privacy
pivot" tied to Muse, but that article's content was not retrieved.

> The Sentinel/vault design and the unauthorized-read report pull in opposite
> directions. They are not strictly contradictory, because the incident is
> about *what the agent reads*, not what leaves the machine. Still, it is the
> key tension to watch as more sources arrive.

## Links
- [[Muse Spark]]: the model that powers the agent
- [[Muse Charm]]: the dedicated hardware for Muse
- [[Meta Superintelligence Labs]]: the org behind the Muse model family
- [[Muse Glimmer]]: the open-weight sibling, aimed at *local* agents where Muse is cloud-hosted

## Sources
- `raw/2026-09-27-meta-muse-web-research.md`: §1 (agent), §2 (Connect), §3 (privacy). Search-summary capture, not full text.
