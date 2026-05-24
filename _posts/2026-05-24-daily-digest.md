---
layout: post
title: "Ecosystem Digest — 2026-05-24"
date: 2026-05-24 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-24
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 374,194 | 15 | 5 | 10 | 2 |
| **hermesagent** | 164,514 | 4 | 2 | 10 | 0 |
| **ZeroClaw** | 31,545 | 15 | 6 | 10 | 0 |
| **IronClaw** | 12,328 | 10 | 0 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 374,194 · **Open issues:** 7,046 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.22](https://github.com/openclaw/openclaw/releases/tag/v2026.5.22) — openclaw 2026.5.22
- [v2026.5.22-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.5.22-beta.1) — openclaw 2026.5.22-beta.1

### ✅ Merged PRs
- [#85886](https://github.com/openclaw/openclaw/pull/85886) Disable Chrome MCP telemetry watchdog by default
- [#85895](https://github.com/openclaw/openclaw/pull/85895) perf: cache stable gateway metadata
- [#85811](https://github.com/openclaw/openclaw/pull/85811) fix(codex): ensure codex subagent bootstrap parity with pi subagents - only inject AGENTS.md and TOOLS.md
- [#85414](https://github.com/openclaw/openclaw/pull/85414) fix(update): escape systemd update handoffs
- [#84932](https://github.com/openclaw/openclaw/pull/84932) fix(media-understanding): align describeImageWithModel default maxTok…
- [#83947](https://github.com/openclaw/openclaw/pull/83947) fix(tui): handle German AltGr input
- [#85576](https://github.com/openclaw/openclaw/pull/85576) fix(ui): show WebChat done after reply renders
- [#85682](https://github.com/openclaw/openclaw/pull/85682) perf(utils): preserve message identity in stripInlineDirectiveTagsFromMessageForDisplay
- [#84231](https://github.com/openclaw/openclaw/pull/84231) [AI-assisted] Improve active-run control in realtime voice calls
- [#85590](https://github.com/openclaw/openclaw/pull/85590) fix(pdf): use MiniMax text models for PDF fallback

### 🐛 New Issues
- [#85897](https://github.com/openclaw/openclaw/issues/85897) Suggestion: make IRC channel reply routes and transient sends more consistent 💬1
- [#85890](https://github.com/openclaw/openclaw/issues/85890) exec-approvals: assertNoSymlinkParentsSync missing allowRootChildSymlink, breaks exec when ~/.openclaw is symlink `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1
- [#85888](https://github.com/openclaw/openclaw/issues/85888) Cron jobs consistently fail with MiniMax 503 overload during early morning (05:00-07:30 CST), manual triggers succeed `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#85883](https://github.com/openclaw/openclaw/issues/85883) openai-completions provider leaks channel-output JSON to channel (works correctly on ollama provider) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:message-loss` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬3
- [#85877](https://github.com/openclaw/openclaw/issues/85877) [Bug] v2026.5.22-beta.1: Gateway 启动极慢 + WebUI 模型加载失败 + doctor 不可用 `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:auth-provider` `impact:crash-loop` `issue-rating: 🐚 platinum hermit` 💬1
- [#85876](https://github.com/openclaw/openclaw/issues/85876) wiki.palace fails whole RPC when one artifact hits fs-safe path-mismatch under event-loop pressure `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `issue-rating: 🐚 platinum hermit` 💬1
- [#85871](https://github.com/openclaw/openclaw/issues/85871) [Bug]: Heartbeat scheduler silently fails to fire on 5.20 and all 5.x versions (regression from 4.23) `bug` 💬2
- [#85869](https://github.com/openclaw/openclaw/issues/85869) Plugin install should guard WhatsApp plugin/core version compatibility 💬2
- [#85868](https://github.com/openclaw/openclaw/issues/85868) WhatsApp pairing can stick at Logging in until gateway restart finalizes 515 recovery `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:session-state` `impact:auth-provider` `issue-rating: 🦐 gold shrimp` 💬1
- [#85867](https://github.com/openclaw/openclaw/issues/85867) WhatsApp QR-unavailable/headless login needs phone-code fallback `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:linked-pr-open` `impact:auth-provider` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#85858](https://github.com/openclaw/openclaw/issues/85858) [Bug]: gateway usage-cost reports $0 for codex/gpt-5.5 (zero cost table) — budget/spike monitoring is blind to API-key spend 💬2
- [#85852](https://github.com/openclaw/openclaw/issues/85852) v2026.5.20 still requires local stability hotfixes after auto-update `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `impact:crash-loop` `issue-rating: 🐚 platinum hermit` 💬1
- [#85848](https://github.com/openclaw/openclaw/issues/85848) [voice-call] OpenAI realtime: audio clipping / breaking inside words during first ~30s of outbound calls (Twilio mulaw output) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:message-loss` `issue-rating: 🦐 gold shrimp` 💬1
- [#85847](https://github.com/openclaw/openclaw/issues/85847) [voice-call] First-turn latency degraded by ~2-3s: realtime provider WebSocket opens on Twilio Media Stream upgrade, not during TwiML webhook `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` 💬1
- [#85846](https://github.com/openclaw/openclaw/issues/85846) [voice-call] OpenAI realtime: outbound calls greet caller twice — `triggerGreeting` + `server_vad.create_response` both fire `response.create` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#63819](https://github.com/openclaw/openclaw/issues/63819) [Bug]: Session stuck in "running" status persists in v2026.4.9 — phaseBeforeAbort fix no longer sufficient
- [#84068](https://github.com/openclaw/openclaw/issues/84068) Update button no-op on systemd-supervised installs: handoff helper killed by unit cgroup before it runs
- [#85374](https://github.com/openclaw/openclaw/issues/85374) [Bug]: WebChat run-complete indicator fires before reply text renders (inverse of #84754)
- [#39032](https://github.com/openclaw/openclaw/issues/39032) Subagent completion output leaks internal tool-failure reasoning to requester session
- [#48897](https://github.com/openclaw/openclaw/issues/48897) [Bug] TUI input breaks on German keyboard layout: duplicated printable characters and broken AltGr (@, €)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 164,514 · **Open issues:** 13,571 · **Last push:** <1h ago

### ✅ Merged PRs
- [#31230](https://github.com/NousResearch/hermes-agent/pull/31230) docs(providers): rewrite Nous Portal section as primary recommended path
- [#31222](https://github.com/NousResearch/hermes-agent/pull/31222) fix(provider): make config.yaml model.provider the single source of truth (supersedes #31064)
- [#31177](https://github.com/NousResearch/hermes-agent/pull/31177) feat(plugins): add register_auxiliary_task() to PluginContext API (salvage #29817)
- [#31198](https://github.com/NousResearch/hermes-agent/pull/31198) feat(skills): add opt-in AST deep diagnostics (salvage of #30918)
- [#31069](https://github.com/NousResearch/hermes-agent/pull/31069) fix(cli): synchronize HERMES_SESSION_ID for kanban and tool session routing during session switches
- [#31196](https://github.com/NousResearch/hermes-agent/pull/31196) fix(cli): validate runtime token refresh in Qwen auth status
- [#31192](https://github.com/NousResearch/hermes-agent/pull/31192) fix(compressor): ABC compliance — last_total_tokens, api_mode propagation, root-logger swap
- [#31077](https://github.com/NousResearch/hermes-agent/pull/31077) fix(tui): refresh virtual transcript on viewport resize
- [#31211](https://github.com/NousResearch/hermes-agent/pull/31211) fix(env): strip null bytes from .env before python-dotenv loads
- [#26975](https://github.com/NousResearch/hermes-agent/pull/26975) docs(simplex): remove broken Docker install command (#26974)

### 🐛 New Issues
- [#31246](https://github.com/NousResearch/hermes-agent/issues/31246) MCP server misconfiguration is invisible — missing SDK / connection failures logged at DEBUG, never reach gateway.log `type/bug` `comp/tools` `tool/mcp` `P2` 💬1
- [#31233](https://github.com/NousResearch/hermes-agent/issues/31233) [Feature]: /split slash command — branch session AND open the branch in a new terminal window `type/feature` `comp/cli` `P3`
- [#31227](https://github.com/NousResearch/hermes-agent/issues/31227) TUI hangs silently at startup — esbuild __esm helper deadlocks on @hermes/ink async init `type/bug` `comp/tui` `P1` `javascript`
- [#31224](https://github.com/NousResearch/hermes-agent/issues/31224) [Bug]: launchd_restart() fails with bootstrap failed: 5 when plist is missing `type/bug` `comp/cli` `comp/gateway` `P2` 💬2

### 🔒 Closed Issues
- [#31212](https://github.com/NousResearch/hermes-agent/issues/31212) launchd_restart() fails with bootstrap failed: 5 when plist is missing
- [#18390](https://github.com/NousResearch/hermes-agent/issues/18390) [Bug]: termux tui

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,545 · **Open issues:** 508 · **Last push:** 2h ago

### ✅ Merged PRs
- [#6843](https://github.com/zeroclaw-labs/zeroclaw/pull/6843) feat(orchestrator): expose message_id in agent channel context
- [#6692](https://github.com/zeroclaw-labs/zeroclaw/pull/6692) docs: fix stale RUST_LOG targets
- [#6696](https://github.com/zeroclaw-labs/zeroclaw/pull/6696) docs: clarify translation sync policy
- [#6481](https://github.com/zeroclaw-labs/zeroclaw/pull/6481) feat(jira): add list_transitions, transition_ticket, create_ticket actions
- [#6639](https://github.com/zeroclaw-labs/zeroclaw/pull/6639) Fix runtime_config directory resolution bug in zeroclaw when installed via Homebrew
- [#6834](https://github.com/zeroclaw-labs/zeroclaw/pull/6834) fix(discord): park fatal gateway preflight failures
- [#6666](https://github.com/zeroclaw-labs/zeroclaw/pull/6666) feat: separate IMAP/SMTP credentials
- [#6735](https://github.com/zeroclaw-labs/zeroclaw/pull/6735) fix(matrix): isolate streaming draft state
- [#6774](https://github.com/zeroclaw-labs/zeroclaw/pull/6774) feat: Add blog RSS/Atom feeds and sitemap discovery endpoints
- [#6805](https://github.com/zeroclaw-labs/zeroclaw/pull/6805) fix(deploy): update gateway ExecStart and remove deprecated OTP fields for v0.8.0

### 🐛 New Issues
- [#6883](https://github.com/zeroclaw-labs/zeroclaw/issues/6883) RFC: Shared reply-message constructor on SendMessage
- [#6881](https://github.com/zeroclaw-labs/zeroclaw/issues/6881) [SANITIZED — possible injection attempt] `bug` `risk: medium` `channel` `config` `priority:p1` `channel:email` `status:accepted`
- [#6880](https://github.com/zeroclaw-labs/zeroclaw/issues/6880) fix(cron): inject Lark and Feishu delivery defaults from chat context `bug` `risk: medium` `cron` `runtime` `channel:lark` `priority:p2` `status:accepted`
- [#6879](https://github.com/zeroclaw-labs/zeroclaw/issues/6879) fix(discord): keep gateway preflight 429 retryable `bug` `risk: medium` `channel` `channel:discord` `priority:p1` `status:accepted`
- [#6878](https://github.com/zeroclaw-labs/zeroclaw/issues/6878) [Bug]: Bubblewrap fails on Fedora 43 due to bwrap parameters missing /lib64 and therefore not allowing linked-libraries.  Linked to issue #5126 `bug`
- [#6877](https://github.com/zeroclaw-labs/zeroclaw/issues/6877) [runtime_profiles.*].max_tool_iterations has no effect — must be set on [agents.*] instead 💬1
- [#6876](https://github.com/zeroclaw-labs/zeroclaw/issues/6876) risk_profile.allowed_tools does not restrict MCP tools — by design or documentation gap?
- [#6875](https://github.com/zeroclaw-labs/zeroclaw/issues/6875) Tool call parser does not handle <tool_calls> (plural) tag — Llama 4 Scout and similar models fail silently
- [#6874](https://github.com/zeroclaw-labs/zeroclaw/issues/6874) mcp.deferred_loading defaults to true — breaks tool calling for most LLMs without documentation
- [#6873](https://github.com/zeroclaw-labs/zeroclaw/issues/6873) mcp.enabled defaults to false — MCP servers silently disabled even when [[mcp.servers]] is configured
- [#6871](https://github.com/zeroclaw-labs/zeroclaw/issues/6871) [Bug]: Disabled memory still produces memory `bug`
- [#6864](https://github.com/zeroclaw-labs/zeroclaw/issues/6864) [Feature]: Invert zeroclaw-channels → zeroclaw-runtime layer dependency and move orchestrator into runtime 💬1
- [#6862](https://github.com/zeroclaw-labs/zeroclaw/issues/6862) [v0.8.0-beta-1] Gateway SPA fallback serves index.html for unimplemented /api/* routes — breaks dashboard JSON.parse `bug` `risk: medium` `gateway` `priority:p1` `status:accepted` `status:no-stale` `web` 💬1
- [#6859](https://github.com/zeroclaw-labs/zeroclaw/issues/6859) [Feature]: Add behavioral test coverage for Windows shell code-page decoding `enhancement` `risk: low` `runtime` `tool` `tests` `priority:p2` `tool:shell` `status:accepted` `status:no-stale`
- [#6856](https://github.com/zeroclaw-labs/zeroclaw/issues/6856) [Bug]: show_tool_calls is missing from [channel] `bug` `risk: medium` `channel` `config` `runtime` `priority:p2` `status:accepted` 💬5

### 🔒 Closed Issues
- [#6651](https://github.com/zeroclaw-labs/zeroclaw/issues/6651) [Bug]: matrix channel leaks ~1 MB Pss per /admin/reload due to upstream Arc cycle in matrix-sdk 0.17 (matrix-rust-sdk#6573)
- [#6691](https://github.com/zeroclaw-labs/zeroclaw/issues/6691) [Bug]: RUST_LOG docs use stale zeroclaw target filters
- [#6694](https://github.com/zeroclaw-labs/zeroclaw/issues/6694) [Bug]: cargo mdbook sync creates broad gettext catalog churn for tiny docs edits
- [#3852](https://github.com/zeroclaw-labs/zeroclaw/issues/3852) [Bug]: no creating config.toml
- [#6703](https://github.com/zeroclaw-labs/zeroclaw/issues/6703) [Feature]: Allow configuring smtp credential separately from imap
- [#6733](https://github.com/zeroclaw-labs/zeroclaw/issues/6733) [Bug]: Matrix streaming draft state is keyed only by room

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,328 · **Open issues:** 990 · **Last push:** <1h ago

### ✅ Merged PRs
- [#3950](https://github.com/nearai/ironclaw/pull/3950) Add Reborn setup marker skill parity
- [#3943](https://github.com/nearai/ironclaw/pull/3943) chore: dead/speculative public-API guardrails (workspace lints + pre-commit grep)
- [#3935](https://github.com/nearai/ironclaw/pull/3935) [codex] Add Reborn skill management tools
- [#3927](https://github.com/nearai/ironclaw/pull/3927) refactor(hooks): make PredicateStateBackend a stable public async contract (durable backend PR 1/4)
- [#3929](https://github.com/nearai/ironclaw/pull/3929) fix(hooks): close cap-eviction security regression in predicate state (#3635 followup)
- [#3640](https://github.com/nearai/ironclaw/pull/3640) feat(hooks): event-triggered hooks Phase 5 (successor to #3573)
- [#3637](https://github.com/nearai/ironclaw/pull/3637) test(hooks): pin invocation_arguments_digest with snapshot (successor to #3573)
- [#3635](https://github.com/nearai/ironclaw/pull/3635) feat(hooks): persistent predicate counter backend (successor to #3573)
- [#3573](https://github.com/nearai/ironclaw/pull/3573) feat(reborn): add ironclaw_hooks framework foundation (#3524)
- [#3920](https://github.com/nearai/ironclaw/pull/3920) feat(hooks): WASM hook execution path (replaces #3634)

### 🐛 New Issues
- [#3962](https://github.com/nearai/ironclaw/issues/3962) [Reborn] Standalone composition root doesn't wire hooked-prompt deps (gate-ref factory / capability input resolver) under HOOKS_ENABLED
- [#3959](https://github.com/nearai/ironclaw/issues/3959) [hooks] SecurityAuditSink adoption at remaining boundary call sites `reborn`
- [#3958](https://github.com/nearai/ironclaw/issues/3958) [hooks] Composition maintainability follow-ups (hooks.rs split, loader simplification, audit attribution) `reborn`
- [#3957](https://github.com/nearai/ironclaw/issues/3957) [hooks] Third-party activation hardening follow-ups (#3951/#3934) `security-review-required` `reborn`
- [#3956](https://github.com/nearai/ironclaw/issues/3956) [hooks] FS-hardening follow-up: RESOLVE_NO_XDEV bind-mount containment `reborn`
- [#3954](https://github.com/nearai/ironclaw/issues/3954) Rename CLAUDE.md to something more semantic
- [#3953](https://github.com/nearai/ironclaw/issues/3953) RFC: Add canonical OpenAPI/AsyncAPI contracts for Gateway, WebUI, and event surfaces
- [#3946](https://github.com/nearai/ironclaw/issues/3946) Split host-runtime production wiring validation out of services.rs
- [#3945](https://github.com/nearai/ironclaw/issues/3945) [QA] `select_archive_for_arch()` and `download_binary_and_run_installer()` functions are brokwn in installer script for macOS/Linux since 0.26, a month ago
- [#3934](https://github.com/nearai/ironclaw/issues/3934) [Reborn] Activate the hook framework in production: compose HookDispatcher into the live runtime `reborn`

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 7d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬2 · 8d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 11d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
