---
layout: post
title: "OpenClaw Radar — 2026-05-13"
date: 2026-05-13 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-13
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 371,313 | 7 | 10 | 10 | 3 |
| **hermesagent** | 147,018 | 10 | 0 | 10 | 0 |
| **ZeroClaw** | 31,292 | 1 | 5 | 8 | 0 |
| **IronClaw** | 12,225 | 8 | 4 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 371,313 · **Open issues:** 7,324 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.12-beta.3](https://github.com/openclaw/openclaw/releases/tag/v2026.5.12-beta.3) — openclaw 2026.5.12-beta.3
- [v2026.5.12-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.5.12-beta.2) — openclaw 2026.5.12-beta.2
- [v2026.5.12-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.5.12-beta.1) — openclaw 2026.5.12-beta.1

### ✅ Merged PRs
- [#81246](https://github.com/openclaw/openclaw/pull/81246) fix(whatsapp): drain debounced inbound before close
- [#81236](https://github.com/openclaw/openclaw/pull/81236) [AI-assisted] fix(gateway): clarify invalid config recovery hints
- [#81065](https://github.com/openclaw/openclaw/pull/81065) Limit hook CLI tool authority [AI]
- [#81067](https://github.com/openclaw/openclaw/pull/81067) Require admin scope for node device token management [AI]
- [#80898](https://github.com/openclaw/openclaw/pull/80898) Restrict chat sender allowlist matching [AI]
- [#80834](https://github.com/openclaw/openclaw/pull/80834) fix(install): don't abort install.ps1 when git writes to stderr
- [#81220](https://github.com/openclaw/openclaw/pull/81220) feat(onboard): add --skip-hooks flag
- [#80444](https://github.com/openclaw/openclaw/pull/80444) [security] redact persisted tool result details
- [#80796](https://github.com/openclaw/openclaw/pull/80796) fix(config-audit): scrub pre-redactor argv values from historical config-audit.jsonl entries
- [#81192](https://github.com/openclaw/openclaw/pull/81192) feat(onboard): offer codex migration after harness install

### 🐛 New Issues
- [#81250](https://github.com/openclaw/openclaw/issues/81250) ACP: OpenCode adapter rejects session/set_config_option timeout, causing ACP child sessions to fail immediately 💬1
- [#81249](https://github.com/openclaw/openclaw/issues/81249) [Feature/Bug]: Local Ollama embeddings fail when proxy is enabled (SSRF defenses ignore NO_PROXY) `enhancement` 💬1
- [#81241](https://github.com/openclaw/openclaw/issues/81241) Telegram inbound: openclaw.runtime-context envelope leaks into user message body 💬1
- [#81234](https://github.com/openclaw/openclaw/issues/81234) [2026.5.12-beta.3] Cron agent jobs time out after turn-accepted; Discord DM lane can be blocked by stale cron sessionKey 💬2
- [#81232](https://github.com/openclaw/openclaw/issues/81232) [Feature] Discord: fetch a single message by channelId + messageId (or URL) 💬1
- [#81218](https://github.com/openclaw/openclaw/issues/81218) [Bug]: vLLM/SGLang provider wildcards cannot discover from explicit provider endpoints 💬1
- [#81216](https://github.com/openclaw/openclaw/issues/81216) Dynamic model enumeration for CLI runtimes (claude-cli, codex-cli, google-gemini-cli) instead of static catalog 💬1

### 🔒 Closed Issues
- [#81240](https://github.com/openclaw/openclaw/issues/81240) Slack channel session replies are generated but never posted (silent outbound failure)
- [#80402](https://github.com/openclaw/openclaw/issues/80402) openclaw doctor rewrites agents.defaults.model.primary from claude-cli/* to anthropic/*, breaking CLI session continuity
- [#79413](https://github.com/openclaw/openclaw/issues/79413) [Bug]: Native Codex runtime shows mixed openai-codex model state and idle-timeouts in Telegram direct sessions
- [#73510](https://github.com/openclaw/openclaw/issues/73510) Bug Report: Stuck sessions cause permanent gateway hang with no auto-recovery (v2026.4.26)
- [#81245](https://github.com/openclaw/openclaw/issues/81245) npm-installed third-party channel plugins can load but cannot be configured through the official configure flow
- [#40652](https://github.com/openclaw/openclaw/issues/40652) [Bug]: Gateway invalid-config startup error should suggest --fix and .bak recovery
- [#81237](https://github.com/openclaw/openclaw/issues/81237) Bug: macOS app browser control enabled but connected node does not advertise browser capability
- [#73303](https://github.com/openclaw/openclaw/issues/73303) v2026.4.26: gateway restart can hang ~3-4 min before new process starts
- [#73121](https://github.com/openclaw/openclaw/issues/73121) Zombie running tasks: CLI runtime tasks that terminate are never auto-transitioned to failed/timed_out
- [#72627](https://github.com/openclaw/openclaw/issues/72627) Add per-agent config to disable [[reply_to_current]] directive and auto-send

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 147,018 · **Open issues:** 10,588 · **Last push:** <1h ago

### ✅ Merged PRs
- [#24725](https://github.com/NousResearch/hermes-agent/pull/24725) [SANITIZED — possible injection attempt]
- [#24711](https://github.com/NousResearch/hermes-agent/pull/24711) fix(install): use stash@{0} instead of git rev-parse refs/stash for autostash recovery
- [#24702](https://github.com/NousResearch/hermes-agent/pull/24702) fix(cache): drop ttl=1h on Portal Qwen — Alibaba upstream is 5m-only
- [#24705](https://github.com/NousResearch/hermes-agent/pull/24705) fix(retry): use float() for Retry-After header to handle sub-second values
- [#24706](https://github.com/NousResearch/hermes-agent/pull/24706) fix(signal): handle group messages from linked devices in syncMessage path
- [#24709](https://github.com/NousResearch/hermes-agent/pull/24709) docs(lsp): document follow-up fixes from #24630
- [#24707](https://github.com/NousResearch/hermes-agent/pull/24707) fix(voice_mode): detect audio in WSL when sd.query_devices() returns empty list
- [#24710](https://github.com/NousResearch/hermes-agent/pull/24710) fix(gateway): add chat_id to hook_ctx for message source tracking
- [#24708](https://github.com/NousResearch/hermes-agent/pull/24708) fix(tui): use TERMINAL_CWD in _session_info for accurate status line path
- [#24715](https://github.com/NousResearch/hermes-agent/pull/24715) fix(prompt_builder): inject tool-use enforcement for GLM models

### 🐛 New Issues
- [#24736](https://github.com/NousResearch/hermes-agent/issues/24736) bug(web_tools): TOCTOU race in _get_parallel_client / _get_async_parallel_client / _get_exa_client singleton init
- [#24733](https://github.com/NousResearch/hermes-agent/issues/24733) feat: /yolo <duration> and /yolo until <time> — bounded auto-expiry for yolo mode `type/feature` `comp/cli` `comp/tui` `P3`
- [#24731](https://github.com/NousResearch/hermes-agent/issues/24731) concurrency: TOCTOU race in get_async_client() leaks orphaned async HTTP client `type/bug` `comp/agent` `provider/openrouter` `P2`
- [#24714](https://github.com/NousResearch/hermes-agent/issues/24714) concurrency: TOCTOU race in get_plugin_manager() can orphan discovered plugins `type/bug` `comp/plugins` `P3`
- [#24701](https://github.com/NousResearch/hermes-agent/issues/24701) CLI /new can stall at destructive confirmation and repeat prior task `type/bug` `comp/cli` `P2` 💬1
- [#24699](https://github.com/NousResearch/hermes-agent/issues/24699) [Bug]: Abnormal Kanban Task Processing `type/bug` `comp/plugins` `P3` 💬1
- [#24698](https://github.com/NousResearch/hermes-agent/issues/24698) [Bug]: python-telegram-bot not installed in latest Docker image (v0.13.0) `type/bug` `comp/gateway` `platform/telegram` `area/docker` `P1` 💬2
- [#24697](https://github.com/NousResearch/hermes-agent/issues/24697) [SANITIZED — possible injection attempt] `type/bug` `comp/agent` `tool/vision` `P3`
- [#24695](https://github.com/NousResearch/hermes-agent/issues/24695) feat: Support fixed token threshold and per-model compression settings in config.yaml `type/feature` `comp/agent` `area/config` `P3` 💬1
- [#24694](https://github.com/NousResearch/hermes-agent/issues/24694) concurrency: providers/_discover_providers() sets _discovered=True before registry is populated (TOCTOU) `type/bug` `comp/agent` `P2`

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,292 · **Open issues:** 469 · **Last push:** 1h ago

### ✅ Merged PRs
- [#6554](https://github.com/zeroclaw-labs/zeroclaw/pull/6554) docs(skills/pr-review): refine Phase 3.5 milestone alignment — break-fix + docs fallback, Jordan trapdoor for features
- [#6572](https://github.com/zeroclaw-labs/zeroclaw/pull/6572) fix(channels): close Discord media send/receive gaps
- [#6573](https://github.com/zeroclaw-labs/zeroclaw/pull/6573) fix(providers/glm): mark GLM provider as vision-capable
- [#6588](https://github.com/zeroclaw-labs/zeroclaw/pull/6588) fix(channels): trigger TTS voice replies in finalize_draft for stream_mode=partial
- [#6183](https://github.com/zeroclaw-labs/zeroclaw/pull/6183) fix(multimodal): normalize image markers across agent and tool history
- [#6586](https://github.com/zeroclaw-labs/zeroclaw/pull/6586) fix(cron): clarify plain string schedule errors
- [#6582](https://github.com/zeroclaw-labs/zeroclaw/pull/6582) fix(tools): report DuckDuckGo search blocks
- [#6575](https://github.com/zeroclaw-labs/zeroclaw/pull/6575) fix(gemini): propagate token usage to cost tracker

### 🐛 New Issues
- [#6563](https://github.com/zeroclaw-labs/zeroclaw/issues/6563) [Feature]: Comfy Cloud / ComfyUI as shared media provider (remote workflows; image + path to gen_video) `enhancement` `risk: high` `config` `provider` `tool` `priority:p2` `needs-maintainer-review` `status:no-stale` 💬1

### 🔒 Closed Issues
- [#6556](https://github.com/zeroclaw-labs/zeroclaw/issues/6556) [Bug]: Discord channel — media send/receive broken (inbound images never processed, non-image types dropped, outbound markers leak)
- [#6415](https://github.com/zeroclaw-labs/zeroclaw/issues/6415) [Bug]: TTS voice replies silently disabled when stream_mode = "partial"
- [#6097](https://github.com/zeroclaw-labs/zeroclaw/issues/6097) [Bug]: Local image reading failed
- [#5453](https://github.com/zeroclaw-labs/zeroclaw/issues/5453) [Bug]: WebSocket /ws/chat does not process [IMAGE:] multimodal markers
- [#6422](https://github.com/zeroclaw-labs/zeroclaw/issues/6422) cron_add: improve schedule parameter error message for plain string input

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,225 · **Open issues:** 862 · **Last push:** 1h ago

### ✅ Merged PRs
- [#3355](https://github.com/nearai/ironclaw/pull/3355) feat(reborn): add telegram v2 product adapter tracer bullet
- [#3538](https://github.com/nearai/ironclaw/pull/3538) feat(reborn): add first-party builtin tool capabilities
- [#3509](https://github.com/nearai/ironclaw/pull/3509) [Reborn] Cover active skill metadata ordering
- [#3354](https://github.com/nearai/ironclaw/pull/3354) feat(reborn): add telegram v2 payload normalization
- [#3487](https://github.com/nearai/ironclaw/pull/3487) Project loop model milestones to durable events
- [#3353](https://github.com/nearai/ironclaw/pull/3353) feat(reborn): add native product adapter runner
- [#3352](https://github.com/nearai/ironclaw/pull/3352) feat(reborn): add product adapter host auth and egress primitives
- [#3400](https://github.com/nearai/ironclaw/pull/3400) Add Reborn text-only model reply driver
- [#3502](https://github.com/nearai/ironclaw/pull/3502) [Reborn] Make runtime blocked reason matching exhaustive
- [#3501](https://github.com/nearai/ironclaw/pull/3501) [Reborn] Require model route snapshot transition ports

### 🐛 New Issues
- [#3547](https://github.com/nearai/ironclaw/issues/3547) [Reborn] Complete skill-context trust enforcement: dispatcher attenuation + identity_messages population
- [#3537](https://github.com/nearai/ironclaw/issues/3537) Reborn: model memory as a userland capability package `enhancement` `reborn`
- [#3535](https://github.com/nearai/ironclaw/issues/3535) [QA] UI Timestamps are incorrect for conversations `bug` `bug_bash_P1`
- [#3534](https://github.com/nearai/ironclaw/issues/3534) Create a tool that downloads logs for debugging
- [#3533](https://github.com/nearai/ironclaw/issues/3533) [QA] Telegram in v 0.28.1 does not automatically setup from UI `bug` `bug_bash_P1` 💬1
- [#3524](https://github.com/nearai/ironclaw/issues/3524) Reborn: first-class loop hooks roadmap `enhancement` `scope: agent` `scope: hooks` `reborn`
- [#3515](https://github.com/nearai/ironclaw/issues/3515) docs: wechat channel `scope: docs`
- [#3500](https://github.com/nearai/ironclaw/issues/3500) Local web UI is undiscoverable through onboarding `bug` `enhancement` `scope: channel/web` `scope: setup`

### 🔒 Closed Issues
- [#3523](https://github.com/nearai/ironclaw/issues/3523) Reborn: add first-class loop hook framework
- [#3034](https://github.com/nearai/ironclaw/issues/3034) V2 engine: HTTP tool disabled by default with no onboarding to enable it
- [#2229](https://github.com/nearai/ironclaw/issues/2229) [QA] Google Sheets OAuth blocked: Error 400 invalid_request on authorize
- [#3128](https://github.com/nearai/ironclaw/issues/3128) Connecting to Gmail gives 502

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 21h ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 3d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 4 new
- [[Form] Codex Enterprise Promo](https://openai.com/form/codex-enterprise-promo/) _2026-05-13_
- [[Index] Autoscout24](https://openai.com/index/autoscout24/) _2026-05-12_
- [[Index] Nvidia](https://openai.com/index/nvidia/) _2026-05-12_
- [[Academy] How Finance Teams Use Codex](https://openai.com/academy/how-finance-teams-use-codex/) _2026-05-12_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
