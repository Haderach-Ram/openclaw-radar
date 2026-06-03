---
layout: post
title: "Ecosystem Digest — 2026-06-01"
date: 2026-06-01 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-01
*Generated 05:44 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 376,291 | 7 | 4 | 6 | 0 |
| **hermesagent** | 177,326 | 7 | 3 | 8 | 0 |
| **ZeroClaw** | 31,707 | 11 | 5 | 10 | 1 |
| **IronClaw** | 12,392 | 15 | 2 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 376,291 · **Open issues:** 7,193 · **Last push:** <1h ago

### ✅ Merged PRs
- [#87074](https://github.com/openclaw/openclaw/pull/87074) fix(policy): reject unsupported policy keys
- [#89356](https://github.com/openclaw/openclaw/pull/89356) Add accessible Workboard movement controls
- [#81488](https://github.com/openclaw/openclaw/pull/81488) Harden node exec approval precheck env [AI]
- [#87056](https://github.com/openclaw/openclaw/pull/87056) Policy: add data handling conformance checks
- [#84431](https://github.com/openclaw/openclaw/pull/84431) Treat soft plugin repair warnings as nonfatal
- [#89480](https://github.com/openclaw/openclaw/pull/89480) fix: recover suspicious gateway startup configs

### 🐛 New Issues
- [#89633](https://github.com/openclaw/openclaw/issues/89633) Codex turn fails with generic Telegram fallback when invalid image tool model is configured, leaving child agent orphaned on full stdout pipe `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:message-loss` `impact:crash-loop` `issue-rating: 🐚 platinum hermit` 💬1
- [#89626](https://github.com/openclaw/openclaw/issues/89626) Sub-agent completion events delivered 3x — duplicate messages on auto-announce retry `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬1
- [#89625](https://github.com/openclaw/openclaw/issues/89625) [Feature]: Support ignoreOtherMentions config option for Slack channels `enhancement` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#89617](https://github.com/openclaw/openclaw/issues/89617) Add Atomic Chat as a bundled local provider (OpenAI-compatible, 127.0.0.1:1337) `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:linked-pr-open` `impact:auth-provider` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#89609](https://github.com/openclaw/openclaw/issues/89609) [Bug]: openclaw migrate codex always fails with "Unknown migration provider" — standalone provider discovery (preferPersisted:false) is blind to global plugins `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#89607](https://github.com/openclaw/openclaw/issues/89607) Secret resolver does not inject file-source secrets into ElevenLabs TTS provider at runtime `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-security-review` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:security` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#89606](https://github.com/openclaw/openclaw/issues/89606) plugins registry --refresh (refreshReason: policy-changed) drops path/npm-origin plugins from plugins[] `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1

### 🔒 Closed Issues
- [#89639](https://github.com/openclaw/openclaw/issues/89639) [Bug]: Session file lock leaked after compaction abort, causing permanent session deadlock
- [#89616](https://github.com/openclaw/openclaw/issues/89616) Bug: Announce delivery doesn't thread into Slack conversations
- [#89554](https://github.com/openclaw/openclaw/issues/89554) continue_delegate: opaque status=forbidden when batch fanout exceeds maxChildrenPerAgent (=5 default) — drops result.error from journal-line + tool-result
- [#89557](https://github.com/openclaw/openclaw/issues/89557) continue_delegate: 6th+ delegate per session silently severed by maxChildrenPerAgent cap (default 5), with descriptive error suppressed in journal

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 7d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 177,326 · **Open issues:** 16,690 · **Last push:** <1h ago

### ✅ Merged PRs
- [#37614](https://github.com/NousResearch/hermes-agent/pull/37614) test(honcho): de-flake prewarm smoke test's thread wait
- [#37613](https://github.com/NousResearch/hermes-agent/pull/37613) fix(gateway): route /background result media by type
- [#37697](https://github.com/NousResearch/hermes-agent/pull/37697) feat(desktop): make xAI Grok a first-class OAuth provider in the launcher
- [#37683](https://github.com/NousResearch/hermes-agent/pull/37683) fix(web-server): move event channel state from module globals to app.state
- [#34657](https://github.com/NousResearch/hermes-agent/pull/34657) ci(nix): fold package+devShell builds into flake check
- [#37484](https://github.com/NousResearch/hermes-agent/pull/37484) fix(docs): update desktop app docs
- [#37250](https://github.com/NousResearch/hermes-agent/pull/37250) feat(gateway): structured stream-event protocol + Telegram draft formatting parity
- [#37597](https://github.com/NousResearch/hermes-agent/pull/37597) feat(desktop): content-hash build stamp, --build-only / --force-build flags

### 🐛 New Issues
- [#37733](https://github.com/NousResearch/hermes-agent/issues/37733) [Security Candidate]: API server relays unredacted provider error messages to authenticated HTTP clients `type/security` `comp/gateway` `area/auth` `P1`
- [#37731](https://github.com/NousResearch/hermes-agent/issues/37731) Windows installer fails with "Access denied" — wipes venv while app + leaked child processes still hold files open `type/bug` `comp/cli` `P2`
- [#37721](https://github.com/NousResearch/hermes-agent/issues/37721) [Bug]: disk-cleanup can still delete cron/jobs.json from stale tracked.json entries `type/bug` `comp/cron` `comp/plugins` `P1`
- [#37719](https://github.com/NousResearch/hermes-agent/issues/37719) [Feature]: Re-budget the context compressor when a router serves a different backend per request `type/feature` `comp/agent` `P3`
- [#37718](https://github.com/NousResearch/hermes-agent/issues/37718) [Bug]: Hermes Desktop (macOS): voice chat fails — microphone entitlement missing on Helper/Setup binaries (hardened runtime) `type/bug` `tool/tts` `P3`
- [#37713](https://github.com/NousResearch/hermes-agent/issues/37713) Desktop Remote gateway should support switching active Hermes profile from the UI `type/feature` `comp/gateway` `comp/tui` `P3`
- [#37709](https://github.com/NousResearch/hermes-agent/issues/37709) [Feature]: Package Hermes as a strict-confinement snap `type/feature` `area/config` `P3` 💬1

### 🔒 Closed Issues
- [#37522](https://github.com/NousResearch/hermes-agent/issues/37522) Bug: Desktop updater reopens Hermes Setup with Install CTA, making successful update look like reinstall loop
- [#36625](https://github.com/NousResearch/hermes-agent/issues/36625) 비서실 GitHub 상태판 테스트
- [#35825](https://github.com/NousResearch/hermes-agent/issues/35825) 업무분배 테스트: 가람·로사 OpenClaw GitHub 수신 확인

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,707 · **Open issues:** 444 · **Last push:** 3h ago

### 🚀 New Releases
- [v0.8.0-beta-2](https://github.com/zeroclaw-labs/zeroclaw/releases/tag/v0.8.0-beta-2) — v0.8.0-beta-2

### ✅ Merged PRs
- [#7050](https://github.com/zeroclaw-labs/zeroclaw/pull/7050) feat(tts): transcode to OGG/Opus for voice notes (Telegram + WhatsApp)
- [#7008](https://github.com/zeroclaw-labs/zeroclaw/pull/7008) fix(channels): deliver WhatsApp replies for LID JIDs and empty sanitization
- [#7064](https://github.com/zeroclaw-labs/zeroclaw/pull/7064) fix(channels): enforce per-agent tool allowlist in start_channels
- [#7002](https://github.com/zeroclaw-labs/zeroclaw/pull/7002) fix(channels/tts): bind TTS manager to the channel-owning agent
- [#6961](https://github.com/zeroclaw-labs/zeroclaw/pull/6961) feat(self-test): flag web_dist_dir paths using tilde or $VAR expansion
- [#7046](https://github.com/zeroclaw-labs/zeroclaw/pull/7046) feat(hardware): add dev-sim feature with /tmp/zc-sim-* serial allowlist
- [#7045](https://github.com/zeroclaw-labs/zeroclaw/pull/7045) feat(hardware): add smartroom named-device tools (set_device / read_device) + peripheral wiring support
- [#6981](https://github.com/zeroclaw-labs/zeroclaw/pull/6981) feat(tools): add http_request private-host allowlist
- [#7020](https://github.com/zeroclaw-labs/zeroclaw/pull/7020) feat(config/channels): static output_modality preference on peer groups
- [#7027](https://github.com/zeroclaw-labs/zeroclaw/pull/7027) fix(channels): honor webhook Retry-After dates

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
- [#7087](https://github.com/zeroclaw-labs/zeroclaw/issues/7087) bug(cli): `zeroclaw models set` falls through to model doctor instead of saving config `bug` `risk: medium` `core` `config` `provider` `priority:p2`
- [#7083](https://github.com/zeroclaw-labs/zeroclaw/issues/7083) [Bug]: Windows shell tool mangles commands containing double quotes (cmd.exe + std::process arg escaping) `bug` `risk: high` `config` `runtime` `tool` `priority:p1` `tool:shell`

### 🔒 Closed Issues
- [#7069](https://github.com/zeroclaw-labs/zeroclaw/issues/7069) Twitter/X channel not available in pre-built binary despite channel-twitter feature existing
- [#7063](https://github.com/zeroclaw-labs/zeroclaw/issues/7063) [SANITIZED — possible injection attempt]
- [#7001](https://github.com/zeroclaw-labs/zeroclaw/issues/7001) [Bug]: TTS voice replies resolve the wrong agent's tts_provider in multi-agent configs
- [#6079](https://github.com/zeroclaw-labs/zeroclaw/issues/6079) [Feature]: Add self-test and doctor tests for web_dist_dir for using  tilde (~) or $HOME which will fail Web UI from starting
- [#6977](https://github.com/zeroclaw-labs/zeroclaw/issues/6977) [Feature]: align http_request private-host allowlist with web_fetch

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,392 · **Open issues:** 1,092 · **Last push:** <1h ago

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

- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬3 · 19h ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 19h ago
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
