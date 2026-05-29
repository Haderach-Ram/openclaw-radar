---
layout: post
title: "Ecosystem Digest — 2026-05-29"
date: 2026-05-29 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-29
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 375,319 | 7 | 5 | 10 | 2 |
| **hermesagent** | 171,680 | 6 | 6 | 10 | 2 |
| **ZeroClaw** | 31,623 | 9 | 1 | 4 | 0 |
| **IronClaw** | 12,367 | 15 | 3 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 375,319 · **Open issues:** 7,012 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.27](https://github.com/openclaw/openclaw/releases/tag/v2026.5.27) — openclaw 2026.5.27
- [v2026.5.27-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.5.27-beta.1) — openclaw 2026.5.27-beta.1

### ✅ Merged PRs
- [#87640](https://github.com/openclaw/openclaw/pull/87640) fix(context-engine): quarantine broken plugin engines
- [#87842](https://github.com/openclaw/openclaw/pull/87842) chore: rename dependency guard workflow
- [#87797](https://github.com/openclaw/openclaw/pull/87797) refactor: extract gateway client package
- [#87791](https://github.com/openclaw/openclaw/pull/87791) feat(ci): guard dependency graph changes in PRs
- [#87833](https://github.com/openclaw/openclaw/pull/87833) fix: probe stale rate-limit cooldown primaries
- [#87812](https://github.com/openclaw/openclaw/pull/87812) [SANITIZED — possible injection attempt]
- [#87832](https://github.com/openclaw/openclaw/pull/87832) ci: restore timing summary artifact
- [#84224](https://github.com/openclaw/openclaw/pull/84224) fix(doctor): handle gateway SecretRefs in auth checks
- [#87222](https://github.com/openclaw/openclaw/pull/87222) fix(ui): scope usage requests by agent filter
- [#87559](https://github.com/openclaw/openclaw/pull/87559) fix(auth): harden Codex auth probes

### 🐛 New Issues
- [#87854](https://github.com/openclaw/openclaw/issues/87854) Memory Dreaming Promotion: candidates found but applied=0 (rehydratePromotionCandidate returns null for all) 💬1
- [#87847](https://github.com/openclaw/openclaw/issues/87847) Telegram isolated polling spool drain: ENOENT race in recoverStaleTelegramSpooledUpdateClaims `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` 💬1
- [#87830](https://github.com/openclaw/openclaw/issues/87830) [Bug]: Persistent ACP session resume fails for Kiro threads after backend invalidation `P1` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬1
- [#87821](https://github.com/openclaw/openclaw/issues/87821) [Bug]: Isolated cron runs can wedge gateway `bug` `bug:crash` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:crash-loop` `issue-rating: 🦪 silver shellfish` 💬1
- [#87816](https://github.com/openclaw/openclaw/issues/87816) feat(tts): xiaomi voicedesign/voiceclone model support `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#87815](https://github.com/openclaw/openclaw/issues/87815) [Bug]: status --deep falsely reports gateway.auth.mode="none" when token auth is configured via secret reference `bug` `bug:behavior` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:security` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#87808](https://github.com/openclaw/openclaw/issues/87808) [Bug]: Gateway restart during active embedded Codex WebChat turn drops final reply and only logs client closed before turn completed `bug` `P2` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬1

### 🔒 Closed Issues
- [#87846](https://github.com/openclaw/openclaw/issues/87846) [Bug]: doctor --lint falsely reports SecretRef-managed gateway.auth.token as unavailable
- [#87837](https://github.com/openclaw/openclaw/issues/87837) feat(feishu): log outbound message delivery result (message_id or error) after Feishu API call
- [#87608](https://github.com/openclaw/openclaw/issues/87608) [Bug] Ollama Cloud rate-limit cooldown permanently blocks agents — not released after API recovery
- [#87807](https://github.com/openclaw/openclaw/issues/87807) [SANITIZED — possible injection attempt]
- [#87132](https://github.com/openclaw/openclaw/issues/87132) [Bug]: Usage page agent filter broken since v2026.5.17 – sessions.usage API always scoped to "main" agent

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 2d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 171,680 · **Open issues:** 14,770 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.29](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.5.29) — Hermes Agent v0.15.1 (2026.5.29) — The Patch Release
- [v2026.5.28](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.5.28) — Hermes Agent v0.15.0 (2026.5.28) — The Velocity Release

### ✅ Merged PRs
- [#34244](https://github.com/NousResearch/hermes-agent/pull/34244) feat(kanban): default_assignee fallback + per-profile concurrency cap (closes #27145, closes #21582)
- [#34236](https://github.com/NousResearch/hermes-agent/pull/34236) docs(docker): refresh user-guide page for s6-overlay reality
- [#33645](https://github.com/NousResearch/hermes-agent/pull/33645) fix(docker): container reuse + bounded-sync cleanup + orphan reaper (#20561)
- [#34217](https://github.com/NousResearch/hermes-agent/pull/34217) test(tui_gateway): stop reloading server module in fixture teardown
- [#34222](https://github.com/NousResearch/hermes-agent/pull/34222) chore: release v0.15.1 (2026.5.29)
- [#34210](https://github.com/NousResearch/hermes-agent/pull/34210) feat(kanban): attach images referenced in task bodies to worker vision
- [#30698](https://github.com/NousResearch/hermes-agent/pull/30698) refactor(web): consume DS primitives, remove local component copies
- [#34204](https://github.com/NousResearch/hermes-agent/pull/34204) test(docker): repair dashboard tests broken by the insecure-opt-in fix
- [#34194](https://github.com/NousResearch/hermes-agent/pull/34194) fix(skills-page): restore per-source pills and category sidebar (stale useMemo deps)
- [#34186](https://github.com/NousResearch/hermes-agent/pull/34186) fix(mcp): resolve bare npx/npm/node against /usr/local/bin

### 🐛 New Issues
- [#34260](https://github.com/NousResearch/hermes-agent/issues/34260) MCP OAuth callback: module-level port global causes port collisions and structural weaknesses vs upstream
- [#34256](https://github.com/NousResearch/hermes-agent/issues/34256) Custom endpoint pricing can overestimate Crof qwen3.5-9b cost by 1,000,000x
- [#34253](https://github.com/NousResearch/hermes-agent/issues/34253) fix(gateway): Feishu session cancellation orphans session guard, permanently blocking messages
- [#34252](https://github.com/NousResearch/hermes-agent/issues/34252) fix: atomic_replace() fails with EXDEV when HERMES_HOME is a cross-filesystem symlink
- [#34246](https://github.com/NousResearch/hermes-agent/issues/34246) [Bug]: Custom endpoint: ChatCompletions returns content, but Hermes treats response as empty (v0.14.0) `type/bug` `comp/agent` `provider/openai` `P2`
- [#34237](https://github.com/NousResearch/hermes-agent/issues/34237) Skills hub creates empty category directories when no skills installed `type/bug` `tool/skills` `P3`

### 🔒 Closed Issues
- [#24329](https://github.com/NousResearch/hermes-agent/issues/24329) Kanban: surface non-runnable ready tasks and unknown assignees
- [#27145](https://github.com/NousResearch/hermes-agent/issues/27145) feat(kanban): auto-assign unassigned ready tasks in dispatcher
- [#21582](https://github.com/NousResearch/hermes-agent/issues/21582) [Feature]: limit tasks per profile in kanban
- [#20561](https://github.com/NousResearch/hermes-agent/issues/20561) Bug: Docker containers accumulate - /stop doesn't clean, multiple per session, async race
- [#34202](https://github.com/NousResearch/hermes-agent/issues/34202) Dashboard infinite reload loop in loopback mode — GET /api/auth/me returns 401 on every page load
- [#34206](https://github.com/NousResearch/hermes-agent/issues/34206) [Bug]: Infinite reload loop / React state loop on Sessions tab (Firefox + Chrome) — repeated 401 on /api/auth/me (v0.15.0)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,623 · **Open issues:** 533 · **Last push:** 3h ago

### ✅ Merged PRs
- [#6908](https://github.com/zeroclaw-labs/zeroclaw/pull/6908) fix(onboard): add Codex subscription auth for OpenAI provider
- [#6382](https://github.com/zeroclaw-labs/zeroclaw/pull/6382) docs(channels): reconcile against schema and fix stale CLI refs
- [#6980](https://github.com/zeroclaw-labs/zeroclaw/pull/6980) fix(provider): preserve reasoning_content in native tool requests
- [#6913](https://github.com/zeroclaw-labs/zeroclaw/pull/6913) fix(config): use platform-agnostic paths in policy tests

### 🐛 New Issues
- [#6996](https://github.com/zeroclaw-labs/zeroclaw/issues/6996) RFC: Granular sandbox policy — filesystem and network restrictions `enhancement`
- [#6995](https://github.com/zeroclaw-labs/zeroclaw/issues/6995) [Bug]: Backspace in `zeroclaw agent` CLI deletes byte-by-byte instead of character-by-character (UTF-8 CJK chars need 3 backspaces) `bug`
- [#6992](https://github.com/zeroclaw-labs/zeroclaw/issues/6992) [Bug]: Slack Socket Mode rejects all messages as "unauthorized user" `bug`
- [#6991](https://github.com/zeroclaw-labs/zeroclaw/issues/6991) bug(runtime): Native tool serialization (tools_to_openai_format) ignores Risk Profile and Tool Filter restrictions in v0.8.0-beta-1 `bug`
- [#6990](https://github.com/zeroclaw-labs/zeroclaw/issues/6990) i18n: bring new file_download tool strings under the fl!() / Fluent contract
- [#6989](https://github.com/zeroclaw-labs/zeroclaw/issues/6989) config: extend #[secret] (or add a header-token field) so headers maps redact bearer tokens
- [#6984](https://github.com/zeroclaw-labs/zeroclaw/issues/6984) bug(gateway): token rotation does not revoke existing bearer tokens `bug` `risk: high` `gateway` `security` `security:pairing` `priority:p1`
- [#6976](https://github.com/zeroclaw-labs/zeroclaw/issues/6976) [Bug]: Web UI WebSocket chat fails with 1006 — missing `?agent=` query parameter `bug` `risk: low` `gateway` `gateway: ws` `priority:p2` `status:in-progress` `status:no-stale` `web` 💬1
- [#6975](https://github.com/zeroclaw-labs/zeroclaw/issues/6975) [Bug]: `zeroclaw onboard` marks agents/profiles sections complete without writing config `bug` `risk: low` `config` `onboard` `status:blocked` `status:no-stale` `priority:p3` 💬1

### 🔒 Closed Issues
- [#6147](https://github.com/zeroclaw-labs/zeroclaw/issues/6147) [Bug]: anthropic.rs has same temperature: f64 shape as Bedrock pre-#6144 — verify whether native Anthropic API rejects for opus-4-7

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,367 · **Open issues:** 1,054 · **Last push:** <1h ago

### ✅ Merged PRs
- [#4221](https://github.com/nearai/ironclaw/pull/4221) ci(nearai-bench): scope id-token: write to the bench job
- [#4220](https://github.com/nearai/ironclaw/pull/4220) ci(nearai-bench): grant id-token: write so @main resolves
- [#4218](https://github.com/nearai/ironclaw/pull/4218) Allow extension search without query
- [#4217](https://github.com/nearai/ironclaw/pull/4217) ci(nearai-bench): track @main instead of pinning to a SHA
- [#4212](https://github.com/nearai/ironclaw/pull/4212) [codex] Project skill activations to WebUI
- [#4211](https://github.com/nearai/ironclaw/pull/4211) fix(reborn): truncate glob scan budget results
- [#3903](https://github.com/nearai/ironclaw/pull/3903) [codex] Close Reborn production credential boundary gaps
- [#4196](https://github.com/nearai/ironclaw/pull/4196) feat(reborn): expose work summary projections
- [#4210](https://github.com/nearai/ironclaw/pull/4210) [codex] classify invalid tool input as model error
- [#4208](https://github.com/nearai/ironclaw/pull/4208) [codex] tighten builtin HTTP input diagnostics

### 🐛 New Issues
- [#4222](https://github.com/nearai/ironclaw/issues/4222) Zeroize injected HTTP credential material across network request carriers
- [#4215](https://github.com/nearai/ironclaw/issues/4215) [Reborn] Consolidate duplicated PKCE math into ironclaw_common::pkce (Track A) `reborn` `module:M4-host-kernel`
- [#4209](https://github.com/nearai/ironclaw/issues/4209) [Reborn] Decompose ironclaw_host_runtime/src/lib.rs (1828 lines) — extract egress modules before auth credential work `reborn` 💬1
- [#4206](https://github.com/nearai/ironclaw/issues/4206) Make runtime HTTP egress async end to end
- [#4205](https://github.com/nearai/ironclaw/issues/4205) Follow up auth gate read-model wiring and run-state reuse
- [#4204](https://github.com/nearai/ironclaw/issues/4204) WebChat v2 SSO: GitHub + NEAR providers + CLI OAuthRouterConfig wire-up (#4116 follow-up) `reborn`
- [#4203](https://github.com/nearai/ironclaw/issues/4203) Reborn: product-adapter credential path-injection bridge (Telegram bot token via host egress) `reborn`
- [#4202](https://github.com/nearai/ironclaw/issues/4202) Reborn: harden OAuth callback token cleanup (durable/crash-safe + restart-safe replay) `reborn` 💬1
- [#4201](https://github.com/nearai/ironclaw/issues/4201) Reborn: product-facing auth HTTP surfaces (manual-token, recovery, refresh, cleanup) `reborn`
- [#4198](https://github.com/nearai/ironclaw/issues/4198) [sub-issue] Owner visibility for unpaired users is unclear
- [#4197](https://github.com/nearai/ironclaw/issues/4197) [sub-issue] Vision analysis resolves incorrect/stale images
- [#4195](https://github.com/nearai/ironclaw/issues/4195) [sub-issue] WeCom image attachments are unstable / inconsistent
- [#4194](https://github.com/nearai/ironclaw/issues/4194) [sub-issue] Group chat and private DM are merged into the same Web UI conversation
- [#4193](https://github.com/nearai/ironclaw/issues/4193) [sub-issue] WeCom setup UX lacks onboarding/prerequisite guidance
- [#4191](https://github.com/nearai/ironclaw/issues/4191) [v0.29.0][Staging] WeCom Channel Validation Findings

### 🔒 Closed Issues
- [#4085](https://github.com/nearai/ironclaw/issues/4085) [Reborn] RESOLVED by #3887 — production builders now require TenantSandboxProcessPort from caller
- [#4161](https://github.com/nearai/ironclaw/issues/4161) Follow up: refactor Google OAuth adapter boundaries
- [#4113](https://github.com/nearai/ironclaw/issues/4113) Reborn GSuite: implement Google token refresh and account health

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#86371](https://github.com/openclaw/openclaw/issues/86371) Bug: message tool filePath fails with LocalMediaAccessError in retry flows when agentId is not propagated — 💬1 · 21h ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬2 · 1d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 3d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 12d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬2 · 13d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 16d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 3 new
- [[News] Claude Opus 4 8](https://www.anthropic.com/news/claude-opus-4-8) _2026-05-28_
- [[News] Milan Office Opening](https://www.anthropic.com/news/milan-office-opening) _2026-05-28_
- [[News] Series H](https://www.anthropic.com/news/series-h) _2026-05-28_

### OpenAI — 2 new
- [[Index] Endava](https://openai.com/index/endava/) _2026-05-29_
- [[Index] Chip Ganassi Racing](https://openai.com/index/chip-ganassi-racing/) _2026-05-28_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
