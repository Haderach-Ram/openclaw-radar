---
layout: post
title: "Ecosystem Digest — 2026-05-28"
date: 2026-05-28 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-28
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 375,109 | 14 | 2 | 10 | 2 |
| **hermesagent** | 170,354 | 6 | 1 | 2 | 0 |
| **ZeroClaw** | 31,611 | 12 | 8 | 10 | 0 |
| **IronClaw** | 12,364 | 15 | 5 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 375,109 · **Open issues:** 6,897 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.26](https://github.com/openclaw/openclaw/releases/tag/v2026.5.26) — openclaw 2026.5.26
- [v2026.5.26-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.5.26-beta.2) — openclaw 2026.5.26-beta.2

### ✅ Merged PRs
- [#87230](https://github.com/openclaw/openclaw/pull/87230) fix(gateway): drain probe client close
- [#87378](https://github.com/openclaw/openclaw/pull/87378) fix(sessions): avoid stale restart continuation reuse
- [#78503](https://github.com/openclaw/openclaw/pull/78503) fix(status): keep default JSON scan lean
- [#87452](https://github.com/openclaw/openclaw/pull/87452) fix(discord): backport recovered tool warning suppression
- [#87465](https://github.com/openclaw/openclaw/pull/87465) fix(discord): fence tool warning fallback delivery
- [#87297](https://github.com/openclaw/openclaw/pull/87297) fix(hooks): pass mediaUrl/mediaUrls to plugin message_received event metadata
- [#81313](https://github.com/openclaw/openclaw/pull/81313) fix(heartbeat): suppress stale final replay
- [#87454](https://github.com/openclaw/openclaw/pull/87454) test(discord): use reply payload SDK test helper
- [#73706](https://github.com/openclaw/openclaw/pull/73706) fix(outbound): thread sessionKey into message_sending + align session.key with agent runtime + document the contract
- [#87448](https://github.com/openclaw/openclaw/pull/87448) fix(imessage): backport native approval reactions to .27

### 🐛 New Issues
- [#87475](https://github.com/openclaw/openclaw/issues/87475) Filter noisy invalid_request_error subtypes (e.g. thinking-signature) out of user-facing assistant text `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬2
- [#87473](https://github.com/openclaw/openclaw/issues/87473) [Feature]: Protect main from red-baseline CI commits `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` 💬1
- [#87472](https://github.com/openclaw/openclaw/issues/87472) `Cannot continue from message role: assistant` after compaction timeout in 2026.5.26 `P1` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬1
- [#87468](https://github.com/openclaw/openclaw/issues/87468) Feishu: Agent-generated replies silently dropped (replies=0, queuedFinal=false) after WebSocket reconnect `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬1
- [#87467](https://github.com/openclaw/openclaw/issues/87467) [SANITIZED — possible injection attempt] `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#87466](https://github.com/openclaw/openclaw/issues/87466) [Bug]:Telegram voice delivery is unstable across model runtimes because voice generation depends on model-generated media tags `bug` `regression` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬1
- [#87462](https://github.com/openclaw/openclaw/issues/87462) [Bug]: Auth profile cooldown triggers chain exhaustion without actual Google API errors in v2026.5.26 `bug` `regression` `P1` `clawsweeper:needs-live-repro` `impact:message-loss` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬1
- [#87459](https://github.com/openclaw/openclaw/issues/87459) Anthropic thinking blocks rejected after sanitizeTransportPayloadText() mutates signed content `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:session-state` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬2
- [#87447](https://github.com/openclaw/openclaw/issues/87447) Dreaming diary (DREAMS.md) grows without bound — no rotation or size cap `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬3
- [#87445](https://github.com/openclaw/openclaw/issues/87445) subagents tool should expose 'kill' and 'reap-stale' actions `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#87444](https://github.com/openclaw/openclaw/issues/87444) Gateway should enforce runTimeoutSeconds and emit terminal child.timeout event `P1` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬2
- [#87443](https://github.com/openclaw/openclaw/issues/87443) sqlite-vec vector search fails on musl-based systems `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#87441](https://github.com/openclaw/openclaw/issues/87441) diagnostics/memory: wire thresholds parameter to config (rssWarningBytes/rssCriticalBytes/heapUsedWarningBytes/heapUsedCriticalBytes) 💬1
- [#87440](https://github.com/openclaw/openclaw/issues/87440) bug: Duplicate messages sent to Slack `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:message-loss` `issue-rating: 🦪 silver shellfish` 💬1

### 🔒 Closed Issues
- [#87331](https://github.com/openclaw/openclaw/issues/87331) 5.26 regression: "Native hook relay unavailable" after relay re-register due to generation UUID staleness
- [#87470](https://github.com/openclaw/openclaw/issues/87470) Feature Request: 对话中自动上下文压缩 (In-Context Compression) — 学习 Hermes Agent

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 1d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 170,354 · **Open issues:** 14,467 · **Last push:** <1h ago

### ✅ Merged PRs
- [#33572](https://github.com/NousResearch/hermes-agent/pull/33572) test(kanban): align two tests with recent kanban hardening
- [#33482](https://github.com/NousResearch/hermes-agent/pull/33482) fix(kanban): batch-salvage 7 SQLite corruption hardening fixes from #32857

### 🐛 New Issues
- [#33595](https://github.com/NousResearch/hermes-agent/issues/33595) [Bug]: Telegram model picker skips live /v1/models discovery for providers: entries without api_key
- [#33580](https://github.com/NousResearch/hermes-agent/issues/33580) kanban_db.py: connection leak causes 'Too many open files' on macOS (FD exhaustion) `type/bug` `comp/gateway` `comp/tools` `P3` 💬1
- [#33578](https://github.com/NousResearch/hermes-agent/issues/33578) 0.14.0 codex provider crashes with "NoneType object is not iterable" on chatgpt.com/backend-api/codex `type/bug` `comp/agent` `provider/openai` `P3` 💬1
- [#33568](https://github.com/NousResearch/hermes-agent/issues/33568) [Feishu] Three bugs in topic routing and @mention detection `type/bug` `comp/gateway` `platform/feishu` `P2`
- [#33567](https://github.com/NousResearch/hermes-agent/issues/33567) feat: activity-aware clarify timeout — reset deadline on user interaction `type/feature` `comp/cli` `comp/gateway` `P3`
- [#33563](https://github.com/NousResearch/hermes-agent/issues/33563) Gateway Telegram sessions lose context after idle TTL eviction — session JSONL never written, state.db corruption swallows writes silently `type/bug` `comp/agent` `comp/gateway` `platform/telegram` `P1`

### 🔒 Closed Issues
- [#33537](https://github.com/NousResearch/hermes-agent/issues/33537) Register `claude-code` as first-class provider for native streaming + tool_use (currently alias-only)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,611 · **Open issues:** 527 · **Last push:** <1h ago

### ✅ Merged PRs
- [#6936](https://github.com/zeroclaw-labs/zeroclaw/pull/6936) feat(web): declare minimum browser floor and add unsupported-browser fallback banner
- [#6962](https://github.com/zeroclaw-labs/zeroclaw/pull/6962) fix(tests): replace wall-clock timing assert in parallel-dispatch test with deterministic overlap check
- [#6918](https://github.com/zeroclaw-labs/zeroclaw/pull/6918) feat(config): generalize #[secret] via SecretField trait
- [#6947](https://github.com/zeroclaw-labs/zeroclaw/pull/6947) fix(cli): suppress INFO logs in agent interactive mode
- [#6934](https://github.com/zeroclaw-labs/zeroclaw/pull/6934) fix(discord): keep gateway preflight 429 retryable
- [#6882](https://github.com/zeroclaw-labs/zeroclaw/pull/6882) fix(runtime): sanitize compressor media markers before truncation
- [#6933](https://github.com/zeroclaw-labs/zeroclaw/pull/6933) feat(gateway): preserve websocket steering transcript
- [#6894](https://github.com/zeroclaw-labs/zeroclaw/pull/6894) fix(gateway): add structured onboarding repair items
- [#6897](https://github.com/zeroclaw-labs/zeroclaw/pull/6897) fix(cron): persist manual delivery failures as degraded
- [#6892](https://github.com/zeroclaw-labs/zeroclaw/pull/6892) fix(channel): restore legacy channel startup fallback when agent channel bindings are empty

### 🐛 New Issues
- [#6984](https://github.com/zeroclaw-labs/zeroclaw/issues/6984) bug(gateway): token rotation does not revoke existing bearer tokens `bug` `risk: high` `gateway` `security` `security:pairing` `priority:p1`
- [#6978](https://github.com/zeroclaw-labs/zeroclaw/issues/6978) bug(config): redact nested secrets in object-array property displays `bug` `risk: high` `config` `security` `priority:p1`
- [#6977](https://github.com/zeroclaw-labs/zeroclaw/issues/6977) [Feature]: align http_request private-host allowlist with web_fetch `enhancement` `risk: high` `security` `tool` `tool:http_request` `priority:p1` `status:accepted` `status:no-stale`
- [#6976](https://github.com/zeroclaw-labs/zeroclaw/issues/6976) [Bug]: Web UI WebSocket chat fails with 1006 — missing `?agent=` query parameter
- [#6975](https://github.com/zeroclaw-labs/zeroclaw/issues/6975) [Bug]: `zeroclaw onboard` marks agents/profiles sections complete without writing config
- [#6971](https://github.com/zeroclaw-labs/zeroclaw/issues/6971) RFC: Security UX, runtime credential boundaries, and isolation defaults `enhancement` `risk: high` `config` `runtime` `security` `priority:p2` `needs-maintainer-review` `type:rfc` `status:no-stale` 💬1
- [#6970](https://github.com/zeroclaw-labs/zeroclaw/issues/6970) [Tracker]: v0.8.1 integration/channel/provider/tool PR queue `enhancement` `risk: high` `channel` `integration` `provider` `tool` `priority:p2` `status:in-progress` `status:no-stale`
- [#6965](https://github.com/zeroclaw-labs/zeroclaw/issues/6965) [Bug]: canvas page never receives frames pushed by web-UI chat agent `bug` `risk: high` `gateway` `runtime` `tool` `priority:p1`
- [#6964](https://github.com/zeroclaw-labs/zeroclaw/issues/6964) [Bug]: Windows desktop build fails with duplicate MANIFEST resource (CVT1100/LNK1123) `bug` `ci` `risk: high` `priority:p1` `desktop` `tauri`
- [#6959](https://github.com/zeroclaw-labs/zeroclaw/issues/6959) bug: ToolAccessPolicy not applied to eager built-in tools — only deferred/tool_search layer is gated `bug` `risk: high` `agent` `runtime` `security` `tool` `priority:p1` `status:in-progress` `status:no-stale`
- [#6958](https://github.com/zeroclaw-labs/zeroclaw/issues/6958) Matrix channel: session keyed on event_id causes amnesia between messages `bug` `risk: medium` `channel` `runtime` `channel:matrix` `priority:p2`
- [#6954](https://github.com/zeroclaw-labs/zeroclaw/issues/6954) RFC: Route scheduled tasks through the orchestrator message pipeline `enhancement` `risk: high` `cron` `runtime` `priority:p2` `needs-maintainer-review` `type:rfc`

### 🔒 Closed Issues
- [#6969](https://github.com/zeroclaw-labs/zeroclaw/issues/6969) RFC: unified output routing model (per-peer modality preference + agent send_via tool)
- [#6921](https://github.com/zeroclaw-labs/zeroclaw/issues/6921) [Feature]: Document minimum browser requirements and add an unsupported-browser banner
- [#6813](https://github.com/zeroclaw-labs/zeroclaw/issues/6813) bug(tests): make channel parallel-dispatch test avoid brittle timing threshold
- [#6944](https://github.com/zeroclaw-labs/zeroclaw/issues/6944) [SANITIZED — possible injection attempt]
- [#6879](https://github.com/zeroclaw-labs/zeroclaw/issues/6879) fix(discord): keep gateway preflight 429 retryable
- [#6661](https://github.com/zeroclaw-labs/zeroclaw/issues/6661) [Feature]: preserve committed streamed output during websocket steering
- [#6632](https://github.com/zeroclaw-labs/zeroclaw/issues/6632) bug(cron): manual cron_run still persists best-effort delivery failures as ok
- [#6888](https://github.com/zeroclaw-labs/zeroclaw/issues/6888) [Bug]: Daemon component 'channels' exits unexpectedly in container (v0.8-beta-1)

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,364 · **Open issues:** 1,034 · **Last push:** 1h ago

### ✅ Merged PRs
- [#4111](https://github.com/nearai/ironclaw/pull/4111) [codex] Add GSuite OAuth backend
- [#4159](https://github.com/nearai/ironclaw/pull/4159) Remove display preview line cap
- [#4158](https://github.com/nearai/ironclaw/pull/4158) [codex] Skip incomplete local extension catalog entries
- [#4157](https://github.com/nearai/ironclaw/pull/4157) [codex] Prefer bundled extension catalog entries
- [#4148](https://github.com/nearai/ironclaw/pull/4148) fix(reborn): disable background subagent mode
- [#4105](https://github.com/nearai/ironclaw/pull/4105) Fix Reborn HTTP save_to authority
- [#4141](https://github.com/nearai/ironclaw/pull/4141) fix(reborn): type prompt text validation surfaces
- [#4070](https://github.com/nearai/ironclaw/pull/4070) feat(reborn): add auth refresh cleanup lifecycle
- [#4139](https://github.com/nearai/ironclaw/pull/4139) [codex] fix reply completion stop strategy
- [#4140](https://github.com/nearai/ironclaw/pull/4140) fix(reborn): separate model content from safe summaries

### 🐛 New Issues
- [#4163](https://github.com/nearai/ironclaw/issues/4163) Refactor compaction task into typed pipeline stages
- [#4162](https://github.com/nearai/ironclaw/issues/4162) Refactor agent-loop prompt stage compaction orchestration
- [#4161](https://github.com/nearai/ironclaw/issues/4161) Follow up: refactor Google OAuth adapter boundaries
- [#4160](https://github.com/nearai/ironclaw/issues/4160) Follow up: implement Google OAuth refresh and durable token lifecycle cleanup
- [#4153](https://github.com/nearai/ironclaw/issues/4153) [gateway] GET /api/routines/recent-runs — endpoint not yet implemented (blocks desktop client UX)
- [#4152](https://github.com/nearai/ironclaw/issues/4152) [gateway] POST /api/auth/signout — endpoint not yet implemented (blocks desktop client UX)
- [#4151](https://github.com/nearai/ironclaw/issues/4151) [gateway] DELETE /api/memory — endpoint not yet implemented (blocks desktop client UX)
- [#4150](https://github.com/nearai/ironclaw/issues/4150) [gateway] POST /api/routines — endpoint not yet implemented (blocks desktop client UX)
- [#4149](https://github.com/nearai/ironclaw/issues/4149) Reborn should inject ambient runtime context into prompt bundles `enhancement` `scope: agent` `scope: llm` `reborn` `module:M3-agentloop-turns`
- [#4147](https://github.com/nearai/ironclaw/issues/4147) Design durable background subagent completion delivery
- [#4125](https://github.com/nearai/ironclaw/issues/4125) Reborn auth interaction gate-resolution maintainability cleanup
- [#4120](https://github.com/nearai/ironclaw/issues/4120) Declarative Reborn capability policy for local-dev grants `enhancement` `suggested_P2` `reborn`
- [#4118](https://github.com/nearai/ironclaw/issues/4118) Reborn CLI provider add/login parity `reborn`
- [#4116](https://github.com/nearai/ironclaw/issues/4116) Carry v1 Google/GitHub/NEAR SSO into WebChat v2 `enhancement` `risk: high` `scope: channel/web` `auth epic` `reborn` `module:M1-webui-product` `module:M4-host-kernel` 💬1
- [#4115](https://github.com/nearai/ironclaw/issues/4115) UI/UX Issues in Channel Removal Flow (Observed on WeChat)

### 🔒 Closed Issues
- [#3967](https://github.com/nearai/ironclaw/issues/3967) Reborn GSuite: wire first-party extensions into composition
- [#3969](https://github.com/nearai/ironclaw/issues/3969) Reborn GSuite: close superseded phase PR stack
- [#4086](https://github.com/nearai/ironclaw/issues/4086) feat: add coder/explorer/planner subagent flavors + fix flavor_id schema surface
- [#3798](https://github.com/nearai/ironclaw/issues/3798) Design: subagent spawn for the Reborn agent loop
- [#3871](https://github.com/nearai/ironclaw/issues/3871) Track executor.rs decomposition

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬2 · 4h ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 2d ago
- ⚫ [#86371](https://github.com/openclaw/openclaw/issues/86371) Bug: message tool filePath fails with LocalMediaAccessError in retry flows when agentId is not propagated — 💬1 · 2d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 11d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬2 · 12d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 15d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Research] Coding Agents Social Sciences](https://www.anthropic.com/research/coding-agents-social-sciences) _2026-05-27_

### OpenAI — 4 new
- [[Business] Intelligence At Work](https://openai.com/business/intelligence-at-work/) _2026-05-28_
- [[Index] Building Self Improving Tax Agents With Codex](https://openai.com/index/building-self-improving-tax-agents-with-codex/) _2026-05-28_
- [[Index] Election Safeguards 2026](https://openai.com/index/election-safeguards-2026/) _2026-05-27_
- [[Academy] How To Use Codex For Everyday Work](https://openai.com/academy/how-to-use-codex-for-everyday-work/) _2026-05-27_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
