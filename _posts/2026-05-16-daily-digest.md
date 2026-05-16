---
layout: post
title: "Ecosystem Digest — 2026-05-16"
date: 2026-05-16 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-16
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 372,199 | 11 | 10 | 10 | 2 |
| **hermesagent** | 152,097 | 6 | 1 | 9 | 0 |
| **ZeroClaw** | 31,368 | 11 | 5 | 10 | 0 |
| **IronClaw** | 12,260 | 8 | 0 | 10 | 1 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 372,199 · **Open issues:** 7,019 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.16-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.5.16-beta.1) — openclaw 2026.5.16-beta.1
- [v2026.5.14-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.5.14-beta.2) — openclaw 2026.5.14-beta.2

### ✅ Merged PRs
- [#82391](https://github.com/openclaw/openclaw/pull/82391) fix(config): warn for stale web search providers
- [#82376](https://github.com/openclaw/openclaw/pull/82376) Start configured web search providers at gateway startup
- [#82378](https://github.com/openclaw/openclaw/pull/82378) Fix Codex raw tool-output watchdog
- [#82362](https://github.com/openclaw/openclaw/pull/82362) feat: add xAI Grok OAuth
- [#82289](https://github.com/openclaw/openclaw/pull/82289) fix(plugins): preserve host package during peer repair
- [#82369](https://github.com/openclaw/openclaw/pull/82369) Recover stale embedded tool calls during gateway diagnostics
- [#82363](https://github.com/openclaw/openclaw/pull/82363) Fix session fallback provenance across reloads
- [#82352](https://github.com/openclaw/openclaw/pull/82352) fix: clarify provider timeout ceiling
- [#82324](https://github.com/openclaw/openclaw/pull/82324) [codex] Unify OpenAI auth provider picker
- [#82342](https://github.com/openclaw/openclaw/pull/82342) fix(auto-reply): abort active text stop runs

### 🐛 New Issues
- [#82394](https://github.com/openclaw/openclaw/issues/82394) [Bug]: Empty assistant turn (thinking-only, no text, no toolCall) recorded as finalStatus="success" → user sees generic "Something went wrong" error `bug` 💬1
- [#82390](https://github.com/openclaw/openclaw/issues/82390) [Bug] Slack DM inbound silently dropped for thread replies + assistant_app_thread message_changed events 💬2
- [#82383](https://github.com/openclaw/openclaw/issues/82383) [Bug] memory-core dreaming cron job not disabled when dreaming.enabled is set to false 💬2
- [#82372](https://github.com/openclaw/openclaw/issues/82372) [SANITIZED — possible injection attempt] 💬1
- [#82370](https://github.com/openclaw/openclaw/issues/82370) Subagent completion announce delivery always fails with 'active requester session could not be woken' (regression in 2026.5.12) 💬2
- [#82368](https://github.com/openclaw/openclaw/issues/82368) 2026.5.12 update disables Codex plugin / drops runtime migration, causing "Requested agent harness codex is not registered" 💬1
- [#82367](https://github.com/openclaw/openclaw/issues/82367) [Bug]: 2006.5.12 Default model resolution ignores `agents.defaults.model.primary` for non-library Ollama models `bug` `regression` 💬2
- [#82364](https://github.com/openclaw/openclaw/issues/82364) 2026.5.12: session reset reuses stale sessionFile; codex-acp orphans can leave agents stuck 💬1
- [#82357](https://github.com/openclaw/openclaw/issues/82357) [SANITIZED — possible injection attempt] 💬1
- [#82356](https://github.com/openclaw/openclaw/issues/82356) [Regression] Feishu slash commands in Codex/GPT sessions dispatch with delivered=false 💬1
- [#82347](https://github.com/openclaw/openclaw/issues/82347) [Bug]: Telegram channel blocked by infinite retry loop on expired callback_query approval 💬2

### 🔒 Closed Issues
- [#82306](https://github.com/openclaw/openclaw/issues/82306) [Bug]: Subagent completion errors silently swallowed, causing ghost runs with no diagnostic trace
- [#82393](https://github.com/openclaw/openclaw/issues/82393) 5.12 飞书插件 tool calling schema 与 MiMo-V2.5-Pro 不兼容（400 error）
- [#82274](https://github.com/openclaw/openclaw/issues/82274) 2026.5.12: Telegram isolated-ingress HOL blocking + Codex app-server stalls mid-turn after custom_tool_call_output → 30 min idle timeout
- [#82313](https://github.com/openclaw/openclaw/issues/82313) [Bug]: Gateway startup validation rejects tools.web.search.provider: "brave" even when brave plugin is correctly installed (2026.5.12)
- [#82384](https://github.com/openclaw/openclaw/issues/82384) session-resource-loader blocks event loop 5-7s on every agent run (synchronous file I/O)
- [#82385](https://github.com/openclaw/openclaw/issues/82385) [Bug]: Xiaomi MiMo provider: replay fails with 400 "Param Incorrect" when conversation has tool calls
- [#82387](https://github.com/openclaw/openclaw/issues/82387) [Bug] mimo-v2-pro reasoning_content dropped in multi-turn conversation causing 400 error
- [#81819](https://github.com/openclaw/openclaw/issues/81819) [Bug]: Unable to resolve bundled plugin public surface speech-core/runtime-api.js
- [#79462](https://github.com/openclaw/openclaw/issues/79462) [Bug]: 2026.5.7 @openclaw/codex missing openclaw peer link plus stale NODE_PATH causes hook stalls and password_missing
- [#82382](https://github.com/openclaw/openclaw/issues/82382) [Bug]: Session state can be stuck at status="running", hasActiveRun=false after embedded run is aborted

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 152,097 · **Open issues:** 11,545 · **Last push:** <1h ago

### ✅ Merged PRs
- [#26687](https://github.com/NousResearch/hermes-agent/pull/26687) fix(tui): prevent /agents crash on timeout/error statuses
- [#26195](https://github.com/NousResearch/hermes-agent/pull/26195) fix(tui): width-aware markdown table rendering with vertical fallback
- [#26683](https://github.com/NousResearch/hermes-agent/pull/26683) fix(tui): avoid DECSTBM bleed on bottom status row
- [#26664](https://github.com/NousResearch/hermes-agent/pull/26664) fix(xai-oauth): break entitlement-403 credential-refresh loop, bump grok-4.3 context to 1M
- [#26666](https://github.com/NousResearch/hermes-agent/pull/26666) fix(xai-oauth): rewrite entitlement-403 hint to not accuse subscribers
- [#26672](https://github.com/NousResearch/hermes-agent/pull/26672) fix(xai-oauth): lead entitlement-403 hint with X Premium+ gotcha
- [#26646](https://github.com/NousResearch/hermes-agent/pull/26646) feat(docs): show per-skill pages in the left sidebar
- [#26648](https://github.com/NousResearch/hermes-agent/pull/26648) fix(deepseek): wire thinking-mode via DeepSeekProfile (closes #15700, #17212, #17825)
- [#26644](https://github.com/NousResearch/hermes-agent/pull/26644) fix(xai-oauth): recover from prelude SSE errors, gate reasoning replay, surface entitlement 403s

### 🐛 New Issues
- [#26697](https://github.com/NousResearch/hermes-agent/issues/26697) [Bug] send_message tool ignores markdown_support config for QQ platform
- [#26696](https://github.com/NousResearch/hermes-agent/issues/26696) [Feature]: TokenTelemetry Plugin for Integration into Hermes Dashboard
- [#26693](https://github.com/NousResearch/hermes-agent/issues/26693) [Bug]: hermes doctor promotes invalid direct API keys into the final summary even when OAuth fallback is already healthy `type/bug` `comp/cli` `P3` 💬1
- [#26689](https://github.com/NousResearch/hermes-agent/issues/26689) Accessibility improvements for blind VoiceOver users `type/feature` `comp/cli` `comp/gateway` `comp/tui` `P3` 💬1
- [#26675](https://github.com/NousResearch/hermes-agent/issues/26675) [Feature]: Managed Agent Runtime contracts on top of agent_control / Kanban / SessionDB `type/feature` `comp/agent` `comp/plugins` `P3`
- [#26670](https://github.com/NousResearch/hermes-agent/issues/26670) fix(update): hermes update on Windows fails to quarantine hermes.exe when another instance is running `type/bug` `comp/cli` `P3`

### 🔒 Closed Issues
- [#25768](https://github.com/NousResearch/hermes-agent/issues/25768) [Bug]: TUI status bar renders duplicate layers after scrolling transcript

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,368 · **Open issues:** 458 · **Last push:** <1h ago

### ✅ Merged PRs
- [#6621](https://github.com/zeroclaw-labs/zeroclaw/pull/6621) fix(docker): install dashboard outside /zeroclaw-data bind mount (#6400)
- [#6086](https://github.com/zeroclaw-labs/zeroclaw/pull/6086) fix(config): add allowed_path/allowed_paths aliases for allowed_roots
- [#6677](https://github.com/zeroclaw-labs/zeroclaw/pull/6677) test(skills): fix heredoc manifest fixture
- [#6656](https://github.com/zeroclaw-labs/zeroclaw/pull/6656) perf(cron): persist run results in one transaction
- [#6655](https://github.com/zeroclaw-labs/zeroclaw/pull/6655) fix(cron): keep read-only access off schema init path
- [#5952](https://github.com/zeroclaw-labs/zeroclaw/pull/5952) fix(skills): restrict audit to structural checks, delegate command sa…
- [#6596](https://github.com/zeroclaw-labs/zeroclaw/pull/6596) fix(runtime/observability): share PrometheusObserver across subsystems
- [#6133](https://github.com/zeroclaw-labs/zeroclaw/pull/6133) docs(ci): remove stale strict-delta references
- [#6430](https://github.com/zeroclaw-labs/zeroclaw/pull/6430) fix(cli): capture original bash completion function body to prevent infinite recursion
- [#6409](https://github.com/zeroclaw-labs/zeroclaw/pull/6409) feat(skills): show tier banner on `zeroclaw skills install`

### 🐛 New Issues
- [#6691](https://github.com/zeroclaw-labs/zeroclaw/issues/6691) [Bug]: RUST_LOG docs use stale zeroclaw target filters `bug` `risk: low` `docs` `observability` `priority:p2`
- [#6689](https://github.com/zeroclaw-labs/zeroclaw/issues/6689) Production SOP audit is silently no-op: documented sop_run_*/sop_step_* Memory keys are never written
- [#6687](https://github.com/zeroclaw-labs/zeroclaw/issues/6687) Two independent SopEngine instances per daemon: MQTT-started runs are invisible to agent sop_status
- [#6686](https://github.com/zeroclaw-labs/zeroclaw/issues/6686) SOP cron triggers (SopCronCache / check_sop_cron_triggers) have no production caller
- [#6685](https://github.com/zeroclaw-labs/zeroclaw/issues/6685) SOP HTTP fan-in (POST /sop/* and /webhook fallback) is documented but not wired
- [#6683](https://github.com/zeroclaw-labs/zeroclaw/issues/6683) skill_manage `patch` ignores cooldown — unbounded patches per skill possible
- [#6681](https://github.com/zeroclaw-labs/zeroclaw/issues/6681) [Bug]: zeroclaw skills install clawhub:* panics — reqwest::blocking dropped inside #[tokio::main]
- [#6678](https://github.com/zeroclaw-labs/zeroclaw/issues/6678) [Bug]: Skill tools rejected by Anthropic API — `format!("{}.{}", ...)` produces names violating `^[a-zA-Z0-9_-]{1,128}$`
- [#6672](https://github.com/zeroclaw-labs/zeroclaw/issues/6672) [Bug]: reasoning_content not passed back in agentic tool-call loops with Xiaomi thinking mode models (mimo-v2.5, mimo-v2.5-pro) `bug`
- [#6670](https://github.com/zeroclaw-labs/zeroclaw/issues/6670) [Feature]: Localize skills install output and tier banner with Fluent `enhancement` `risk: medium` `runtime` `skills` `priority:p2`
- [#6669](https://github.com/zeroclaw-labs/zeroclaw/issues/6669) [Feature]: Audit observability backends for split-instance metric/trace sinks `enhancement` `risk: medium` `observability` `runtime` `observability:otel` `observability:prometheus` `priority:p2`

### 🔒 Closed Issues
- [#6679](https://github.com/zeroclaw-labs/zeroclaw/issues/6679) bug(ci): require fresh PR checks before merging stale branches
- [#6400](https://github.com/zeroclaw-labs/zeroclaw/issues/6400) [Bug]: Docker bind mount at /zeroclaw-data shadows pre-built web dashboard copied during Dockerfile build
- [#5533](https://github.com/zeroclaw-labs/zeroclaw/issues/5533) [Bug]: allowed_Path doesn't respect contains logic
- [#5833](https://github.com/zeroclaw-labs/zeroclaw/issues/5833) feat(tools): session ownership model for destructive operations
- [#5956](https://github.com/zeroclaw-labs/zeroclaw/issues/5956) [Feature]: Document skill audit scope decision: structural checks only, command-content safety belongs in shell policy

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,260 · **Open issues:** 913 · **Last push:** 2h ago

### 🚀 New Releases
- [ironclaw-v0.28.2](https://github.com/nearai/ironclaw/releases/tag/ironclaw-v0.28.2) — 0.28.2 - 2026-05-14

### ✅ Merged PRs
- [#3652](https://github.com/nearai/ironclaw/pull/3652) arch(ws-16): wire live planned runtime composition
- [#3532](https://github.com/nearai/ironclaw/pull/3532) Fix markdown_to_mrkdwn to avoid converting emphasis inside generated <…
- [#3651](https://github.com/nearai/ironclaw/pull/3651) arch(ws-14): register planned driver default path
- [#3686](https://github.com/nearai/ironclaw/pull/3686) fix(ws-13): ack drained inputs before cancel exit
- [#3665](https://github.com/nearai/ironclaw/pull/3665) feat(engine): IRONCLAW_DISABLE_CODEACT flag to disable v2 CodeAct
- [#3685](https://github.com/nearai/ironclaw/pull/3685) fix(ws-13): wire live cancellation into host
- [#3684](https://github.com/nearai/ironclaw/pull/3684) fix(ws-13): verify cancellation from turn state
- [#3648](https://github.com/nearai/ironclaw/pull/3648) arch(ws-13): add host cancellation accessor
- [#3659](https://github.com/nearai/ironclaw/pull/3659) feat(filesystem): unified storage dispatch fabric — foundation + SQL backends + indexer
- [#3649](https://github.com/nearai/ironclaw/pull/3649) arch(ws-15): add prompt context assembly

### 🐛 New Issues
- [#3692](https://github.com/nearai/ironclaw/issues/3692) Reborn: add policy-gated personal identity and heartbeat prompt context
- [#3690](https://github.com/nearai/ironclaw/issues/3690) hooks: narrow RuntimeEvent to HookObservableEvent projection for Installed-tier event hooks `risk: medium` `scope: hooks`
- [#3689](https://github.com/nearai/ironclaw/issues/3689) hooks: per-hook DoS dispatch budget for event-triggered hooks (Installed tier) `risk: medium` `scope: hooks`
- [#3675](https://github.com/nearai/ironclaw/issues/3675) TUI cannot render the markdown table correctly
- [#3673](https://github.com/nearai/ironclaw/issues/3673) [QA] openai_compatible provider drops reasoning_content on outgoing requests, breaks DeepSeek v4-pro multi-turn tool calls
- [#3627](https://github.com/nearai/ironclaw/issues/3627) [Reborn WebUI Beta] Implement RebornServices submit/cancel/resolve facade methods `scope: channel/web` `scope: config` `suggested_P0` `reborn` `module:M2-inbound-workflow`
- [#3626](https://github.com/nearai/ironclaw/issues/3626) [Reborn WebUI Beta] Bind WebUI caller and thread scope to canonical TurnScope `scope: channel/web` `suggested_P0` `reborn` `module:M2-inbound-workflow`
- [#3625](https://github.com/nearai/ironclaw/issues/3625) [Reborn WebUI Beta] Add WebUI idempotency and accepted-message ledger `scope: channel/web` `suggested_P0` `reborn` `module:M2-inbound-workflow`

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬2 · 1h ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 3d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 6d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 2 new
- [[Index] Databricks](https://openai.com/index/databricks/) _2026-05-16_
- [[Index] Sea David Chen](https://openai.com/index/sea-david-chen/) _2026-05-15_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
