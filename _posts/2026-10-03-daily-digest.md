---
layout: post
title: "Ecosystem Digest — 2026-10-03"
date: 2026-10-03 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-03
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 391,196 | 6 | 2 | 10 | 1 |
| **hermesagent** | 250,787 | 6 | 0 | 2 | 0 |
| **ZeroClaw** | 32,925 | 2 | 3 | 3 | 0 |
| **IronClaw** | 12,634 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,884 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 391,196 · **Open issues:** 9,195 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.8.35](https://github.com/openclaw/openclaw/releases/tag/v2026.8.35) — openclaw 2026.8.35

### ✅ Merged PRs
- [#163925](https://github.com/openclaw/openclaw/pull/163925) fix(release): accept split worker package chunks
- [#163938](https://github.com/openclaw/openclaw/pull/163938) refactor(gateway): simplify hosted-session inference lifecycle
- [#163910](https://github.com/openclaw/openclaw/pull/163910) refactor(gateway): deslop gateway methods
- [#163936](https://github.com/openclaw/openclaw/pull/163936) fix(memory): recover search after an embedding fallback outage
- [#163862](https://github.com/openclaw/openclaw/pull/163862) fix(gateway): approve same-machine node capabilities silently
- [#163167](https://github.com/openclaw/openclaw/pull/163167) refactor(doctor): retire pre-July delivery queue files
- [#163927](https://github.com/openclaw/openclaw/pull/163927) refactor(nodes): simplify pairing and worker availability checks
- [#163558](https://github.com/openclaw/openclaw/pull/163558) fix(swarm): wait for owned cleanup when stopping children
- [#162669](https://github.com/openclaw/openclaw/pull/162669) feat(plugin-sdk): join service and account scheduling at retirement
- [#163935](https://github.com/openclaw/openclaw/pull/163935) chore(i18n): refresh native locales

### 🐛 New Issues
- [#163950](https://github.com/openclaw/openclaw/issues/163950) [Bug] Updater: failed post-update verification leaves permanent warning on healthy npm/LaunchAgent gateway `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-friction` 💬1
- [#163946](https://github.com/openclaw/openclaw/issues/163946) Implement RFC 0016: launch Claws in OpenClaw Labs `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#163942](https://github.com/openclaw/openclaw/issues/163942) Doctor changes the WhatsApp default account when promoting shared channel policy `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#163940](https://github.com/openclaw/openclaw/issues/163940) Automations model-catalog warning cannot be dismissed `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#163939](https://github.com/openclaw/openclaw/issues/163939) Windows health checks time out when a healthy Gateway listener cannot be attributed `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬2
- [#163929](https://github.com/openclaw/openclaw/issues/163929) Update failure: managed-service-preflight (2026.9.4) `P0` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-release-blocker` 💬2

### 🔒 Closed Issues
- [#96534](https://github.com/openclaw/openclaw/issues/96534) memory_search latches fallback embedding model after provider outage; only full restart recovers (soft reload insufficient)
- [#163924](https://github.com/openclaw/openclaw/issues/163924) [Bug]: chat.send from a resuming Control UI is rejected for its own __controlUiReconnectResume param — connection is then permanently unable to send

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 250,787 · **Open issues:** 47,918 · **Last push:** <1h ago

### ✅ Merged PRs
- [#131939](https://github.com/NousResearch/hermes-agent/pull/131939) fix(web/firecrawl): accept the server timeout in the keyless scrape client [risk 0.30]
- [#131888](https://github.com/NousResearch/hermes-agent/pull/131888) fix(gateway): stop losing late steering and busy follow-ups (#131644)

### 🐛 New Issues
- [#131947](https://github.com/NousResearch/hermes-agent/issues/131947) [Bug]: Desktop: долгие «Summarizing thread», циклы без результата и таймаут смены reasoning
- [#131945](https://github.com/NousResearch/hermes-agent/issues/131945) Desktop SDK: host-rendered transcript density and disclosure preferences
- [#131944](https://github.com/NousResearch/hermes-agent/issues/131944) Desktop SDK: declarative composer presentation preferences without native DOM access
- [#131943](https://github.com/NousResearch/hermes-agent/issues/131943) Desktop SDK: host-owned sidebar density and chrome preferences beyond sessionListDensity
- [#131934](https://github.com/NousResearch/hermes-agent/issues/131934) [Bug]: Windows desktop boot stalls 35s+ → "Timed out connecting to Hermes backend after 15000ms" — new repro link to credential-pool "no available entries" log storm `type/perf` `P2` `needs-repro` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows` 💬1
- [#131924](https://github.com/NousResearch/hermes-agent/issues/131924) [Bug]: hermes send / standalone Telegram sends ignore display.platforms.telegram.notifications `type/bug` `comp/tools` `platform/telegram` `area/config` `P2` `sweeper:risk-message-delivery`

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,925 · **Open issues:** 896 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11370](https://github.com/zeroclaw-labs/zeroclaw/pull/11370) fix(config): lock the loader's data dir and resume interrupted splits
- [#11291](https://github.com/zeroclaw-labs/zeroclaw/pull/11291) fix(rpc): retire the local connection when its writer fails
- [#11433](https://github.com/zeroclaw-labs/zeroclaw/pull/11433) fix(ci): accept anymap2 maintenance advisory pending Matrix migration

### 🐛 New Issues
- [#11470](https://github.com/zeroclaw-labs/zeroclaw/issues/11470) [Task]: Use the effective shell dialect for cron path checks
- [#11442](https://github.com/zeroclaw-labs/zeroclaw/issues/11442) [Task]: Retire legacy native tool adapters after verified replacements

### 🔒 Closed Issues
- [#11369](https://github.com/zeroclaw-labs/zeroclaw/issues/11369) [Bug]: Docker images built from master exit at startup, and an interrupted upgrade can strand the database
- [#10791](https://github.com/zeroclaw-labs/zeroclaw/issues/10791) [Task]: Retire local RPC connections after terminal writer failure
- [#11434](https://github.com/zeroclaw-labs/zeroclaw/issues/11434) [Feature]: Gateway route to send a message through a running channel without an agent turn

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,634 · **Open issues:** 1,538 · **Last push:** 1d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,884 · **Open issues:** 102 · **Last push:** 10d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 5d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 6d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 7d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 17d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 25d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 27d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 35d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 39d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 51d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 54d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Claude Frontier Academy](https://www.anthropic.com/news/claude-frontier-academy) _2026-10-02_

### OpenAI — 2 new
- [[Partners] Megazonecloud](https://openai.com/business/partners/megazonecloud/) _2026-10-02_
- [[Index] Chatham Financial](https://openai.com/index/chatham-financial/) _2026-10-02_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/singularity — top 2 new
- [Opus 5.5 recapped all of human history as if it were a 24-hour day in this one-shot animated video, with its own original score](https://reddit.com/r/singularity/comments/1ww2o3o/opus_55_recapped_all_of_human_history_as_if_it/) ↑590
- [OpenAI is now working directly with Lockheed Martin’s F-35 engineers to solve the math and physics behind advanced fighter-jet sensors](https://reddit.com/r/singularity/comments/1ww9myb/openai_is_now_working_directly_with_lockheed/) ↑156

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [I'm taking the guard rails off](https://reddit.com/r/openclaw/comments/1ww95b4/im_taking_the_guard_rails_off/) ↑2
- [OpenClaw issues, bad settings?](https://reddit.com/r/openclaw/comments/1ww2fqr/openclaw_issues_bad_settings/) ↑1

### X — @openclaw
- [We’ve integrated 
@TencentHunyuan
's AI-Infra-Guard (AIG) into ClawScan, the open-source command-line tool that powers s](https://x.com/openclaw/status/2106162952923656337) ↑0 🔁0 · recent


### X — @steipete
- [This was by far my favorite slide at DevDay.
Kudos to the team!](https://x.com/steipete/status/2106076508020506722) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
