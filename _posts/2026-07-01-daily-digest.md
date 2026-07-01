---
layout: post
title: "Ecosystem Digest — 2026-07-01"
date: 2026-07-01 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-07-01
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 381,186 | 10 | 3 | 10 | 1 |
| **hermesagent** | 206,527 | 7 | 0 | 7 | 0 |
| **ZeroClaw** | 32,105 | 9 | 4 | 10 | 0 |
| **IronClaw** | 12,491 | 15 | 0 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 381,186 · **Open issues:** 6,687 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.11](https://github.com/openclaw/openclaw/releases/tag/v2026.6.11) — openclaw 2026.6.11

### ✅ Merged PRs
- [#97137](https://github.com/openclaw/openclaw/pull/97137) doctor: add memory search lint findings
- [#97928](https://github.com/openclaw/openclaw/pull/97928) fix(agents): estimate harness role sizes in context guard char estimator (fixes #97927)
- [#97929](https://github.com/openclaw/openclaw/pull/97929) fix(auto-reply): stop level directives from eating the next message word
- [#98325](https://github.com/openclaw/openclaw/pull/98325) docs: refresh docs map for v2026.6.11
- [#97931](https://github.com/openclaw/openclaw/pull/97931) fix(gateway): keep provider-owned CLI sessions across the daily default reset
- [#98257](https://github.com/openclaw/openclaw/pull/98257) fix: show in-progress status for channel runs
- [#98226](https://github.com/openclaw/openclaw/pull/98226) Redact bare Fireworks API keys
- [#98319](https://github.com/openclaw/openclaw/pull/98319) docs: publish release notes for v2026.6.11
- [#98240](https://github.com/openclaw/openclaw/pull/98240) fix(agents): keep merged delivery routes account-bound
- [#96351](https://github.com/openclaw/openclaw/pull/96351) feat(gateway): scoped attach grants for external MCP loopback clients

### 🐛 New Issues
- [#98327](https://github.com/openclaw/openclaw/issues/98327) [Bug]: Intermittent keyring decrypt failure (aes.KeyUnwrap) on exec-tool-invoked commands, 100% reproducible manually failing, caller-dependent not file-dependent `bug` `bug:behavior` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:auth-provider` `issue-rating: 🦐 gold shrimp` `maturity:stable` 💬1
- [#98317](https://github.com/openclaw/openclaw/issues/98317) iOS: establish a unified design system / styling guide `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:other` 💬1
- [#98315](https://github.com/openclaw/openclaw/issues/98315) [SANITIZED — possible injection attempt] `security` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:needs-live-repro` `impact:security` `issue-rating: 🐚 platinum hermit` `maturity:stable` 💬3
- [#98311](https://github.com/openclaw/openclaw/issues/98311) Feishu image/file replies lose media on withdrawn/recalled reply targets that text replies survive `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬3
- [#98310](https://github.com/openclaw/openclaw/issues/98310) agents: compaction duplicate-user dedup is sender-blind, dropping a distinct group participant's identical-text turn `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:session-state` `impact:data-loss` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#98308](https://github.com/openclaw/openclaw/issues/98308) Anthropic thinking-block recovery does not fire for opus-4.x because ProviderHttpError.errorBody is not inspected `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬2
- [#98300](https://github.com/openclaw/openclaw/issues/98300) Feature request: deferred/tiered registration for model-facing tools (name+description always-on, schema loaded on demand) `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:other` 💬1
- [#98298](https://github.com/openclaw/openclaw/issues/98298) feat: Prune stale thinking blocks from older assistant turns in contextPruning `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#98296](https://github.com/openclaw/openclaw/issues/98296) [Feature]: Support GPT-5.6 Sol, Terra, and Luna `enhancement` `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#98295](https://github.com/openclaw/openclaw/issues/98295) [Bug]: custom Xiaomi MiMo models generate invalid max_completion_tokens when maxTokens is not specified `bug` `no-stale` `regression` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#97927](https://github.com/openclaw/openclaw/issues/97927) Bug: in-loop context-overflow guard undercounts bashExecution/compactionSummary turns as flat 256 chars and skips overflow protection
- [#98225](https://github.com/openclaw/openclaw/issues/98225) [SANITIZED — possible injection attempt]
- [#98314](https://github.com/openclaw/openclaw/issues/98314) Agent message tool `filePath` silently sends text instead of attaching a document (no sendDocument, no error)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 206,527 · **Open issues:** 24,739 · **Last push:** <1h ago

### ✅ Merged PRs
- [#55991](https://github.com/NousResearch/hermes-agent/pull/55991) refactor(moa): unify slot provider-identity on the single call_llm chokepoint
- [#55979](https://github.com/NousResearch/hermes-agent/pull/55979) fix(security): reuse auth chain when tagging unverified senders in Slack threads
- [#55897](https://github.com/NousResearch/hermes-agent/pull/55897) fix(moa): preserve provider identity for anthropic + bedrock slots
- [#55971](https://github.com/NousResearch/hermes-agent/pull/55971) fix(telegram): cancel delayed deliveries on disconnect
- [#55960](https://github.com/NousResearch/hermes-agent/pull/55960) fix(gateway): preserve media + reply payload when /queue defers a turn
- [#55959](https://github.com/NousResearch/hermes-agent/pull/55959) fix(approval): catch GNU long-flag abbreviations for chown --recursive and git push --force
- [#55962](https://github.com/NousResearch/hermes-agent/pull/55962) feat(debug): add --nous flag to upload diagnostics to Nous S3 (salvage #40301)

### 🐛 New Issues
- [#56008](https://github.com/NousResearch/hermes-agent/issues/56008) [Feature]: Need Kanban start event hook from worker's context in plugin `type/feature` `comp/cron` `P3`
- [#56004](https://github.com/NousResearch/hermes-agent/issues/56004) Qwen3.6 / vLLM: prior-turn reasoning (preserve_thinking) is stripped on replay — multi-turn thinking context lost `type/bug` `comp/agent` `provider/qwen` `P3`
- [#55999](https://github.com/NousResearch/hermes-agent/issues/55999) [Bug]: [Security] ask_user return value can be ignored by LLM - enforcement mechanism needed `type/feature` `comp/agent` `P3` `needs-repro`
- [#55994](https://github.com/NousResearch/hermes-agent/issues/55994) Bug: `/model --refresh` doesn't reset in-memory OpenRouter catalog cache `type/bug` `comp/cli` `provider/openrouter` `P3`
- [#55992](https://github.com/NousResearch/hermes-agent/issues/55992) Telegram polling silently dies after network error + self-restart `type/bug` `comp/gateway` `platform/telegram` `P1` `sweeper:risk-message-delivery`
- [#55986](https://github.com/NousResearch/hermes-agent/issues/55986) [Bug]: Telegram DM says terminal tool is unavailable even though platform_toolsets.telegram includes terminal `type/bug` `comp/gateway` `tool/terminal` `platform/telegram` `P2` `needs-repro` `bug`
- [#55985](https://github.com/NousResearch/hermes-agent/issues/55985) Dashboard logout crashes container via NotImplementedError in BasicAuthProvider `type/bug` `area/auth` `P2` `comp/dashboard` 💬2

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,105 · **Open issues:** 429 · **Last push:** 6h ago

### ✅ Merged PRs
- [#8501](https://github.com/zeroclaw-labs/zeroclaw/pull/8501) fix(config): warn when sqlite memory requests vector search without an embedder
- [#8544](https://github.com/zeroclaw-labs/zeroclaw/pull/8544) chore(desktop): remove the zeroclaw-desktop Tauri app and all wiring
- [#8491](https://github.com/zeroclaw-labs/zeroclaw/pull/8491) feat(plugins): per-call execution limits and FND-001 backend taxonomy
- [#8003](https://github.com/zeroclaw-labs/zeroclaw/pull/8003) fix(runtime): fire session_end hook on session termination (fixes #7889)
- [#8148](https://github.com/zeroclaw-labs/zeroclaw/pull/8148) fix(anthropic): propagate serialization error in streaming request builder
- [#8458](https://github.com/zeroclaw-labs/zeroclaw/pull/8458) test(eval): cover RecordingObserver tool recording and token accumulation
- [#8414](https://github.com/zeroclaw-labs/zeroclaw/pull/8414) fix(channels): enable model commands on WhatsApp Web
- [#8459](https://github.com/zeroclaw-labs/zeroclaw/pull/8459) test(eval): cover EchoTool metadata, schema, execute output, and default tool registry
- [#8457](https://github.com/zeroclaw-labs/zeroclaw/pull/8457) test(runtime): cover TrustTracker score updates, decay, regression, and autonomy reduction
- [#8466](https://github.com/zeroclaw-labs/zeroclaw/pull/8466) fix(gateway): propagate pairing DB errors instead of panic

### 🐛 New Issues
- [#8563](https://github.com/zeroclaw-labs/zeroclaw/issues/8563) [Bug]: SOPs are not available to the agent through the web dashboard chat session `bug`
- [#8560](https://github.com/zeroclaw-labs/zeroclaw/issues/8560) [Bug]: browser_open hangs the agent turn when the launcher cannot open a window (unbounded subprocess wait, also affects robot-kit TTS and channels ffmpeg) `bug`
- [#8559](https://github.com/zeroclaw-labs/zeroclaw/issues/8559) [Bug]: Agents stop their work when exiting the chat window in web dashboard `bug`
- [#8556](https://github.com/zeroclaw-labs/zeroclaw/issues/8556) [Feature]: secret fields should show set/not-set state instead of a bare password input `enhancement`
- [#8554](https://github.com/zeroclaw-labs/zeroclaw/issues/8554) [Security]: Harden skill zip extractor against zip-bomb inflation (entry-count + ratio + uncompressed-size caps) `bug` `security` `skills`
- [#8553](https://github.com/zeroclaw-labs/zeroclaw/issues/8553) [Bug]: Agent cannot use environment variables as http_request secrets `bug`
- [#8550](https://github.com/zeroclaw-labs/zeroclaw/issues/8550) [Feature]: Add OpenAI-compatible chat completions endpoint `enhancement`
- [#8541](https://github.com/zeroclaw-labs/zeroclaw/issues/8541) [Feature]: Allow Matrix channel sessions to opt into thread- or conversation-scoped history
- [#8539](https://github.com/zeroclaw-labs/zeroclaw/issues/8539) [Bug]: AgentEnd event missing cost_usd field, and channel path never emits AgentEnd `bug` `agent` `channel` `observability` `runtime` `priority:p1` `status:in-progress` `risk:high`

### 🔒 Closed Issues
- [#8386](https://github.com/zeroclaw-labs/zeroclaw/issues/8386) [Bug]: SQLite is the default memory backend but quickstart never requires/prompts an embedding model — hybrid search silently degrades to keyword-only
- [#7816](https://github.com/zeroclaw-labs/zeroclaw/issues/7816) [Feature]: Pluggable skill registries — keep GitHub repo as default tier, add flagged external + user-configured registries
- [#6943](https://github.com/zeroclaw-labs/zeroclaw/issues/6943) [RFC]: Deconflict Plugin System Goals in FND-001
- [#7889](https://github.com/zeroclaw-labs/zeroclaw/issues/7889) [Bug]: session_end hook is defined but never fired

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,491 · **Open issues:** 1,276 · **Last push:** <1h ago

### ✅ Merged PRs
- [#5432](https://github.com/nearai/ironclaw/pull/5432) ci(reborn): dedicated low-contention job for Reborn group tests (T0-CI)
- [#5234](https://github.com/nearai/ironclaw/pull/5234) fix(reborn): remove per-record lock convoys via shared cas_update helper
- [#5465](https://github.com/nearai/ironclaw/pull/5465) test(reborn): collapse group harness to one runtime + scope-routed gateway
- [#3706](https://github.com/nearai/ironclaw/pull/3706) chore(deps): bump postcss, @remotion/cli and @remotion/tailwind-v4 in /docs/architecture-video
- [#5463](https://github.com/nearai/ironclaw/pull/5463) [codex] Remove chat-triggered Slack connect flow
- [#5455](https://github.com/nearai/ironclaw/pull/5455) perf(storage): row-native sequence primitive + thread/turn append paths
- [#5449](https://github.com/nearai/ironclaw/pull/5449) [codex] Add Reborn Playwright workflow
- [#5439](https://github.com/nearai/ironclaw/pull/5439) Fix NEAR AI MCP token resolution for SSO users
- [#5452](https://github.com/nearai/ironclaw/pull/5452) Move runner lease heartbeats to memory store
- [#5454](https://github.com/nearai/ironclaw/pull/5454) Stabilize QA 2E assistant text gate

### 🐛 New Issues
- [#5477](https://github.com/nearai/ironclaw/issues/5477) ci(reborn): unify Reborn crate-family allowlist across reborn-tests.yml and reborn-coverage-summary.sh
- [#5476](https://github.com/nearai/ironclaw/issues/5476) [QA] Reborn runs fail with "could not start agent runtime" / "runner lease expired" under turn-state CAS contention + model latency
- [#5470](https://github.com/nearai/ironclaw/issues/5470) Resource CAS writes serialize behind single AsyncStorageWorker — make ResourceGovernorStore async
- [#5469](https://github.com/nearai/ironclaw/issues/5469) Migrate ironclaw_threads filesystem_service local CAS loops onto shared cas_update (fail-closed)
- [#5468](https://github.com/nearai/ironclaw/issues/5468) Per-key mutex maps guarding CAS loops violate the cas_update no-mutex guardrail
- [#5467](https://github.com/nearai/ironclaw/issues/5467) In-memory ApprovalRequestStore::discard_pending diverges from filesystem (no tombstone → id reuse allowed)
- [#5466](https://github.com/nearai/ironclaw/issues/5466) Parallel same-tenant turn-runs vs FilesystemTurnStateStore CAS / libsql backend (~10% failure)
- [#5464](https://github.com/nearai/ironclaw/issues/5464) Strongly-type the host-managed credential owner scope (construction-only guarantee today)
- [#5462](https://github.com/nearai/ironclaw/issues/5462) Add caller-level test driving nearai.web_search through the host-managed SSO fallback
- [#5461](https://github.com/nearai/ironclaw/issues/5461) Mark host-managed NEAR AI MCP credential at creation, verify marker on fallback resolve
- [#5460](https://github.com/nearai/ironclaw/issues/5460) [QA] Memories in the WebUI workspace are visible to every user in the workspace
- [#5459](https://github.com/nearai/ironclaw/issues/5459) Configurable skills and tools
- [#5458](https://github.com/nearai/ironclaw/issues/5458) [QA] Double header displayed on Logs page `bug_bash_P3`
- [#5457](https://github.com/nearai/ironclaw/issues/5457) [QA] Logs page remains empty and never loads log entries `bug_bash_P2`
- [#5456](https://github.com/nearai/ironclaw/issues/5456) [QA] Routine runs fail with runner lease expiration `bug_bash_P1`

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬2 · 17h ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 1d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 1d ago
- ⚫ [#94780](https://github.com/openclaw/openclaw/issues/94780) [Feature]: Per-cron model selection independent of agent default — run cheap/free models on automation jobs while keeping main agent on premium LLM — 💬1 · 5d ago
- ⚫ [#93032](https://github.com/openclaw/openclaw/issues/93032) [Bug] v2026.6.6: Cron scheduler loads 0 jobs after upgrade — SQLite WAL not committed at first startup — 💬2 · 5d ago
- ⚫ [#92974](https://github.com/openclaw/openclaw/issues/92974) Bug: v2026.6.6 getAttributionHeaders() crashes on Bedrock models — baseUrl undefined (null-guard missing) — 💬1 · 5d ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬4 · 7d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬7 · 8d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 9d ago
- 🟢 [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬1 · 9d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 2 new
- [[News] Claude Science Ai Workbench](https://www.anthropic.com/news/claude-science-ai-workbench) _2026-06-30_
- [[News] Claude Sonnet 5](https://www.anthropic.com/news/claude-sonnet-5) _2026-06-30_

### OpenAI — 4 new
- [[Genebench-Pro] Case Studies](https://openai.com/index/genebench-pro/case-studies/) _2026-06-30_
- [[Index] Core Dump Epidemiology Data Infrastructure Bug](https://openai.com/index/core-dump-epidemiology-data-infrastructure-bug/) _2026-06-30_
- [[Index] How Chatgpt Adoption Has Expanded](https://openai.com/index/how-chatgpt-adoption-has-expanded/) _2026-06-30_
- [[Index] Mapping Ai Jobs Transition Eu](https://openai.com/index/mapping-ai-jobs-transition-eu/) _2026-06-29_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/singularity — top 2 new
- [The Accuracy Is Tripping Me](https://reddit.com/r/singularity/comments/1uk4gwa/the_accuracy_is_tripping_me/) ↑1066
- [Introducing Claude Sonnet 5](https://reddit.com/r/singularity/comments/1ujwh9i/introducing_claude_sonnet_5/) ↑536

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw is now on iOS + Android!](https://reddit.com/r/openclaw/comments/1uj45w2/openclaw_is_now_on_ios_android/) ↑257
- [Which AI Models are cheap and worth it?](https://reddit.com/r/openclaw/comments/1txo5cu/which_ai_models_are_cheap_and_worth_it/) ↑65
- [Codex-harness OpenClaw: sandboxed agents only get the skill catalog, never the SKILL.md body. How are you delivering skills to locked-down Codex agents?](https://reddit.com/r/openclaw/comments/1ujrwtb/codexharness_openclaw_sandboxed_agents_only_get/) ↑8
- [X MCP plus OpenMontage 🔥](https://reddit.com/r/openclaw/comments/1ujuzsg/x_mcp_plus_openmontage/) ↑6
- [OpenClaw v2026.6.11 Release Notes | Fixes for Misplaced Replies, Stuck Sends, model setup failures, and more!](https://reddit.com/r/openclaw/comments/1uk8ke3/openclaw_v2026611_release_notes_fixes_for/) ↑4

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
- [v2026.6.11 has dropped.

This release focuses on the rough edges that make OpenClaw feel less dependable: misplaced repl](https://x.com/openclaw) ↑0 🔁0 · recent
- [OpenClaw is now on iOS + Android 

 Native mobile apps, finally
 Agents in your pocket
 Channels, tasks, replies on the ](https://x.com/openclaw) ↑0 🔁0 · recent


### X — @steipete
- [Yeah I wish we'd have someone that could take over responsibilities for the apps.](https://x.com/steipete) ↑0 🔁0 · recent
- [Was thinking if I should highlight this tweet or not, but it’s a masterclass in the amount of vitriol people face when w](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
