---
layout: post
title: "Ecosystem Digest — 2026-10-19"
date: 2026-10-19 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-19
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 392,402 | 1 | 1 | 10 | 1 |
| **hermesagent** | 254,968 | 10 | 2 | 5 | 0 |
| **ZeroClaw** | 32,995 | 9 | 4 | 9 | 1 |
| **IronClaw** | 12,662 | 0 | 1 | 0 | 0 |
| **Moltis** | 2,899 | 0 | 0 | 2 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 392,402 · **Open issues:** 9,513 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.10.5](https://github.com/openclaw/openclaw/releases/tag/v2026.10.5) — openclaw 2026.10.5

### ✅ Merged PRs
- [#176607](https://github.com/openclaw/openclaw/pull/176607) chore(release): close out 2026.10.5 on main
- [#176513](https://github.com/openclaw/openclaw/pull/176513) fix: prevent unrelated coauthors on shared-main channel tasks
- [#174211](https://github.com/openclaw/openclaw/pull/174211) fix(goals): keep pursuing after delegated work finishes
- [#176708](https://github.com/openclaw/openclaw/pull/176708) test(ui): build usage cost fixtures when the case starts
- [#176414](https://github.com/openclaw/openclaw/pull/176414) perf(control-ui): defer hidden composer menu construction
- [#176703](https://github.com/openclaw/openclaw/pull/176703) test(agents, gateway, plugins): remove low-value tests (batch d260)
- [#176715](https://github.com/openclaw/openclaw/pull/176715) test(heartbeat): heartbeat live suite never sees the forced monitor poll
- [#176771](https://github.com/openclaw/openclaw/pull/176771) refactor: consolidate single-consumer core command helpers
- [#176754](https://github.com/openclaw/openclaw/pull/176754) refactor(agents): remove redundant private wrappers and checks
- [#176722](https://github.com/openclaw/openclaw/pull/176722) refactor(agents): reuse parsed and normalized inputs

### 🐛 New Issues
- [#176778](https://github.com/openclaw/openclaw/issues/176778) Workspace synchronization captures retained test compiler caches `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬2

### 🔒 Closed Issues
- [#176235](https://github.com/openclaw/openclaw/issues/176235) [Bug]: backgrounded exec finishing during an isolated cron run injects a user turn and kills the run (SqliteTranscriptMutationConflictError)

### 🔥 Hot Issues (most commented)
- [#143524](https://github.com/openclaw/openclaw/issues/143524) [Bug]: Agent SQLite WAL grows to 1.4–2.8 GB in days despite wal_autocheckpoint=1000; blocks gateway startup (Windows, 2026.9.2/9.3) — 💬131 · 2d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 254,968 · **Open issues:** 49,966 · **Last push:** <1h ago

### ✅ Merged PRs
- [#141312](https://github.com/NousResearch/hermes-agent/pull/141312) Desktop: pick subagent provider and model from dropdowns under Settings → Model (salvage #129142)
- [#124273](https://github.com/NousResearch/hermes-agent/pull/124273) fix(sessions): proactive prune rewrites only the changed rows, in place
- [#140645](https://github.com/NousResearch/hermes-agent/pull/140645) fix(desktop): unattended OAuth recovery never opens a window; one login flow per cookie jar
- [#139497](https://github.com/NousResearch/hermes-agent/pull/139497) plugin-catalog: bump loreconvo to 0.10.17
- [#141070](https://github.com/NousResearch/hermes-agent/pull/141070) fix(update): a system-scope dashboard unit without root gets one exact restart command, not a polkit dump (#141021)

### 🐛 New Issues
- [#141333](https://github.com/NousResearch/hermes-agent/issues/141333) [Bug]: Bot Mode group-round prompts are ingested by memory providers as user speech `type/bug` `comp/agent` `tool/memory` `P3` `comp/desktop`
- [#141329](https://github.com/NousResearch/hermes-agent/issues/141329) [Bug]: Desktop UI stops painting after long session; renderer CPU/memory grows ~9x/3x, gateway alive `type/bug` `P2` `comp/desktop` `desktop/chat` `desktop/shell`
- [#141328](https://github.com/NousResearch/hermes-agent/issues/141328) Hardening for non-operator dashboard users: config-selected plugin names and command-selecting settings `type/security` `comp/cli` `comp/tools` `comp/plugins` `tool/memory` `tool/tts` `area/config` `P3`
- [#141323](https://github.com/NousResearch/hermes-agent/issues/141323) [Bug]: Team Gateway Slack scope claim fails with 502 connector_error `type/bug` `comp/gateway` `platform/slack` `area/auth` `P2` `comp/portal`
- [#141321](https://github.com/NousResearch/hermes-agent/issues/141321) Gateway fixes (#134889), package 12: Ink and Desktop commands, estimates, decided gateway behaviour, ACP edit modes, custom providers, Telegram topics and remote Desktop `type/bug` `comp/cli` `comp/gateway` `comp/tui` `comp/acp` `tool/delegate` `P2` `comp/desktop` `area/sessions` `area/profiles` `comp/tui-gateway`
- [#141320](https://github.com/NousResearch/hermes-agent/issues/141320) Voice (Linux): interrupting TTS plays seconds of loud static; barge-in thresholds not configurable `type/bug` `comp/tools` `tool/file` `tool/tts` `area/config` `P2` 💬2
- [#141318](https://github.com/NousResearch/hermes-agent/issues/141318) Delegated subagents run background skill review (child AIAgent lacks skip_background_review) `type/security` `comp/tools` `tool/delegate` `tool/memory` `tool/skills` `P3` 💬1
- [#141315](https://github.com/NousResearch/hermes-agent/issues/141315) [SANITIZED — possible injection attempt] `type/feature` `comp/tools` `tool/file` `tool/delegate` `area/config` `P3` `area/compression`
- [#141314](https://github.com/NousResearch/hermes-agent/issues/141314) Python 3.14 compatibility: Kanban dependency blocks web-perplexity enablement `type/bug` `comp/plugins` `P3` `area/install-update` `cause/upstream`
- [#141313](https://github.com/NousResearch/hermes-agent/issues/141313) CLI voice mode: TTS never speaks replies from external-process providers (e.g. claude-subscription-directsdk) `type/bug` `comp/cli` `tool/file` `tool/tts` `P2` 💬2

### 🔒 Closed Issues
- [#114170](https://github.com/NousResearch/hermes-agent/issues/114170) [Feature]: Put the subagent model on Settings > Models
- [#139694](https://github.com/NousResearch/hermes-agent/issues/139694) /model switch never commits when a multi-profile gateway is hosted in the default home

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,995 · **Open issues:** 998 · **Last push:** 2h ago

### 🚀 New Releases
- [v0.8.6](https://github.com/zeroclaw-labs/zeroclaw/releases/tag/v0.8.6) — v0.8.6

### ✅ Merged PRs
- [#11688](https://github.com/zeroclaw-labs/zeroclaw/pull/11688) test(runtime): tolerate concurrent writers when checking persisted trace correlation
- [#11407](https://github.com/zeroclaw-labs/zeroclaw/pull/11407) fix(zerocode): render live session updates promptly under load
- [#11838](https://github.com/zeroclaw-labs/zeroclaw/pull/11838) style(tests): apply rustfmt to the Stable ARM64 target constant
- [#11692](https://github.com/zeroclaw-labs/zeroclaw/pull/11692) feat(runtime): surface cost warn_at_percent warnings in ZeroCode
- [#11513](https://github.com/zeroclaw-labs/zeroclaw/pull/11513) feat(zerocode): show focused runtime context
- [#11508](https://github.com/zeroclaw-labs/zeroclaw/pull/11508) feat(zerocode): guide Config alias setup
- [#11837](https://github.com/zeroclaw-labs/zeroclaw/pull/11837) fix(release): bound memory for the Stable aarch64 musl build
- [#11836](https://github.com/zeroclaw-labs/zeroclaw/pull/11836) chore(docs): pin translations to v0.8.6
- [#11835](https://github.com/zeroclaw-labs/zeroclaw/pull/11835) chore(release): bump version to v0.8.6

### 🐛 New Issues
- [#11839](https://github.com/zeroclaw-labs/zeroclaw/issues/11839) [Task]: the macOS universal desktop build gates publishing and runs close to its timeout `type:ci` `release:v0.8.7`
- [#11834](https://github.com/zeroclaw-labs/zeroclaw/issues/11834) [Bug]: Workspace is not clippy-clean on Rust 1.99 (18 new findings; CI still pins 1.98.0) `bug` 💬1
- [#11831](https://github.com/zeroclaw-labs/zeroclaw/issues/11831) [Task]: move the macOS plugin smoke leg off `macos-14` before the October 19 brownout `type:ci` `release:v0.8.6` 💬1
- [#11830](https://github.com/zeroclaw-labs/zeroclaw/issues/11830) [Task]: drop the whole-file digest of the Stable workflow from the release workflow architecture test `tests` `release:v0.8.7` 💬1
- [#11828](https://github.com/zeroclaw-labs/zeroclaw/issues/11828) [Task]: the arm64 `dist` image runs out of memory in docker-publish.yml, so v0.8.6 can ship without its `dist` image `type:ci` `release:v0.8.6` 💬1
- [#11820](https://github.com/zeroclaw-labs/zeroclaw/issues/11820) [Bug]: config set of a plugin instance's settings or egress grant is written to disk only and never reaches a running daemon `bug` `config` `priority:p2` `risk:medium` `cli` `topic:plugins` `topic:operator-ux` `release:v0.8.7` 💬1
- [#11819](https://github.com/zeroclaw-labs/zeroclaw/issues/11819) [Bug]: Quickstart lists models from the provider's default endpoint before asking for the URI, and the picker takes no typed model `bug` `priority:p3` `quickstart` `risk:low` `topic:operator-ux` `release:v0.8.7` 💬1
- [#11817](https://github.com/zeroclaw-labs/zeroclaw/issues/11817) [Bug]: under signature_mode = strict, plugin info and plugin list --verify report an installed unsigned package as not installed `bug` `priority:p3` `risk:low` `cli` `topic:plugins` `topic:operator-ux` `release:v0.8.7` 💬1
- [#11813](https://github.com/zeroclaw-labs/zeroclaw/issues/11813) [Bug]: plugin egress connections stall when the first resolved address is blackholed and never try the others `bug` `priority:p1` `topic:plugins` `release:v0.8.6` 💬1

### 🔒 Closed Issues
- [#11490](https://github.com/zeroclaw-labs/zeroclaw/issues/11490) [Feature]: Explain empty Config sections and alias setup in ZeroCode
- [#10950](https://github.com/zeroclaw-labs/zeroclaw/issues/10950) [Bug]: cost.warn_at_percent warnings are ignored by the runtime
- [#8383](https://github.com/zeroclaw-labs/zeroclaw/issues/8383) [Feature]: Show active runtime context in ZeroCode Dashboard
- [#11648](https://github.com/zeroclaw-labs/zeroclaw/issues/11648) [Bug]: Web dashboard pairing input still limited to 6 digits after PairingCodePolicy default became 32 alphanumeric

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,662 · **Open issues:** 1,552 · **Last push:** 5h ago

### 🔒 Closed Issues
- [#8025](https://github.com/nearai/ironclaw/issues/8025) Bug: unexpected behavior with special characters in input

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,899 · **Open issues:** 114 · **Last push:** 3h ago

### ✅ Merged PRs
- [#1295](https://github.com/moltis-org/moltis/pull/1295) fix(discord): classify direct messages as direct chats
- [#1306](https://github.com/moltis-org/moltis/pull/1306) feat: native gpui desktop client (apps/desktop) and moltis-client crate

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 4d ago
- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬1 · 10d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 13d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 21d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 23d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 33d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 41d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 43d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 51d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 55d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Public Benefit Fund](https://www.anthropic.com/news/public-benefit-fund) _2026-10-18_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Linux creator says anti-AI rules are "idiotic." (Absolute god-tier take.)](https://reddit.com/r/LocalLLaMA/comments/1x8e4wd/linux_creator_says_antiai_rules_are_idiotic/) ↑2930
- [Two pallets of ZOTAC RTX 5090 graphics cards worth $470,000 disappear at Brazilian airport](https://reddit.com/r/LocalLLaMA/comments/1x91svd/two_pallets_of_zotac_rtx_5090_graphics_cards/) ↑820
- [Google Open Sources Harness2 for Self Improving AI Agents](https://reddit.com/r/LocalLLaMA/comments/1x9gfnb/google_open_sources_harness2_for_self_improving/) ↑469
- [72 hours, four big open weights drops. The only one that fits in 24GB came from NVIDIA, of all companies.](https://reddit.com/r/LocalLLaMA/comments/1x9d23j/72_hours_four_big_open_weights_drops_the_only_one/) ↑425
- [You don’t need that expensive of a build for local llms.](https://reddit.com/r/LocalLLaMA/comments/1x8s73i/you_dont_need_that_expensive_of_a_build_for_local/) ↑355

### r/singularity — top 5 new
- [Real.](https://reddit.com/r/singularity/comments/1x8557v/real/) ↑1815
- [Anthropic creates a public benefit fund, pledging 20% of its shares to the public good, with another 2% potentially added for every 50% increase in its valuation](https://reddit.com/r/singularity/comments/1x9a50t/anthropic_creates_a_public_benefit_fund_pledging/) ↑1221
- [How employment is changing at Anthropic](https://reddit.com/r/singularity/comments/1x8ztaj/how_employment_is_changing_at_anthropic/) ↑377
- [New chinese model benchmark scores are INSANE!](https://reddit.com/r/singularity/comments/1x8lwr6/new_chinese_model_benchmark_scores_are_insane/) ↑366
- [Linux creator, Linus Torvalds, says anti-AI rules are "idiotic." (Absolute god-tier take.)](https://reddit.com/r/singularity/comments/1x8r2wc/linux_creator_linus_torvalds_says_antiai_rules/) ↑298

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [LOOI + OpenClaw](https://reddit.com/r/openclaw/comments/1x912w2/looi_openclaw/) ↑8
- [Disappointed at Openclaw with Local LLM - what am I doing wrong?](https://reddit.com/r/openclaw/comments/1x8g9eq/disappointed_at_openclaw_with_local_llm_what_am_i/) ↑7
- [OpenClaw and DLSS Game Modding](https://reddit.com/r/openclaw/comments/1x8wvv3/openclaw_and_dlss_game_modding/) ↑3
- [I need help with my verbose installation](https://reddit.com/r/openclaw/comments/1x8wpfj/i_need_help_with_my_verbose_installation/) ↑3
- [MiniPC - upgrading from pi5](https://reddit.com/r/openclaw/comments/1x8yykq/minipc_upgrading_from_pi5/) ↑2

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [Set up OpenClaw out of the box on the new 
@nvidia
 RTX Spark laptops.

Choose a local model or connect a cloud provider](https://x.com/openclaw/status/2111190844225306694)

### X — @steipete
- [AI;DR](https://x.com/steipete/status/2111918049116987476) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
