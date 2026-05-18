---
layout: post
title: "Ecosystem Digest — 2026-05-18"
date: 2026-05-18 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-18
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 372,714 | 15 | 10 | 10 | 3 |
| **hermesagent** | 154,927 | 3 | 1 | 2 | 0 |
| **ZeroClaw** | 31,406 | 10 | 4 | 9 | 0 |
| **IronClaw** | 12,279 | 7 | 1 | 6 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 372,714 · **Open issues:** 7,009 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.16-beta.6](https://github.com/openclaw/openclaw/releases/tag/v2026.5.16-beta.6) — openclaw 2026.5.16-beta.6
- [v2026.5.16-beta.5](https://github.com/openclaw/openclaw/releases/tag/v2026.5.16-beta.5) — openclaw 2026.5.16-beta.5
- [v2026.5.16-beta.4](https://github.com/openclaw/openclaw/releases/tag/v2026.5.16-beta.4) — openclaw 2026.5.16-beta.4

### ✅ Merged PRs
- [#83374](https://github.com/openclaw/openclaw/pull/83374) chore(labels): cool label palette
- [#83381](https://github.com/openclaw/openclaw/pull/83381) fix(telegram): fail closed on missing topic threads
- [#83322](https://github.com/openclaw/openclaw/pull/83322) xai: OAuth login fixes plus openclaw User-Agent attribution
- [#83314](https://github.com/openclaw/openclaw/pull/83314) fix(migrate): count hidden config conflicts in preview
- [#83310](https://github.com/openclaw/openclaw/pull/83310) fix(update): require integer timeout values
- [#83371](https://github.com/openclaw/openclaw/pull/83371) test(channels): preserve thread origin contracts
- [#83351](https://github.com/openclaw/openclaw/pull/83351) fix(telegram): preserve forum topic origin targets
- [#83362](https://github.com/openclaw/openclaw/pull/83362) Fix transcript-only assistant rows in latest reply lookup
- [#83357](https://github.com/openclaw/openclaw/pull/83357) chore(labels): add label color sync policy
- [#83332](https://github.com/openclaw/openclaw/pull/83332) fix(cron): suppress source replies for announce delivery

### 🐛 New Issues
- [#83393](https://github.com/openclaw/openclaw/issues/83393) Bug: Signal inbound final replies can remain on Codex/internal surface instead of returning to Signal 💬1
- [#83390](https://github.com/openclaw/openclaw/issues/83390) docs: clarify mechanistic difference between Codex Code Mode and OC generic code mode 💬2
- [#83389](https://github.com/openclaw/openclaw/issues/83389) code-mode: timeout and runtime_unavailable error codes surface as "internal_error" `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` 💬1
- [#83388](https://github.com/openclaw/openclaw/issues/83388) code-mode: AgentToolsSchema rejects "codeMode" key but docs say agent-level config works `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` 💬1
- [#83387](https://github.com/openclaw/openclaw/issues/83387) code-mode: ctx.agentId undefined in before_tool_call for outer code-mode exec dispatch `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-security-review` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:security` `impact:auth-provider` 💬2
- [#83386](https://github.com/openclaw/openclaw/issues/83386) BM25 full-text search returns 0 results for Chinese queries with multiple terms `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `impact:session-state` `clawsweeper:current-main-repro` 💬1
- [#83384](https://github.com/openclaw/openclaw/issues/83384) BM25 full-text search returns 0 results for Chinese queries with multiple terms 💬1
- [#83380](https://github.com/openclaw/openclaw/issues/83380) @openclaw/codex 2026.5.16-beta.4: dispatch sends `profile=-`, 401 "Missing bearer" despite OAuth profile registered & `Auth: yes` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:auth-provider` 💬1
- [#83375](https://github.com/openclaw/openclaw/issues/83375) BlueBubbles: catchup polling uses iMessage;-; GUID prefix but macOS Tahoe creates any;-; chats `P3` `impact:message-loss` 💬1
- [#83366](https://github.com/openclaw/openclaw/issues/83366) [Bug]: Gateway event-loop starvation causes Discord/session timeouts under cron and tool load `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `impact:crash-loop` 💬1
- [#83365](https://github.com/openclaw/openclaw/issues/83365) [Bug]: iMessage group media final replies can silently fail even though direct imsg send-rich succeeds `P2` `clawsweeper:needs-live-repro` `impact:message-loss` 💬1
- [#83364](https://github.com/openclaw/openclaw/issues/83364) agents.files.set hangs for >30s on a specific agentId after N compactions; co-resident agents on the same VM are fine `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:session-state` 💬1
- [#83361](https://github.com/openclaw/openclaw/issues/83361) MCP server anyOf schemas rejected by DeepSeek - should strip at gateway level 💬2
- [#83360](https://github.com/openclaw/openclaw/issues/83360) [Bug]: auto-update can never succeed under systemd — updater is spawned as a child of the gateway it needs to restart `P2` `clawsweeper:source-repro` 💬1
- [#83359](https://github.com/openclaw/openclaw/issues/83359) fix: beta package upgrades can fail during legacy updater handoff `bug` `maintainer` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:crash-loop` 💬1

### 🔒 Closed Issues
- [#80339](https://github.com/openclaw/openclaw/issues/80339) Runtime tool fixtures need a default-tool hard gate after known drifts are fixed
- [#83392](https://github.com/openclaw/openclaw/issues/83392) [Feature]: Session reset pre-callback — allow agent to save context before /reset
- [#83379](https://github.com/openclaw/openclaw/issues/83379) [Bug]: Isolated cron agentTurn fails with 'setup failed: sandbox' — intermittent, pre-runner, before LLM invocation
- [#83284](https://github.com/openclaw/openclaw/issues/83284) [Bug]: migrate text preview can hide blocking config conflicts
- [#83281](https://github.com/openclaw/openclaw/issues/83281) [Bug]: update --timeout accepts partially numeric strings despite positive-integer contract
- [#83373](https://github.com/openclaw/openclaw/issues/83373) [Bug]: After the OpenClaw 2026.5.12 update, VLLM is no longer usable.
- [#78910](https://github.com/openclaw/openclaw/issues/78910) Discord Gateway WS 1006 rapid disconnect loop after upgrade to v2026.5.6
- [#83302](https://github.com/openclaw/openclaw/issues/83302) Telegram forum-topic follow-up delivery can lose topic context when OriginatingTo is flattened
- [#83132](https://github.com/openclaw/openclaw/issues/83132) [Bug]: native subagent spawn can return accepted without durable registry entry
- [#83035](https://github.com/openclaw/openclaw/issues/83035) [Bug]: ERR_INTERNAL_ASSERTION in ESM→CJS translator at gateway startup on both Node 22.22.2 and Node 24.15.0 (Linux)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 154,927 · **Open issues:** 11,899 · **Last push:** <1h ago

### ✅ Merged PRs
- [#27625](https://github.com/NousResearch/hermes-agent/pull/27625) feat(auxiliary): layered fallback (chain → main agent) + capacity-error gate fix
- [#27663](https://github.com/NousResearch/hermes-agent/pull/27663) feat(auth):  Switch to JWT token for inference against Nous and stop replaying invalid Nous refresh tokens 

### 🐛 New Issues
- [#27695](https://github.com/NousResearch/hermes-agent/issues/27695) feat(feishu): support markdown tables via CardKit table element `duplicate` `type/feature` `comp/gateway` `platform/feishu` `P3` 💬1
- [#27689](https://github.com/NousResearch/hermes-agent/issues/27689) [Bug] pre_api_request hook passes messages but test asserts it should not `type/bug` `comp/agent` `comp/plugins` `P3`
- [#27683](https://github.com/NousResearch/hermes-agent/issues/27683) web_tools.py: missing _ensure_plugins_discovered() at search/extract/crawl dispatch sites causes web tools to silently fail `type/bug` `comp/tools` `tool/web` `P2` 💬2

### 🔒 Closed Issues
- [#27692](https://github.com/NousResearch/hermes-agent/issues/27692) feat(feishu): support markdown tables via CardKit table element

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,406 · **Open issues:** 481 · **Last push:** <1h ago

### ✅ Merged PRs
- [#6710](https://github.com/zeroclaw-labs/zeroclaw/pull/6710) [desktop] support for windows and linux for desktop app
- [#6553](https://github.com/zeroclaw-labs/zeroclaw/pull/6553) fix(observability): restore broken SSE /logs stream; add build-stamped version and health pulse for remote/Docker deployments
- [#6707](https://github.com/zeroclaw-labs/zeroclaw/pull/6707) fix(xtask): parse Fluent audit inputs correctly
- [#6172](https://github.com/zeroclaw-labs/zeroclaw/pull/6172) docs: update arduino-uno-q-setup
- [#6673](https://github.com/zeroclaw-labs/zeroclaw/pull/6673) fix(onboard): restore interactive flag compatibility
- [#6550](https://github.com/zeroclaw-labs/zeroclaw/pull/6550) fix(channels): localize runtime command replies
- [#6432](https://github.com/zeroclaw-labs/zeroclaw/pull/6432) fix(memory): tolerate concurrent sqlite schema migrations
- [#6054](https://github.com/zeroclaw-labs/zeroclaw/pull/6054) fix(skills): respect timeout_secs from SKILL.toml
- [#6713](https://github.com/zeroclaw-labs/zeroclaw/pull/6713) fix(cron): use cmd.exe on Windows instead of hardcoded sh

### 🐛 New Issues
- [#6751](https://github.com/zeroclaw-labs/zeroclaw/issues/6751) fix(ci): pr-title workflow has never run — startup_failure on every PR since #6396
- [#6747](https://github.com/zeroclaw-labs/zeroclaw/issues/6747) [Bug]: amannn/action-semantic-pull-request fails to run `bug`
- [#6742](https://github.com/zeroclaw-labs/zeroclaw/issues/6742) [Feature]: Add streaming payload tracing tests for --log-llm `enhancement` `risk: low` `provider` `tests` `provider:reliable`
- [#6739](https://github.com/zeroclaw-labs/zeroclaw/issues/6739) [Bug]: Cron timezone contract is inconsistent across tools, CLI, and API `bug` `risk: high` `cron` `gateway` `runtime` `tool` `priority:p2` `tool:cron` `status:accepted` `status:no-stale`
- [#6734](https://github.com/zeroclaw-labs/zeroclaw/issues/6734) [Bug]: Qwen 3.6 tool-call envelopes can leak into Matrix replies `bug` `risk: high` `channel` `provider` `runtime` `provider:compatible` `provider:qwen` `channel:matrix` `priority:p1` `status:in-progress` `status:no-stale`
- [#6733](https://github.com/zeroclaw-labs/zeroclaw/issues/6733) [Bug]: Matrix streaming draft state is keyed only by room `bug` `risk: medium` `channel` `channel:matrix` `priority:p2` `status:in-progress` `status:no-stale`
- [#6723](https://github.com/zeroclaw-labs/zeroclaw/issues/6723) Native OpenAI provider hardcodes 120s request timeout, silently ignores timeout_secs config `bug` `risk: medium` `config` `provider` `runtime` `provider:openai` `priority:p2` `status:accepted` `status:no-stale`
- [#6722](https://github.com/zeroclaw-labs/zeroclaw/issues/6722) MemoryConfig.rerank_enabled / rerank_threshold scaffolded but no consumer `bug` `risk: medium` `config` `memory` `runtime` `priority:p2` `status:accepted` `status:no-stale`
- [#6721](https://github.com/zeroclaw-labs/zeroclaw/issues/6721) tool_search not in default_auto_approve → deferred_loading+webhook silently hangs 120s then auto-denies `bug` `risk: high` `agent` `config` `gateway` `runtime` `tool` `priority:p1` `tool:mcp` `status:accepted` `status:no-stale`
- [#6720](https://github.com/zeroclaw-labs/zeroclaw/issues/6720) [agent] context_aware_tools config field is declared but unread (dead code) `bug` `risk: medium` `agent` `config` `runtime` `priority:p2` `status:accepted` `status:no-stale`

### 🔒 Closed Issues
- [#5994](https://github.com/zeroclaw-labs/zeroclaw/issues/5994) [Feature]: Build Official Website + End-to-End Documentation (Config and CLI)
- [#6548](https://github.com/zeroclaw-labs/zeroclaw/issues/6548) [SANITIZED — possible injection attempt]
- [#6431](https://github.com/zeroclaw-labs/zeroclaw/issues/6431) [Bug]: SQLite memory schema init can fail during concurrent startup
- [#6705](https://github.com/zeroclaw-labs/zeroclaw/issues/6705) [SANITIZED — possible injection attempt]

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,279 · **Open issues:** 925 · **Last push:** <1h ago

### ✅ Merged PRs
- [#3695](https://github.com/nearai/ironclaw/pull/3695) arch(reborn): consolidate composition root, narrow public surface, ship live binary
- [#3723](https://github.com/nearai/ironclaw/pull/3723) [codex] replace agent-loop planning docs
- [#3131](https://github.com/nearai/ironclaw/pull/3131) Add Trace Commons client to Reborn
- [#3636](https://github.com/nearai/ironclaw/pull/3636) feat(hooks): DenyReasonCode closed-vocabulary enum (successor to #3573)
- [#3683](https://github.com/nearai/ironclaw/pull/3683) feat(reborn): add host-owned ingress contracts
- [#3719](https://github.com/nearai/ironclaw/pull/3719) chore(deps): bump deps to address security advisories

### 🐛 New Issues
- [#3734](https://github.com/nearai/ironclaw/issues/3734) v0.28.2 regression: provider config missing API Key and Fetch available models controls `bug`
- [#3733](https://github.com/nearai/ironclaw/issues/3733) Invalid Gmail token shows success/activated toast `bug`
- [#3732](https://github.com/nearai/ironclaw/issues/3732) Gmail auth gate shows inconsistent UI: OAuth link in one thread, manual token input in another `bug`
- [#3731](https://github.com/nearai/ironclaw/issues/3731) Chat re-prompts `tool_install(gmail)` even though Gmail is already installed `bug`
- [#3729](https://github.com/nearai/ironclaw/issues/3729) Failed `tool_install` calls are shown as successful after page refresh `bug`
- [#3728](https://github.com/nearai/ironclaw/issues/3728) Denying `tool_install(gmail)` once re-prompts the same approval and final response asks user to approve after repeated denial `bug`
- [#3726](https://github.com/nearai/ironclaw/issues/3726) Track Reborn composition crate split and public surface narrowing

### 🔒 Closed Issues
- [#3736](https://github.com/nearai/ironclaw/issues/3736) [Question] v0.28.2 regression: unconfigured providers still show Use button in TEE agents

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 1d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬2 · 2d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 5d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
