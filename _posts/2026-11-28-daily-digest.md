---
layout: post
title: "Ecosystem Digest — 2026-11-28"
date: 2026-11-28 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-28
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 395,358 | 1 | 4 | 10 | 1 |
| **hermesagent** | 266,604 | 9 | 4 | 10 | 0 |
| **ZeroClaw** | 33,641 | 6 | 0 | 0 | 0 |
| **IronClaw** | 12,720 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,989 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 395,358 · **Open issues:** 9,356 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.12.1-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.12.1-beta.1) — openclaw 2026.12.1-beta.1

### ✅ Merged PRs
- [#206521](https://github.com/openclaw/openclaw/pull/206521) feat(ios): a sent message rises from the composer, and times show while dragging left
- [#207106](https://github.com/openclaw/openclaw/pull/207106) improve: reduce sidebar row rebuilds during child activity
- [#206987](https://github.com/openclaw/openclaw/pull/206987) fix: keep past blockers from stopping current work
- [#207037](https://github.com/openclaw/openclaw/pull/207037) fix: let backups finish when Gateway startup creates a database
- [#206514](https://github.com/openclaw/openclaw/pull/206514) feat(ios): sent videos play inline in the chat
- [#207084](https://github.com/openclaw/openclaw/pull/207084) improve: reduce memory needed to renew the Gateway lock
- [#207054](https://github.com/openclaw/openclaw/pull/207054) improve: use less agent context after a Gateway restart
- [#206758](https://github.com/openclaw/openclaw/pull/206758) fix(imap): require the authenticated From mailbox to match the allowlisted sender
- [#206519](https://github.com/openclaw/openclaw/pull/206519) feat(ios): the chat header shows the agent and title, a more menu, and fits landscape
- [#207045](https://github.com/openclaw/openclaw/pull/207045) fix: preserve source ranges in compaction requests

### 🐛 New Issues
- [#207117](https://github.com/openclaw/openclaw/issues/207117) [Bug]: Internal Codex steering timeout text is delivered to the chat once per message sent during a blocking approval `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#207019](https://github.com/openclaw/openclaw/issues/207019) Backup exits without an archive when Gateway startup creates a managed SQLite database during capture
- [#167177](https://github.com/openclaw/openclaw/issues/167177) [Feature]: Make CLI live-session capacity configurable
- [#207099](https://github.com/openclaw/openclaw/issues/207099) decision_evaluate: stacked validators emit one generic "provide state and a nonempty questions map" for at least 4 distinct arg defects
- [#207098](https://github.com/openclaw/openclaw/issues/207098) decisionModels.questionTypes manifest cap (≤3: boolean/choice/score) blocks locally-supported decision types (text/number/date/box/boxes/noul)

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬87 · 3d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 266,604 · **Open issues:** 54,889 · **Last push:** <1h ago

### ✅ Merged PRs
- [#160960](https://github.com/NousResearch/hermes-agent/pull/160960) fix(cli): arrow keys no longer close the hermes sessions and plugins pickers (salvage #54711)
- [#159450](https://github.com/NousResearch/hermes-agent/pull/159450) fix(plugins): run a marked profile's plugin code under the name it was opened by
- [#160300](https://github.com/NousResearch/hermes-agent/pull/160300) fix(platform): refuse stub review_push/revert, resolve child cwd PATH, and test xcode-select timeout
- [#148532](https://github.com/NousResearch/hermes-agent/pull/148532) fix(docker): an image upgrade no longer fills the data volume rebuilding the image's own extras
- [#160797](https://github.com/NousResearch/hermes-agent/pull/160797) feat(cli,tui): OSC 7577 program resume (salvage of #160297)
- [#160859](https://github.com/NousResearch/hermes-agent/pull/160859) fix(plugins): skip live catalog fetch when lazy installs are off
- [#160314](https://github.com/NousResearch/hermes-agent/pull/160314) fix(ci): keep prompt surface paths masked under outer or symlinked temp dirs
- [#159106](https://github.com/NousResearch/hermes-agent/pull/159106) test(release): cover commit-claim guards and deduplicate stagers
- [#160301](https://github.com/NousResearch/hermes-agent/pull/160301) fix(desktop): guard Electron resolveGitBinary and callers against macOS CLT git stub
- [#160878](https://github.com/NousResearch/hermes-agent/pull/160878) test(ci): enforce bare-Python ruamel guard in protected canary driver

### 🐛 New Issues
- [#160970](https://github.com/NousResearch/hermes-agent/issues/160970) [Bug]: Multiplexed secondary profile delivers final responses through the default profile's bot when its adapter is detached (cross-profile misdelivery) `type/security` `comp/gateway` `platform/telegram` `P3` `area/profiles`
- [#160968](https://github.com/NousResearch/hermes-agent/issues/160968) fix(cli): preserve assistant text sharing a message with a tool call `type/bug` `comp/cli` `P2` `area/streaming`
- [#160967](https://github.com/NousResearch/hermes-agent/issues/160967) feat(cli): built-in per-turn footer line `type/feature` `comp/cli` `area/config` `P3`
- [#160964](https://github.com/NousResearch/hermes-agent/issues/160964) Host gateway plugin-reload pass seeds marker-less dirs under profiles/, which marker-based sweep scripts then promote to real profiles `type/bug` `comp/gateway` `P3` `area/profiles`
- [#160963](https://github.com/NousResearch/hermes-agent/issues/160963) Kanban: a headless worker stopped by a consent refusal is booked as a crash and auto-blocked, instead of blocking as needs_input `type/bug` `comp/cli` `comp/cron` `tool/file` `P2`
- [#160957](https://github.com/NousResearch/hermes-agent/issues/160957) Structured improvement memory for harness edits — predicted-versus-observed outcomes under a stable root cause `type/feature` `comp/agent` `tool/memory` `tool/skills` `P3`
- [#160952](https://github.com/NousResearch/hermes-agent/issues/160952) Mid-turn user steering releases a running tool call but the turn ends with no assistant output ('result unavailable') `type/bug` `comp/agent` `tool/terminal` `P2`
- [#160948](https://github.com/NousResearch/hermes-agent/issues/160948) [Feature]: Attach selected session-log excerpts to chat composer as context chips (like @file attachments) `type/feature` `P3` `comp/desktop` `desktop/chat` `desktop/files` 💬1
- [#160945](https://github.com/NousResearch/hermes-agent/issues/160945) [Bug]: cron agent sessions never get the external memory provider's tools (honcho_*), although the provider registers and activates `type/bug` `comp/agent` `comp/tools` `tool/memory` `area/config` `P2` 💬2

### 🔒 Closed Issues
- [#147564](https://github.com/NousResearch/hermes-agent/issues/147564) [Bug] Hermes Cloud instance: all outbound TCP refused (Errno 111) — dashboard login 503 'Auth provider nous unreachable', survives upgrade/reset/restart
- [#94714](https://github.com/NousResearch/hermes-agent/issues/94714) [Bug]: hermes sessions browse exits with 'Cancelled.' when pressing arrow keys
- [#91005](https://github.com/NousResearch/hermes-agent/issues/91005) [Feature]: Verified local cold archive for soft-archived logical sessions
- [#160917](https://github.com/NousResearch/hermes-agent/issues/160917) Withdrawn

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,641 · **Open issues:** 1,288 · **Last push:** 16h ago

### 🐛 New Issues
- [#12774](https://github.com/zeroclaw-labs/zeroclaw/issues/12774) [Bug]: OpenRouter drops declared tool-result image attachments `bug`
- [#12773](https://github.com/zeroclaw-labs/zeroclaw/issues/12773) [Bug]: Quickstart cannot configure Lark/Feishu credentials; writes an invalid channel block dropped on reload
- [#12772](https://github.com/zeroclaw-labs/zeroclaw/issues/12772) Feature request: support excluding individual MCP tools inside mcp_bundles `bug`
- [#12767](https://github.com/zeroclaw-labs/zeroclaw/issues/12767) [Bug]: a transient MCP failure at channel startup (HTTP 429/503, connection refused) leaves the agent without MCP tools until restart, and /health stays green
- [#12766](https://github.com/zeroclaw-labs/zeroclaw/issues/12766) [Bug]: gateway does not answer /health during startup while MCP tool listings connect, so liveness probes restart the daemon during an MCP outage
- [#12765](https://github.com/zeroclaw-labs/zeroclaw/issues/12765) [Feature]: Add a Buzz (buzz.xyz) channel, the free open-source Slack alternative

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,720 · **Open issues:** 1,575 · **Last push:** 18d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,989 · **Open issues:** 127 · **Last push:** 35d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬5 · 7d ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 25d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 34d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 53d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 61d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 63d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 73d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 81d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 83d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 91d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Reuters confirms: Cutting off distillation and compute works and slows down Chinese Models massively](https://reddit.com/r/LocalLLaMA/comments/1y5ysad/reuters_confirms_cutting_off_distillation_and/) ↑779
- [Is it true that even best open models are behind Haiku](https://reddit.com/r/LocalLLaMA/comments/1y51h3b/is_it_true_that_even_best_open_models_are_behind/) ↑752
- [54% faster generation by removing the Linux OS and llama.cpp](https://reddit.com/r/LocalLLaMA/comments/1y6yfrt/54_faster_generation_by_removing_the_linux_os_and/) ↑349
- [Inkling-2-Mini-Unbound v3: no more thinking loops (debugging 73.3% → 100%, answers 3x faster), plus Inkling-2-Mini-Prime, the same fix for the original censored model](https://reddit.com/r/LocalLLaMA/comments/1y6tjly/inkling2miniunbound_v3_no_more_thinking_loops/) ↑274
- [AMD-specific llama.cpp patch nearly doubles prefill/decode](https://reddit.com/r/LocalLLaMA/comments/1y73gcc/amdspecific_llamacpp_patch_nearly_doubles/) ↑172

### r/singularity — top 2 new
- [This is how Claude has been reacting to GTA recomp requests](https://reddit.com/r/singularity/comments/1y6m51z/this_is_how_claude_has_been_reacting_to_gta/) ↑3596
- [There are now countless users coming out about Claude sabotaging any ML work. This is an incredibly shit look for Anthropic, but it is to be expected from that company](https://reddit.com/r/singularity/comments/1y6yobd/there_are_now_countless_users_coming_out_about/) ↑918

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Sub-Agent rights](https://reddit.com/r/openclaw/comments/1y6oqmp/subagent_rights/) ↑2
- [Damas y caballeros, estoy perdido](https://reddit.com/r/openclaw/comments/1y6jqua/damas_y_caballeros_estoy_perdido/) ↑0

### X — @openclaw
_No tweets found on profile (fetch may have failed)._

### X — @steipete
_No tweets found on profile (fetch may have failed)._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
