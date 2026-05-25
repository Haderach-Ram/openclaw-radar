---
layout: post
title: "Ecosystem Digest — 2026-05-25"
date: 2026-05-25 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-25
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 374,419 | 7 | 3 | 7 | 2 |
| **hermesagent** | 165,769 | 7 | 6 | 10 | 0 |
| **ZeroClaw** | 31,565 | 13 | 5 | 10 | 0 |
| **IronClaw** | 12,333 | 3 | 6 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 374,419 · **Open issues:** 6,822 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.24-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.5.24-beta.2) — openclaw 2026.5.24-beta.2
- [v2026.5.24-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.5.24-beta.1) — openclaw 2026.5.24-beta.1

### ✅ Merged PRs
- [#82958](https://github.com/openclaw/openclaw/pull/82958) fix(telegram): route polling diagnostics away from errors
- [#84846](https://github.com/openclaw/openclaw/pull/84846) fix(gateway): back off session tool mirrors under pressure
- [#85739](https://github.com/openclaw/openclaw/pull/85739) fix(config): skip shell env fallback on Windows
- [#84834](https://github.com/openclaw/openclaw/pull/84834) fix(gateway): avoid duplicate session message broadcasts
- [#86150](https://github.com/openclaw/openclaw/pull/86150) Repair anchorless iMessage watch payload routing
- [#85780](https://github.com/openclaw/openclaw/pull/85780) fix(cli): route node status hints to stdout
- [#86060](https://github.com/openclaw/openclaw/pull/86060) Fix oc-path deep config edits

### 🐛 New Issues
- [#86288](https://github.com/openclaw/openclaw/issues/86288) Clarify AGENTS.md review policy for config/default additions as merge risk `maintainer` 💬1
- [#86262](https://github.com/openclaw/openclaw/issues/86262) Telegram forum topic responses routed to DM instead of group (channel=webchat instead of channel=telegram) `P1` `clawsweeper:needs-info` `impact:session-state` `impact:message-loss` `issue-rating: 🦐 gold shrimp` 💬1
- [#86249](https://github.com/openclaw/openclaw/issues/86249) [Bug]: REM phase ignores light-sleep staged candidates — rescans full short-term store, recycling old high-scoring entries `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#86241](https://github.com/openclaw/openclaw/issues/86241) [Bug]:[Bug] preserveGatewayHookRunner causes handler stacking + N-fold delivery after subagent hot-reload cycles (2026.5.22 regression) `bug` `regression` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:session-state` `impact:data-loss` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬1
- [#86239](https://github.com/openclaw/openclaw/issues/86239) [Bug]: MissingAgentHarnessError on inbound dispatch under event-loop starvation — harness IS registered (2026.5.22, distinct root cause from #86227) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬2
- [#86237](https://github.com/openclaw/openclaw/issues/86237) Rename 'cron' subsystem to disambiguate from system cron 💬1
- [#86236](https://github.com/openclaw/openclaw/issues/86236) Cron isolated main with Codex runtime exposes only message tool while manual main exposes bash `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:security` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬1

### 🔒 Closed Issues
- [#82957](https://github.com/openclaw/openclaw/issues/82957) [Bug]: Telegram polling startup diagnostic is logged at error level
- [#84844](https://github.com/openclaw/openclaw/issues/84844) [Bug]: Gateway scheduler keeps work queued while CPU is saturated
- [#84795](https://github.com/openclaw/openclaw/issues/84795) Windows native: shell env fallback failed with spawnSync /bin/sh ENOENT

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 165,769 · **Open issues:** 13,469 · **Last push:** <1h ago

### ✅ Merged PRs
- [#31775](https://github.com/NousResearch/hermes-agent/pull/31775) docs(docker): add 'Installing more tools in the container' section
- [#31758](https://github.com/NousResearch/hermes-agent/pull/31758) fix(security): redact credentials before persistence in session capture (salvage #24758 + #19855)
- [#31759](https://github.com/NousResearch/hermes-agent/pull/31759) fix(image_gen): cache xAI ephemeral URL responses to disk (#26942)
- [#31601](https://github.com/NousResearch/hermes-agent/pull/31601) fix(model): disambiguate xAI OAuth picker label
- [#31748](https://github.com/NousResearch/hermes-agent/pull/31748) refactor(gateway): migrate Mattermost adapter to bundled plugin (salvage of #30916)
- [#31745](https://github.com/NousResearch/hermes-agent/pull/31745) feat(tts): add register_tts_provider() plugin hook (salvage of #30420)
- [#24788](https://github.com/NousResearch/hermes-agent/pull/24788) Harden Google Chat OAuth credential persistence
- [#31744](https://github.com/NousResearch/hermes-agent/pull/31744) ci(supply-chain): anchor install-hook regex at repo root
- [#31747](https://github.com/NousResearch/hermes-agent/pull/31747) fix(security): salvage #30553 + #11004 OAuth file-safety hardening
- [#21152](https://github.com/NousResearch/hermes-agent/pull/21152) fix(security): close TOCTOU window when saving Claude Code OAuth credentials

### 🐛 New Issues
- [#31791](https://github.com/NousResearch/hermes-agent/issues/31791) Bug: read_file produces confusing error when called with empty/missing path
- [#31789](https://github.com/NousResearch/hermes-agent/issues/31789) Feature request: memory-only profile isolation with shared runtime state `type/feature` `tool/memory` `area/config` `P3`
- [#31782](https://github.com/NousResearch/hermes-agent/issues/31782) Add private DuckDB workflow-lab analyzer `type/feature` `P3` 💬1
- [#31780](https://github.com/NousResearch/hermes-agent/issues/31780) hermes doctor --fix does not fix custom_providers dict→list structure issue `type/bug` `comp/cli` `area/config` `P2`
- [#31776](https://github.com/NousResearch/hermes-agent/issues/31776) Feature request: expose multi-bank routing for Hindsight memory tools `duplicate` `type/feature` `comp/plugins` `tool/memory` `P3` 💬1
- [#31771](https://github.com/NousResearch/hermes-agent/issues/31771) [Bug]: QQBot adapter busy-loops after WebSocket reconnect failure, causing 100% CPU `type/bug` `comp/gateway` `platform/qqbot` `P2` 💬1
- [#31762](https://github.com/NousResearch/hermes-agent/issues/31762) feat(prompt_builder): scan HERMES_HOME for global context files (HERMES.md, AGENTS.md, CLAUDE.md) `type/feature` `comp/agent` `P3` 💬2

### 🔒 Closed Issues
- [#27228](https://github.com/NousResearch/hermes-agent/issues/27228) High quota burn with xAI Grok-4.3 OAuth on SuperGrok $30 plan
- [#28068](https://github.com/NousResearch/hermes-agent/issues/28068) X Premium+ (affiliate/gifted) account fails OAuth — receives SuperGrok Heavy build code
- [#26847](https://github.com/NousResearch/hermes-agent/issues/26847) [Bug]: xAI OAuth (xai-oauth) returns HTTP 403 for standard SuperGrok subscribers — backend enforcing Heavy-only despite docs claiming all tiers
- [#5530](https://github.com/NousResearch/hermes-agent/issues/5530) Add "grok" to TOOL_USE_ENFORCEMENT_MODELS for direct xAI usage
- [#26942](https://github.com/NousResearch/hermes-agent/issues/26942) image_gen + video_gen: xAI ephemeral tmp URLs 404 by send_photo time — needs gateway-side caching
- [#30398](https://github.com/NousResearch/hermes-agent/issues/30398) Add register_tts_provider() plugin hook for Python-SDK and streaming TTS engines

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,565 · **Open issues:** 511 · **Last push:** 1h ago

### ✅ Merged PRs
- [#6866](https://github.com/zeroclaw-labs/zeroclaw/pull/6866) feat(channels): support selective channel builds and filter channel list by compiled features
- [#6712](https://github.com/zeroclaw-labs/zeroclaw/pull/6712) fix(provider): replace expect_err panic with propagated error in Codex stream cleanup
- [#6852](https://github.com/zeroclaw-labs/zeroclaw/pull/6852) feat(channels/lark): implement request_approval() for Lark/Feishu
- [#5652](https://github.com/zeroclaw-labs/zeroclaw/pull/5652) feat(provider): add native extended thinking for Anthropic and Bedrock providers
- [#6865](https://github.com/zeroclaw-labs/zeroclaw/pull/6865) fix(providers): avoid synthetic Codex tool call ids
- [#6863](https://github.com/zeroclaw-labs/zeroclaw/pull/6863) fix(providers): preserve Ollama cloud suffix for private remotes
- [#6868](https://github.com/zeroclaw-labs/zeroclaw/pull/6868) fix(mdbook): stabilize gettext catalog diffs for docs sync
- [#6855](https://github.com/zeroclaw-labs/zeroclaw/pull/6855) docs(triage): sync stale exemption label spelling
- [#6890](https://github.com/zeroclaw-labs/zeroclaw/pull/6890) fix(provider): resolve per-provider API key from config model entry
- [#6680](https://github.com/zeroclaw-labs/zeroclaw/pull/6680) feat(channel): add WeCom AI Bot WebSocket channel

### 🐛 New Issues
- [#6906](https://github.com/zeroclaw-labs/zeroclaw/issues/6906) [Feature]: improve Nix flake `enhancement`
- [#6895](https://github.com/zeroclaw-labs/zeroclaw/issues/6895) feat(channels): define a lean default channel set `enhancement` `risk: medium` `dependencies` `channel` `config` `priority:p2` `status:accepted` `status:no-stale`
- [#6891](https://github.com/zeroclaw-labs/zeroclaw/issues/6891) [Bug]: Scheduled Jobs edit error API 422 `bug` `risk: medium` `cron` `gateway` `cron:scheduler` `gateway: api` `priority:p1` `status:accepted` `status:no-stale` `web` 💬1
- [#6889](https://github.com/zeroclaw-labs/zeroclaw/issues/6889) [Bug]: reqwest errors in provider only show top-level message, hiding root cause `bug` `risk: medium` `observability` `provider` `provider:anthropic` `provider:compatible` `provider:openrouter` `priority:p2` `status:accepted` `status:no-stale` 💬1
- [#6888](https://github.com/zeroclaw-labs/zeroclaw/issues/6888) [Bug]: Daemon component 'channels' exits unexpectedly in container (v0.8-beta-1) `bug` `risk: high` `channel` `daemon` `runtime` `priority:p1` `status:in-progress` `status:no-stale` 💬1
- [#6883](https://github.com/zeroclaw-labs/zeroclaw/issues/6883) RFC: Shared reply-message constructor on SendMessage `enhancement` `risk: medium` `channel` `channel: core` `type:rfc` `status:accepted` `status:no-stale` `priority:p3` 💬1
- [#6881](https://github.com/zeroclaw-labs/zeroclaw/issues/6881) [SANITIZED — possible injection attempt] `bug` `risk: medium` `channel` `config` `priority:p1` `channel:email` `status:accepted` `status:no-stale`
- [#6880](https://github.com/zeroclaw-labs/zeroclaw/issues/6880) fix(cron): inject Lark and Feishu delivery defaults from chat context `bug` `risk: medium` `cron` `runtime` `channel:lark` `priority:p2` `status:accepted` `status:no-stale`
- [#6879](https://github.com/zeroclaw-labs/zeroclaw/issues/6879) fix(discord): keep gateway preflight 429 retryable `bug` `risk: medium` `channel` `channel:discord` `priority:p1` `status:accepted` `status:no-stale`
- [#6878](https://github.com/zeroclaw-labs/zeroclaw/issues/6878) [Bug]: Bubblewrap fails on Fedora 43 due to bwrap parameters missing /lib64 and therefore not allowing linked-libraries.  Linked to issue #5126 `bug` `risk: high` `runtime` `security` `security:bubblewrap` `priority:p1` `status:accepted` `status:no-stale` 💬2
- [#6877](https://github.com/zeroclaw-labs/zeroclaw/issues/6877) [runtime_profiles.*].max_tool_iterations has no effect — must be set on [agents.*] instead `bug` `risk: high` `docs` `agent` `config` `runtime` `priority:p1` `status:accepted` `status:no-stale` 💬2
- [#6876](https://github.com/zeroclaw-labs/zeroclaw/issues/6876) risk_profile.allowed_tools does not restrict MCP tools — by design or documentation gap? `bug` `risk: high` `docs` `config` `runtime` `security` `tool` `priority:p1` `tool:mcp` `status:accepted` `status:no-stale` 💬1
- [#6875](https://github.com/zeroclaw-labs/zeroclaw/issues/6875) Tool call parser does not handle <tool_calls> (plural) tag — Llama 4 Scout and similar models fail silently `bug` `risk: medium` `provider` `runtime` `tool` `provider:compatible` `provider:groq` `priority:p1` `status:accepted` `status:no-stale` 💬1

### 🔒 Closed Issues
- [#6708](https://github.com/zeroclaw-labs/zeroclaw/issues/6708) bug(provider): avoid expect_err panic in Codex UTF-8 stream cleanup
- [#5630](https://github.com/zeroclaw-labs/zeroclaw/issues/5630) [Feature]: Native extended thinking support for Anthropic provider
- [#6770](https://github.com/zeroclaw-labs/zeroclaw/issues/6770) [Feature]: `zeroclaw channel list` should only show channels compiled into the current build
- [#6697](https://github.com/zeroclaw-labs/zeroclaw/issues/6697) [Bug]: make cargo mdbook sync produce stable minimal gettext diffs
- [#6201](https://github.com/zeroclaw-labs/zeroclaw/issues/6201) [Feature]: recover WeCom AI Bot WebSocket channel as separate wecom_ws support

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,333 · **Open issues:** 1,007 · **Last push:** <1h ago

### ✅ Merged PRs
- [#4014](https://github.com/nearai/ironclaw/pull/4014) Classify recoverable tool operation failures
- [#4009](https://github.com/nearai/ironclaw/pull/4009) [codex] Log raw Reborn errors before safe summaries
- [#4010](https://github.com/nearai/ironclaw/pull/4010) [codex] Add model-visible tool error recovery
- [#3991](https://github.com/nearai/ironclaw/pull/3991) [codex] Add Reborn local-dev-yolo profile
- [#4005](https://github.com/nearai/ironclaw/pull/4005) [codex] Add Reborn integration binary CI
- [#3925](https://github.com/nearai/ironclaw/pull/3925) Validate GitHub Reborn tools in AgentLoop trace
- [#3999](https://github.com/nearai/ironclaw/pull/3999) Allow multiline provider tool arguments
- [#3998](https://github.com/nearai/ironclaw/pull/3998) [codex] Fix model retry prompt grant renewal
- [#3989](https://github.com/nearai/ironclaw/pull/3989) Resolve built-in capability schemas on visible surfaces
- [#3990](https://github.com/nearai/ironclaw/pull/3990) Add Reborn product command foundation

### 🐛 New Issues
- [#4019](https://github.com/nearai/ironclaw/issues/4019) Durably enforce tool-execution invariants: audited single funnel + deny-by-default config + CI boundary tests 💬1
- [#4017](https://github.com/nearai/ironclaw/issues/4017) [SANITIZED — possible injection attempt] 💬3
- [#3988](https://github.com/nearai/ironclaw/issues/3988) Decompose loop support capability port adapter

### 🔒 Closed Issues
- [#3812](https://github.com/nearai/ironclaw/issues/3812) [Reborn] Step 3: Implement Reborn-native OAuth callbacks and setup continuations
- [#3811](https://github.com/nearai/ironclaw/issues/3811) [Reborn] Step 2: Wire Reborn-native product auth and secrets composition
- [#3810](https://github.com/nearai/ironclaw/issues/3810) [Reborn] Step 1: Auth product contracts, V1 behavior inventory, and fake-service tests
- [#3614](https://github.com/nearai/ironclaw/issues/3614) [Reborn WebUI Beta] Define WebChat v2 timeline and event schema
- [#3269](https://github.com/nearai/ironclaw/issues/3269) [Reborn] Define ProductAdapter replacement for stale transport PR
- [#3579](https://github.com/nearai/ironclaw/issues/3579) Port Slack channel to Reborn ProductAdapter

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 8d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬2 · 9d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 12d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
