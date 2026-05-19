---
layout: post
title: "Ecosystem Digest — 2026-05-19"
date: 2026-05-19 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-19
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 372,985 | 11 | 6 | 10 | 4 |
| **hermesagent** | 156,550 | 12 | 0 | 4 | 0 |
| **ZeroClaw** | 31,430 | 7 | 8 | 10 | 0 |
| **IronClaw** | 12,288 | 12 | 2 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 372,985 · **Open issues:** 7,064 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.19-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.5.19-beta.1) — openclaw 2026.5.19-beta.1
- [v2026.5.18](https://github.com/openclaw/openclaw/releases/tag/v2026.5.18) — openclaw 2026.5.18
- [v2026.5.18-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.5.18-beta.1) — openclaw 2026.5.18-beta.1
- [v2026.5.16-beta.7](https://github.com/openclaw/openclaw/releases/tag/v2026.5.16-beta.7) — openclaw 2026.5.16-beta.7

### ✅ Merged PRs
- [#83827](https://github.com/openclaw/openclaw/pull/83827) Preserve queued Telegram topic followups
- [#83807](https://github.com/openclaw/openclaw/pull/83807) fix(codex): guard against stale codex app snapshots leading to plugin invocation failure
- [#83323](https://github.com/openclaw/openclaw/pull/83323) fix(migrate): use resolved provider for options
- [#83848](https://github.com/openclaw/openclaw/pull/83848) fix(deepseek): normalize mcp union tool schemas
- [#83829](https://github.com/openclaw/openclaw/pull/83829) Fix Telegram forum topic parallel flow
- [#83260](https://github.com/openclaw/openclaw/pull/83260) Improve Telegram groups config shape diagnostics
- [#83319](https://github.com/openclaw/openclaw/pull/83319) [SANITIZED — possible injection attempt]
- [#83841](https://github.com/openclaw/openclaw/pull/83841) Fix memory plugin CLI help dispatch
- [#83813](https://github.com/openclaw/openclaw/pull/83813) codex: surface deferred dynamic tool names
- [#83828](https://github.com/openclaw/openclaw/pull/83828) fix(cli): include loopback tools in cli prompts

### 🐛 New Issues
- [#83864](https://github.com/openclaw/openclaw/issues/83864) gateway config.patch fails for agents.defaults.model.primary despite parent path being allowlisted `P2` `impact:auth-provider` 💬1
- [#83863](https://github.com/openclaw/openclaw/issues/83863) ACP/Codex child tasks can be marked succeeded with progress-only output and no final deliverable 💬2
- [#83859](https://github.com/openclaw/openclaw/issues/83859) [Bug]: xAI TTS works with --gateway but times out in local execution `bug` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬1
- [#83857](https://github.com/openclaw/openclaw/issues/83857) [Bug]: xAI image generation and TTS work via infer but not through Crestodian REPL `bug` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` 💬1
- [#83856](https://github.com/openclaw/openclaw/issues/83856) Unbounded pagination loop in loadCronJobForShow can hang indefinitely `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:crash-loop` `issue-rating: 🦞 diamond lobster` 💬1
- [#83855](https://github.com/openclaw/openclaw/issues/83855) Rejected promise cached permanently in getConfigSnapshot `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` 💬1
- [#83853](https://github.com/openclaw/openclaw/issues/83853) addUserForToken failure swallowed — RefreshingAuthProvider returned without a bound user `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#83852](https://github.com/openclaw/openclaw/issues/83852) [Bug]: Codex-native subagent completes as BLOCKED but remains running when native hook relay is unavailable `bug` `regression` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬2
- [#83851](https://github.com/openclaw/openclaw/issues/83851) config patch should return deterministic reload/apply status `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` 💬1
- [#83837](https://github.com/openclaw/openclaw/issues/83837) [Bug]: Small Local Ollama Models Respond with "NO" `bug` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:message-loss` `impact:auth-provider` `issue-rating: 🦪 silver shellfish` 💬1
- [#83836](https://github.com/openclaw/openclaw/issues/83836) Codex replay can silently fail Telegram turns with invalid_encrypted_content from mirrored thinking blocks `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬2

### 🔒 Closed Issues
- [#83861](https://github.com/openclaw/openclaw/issues/83861) Codex progress drafts not activating on Mattermost despite correct config and shipped code (v2026.5.18)
- [#83361](https://github.com/openclaw/openclaw/issues/83361) MCP server anyOf schemas rejected by DeepSeek - should strip at gateway level
- [#83285](https://github.com/openclaw/openclaw/issues/83285) [Bug]: migrate Codex provider options are dropped when provider defaults to codex
- [#83083](https://github.com/openclaw/openclaw/issues/83083) Telegram groups config shape error needs actionable startup/doctor guidance
- [#83854](https://github.com/openclaw/openclaw/issues/83854) No test coverage for security-sensitive restart-script generation
- [#83745](https://github.com/openclaw/openclaw/issues/83745) [Bug]: documented openclaw memory CLI is listed but dispatch rejects it as unknown command

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 156,550 · **Open issues:** 12,216 · **Last push:** <1h ago

### ✅ Merged PRs
- [#28287](https://github.com/NousResearch/hermes-agent/pull/28287) feat(skills): add baoyu-article-illustrator skill
- [#28169](https://github.com/NousResearch/hermes-agent/pull/28169) feat(install.ps1): strip BOM, add -Commit/-Tag pin params, harden git ops
- [#23854](https://github.com/NousResearch/hermes-agent/pull/23854) feat(cli): add /update slash command to CLI and TUI
- [#28221](https://github.com/NousResearch/hermes-agent/pull/28221) [SANITIZED — possible injection attempt]

### 🐛 New Issues
- [#28300](https://github.com/NousResearch/hermes-agent/issues/28300) Modal terminal backend: blocking Modal API called from a running event loop → "Task was destroyed but it is pending" / "no running event loop" `type/bug` `backend/modal` `comp/agent` `tool/terminal` `P2`
- [#28299](https://github.com/NousResearch/hermes-agent/issues/28299) Daytona terminal backend: all sandboxes named "hermes-default" → DaytonaConflictError on concurrent use `type/bug` `backend/daytona` `tool/terminal` `P2`
- [#28296](https://github.com/NousResearch/hermes-agent/issues/28296) OpenVikingMemoryProvider missing on_session_switch — session ID goes stale after /new `type/bug` `comp/plugins` `tool/memory` `P3`
- [#28293](https://github.com/NousResearch/hermes-agent/issues/28293) fix(gateway): WeCom gateway CPU spin when WebSocket enters CLOSING state `type/bug` `comp/gateway` `platform/wecom` `P2` 💬1
- [#28292](https://github.com/NousResearch/hermes-agent/issues/28292) [Bug]: profile import creates a wrapper that does not preserve a custom HERMES_HOME `type/bug` `comp/cli` `area/config` `P3`
- [#28291](https://github.com/NousResearch/hermes-agent/issues/28291) Bug: moonshot_schema._fill_missing_type crashes on JSON Schema union types (list type) `type/bug` `comp/agent` `P2`
- [#28290](https://github.com/NousResearch/hermes-agent/issues/28290) feat: inject temporal context markers for intra-session time awareness `type/feature` `comp/agent` `P3` 💬1
- [#28289](https://github.com/NousResearch/hermes-agent/issues/28289) [Feature]: There is no fact-checking process or evidence display `type/feature` `comp/agent` `P3`
- [#28285](https://github.com/NousResearch/hermes-agent/issues/28285) Bug: Kanban 数据库连接泄漏导致 Gateway 调度器崩溃 `type/bug` `comp/gateway` `comp/cron` `P1` 💬1
- [#28284](https://github.com/NousResearch/hermes-agent/issues/28284) Test: Issue from CLI `invalid`
- [#28283](https://github.com/NousResearch/hermes-agent/issues/28283) Surface `pinPeerName` in `hermes memory setup` wizard for multi-instance Honcho setups `type/feature` `comp/cli` `comp/plugins` `area/config` `P3`
- [#28279](https://github.com/NousResearch/hermes-agent/issues/28279) Feature: Per-Chat Memory Isolation (Scoped Memory) `type/feature` `comp/agent` `tool/memory` `P3` 💬1

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,430 · **Open issues:** 468 · **Last push:** <1h ago

### ✅ Merged PRs
- [#6749](https://github.com/zeroclaw-labs/zeroclaw/pull/6749) ci: expand manual cross-platform build matrix coverage
- [#6750](https://github.com/zeroclaw-labs/zeroclaw/pull/6750) fix: Windows snapshot TTL is shorter than the polling interval
- [#6758](https://github.com/zeroclaw-labs/zeroclaw/pull/6758) feat(providers): split MiniMax picker into Global and China entries
- [#6757](https://github.com/zeroclaw-labs/zeroclaw/pull/6757) fix(observability): scope gateway broadcast hook lifetime
- [#6743](https://github.com/zeroclaw-labs/zeroclaw/pull/6743) fix(providers): skip unresolvable multimodal images
- [#6744](https://github.com/zeroclaw-labs/zeroclaw/pull/6744) test(providers): cover streaming payload tracing
- [#6616](https://github.com/zeroclaw-labs/zeroclaw/pull/6616) test(tools): cover Tavily search routing aliases
- [#6682](https://github.com/zeroclaw-labs/zeroclaw/pull/6682) fix(skills): run ClawHub install on the async runtime
- [#6445](https://github.com/zeroclaw-labs/zeroclaw/pull/6445) feat(providers): add GitHub Models as a model provider
- [#6209](https://github.com/zeroclaw-labs/zeroclaw/pull/6209) fix(skills): strict SkillMeta + relocate SkillForge provenance to [forge] (#6128, #6210)

### 🐛 New Issues
- [#6760](https://github.com/zeroclaw-labs/zeroclaw/issues/6760) [Feature]: Update Documentation for Docker - Tested v0.7.5-debian `enhancement` `type: docs` `risk: low` `docs` `priority:p3` 💬1
- [#6756](https://github.com/zeroclaw-labs/zeroclaw/issues/6756) models list: custom provider fails because doctor path never reads stored api_key from config `bug` `risk: high` `config` `doctor` `provider` `runtime` `provider:compatible` `priority:p2`
- [#6754](https://github.com/zeroclaw-labs/zeroclaw/issues/6754) [Feature]: ACP bridge auto-pairing should not depend on a one-time-use code `enhancement` `risk: high` `config` `gateway` `security` `security:pairing` `gateway:local_bridge` `priority:p2` `status:accepted`
- [#6751](https://github.com/zeroclaw-labs/zeroclaw/issues/6751) fix(ci): pr-title workflow has never run — startup_failure on every PR since #6396 `bug` `ci` `risk: high` `priority:p2` `status:in-progress` `status:no-stale`
- [#6729](https://github.com/zeroclaw-labs/zeroclaw/issues/6729) [Feature]: Agent capability flags for shared/ access and workspace escape `enhancement` `risk: low` `config` `security` `priority:p2` 💬1
- [#6724](https://github.com/zeroclaw-labs/zeroclaw/issues/6724) Channels supervisor crashloops when all configured channels have enabled=false `bug` `risk: high` `channel` `config` `daemon` `runtime` `priority:p3`
- [#6715](https://github.com/zeroclaw-labs/zeroclaw/issues/6715) [Feature]: Delete unneeded branches from main zeroclaw-labs/zeroclaw repository `enhancement` `risk: medium` `needs-maintainer-review` `priority:p3` 💬1

### 🔒 Closed Issues
- [#6742](https://github.com/zeroclaw-labs/zeroclaw/issues/6742) [Feature]: Add streaming payload tracing tests for --log-llm
- [#6245](https://github.com/zeroclaw-labs/zeroclaw/issues/6245) Tavily search provider is unimplemented (TODO stub only)
- [#6681](https://github.com/zeroclaw-labs/zeroclaw/issues/6681) [Bug]: zeroclaw skills install clawhub:* panics — reqwest::blocking dropped inside #[tokio::main]
- [#6444](https://github.com/zeroclaw-labs/zeroclaw/issues/6444) Add GitHub Models as a model provider
- [#6128](https://github.com/zeroclaw-labs/zeroclaw/issues/6128) skills: add #[serde(deny_unknown_fields)] to SkillMeta to surface silent-drop typos (follow-up to #5972)
- [#6210](https://github.com/zeroclaw-labs/zeroclaw/issues/6210) skills: SkillForge auto-integrator emits non-schema fields inside [skill] block (follow-up to #6128)
- [#6439](https://github.com/zeroclaw-labs/zeroclaw/issues/6439) Add Morph (Fast Apply) as a model provider
- [#6739](https://github.com/zeroclaw-labs/zeroclaw/issues/6739) [Bug]: Cron timezone contract is inconsistent across tools, CLI, and API

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,288 · **Open issues:** 940 · **Last push:** <1h ago

### ✅ Merged PRs
- [#3658](https://github.com/nearai/ironclaw/pull/3658) feat(tui): Ctrl-S downloads logs from the Logs tab
- [#3730](https://github.com/nearai/ironclaw/pull/3730) test(reborn): restack product-live AgentLoop tool harness
- [#3679](https://github.com/nearai/ironclaw/pull/3679) feat(reborn): apply universal FS dispatch across consumer crates
- [#3722](https://github.com/nearai/ironclaw/pull/3722) fix(reborn): preserve provider tool roundtrip metadata
- [#3757](https://github.com/nearai/ironclaw/pull/3757) docs: add crates agent guidance maps
- [#3694](https://github.com/nearai/ironclaw/pull/3694) fix(webui): add send-message idempotency replay guards
- [#3720](https://github.com/nearai/ironclaw/pull/3720) [codex] verify durable tool result refs
- [#3704](https://github.com/nearai/ironclaw/pull/3704) feat(reborn): boot TOML + provider catalog (config.toml + providers.json)
- [#3717](https://github.com/nearai/ironclaw/pull/3717) [codex] Wire planned profile resolver in Reborn composition
- [#3735](https://github.com/nearai/ironclaw/pull/3735) feat(product_workflow): expose get_run_state on RebornServicesApi facade

### 🐛 New Issues
- [#3763](https://github.com/nearai/ironclaw/issues/3763) Per-user / per-tenant tool enable/disable in the web UI `suggested_P2` `customer`
- [#3762](https://github.com/nearai/ironclaw/issues/3762) [SANITIZED — possible injection attempt] `suggested_P1` `customer`
- [#3756](https://github.com/nearai/ironclaw/issues/3756) ANSI coloring causes log string to break
- [#3755](https://github.com/nearai/ironclaw/issues/3755) Workspace embed loop: AuthFailed hint is OpenAI-specific but error can come from NEAR AI / Bedrock too
- [#3754](https://github.com/nearai/ironclaw/issues/3754) OpenAI embeddings: /v1/v1/embeddings double-up when base_url already ends in /v1
- [#3753](https://github.com/nearai/ironclaw/issues/3753) ironclaw doctor: Bedrock embeddings fall through to OPENAI_API_KEY check
- [#3752](https://github.com/nearai/ironclaw/issues/3752) [SANITIZED — possible injection attempt]
- [#3751](https://github.com/nearai/ironclaw/issues/3751) Unknown embedding provider names silently route to OpenAI
- [#3750](https://github.com/nearai/ironclaw/issues/3750) Bedrock embeddings ignore DB/TOML model setting
- [#3748](https://github.com/nearai/ironclaw/issues/3748) Refactor Reborn production builders to route through factory `reborn` 💬1
- [#3745](https://github.com/nearai/ironclaw/issues/3745) Reborn: add owner-aware personal context authorization
- [#3743](https://github.com/nearai/ironclaw/issues/3743) Settings Telegram pairing approval shows duplicate success toasts

### 🔒 Closed Issues
- [#3578](https://github.com/nearai/ironclaw/issues/3578) Define host-owned ingress boundary for Reborn HTTP surfaces
- [#3736](https://github.com/nearai/ironclaw/issues/3736) [Question] v0.28.2 regression: unconfigured providers still show Use button in TEE agents

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 2d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬2 · 3d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 6d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Anthropic Acquires Stainless](https://www.anthropic.com/news/anthropic-acquires-stainless) _2026-05-18_

### OpenAI — 2 new
- [[Form] Codex Project Showcase And Feedback](https://openai.com/form/codex-project-showcase-and-feedback/) _2026-05-18_
- [[Index] Dell Codex Enterprise Partnership](https://openai.com/index/dell-codex-enterprise-partnership/) _2026-05-18_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
