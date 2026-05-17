---
layout: post
title: "Ecosystem Digest — 2026-05-17"
date: 2026-05-17 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-17
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 372,461 | 11 | 10 | 10 | 3 |
| **hermesagent** | 153,505 | 5 | 2 | 9 | 1 |
| **ZeroClaw** | 31,385 | 14 | 8 | 9 | 0 |
| **IronClaw** | 12,268 | 8 | 1 | 8 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 372,461 · **Open issues:** 6,935 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.16-beta.3](https://github.com/openclaw/openclaw/releases/tag/v2026.5.16-beta.3) — openclaw 2026.5.16-beta.3
- [v2026.5.16-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.5.16-beta.2) — openclaw 2026.5.16-beta.2
- [v2026.5.16-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.5.16-beta.1) — openclaw 2026.5.16-beta.1

### ✅ Merged PRs
- [#82819](https://github.com/openclaw/openclaw/pull/82819) fix(cli): resolve web command SecretRefs
- [#82671](https://github.com/openclaw/openclaw/pull/82671) fix(plugins): harden bundled runtime path resolution
- [#82750](https://github.com/openclaw/openclaw/pull/82750) fix(agents): normalize Copilot replay tool IDs
- [#82820](https://github.com/openclaw/openclaw/pull/82820) fix(telegram): keep streamed text when tts arrives
- [#82789](https://github.com/openclaw/openclaw/pull/82789) feat: add fal and OpenRouter music generation
- [#82816](https://github.com/openclaw/openclaw/pull/82816) fix(codex): guard post-tool raw assistant terminal gaps
- [#82770](https://github.com/openclaw/openclaw/pull/82770) fix(memory): abort timed-out embedding requests
- [#82410](https://github.com/openclaw/openclaw/pull/82410) fix: preserve reasoning_content replay from thinking blocks in anthropic-messages transport
- [#82798](https://github.com/openclaw/openclaw/pull/82798) Fix infer SecretRef resolution for provider-backed commands
- [#82814](https://github.com/openclaw/openclaw/pull/82814) fix: reuse plugin manifest metadata safely

### 🐛 New Issues
- [#82837](https://github.com/openclaw/openclaw/issues/82837) [Bug]: Image tool and infer image describe fail with "chat content is empty" error - MiniMax image understanding broken `bug` `regression`
- [#82833](https://github.com/openclaw/openclaw/issues/82833) [Regression]: `message` tool not exposed to weixin agent despite being in `alsoAllow` since 2026.5.16-beta.3 `bug` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` 💬1
- [#82830](https://github.com/openclaw/openclaw/issues/82830) MCP stdio server processes leak on Windows - old processes never terminated 💬1
- [#82829](https://github.com/openclaw/openclaw/issues/82829) Telegram Topic messages silently dropped due to `deliver` callback indentation bug in `bot-*.js` 💬1
- [#82827](https://github.com/openclaw/openclaw/issues/82827) [Bug]:  Signal group auto-replies broken again in v2026.5.12 because Signal group IDs are lowercased `bug` `regression` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` 💬1
- [#82826](https://github.com/openclaw/openclaw/issues/82826) MiMo provider: All models fail 400 "Param Incorrect (format)" — direct curl works, Gateway fails `P2` `clawsweeper:needs-live-repro` 💬1
- [#82813](https://github.com/openclaw/openclaw/issues/82813) Discord channel silently disabled after 2026.4.x → 2026.5.x upgrade (externalised plugin not auto-installed) `P1` `clawsweeper:needs-live-repro` 💬1
- [#82811](https://github.com/openclaw/openclaw/issues/82811) Cron job Memory Dreaming Promotion stalled at runtime-plugins after OpenClaw 2026.5.12 upgrade `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` 💬1
- [#82809](https://github.com/openclaw/openclaw/issues/82809) Test issue from OpenClaw 💬1
- [#82807](https://github.com/openclaw/openclaw/issues/82807) [Bug] Discord: long text messages fail to send in openclaw 2026.5.16-beta.3 `bug` `P1` `clawsweeper:needs-live-repro` 💬1
- [#82803](https://github.com/openclaw/openclaw/issues/82803) [Bug]: Subagent completion direct announce fails with no visible reply `bug` `maintainer` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` 💬1

### 🔒 Closed Issues
- [#82835](https://github.com/openclaw/openclaw/issues/82835) [SANITIZED — possible injection attempt]
- [#82812](https://github.com/openclaw/openclaw/issues/82812) bug: per-turn dynamic context bleeds into extraSystemPromptHash, triggering false cli session reset + A-type empty output
- [#82621](https://github.com/openclaw/openclaw/issues/82621) Bug: CLI web search does not resolve plugin-scoped webSearch SecretRefs
- [#49086](https://github.com/openclaw/openclaw/issues/49086) [Bug/Template]: LLM hallucinates Unix timestamps when writing heartbeat-state.json — causes skipped or over-triggered checks
- [#75797](https://github.com/openclaw/openclaw/issues/75797) [v29] Google secrets reloader crash-loop: Unable to open bundled plugin public surface google/web-search-contract-api.js
- [#78462](https://github.com/openclaw/openclaw/issues/78462) Bundled persistedAuthState probes prefer source auth-presence modules in dev checkout
- [#82749](https://github.com/openclaw/openclaw/issues/82749) [Bug]: Provider switch replays overlong historical tool IDs into GitHub Copilot
- [#82399](https://github.com/openclaw/openclaw/issues/82399) [Bug]: Version 5.12 does not support the use of local network large models.
- [#48082](https://github.com/openclaw/openclaw/issues/48082) [Bug]: exec tool SIGSEGV on Feiniu NAS (custom kernel 6.12.18-trim) /exec 工具在飞牛 NAS 上崩溃 (SIGSEGV，定制内核 6.12.18-trim)
- [#80611](https://github.com/openclaw/openclaw/issues/80611) Non-deep `openclaw status` repeatedly loads plugin metadata and takes ~20s on 2026.5.7

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 153,505 · **Open issues:** 11,713 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.16](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.5.16) — Hermes Agent v0.14.0 (2026.5.16)

### ✅ Merged PRs
- [#27189](https://github.com/NousResearch/hermes-agent/pull/27189) fix(compressor): strip historical media after compression (salvage of #19951)
- [#27184](https://github.com/NousResearch/hermes-agent/pull/27184) fix(xai): surface provider 'error' SSE frame in Codex fallback stream
- [#27185](https://github.com/NousResearch/hermes-agent/pull/27185) fix(agent): reset _fallback_index at turn start even when no fallback activated
- [#27187](https://github.com/NousResearch/hermes-agent/pull/27187) fix(plugins): surface category-namespaced plugins in `hermes plugins list`; drop dead Langfuse path
- [#27188](https://github.com/NousResearch/hermes-agent/pull/27188) feat(cli): add `hermes send` to pipe script output to any messaging platform (salvage of #19631)
- [#27175](https://github.com/NousResearch/hermes-agent/pull/27175) feat(cli): show ▶ N indicator in status bar for running /background tasks
- [#27176](https://github.com/NousResearch/hermes-agent/pull/27176) feat(status): append session recap to /status output (salvage of #18587)
- [#27151](https://github.com/NousResearch/hermes-agent/pull/27151) fix(telegram): restore DM topic typing indicator
- [#27162](https://github.com/NousResearch/hermes-agent/pull/27162) fix(codex): rotate pool on usage_limit_reached 429

### 🐛 New Issues
- [#27221](https://github.com/NousResearch/hermes-agent/issues/27221) [Bug]: entrypoint.sh misses chown for ui-tui/ and gateway/ when HERMES_UID is remapped `type/bug` `comp/tui` `area/docker` `P2` 💬2
- [#27206](https://github.com/NousResearch/hermes-agent/issues/27206) feat(gateway): plugin hook for /stop interrupt — agent_loop_stopped `type/feature` `comp/gateway` `comp/plugins` `P3` 💬1
- [#27198](https://github.com/NousResearch/hermes-agent/issues/27198) [Bug]: WhatsApp messages stuck at 1 tick — delivery ACK missing in addition to read receipts `type/bug` `platform/whatsapp` `P2` 💬2
- [#27197](https://github.com/NousResearch/hermes-agent/issues/27197) [Bug]: xAI Grok (xai-oauth) returns HTTP 400 or streaming fallback errors on Responses API `type/bug` `comp/agent` `provider/xai` `P3` 💬3
- [#27192](https://github.com/NousResearch/hermes-agent/issues/27192) Build action-oriented replay dashboard pages `type/feature` `comp/tui` `P3` 💬2

### 🔒 Closed Issues
- [#933](https://github.com/NousResearch/hermes-agent/issues/933) Feature Request: Support multiple OAuth tokens with automatic fallback
- [#20465](https://github.com/NousResearch/hermes-agent/issues/20465) [Bug] Interactive CLI session does not auto-fallback on Codex 429 'usage_limit_reached', while cron jobs with the same fallback chain do

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,385 · **Open issues:** 476 · **Last push:** <1h ago

### ✅ Merged PRs
- [#6447](https://github.com/zeroclaw-labs/zeroclaw/pull/6447) Update github actions
- [#6624](https://github.com/zeroclaw-labs/zeroclaw/pull/6624) fix(providers/compatible): normalize image markers at provider boundary (#6399)
- [#6671](https://github.com/zeroclaw-labs/zeroclaw/pull/6671) fix(gateway): publish session notifications
- [#6674](https://github.com/zeroclaw-labs/zeroclaw/pull/6674) feat(skills): localize install output with Fluent
- [#6676](https://github.com/zeroclaw-labs/zeroclaw/pull/6676) feat(skills): suggest missing skill capabilities
- [#6668](https://github.com/zeroclaw-labs/zeroclaw/pull/6668) fix(provider): recover Codex non-streaming fallback
- [#6396](https://github.com/zeroclaw-labs/zeroclaw/pull/6396) feat(ci): force check pr title
- [#6287](https://github.com/zeroclaw-labs/zeroclaw/pull/6287) fix(config/channels/slack): make bot_token optional and load from env at startup
- [#6236](https://github.com/zeroclaw-labs/zeroclaw/pull/6236) fix(security): allow safe device redirect targets in path policy

### 🐛 New Issues
- [#6729](https://github.com/zeroclaw-labs/zeroclaw/issues/6729) [Feature]: Agent capability flags for shared/ access and workspace escape `enhancement` `risk: low` `config` `security`
- [#6724](https://github.com/zeroclaw-labs/zeroclaw/issues/6724) Channels supervisor crashloops when all configured channels have enabled=false
- [#6723](https://github.com/zeroclaw-labs/zeroclaw/issues/6723) Native OpenAI provider hardcodes 120s request timeout, silently ignores timeout_secs config
- [#6722](https://github.com/zeroclaw-labs/zeroclaw/issues/6722) MemoryConfig.rerank_enabled / rerank_threshold scaffolded but no consumer
- [#6721](https://github.com/zeroclaw-labs/zeroclaw/issues/6721) tool_search not in default_auto_approve → deferred_loading+webhook silently hangs 120s then auto-denies
- [#6720](https://github.com/zeroclaw-labs/zeroclaw/issues/6720) [agent] context_aware_tools config field is declared but unread (dead code)
- [#6715](https://github.com/zeroclaw-labs/zeroclaw/issues/6715) [Feature]: Delete unneeded branches from main zeroclaw-labs/zeroclaw repository `enhancement`
- [#6714](https://github.com/zeroclaw-labs/zeroclaw/issues/6714) [Feature]: Remove remote-markdown-link block from skill audit
- [#6708](https://github.com/zeroclaw-labs/zeroclaw/issues/6708) bug(provider): avoid expect_err panic in Codex UTF-8 stream cleanup `bug` `risk: medium` `provider` `provider:openai` `priority:p2` `status:accepted` `status:no-stale`
- [#6705](https://github.com/zeroclaw-labs/zeroclaw/issues/6705) [SANITIZED — possible injection attempt] `bug` `risk: high` `cron` `runtime` `tool` `cron:scheduler` `priority:p1` `tool:cron` `status:accepted` `status:no-stale`
- [#6704](https://github.com/zeroclaw-labs/zeroclaw/issues/6704) [Bug]: Shell tool output is garbled on Windows with non-UTF-8 console code pages `bug` `risk: high` `runtime` `tool` `priority:p1` `tool:shell` `status:accepted` `status:no-stale`
- [#6703](https://github.com/zeroclaw-labs/zeroclaw/issues/6703) [Feature]: Allow configuring smtp credential separately from imap `enhancement` `risk: medium` `channel` `config` `priority:p2` `channel:email` `status:in-progress` `status:no-stale`
- [#6702](https://github.com/zeroclaw-labs/zeroclaw/issues/6702) [Bug]: Dashboard assistant bubble accumulates blank lines for each tool-call card `bug` `risk: low` `gateway` `status:accepted` `status:no-stale` `priority:p3`
- [#6699](https://github.com/zeroclaw-labs/zeroclaw/issues/6699) tool_filter_groups is a no-op for real MCP tools (prefix-check bug) + no integration with deferred_loading `bug` `risk: high` `agent` `config` `runtime` `tool` `priority:p1` `tool:mcp` `status:accepted` `status:no-stale`

### 🔒 Closed Issues
- [#6132](https://github.com/zeroclaw-labs/zeroclaw/issues/6132) audit(#5972 follow-up): extend manifest prompt audit to scan [skill].prompts after #5972 merges
- [#3542](https://github.com/zeroclaw-labs/zeroclaw/issues/3542) [Feature]: I hope the webhook endpoint can support agent mode so that it can trigger full agent workflows and tool execution.
- [#6399](https://github.com/zeroclaw-labs/zeroclaw/issues/6399) [Bug]: Custom remote provider sends local image file paths instead of data URLs, breaking multimodal requests
- [#6659](https://github.com/zeroclaw-labs/zeroclaw/issues/6659) No API for pushing notifications into an operator's gateway session (zeroclaw 0.7.4)
- [#6123](https://github.com/zeroclaw-labs/zeroclaw/issues/6123) [Bug]: default_model issue on fresh install
- [#6670](https://github.com/zeroclaw-labs/zeroclaw/issues/6670) [Feature]: Localize skills install output and tier banner with Fluent
- [#6394](https://github.com/zeroclaw-labs/zeroclaw/issues/6394) [Feature]: GitHub action that checks for PR's title
- [#6237](https://github.com/zeroclaw-labs/zeroclaw/issues/6237) [Bug]: slack bot_token must be stored in the configuration file instead of taken from environment variable

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,268 · **Open issues:** 925 · **Last push:** <1h ago

### ✅ Merged PRs
- [#3710](https://github.com/nearai/ironclaw/pull/3710) test(reborn): add product-live planned AgentLoop harness
- [#3688](https://github.com/nearai/ironclaw/pull/3688) refactor(reborn): project ProductAdapter from single ExtensionManifestV2
- [#3712](https://github.com/nearai/ironclaw/pull/3712) fix(reborn): trust result refs with durable replies
- [#3709](https://github.com/nearai/ironclaw/pull/3709) docs(api): document the Responses API end-to-end
- [#3122](https://github.com/nearai/ironclaw/pull/3122) feat(web): support externally-provided tools in Responses API
- [#3588](https://github.com/nearai/ironclaw/pull/3588) feat(gateway): add logs download button
- [#3691](https://github.com/nearai/ironclaw/pull/3691) feat(product-workflow): add WebUI service facade 
- [#3653](https://github.com/nearai/ironclaw/pull/3653) arch(ws-17): prove product live planned-runtime cutover

### 🐛 New Issues
- [#3702](https://github.com/nearai/ironclaw/issues/3702) Reborn: revise and implement binary-E2E test framework plan
- [#3701](https://github.com/nearai/ironclaw/issues/3701) v0.28.2 macOS prebuilt: gateway never binds despite config + doctor reporting it enabled
- [#3700](https://github.com/nearai/ironclaw/issues/3700) [Deferred] Reborn: route web chat send through product-live workflow 💬1
- [#3699](https://github.com/nearai/ironclaw/issues/3699) [Deferred] Reborn: roll product-live workflow to CLI, Telegram, and webhooks 💬1
- [#3698](https://github.com/nearai/ironclaw/issues/3698) Reborn: build test/dry-run product-live runtime harness 💬2
- [#3697](https://github.com/nearai/ironclaw/issues/3697) [Deferred] Reborn: project live turn milestones into web AppEvents 💬1
- [#3696](https://github.com/nearai/ironclaw/issues/3696) Reborn: wire planned run-profile resolver into production composition factories
- [#3692](https://github.com/nearai/ironclaw/issues/3692) Reborn: add policy-gated personal identity and heartbeat prompt context 💬4

### 🔒 Closed Issues
- [#3534](https://github.com/nearai/ironclaw/issues/3534) Create a tool that downloads logs for debugging

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 13h ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬2 · 1d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 4d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 4 new
- [[Index] Malta Chatgpt Plus Partnership](https://openai.com/index/malta-chatgpt-plus-partnership/) _2026-05-16_
- [[Codex-For-Work] How Business Operations Teams Use Codex](https://openai.com/academy/codex-for-work/how-business-operations-teams-use-codex/) _2026-05-16_
- [[Codex-For-Work] How Data Science Teams Use Codex](https://openai.com/academy/codex-for-work/how-data-science-teams-use-codex/) _2026-05-16_
- [[Codex-For-Work] How Sales Teams Use Codex](https://openai.com/academy/codex-for-work/how-sales-teams-use-codex/) _2026-05-16_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
