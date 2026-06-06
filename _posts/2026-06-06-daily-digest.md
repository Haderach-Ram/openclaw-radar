---
layout: post
title: "Ecosystem Digest — 2026-06-06"
date: 2026-06-06 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-06
*Generated 07:51 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 377,122 | 11 | 7 | 10 | 0 |
| **hermesagent** | 183,219 | 8 | 0 | 9 | 1 |
| **ZeroClaw** | 31,780 | 8 | 4 | 10 | 0 |
| **IronClaw** | 12,397 | 7 | 2 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 377,122 · **Open issues:** 7,808 · **Last push:** <1h ago

### ✅ Merged PRs
- [#90697](https://github.com/openclaw/openclaw/pull/90697) fix(llm): defer Anthropic stream start event until after message_start
- [#90728](https://github.com/openclaw/openclaw/pull/90728) fix(agents): coerce non-text/image MCP tool-result blocks to text (fixes #90710)
- [#90607](https://github.com/openclaw/openclaw/pull/90607) fix(voice-call): track Twilio streams after connect
- [#89566](https://github.com/openclaw/openclaw/pull/89566) fix(telegram): suppress post-final tool error noise
- [#90027](https://github.com/openclaw/openclaw/pull/90027) test(codex): pin completion-idle timeout thread reset
- [#90775](https://github.com/openclaw/openclaw/pull/90775) fix: refresh prompt fence after compaction writes
- [#90609](https://github.com/openclaw/openclaw/pull/90609) fix(google): preserve Vertex ADC catalog auth
- [#90717](https://github.com/openclaw/openclaw/pull/90717) fix(agents): re-probe single-provider primary during cooldown
- [#74980](https://github.com/openclaw/openclaw/pull/74980) build(deps): bump docker/login-action from 3.6.0 to 4.1.0
- [#86481](https://github.com/openclaw/openclaw/pull/86481) chore(deps): bump the android-deps group across 1 directory with 9 updates

### 🐛 New Issues
- [#90810](https://github.com/openclaw/openclaw/issues/90810) [Bug]: Prompt cache invalidated on every user turn on full-resend transports — transient timestamp + content-form decoration on the current user message (regression from #3658)
- [#90806](https://github.com/openclaw/openclaw/issues/90806) [Bug]: uninstall documentation nukes cwd `bug` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:data-loss` `P0` `issue-rating: 🦞 diamond lobster` 💬1
- [#90804](https://github.com/openclaw/openclaw/issues/90804) [Bug]: 飞书发图片或文件 常常出问题 要么不会发，要么重复发 `bug` `bug:crash` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:message-loss` `issue-rating: 🦪 silver shellfish` 💬1
- [#90801](https://github.com/openclaw/openclaw/issues/90801) [Bug]: memory status shows inconsistent Dirty state, watcher stops auto-indexing, and --deep required to confirm health on 2026.6.1 `bug` `regression` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬1
- [#90800](https://github.com/openclaw/openclaw/issues/90800) Chinese IME (Input Method) causes severe typing lag in webchat input `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#90789](https://github.com/openclaw/openclaw/issues/90789) [Bug] claude-cli backend: synthetic "No response requested." placeholder leaves Telegram turn fully silent with no observability `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬3
- [#90787](https://github.com/openclaw/openclaw/issues/90787) [Bug]: memorySearch provider silently resets to "openai" after upgrade to 2026.6.1, causing permanent Dirty index and vector search outage `bug` `regression` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#90786](https://github.com/openclaw/openclaw/issues/90786) [Bug]: memory status --index and --deep fail with "Unknown memory embedding provider: google" on 2026.6.1 `bug` `regression` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬3
- [#90783](https://github.com/openclaw/openclaw/issues/90783) [Bug]: memory pressure WARN is non-actionable — no units, no breakdown, no operator guidance, no self-heal, and log level disagrees with payload `P3` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#90781](https://github.com/openclaw/openclaw/issues/90781) [Bug]: memory-core narrative generation silently produces no text and writes fallback diary entries (light/rem/deep phases) 💬1
- [#90778](https://github.com/openclaw/openclaw/issues/90778) Gmail hook delivery verification fails even when message tool uses Telegram target `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#90667](https://github.com/openclaw/openclaw/issues/90667) [Bug]: Extended thinking sessions permanently broken after gateway restart / cache miss — no recovery for research agents
- [#90710](https://github.com/openclaw/openclaw/issues/90710) convertContentBlocks coerces MCP resource_link/resource/audio blocks into malformed image blocks -> Anthropic 400 -> poisoned session history
- [#81122](https://github.com/openclaw/openclaw/issues/81122) Bug: Twilio voice-call can get stuck in hold music after failed/no-stream call
- [#90796](https://github.com/openclaw/openclaw/issues/90796) [Bug]: [Windows] gateway run does not exit after shutdown; EADDRINUSE every restart
- [#90729](https://github.com/openclaw/openclaw/issues/90729) EmbeddedAttemptSessionTakeoverError: auto-compaction at reason=threshold trips fence on rewritten session jsonl
- [#90784](https://github.com/openclaw/openclaw/issues/90784) [Bug]: Matrix progress streaming can leave preview edits in the room while the final answer exists only in session history
- [#90777](https://github.com/openclaw/openclaw/issues/90777) [Bug]: channels.feishu streaming drops intermediate/final frames on Feishu multi-client (PC + mobile)

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 10d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 183,219 · **Open issues:** 18,295 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.5](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.6.5) — Hermes Agent v0.16.0 (2026.6.5) — The Surface Release

### ✅ Merged PRs
- [#40240](https://github.com/NousResearch/hermes-agent/pull/40240) feat: usable mid-turn steer — desktop affordance + trusted injection
- [#39485](https://github.com/NousResearch/hermes-agent/pull/39485) fix(line): map inbound message types to the correct MessageType
- [#40235](https://github.com/NousResearch/hermes-agent/pull/40235) fix(tui): clean force-send of queued messages
- [#40234](https://github.com/NousResearch/hermes-agent/pull/40234) feat(desktop): arrow-key history + queue editing in composer
- [#40221](https://github.com/NousResearch/hermes-agent/pull/40221) fix(desktop): reliable composer message queue
- [#40214](https://github.com/NousResearch/hermes-agent/pull/40214) feat: add /version slash command (salvage #40202)
- [#40217](https://github.com/NousResearch/hermes-agent/pull/40217) fix(desktop): repair macOS updater helper
- [#40210](https://github.com/NousResearch/hermes-agent/pull/40210) fix(desktop): show send button for committed IME text (Chinese/Japanese/Korean)
- [#40209](https://github.com/NousResearch/hermes-agent/pull/40209) fix(desktop): avoid restricted OAuth Content-Length header (salvage #40055)

### 🐛 New Issues
- [#40251](https://github.com/NousResearch/hermes-agent/issues/40251) ❤️ 一个中国用户的感谢信：Hermes 的 skill/memory 系统让我看到了 AI Agent 真正的可成长性
- [#40250](https://github.com/NousResearch/hermes-agent/issues/40250) [Bug]: Terminal escape sequences leaking into response output, causing first 1-3 characters to be cut
- [#40239](https://github.com/NousResearch/hermes-agent/issues/40239) [Feature]: Add Portuguese (pt-BR) language support to the desktop app (i18n / localization) 💬2
- [#40232](https://github.com/NousResearch/hermes-agent/issues/40232) Schema sanitizer should strip/rename property keys with invalid characters for strict backends
- [#40227](https://github.com/NousResearch/hermes-agent/issues/40227) Issue: Hindsight 插件与 hindsight_embed 包 API 不兼容 `type/bug` `comp/plugins` `tool/memory` `P3`
- [#40226](https://github.com/NousResearch/hermes-agent/issues/40226) Desktop app: Chinese IME input breaks composer - text not synced, Enter doesn't send `type/bug` `P3`
- [#40225](https://github.com/NousResearch/hermes-agent/issues/40225) fix(feishu): card approval buttons use _allow_group_message instead of _is_interactive_operator_authorized, rejecting all users in DM `type/bug` `comp/gateway` `platform/feishu` `P2`
- [#40219](https://github.com/NousResearch/hermes-agent/issues/40219) [Feature]: Add Japanese language support (i18n / localization) `type/feature` `comp/tui` `P3` 💬4

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,780 · **Open issues:** 516 · **Last push:** 3h ago

### ✅ Merged PRs
- [#7188](https://github.com/zeroclaw-labs/zeroclaw/pull/7188) fix(cron): support relative after schedules
- [#7090](https://github.com/zeroclaw-labs/zeroclaw/pull/7090) fix(hardware): robustly resolve embedded firmware paths via CARGO_MANIFEST_DIR
- [#7224](https://github.com/zeroclaw-labs/zeroclaw/pull/7224) fix(ollama): pass defaulted temperature as option
- [#7047](https://github.com/zeroclaw-labs/zeroclaw/pull/7047) fix(hardware): surface pin_devices and description in hardware_capabilities tool
- [#7017](https://github.com/zeroclaw-labs/zeroclaw/pull/7017) refactor(channels/whatsapp_web): share allowlist matching via crate::allowlist
- [#7226](https://github.com/zeroclaw-labs/zeroclaw/pull/7226) fix(channels/whatsapp-web): treat replies to bot as mentions
- [#7161](https://github.com/zeroclaw-labs/zeroclaw/pull/7161) docs(setup): add FreeBSD setup guide + installable rc.d/jail dist files
- [#7109](https://github.com/zeroclaw-labs/zeroclaw/pull/7109) fix(qq): restore audio attachment transcription
- [#7219](https://github.com/zeroclaw-labs/zeroclaw/pull/7219) fix(web): cover ApprovalBanner and error banner in translate="no" guard
- [#7132](https://github.com/zeroclaw-labs/zeroclaw/pull/7132) chore(docs): scrub stale "zeroclaw onboard" references across docs, scripts, channels, providers, and runtime

### 🐛 New Issues
- [#7271](https://github.com/zeroclaw-labs/zeroclaw/issues/7271) [Bug]: Config writer leaves stale schema_version on partial saves → V3-bodied/schema-2 configs crash older binaries with opaque "missing field provider" `bug`
- [#7269](https://github.com/zeroclaw-labs/zeroclaw/issues/7269) bug(docs): clean up docs build warning noise `bug` `risk: low` `docs`
- [#7266](https://github.com/zeroclaw-labs/zeroclaw/issues/7266) [Bug]: DelegateTool can inherit parent provider endpoint/runtime options for explicit sub-agent aliases `bug` `risk: high` `config` `provider` `runtime` `security` `priority:p1`
- [#7263](https://github.com/zeroclaw-labs/zeroclaw/issues/7263) [Bug]: Subagents do not inherit "cwd" in ACP sessions `bug`
- [#7259](https://github.com/zeroclaw-labs/zeroclaw/issues/7259) test(channels/telegram): make empty document send-path test local-only `bug` `size: S` `risk: low` `channel` `tests` `channel:telegram`
- [#7253](https://github.com/zeroclaw-labs/zeroclaw/issues/7253) [Bug]: Web console - Config: Couldn't load sections `bug`
- [#7252](https://github.com/zeroclaw-labs/zeroclaw/issues/7252) [Bug]: session/kill can rehydrate killed ACP sessions from durable history `bug` `risk: high` `daemon` `runtime` `priority:p1`
- [#7250](https://github.com/zeroclaw-labs/zeroclaw/issues/7250) [Bug]: scheduler.catch_up_on_startup = false still runs overdue cron jobs after startup `bug` `risk: high` `cron` `runtime` `priority:p2`

### 🔒 Closed Issues
- [#6280](https://github.com/zeroclaw-labs/zeroclaw/issues/6280) [Bug]: Windows full build fails: zeroclaw-hardware compilation errors
- [#7128](https://github.com/zeroclaw-labs/zeroclaw/issues/7128) chore: scrub stale `zeroclaw onboard` references after #6848 deletion
- [#6120](https://github.com/zeroclaw-labs/zeroclaw/issues/6120) [Bug]: Onboarding: choosing OpenAI Codex prompts for OpenAI API key instead
- [#5882](https://github.com/zeroclaw-labs/zeroclaw/issues/5882) [Feature]: Ratatui-based agent mode REPL

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,397 · **Open issues:** 1,105 · **Last push:** 1h ago

### ✅ Merged PRs
- [#3951](https://github.com/nearai/ironclaw/pull/3951) feat(hooks): third-party extension hook activation via hook-only projection (HOOKS_THIRD_PARTY_ENABLED, default OFF)
- [#3941](https://github.com/nearai/ironclaw/pull/3941) fix(hooks): address dropped #3918/#3919 maintainability follow-ups (dead API, vacuous test, under-exposed const)
- [#3938](https://github.com/nearai/ironclaw/pull/3938) feat(hooks): activate hook framework in production behind HOOKS_ENABLED flag (#3934)
- [#3937](https://github.com/nearai/ironclaw/pull/3937) test(hooks): cross-backend adversarial parity suite + A3 closeout (durable backend PR 4/4)
- [#3936](https://github.com/nearai/ironclaw/pull/3936) feat(hooks): LibSqlPredicateStateBackend in own crate (durable backend PR 3/4, replaces #3930)
- [#3933](https://github.com/nearai/ironclaw/pull/3933) feat(hooks): PostgresPredicateStateBackend (durable backend PR 2/4, replaces #3932)
- [#3931](https://github.com/nearai/ironclaw/pull/3931) fix(hooks): close cross-tenant leakage + replay + provider spoofing in event-triggered (#3640 followup)
- [#3928](https://github.com/nearai/ironclaw/pull/3928) test(hooks): drive arguments_digest snapshot through invoke_capability (#3637 followup)
- [#3922](https://github.com/nearai/ironclaw/pull/3922) feat: wire SecurityAuditSink into obligation handler + hook deny paths
- [#4497](https://github.com/nearai/ironclaw/pull/4497) [codex] Add NEAR onboarding setup menu

### 🐛 New Issues
- [#4512](https://github.com/nearai/ironclaw/issues/4512) Concurrent sandbox job_semaphore is never acquired
- [#4505](https://github.com/nearai/ironclaw/issues/4505) [sub-issue] WeCom Group conversation titles are not distinguishable in the Web UI sidebar `enhancement`
- [#4502](https://github.com/nearai/ironclaw/issues/4502) [sub-issue] WeCom group chat approval reply does not work `bug` 💬1
- [#4500](https://github.com/nearai/ironclaw/issues/4500) Channel onboarding system event is written to the wrong conversation `bug`
- [#4491](https://github.com/nearai/ironclaw/issues/4491) Use Slack AI streaming for Reborn Slack progress
- [#4488](https://github.com/nearai/ironclaw/issues/4488) [Reborn] Split ProductWorkflow into explicit submit/read/subscribe doors `reborn` `module:M2-inbound-workflow` 💬2
- [#4483](https://github.com/nearai/ironclaw/issues/4483) [Reborn] Harden ProductWorkflow submit/projection boundary for OpenAI wiring `reborn` `module:M2-inbound-workflow`

### 🔒 Closed Issues
- [#3934](https://github.com/nearai/ironclaw/issues/3934) [Reborn] Activate the hook framework in production: compose HookDispatcher into the live runtime
- [#4194](https://github.com/nearai/ironclaw/issues/4194) [sub-issue] Group chat and private DM are merged into the same Web UI conversation

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 22h ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 1d ago
- ⚫ [#88967](https://github.com/openclaw/openclaw/issues/88967) Telegram: allowBots support for group chats (bot-authored messages not ingested into session) — 💬1 · 1d ago
- ⚫ [#88517](https://github.com/openclaw/openclaw/issues/88517) [SANITIZED — possible injection attempt] — 💬3 · 2d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 3d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 3d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬5 · 5d ago
- ⚫ [#86371](https://github.com/openclaw/openclaw/issues/86371) Bug: message tool filePath fails with LocalMediaAccessError in retry flows when agentId is not propagated — 💬1 · 8d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 11d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 24d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Research] Making Claude A Chemist](https://www.anthropic.com/research/making-claude-a-chemist) _2026-06-05_

### OpenAI — 1 new
- [[Products] Release Notes](https://openai.com/products/release-notes/) _2026-06-05_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
