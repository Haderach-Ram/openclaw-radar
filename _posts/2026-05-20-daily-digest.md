---
layout: post
title: "Ecosystem Digest — 2026-05-20"
date: 2026-05-20 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-20
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 373,273 | 5 | 5 | 10 | 2 |
| **hermesagent** | 158,118 | 8 | 2 | 6 | 0 |
| **ZeroClaw** | 31,466 | 2 | 2 | 2 | 0 |
| **IronClaw** | 12,295 | 12 | 5 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 373,273 · **Open issues:** 7,219 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.19-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.5.19-beta.2) — openclaw 2026.5.19-beta.2
- [v2026.5.19-alpha.1](https://github.com/openclaw/openclaw/releases/tag/v2026.5.19-alpha.1) — openclaw 2026.5.19-alpha.1

### ✅ Merged PRs
- [#84191](https://github.com/openclaw/openclaw/pull/84191) Expose messageId in message CLI JSON output
- [#83315](https://github.com/openclaw/openclaw/pull/83315) fix(doctor): preserve unknown web search records
- [#84368](https://github.com/openclaw/openclaw/pull/84368) fix(code-mode): sharpen exec tool description so models stop wasting turns rediscovering constraints
- [#84308](https://github.com/openclaw/openclaw/pull/84308) fix(cron): keep recovered tool warnings diagnostic
- [#84374](https://github.com/openclaw/openclaw/pull/84374) Fix Anthropic CLI auth routing for shorthand refs
- [#84311](https://github.com/openclaw/openclaw/pull/84311) fix(cron): use structured denial signals
- [#84355](https://github.com/openclaw/openclaw/pull/84355) gateway: use identity.name in agent summaries when name is unset
- [#84331](https://github.com/openclaw/openclaw/pull/84331) Move Codex soul context to developer instructions
- [#84169](https://github.com/openclaw/openclaw/pull/84169) fix(discord): preserve streamed replies after tool warnings
- [#84309](https://github.com/openclaw/openclaw/pull/84309) fix(twitch): export clearRegistryForTest for cross-test isolation (#83887)

### 🐛 New Issues
- [#84393](https://github.com/openclaw/openclaw/issues/84393) OpenClaw Codex runtime silently injects coding-agent base prompt into operational agents `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:needs-live-repro` `impact:session-state` `impact:security` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬2
- [#84386](https://github.com/openclaw/openclaw/issues/84386) [Bug]: Codex OAuth relogin creates fresh named profile but lastGood keeps selecting stale default on 2026.5.18 `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬2
- [#84384](https://github.com/openclaw/openclaw/issues/84384) [Bug]: Gemini 2.5 Flash via vertex-ai (OpenAI-compatible) streaming times out — thinking tokens not handled `P2` `clawsweeper:needs-live-repro` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬1
- [#84376](https://github.com/openclaw/openclaw/issues/84376) [Bug]: secrets audit flags codex "codex-app-server" auth marker as PLAINTEXT_FOUND (isNonSecretApiKeyMarker should include it) `bug` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-security-review` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:security` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#84365](https://github.com/openclaw/openclaw/issues/84365) [Bug]: Codex Harness Startup Failures on Windows (OpenClaw 2026.5.18) `bug` 💬2

### 🔒 Closed Issues
- [#83287](https://github.com/openclaw/openclaw/issues/83287) [Bug]: legacy web search migration drops unrelated record-valued config
- [#67626](https://github.com/openclaw/openclaw/issues/67626) [Bug]: 越更新越更的像屎一样
- [#84332](https://github.com/openclaw/openclaw/issues/84332) Heartbeat-spawned claude live session captures channel user inbounds, causing context-amnesiac fork replies
- [#84379](https://github.com/openclaw/openclaw/issues/84379) xAI OAuth fails: `api:access` scope rejected by xAI server ("Unknown scope: ap")
- [#84222](https://github.com/openclaw/openclaw/issues/84222) [Bug]: [reopen #82344] Regression after upgrading from 2026.5.7 → 2026.5.18: embedded runtime detected as third-party harness while direct Claude CLI still works

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 158,118 · **Open issues:** 12,239 · **Last push:** <1h ago

### ✅ Merged PRs
- [#28993](https://github.com/NousResearch/hermes-agent/pull/28993) fix(gateway): transcribe native voice notes (Discord + DingTalk)
- [#28994](https://github.com/NousResearch/hermes-agent/pull/28994) fix(kanban): worker-initiated block must not be auto-promoted (#28712)
- [#28861](https://github.com/NousResearch/hermes-agent/pull/28861) ci(tests): add pytest-timeout 60s hard cap to break suite-teardown deadlock
- [#28957](https://github.com/NousResearch/hermes-agent/pull/28957) perf(compression): defer feasibility check to first compression attempt — cut 170-290ms off every chat invocation
- [#28964](https://github.com/NousResearch/hermes-agent/pull/28964) nix: package apps/desktop as .#desktop
- [#28955](https://github.com/NousResearch/hermes-agent/pull/28955) fix(cli): handle worktrees with no remote refs (salvage #11384)

### 🐛 New Issues
- [#29037](https://github.com/NousResearch/hermes-agent/issues/29037) fix(weixin): replace aiohttp ClientTimeout with asyncio.wait_for()
- [#29034](https://github.com/NousResearch/hermes-agent/issues/29034) Kanban defaults can auto-launch unbounded paid worker swarms across all boards
- [#29027](https://github.com/NousResearch/hermes-agent/issues/29027) kanban dispatcher retries kanban_block with 'review-required:' reasons up to failure_limit, causing duplicate worker runs of finished tasks `type/bug` `comp/cli` `P3`
- [#29026](https://github.com/NousResearch/hermes-agent/issues/29026) [Feature]: Discord Reaction Support in Hermes Agent `type/feature` `comp/gateway` `platform/discord` `P3`
- [#29023](https://github.com/NousResearch/hermes-agent/issues/29023) [Bug]: WhatsApp reply-to-bot detection fails — device suffix mismatch in botIds vs quotedParticipant `type/bug` `comp/gateway` `platform/whatsapp` `P2` 💬1
- [#29017](https://github.com/NousResearch/hermes-agent/issues/29017) docs(curator): 'agent-created' definition is stale — docs claim foreground-created skills are curated, but PR #19621 restricted to background-review only `type/docs` `tool/skills` `P3`
- [#29015](https://github.com/NousResearch/hermes-agent/issues/29015) macOS: per-profile HOME isolation in _make_run_env hides ~/Library/Keychains from worker subprocesses, breaks claude CLI auth `type/bug` `comp/agent` `backend/local` `P2`
- [#29014](https://github.com/NousResearch/hermes-agent/issues/29014) Kanban dispatcher repeatedly respawns blocked/manual-gate tasks, causing provider quota drain `type/bug` `comp/gateway` `comp/cron` `P3`

### 🔒 Closed Issues
- [#28706](https://github.com/NousResearch/hermes-agent/issues/28706) [OPS] CPU spikes to 144%+ due to uncoordinated kanban worker CI parallelism
- [#28712](https://github.com/NousResearch/hermes-agent/issues/28712) kanban: dispatcher auto-promotes blocked task → respawn worker → protocol_violation loop

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,466 · **Open issues:** 497 · **Last push:** <1h ago

### ✅ Merged PRs
- [#6776](https://github.com/zeroclaw-labs/zeroclaw/pull/6776) fix(web): 0.8.0 ui fixes
- [#6649](https://github.com/zeroclaw-labs/zeroclaw/pull/6649) feat(channels/acp): persist ACP sessions

### 🐛 New Issues
- [#6801](https://github.com/zeroclaw-labs/zeroclaw/issues/6801) [Bug]: purge_namespace deletes by category column on integration/v0.8.0  `bug`
- [#6771](https://github.com/zeroclaw-labs/zeroclaw/issues/6771) [Bug]: Multiline Heredocs incorrectly blocked by SecurityPolicy `bug`

### 🔒 Closed Issues
- [#1458](https://github.com/zeroclaw-labs/zeroclaw/issues/1458) [Feature]: Add support for local CA certificates for custom inference provider
- [#6543](https://github.com/zeroclaw-labs/zeroclaw/issues/6543) [Feature]: ACP session restore

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,295 · **Open issues:** 946 · **Last push:** <1h ago

### ✅ Merged PRs
- [#3795](https://github.com/nearai/ironclaw/pull/3795) Tighten legacy extension v2 capability manifests
- [#3794](https://github.com/nearai/ironclaw/pull/3794) Add extension v2 lifecycle E2E coverage
- [#3792](https://github.com/nearai/ironclaw/pull/3792) feat(reborn): route REPL LLM auth through composition
- [#3791](https://github.com/nearai/ironclaw/pull/3791) Convert representative runtime fixtures to host API manifests
- [#3790](https://github.com/nearai/ironclaw/pull/3790) Add hot capability catalog publication
- [#3788](https://github.com/nearai/ironclaw/pull/3788) Wire default HostPortCatalog into extension discovery
- [#3739](https://github.com/nearai/ironclaw/pull/3739) refactor: extract embeddings into ironclaw_embeddings crate
- [#3787](https://github.com/nearai/ironclaw/pull/3787) Register default host API contracts in composition
- [#3786](https://github.com/nearai/ironclaw/pull/3786) test(reborn): cover approval cancellation parity
- [#3785](https://github.com/nearai/ironclaw/pull/3785) feat(reborn): add composed CLI repl

### 🐛 New Issues
- [#3809](https://github.com/nearai/ironclaw/issues/3809) [Reborn] Lane 8: finish EventStreamManager timeline/replay path `reborn` `module:M5-events-streaming`
- [#3807](https://github.com/nearai/ironclaw/issues/3807) [Reborn WebUI] Lane 7: finish beta route/tool surface path `scope: channel/web` `reborn`
- [#3806](https://github.com/nearai/ironclaw/issues/3806) [Reborn] Lane 6: implement GitHub WASM read/write capability path `reborn`
- [#3805](https://github.com/nearai/ironclaw/issues/3805) [Reborn] Lane 5: implement Notion MCP capability path `reborn`
- [#3804](https://github.com/nearai/ironclaw/issues/3804) [Reborn] Lane 4: implement Native Memory as a capability provider `reborn`
- [#3803](https://github.com/nearai/ironclaw/issues/3803) [Reborn] Lane 3: wire existing secrets/egress substrate through production tool composition `scope: secrets` `reborn` `module:M4-host-kernel`
- [#3801](https://github.com/nearai/ironclaw/issues/3801) [Reborn] Lane 2: finish extension-v2 catalog readiness after catalog PRs merge `reborn`
- [#3800](https://github.com/nearai/ironclaw/issues/3800) [Reborn] Lane 1: finish REPL golden path after composition PRs merge `reborn` `module:M3-agentloop-turns`
- [#3798](https://github.com/nearai/ironclaw/issues/3798) Design: subagent spawn for the Reborn agent loop `enhancement` `scope: agent` `reborn`
- [#3796](https://github.com/nearai/ironclaw/issues/3796) feat(reborn): add tenant-scoped groups and project ACLs `reborn`
- [#3773](https://github.com/nearai/ironclaw/issues/3773) [epic] Crate boundary & ownership ambiguity audit — reborn-integration `documentation` `scope: agent`
- [#3771](https://github.com/nearai/ironclaw/issues/3771) v0.28.2: Improve Configure UI for non-API-key providers and AWS Bedrock

### 🔒 Closed Issues
- [#3630](https://github.com/nearai/ironclaw/issues/3630) [Reborn WebUI Beta] Define gate, cancel, and resume DTO lifecycle
- [#3629](https://github.com/nearai/ironclaw/issues/3629) [Reborn WebUI Beta] Add M2 facade contract tests with fake turn and event ports
- [#3628](https://github.com/nearai/ironclaw/issues/3628) [Reborn WebUI Beta] Add stable WebUI facade error taxonomy
- [#3627](https://github.com/nearai/ironclaw/issues/3627) [Reborn WebUI Beta] Implement RebornServices submit/cancel/resolve facade methods
- [#3612](https://github.com/nearai/ironclaw/issues/3612) [Reborn WebUI Beta] Add WebUI-facing RebornServices facade

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 3d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬2 · 4d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 7d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 2 new
- [[News] Anthropic Kpmg](https://www.anthropic.com/news/anthropic-kpmg) _2026-05-19_
- [[News] Widening Conversation Ai](https://www.anthropic.com/news/widening-conversation-ai) _2026-05-20_

### OpenAI — 4 new
- [[Business] Guaranteed Capacity](https://openai.com/business/guaranteed-capacity/) _2026-05-20_
- [[Research] Verify](https://openai.com/research/verify/) _2026-05-20_
- [[Form] Guaranteed Capacity](https://openai.com/form/guaranteed-capacity/) _2026-05-19_
- [Deployco](https://openai.com/deployco/) _2026-05-19_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
