---
layout: post
title: "Ecosystem Digest — 2026-05-12"
date: 2026-05-12 07:51:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-12
*Generated 07:51 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 370,954 | 15 | 7 | 10 | 3 |
| **hermesagent** | 144,990 | 11 | 2 | 6 | 1 |
| **ZeroClaw** | 31,252 | 7 | 7 | 10 | 0 |
| **IronClaw** | 12,216 | 15 | 2 | 10 | 1 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 370,954 · **Open issues:** 7,319 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.10-beta.5](https://github.com/openclaw/openclaw/releases/tag/v2026.5.10-beta.5) — openclaw 2026.5.10-beta.5
- [v2026.5.10-beta.4](https://github.com/openclaw/openclaw/releases/tag/v2026.5.10-beta.4) — openclaw 2026.5.10-beta.4
- [v2026.5.10-beta.3](https://github.com/openclaw/openclaw/releases/tag/v2026.5.10-beta.3) — openclaw 2026.5.10-beta.3

### ✅ Merged PRs
- [#80675](https://github.com/openclaw/openclaw/pull/80675) fix: surface explicit error on LLM idle timeout to prevent ghost turns
- [#80821](https://github.com/openclaw/openclaw/pull/80821) Add message tool delivery hint to inbound context
- [#80822](https://github.com/openclaw/openclaw/pull/80822) fix(onboarding): fix onboarding hangs instead of exiting
- [#80816](https://github.com/openclaw/openclaw/pull/80816) fix(onboarding): treat already-installed codex as success, update in place
- [#68839](https://github.com/openclaw/openclaw/pull/68839) fix(auto-reply): guard FOLLOWUP_QUEUES delete against late drain finally
- [#80798](https://github.com/openclaw/openclaw/pull/80798) feat(onboarding): featured provider tier in interactive picker
- [#68848](https://github.com/openclaw/openclaw/pull/68848) fix(gateway): clear nodeWakeById on no-registration early-return
- [#78243](https://github.com/openclaw/openclaw/pull/78243) fix(cron): mark active-jobs on manual-run path to suppress transient lost marker
- [#80792](https://github.com/openclaw/openclaw/pull/80792) fix(codex): default plugin destructive actions on
- [#80803](https://github.com/openclaw/openclaw/pull/80803) test: stabilize core fast tests

### 🐛 New Issues
- [#80847](https://github.com/openclaw/openclaw/issues/80847) bug(plugins): plugin tools intermittently unavailable in sub-agent sessions despite contracts.tools and compiled dist (regression from #56208) `bug` `regression` 💬1
- [#80846](https://github.com/openclaw/openclaw/issues/80846) Telegram /reasoning stream not showing character-by-character (regression in v2026.5.7) 💬1
- [#80844](https://github.com/openclaw/openclaw/issues/80844) Critical npm audit advisory via @mistralai/mistralai in openclaw 2026.5.7 💬1
- [#80843](https://github.com/openclaw/openclaw/issues/80843) Feature: add web_search provider fallback chain for quota and network failures 💬1
- [#80841](https://github.com/openclaw/openclaw/issues/80841) voice-call: support Twilio AMD on outbound + dynamic mode switch when machine detected 💬1
- [#80840](https://github.com/openclaw/openclaw/issues/80840) voice-call: realtime.tools[] entries advertised to model but no handler bind path 💬1
- [#80836](https://github.com/openclaw/openclaw/issues/80836) RFE: gateway.auth.tokenScopes config field for headless/single-tenant deployments 💬1
- [#80835](https://github.com/openclaw/openclaw/issues/80835) Bug: message tool's after/oldest parameter silently returns [] for ISO 8601 timestamps 💬1
- [#80828](https://github.com/openclaw/openclaw/issues/80828) Title: [Feature Request] Social-Identity MFA: WhatsApp/Messaging-based Authentication Handshake `enhancement` 💬1
- [#80820](https://github.com/openclaw/openclaw/issues/80820) [Bug]: Gateway event loop stalls 8–12s every ~30 minutes at idle — active=0, waiting=0, queued=0 `bug` 💬1
- [#80819](https://github.com/openclaw/openclaw/issues/80819) [Bug]: Claude CLI live-session bridge ignores `control_request` (`can_use_tool`) — sessions stall until 180/600s timeout — reproduces on `2026.5.3-1` 💬1
- [#80817](https://github.com/openclaw/openclaw/issues/80817) [Bug]: `openclaw doctor` (without `--fix`) emits `◇  Doctor changes: Removed agents.defaults.agentRuntime` in past tense even when nothing was changed — reproduces on `v2026.5.10-beta.1` `bug` `bug:behavior` 💬3
- [#80814](https://github.com/openclaw/openclaw/issues/80814) codex (app-server) runtime drops openclaw.json mcp.servers — only codex-cli bridges them 💬1
- [#80809](https://github.com/openclaw/openclaw/issues/80809) MiniMax-M2.7-highspeed returns no text / incomplete terminal response in OpenClaw 2026.5.7 💬1
- [#80806](https://github.com/openclaw/openclaw/issues/80806) feat(hooks): expose senderId and sender metadata in agent turn hook contexts (before_prompt_build, agent_turn_prepare, etc.) 💬1

### 🔒 Closed Issues
- [#80842](https://github.com/openclaw/openclaw/issues/80842) [Feature]: Openclaw for Dingtalk optimization
- [#80832](https://github.com/openclaw/openclaw/issues/80832) [Bug]: message tool fails sending to Telegram forum topics (announce fallback works)
- [#80831](https://github.com/openclaw/openclaw/issues/80831) Backup --verify fails with double manifest.json when TMPDIR is inside backup source path
- [#80830](https://github.com/openclaw/openclaw/issues/80830) test
- [#63432](https://github.com/openclaw/openclaw/issues/63432) [Bug]: Control UI on iPad/Tailscale fails on image send with `RangeError: Maximum call stack size exceeded`
- [#63295](https://github.com/openclaw/openclaw/issues/63295) Session reset: /new prompt drops sender envelope, blocking personalized greetings
- [#63162](https://github.com/openclaw/openclaw/issues/63162) [Feature]:  File Explorer Toggle in Control UI

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 144,990 · **Open issues:** 10,225 · **Last push:** <1h ago

### 🚀 New Releases
- [desktop-pr20059-installers](https://github.com/NousResearch/hermes-agent/releases/tag/desktop-pr20059-installers) — Desktop PR #20059 — test installers (ad-hoc)

### ✅ Merged PRs
- [#24082](https://github.com/NousResearch/hermes-agent/pull/24082) fix(nous): surface Portal-flagged free models in picker even when curated list is stale
- [#24063](https://github.com/NousResearch/hermes-agent/pull/24063) feat(computer-use): refresh cua-driver on `hermes update` + add `install --upgrade`
- [#24058](https://github.com/NousResearch/hermes-agent/pull/24058) fix(dashboard): MiniMax 'Login' button launched Claude OAuth (salvage #22849)
- [#23948](https://github.com/NousResearch/hermes-agent/pull/23948) fix(cli): vertical fallback for markdown tables wider than terminal
- [#18036](https://github.com/NousResearch/hermes-agent/pull/18036) ui-tui: bundle with esbuild, drop runtime node_modules
- [#24013](https://github.com/NousResearch/hermes-agent/pull/24013) feat(ui-tui): resolve markdown links to readable page titles

### 🐛 New Issues
- [#24119](https://github.com/NousResearch/hermes-agent/issues/24119) get_model_context_length() unconditionally queries OpenRouter metadata even for non-OpenRouter users, causing false "below minimum 64K" rejections
- [#24117](https://github.com/NousResearch/hermes-agent/issues/24117) Slack Assistant thread can stay stuck in 'is thinking...' after response is sent
- [#24116](https://github.com/NousResearch/hermes-agent/issues/24116) Stale dashboard plugin cache persists after plugin directory is removed from disk
- [#24114](https://github.com/NousResearch/hermes-agent/issues/24114) [Bug]: Matrix gateway misclassifies 2-person rooms as DMs, disabling `MATRIX_REQUIRE_MENTION` and group auto-threading
- [#24108](https://github.com/NousResearch/hermes-agent/issues/24108) docs: three broken `/docs/...` links across the docs site `type/docs` `P3`
- [#24102](https://github.com/NousResearch/hermes-agent/issues/24102) [Bug]: Hermes-Agent keeps probing non-existent google/gemini-3-flash-preview model when using LM Studio OpenAI-compatible API `type/bug` `comp/agent` `area/config` `P2`
- [#24101](https://github.com/NousResearch/hermes-agent/issues/24101) [docs] - Voice & TTS md table malformed `type/docs` `P3`
- [#24100](https://github.com/NousResearch/hermes-agent/issues/24100) [Bug]: gateway command approval prompts route to wrong Discord thread — stale os.environ session key leaks across concurrent gateway sessions `type/bug` `comp/gateway` `platform/discord` `P1`
- [#24098](https://github.com/NousResearch/hermes-agent/issues/24098) Compression failure hangs main response loop indefinitely (HTTP 400 on auxiliary causes silent 88-min stall) `type/bug` `comp/agent` `P1`
- [#24097](https://github.com/NousResearch/hermes-agent/issues/24097) [Bug]: MCP OAuth login times out at 40s; per-server connect_timeout silently ignored `type/bug` `tool/mcp` `area/auth` `P2`
- [#24092](https://github.com/NousResearch/hermes-agent/issues/24092) [Bug]: fallback_providers with provider: custom + explicit base_url falls back to OpenRouter when main model.provider is a named provider `type/bug` `comp/agent` `area/config` `P2`

### 🔒 Closed Issues
- [#24089](https://github.com/NousResearch/hermes-agent/issues/24089) [Bug]: After installing the Windows version of the desktop app, the initialization gets stuck at 94%.
- [#22832](https://github.com/NousResearch/hermes-agent/issues/22832) [Bug]: Minimax oauth flow in the Hermes dashboard actually launches the Claude oauth flow

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,252 · **Open issues:** 474 · **Last push:** <1h ago

### ✅ Merged PRs
- [#6585](https://github.com/zeroclaw-labs/zeroclaw/pull/6585) fix(update): tighten release asset selection
- [#6569](https://github.com/zeroclaw-labs/zeroclaw/pull/6569) fix(vscode): remove duplicate --all-targets from rust-analyzer extraArgs
- [#6568](https://github.com/zeroclaw-labs/zeroclaw/pull/6568) fix(channels): gate telegram tests behind channel-telegram feature
- [#6567](https://github.com/zeroclaw-labs/zeroclaw/pull/6567) fix(ci): add crate paths to labeler.yml for workspace layout
- [#6570](https://github.com/zeroclaw-labs/zeroclaw/pull/6570) docs(container): correct image registry and add onboarding/re-auth steps
- [#6505](https://github.com/zeroclaw-labs/zeroclaw/pull/6505) fix(web): cron jobs table behaviour
- [#6513](https://github.com/zeroclaw-labs/zeroclaw/pull/6513) feat(providers): add atomic-chat as local provider option
- [#5254](https://github.com/zeroclaw-labs/zeroclaw/pull/5254) fix(provider): sanitize llama.cpp gemma4 tool schemas
- [#6008](https://github.com/zeroclaw-labs/zeroclaw/pull/6008) feat(provider): add prompt caching to OpenRouter
- [#6114](https://github.com/zeroclaw-labs/zeroclaw/pull/6114) fix(provider): strip media markers in auxiliary LLM calls

### 🐛 New Issues
- [#6589](https://github.com/zeroclaw-labs/zeroclaw/issues/6589) [BUG]: RouterProvider::supports_vision() uses .any() while supports_native_tools() uses default — silent bypass of multimodal.vision_provider fallback in mixed-provider setups `bug`
- [#6584](https://github.com/zeroclaw-labs/zeroclaw/issues/6584) [Bug]: OpenAI-Compatible provider ignores `reasoning` field, only reads `reasoning_content` `bug`
- [#6576](https://github.com/zeroclaw-labs/zeroclaw/issues/6576) [Feature]: Add v0.7.6 Matrix live homeserver smoke check after matrix-sdk 0.17 bump `enhancement` `risk: low` `channel` `channel:matrix` `release-gate` `priority:p2`
- [#6574](https://github.com/zeroclaw-labs/zeroclaw/issues/6574) [Feature]: configurable behaviour for image-bearing messages when no vision path is available
- [#6565](https://github.com/zeroclaw-labs/zeroclaw/issues/6565) [Feature]: clear inline-keyboard + reflect outcome on Telegram tool-approval messages after click `enhancement` `risk: medium` `channel` `tool` `channel:telegram` `priority:p2`
- [#6563](https://github.com/zeroclaw-labs/zeroclaw/issues/6563) [Feature]: Comfy Cloud / ComfyUI as shared media provider (remote workflows; image + path to gen_video) `enhancement` `risk: high` `config` `provider` `tool` `priority:p2` `needs-maintainer-review` `status:no-stale`
- [#6561](https://github.com/zeroclaw-labs/zeroclaw/issues/6561) fix(gateway): non-loopback --host recovery hint advertises admin URL that admin guard rejects `bug` `risk: low` `core` `gateway` `security: pairing` `priority:p3`

### 🔒 Closed Issues
- [#5687](https://github.com/zeroclaw-labs/zeroclaw/issues/5687) [Bug]: rust-analyzer error
- [#6347](https://github.com/zeroclaw-labs/zeroclaw/issues/6347) test(channels): build_channel_by_id telegram tests fail under default features
- [#6359](https://github.com/zeroclaw-labs/zeroclaw/issues/6359) chore(ci): labeler.yml doesn't auto-label crates/** changes
- [#6393](https://github.com/zeroclaw-labs/zeroclaw/issues/6393) [Bug]: Documentation error docker installation issue
- [#4083](https://github.com/zeroclaw-labs/zeroclaw/issues/4083) [Bug]: Can't get web search tool working on channels
- [#6504](https://github.com/zeroclaw-labs/zeroclaw/issues/6504) [Bug]: Confusing cron jobs table UX
- [#6530](https://github.com/zeroclaw-labs/zeroclaw/issues/6530) [Bug]: Build failure with matrix-sdk v0.16.0: recursion limit overflow when building with channel-matrix feature

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,216 · **Open issues:** 865 · **Last push:** <1h ago

### 🚀 New Releases
- [ironclaw-v0.28.1](https://github.com/nearai/ironclaw/releases/tag/ironclaw-v0.28.1) — 0.28.1 - 2026-05-11

### ✅ Merged PRs
- [#3476](https://github.com/nearai/ironclaw/pull/3476) [Reborn] Wire SkillContextService into loop prompt path
- [#3471](https://github.com/nearai/ironclaw/pull/3471) GitHub issue #3431: [Reborn] Add MemoryPromptContextService production adapter
- [#3468](https://github.com/nearai/ironclaw/pull/3468) GitHub issue #3451: [Reborn] Add direct DB operations for loop checkpoint mappings
- [#3493](https://github.com/nearai/ironclaw/pull/3493) Fix Reborn memory error redaction and SQL replay cursors
- [#3460](https://github.com/nearai/ironclaw/pull/3460) feat(reborn): add trusted LoopExitApplier
- [#3416](https://github.com/nearai/ironclaw/pull/3416) refactor(llm): hide provider-specific auth, model fetch, and embeddings config behind facades
- [#3470](https://github.com/nearai/ironclaw/pull/3470) GitHub issue #3432: [Reborn] Add deterministic trust-aware SkillContextService
- [#3462](https://github.com/nearai/ironclaw/pull/3462) [Reborn] Add user-selectable model routes and provider pool
- [#3495](https://github.com/nearai/ironclaw/pull/3495) Refactor ironclaw_network lib into focused modules
- [#3496](https://github.com/nearai/ironclaw/pull/3496) refactor(filesystem): split mega lib module

### 🐛 New Issues
- [#3500](https://github.com/nearai/ironclaw/issues/3500) Local web UI is undiscoverable through onboarding `enhancement`
- [#3499](https://github.com/nearai/ironclaw/issues/3499) Slack channel sends raw Markdown instead of converting to Slack mrkdwn format
- [#3492](https://github.com/nearai/ironclaw/issues/3492) [Reborn] Establish trust-boundary hardening baseline `enhancement` `reborn` 💬1
- [#3490](https://github.com/nearai/ironclaw/issues/3490) Admin tools settings are not propagated to users 💬1
- [#3484](https://github.com/nearai/ironclaw/issues/3484) [EPIC] Reborn Contributor Runway: enable parallel skill/tool/channel porting `enhancement` `reborn`
- [#3483](https://github.com/nearai/ironclaw/issues/3483) Package ironclaw-reborn in release artifacts
- [#3475](https://github.com/nearai/ironclaw/issues/3475) pairing_approve tool: add integration tests for DB-backed execution and E2E flow
- [#3474](https://github.com/nearai/ironclaw/issues/3474) pairing_approve tool: share web orchestration path (rollback + runtime propagation)
- [#3473](https://github.com/nearai/ironclaw/issues/3473) [Reborn] Wire SkillContextService to production skill sources and loop prompt `reborn`
- [#3466](https://github.com/nearai/ironclaw/issues/3466) [Reborn] Add FirstParty runtime adapter for host-owned capabilities `enhancement` `reborn`
- [#3465](https://github.com/nearai/ironclaw/issues/3465) ENGINE_V2 repeatedly calls `tool_info` during tool-use flows `bug`
- [#3464](https://github.com/nearai/ironclaw/issues/3464) ENGINE_V2: Failed tool calls render inconsistently in Gateway UI `bug`
- [#3463](https://github.com/nearai/ironclaw/issues/3463) Engine V2 generated images do not render correctly in Gateway UI `bug`
- [#3447](https://github.com/nearai/ironclaw/issues/3447) Nightly E2E failed
- [#3434](https://github.com/nearai/ironclaw/issues/3434) [Reborn] Add InstructionBundleBuilder and deterministic rebuild tests `reborn`

### 🔒 Closed Issues
- [#2903](https://github.com/nearai/ironclaw/issues/2903) [QA]  If telegram response is too long to the user, it fails silently
- [#3478](https://github.com/nearai/ironclaw/issues/3478) [Reborn] Add separate System runtime adapter for host-only capabilities

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 2d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 2d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 25 new
- [[Research] 2026Q1 Update](https://openai.com/signals/research/2026q1-update/) _2026-05-12_
- [Daybreak](https://openai.com/daybreak/) _2026-05-12_
- [[Daybreak] Request A Vulnerability Scan](https://openai.com/daybreak/request-a-vulnerability-scan/) _2026-05-12_
- [[Index] Openai Campus Network Student Club Interest Form](https://openai.com/index/openai-campus-network-student-club-interest-form/) _2026-05-12_
- [[Index] Openai Launches The Deployment Company](https://openai.com/index/openai-launches-the-deployment-company/) _2026-05-11_
- [[Business] The Openai Deployment Company](https://openai.com/business/the-openai-deployment-company/) _2026-05-11_
- [[Guides-And-Resources] How Enterprises Are Scaling Ai](https://openai.com/business/guides-and-resources/how-enterprises-are-scaling-ai/) _2026-05-11_
- [[Index] Where The Goblins Came From](https://openai.com/index/where-the-goblins-came-from/) _2026-05-11_
- [[Index] Gpt 4O System Card](https://openai.com/index/gpt-4o-system-card/) _2026-05-06_
- [[Index] Introducing Evmbench](https://openai.com/index/introducing-evmbench/) _2026-05-06_
- [[Index] Understanding Neural Networks Through Sparse Circuits](https://openai.com/index/understanding-neural-networks-through-sparse-circuits/) _2026-05-06_
- [[Index] How We Monitor Internal Coding Agents Misalignment](https://openai.com/index/how-we-monitor-internal-coding-agents-misalignment/) _2026-05-06_
- [[Index] Instruction Hierarchy Challenge](https://openai.com/index/instruction-hierarchy-challenge/) _2026-05-06_
- [[Index] Sora System Card](https://openai.com/index/sora-system-card/) _2026-05-06_
- [[Index] Accelerating Science Gpt 5](https://openai.com/index/accelerating-science-gpt-5/) _2026-05-05_
- [[Index] Gpt 5 5 Instant System Card](https://openai.com/index/gpt-5-5-instant-system-card/) _2026-05-05_
- [[Index] Introducing Simpleqa](https://openai.com/index/introducing-simpleqa/) _2026-05-04_
- [[Index] Publication](https://openai.com/research/index/publication/) _2026-05-04_
- [[Index] Better Exploration With Parameter Noise](https://openai.com/index/better-exploration-with-parameter-noise/) _2026-05-02_
- [[Index] Meta Learning For Wrestling](https://openai.com/index/meta-learning-for-wrestling/) _2026-05-02_
- [[Index] Learning A Hierarchy](https://openai.com/index/learning-a-hierarchy/) _2026-05-02_
- [[Index] Advancing Red Teaming With People And Ai](https://openai.com/index/advancing-red-teaming-with-people-and-ai/) _2026-05-02_
- [[Index] Hierarchical Text Conditional Image Generation With Clip Latents](https://openai.com/index/hierarchical-text-conditional-image-generation-with-clip-latents/) _2026-05-02_
- [[Index] Dall E 2 Pre Training Mitigations](https://openai.com/index/dall-e-2-pre-training-mitigations/) _2026-05-02_
- [[Index] Webgpt](https://openai.com/index/webgpt/) _2026-05-02_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
