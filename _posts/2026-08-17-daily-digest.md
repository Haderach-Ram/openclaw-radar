---
layout: post
title: "Ecosystem Digest — 2026-08-17"
date: 2026-08-17 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-08-17
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 386,473 | 6 | 3 | 10 | 1 |
| **hermesagent** | 231,554 | 11 | 4 | 10 | 1 |
| **ZeroClaw** | 32,599 | 11 | 2 | 4 | 0 |
| **IronClaw** | 12,604 | 3 | 0 | 1 | 0 |
| **Moltis** | 2,821 | 2 | 1 | 4 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 386,473 · **Open issues:** 5,572 · **Last push:** <1h ago

### 🚀 New Releases
- [pr-124528-profiles](https://github.com/openclaw/openclaw/releases/tag/pr-124528-profiles) — PR #124528 Gateway profile evidence

### ✅ Merged PRs
- [#124972](https://github.com/openclaw/openclaw/pull/124972) refactor(channels): delete the per-turn progress receipt line
- [#124914](https://github.com/openclaw/openclaw/pull/124914) fix: scale Gateway RSS diagnostics to runtime limits
- [#124958](https://github.com/openclaw/openclaw/pull/124958) feat(android): status-aware plan pill header and explanation rendering
- [#124968](https://github.com/openclaw/openclaw/pull/124968) fix(ui): stop duplicate dashboard session queries
- [#124948](https://github.com/openclaw/openclaw/pull/124948) fix(doctor): surface legacy-config copy failures
- [#124889](https://github.com/openclaw/openclaw/pull/124889) docs: clarify model switching guidance
- [#124960](https://github.com/openclaw/openclaw/pull/124960) improve(ui): move session status to second row
- [#124950](https://github.com/openclaw/openclaw/pull/124950) refactor(ui): give chat side-panel slots one definition
- [#124942](https://github.com/openclaw/openclaw/pull/124942) refactor(channels): split signal approval routes and align persisted approval-target validation
- [#124949](https://github.com/openclaw/openclaw/pull/124949) fix(qa): keep QA Lab startup off operator state

### 🐛 New Issues
- [#124966](https://github.com/openclaw/openclaw/issues/124966) Control UI: create worktree sessions optimistically and show setup progress `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬2
- [#124952](https://github.com/openclaw/openclaw/issues/124952) [Bug]: modelPolicy.allow is never migrated off legacy claude-cli/* refs, leaving no selectable Claude model `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` `maturity:stable` 💬2
- [#124946](https://github.com/openclaw/openclaw/issues/124946) [SANITIZED — possible injection attempt] `security` `maintainer` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `P0` `issue-rating: 🦞 diamond lobster` 💬2
- [#124933](https://github.com/openclaw/openclaw/issues/124933) [Bug]: Mobile chat transcript always shows message metadata and actions `maintainer` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬2
- [#124930](https://github.com/openclaw/openclaw/issues/124930) Exec approval revalidation is not atomic with runtime spawn `security` `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `impact:security` `issue-rating: 🦪 silver shellfish` 💬1
- [#124926](https://github.com/openclaw/openclaw/issues/124926) infer image generate is unusable in a multi-agent fleet: requires an owner but accepts no agent selector `maintainer` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬6

### 🔒 Closed Issues
- [#95516](https://github.com/openclaw/openclaw/issues/95516) [Feature]: Skill lifecycle management — auto-optimization on failure + usage-based retirement
- [#124424](https://github.com/openclaw/openclaw/issues/124424) Control UI New session fails with unknown parent session on clean and normal gateways
- [#119189](https://github.com/openclaw/openclaw/issues/119189) Gateway logs constant false memory pressure warnings on large-memory hosts

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 231,554 · **Open issues:** 32,493 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.8.16](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.8.16) — Hermes Agent v0.20.2 (2026.8.16)

### ✅ Merged PRs
- [#87118](https://github.com/NousResearch/hermes-agent/pull/87118) fix(gateway): make managed Node suppress PATH fallback
- [#88056](https://github.com/NousResearch/hermes-agent/pull/88056) feat: raise Codex OAuth context to 900K for gpt-5.6 family and gpt-5.4 (subscription 1M rollout)
- [#87886](https://github.com/NousResearch/hermes-agent/pull/87886) feat(desktop): bundle Bot Mode as built-in default-on plugin + core teammate protocol
- [#88016](https://github.com/NousResearch/hermes-agent/pull/88016) fmt(js): `npm run fix` auto-fix
- [#87595](https://github.com/NousResearch/hermes-agent/pull/87595) test(desktop): steered turns render in arrival order — live and after reload
- [#88014](https://github.com/NousResearch/hermes-agent/pull/88014) fmt(js): `npm run fix` auto-fix
- [#88000](https://github.com/NousResearch/hermes-agent/pull/88000) fix(desktop): read cron run-history from the owning gateway
- [#87997](https://github.com/NousResearch/hermes-agent/pull/87997) fix(desktop): keep profile rail alive across remote/Cloud connection switches
- [#87993](https://github.com/NousResearch/hermes-agent/pull/87993) fix(desktop): scope session/pin lists per connection across windows
- [#87977](https://github.com/NousResearch/hermes-agent/pull/87977) feat(desktop): expose connection-aware plugin routing (salvage #85872)

### 🐛 New Issues
- [#88064](https://github.com/NousResearch/hermes-agent/issues/88064) [Bug]: /skill slash invoke fails when skills.external_dirs is the package root `type/bug` `comp/agent` `tool/skills` `P2`
- [#88061](https://github.com/NousResearch/hermes-agent/issues/88061) Design: per-task multi-agent workflow — IM-style task trace + reliable execution (ported from Hermes-Bot-Mode#108) `type/feature` `innovation` `comp/plugins` `P3` `needs-decision` `comp/desktop`
- [#88060](https://github.com/NousResearch/hermes-agent/issues/88060) feat(desktop): composer @ autocomplete should offer Bot Mode agents (ported from Hermes-Bot-Mode#43) `type/feature` `comp/plugins` `P3` `comp/desktop` 💬1
- [#88059](https://github.com/NousResearch/hermes-agent/issues/88059) Bot Mode: bot-to-bot reply silently drops when receiving profile has no Bot Chat session (ported from Hermes-Bot-Mode#48) `type/bug` `P2` `needs-repro` `sweeper:risk-session-state` `comp/desktop` `area/sessions`
- [#88057](https://github.com/NousResearch/hermes-agent/issues/88057) Kanban workers cannot return protected-instruction approval prompts to their authenticated messaging origin `type/bug` `comp/gateway` `comp/cron` `tool/file` `P3` `sweeper:risk-message-delivery` 💬1
- [#88055](https://github.com/NousResearch/hermes-agent/issues/88055) Back off repeated cron-failure deliveries and notify once on recovery `type/feature` `comp/gateway` `comp/cron` `P3` `sweeper:risk-session-state` `sweeper:risk-message-delivery`
- [#88054](https://github.com/NousResearch/hermes-agent/issues/88054) Deduplicate unresolved attention requests across gateway restarts `type/feature` `comp/gateway` `P3` `sweeper:risk-session-state` `sweeper:risk-message-delivery`
- [#88053](https://github.com/NousResearch/hermes-agent/issues/88053) [bug] read-before-write guard rejects all background-review skill writes: ContextVar marks lost across worker-thread snapshots `type/bug` `duplicate` `comp/agent` `tool/skills` `P3` 💬1
- [#88047](https://github.com/NousResearch/hermes-agent/issues/88047) [Bug]: Multiplexed profiles share one platform runtime-status record — a secondary profile's fatal overwrites the primary's "connected" `type/bug` `comp/gateway` `platform/whatsapp` `area/config` `P2` `sweeper:risk-compatibility` `comp/dashboard` `area/profiles`
- [#88042](https://github.com/NousResearch/hermes-agent/issues/88042) [SANITIZED — possible injection attempt] `type/bug` `comp/agent` `tool/mcp` `P2` `sweeper:risk-session-state` `area/compression`
- [#88040](https://github.com/NousResearch/hermes-agent/issues/88040) [Bug]: x_search degrades to Grok explanatory mode when xai-oauth is configured alongside XAI_API_KEY `type/bug` `comp/tools` `tool/web` `provider/xai` `area/auth` `P2` `bug`

### 🔒 Closed Issues
- [#62158](https://github.com/NousResearch/hermes-agent/issues/62158) [Bug]: Desktop chat elapsed-time counter resets to ~1s when navigating away and back
- [#84294](https://github.com/NousResearch/hermes-agent/issues/84294) Pet mascot doesn't load automatically on desktop app startup — only shows when Settings page is opened
- [#87027](https://github.com/NousResearch/hermes-agent/issues/87027) Local/custom provider (Ollama): agent never emits real tool_calls for MCP tools — narrates fabricated results instead, or returns empty content
- [#87882](https://github.com/NousResearch/hermes-agent/issues/87882) [Bug]: Desktop cron run-history is empty for all remote-gateway jobs because run sessions live on the gateway's state.db, not the local backend's

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,599 · **Open issues:** 726 · **Last push:** 1h ago

### ✅ Merged PRs
- [#9580](https://github.com/zeroclaw-labs/zeroclaw/pull/9580) fix(security): harden built-in HTTP egress on the shared network guard
- [#9416](https://github.com/zeroclaw-labs/zeroclaw/pull/9416) docs(tools): document that AllToolsResult.tools is the pre-filter registry
- [#9954](https://github.com/zeroclaw-labs/zeroclaw/pull/9954) fix(sop): unwrap a double-encoded step output before schema validation
- [#9499](https://github.com/zeroclaw-labs/zeroclaw/pull/9499) docs(governance): define RFC voting protocol

### 🐛 New Issues
- [#10045](https://github.com/zeroclaw-labs/zeroclaw/issues/10045) [Bug]: Persisted image markers can retain temporary source paths and repeatedly warn `bug` `provider` `runtime` `priority:p2` `follow-up` `zerocode`
- [#10044](https://github.com/zeroclaw-labs/zeroclaw/issues/10044) [Feature]: Add recovery actions for queued ZeroCode messages `enhancement` `priority:p2` `risk:medium` `zerocode`
- [#10042](https://github.com/zeroclaw-labs/zeroclaw/issues/10042) bug(ci): MSRV system dependency installation can consume job timeout `bug` `ci` `priority:p2` `risk:medium` `type:ci`
- [#10041](https://github.com/zeroclaw-labs/zeroclaw/issues/10041) [Feature]: Isolate interactive Blacksmith debugging from attesting CI `enhancement` `domain:ci` `domain:security` `priority:p2` `follow-up` `risk:high` `type:ci`
- [#10040](https://github.com/zeroclaw-labs/zeroclaw/issues/10040) [Feature]: ci: restore Lint timeout headroom for fork PRs `enhancement` `ci` `priority:p2` `risk:high` `type:ci`
- [#10037](https://github.com/zeroclaw-labs/zeroclaw/issues/10037) [Bug]: POST /api/cron silently stores invalid session_target as isolated `bug` `cron` `gateway` `runtime` `priority:p2` `status:in-progress` `status:accepted` `risk:high` 💬1
- [#10025](https://github.com/zeroclaw-labs/zeroclaw/issues/10025) RFC: zeroclaw swarm — ephemeral agent swarms with a crush-style TUI `enhancement` `agent` `memory` `runtime` `security` `domain:security` `domain:architecture` `priority:p2` `needs-maintainer-review` `type:rfc` `status:no-stale` `risk:high` `cli` 💬1
- [#10023](https://github.com/zeroclaw-labs/zeroclaw/issues/10023) Failure logs claim the requested model, not the pinned fallback model `status:in-progress` 💬1
- [#10020](https://github.com/zeroclaw-labs/zeroclaw/issues/10020) [Bug]: Agentic independent delegates ignore the target thinking policy `bug` `runtime` `tool` `tool:delegate` `priority:p2` `status:in-progress` `status:accepted` `risk:high` 💬1
- [#10019](https://github.com/zeroclaw-labs/zeroclaw/issues/10019) [Docs]: Align the prompt-injection deprecation deadline after Schema V4 `docs` `config` `runtime` `skills` `priority:p2` `status:accepted` `risk:medium` `type:docs` 💬1
- [#10018](https://github.com/zeroclaw-labs/zeroclaw/issues/10018) [Bug]: ACP graceful-summary text is silently dropped on max-iteration exit `bug` `status:in-progress`

### 🔒 Closed Issues
- [#9953](https://github.com/zeroclaw-labs/zeroclaw/issues/9953) [Bug]: SOP step schema validation rejects a double-encoded output object instead of unwrapping it
- [#10022](https://github.com/zeroclaw-labs/zeroclaw/issues/10022) [Bug]: Can't copy text from the ZeroCode chat

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,604 · **Open issues:** 1,500 · **Last push:** 5h ago

### ✅ Merged PRs
- [#7683](https://github.com/nearai/ironclaw/pull/7683) chore: remove retired IronLoop network settings

### 🐛 New Issues
- [#7685](https://github.com/nearai/ironclaw/issues/7685) Epic: Dogfooding & QA bug fixing 08/17/2026 - 08/23/2026
- [#7681](https://github.com/nearai/ironclaw/issues/7681) Slack: unlinked-user connect message is public and requires a manual round trip `enhancement` `scope: channel` `UX / Onboarding` `epic`
- [#7639](https://github.com/nearai/ironclaw/issues/7639) Introduce a shared InlineNotice for page feedback

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,821 · **Open issues:** 94 · **Last push:** <1h ago

### ✅ Merged PRs
- [#1147](https://github.com/moltis-org/moltis/pull/1147) fix(caldav): honor list_events time ranges
- [#1203](https://github.com/moltis-org/moltis/pull/1203) test(gateway): run the push fanout test on a paused clock
- [#1201](https://github.com/moltis-org/moltis/pull/1201) fix(gateway): thread start_background_tasks into the memory runtime builder
- [#1186](https://github.com/moltis-org/moltis/pull/1186) fix(vault): normalize recovery phrase before hashing

### 🐛 New Issues
- [#1205](https://github.com/moltis-org/moltis/issues/1205) [Bug]: Heartbeat ignores configured active hours and runs continuously `bug`
- [#1202](https://github.com/moltis-org/moltis/issues/1202) Format CI gate is red on main: two files over the 1500-line limit

### 🔒 Closed Issues
- [#1193](https://github.com/moltis-org/moltis/issues/1193) Flaky test: push fanout timeout assertion races under full-suite load

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 23h ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 4d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 7d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 10d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 10d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 12d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 14d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 14d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 16d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 16d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [GLM 5.3 Released](https://reddit.com/r/LocalLLaMA/comments/1vny9zs/glm_53_released/) ↑1635
- [Let’s all thank Georgi Gerganov who gave use llama.cpp](https://reddit.com/r/LocalLLaMA/comments/1vq1n1l/lets_all_thank_georgi_gerganov_who_gave_use/) ↑914
- [Newer commits removed the Qwen 35B](https://reddit.com/r/LocalLLaMA/comments/1vpxbm8/newer_commits_removed_the_qwen_35b/) ↑478
- [Qwen 3.8 distillations](https://reddit.com/r/LocalLLaMA/comments/1vq3gig/qwen_38_distillations/) ↑366
- [Based on an accelerating frontier -> local trajectory, expect  a ~30b param 'Mythos at home' by as soon as Jan 2027 (rationalisation below)](https://reddit.com/r/LocalLLaMA/comments/1vq279o/based_on_an_accelerating_frontier_local/) ↑366

### r/singularity — top 2 new
- [Young People Hate AI CEOs So Passionately That It's Almost Hard to Believe](https://reddit.com/r/singularity/comments/1vq6vla/young_people_hate_ai_ceos_so_passionately_that/) ↑1109
- [Solved a math problem with AI? Post it to TheoremDB.org](https://reddit.com/r/singularity/comments/1vq87o5/solved_a_math_problem_with_ai_post_it_to/) ↑65

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Life/Habit Tracking App which uses Open Claw. [Life OS]](https://reddit.com/r/openclaw/comments/1vq76ex/lifehabit_tracking_app_which_uses_open_claw_life/) ↑8
- [am i the only one who wants proper sessions/projects management?](https://reddit.com/r/openclaw/comments/1vpwxj2/am_i_the_only_one_who_wants_proper/) ↑5
- [Built this cool homebot 🦞(StackChan)](https://reddit.com/r/openclaw/comments/1vqebfj/built_this_cool_homebot_stackchan/) ↑4
- [[Project] Human Gate: a fail-closed approval firewall for OpenClaw agent tool calls](https://reddit.com/r/openclaw/comments/1vpy7c1/project_human_gate_a_failclosed_approval_firewall/) ↑3
- [What’s the best way to set up openclaw?](https://reddit.com/r/openclaw/comments/1vq9jwj/whats_the_best_way_to_set_up_openclaw/) ↑2

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
- [going live!](https://x.com/steipete/status/2087607369908023354) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
