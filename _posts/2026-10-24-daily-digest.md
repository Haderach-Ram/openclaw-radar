---
layout: post
title: "Ecosystem Digest — 2026-10-24"
date: 2026-10-24 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-24
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 392,887 | 4 | 10 | 10 | 0 |
| **hermesagent** | 256,544 | 14 | 2 | 0 | 1 |
| **ZeroClaw** | 33,037 | 15 | 1 | 1 | 0 |
| **IronClaw** | 12,671 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,906 | 0 | 0 | 2 | 1 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 392,887 · **Open issues:** 8,830 · **Last push:** <1h ago

### ✅ Merged PRs
- [#182089](https://github.com/openclaw/openclaw/pull/182089) test(ui): restore complete sidebar roster fixture coverage
- [#182068](https://github.com/openclaw/openclaw/pull/182068) fix: show quiet waits and real work in speech bubbles
- [#180952](https://github.com/openclaw/openclaw/pull/180952) perf(agents): avoid loading unrelated setup backends during startup
- [#182018](https://github.com/openclaw/openclaw/pull/182018) perf(sessions): remove unused filter yield machinery
- [#182006](https://github.com/openclaw/openclaw/pull/182006) fix(telegram): skip sticker descriptions when image understanding is off
- [#181994](https://github.com/openclaw/openclaw/pull/181994) refactor: separate steering delivery from policy preparation
- [#182078](https://github.com/openclaw/openclaw/pull/182078) refactor: keep single-use helpers with their callers
- [#181973](https://github.com/openclaw/openclaw/pull/181973) fix(perf): report natural GC cost for paired RPC measurements
- [#181991](https://github.com/openclaw/openclaw/pull/181991) fix(ui): transcript search closes when Escape cancels IME composition
- [#182034](https://github.com/openclaw/openclaw/pull/182034) refactor: reuse message registration and Matrix bootstrap owners

### 🐛 New Issues
- [#182093](https://github.com/openclaw/openclaw/issues/182093) Update failure: node-runtime-preflight (2026.9.3) `clawsweeper:needs-info` `P0` `issue-rating: 🦪 silver shellfish` `impact:ux-release-blocker` 💬1
- [#182087](https://github.com/openclaw/openclaw/issues/182087) Restart recovery replays a session on every boot when a legacy replayable pendingFinalDelivery's resume turn fails terminally `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#182084](https://github.com/openclaw/openclaw/issues/182084) Anthropic subscription "session limit" does not rotate to the api_key (credits) auth profile; runs hang until the 630 s timeout `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:auth-provider` `issue-rating: 🦪 silver shellfish` 💬1
- [#182077](https://github.com/openclaw/openclaw/issues/182077) [Docs Bug]: Show same-model interactive and background provider routes `no-stale` `P3` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#85207](https://github.com/openclaw/openclaw/issues/85207) Codex ACP gateway path can surface bare ACP_TURN_FAILED when active acpx plugin misses runtime hardening
- [#84753](https://github.com/openclaw/openclaw/issues/84753) [Feature]: Show display name instead of user ID in session list
- [#83959](https://github.com/openclaw/openclaw/issues/83959) Codex app-server startup retries can exhaust before replacement server is ready
- [#82662](https://github.com/openclaw/openclaw/issues/82662) [Bug]: Isolated cron agentTurn fails with 'setup timed out before runner start' — all fallback models exhausted on 2026.5.12
- [#79601](https://github.com/openclaw/openclaw/issues/79601) [Bug]: Add client identity labels to gateway WebSocket connections
- [#78954](https://github.com/openclaw/openclaw/issues/78954) Gateway/TUI startup should reach core-ready before channel/plugin sidecars
- [#76756](https://github.com/openclaw/openclaw/issues/76756) [Feature]: plugin-sdk surface for invoking host gateway RPCs (status, models.list, etc.)
- [#74674](https://github.com/openclaw/openclaw/issues/74674) Delivery layer concatenates multiple text content items — pick-one policy needed (split from #69737)
- [#72745](https://github.com/openclaw/openclaw/issues/72745) [Feature]: Introduce Agent-Based Self-Bootstrap Feedback Loop & Business-Driven Code Review Mechanism
- [#71638](https://github.com/openclaw/openclaw/issues/71638) Telegram extension: surface forward_from / via_bot / reply_to_message on MessageReceivedHookEvent

### 🔥 Hot Issues (most commented)
- [#143524](https://github.com/openclaw/openclaw/issues/143524) [Bug]: Agent SQLite WAL grows to 1.4–2.8 GB in days despite wal_autocheckpoint=1000; blocks gateway startup (Windows, 2026.9.2/9.3) — 💬134 · 1d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 256,544 · **Open issues:** 50,699 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.22.5](https://github.com/NousResearch/hermes-agent/releases/tag/v0.22.5) — Hermes Agent v0.22.5

### 🐛 New Issues
- [#143833](https://github.com/NousResearch/hermes-agent/issues/143833) Session list and count calls rescan every lineage receipt on each request (about 130 ms each), backend CPU saturates with many chats `type/perf` `comp/cli` `P2` `area/sessions` `comp/tui-gateway` 💬2
- [#143831](https://github.com/NousResearch/hermes-agent/issues/143831) 0.22.4 regression: legacy session adoption rejects custom source labels — previously resumable sessions become permanently not_found `type/bug` `P3` `area/sessions` `comp/tui-gateway` 💬2
- [#143829](https://github.com/NousResearch/hermes-agent/issues/143829) Desktop: long-history sessions stuck on "Loading session" forever on v0.22.5 — rolling back to v0.22.2 fixes it `type/bug` `comp/gateway` `P2` `area/sessions` `comp/tui-gateway` 💬1
- [#143828](https://github.com/NousResearch/hermes-agent/issues/143828) [Bug]: completion_contract accepts OWNER/<repo> placeholders as real repositories, creating an unfulfillable PR contract `type/bug` `comp/cron` `comp/plugins` `P3`
- [#143826](https://github.com/NousResearch/hermes-agent/issues/143826) Kanban dispatcher should externally notify assignee when gave_up transitions a task to blocked `type/bug` `comp/cron` `comp/plugins` `P2` 💬1
- [#143825](https://github.com/NousResearch/hermes-agent/issues/143825) admission_conflict permanently blocks resume and branch on one desktop local session (v0.22.4, Windows) `type/bug` `comp/gateway` `P2` `area/sessions` 💬1
- [#143824](https://github.com/NousResearch/hermes-agent/issues/143824) kanban PR acceptance: required check with conclusion=skipped classified infra forever, merged PRs can never complete their card `type/bug` `comp/cli` `comp/cron` `comp/plugins` `P2`
- [#143818](https://github.com/NousResearch/hermes-agent/issues/143818) 0.22.4: conversations become permanently unwritable (missing API binding, legacy adoption) and background delegation results never delivered to api_server sessions `type/bug` `comp/gateway` `P2` `area/sessions` 💬1
- [#143817](https://github.com/NousResearch/hermes-agent/issues/143817) Background review can archive an active skill without absorbing anything — the consolidation guard only checks the name `type/bug` `comp/tools` `tool/skills` `P2` 💬2
- [#143816](https://github.com/NousResearch/hermes-agent/issues/143816) [Bug]: UnscopedSecretError for a `docker_forward_env` secret when Desktop re-attaches a sandbox-hosted Bot Screen on a multiplexed gateway `type/bug` `comp/gateway` `tool/terminal` `backend/docker` `area/auth` `P2` `area/profiles` `comp/tui-gateway` 💬2
- [#143814](https://github.com/NousResearch/hermes-agent/issues/143814) [Bug]: Dashboard onboarding wizard loops on umbrelOS with custom (Gemini) provider despite provider being correctly configured `type/bug` `comp/cli` `area/config` `P2` `comp/tui-gateway` 💬1
- [#143810](https://github.com/NousResearch/hermes-agent/issues/143810) TUI: message sent while agent is busy re-renders as a duplicate user bubble; final assistant bubble renders empty (finalTail over-dedupe at message.complete) `type/bug` `comp/tui` `tool/file` `P2` `area/streaming` 💬1
- [#143807](https://github.com/NousResearch/hermes-agent/issues/143807) [Bug]: pinned Chromium 145 (chromium-1208) still trusts the compromised eMudhra intermediates `type/security` `comp/tools` `tool/browser` `P3`
- [#143806](https://github.com/NousResearch/hermes-agent/issues/143806) Logging overload: unbounded queue retains exception traceback graphs and amplifies memory growth `type/perf` `comp/cli` `P2` 💬2

### 🔒 Closed Issues
- [#142324](https://github.com/NousResearch/hermes-agent/issues/142324) Pillow pinned to 12.3.0; GHSA-78g4-xqwv-q3g8 (OpenJPEG heap overflow) fixed only in Pillow 13.0.0
- [#143815](https://github.com/NousResearch/hermes-agent/issues/143815) [Withdrawn] (content removed at author's request)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,037 · **Open issues:** 1,047 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11811](https://github.com/zeroclaw-labs/zeroclaw/pull/11811) fix(plugins): report the runtime's config refusal in plugin info and list --verify

### 🐛 New Issues
- [#12009](https://github.com/zeroclaw-labs/zeroclaw/issues/12009) [Bug]: Security job fails on every build: RUSTSEC-2026-0385 (ctutils 0.4.2) and RUSTSEC-2026-0386 (tokio 1.53.1) `bug` `dependencies` `release:v0.8.7`
- [#12008](https://github.com/zeroclaw-labs/zeroclaw/issues/12008) [Bug]: cron announcements and one-off sends go out through a disabled channel instance; only the QQ arm honours enabled
- [#12006](https://github.com/zeroclaw-labs/zeroclaw/issues/12006) [Bug]: tool_search serves a deferred tool's schema as copied at registry build, so a schema that follows live config goes stale after a reload
- [#12005](https://github.com/zeroclaw-labs/zeroclaw/issues/12005) [Bug]: PowerShell dialect rejects any command with a bare `@` in an argument (allowlisted mail CLI unusable)
- [#12002](https://github.com/zeroclaw-labs/zeroclaw/issues/12002) [Bug]: gateway and ACP turns autosave every user message under the same memory key, so each one overwrites the last
- [#12001](https://github.com/zeroclaw-labs/zeroclaw/issues/12001) RFC: MITM egress proxy to control what the agent can access and to keep secrets hidden from the agent `type:rfc`
- [#12000](https://github.com/zeroclaw-labs/zeroclaw/issues/12000) [Feature]: Add DeepSeek Web Search provider `enhancement`
- [#11996](https://github.com/zeroclaw-labs/zeroclaw/issues/11996) [Feature]: send_via: explicit attachments checked under the read policy
- [#11992](https://github.com/zeroclaw-labs/zeroclaw/issues/11992) [Feature]: Email channel: operator templates and a sanitised HTML body for send_via 💬1
- [#11991](https://github.com/zeroclaw-labs/zeroclaw/issues/11991) [Bug]: outbound email HTML carries raw markup and arbitrary image URLs from the agent's text 💬1
- [#11989](https://github.com/zeroclaw-labs/zeroclaw/issues/11989) [Bug]: per-channel excluded_tools is never applied 💬1
- [#11987](https://github.com/zeroclaw-labs/zeroclaw/issues/11987) [Bug]: Inline nosemgrep comments don't stop Semgrep code scanning alerts `bug` 💬1
- [#11985](https://github.com/zeroclaw-labs/zeroclaw/issues/11985) [Task]: Gateway tests for scoped dashboard chat under JWKS validation, a failed write and a retirement race `gateway` `tests` `follow-up` `type:test` 💬1
- [#11984](https://github.com/zeroclaw-labs/zeroclaw/issues/11984) [Feature]: Dashboard chat for signed-in accounts without administrator rights `enhancement` `gateway` `web` `release:v0.9.0` 💬1
- [#11972](https://github.com/zeroclaw-labs/zeroclaw/issues/11972) [Bug]: zeroclaw gateway get-paircode exits 0 when it cannot fetch a code `bug` `gateway` 💬1

### 🔒 Closed Issues
- [#11876](https://github.com/zeroclaw-labs/zeroclaw/issues/11876) RFC: Focus PR review on purpose, safety, and quality

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,671 · **Open issues:** 1,565 · **Last push:** 23h ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,906 · **Open issues:** 120 · **Last push:** 6h ago

### 🚀 New Releases
- [20261023.01](https://github.com/moltis-org/moltis/releases/tag/20261023.01) — 20261023.01

### ✅ Merged PRs
- [#1318](https://github.com/moltis-org/moltis/pull/1318) fix(providers): use canonical NEAR AI catalog model
- [#1317](https://github.com/moltis-org/moltis/pull/1317) fix(providers): correct DeepSeek thinking tests and refresh Z.AI models

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬1 · 1d ago
- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 9d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 18d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 26d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 28d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 38d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 46d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 48d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 56d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 60d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Research] Alignment Assessment Ukaisi](https://www.anthropic.com/research/alignment-assessment-ukaisi) _2026-10-23_

### OpenAI — 2 new
- [Cyber At The Frontier](https://openai.com/cyber-at-the-frontier/) _2026-10-24_
- [[Index] Scaling Storage One Billion Users Part Two](https://openai.com/index/scaling-storage-one-billion-users-part-two/) _2026-10-24_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/singularity — top 2 new
- [Hacker reverse engineers his Samsung TV and finds on-device AI listening for your dog and baby, watching what you watch, and borrowing your soundbar's mic if the TV doesn't have one. Then OpenAI banne](https://reddit.com/r/singularity/comments/1xduimx/hacker_reverse_engineers_his_samsung_tv_and_finds/) ↑1588
- [Babe wake up Kimi K3.1 is rated higher than Fable 5.1 on Artificial Analysis](https://reddit.com/r/singularity/comments/1xdligf/babe_wake_up_kimi_k31_is_rated_higher_than_fable/) ↑1129

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Stop babysitting self-hosters who know exactly what they're doing](https://reddit.com/r/openclaw/comments/1wpa99h/stop_babysitting_selfhosters_who_know_exactly/) ↑42
- [Stop burning tokens on solved problems: How my 12-year-old Office PC handles Email, OCR, and TTS for $0](https://reddit.com/r/openclaw/comments/1xdpnvm/stop_burning_tokens_on_solved_problems_how_my/) ↑30
- [I'm demoing OpenClaw on GitHub's Open Source Friday tomorrow](https://reddit.com/r/openclaw/comments/1xd0dyp/im_demoing_openclaw_on_githubs_open_source_friday/) ↑9
- [COME SPEND OUR TOKENS](https://reddit.com/r/openclaw/comments/1xcrtzi/come_spend_our_tokens/) ↑5
- [Which AI model should I choose?](https://reddit.com/r/openclaw/comments/1xdivd8/which_ai_model_should_i_choose/) ↑4

### X — @openclaw
- [What is OpenClaw Enterprise, and why does it matter?


@heyneighbor
  sat down with 
@kevins8
 to talk about:

- What Op](https://x.com/openclaw/status/2113756866300010520) ↑0 🔁0 · recent
- [The #1 blocker for enterprise agents is security. 

Agents are powerful because they're non-deterministic, so the questi](https://x.com/openclaw/status/2113756869064110267) ↑0 🔁0 · recent


### X — @steipete
- [I’ll wait a bit before thinking about a new phone.](https://x.com/steipete/status/2113788999303385180) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
