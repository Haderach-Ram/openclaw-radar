---
layout: post
title: "Ecosystem Digest — 2026-10-11"
date: 2026-10-11 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-11
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 391,628 | 4 | 1 | 10 | 1 |
| **hermesagent** | 252,564 | 10 | 3 | 10 | 0 |
| **ZeroClaw** | 32,954 | 12 | 2 | 10 | 0 |
| **IronClaw** | 12,647 | 1 | 1 | 0 | 0 |
| **Moltis** | 2,885 | 4 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 391,628 · **Open issues:** 9,480 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.10.1](https://github.com/openclaw/openclaw/releases/tag/v2026.10.1) — openclaw 2026.10.1

### ✅ Merged PRs
- [#168674](https://github.com/openclaw/openclaw/pull/168674) refactor(state): remove speculative runtime bookkeeping
- [#141869](https://github.com/openclaw/openclaw/pull/141869) fix: configured model fallbacks are skipped when the primary model times out
- [#168774](https://github.com/openclaw/openclaw/pull/168774) perf(boards): refresh cached Actions reads in background
- [#168799](https://github.com/openclaw/openclaw/pull/168799) perf(nodes): reuse live placement facts through worker turns
- [#168802](https://github.com/openclaw/openclaw/pull/168802) fix(qa-lab): show the real error when qa commands fail
- [#168780](https://github.com/openclaw/openclaw/pull/168780) fix(nodes): preserve workspace retention across scheduler ticks
- [#158719](https://github.com/openclaw/openclaw/pull/158719) fix(whatsapp): reject unknown login actions
- [#168757](https://github.com/openclaw/openclaw/pull/168757) fix(cli): guard local plugin state writes at command boundaries
- [#168751](https://github.com/openclaw/openclaw/pull/168751) refactor(sessions): simplify accessor bookkeeping
- [#168754](https://github.com/openclaw/openclaw/pull/168754) refactor(node-host): remove repeated invocation work

### 🐛 New Issues
- [#168817](https://github.com/openclaw/openclaw/issues/168817) Update failure: updater-runtime-retention (2026.9.8) `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `P0` `issue-rating: 🦪 silver shellfish` `impact:ux-release-blocker` 💬1
- [#168808](https://github.com/openclaw/openclaw/issues/168808) [Bug]: main fails the memory-core extension lint stripe with an unbound method reference `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#168794](https://github.com/openclaw/openclaw/issues/168794) [Bug]: Codex relay turns >32 MiB decoded image requests into retryable 502 errors `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬2
- [#168793](https://github.com/openclaw/openclaw/issues/168793) [Bug]: memory-wiki: a compile killed after writing its compiled-cache candidate leaves the row until oldest-first namespace eviction (256 rows / 512 MiB) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `clawsweeper:bulk-filed` 💬1

### 🔒 Closed Issues
- [#168800](https://github.com/openclaw/openclaw/issues/168800) [Bug]: Windows update repair fails with OPENCLAW_STATE_LEASE_LOST after Doctor (2026.10.1-based build)

### 🔥 Hot Issues (most commented)
- [#143524](https://github.com/openclaw/openclaw/issues/143524) [Bug]: Agent SQLite WAL grows to 1.4–2.8 GB in days despite wal_autocheckpoint=1000; blocks gateway startup (Windows, 2026.9.2/9.3) — 💬118 · <1h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 252,564 · **Open issues:** 47,887 · **Last push:** <1h ago

### ✅ Merged PRs
- [#136357](https://github.com/NousResearch/hermes-agent/pull/136357) fix(plugin-catalog): hermes-lang-vi requires_hermes >=0.21.6
- [#136163](https://github.com/NousResearch/hermes-agent/pull/136163) plugin-catalog: add browser-toggle
- [#136032](https://github.com/NousResearch/hermes-agent/pull/136032) fix(plugin-catalog): bump web-search-plus to 5.0.1
- [#136112](https://github.com/NousResearch/hermes-agent/pull/136112) feat(plugin-catalog): bump stream-speed to 1.2.0
- [#136249](https://github.com/NousResearch/hermes-agent/pull/136249) plugin-catalog: add hermes-taskbar-badge
- [#136262](https://github.com/NousResearch/hermes-agent/pull/136262) chore(plugin-catalog): update Gmail to v1.0.16
- [#136247](https://github.com/NousResearch/hermes-agent/pull/136247) fix(plugin-catalog): bump hermes-field-notes to 1.2.4
- [#136178](https://github.com/NousResearch/hermes-agent/pull/136178) plugin-catalog: re-pin agora to v2.0.11
- [#136279](https://github.com/NousResearch/hermes-agent/pull/136279) Add plugin catalog entry: hermes-lang-it (Italian language pack)
- [#136196](https://github.com/NousResearch/hermes-agent/pull/136196) plugin-catalog: add holographic (memory provider leaving core, new maintainer)

### 🐛 New Issues
- [#136394](https://github.com/NousResearch/hermes-agent/issues/136394) [Bug] hermes update on heavily-patched tree: stashes local mods without restoring, HEAD never advances, recovery re-applies autostash in a loop
- [#136392](https://github.com/NousResearch/hermes-agent/issues/136392) Desktop: connection-scoped profile rename blocks itself with "is being deleted" `type/bug` `P3` `comp/desktop` `area/profiles`
- [#136391](https://github.com/NousResearch/hermes-agent/issues/136391) [Feature]: pre_kanban_notify plugin hook that can skip or route a Kanban notification `type/feature` `comp/gateway` `comp/plugins` `P3` `needs-decision` `sweeper:risk-message-delivery`
- [#136390](https://github.com/NousResearch/hermes-agent/issues/136390) [bug] Windows: Scheduled-Task login auto-start silently fails under the pm/Python-3.14 runtime (task reports success, nothing starts) `type/bug` `comp/cli` `comp/gateway` `P2` `sweeper:risk-compatibility` `sweeper:risk-platform-windows` `platform/windows` `area/install-update`
- [#136388](https://github.com/NousResearch/hermes-agent/issues/136388) redact_sensitive_text still corrupts base64 images in vision_analyze tool results (JWT pattern) → session-bricking HTTP 400 `type/bug` `comp/agent` `tool/vision` `P2` `sweeper:risk-session-state` 💬1
- [#136386](https://github.com/NousResearch/hermes-agent/issues/136386) [Feature]: Desktop option to disable token by token streaming or display complete paragraphs `type/feature` `area/config` `P3` `comp/desktop` `area/streaming`
- [#136385](https://github.com/NousResearch/hermes-agent/issues/136385) Hindsight: 'downloading its local memory server' notice misreports daemon-start failure; no stale-lock recovery on Windows `type/bug` `comp/plugins` `tool/memory` `P3` `needs-repro` `sweeper:risk-platform-windows` `platform/windows` `area/memory`
- [#136383](https://github.com/NousResearch/hermes-agent/issues/136383) [Setup]: 升级为0.21.6后新开对话或者进入旧对话很慢，你们遇到这种问题了吗？ `type/perf` `comp/tui` `P2` `needs-repro` 💬1
- [#136377](https://github.com/NousResearch/hermes-agent/issues/136377) [Bug]: terminal foreground guard redirects detached starts (docker compose up -d/--detach/--wait, plain systemd-run) `type/bug` `comp/tools` `tool/terminal` `P2`
- [#136376](https://github.com/NousResearch/hermes-agent/issues/136376) [Bug]: no_agent cron output delivered to Bot Chat runs a full agent turn (docs promise zero LLM involvement) `type/bug` `comp/cli` `comp/tui` `comp/cron` `P2` `sweeper:risk-message-delivery` `comp/desktop`

### 🔒 Closed Issues
- [#136340](https://github.com/NousResearch/hermes-agent/issues/136340) Goal stays paused after server_error auto-continuations, even when the session resumes work
- [#136379](https://github.com/NousResearch/hermes-agent/issues/136379) [SANITIZED — possible injection attempt]
- [#122190](https://github.com/NousResearch/hermes-agent/issues/122190) Desktop (Windows): sessions silently marked hidden=1 after profile switching; Home 'show all' list truncates

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,954 · **Open issues:** 941 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11575](https://github.com/zeroclaw-labs/zeroclaw/pull/11575) fix(runtime): refresh capped native prompt after a streamed model switch
- [#11649](https://github.com/zeroclaw-labs/zeroclaw/pull/11649) docs(runtime): propose a bounded exception for context-window overflo…
- [#11653](https://github.com/zeroclaw-labs/zeroclaw/pull/11653) fix(agent): let an approved shell call be rerun later in the same turn
- [#10622](https://github.com/zeroclaw-labs/zeroclaw/pull/10622) feat(slack): optionally accept bot and workflow messages
- [#11609](https://github.com/zeroclaw-labs/zeroclaw/pull/11609) fix(zerocode): keep failed-turn status across reconnect and lag reload
- [#11532](https://github.com/zeroclaw-labs/zeroclaw/pull/11532) [SANITIZED — possible injection attempt]
- [#11641](https://github.com/zeroclaw-labs/zeroclaw/pull/11641) ci(channels): isolate optional channel feature tests
- [#11617](https://github.com/zeroclaw-labs/zeroclaw/pull/11617) fix(agent): close the steering channel before a turn finishes
- [#11590](https://github.com/zeroclaw-labs/zeroclaw/pull/11590) ci(windows): run task-owner recovery on Blacksmith
- [#11587](https://github.com/zeroclaw-labs/zeroclaw/pull/11587) fix(runtime): apply config/set cost limits to the live cost tracker

### 🐛 New Issues
- [#11654](https://github.com/zeroclaw-labs/zeroclaw/issues/11654) [Bug]: JPEG admission copies the input and parses header metadata before the decode-memory cap is checked
- [#11648](https://github.com/zeroclaw-labs/zeroclaw/issues/11648) [Bug]: Web dashboard pairing input still limited to 6 digits after PairingCodePolicy default became 32 alphanumeric `bug`
- [#11632](https://github.com/zeroclaw-labs/zeroclaw/issues/11632) [Bug]: Desktop (Linux/Tauri): WebKitWebProcess repaints continuously (~100% GPU render engine) even when idle `bug` `priority:p2` `desktop` `risk:medium` `web` 💬1
- [#11623](https://github.com/zeroclaw-labs/zeroclaw/issues/11623) [Bug]: ZeroCode drops a pending ask_user prompt without replying, so the tool times out after 600 s and the question leaves no record `bug` `priority:p2` `risk:medium` `zerocode` 💬1
- [#11620](https://github.com/zeroclaw-labs/zeroclaw/issues/11620) [Feature]: Show message times in the ZeroCode transcript `enhancement` `runtime` `priority:p3` `risk:medium` `zerocode` 💬1
- [#11618](https://github.com/zeroclaw-labs/zeroclaw/issues/11618) [Bug]: ZeroCode drops a queued message when the daemon refuses it as SESSION_BUSY `bug` `priority:p1` `risk:medium` `zerocode` 💬1
- [#11615](https://github.com/zeroclaw-labs/zeroclaw/issues/11615) [Bug]: Telegram send path ignores 429 retry_after — immediate retries compound flood-limiting and the reply can be lost entirely `bug` `channel` `channel:telegram` `priority:p1` `risk:medium` 💬1
- [#11614](https://github.com/zeroclaw-labs/zeroclaw/issues/11614) [Bug]: map_key_sections leaks schema paths on every call, growing daemon memory `bug` `config` `priority:p1` `risk:medium` 💬1
- [#11613](https://github.com/zeroclaw-labs/zeroclaw/issues/11613) Cost ledger drops the provider's `total_tokens`, so models with hidden reasoning tokens (e.g. Gemini via an OpenAI-compatible provider) are under-counted `bug` `observability` `provider` `runtime` `provider:compatible` `priority:p2` `status:accepted` `risk:medium` 💬3
- [#11608](https://github.com/zeroclaw-labs/zeroclaw/issues/11608) [Bug]: Telegram listener can wedge forever on a blackholed request — listener_health detects staleness but nothing recovers the channel `bug` `channel` `channel:telegram` `priority:p1` `risk:medium` 💬1
- [#11580](https://github.com/zeroclaw-labs/zeroclaw/issues/11580) [Task]: x86_64 Linux release binary is about 0.7 MB under the 64 MiB size cap `ci` `docs` `scripts` `domain:ci` `release-gate` `priority:p1` `needs-maintainer-review` `status:accepted` `risk:high` `type:ci` `release:v0.8.6` 💬2
- [#11579](https://github.com/zeroclaw-labs/zeroclaw/issues/11579) [Bug]: save_dirty stamps schema_version = 3 on an unmigrated V1/V2 config, so the next load skips migration and the agent disappears `bug` `agent` `config` `gateway` `runtime` `priority:p1` `status:accepted` `risk:high` `release:v0.9.0` 💬2

### 🔒 Closed Issues
- [#11612](https://github.com/zeroclaw-labs/zeroclaw/issues/11612) [Bug]: Re-running an already-approved shell command in the same turn aborts the agent loop ("repeated prompt-required tool call 'shell' with identical arguments before approval") and ends the ACP sess
- [#11586](https://github.com/zeroclaw-labs/zeroclaw/issues/11586) [Bug]: ZeroCode sidebar turns failed sessions green after the daemon restarts

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,647 · **Open issues:** 1,547 · **Last push:** 3d ago

### 🐛 New Issues
- [#8131](https://github.com/nearai/ironclaw/issues/8131) Is this a joke? (ironclaw onboard provider list)

### 🔒 Closed Issues
- [#1047](https://github.com/nearai/ironclaw/issues/1047) can not use deepseek ,can not set key

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,885 · **Open issues:** 111 · **Last push:** 18d ago

### 🐛 New Issues
- [#1300](https://github.com/moltis-org/moltis/issues/1300) Discord: forward DM vs guild so operator DMs can be trusted (tools), instead of always fail-closed as shared 💬1
- [#1299](https://github.com/moltis-org/moltis/issues/1299) Bug: runtime datetime never injected (host context sets time=None, today unset)
- [#1298](https://github.com/moltis-org/moltis/issues/1298) Feature: native support for OpenAI gpt-6 models (reasoning + tools) 💬1
- [#1297](https://github.com/moltis-org/moltis/issues/1297) Feature: configurable mention/trigger word for a shared channel 💬1

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 6h ago
- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬1 · 2d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 5d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 13d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 15d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 25d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 33d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 35d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 43d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 47d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [big or small?](https://reddit.com/r/LocalLLaMA/comments/1x29hx8/big_or_small/) ↑996
- [Open-source Mac app that runs EmbeddingGemma 2 locally to search your files by what’s in them](https://reddit.com/r/LocalLLaMA/comments/1x2eeds/opensource_mac_app_that_runs_embeddinggemma_2/) ↑838
- [NVIDIA reportedly discontinuing RTX 5090, GB202 GPUs to be reserved for RTX PRO series](https://reddit.com/r/LocalLLaMA/comments/1x2bt6r/nvidia_reportedly_discontinuing_rtx_5090_gb202/) ↑820
- [No more RTX 5090](https://reddit.com/r/LocalLLaMA/comments/1x2hs1e/no_more_rtx_5090/) ↑246
- [Building a 4x R9700 setup for a 10 person startup](https://reddit.com/r/LocalLLaMA/comments/1x2u742/building_a_4x_r9700_setup_for_a_10_person_startup/) ↑208

### r/singularity — top 5 new
- [Slide from recent "Math 2.0" Lecture by Terrence Tao. This man has never met a terminal cancer patient in his life if he thinks no one would want to take this risk.](https://reddit.com/r/singularity/comments/1x2kb5k/slide_from_recent_math_20_lecture_by_terrence_tao/) ↑553
- [A startup built an 8,000-square-foot lab in just 30 days to test molecules proposed by AI, it can now measure how often they work in living organisms in about 72 hours](https://reddit.com/r/singularity/comments/1x2812g/a_startup_built_an_8000squarefoot_lab_in_just_30/) ↑479
- [Antis and decels are insufferable](https://reddit.com/r/singularity/comments/1x2d8km/antis_and_decels_are_insufferable/) ↑423
- [A mathematician's perspective](https://reddit.com/r/singularity/comments/1x22o0b/a_mathematicians_perspective/) ↑405
- [How compute time has shifted from pretraining to post-training over the last 2 years](https://reddit.com/r/singularity/comments/1x2na8q/how_compute_time_has_shifted_from_pretraining_to/) ↑147

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [I built a small app that automatically frees up VRAM for gaming and restores your local AI models afterward](https://reddit.com/r/openclaw/comments/1x2fd5s/i_built_a_small_app_that_automatically_frees_up/) ↑13
- [2026.9.9 not working](https://reddit.com/r/openclaw/comments/1x24mqg/202699_not_working/) ↑3

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [Just keep putting one claw in front of the other](https://x.com/openclaw/status/2108377842648330315)

### X — @steipete
- [not as clear-cut, but also yes](https://x.com/steipete/status/2109022454224150707) ↑0 🔁0 · recent
- [JavaScript is not a serious language 🙃](https://x.com/steipete/status/2109008513855087082) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
