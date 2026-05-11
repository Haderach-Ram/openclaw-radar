---
layout: post
title: "OpenClaw Radar — 2026-05-11"
date: 2026-05-11 08:03:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-10
*Generated 17:22 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 370,380 | 13 | 8 | 8 | 1 |
| **hermesagent** | 141,701 | 9 | 1 | 4 | 0 |
| **ZeroClaw** | 31,208 | 15 | 6 | 10 | 0 |
| **IronClaw** | 12,195 | 15 | 0 | 8 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 370,380 · **Open issues:** 7,571 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.9-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.5.9-beta.1) — openclaw 2026.5.9-beta.1

### ✅ Merged PRs
- [#80182](https://github.com/openclaw/openclaw/pull/80182) [codex] reduce plugin sdk surface
- [#80159](https://github.com/openclaw/openclaw/pull/80159) chore(canvas): refresh a2ui bundle hash
- [#80194](https://github.com/openclaw/openclaw/pull/80194) Add Telegram real-user Crabbox proof
- [#80187](https://github.com/openclaw/openclaw/pull/80187) fix(acpx): await startup probe before gateway ready
- [#79484](https://github.com/openclaw/openclaw/pull/79484) fix(agents): initialize context engines before CLI compaction
- [#80168](https://github.com/openclaw/openclaw/pull/80168) fix: allow tweakcn theme imports in Control UI CSP
- [#80138](https://github.com/openclaw/openclaw/pull/80138) fix: preserve Codex auth during route repair
- [#79911](https://github.com/openclaw/openclaw/pull/79911) fix(onboard): custom provider context window vs compaction floor (#79428)

### 🐛 New Issues
- [#80236](https://github.com/openclaw/openclaw/issues/80236) [Codex×Pi parity] Codex app-server returns unsupported read result in approval followthrough 💬2
- [#80234](https://github.com/openclaw/openclaw/issues/80234) Discord bot replies can trigger implicit reply-to-bot mentions 💬1
- [#80232](https://github.com/openclaw/openclaw/issues/80232) Feature Request: pageStatus filtering for wiki compile/search/lint 💬1
- [#80231](https://github.com/openclaw/openclaw/issues/80231) Group chat messages don't update in real-time on iOS — requires exit and re-entry 💬1
- [#80227](https://github.com/openclaw/openclaw/issues/80227) [Bug] Discord plugin: REST gateway metadata fetch bypasses account proxy, only WebSocket uses it 💬1
- [#80226](https://github.com/openclaw/openclaw/issues/80226) [Bug]: Memory index fails with "embeddings max length per batch size is 2000" — no chunking before embedding `bug` `regression` 💬1
- [#80219](https://github.com/openclaw/openclaw/issues/80219) [plugin sdk] Consolidate author surface, lifecycle semantics, and export sprawl 💬2
- [#80213](https://github.com/openclaw/openclaw/issues/80213) [Feature]: Skill author-defined setup hook (run skill-supplied script on install/update) `enhancement` 💬2
- [#80212](https://github.com/openclaw/openclaw/issues/80212) [Feature Request] Allow cron jobs to set session key matching inbound DM reply routing 💬1
- [#80206](https://github.com/openclaw/openclaw/issues/80206) [Bug]: Skills UI shows "Missing requirements" for clawhub and mcporter despite both binaries being installed and functional `bug` `regression` 💬2
- [#80205](https://github.com/openclaw/openclaw/issues/80205) npm plugin peer link drift can leave Discord tokens configured_unavailable 💬1
- [#80202](https://github.com/openclaw/openclaw/issues/80202) [5.9-beta.1] huggingface/openrouter/xai plugins fail register: api.registerModelCatalogProvider is not a function 💬1
- [#80201](https://github.com/openclaw/openclaw/issues/80201) [Bug]: Subagent announce delivered to parallel Telegram channel session instead of originating parent session (single-user, intra-agent) `bug` `bug:behavior` 💬1

### 🔒 Closed Issues
- [#80237](https://github.com/openclaw/openclaw/issues/80237) [Bug] Dashboard UI returns Internal Server Error - MODULE_NOT_FOUND
- [#79312](https://github.com/openclaw/openclaw/issues/79312) OpenAI Codex provider usage no longer shown in /status or openclaw status --usage
- [#79492](https://github.com/openclaw/openclaw/issues/79492) Agent runtime returns empty response for anthropic/claude-opus-4-7 while infer model run works (macOS 26.2, Node 26)
- [#39889](https://github.com/openclaw/openclaw/issues/39889) Control UI chat hangs in Chromium/Vivaldi; <openclaw-app> not registered/rendered although backend responds successfully
- [#39719](https://github.com/openclaw/openclaw/issues/39719) Stale iCloud skill paths in sessions.json after workspace migration
- [#39695](https://github.com/openclaw/openclaw/issues/39695) [Bug] Agent Responds but Silently Fails to Execute exec Tool or Create Session Logs
- [#39626](https://github.com/openclaw/openclaw/issues/39626) [Bug]: Exposes the format of tool calls, for example:exec{"command": "openclaw status", "description": "Check OpenClaw version and status"}
- [#80230](https://github.com/openclaw/openclaw/issues/80230) Add client-side clear chat command to Control UI webchat

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬104 · 5h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 141,701 · **Open issues:** 9,703 · **Last push:** <1h ago

### ✅ Merged PRs
- [#22991](https://github.com/NousResearch/hermes-agent/pull/22991) fix(codex): restore gpt-5.3-codex-spark for ChatGPT Pro (salvage #18286 + #19530, fixes #16172)
- [#23001](https://github.com/NousResearch/hermes-agent/pull/23001) chore(models): refresh OpenRouter + Nous fallback lists
- [#23003](https://github.com/NousResearch/hermes-agent/pull/23003) fix(kanban): /kanban slash command emits curated help (carve-out of #21795)
- [#23005](https://github.com/NousResearch/hermes-agent/pull/23005) feat(stream-retry): log inner cause, upstream headers, bytes/elapsed on every drop

### 🐛 New Issues
- [#23143](https://github.com/NousResearch/hermes-agent/issues/23143) feat(openviking): Add missing tools — grep, glob, forget, health
- [#23140](https://github.com/NousResearch/hermes-agent/issues/23140) Gateway mode doesn't invoke pre_llm_call / post_llm_call hooks — LCM and other context plugins fail silently in platform sessions
- [#23139](https://github.com/NousResearch/hermes-agent/issues/23139) [Bug]: kanban boads rm --delete does not delete boards
- [#23138](https://github.com/NousResearch/hermes-agent/issues/23138) [Bug] Eager fallback on HTTP 402 (FailoverReason.billing) does not activate; cron job loops on dead primary until output-length crash
- [#23137](https://github.com/NousResearch/hermes-agent/issues/23137) Please add SWE benchmark to show how good this approach is relative to the vanilla models(or to the simple /goal agent)
- [#23136](https://github.com/NousResearch/hermes-agent/issues/23136) [Feature]: HA outbound - support notify service (mobile push)
- [#23131](https://github.com/NousResearch/hermes-agent/issues/23131) Bug: /reset and /new do not reload default model from config.yaml
- [#23130](https://github.com/NousResearch/hermes-agent/issues/23130) Feature: workspace-scoped MCP config equivalent to VS Code .vscode/mcp.json `type/feature` `comp/agent` `tool/mcp` `area/config` `P3`
- [#23129](https://github.com/NousResearch/hermes-agent/issues/23129) [Bug]: MCP HTTP client double-encodes anyOf:[string,array] arguments — Jina read_url always fails `type/bug` `comp/agent` `tool/mcp` `P2`

### 🔒 Closed Issues
- [#23075](https://github.com/NousResearch/hermes-agent/issues/23075) Created by mistake

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,208 · **Open issues:** 471 · **Last push:** <1h ago

### ✅ Merged PRs
- [#6533](https://github.com/zeroclaw-labs/zeroclaw/pull/6533) fix(config): respect ZEROCLAW_CONFIG_DIR in path field defaults
- [#6545](https://github.com/zeroclaw-labs/zeroclaw/pull/6545) feat(runtime): multi-agent runtime
- [#6523](https://github.com/zeroclaw-labs/zeroclaw/pull/6523) feat(config)!: V0.8.0 schema-mirror env-var grammar (breaking change); eradicate every legacy override
- [#6546](https://github.com/zeroclaw-labs/zeroclaw/pull/6546) fix(agent): suppress tool protocol when no tools are available
- [#6540](https://github.com/zeroclaw-labs/zeroclaw/pull/6540) fix(build): route source web builds through cargo
- [#6542](https://github.com/zeroclaw-labs/zeroclaw/pull/6542) docs(skills): add user-facing skills guide
- [#6539](https://github.com/zeroclaw-labs/zeroclaw/pull/6539) fix(runtime): require shell approval in direct sessions
- [#6544](https://github.com/zeroclaw-labs/zeroclaw/pull/6544) fix(runtime): omit native tool prompt catalog
- [#6541](https://github.com/zeroclaw-labs/zeroclaw/pull/6541) fix(channels): scope session key for channel tools
- [#6534](https://github.com/zeroclaw-labs/zeroclaw/pull/6534) fix(sop): call reload() after SopEngine construction at both call sites

### 🐛 New Issues
- [#6558](https://github.com/zeroclaw-labs/zeroclaw/issues/6558) [Bug]: providers erro `risk: low` `config` `provider` `provider:compatible` `provider:qwen` `r:support` `priority:p3` 💬2
- [#6557](https://github.com/zeroclaw-labs/zeroclaw/issues/6557) [Feature]: Reconcile runtime model switching with provider structure for v0.8.0 `enhancement` `risk: medium` `channel` `config` `provider` `runtime` `priority:p2` `status:accepted` `status:no-stale`
- [#6556](https://github.com/zeroclaw-labs/zeroclaw/issues/6556) [Bug]: Discord channel — media send/receive broken (inbound images never processed, non-image types dropped, outbound markers leak) `bug` `risk: high` `channel` `security` `channel:discord` `priority:p1` `status:no-stale`
- [#6551](https://github.com/zeroclaw-labs/zeroclaw/issues/6551) [Bug]: Non-leading system messages can be sent to OpenAI-compatible providers `bug` `risk: high` `provider` `runtime` `provider:compatible` `priority:p1` `status:in-progress` `status:no-stale`
- [#6548](https://github.com/zeroclaw-labs/zeroclaw/issues/6548) [Bug]: Channel runtime command replies bypass Fluent localization `bug` `risk: medium` `channel` `runtime` `channel:core` `priority:p2` `status:in-progress` `status:no-stale`
- [#6543](https://github.com/zeroclaw-labs/zeroclaw/issues/6543) [Feature]: ACP session restore `enhancement` `risk: high` `channel` `runtime` `channel:core` `priority:p2` `status:no-stale` 💬1
- [#6530](https://github.com/zeroclaw-labs/zeroclaw/issues/6530) [Bug]: Build failure with matrix-sdk v0.16.0: recursion limit overflow when building with channel-matrix feature `bug` `ci` `risk: low` `channel` `channel:matrix` `status:accepted` `status:no-stale` `priority:p3` 💬4
- [#6520](https://github.com/zeroclaw-labs/zeroclaw/issues/6520) [Bug]:Gemini CLI provider crashes due to outdated argument syntax (--print vs --prompt) `bug` `risk: medium` `provider` `provider:gemini` `priority:p2` `status:accepted` `status:no-stale` 💬2
- [#6419](https://github.com/zeroclaw-labs/zeroclaw/issues/6419) [Bug]: WorkspaceManager fails to load profiles at Runtime startup `bug` `risk: medium` `config` `runtime` `tool` `tool:core` `priority:p2` `status:accepted` `status:no-stale` 💬2
- [#6378](https://github.com/zeroclaw-labs/zeroclaw/issues/6378) [Feature]: Discord Bot respond only in specific Discord channels `enhancement` `risk: high` `docs` `channel` `config` `channel:discord` `priority:p2` `status:accepted` `status:no-stale` 💬5
- [#6361](https://github.com/zeroclaw-labs/zeroclaw/issues/6361) [Bug]: context_compression drops assistant(tool_calls) and tool(result) entirely for OpenAI-compatible providers (e.g. MiniMax), causing tool loops and 2013 invalid message role: system `bug` `risk: high` `agent` `provider` `runtime` `tool` `provider:minimax` `provider: compatible` `priority:p1` `status:in-progress` `needs-maintainer-review` `status:no-stale` 💬2
- [#6309](https://github.com/zeroclaw-labs/zeroclaw/issues/6309) [Bug]:Agent running model_routing_config  "action": "upsert_agent"  stomps on schema_version = 2 settings `bug` `risk: high` `config` `provider` `tool` `tool: model_routing_config` `priority:p1` `status:accepted` `status:no-stale` 💬1
- [#6272](https://github.com/zeroclaw-labs/zeroclaw/issues/6272) Multi-agent runtime: per-alias workspaces, permissions, and shared resources `enhancement` `risk: high` `config` `runtime` `priority:p1` `status:accepted` `status:no-stale` 💬2
- [#6271](https://github.com/zeroclaw-labs/zeroclaw/issues/6271) [Feature]: V3 SwarmConfig schema + runtime implementation `enhancement` `risk: medium` `channel` `config` `tool` `priority:p2` `status:accepted` `status:no-stale` 💬1
- [#6253](https://github.com/zeroclaw-labs/zeroclaw/issues/6253) [Feature]: Track: zeroclaw skills support and UX (v0.7.6) `enhancement` `risk: low` `skills` `priority:p1` `status:accepted` `status:no-stale` 💬1

### 🔒 Closed Issues
- [#6207](https://github.com/zeroclaw-labs/zeroclaw/issues/6207) [Bug]: Web dashboard / WebSocket gateway path bypasses ApprovalManager — supervised tool approvals never surface in daemon web UI
- [#6547](https://github.com/zeroclaw-labs/zeroclaw/issues/6547) [Feature]: homebrew merge fail
- [#5863](https://github.com/zeroclaw-labs/zeroclaw/issues/5863) [Feature]: Document about skills wanted.
- [#5605](https://github.com/zeroclaw-labs/zeroclaw/issues/5605) [Bug]: Default Configuration Path Issues in Multi-Instance Deployments
- [#6030](https://github.com/zeroclaw-labs/zeroclaw/issues/6030) [Feature]: scope TOOL_LOOP_SESSION_KEY in channel orchestrator
- [#6039](https://github.com/zeroclaw-labs/zeroclaw/issues/6039) [Bug]: Copilot provider does not handle image uploaded via Discord channel

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,195 · **Open issues:** 865 · **Last push:** 13h ago

### ✅ Merged PRs
- [#3445](https://github.com/nearai/ironclaw/pull/3445) fix(reborn): close secret store review gaps
- [#3414](https://github.com/nearai/ironclaw/pull/3414) feat(reborn): add durable encrypted secret store
- [#3440](https://github.com/nearai/ironclaw/pull/3440) fix(resources): close durable governor review gaps
- [#3427](https://github.com/nearai/ironclaw/pull/3427) feat(reborn): add durable resource governor
- [#3411](https://github.com/nearai/ironclaw/pull/3411) feat(reborn): add loop prompt bundle port
- [#3426](https://github.com/nearai/ironclaw/pull/3426) Implement Reborn visible capability catalog
- [#3437](https://github.com/nearai/ironclaw/pull/3437) Avoid REPL auth retry race in E2E
- [#3430](https://github.com/nearai/ironclaw/pull/3430) Fix E2E auth and approval coverage

### 🐛 New Issues
- [#3447](https://github.com/nearai/ironclaw/issues/3447) Nightly E2E failed
- [#3443](https://github.com/nearai/ironclaw/issues/3443) Layer A-D LLM boundary cleanup: remaining follow-ups
- [#3436](https://github.com/nearai/ironclaw/issues/3436) DeepSeek API returns 400: reasoning_content must be passed back in thinking mode
- [#3435](https://github.com/nearai/ironclaw/issues/3435) [Reborn] Add production TurnRunWakeNotifier scheduler `risk: high` `scope: agent` `reborn`
- [#3434](https://github.com/nearai/ironclaw/issues/3434) [Reborn] Add InstructionBundleBuilder and deterministic rebuild tests `reborn`
- [#3433](https://github.com/nearai/ironclaw/issues/3433) [Reborn] Complete HostManagedModelGateway budget, credential, and redaction tests `reborn`
- [#3432](https://github.com/nearai/ironclaw/issues/3432) [Reborn] Add deterministic trust-aware SkillContextService `reborn`
- [#3431](https://github.com/nearai/ironclaw/issues/3431) [Reborn] Add MemoryPromptContextService production adapter `reborn`
- [#3429](https://github.com/nearai/ironclaw/issues/3429) [Reborn] Add loop production readiness validation `reborn`
- [#3425](https://github.com/nearai/ironclaw/issues/3425) Bug: Intermittent i18n regression in Production causes translation keys to render in the UI `bug`
- [#3424](https://github.com/nearai/ironclaw/issues/3424) [Reborn] Add trusted LoopExitApplier `reborn`
- [#3259](https://github.com/nearai/ironclaw/issues/3259) Publish 0.25.0–0.27.0 to crates.io — downstream pinned to 0.24.0 by wasmtime 28.x CVEs 💬2
- [#3107](https://github.com/nearai/ironclaw/issues/3107) [Reborn] Define AgentLoopDriver and run-class profile contract `enhancement` `reborn` 💬3
- [#2987](https://github.com/nearai/ironclaw/issues/2987) [EPIC] Track Reborn architecture landing strategy and grouped PR plan `enhancement` `risk: high` `scope: docs` `ownership` `reborn` 💬44
- [#2949](https://github.com/nearai/ironclaw/issues/2949) ERROR: there isn't a download for your platform x86_64-unknown-linux-gnu 💬4

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 16h ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 1d ago

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*