---
layout: post
title: "Ecosystem Digest — 2026-06-03"
date: 2026-06-03 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-03
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 376,307 | 5 | 2 | 5 | 0 |
| **hermesagent** | 177,474 | 7 | 2 | 10 | 0 |
| **ZeroClaw** | 31,706 | 9 | 0 | 0 | 1 |
| **IronClaw** | 12,393 | 15 | 2 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 376,307 · **Open issues:** 7,207 · **Last push:** <1h ago

### ✅ Merged PRs
- [#89601](https://github.com/openclaw/openclaw/pull/89601) fix(outbound): stop schema-padded poll modifiers from blocking send
- [#87074](https://github.com/openclaw/openclaw/pull/87074) fix(policy): reject unsupported policy keys
- [#89356](https://github.com/openclaw/openclaw/pull/89356) Add accessible Workboard movement controls
- [#81488](https://github.com/openclaw/openclaw/pull/81488) Harden node exec approval precheck env [AI]
- [#87056](https://github.com/openclaw/openclaw/pull/87056) Policy: add data handling conformance checks

### 🐛 New Issues
- [#89660](https://github.com/openclaw/openclaw/issues/89660) [Bug]: requiresReasoningContentOnAssistantMessages missing from ModelCompatSchema — can't replicate native DeepSeek behavior on custom providers `bug`
- [#89655](https://github.com/openclaw/openclaw/issues/89655) [Bug]: `NODE_USE_SYSTEM_CA=1` breaks `openai-codex` auth/keychain paths on macOS and can fail fresh runtime launch with `SecItemCopyMatching failed -50` `bug` `regression` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬2
- [#89651](https://github.com/openclaw/openclaw/issues/89651) Gateway startup does not load the plugin owning a configured memory embedding provider (memorySearch.provider) 💬1
- [#89641](https://github.com/openclaw/openclaw/issues/89641) [Bug]: Bash run_in_background task-notification silently drops Telegram reply when session is idle `P1` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬1
- [#89633](https://github.com/openclaw/openclaw/issues/89633) Codex turn fails with generic Telegram fallback when invalid image tool model is configured, leaving child agent orphaned on full stdout pipe `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:message-loss` `impact:crash-loop` `issue-rating: 🐚 platinum hermit` 💬1

### 🔒 Closed Issues
- [#89639](https://github.com/openclaw/openclaw/issues/89639) [Bug]: Session file lock leaked after compaction abort, causing permanent session deadlock
- [#89616](https://github.com/openclaw/openclaw/issues/89616) Bug: Announce delivery doesn't thread into Slack conversations

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 7d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 177,474 · **Open issues:** 16,704 · **Last push:** <1h ago

### ✅ Merged PRs
- [#37752](https://github.com/NousResearch/hermes-agent/pull/37752) fix(deps): refresh lockfile to clear 6 npm audit findings
- [#37745](https://github.com/NousResearch/hermes-agent/pull/37745) fix(desktop): inherit microphone entitlement for macOS helpers (#37718)
- [#37749](https://github.com/NousResearch/hermes-agent/pull/37749) fix: expand skill bundles in cron jobs
- [#37747](https://github.com/NousResearch/hermes-agent/pull/37747) fix(dashboard): allow desktop websocket origins on remote binds
- [#37738](https://github.com/NousResearch/hermes-agent/pull/37738) feat(desktop): inline model picker in the status bar
- [#37739](https://github.com/NousResearch/hermes-agent/pull/37739) fix(desktop): adopt existing macOS install + auto-place app
- [#37679](https://github.com/NousResearch/hermes-agent/pull/37679) fix(gateway): close ResponseStore + dispose unowned adapter on reconnect failure
- [#37691](https://github.com/NousResearch/hermes-agent/pull/37691) fix(desktop): configure Linux Electron sandbox helper
- [#37660](https://github.com/NousResearch/hermes-agent/pull/37660) refactor(uv): single managed-uv path, delete fts5 installer escalation
- [#36171](https://github.com/NousResearch/hermes-agent/pull/36171) fix(node/nix): consolidate workspace lockfile + update all consumers

### 🐛 New Issues
- [#37777](https://github.com/NousResearch/hermes-agent/issues/37777) [Feature] Support Feishu interactive card (msg_type=interactive) in send_message `type/feature` `comp/gateway` `platform/feishu` `P3`
- [#37776](https://github.com/NousResearch/hermes-agent/issues/37776) AI/Tech News Brief: June 3, 2026 — Research Findings `invalid` `P3`
- [#37775](https://github.com/NousResearch/hermes-agent/issues/37775) Desktop app update gets stuck forever; terminal shows hermes:api ECONNREFUSED 127.0.0.1:9120 on Fedora Wayland `type/bug` `comp/gateway` `P2`
- [#37774](https://github.com/NousResearch/hermes-agent/issues/37774) AI News Research - June 3, 2026 `invalid` `P3`
- [#37768](https://github.com/NousResearch/hermes-agent/issues/37768) MCP tool call returns 'not connected' while hermes mcp test passes `type/bug` `tool/mcp` `P2`
- [#37763](https://github.com/NousResearch/hermes-agent/issues/37763) Gateway cron script can coincide with unexpected SIGTERM after nested hermes chat `type/bug` `comp/gateway` `comp/cron` `P2`
- [#37759](https://github.com/NousResearch/hermes-agent/issues/37759) [Bug]: honcho_conclude silently fails on self-hosted Honcho — create_conclusion routes through peer instead of session `type/bug` `comp/plugins` `tool/memory` `P3`

### 🔒 Closed Issues
- [#37258](https://github.com/NousResearch/hermes-agent/issues/37258) Harden browser tool subprocess environment
- [#37718](https://github.com/NousResearch/hermes-agent/issues/37718) [Bug]: Hermes Desktop (macOS): voice chat fails — microphone entitlement missing on Helper/Setup binaries (hardened runtime)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,706 · **Open issues:** 447 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.8.0-beta-2](https://github.com/zeroclaw-labs/zeroclaw/releases/tag/v0.8.0-beta-2) — v0.8.0-beta-2

### 🐛 New Issues
- [#7117](https://github.com/zeroclaw-labs/zeroclaw/issues/7117) [Feature]: Config UX parity across CLI, Quickstart, zerocode (incl. navigation), and web surfaces `enhancement` `config`
- [#7113](https://github.com/zeroclaw-labs/zeroclaw/issues/7113) feat(slack): show visible lifecycle progress while agent is working
- [#7112](https://github.com/zeroclaw-labs/zeroclaw/issues/7112) [Tracker]: v0.8.0 release queue and Stable-tier blockers `enhancement` `risk: high` `config` `runtime` `security` `tool` `priority:p1` `status:accepted` `status:no-stale`
- [#7110](https://github.com/zeroclaw-labs/zeroclaw/issues/7110) [Bug]: docs PO catalogs contain generated assistant-response translations `bug` `risk: low` `docs`
- [#7108](https://github.com/zeroclaw-labs/zeroclaw/issues/7108) feat(ci): improve cached Rust builds and CI critical path `enhancement` `type: ci` `ci` `risk: high`
- [#7100](https://github.com/zeroclaw-labs/zeroclaw/issues/7100) [Feature]: Per-model capability & context-window config (vision, context_window) for capability checks, context budget, and UI display
- [#7099](https://github.com/zeroclaw-labs/zeroclaw/issues/7099) [Feature]: Route zeroclaw status output through CLI i18n `enhancement` `risk: medium` `core`
- [#7089](https://github.com/zeroclaw-labs/zeroclaw/issues/7089) [Feature]: Evaluate PowerShell / Git Bash vs cmd.exe as the Windows shell host (make it configurable?) `enhancement` `risk: high` `config` `runtime` `tool` `priority:p2` `tool:shell` `needs-maintainer-review` 💬1
- [#7088](https://github.com/zeroclaw-labs/zeroclaw/issues/7088) bug(cron): DingTalk is missing from cron delivery tool schemas `bug` `risk: medium` `channel` `cron` `runtime` `tool` `priority:p2` `channel:dingtalk`

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,393 · **Open issues:** 1,092 · **Last push:** <1h ago

### ✅ Merged PRs
- [#4369](https://github.com/nearai/ironclaw/pull/4369) [codex] Harden skill context budget contract tests
- [#4374](https://github.com/nearai/ironclaw/pull/4374) Accept memory_search query aliases
- [#4357](https://github.com/nearai/ironclaw/pull/4357) Fix local-dev Reborn memory mount
- [#4371](https://github.com/nearai/ironclaw/pull/4371) Fix Codex ChatGPT Reborn empty responses
- [#4318](https://github.com/nearai/ironclaw/pull/4318) PR17: Add trigger first-party capabilities
- [#4347](https://github.com/nearai/ironclaw/pull/4347) Fix Reborn Gmail OAuth auth gate scopes
- [#4345](https://github.com/nearai/ironclaw/pull/4345) Wire Notion DCR OAuth for Reborn WebUI
- [#4346](https://github.com/nearai/ironclaw/pull/4346) Fix Gmail OAuth auth gate requirements
- [#4337](https://github.com/nearai/ironclaw/pull/4337) Fix Google OAuth prompts for runtime auth gates
- [#4332](https://github.com/nearai/ironclaw/pull/4332) [codex] Enable WebUI v2 DCR extension setup

### 🐛 New Issues
- [#4376](https://github.com/nearai/ironclaw/issues/4376) Harden HTTP credential carriers with non-clone types and DTO boundary
- [#4368](https://github.com/nearai/ironclaw/issues/4368) [reborn-loop] L11: Architecture + convention hygiene — LoopHostDependencies bundle, debug! demotion, saturating_sub `reborn` `module:M4-host-kernel`
- [#4367](https://github.com/nearai/ironclaw/issues/4367) [reborn-loop] L10: Loop strategies + stop conditions — drain cap, identity bin-pack, JSON reply rejection `reborn` `module:M3-agentloop-turns`
- [#4366](https://github.com/nearai/ironclaw/issues/4366) [reborn-loop] L9: Compaction + checkpoint — defer-not-error, pre-size check, drop hex encoding `reborn` `module:M3-agentloop-turns`
- [#4365](https://github.com/nearai/ironclaw/issues/4365) [reborn-loop] L8: Cancellation propagation — interruptible model awaits + polling backoff `reborn` `module:M4-host-kernel`
- [#4364](https://github.com/nearai/ironclaw/issues/4364) [reborn-loop] L7: Budget accuracy — wall-clock, output-token reconcile, cost coverage, CJK tokens `reborn` `module:M4-host-kernel`
- [#4363](https://github.com/nearai/ironclaw/issues/4363) [reborn-loop] L6: Capability pipeline observability + batch rollback + system_inference lifecycle `reborn` `module:M3-agentloop-turns`
- [#4362](https://github.com/nearai/ironclaw/issues/4362) [reborn-loop] L5: Persistence + event ordering + F-A1 re-investigation `reborn` `module:M3-agentloop-turns`
- [#4361](https://github.com/nearai/ironclaw/issues/4361) [reborn-loop] L4: Recovery strategy coverage + exit checkpoint fallback + retry surface refresh `reborn` `module:M3-agentloop-turns`
- [#4360](https://github.com/nearai/ironclaw/issues/4360) [reborn-loop] L3: Capability validation hardening — $ref rejection, depth guard, capability_info visibility `reborn` `module:M4-host-kernel`
- [#4359](https://github.com/nearai/ironclaw/issues/4359) [reborn-loop] L2: Prompt safety wiring — required safety_context, SafetyLayer-scanned skills, deprecate bare gateway `reborn` `module:M4-host-kernel`
- [#4358](https://github.com/nearai/ironclaw/issues/4358) [reborn-loop] L1: Gate replay re-validates current policy + durable dispatch records `reborn` `module:M3-agentloop-turns`
- [#4353](https://github.com/nearai/ironclaw/issues/4353) [reborn-subagent] C6: Hygiene — readiness accuracy, eviction observability, config knobs, graceful unknowns `reborn` `module:M3-agentloop-turns` `module:M4-host-kernel`
- [#4352](https://github.com/nearai/ironclaw/issues/4352) [reborn-subagent] C5: Subagent provenance in audit envelope, capability results, and effect kinds `reborn` `module:M4-host-kernel`
- [#4351](https://github.com/nearai/ironclaw/issues/4351) [reborn-subagent] C4: Capability surface + safety gating — fail-closed injection scan, family-id-keyed predicate `reborn` `module:M4-host-kernel`

### 🔒 Closed Issues
- [#4355](https://github.com/nearai/ironclaw/issues/4355) engine v2: newtype client_thread_id / client_response_id on ThreadExecutionContext (Z2 follow-up from #3669)
- [#3806](https://github.com/nearai/ironclaw/issues/3806) [Reborn] Lane 6: implement GitHub WASM read/write capability path

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · <1h ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 21h ago
- ⚫ [#88517](https://github.com/openclaw/openclaw/issues/88517) [SANITIZED — possible injection attempt] — 💬3 · 1d ago
- ⚫ [#88967](https://github.com/openclaw/openclaw/issues/88967) Telegram: allowBots support for group chats (bot-authored messages not ingested into session) — 💬1 · 1d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬5 · 2d ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬1 · 4d ago
- ⚫ [#86371](https://github.com/openclaw/openclaw/issues/86371) Bug: message tool filePath fails with LocalMediaAccessError in retry flows when agentId is not propagated — 💬1 · 5d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 8d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 21d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
