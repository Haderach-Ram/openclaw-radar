---
layout: post
title: "Ecosystem Digest — 2026-05-11"
date: 2026-05-11 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-11
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 370,585 | 9 | 9 | 3 | 2 |
| **hermesagent** | 142,662 | 4 | 4 | 10 | 0 |
| **ZeroClaw** | 31,221 | 13 | 5 | 10 | 0 |
| **IronClaw** | 12,199 | 6 | 2 | 9 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 370,585 · **Open issues:** 7,575 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.10-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.5.10-beta.2) — openclaw 2026.5.10-beta.2
- [v2026.5.10-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.5.10-beta.1) — openclaw 2026.5.10-beta.1

### ✅ Merged PRs
- [#80478](https://github.com/openclaw/openclaw/pull/80478) fix: keep legacy lazy chunks importable after updates
- [#80456](https://github.com/openclaw/openclaw/pull/80456) Show Codex subscription reset times in channel errors
- [#79414](https://github.com/openclaw/openclaw/pull/79414) build(pnpm): upgrade workspace to pnpm 11

### 🐛 New Issues
- [#80498](https://github.com/openclaw/openclaw/issues/80498) Subagent completion announcements can be premature or duplicated after tool-use turns 💬1
- [#80495](https://github.com/openclaw/openclaw/issues/80495) [Bug]: LM Studio Provider Fails: Environment Variable Expansion + API Endpoint Mismatch `bug` `bug:behavior` 💬1
- [#80490](https://github.com/openclaw/openclaw/issues/80490) doctor --fix does not auto-build unbuilt plugins (validator error misdirects users) 💬1
- [#80487](https://github.com/openclaw/openclaw/issues/80487) [Bug]: Per-model `api` override not resolved in auth path `bug` `bug:behavior` 💬1
- [#80483](https://github.com/openclaw/openclaw/issues/80483) voice-call realtime: "Realtime voice provider \"openai\" is not registered" on startup — load-order bug similar to #60936 but on realtime voice path 💬1
- [#80476](https://github.com/openclaw/openclaw/issues/80476) [Feature]: bundled openai-compatible embedding provider for self-hosted servers (llama.cpp, Ollama, vLLM, TGI, LocalAI) 💬1
- [#80469](https://github.com/openclaw/openclaw/issues/80469) `/btw` uses plain OpenAI Responses with Codex OAuth instead of active Codex transport 💬1
- [#80468](https://github.com/openclaw/openclaw/issues/80468) Cron-delivered messages not visible in channel session context 💬1
- [#80462](https://github.com/openclaw/openclaw/issues/80462) [Bug]: openclaw doctor regenerates systemd user unit on every update, clobbering custom TimeoutStartSec / ExecStart / EnvironmentFile 💬1

### 🔒 Closed Issues
- [#79936](https://github.com/openclaw/openclaw/issues/79936) [Feature]: CLI setup wizard has no i18n — all prompts hardcoded English across 11 files
- [#79460](https://github.com/openclaw/openclaw/issues/79460) Question: preferred approach for Chinese (zh-CN/zh-TW) docs localization?
- [#47951](https://github.com/openclaw/openclaw/issues/47951) ACP Codex long tasks can be accepted but never start (empty child session transcript)
- [#47643](https://github.com/openclaw/openclaw/issues/47643) [Bug]: Persistent Telegram Channel Issues: Sync Failures, Loops, and Config Changes Not Applying on Windows
- [#80459](https://github.com/openclaw/openclaw/issues/80459) [Bug]: Windows Control UI update leaves external Discord plugin in stale/broken install state
- [#47651](https://github.com/openclaw/openclaw/issues/47651) Feature request: Multimodal memory indexing via Gemini Embedding 2
- [#47555](https://github.com/openclaw/openclaw/issues/47555) [Bug]: --profile flag ignored when executing gateway restart from agent session
- [#46810](https://github.com/openclaw/openclaw/issues/46810) Control UI: Exec approval modal with command highlighting
- [#46341](https://github.com/openclaw/openclaw/issues/46341) [Bug] Recurring cron jobs silently skip transient-error retry — only one-shot jobs retry with backoff

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 142,662 · **Open issues:** 9,866 · **Last push:** <1h ago

### ✅ Merged PRs
- [#23486](https://github.com/NousResearch/hermes-agent/pull/23486) test(conftest): plug every gateway-kill leak path
- [#23482](https://github.com/NousResearch/hermes-agent/pull/23482) fix(auxiliary): evict cached client on timeout/connection error
- [#23458](https://github.com/NousResearch/hermes-agent/pull/23458) fix(telegram): normalize DM threads and retry control sends (salvage of #10371)
- [#23483](https://github.com/NousResearch/hermes-agent/pull/23483) docs(kanban): worker lane contract + review-required convention (closes #19931)
- [#23456](https://github.com/NousResearch/hermes-agent/pull/23456) feat(goals): /goal checklist + /subgoal user controls
- [#23455](https://github.com/NousResearch/hermes-agent/pull/23455) fix(stream-consumer): use UTF-16 length for Telegram message splitting (salvage of #11170)
- [#23454](https://github.com/NousResearch/hermes-agent/pull/23454) fix(cli): drive _prompt_text_input directly when off main thread (#23185)
- [#23453](https://github.com/NousResearch/hermes-agent/pull/23453) fix(tools): clarify kanban_complete phantom-card retry guidance (salvage #23072)
- [#23440](https://github.com/NousResearch/hermes-agent/pull/23440) fix(telegram): pass source.thread_id explicitly on auto-reset notice (carve-out of #7404)
- [#23439](https://github.com/NousResearch/hermes-agent/pull/23439) fix(tui): right-click copies selection, only pastes when no selection

### 🐛 New Issues
- [#23501](https://github.com/NousResearch/hermes-agent/issues/23501) [Feature]: Region-aware model filtering — hide geoblocked models from /model picker `type/feature` `comp/cli` `comp/tui` `P3`
- [#23496](https://github.com/NousResearch/hermes-agent/issues/23496) [Bug]: Headless VM fails to use browser: tools/browser_tool.py writes AGENT_BROWSER_CHROME_FLAGS but agent-browser reads AGENT_BROWSER_ARGS  --sandbox-bypass injection is a no-op `type/bug` `comp/tools` `tool/browser` `P1` 💬1
- [#23491](https://github.com/NousResearch/hermes-agent/issues/23491) [Bug]: Feishu WebSocket disconnect leaves gateway as zombie process — cron ticker stops, no auto-reconnect `type/bug` `duplicate` `comp/gateway` `platform/feishu` `P2` 💬1
- [#23487](https://github.com/NousResearch/hermes-agent/issues/23487) [Feature]: Option to disable new session banner/info `type/feature` `comp/cli` `comp/tui` `P3`

### 🔒 Closed Issues
- [#19932](https://github.com/NousResearch/hermes-agent/issues/19932) Feature: read-only GitHub bridge for Hermes Kanban
- [#23432](https://github.com/NousResearch/hermes-agent/issues/23432) Auxiliary compression timeout can poison cached sync client, causing later auxiliary calls to fail
- [#19931](https://github.com/NousResearch/hermes-agent/issues/19931) Architecture: specialist worker lanes under Hermes Kanban orchestration
- [#3206](https://github.com/NousResearch/hermes-agent/issues/3206) [Bug]: Telegram DM sends fail with 'Message thread not found' — spurious thread_id from reply chains

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,221 · **Open issues:** 475 · **Last push:** 12h ago

### ✅ Merged PRs
- [#6534](https://github.com/zeroclaw-labs/zeroclaw/pull/6534) fix(sop): call reload() after SopEngine construction at both call sites
- [#6533](https://github.com/zeroclaw-labs/zeroclaw/pull/6533) fix(config): respect ZEROCLAW_CONFIG_DIR in path field defaults
- [#6545](https://github.com/zeroclaw-labs/zeroclaw/pull/6545) feat(runtime): multi-agent runtime
- [#6523](https://github.com/zeroclaw-labs/zeroclaw/pull/6523) feat(config)!: V0.8.0 schema-mirror env-var grammar (breaking change); eradicate every legacy override
- [#6546](https://github.com/zeroclaw-labs/zeroclaw/pull/6546) fix(agent): suppress tool protocol when no tools are available
- [#6540](https://github.com/zeroclaw-labs/zeroclaw/pull/6540) fix(build): route source web builds through cargo
- [#6542](https://github.com/zeroclaw-labs/zeroclaw/pull/6542) docs(skills): add user-facing skills guide
- [#6539](https://github.com/zeroclaw-labs/zeroclaw/pull/6539) fix(runtime): require shell approval in direct sessions
- [#6544](https://github.com/zeroclaw-labs/zeroclaw/pull/6544) fix(runtime): omit native tool prompt catalog
- [#6541](https://github.com/zeroclaw-labs/zeroclaw/pull/6541) fix(channels): scope session key for channel tools

### 🐛 New Issues
- [#6563](https://github.com/zeroclaw-labs/zeroclaw/issues/6563) [Feature]: Comfy Cloud / ComfyUI as shared media provider (remote workflows; image + path to gen_video)
- [#6561](https://github.com/zeroclaw-labs/zeroclaw/issues/6561) fix(gateway): non-loopback --host recovery hint advertises admin URL that admin guard rejects
- [#6558](https://github.com/zeroclaw-labs/zeroclaw/issues/6558) [Bug]: providers erro `risk: low` `config` `provider` `provider:compatible` `provider:qwen` `r:support` `priority:p3` 💬2
- [#6557](https://github.com/zeroclaw-labs/zeroclaw/issues/6557) [Feature]: Reconcile runtime model switching with provider structure for v0.8.0 `enhancement` `risk: medium` `channel` `config` `provider` `runtime` `priority:p2` `status:accepted` `status:no-stale`
- [#6556](https://github.com/zeroclaw-labs/zeroclaw/issues/6556) [Bug]: Discord channel — media send/receive broken (inbound images never processed, non-image types dropped, outbound markers leak) `bug` `risk: high` `channel` `security` `channel:discord` `priority:p1` `status:no-stale`
- [#6551](https://github.com/zeroclaw-labs/zeroclaw/issues/6551) [Bug]: Non-leading system messages can be sent to OpenAI-compatible providers `bug` `risk: high` `provider` `runtime` `provider:compatible` `priority:p1` `status:in-progress` `status:no-stale`
- [#6548](https://github.com/zeroclaw-labs/zeroclaw/issues/6548) [Bug]: Channel runtime command replies bypass Fluent localization `bug` `risk: medium` `channel` `runtime` `channel:core` `priority:p2` `status:in-progress` `status:no-stale`
- [#6543](https://github.com/zeroclaw-labs/zeroclaw/issues/6543) [Feature]: ACP session restore `enhancement` `risk: high` `channel` `runtime` `channel:core` `priority:p2` `status:no-stale` 💬1
- [#6530](https://github.com/zeroclaw-labs/zeroclaw/issues/6530) [Bug]: Build failure with matrix-sdk v0.16.0: recursion limit overflow when building with channel-matrix feature `bug` `ci` `risk: low` `channel` `channel:matrix` `status:accepted` `status:no-stale` `priority:p3` 💬4
- [#6520](https://github.com/zeroclaw-labs/zeroclaw/issues/6520) [Bug]:Gemini CLI provider crashes due to outdated argument syntax (--print vs --prompt) `bug` `risk: medium` `provider` `provider:gemini` `priority:p2` `status:accepted` `status:no-stale` 💬2
- [#6419](https://github.com/zeroclaw-labs/zeroclaw/issues/6419) [Bug]: WorkspaceManager fails to load profiles at Runtime startup `bug` `risk: medium` `config` `runtime` `tool` `tool:core` `priority:p2` `status:accepted` `status:no-stale` 💬2
- [#6272](https://github.com/zeroclaw-labs/zeroclaw/issues/6272) Multi-agent runtime: per-alias workspaces, permissions, and shared resources `enhancement` `risk: high` `config` `runtime` `priority:p1` `status:accepted` `status:no-stale` 💬2
- [#6271](https://github.com/zeroclaw-labs/zeroclaw/issues/6271) [Feature]: V3 SwarmConfig schema + runtime implementation `enhancement` `risk: medium` `channel` `config` `tool` `priority:p2` `status:accepted` `status:no-stale` 💬1

### 🔒 Closed Issues
- [#6207](https://github.com/zeroclaw-labs/zeroclaw/issues/6207) [Bug]: Web dashboard / WebSocket gateway path bypasses ApprovalManager — supervised tool approvals never surface in daemon web UI
- [#6547](https://github.com/zeroclaw-labs/zeroclaw/issues/6547) [Feature]: homebrew merge fail
- [#5863](https://github.com/zeroclaw-labs/zeroclaw/issues/5863) [Feature]: Document about skills wanted.
- [#5605](https://github.com/zeroclaw-labs/zeroclaw/issues/5605) [Bug]: Default Configuration Path Issues in Multi-Instance Deployments
- [#6030](https://github.com/zeroclaw-labs/zeroclaw/issues/6030) [Feature]: scope TOOL_LOOP_SESSION_KEY in channel orchestrator

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,199 · **Open issues:** 864 · **Last push:** 1h ago

### ✅ Merged PRs
- [#3458](https://github.com/nearai/ironclaw/pull/3458) feat(reborn): extract boot config boundary
- [#3444](https://github.com/nearai/ironclaw/pull/3444) fix(reborn): strengthen host runtime publication gates
- [#3453](https://github.com/nearai/ironclaw/pull/3453) refactor(reborn): type loop support identity fields
- [#3455](https://github.com/nearai/ironclaw/pull/3455) feat(reborn): add standalone CLI binary crate
- [#3442](https://github.com/nearai/ironclaw/pull/3442) test(KB-037): verify LoopExit contract acceptance criteria and add gap coverage tests
- [#3441](https://github.com/nearai/ironclaw/pull/3441) test(KB-060): verify checkpoint state store acceptance criteria & strengthen edge-case coverage
- [#3439](https://github.com/nearai/ironclaw/pull/3439) feat(reborn): add text-only loop driver host factory
- [#3438](https://github.com/nearai/ironclaw/pull/3438) Add Reborn turn run scheduler
- [#3450](https://github.com/nearai/ironclaw/pull/3450) Finalize Reborn visible surface contract

### 🐛 New Issues
- [#3459](https://github.com/nearai/ironclaw/issues/3459) [Reborn] Add user-selectable model routes and provider pool `reborn`
- [#3452](https://github.com/nearai/ironclaw/issues/3452) [Reborn] Replace stringly loop support identity/reason fields `risk: medium` `refactoring` `reborn`
- [#3451](https://github.com/nearai/ironclaw/issues/3451) [Reborn] Add direct DB operations for loop checkpoint mappings `risk: medium` `scope: db` `reborn`
- [#3447](https://github.com/nearai/ironclaw/issues/3447) Nightly E2E failed
- [#3259](https://github.com/nearai/ironclaw/issues/3259) Publish 0.25.0–0.27.0 to crates.io — downstream pinned to 0.24.0 by wasmtime 28.x CVEs 💬2
- [#2752](https://github.com/nearai/ironclaw/issues/2752) [QA] command onboard throws db error on provider step `bug` `scope: db` `scope: secrets` `scope: setup` `bug_bash_P1` 💬1

### 🔒 Closed Issues
- [#3402](https://github.com/nearai/ironclaw/issues/3402) [Reborn] Add loop driver registry and readiness validation
- [#3090](https://github.com/nearai/ironclaw/issues/3090) [Reborn] Add ToolSurfaceService and CapabilityCatalog

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 1d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 1d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 15 new
- [[Events] Aws Summit Dc](https://www.anthropic.com/events/aws-summit-dc) _2026-05-11_
- [[Events] Aws Summit London](https://www.anthropic.com/events/aws-summit-london) _2026-05-11_
- [[Events] Aws Summit Nyc](https://www.anthropic.com/events/aws-summit-nyc) _2026-05-11_
- [[Events] Aws Summit Tokyo](https://www.anthropic.com/events/aws-summit-tokyo) _2026-05-11_
- [[Events] Claude For Finance](https://www.anthropic.com/events/claude-for-finance) _2026-05-11_
- [[Events] Google Cloud Next 2025](https://www.anthropic.com/events/google-cloud-next-2025) _2026-05-11_
- [[Events] Paris Builder Summit](https://www.anthropic.com/events/paris-builder-summit) _2026-05-11_
- [[Events] Seoul Builder Summit](https://www.anthropic.com/events/seoul-builder-summit) _2026-05-11_
- [[Features] 81K Interviews](https://www.anthropic.com/features/81k-interviews) _2026-05-11_
- [[Features] Claude On Mars](https://www.anthropic.com/features/claude-on-mars) _2026-05-11_
- [[Features] Project Deal](https://www.anthropic.com/features/project-deal) _2026-05-11_
- [Glasswing](https://www.anthropic.com/glasswing) _2026-05-11_
- [Learn](https://www.anthropic.com/learn) _2026-05-11_
- [Supported Countries](https://www.anthropic.com/supported-countries) _2026-05-11_
- [Unsubscribe](https://www.anthropic.com/unsubscribe) _2026-05-11_

### OpenAI — 25 new
- [[Business] Customer Stories](https://openai.com/business/customer-stories/) _2026-05-11_
- [Api Scale Tier](https://openai.com/api-scale-tier/) _2026-05-10_
- [[Chatgpt] Overview](https://openai.com/chatgpt/overview/) _2026-05-10_
- [[Index] Rakuten 2024](https://openai.com/index/rakuten-2024/) _2026-05-11_
- [[Index] Cred Swamy Seetharaman](https://openai.com/index/cred-swamy-seetharaman/) _2026-05-10_
- [[Index] Model Ml Chaz Englander](https://openai.com/index/model-ml-chaz-englander/) _2026-05-10_
- [[Index] O1 Economics](https://openai.com/index/o1-economics/) _2026-05-10_
- [[Index] Next Phase Of Microsoft Partnership](https://openai.com/index/next-phase-of-microsoft-partnership/) _2026-05-10_
- [[Index] Delivering Low Latency Voice Ai At Scale](https://openai.com/index/delivering-low-latency-voice-ai-at-scale/) _2026-05-10_
- [[Index] Cybersecurity In The Intelligence Age](https://openai.com/index/cybersecurity-in-the-intelligence-age/) _2026-05-11_
- [[Index] Cisco](https://openai.com/index/cisco/) _2026-05-11_
- [[Index] Scania](https://openai.com/index/scania/) _2026-05-11_
- [[Index] Harvey](https://openai.com/index/harvey/) _2026-05-11_
- [[Index] Basis](https://openai.com/index/basis/) _2026-05-11_
- [[Index] Ada](https://openai.com/index/ada/) _2026-05-11_
- [[Index] Rakuten 2024](https://openai.com/index/rakuten-2024/) _2026-05-11_
- [[Index] Indeed](https://openai.com/index/indeed/) _2026-05-11_
- [[Index] Cna Walter Fernandez](https://openai.com/index/cna-walter-fernandez/) _2026-05-11_
- [[Index] Safetykit](https://openai.com/index/safetykit/) _2026-05-11_
- [[Index] Uber](https://openai.com/index/uber/) _2026-05-11_
- [[Index] 10Bedicu](https://openai.com/index/10bedicu/) _2026-05-11_
- [[Index] Doordash Mariana Garavaglia](https://openai.com/index/doordash-mariana-garavaglia/) _2026-05-11_
- [[Index] Launchdarkly Claire Vo](https://openai.com/index/launchdarkly-claire-vo/) _2026-05-11_
- [[Index] Steuerrecht](https://openai.com/index/steuerrecht/) _2026-05-11_
- [[Index] Uber Enables Outstanding Experiences](https://openai.com/index/uber-enables-outstanding-experiences/) _2026-05-11_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*