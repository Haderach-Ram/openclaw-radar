---
layout: post
title: "Ecosystem Digest — 2026-09-01"
date: 2026-09-01 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-01
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 388,330 | 8 | 3 | 10 | 1 |
| **hermesagent** | 239,055 | 11 | 1 | 10 | 1 |
| **ZeroClaw** | 32,695 | 8 | 1 | 3 | 0 |
| **IronClaw** | 12,602 | 10 | 3 | 3 | 0 |
| **Moltis** | 2,841 | 1 | 1 | 2 | 2 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 388,330 · **Open issues:** 5,898 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.8.1](https://github.com/openclaw/openclaw/releases/tag/v2026.8.1) — OpenClaw 2026.8.1

### ✅ Merged PRs
- [#134645](https://github.com/openclaw/openclaw/pull/134645) chore(ui): refresh control ui locales
- [#134637](https://github.com/openclaw/openclaw/pull/134637) test(ui): remove duplicate task detail reset case
- [#134642](https://github.com/openclaw/openclaw/pull/134642) test(gateway): share title-retention disk fixtures across isolated readers
- [#134478](https://github.com/openclaw/openclaw/pull/134478) UI: simplify Side chat clear action
- [#134083](https://github.com/openclaw/openclaw/pull/134083) fix(outbound): a delivery mirrored into another session is silently dropped
- [#134568](https://github.com/openclaw/openclaw/pull/134568) fix: migrate identical session event replays
- [#134624](https://github.com/openclaw/openclaw/pull/134624) test(memory): remove duplicate nested batch error case
- [#134640](https://github.com/openclaw/openclaw/pull/134640) refactor(migrate-hermes): consolidate provider and config plumbing
- [#134635](https://github.com/openclaw/openclaw/pull/134635) test(openai): signal transcription socket creation and own cleanup
- [#134629](https://github.com/openclaw/openclaw/pull/134629) fix(release): run frozen package checks from trusted sparse tooling

### 🐛 New Issues
- [#134649](https://github.com/openclaw/openclaw/issues/134649) [Bug]: Gateway shutdown hangs 5+ minutes when local llama-server child process doesn't terminate with parent `bug` `bug:behavior`
- [#134647](https://github.com/openclaw/openclaw/issues/134647) bug: sidebar pin tooltips repeat session titles `maintainer` 💬1
- [#134644](https://github.com/openclaw/openclaw/issues/134644) [Bug]: Slack mid-turn steering merges second answer into first assistant message 💬1
- [#134638](https://github.com/openclaw/openclaw/issues/134638) [Bug]: Installer prints an `Installer log:` path that is normally deleted before the user can read it `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬3
- [#134625](https://github.com/openclaw/openclaw/issues/134625) Chat/activity streams bounce back from the bottom in long sessions `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:linked-pr-open` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:ux-friction` 💬1
- [#134621](https://github.com/openclaw/openclaw/issues/134621) [Bug]: macOS computer input executes, then result validation rejects it `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬2
- [#134619](https://github.com/openclaw/openclaw/issues/134619) [Bug]: Upgrade to 8.1 Completely Breaks Existing Installation and Major Features `bug` `regression` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `impact:crash-loop` `issue-rating: 🦪 silver shellfish` `maturity:stable` 💬1
- [#134616](https://github.com/openclaw/openclaw/issues/134616) [Bug]: The upgrade of OpenClaw from 2026.7.1 to 2026.8.1 has been unsuccessful. `bug` `regression` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:other` `maturity:stable` 💬1

### 🔒 Closed Issues
- [#133941](https://github.com/openclaw/openclaw/issues/133941) Session list title previews retain full prompt strings in Gateway memory
- [#132766](https://github.com/openclaw/openclaw/issues/132766) Outbound delivery mirror takes its transcript writer fence with no arguments, so cross-session mirrors into a rebound target session are silently dropped
- [#134455](https://github.com/openclaw/openclaw/issues/134455) Legacy session migration cannot converge on byte-identical duplicate leaf records

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 239,055 · **Open issues:** 38,120 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.8.31](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.8.31) — Hermes Agent v0.21.0 (v2026.8.31)

### ✅ Merged PRs
- [#96839](https://github.com/NousResearch/hermes-agent/pull/96839) Make the tips/tours switches reach the agent
- [#99917](https://github.com/NousResearch/hermes-agent/pull/99917) fmt(js): `npm run fix` auto-fix
- [#99916](https://github.com/NousResearch/hermes-agent/pull/99916) fix(desktop): dock the sidebar rails down to 640px
- [#96612](https://github.com/NousResearch/hermes-agent/pull/96612) feat(desktop): collapse Yesterday / Last week groups in the sessions sidebar
- [#99906](https://github.com/NousResearch/hermes-agent/pull/99906) fix(tui_gateway): retire recovery marker on local stop (supersedes #72231)
- [#99764](https://github.com/NousResearch/hermes-agent/pull/99764) fix(desktop): make /stop interrupt active turns
- [#99878](https://github.com/NousResearch/hermes-agent/pull/99878) fix(bot-mode): keep Bot Chat open on its compression lineage (supersedes #97416)
- [#99210](https://github.com/NousResearch/hermes-agent/pull/99210) refactor(dashboard-auth): replace PKCE cookie payload with base64url(JSON) codec
- [#97067](https://github.com/NousResearch/hermes-agent/pull/97067) fix(desktop): recycle stale SSH backend after post-update Models-page 503 (#97046)
- [#99890](https://github.com/NousResearch/hermes-agent/pull/99890) fix(desktop): restore the transcript when regenerate is rejected (supersedes #95848)

### 🐛 New Issues
- [#99918](https://github.com/NousResearch/hermes-agent/issues/99918) plugins doctor should unload registrations before deleting temporary home on Windows
- [#99911](https://github.com/NousResearch/hermes-agent/issues/99911) Windows: hermes update crashes with 'Gateway ownership is ambiguous' when gateway runs via Scheduled Task
- [#99897](https://github.com/NousResearch/hermes-agent/issues/99897) Output-cap retry clamp is computed but not applied to the retried request (spins until max compression attempts) `type/bug` `comp/agent` `provider/qwen` `P2` `sweeper:risk-compatibility` `area/compression` 💬1
- [#99895](https://github.com/NousResearch/hermes-agent/issues/99895) [Bug]: Windows: AttributeError: module 'asyncio' has no attribute 'start_unix_server' in shutdown_watchdog (v0.21.0) `type/bug` `duplicate` `comp/gateway` `P2` `sweeper:risk-platform-windows` `platform/windows` `bug` 💬1
- [#99889](https://github.com/NousResearch/hermes-agent/issues/99889) [Bug]: Desktop (Windows): interaction freezes dominated by style recalculation — 48% of renderer main-thread time, single recalcs up to 1.4 s over ~6k nodes (invalidation-tracking traces included) `type/perf` `P2` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows`
- [#99886](https://github.com/NousResearch/hermes-agent/issues/99886) Unofficial Grok Bot provider (Cursor sand ConnectRPC) `type/feature` `comp/agent` `comp/cli` `area/auth` `area/config` `P3` `needs-decision` `sweeper:risk-security-boundary` `sweeper:risk-compatibility` `area/usage-cost` 💬2
- [#99882](https://github.com/NousResearch/hermes-agent/issues/99882) [Bug]: Queued follow-ups (demoted to queue during context compression) are silently orphaned — messages lost, no log `type/bug` `comp/gateway` `P1` `sweeper:risk-session-state` `sweeper:risk-message-delivery` `area/compression` 💬1
- [#99879](https://github.com/NousResearch/hermes-agent/issues/99879) Routines run late after gateway downtime with no missed-run status `type/bug` `comp/gateway` `comp/cron` `P1` `sweeper:risk-message-delivery` `sweeper:risk-compatibility` `sweeper:risk-automation`
- [#99877](https://github.com/NousResearch/hermes-agent/issues/99877) [Bug]: requires_toolsets gate has no alias normalization — a skill declaring 'files' is silently gated out forever `type/bug` `comp/agent` `tool/skills` `P2` 💬1
- [#99876](https://github.com/NousResearch/hermes-agent/issues/99876) [Feature]: Email platform - add read-only / no-auto-reply mode `type/feature` `comp/plugins` `platform/email` `area/config` `P3` `sweeper:risk-message-delivery` `sweeper:risk-compatibility`
- [#99875](https://github.com/NousResearch/hermes-agent/issues/99875) meta/muse-spark-1.2-contributor catalog-listed on api.meta.ai but POST /v1/responses|/v1/chat/completions 404 via Hermes (Muse TUI same key 200) `type/bug` `comp/plugins` `P3` `needs-repro`

### 🔒 Closed Issues
- [#97046](https://github.com/NousResearch/hermes-agent/issues/97046) [Bug]: Desktop (SSH remote backend): post-update code-skew 503 on Models page shows raw JSON + wrong (systemd) restart advice; Desktop-owned SSH backends stay stale

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,695 · **Open issues:** 823 · **Last push:** <1h ago

### ✅ Merged PRs
- [#9963](https://github.com/zeroclaw-labs/zeroclaw/pull/9963) feat(vi): add SD-JWT disclosure resolution and reference test vectors
- [#10508](https://github.com/zeroclaw-labs/zeroclaw/pull/10508) fix(security): patch wasmtime sandbox escape
- [#10142](https://github.com/zeroclaw-labs/zeroclaw/pull/10142) feat(zerorelay): secure transport with blind relay and native mTLS enrollment (supersedes #9080)

### 🐛 New Issues
- [#10523](https://github.com/zeroclaw-labs/zeroclaw/issues/10523) [Bug]: Bootstrap file truncation at 6000 chars is invisible to the operator
- [#10513](https://github.com/zeroclaw-labs/zeroclaw/issues/10513) [Bug]: RPC `sops.run` returns a run ID for a step nothing will execute `bug` `daemon` `runtime` `priority:p1` `tool:sop` `status:accepted` `risk:high` 💬1
- [#10510](https://github.com/zeroclaw-labs/zeroclaw/issues/10510) [Docs]: Upgrade mdBook to 0.5.4 and adopt built-in image zoom `ci` `docs` `dependencies` `priority:p3` `risk:medium` `type:docs` `type:ci` `type:dependencies`
- [#10509](https://github.com/zeroclaw-labs/zeroclaw/issues/10509) [Docs]: Add text scaling and diagram zoom to the docs reader `enhancement` `docs` `priority:p3` `risk:low` `type:docs`
- [#10506](https://github.com/zeroclaw-labs/zeroclaw/issues/10506) Sequential wasi:http requests in one plugin invocation intermittently fail (stale connection); batching avoids it `bug` `runtime` `runtime:wasm` `domain:web-fetch` `priority:p2` `risk:high` 💬1
- [#10505](https://github.com/zeroclaw-labs/zeroclaw/issues/10505) Plugin instantiation fails with cryptic 'no matching implementation in the linker' (registered: 0) on a WIT version skew `bug` `runtime` `runtime:wasm` `priority:p2` `r:needs-repro` `risk:medium` 💬1
- [#10501](https://github.com/zeroclaw-labs/zeroclaw/issues/10501) MCP tool-result images 400 on OpenAI-compatible providers (image part in a role:tool message) `bug` `provider` `tool` `provider:compatible` `priority:p1` `tool:mcp` `status:in-progress` `risk:medium` 💬1
- [#10495](https://github.com/zeroclaw-labs/zeroclaw/issues/10495) [Bug]: Config::save() can replace an operator's populated config.toml with a near-empty file `bug` `config` `priority:p0` `status:accepted` `risk:high` 💬2

### 🔒 Closed Issues
- [#10497](https://github.com/zeroclaw-labs/zeroclaw/issues/10497) [Feature]: pairing-code lifetime controls: startup-code TTL and the dead pairing_dashboard fields

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,602 · **Open issues:** 1,491 · **Last push:** <1h ago

### ✅ Merged PRs
- [#7977](https://github.com/nearai/ironclaw/pull/7977) fix(loop): terminate on dominant repeated output, cap interactive wall clock
- [#7992](https://github.com/nearai/ironclaw/pull/7992) ci: unify bounded integration execution
- [#7995](https://github.com/nearai/ironclaw/pull/7995) fix(ci): stabilize main branch coverage checks

### 🐛 New Issues
- [#8009](https://github.com/nearai/ironclaw/issues/8009) MCP egress errors flatten to "response_error", making discovery failures undiagnosable
- [#8008](https://github.com/nearai/ironclaw/issues/8008) Hosted-MCP discovery: a leak-blocked tools/list page discards the entire catalog
- [#8007](https://github.com/nearai/ironclaw/issues/8007) Progressive reply publication: decomposition and aggregation follow-ups
- [#8004](https://github.com/nearai/ironclaw/issues/8004) Daily ironclaw failure taxonomy — 2026-08-31
- [#7987](https://github.com/nearai/ironclaw/issues/7987) tool schemas: flatten_top_level rebuilds from a whitelist, silently discarding every non-forbidden top-level constraint `bug` `scope: llm` 💬1
- [#7986](https://github.com/nearai/ironclaw/issues/7986) perf(github): list_repos ships 81 raw fields per repo — 519 KB for one listing, with the package's own projection seam unused `bug` `scope: extensions` `suggested_P2` 💬1
- [#7890](https://github.com/nearai/ironclaw/issues/7890) Retire the app.css Tailwind colour-alias compat layer before the WS3b reskin `module:M1-webui-product` `scope: webui` `ux` 💬1
- [#7782](https://github.com/nearai/ironclaw/issues/7782) Epic: Design System Phases 4–5 — agentic interactions, components & information architecture `module:M1-webui-product` `scope: webui` `epic` `ux` 💬1
- [#7781](https://github.com/nearai/ironclaw/issues/7781) Epic: Design System Phases 2–3 — DESIGN.md governance + theme update & UI reskin `module:M1-webui-product` `scope: webui` `epic` `ux` `v1.4.0` 💬2
- [#7042](https://github.com/nearai/ironclaw/issues/7042) Design System — Phase 2: DESIGN.md governance & guidelines `module:M1-webui-product` `scope: webui` `ux` 💬2

### 🔒 Closed Issues
- [#7892](https://github.com/nearai/ironclaw/issues/7892) bug(agent-loop): deferred tool found 15x, never invoked — 123s run with 4 distinct calls and no terminating guard
- [#8002](https://github.com/nearai/ironclaw/issues/8002) Fix main branch CI failures 20260831
- [#7038](https://github.com/nearai/ironclaw/issues/7038) Epic: Design System Phase 1 — Storybook integration & design-system catalog

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,841 · **Open issues:** 80 · **Last push:** 5h ago

### 🚀 New Releases
- [20260831.01](https://github.com/moltis-org/moltis/releases/tag/20260831.01) — 20260831.01
- [20260830.01](https://github.com/moltis-org/moltis/releases/tag/20260830.01) — 20260830.01

### ✅ Merged PRs
- [#1248](https://github.com/moltis-org/moltis/pull/1248) fix(exec): honor explicit null node selection
- [#1221](https://github.com/moltis-org/moltis/pull/1221) fix(gateway): pin Snyk Agent Scan

### 🐛 New Issues
- [#1118](https://github.com/moltis-org/moltis/issues/1118) [Feature]: Add Kubernetes-native sandbox backend with runtimeClassName support 💬3

### 🔒 Closed Issues
- [#1246](https://github.com/moltis-org/moltis/issues/1246) [Bug]: can't run on sandbox after a node is added

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 1d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 3d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 7d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 19d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 22d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 25d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 27d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 29d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 31d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 31d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Improving Alignment Security Efforts](https://www.anthropic.com/news/improving-alignment-security-efforts) _2026-08-31_

### OpenAI — 1 new
- [[Index] Polimill](https://openai.com/index/polimill/) _2026-09-01_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/singularity — top 2 new
- [According to Axios, China is linked to anti-data-center propaganda in the U.S.](https://reddit.com/r/singularity/comments/1w3r29c/according_to_axios_china_is_linked_to/) ↑995
- [😂 seems like 10 hours is a bear market in AI models world](https://reddit.com/r/singularity/comments/1w3m36t/seems_like_10_hours_is_a_bear_market_in_ai_models/) ↑884

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw 2.0 has landed (v2026.8.1)](https://reddit.com/r/openclaw/comments/1w324oz/openclaw_20_has_landed_v202681/) ↑189
- [Has anyone tried Claude OAuth with subscription? It’s back!](https://reddit.com/r/openclaw/comments/1w3mizr/has_anyone_tried_claude_oauth_with_subscription/) ↑126
- [OpenClaw MacClawface - Mac mini case](https://reddit.com/r/openclaw/comments/1w3dm3w/openclaw_macclawface_mac_mini_case/) ↑90
- [OpenClaw became almost unusable after I updated it.](https://reddit.com/r/openclaw/comments/1w3enrs/openclaw_became_almost_unusable_after_i_updated_it/) ↑20
- [I've spent months teaching my AI agent to babysit OpenClaw upgrades so I don't have to — here’s my playbook](https://reddit.com/r/openclaw/comments/1w3vo8p/ive_spent_months_teaching_my_ai_agent_to_babysit/) ↑7

### X — @openclaw
- [The wait is almost over!](https://x.com/openclaw/status/2093864248879559097) ↑0 🔁0 · recent
- [Want to know what it's like behind-the-scenes of building OpenClaw?

Peter and the crew recently sat down with 
@github
](https://x.com/openclaw/status/2093083730604958166) ↑0 🔁0 · recent


### X — @steipete
_No new tweets in the last 7 days._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
