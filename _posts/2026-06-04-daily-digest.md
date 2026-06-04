---
layout: post
title: "Ecosystem Digest — 2026-06-04"
date: 2026-06-04 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-04
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 376,607 | 11 | 9 | 10 | 3 |
| **hermesagent** | 179,251 | 6 | 3 | 10 | 0 |
| **ZeroClaw** | 31,724 | 9 | 3 | 2 | 0 |
| **IronClaw** | 12,395 | 15 | 5 | 10 | 1 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 376,607 · **Open issues:** 7,459 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.2-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.6.2-beta.1) — openclaw 2026.6.2-beta.1
- [v2026.6.1](https://github.com/openclaw/openclaw/releases/tag/v2026.6.1) — openclaw 2026.6.1
- [v2026.6.1-beta.3](https://github.com/openclaw/openclaw/releases/tag/v2026.6.1-beta.3) — openclaw 2026.6.1-beta.3

### ✅ Merged PRs
- [#90053](https://github.com/openclaw/openclaw/pull/90053) fix: hide Skill Workshop revision handoff from chat
- [#88585](https://github.com/openclaw/openclaw/pull/88585) Pin official npm plugin install records
- [#90067](https://github.com/openclaw/openclaw/pull/90067) fix(workboard): isolate stale lifecycle bulk patches
- [#89600](https://github.com/openclaw/openclaw/pull/89600) Fix Workboard status persistence
- [#90028](https://github.com/openclaw/openclaw/pull/90028) docs: clarify legacy openai-codex auth
- [#89102](https://github.com/openclaw/openclaw/pull/89102) refactor(auth): store auth profiles in SQLite
- [#81422](https://github.com/openclaw/openclaw/pull/81422) fix(update): surface plugin channel fallbacks
- [#88964](https://github.com/openclaw/openclaw/pull/88964) fix(agents): repair context-engine tool-result pairing
- [#89176](https://github.com/openclaw/openclaw/pull/89176) fix(browser): honor tab timeout for Chrome MCP
- [#90043](https://github.com/openclaw/openclaw/pull/90043) fix: restore Skill Workshop current chat toggle

### 🐛 New Issues
- [#90113](https://github.com/openclaw/openclaw/issues/90113) Regression: OpenClaw 2026.6.1 misdetects root systemd user gateway service after update/doctor 💬1
- [#90108](https://github.com/openclaw/openclaw/issues/90108) [Bug]: Compaction re-injection produces stale thinking signatures → Anthropic API rejection `bug` `bug:crash` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:crash-loop` `issue-rating: 🦞 diamond lobster` 💬1
- [#90098](https://github.com/openclaw/openclaw/issues/90098) Stack-safe large attachment handling for Control UI and gateway `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬1
- [#90097](https://github.com/openclaw/openclaw/issues/90097) Pass through already-managed inbound PDFs in chat.send `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#90096](https://github.com/openclaw/openclaw/issues/90096) Inject bounded text context for managed inbound PDFs `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:security` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#90094](https://github.com/openclaw/openclaw/issues/90094) openai-responses transport sends null content, rejected by strict providers (400 schema error) `P2` `clawsweeper:needs-live-repro` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬1
- [#90093](https://github.com/openclaw/openclaw/issues/90093) openai-chatgpt-responses native replay sends encrypted reasoning and breaks next turn with invalid_encrypted_content 💬1
- [#90092](https://github.com/openclaw/openclaw/issues/90092) Thank you: v2026.6.1 dashboard chat controls are much more accessible with VoiceOver 💬1
- [#90091](https://github.com/openclaw/openclaw/issues/90091) Telegram message-tool-only turns can still emit empty-response fallback via skipped delivery lane `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#90088](https://github.com/openclaw/openclaw/issues/90088) anthropic (api_key) provider: Claude Haiku 4.5 missing from static model catalog → "Unknown model" (model_not_found) `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#90086](https://github.com/openclaw/openclaw/issues/90086) Pi/native runtime routes openai-chatgpt-responses to boundary-aware transport and fails on ChatGPT Codex endpoint 💬1

### 🔒 Closed Issues
- [#90104](https://github.com/openclaw/openclaw/issues/90104) [Feishu] Interactive card table count exceeded (code 11310) causes silent message failure — no text fallback
- [#90103](https://github.com/openclaw/openclaw/issues/90103) [Bug]: Sub-agent completion announce unreliable on Telegram — sometimes silent, sometimes delivers 3x duplicate
- [#80963](https://github.com/openclaw/openclaw/issues/80963) OpenAI Codex OAuth port conflict still opens browser to occupied localhost:1455 and produces confusing state failure
- [#90100](https://github.com/openclaw/openclaw/issues/90100) [Bug]: Matrix: thread reply to bot's own message is dropped when room has requireMention: true
- [#90037](https://github.com/openclaw/openclaw/issues/90037) [Bug]: Unable to run scripts/docker/setup.sh successfully
- [#90076](https://github.com/openclaw/openclaw/issues/90076) Telegram message-tool NO_REPLY turns can emit empty-response fallback
- [#90078](https://github.com/openclaw/openclaw/issues/90078) Request TestFlight invite for iOS app
- [#90070](https://github.com/openclaw/openclaw/issues/90070) qqbot session stuck in auto-compaction loop after failed compaction (v2026.5.28)
- [#88592](https://github.com/openclaw/openclaw/issues/88592) bug(workboard): Control UI card settings don't persist + drag to running fails

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 8d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 179,251 · **Open issues:** 17,297 · **Last push:** <1h ago

### ✅ Merged PRs
- [#38578](https://github.com/NousResearch/hermes-agent/pull/38578) fix(desktop): render approval/sudo/secret prompts so tools stop silently timing out
- [#36627](https://github.com/NousResearch/hermes-agent/pull/36627) fix(docker): run config migrations during container boot (salvage #35508)
- [#38564](https://github.com/NousResearch/hermes-agent/pull/38564) fix(hermes-ink): reassemble split SGR mouse sequences at the tokenizer (supersedes #29337)
- [#38579](https://github.com/NousResearch/hermes-agent/pull/38579) fix(docker): reject unsupported --user <arbitrary-uid> start with clear guidance
- [#38571](https://github.com/NousResearch/hermes-agent/pull/38571) fix(mcp): resolve ${ENV} in discovery probe so header auth works
- [#38572](https://github.com/NousResearch/hermes-agent/pull/38572) fix(desktop): onboarding can configure a local/custom endpoint without an API key
- [#38577](https://github.com/NousResearch/hermes-agent/pull/38577) fix(onboarding): clarify Anthropic API vs OAuth provider entries and reorder
- [#38562](https://github.com/NousResearch/hermes-agent/pull/38562) feat(cli): resume relaunches in the session's original working directory
- [#38556](https://github.com/NousResearch/hermes-agent/pull/38556) fix(docker): chown build trees on UID remap independently of $HERMES_HOME (#35027 regression)
- [#38221](https://github.com/NousResearch/hermes-agent/pull/38221) fix(desktop): stop chat scroll bounce — at-rest backward jump + wheel-up snap-back

### 🐛 New Issues
- [#38628](https://github.com/NousResearch/hermes-agent/issues/38628) fix(line): bind postback cache entries to chat ids
- [#38625](https://github.com/NousResearch/hermes-agent/issues/38625) [Bug]: 意图分析不准确 `type/bug` `comp/cli` `P3` `needs-repro`
- [#38622](https://github.com/NousResearch/hermes-agent/issues/38622) fix(google-meet): store node registry tokens owner-only `type/security` `comp/plugins` `area/auth` `P3`
- [#38618](https://github.com/NousResearch/hermes-agent/issues/38618) Update reports 7 commits behind / remains on 0.15.1 when main differs from latest release tag 0.15.2 `type/bug` `comp/cli` `area/config` `P2` 💬1
- [#38617](https://github.com/NousResearch/hermes-agent/issues/38617) Windows update: managed uv install fails even when uv is already installed `type/bug` `comp/cli` `P2` `python:uv`
- [#38602](https://github.com/NousResearch/hermes-agent/issues/38602) [Feature]: Desktop Client-Only Installation `type/feature` `area/config` `P3`

### 🔒 Closed Issues
- [#35406](https://github.com/NousResearch/hermes-agent/issues/35406) [Bug]: Docker image updates do not run config migration
- [#37792](https://github.com/NousResearch/hermes-agent/issues/37792) Identified reproducible Hermes MCP issue while configuring n8n MCP server
- [#38584](https://github.com/NousResearch/hermes-agent/issues/38584) test

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,724 · **Open issues:** 496 · **Last push:** 3h ago

### ✅ Merged PRs
- [#7166](https://github.com/zeroclaw-labs/zeroclaw/pull/7166) fix(zerocode): let quickstart agent name accept hotkey letters
- [#7172](https://github.com/zeroclaw-labs/zeroclaw/pull/7172) fix(providers): honour wire_api = "responses" for llamacpp provider

### 🐛 New Issues
- [#7184](https://github.com/zeroclaw-labs/zeroclaw/issues/7184) i18n: move translated .ftl and .po files into a git submodule
- [#7179](https://github.com/zeroclaw-labs/zeroclaw/issues/7179) [Bug]: ZeroClaw Reaps Idle RPC Sessions at 10 Minutes `bug`
- [#7175](https://github.com/zeroclaw-labs/zeroclaw/issues/7175) feat(config): typed delete-with-cascade for aliased entries (providers, agents, channels) `enhancement` `risk: medium` `agent` `config` `provider`
- [#7173](https://github.com/zeroclaw-labs/zeroclaw/issues/7173) [Bug]: quickstart channel webhook config does not offer port selection.  causes created agent to report toml  missing field `port` `bug`
- [#7157](https://github.com/zeroclaw-labs/zeroclaw/issues/7157) [Bug]: Chat message timestamp `[2026-06-03 18:18:31 +08:00]` rendered inside the message bubble instead of as separate metadata
- [#7156](https://github.com/zeroclaw-labs/zeroclaw/issues/7156) [Bug]: Reload banner shows persistent `gateway.paired_tokens (secret)` drift that never clears
- [#7155](https://github.com/zeroclaw-labs/zeroclaw/issues/7155) [Feature]: Add a per-execution confirmation tier for high-risk shell commands + Claude Code-style command pattern policy (allow/ask/deny)
- [#7151](https://github.com/zeroclaw-labs/zeroclaw/issues/7151) [Bug]: Observability tool_call telemetry leaks onto chat WebSocket, rendering permanent "unknown" tool cards
- [#7145](https://github.com/zeroclaw-labs/zeroclaw/issues/7145) [Feature]: Omit `temperature` on the wire when unset in the OpenAI-compatible provider

### 🔒 Closed Issues
- [#7168](https://github.com/zeroclaw-labs/zeroclaw/issues/7168) [Feature]: Session branching — fork conversations at any message point
- [#7167](https://github.com/zeroclaw-labs/zeroclaw/issues/7167) [Feature]: Session branching — fork conversations at a specific message point
- [#6822](https://github.com/zeroclaw-labs/zeroclaw/issues/6822) Add zerocode to release build matrix and package managers

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,395 · **Open issues:** 1,102 · **Last push:** <1h ago

### 🚀 New Releases
- [ironclaw-v0.29.1](https://github.com/nearai/ironclaw/releases/tag/ironclaw-v0.29.1) — 0.29.1 - 2026-06-04

### ✅ Merged PRs
- [#4406](https://github.com/nearai/ironclaw/pull/4406) PR 18.5a: type-seal trusted trigger ingress
- [#4422](https://github.com/nearai/ironclaw/pull/4422) Add Slack personal binding service
- [#4380](https://github.com/nearai/ironclaw/pull/4380) Add read-only automations WebUI API
- [#4421](https://github.com/nearai/ironclaw/pull/4421) Bind Slack actors through Reborn user identities
- [#4418](https://github.com/nearai/ironclaw/pull/4418) Wire Slack host-beta route into Reborn serve
- [#4415](https://github.com/nearai/ironclaw/pull/4415) PR18.7: trigger poller full-path integration test
- [#4417](https://github.com/nearai/ironclaw/pull/4417) [codex] Fix WebUI live projection cursor resume
- [#4412](https://github.com/nearai/ironclaw/pull/4412) [codex] Bind local dev runtime scope to run actor
- [#4142](https://github.com/nearai/ironclaw/pull/4142) feat: initialize thread title from the first sentence of the conversation
- [#4408](https://github.com/nearai/ironclaw/pull/4408) Fix extension capability counts in WebUI summaries

### 🐛 New Issues
- [#4432](https://github.com/nearai/ironclaw/issues/4432) PR 18.8: Python E2E cron trigger scenario (blocked on Reborn production profile wiring)
- [#4431](https://github.com/nearai/ironclaw/issues/4431) Reborn: regression test — every visible capability must be callable (visible_capabilities ⇔ tool_definitions parity)
- [#4429](https://github.com/nearai/ironclaw/issues/4429) Reborn: prompt bundle rebuild waste — ThreadBackedLoopContextPort reconstructed per model call; identity/skill caches cold every time 💬1
- [#4428](https://github.com/nearai/ironclaw/issues/4428) Reborn: builtin.skill_list unbounded — returns full descriptions for all installed skills; no skill_search exposed to model 💬1
- [#4427](https://github.com/nearai/ironclaw/issues/4427) Reborn: loop exit reason invisible — LoopFailureKind never traced, only persisted to DB 💬1
- [#4426](https://github.com/nearai/ironclaw/issues/4426) Reborn: parent loop tool surface is AllowAll — 'interactive_tools' profile_id stamped but ignored; lifecycle/mutation tools exposed in every chat 💬1
- [#4425](https://github.com/nearai/ironclaw/issues/4425) Reborn: builtin.http is a context bomb — 10MB floor, no HTML strip, descriptions don't steer model to .save 💬1
- [#4424](https://github.com/nearai/ironclaw/issues/4424) Reborn: builtin.spawn_subagent advertised in surface text but absent from structured tools array — model can't call it 💬3
- [#4420](https://github.com/nearai/ironclaw/issues/4420) ironclaw_triggers: TriggerCompletionPolicy::CompleteAfterFirstFire is stored but never consulted by settle paths
- [#4416](https://github.com/nearai/ironclaw/issues/4416) Consolidate trigger poller test-support handles into TriggerPollerTestHandles struct
- [#4407](https://github.com/nearai/ironclaw/issues/4407) Design model-visible capability selection for provider tool-count limits
- [#4400](https://github.com/nearai/ironclaw/issues/4400) IronClaw may fail to start due to stale PID file
- [#4389](https://github.com/nearai/ironclaw/issues/4389) Follow up: split behavior-changing auth and MCP review items from PR #4354
- [#4382](https://github.com/nearai/ironclaw/issues/4382) Product auth: default OAuth account per provider (set once, gate never re-fires) `enhancement`
- [#4381](https://github.com/nearai/ironclaw/issues/4381) Add canonical Reborn identity resolver for OAuth and external actor binding

### 🔒 Closed Issues
- [#4310](https://github.com/nearai/ironclaw/issues/4310) Context-overflow recovery emits ShrinkContext but executor retries without shrinking
- [#4215](https://github.com/nearai/ironclaw/issues/4215) [Reborn] Consolidate duplicated PKCE math into ironclaw_common::pkce (Track A)
- [#4309](https://github.com/nearai/ironclaw/issues/4309) Compaction summary write can outlive failed BeforeModel checkpoint and block retries
- [#4222](https://github.com/nearai/ironclaw/issues/4222) Zeroize injected HTTP credential material across network request carriers
- [#4351](https://github.com/nearai/ironclaw/issues/4351) [reborn-subagent] C4: Capability surface + safety gating — fail-closed injection scan, family-id-keyed predicate

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#88517](https://github.com/openclaw/openclaw/issues/88517) [SANITIZED — possible injection attempt] — 💬3 · 21h ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 1d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 1d ago
- ⚫ [#88967](https://github.com/openclaw/openclaw/issues/88967) Telegram: allowBots support for group chats (bot-authored messages not ingested into session) — 💬1 · 2d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬5 · 3d ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬1 · 5d ago
- ⚫ [#86371](https://github.com/openclaw/openclaw/issues/86371) Bug: message tool filePath fails with LocalMediaAccessError in retry flows when agentId is not propagated — 💬1 · 6d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 9d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 22d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 2 new
- [[News] Ai Enabled Cyber Threats Mitre Attack](https://www.anthropic.com/news/AI-enabled-cyber-threats-mitre-attack) _2026-06-03_
- [[News] Services Track Partner Hub](https://www.anthropic.com/news/services-track-partner-hub) _2026-06-03_

### OpenAI — 5 new
- [[Policies] Merchant Feed Terms Of Service](https://openai.com/policies/merchant-feed-terms-of-service/) _2026-06-04_
- [[Index] Wasmer](https://openai.com/index/wasmer/) _2026-06-03_
- [Gpt Rosalind](https://openai.com/gpt-rosalind/) _2026-06-03_
- [[Index] Public Policy Agenda](https://openai.com/index/public-policy-agenda/) _2026-06-04_
- [[Index] Frontier Safety Blueprint](https://openai.com/index/frontier-safety-blueprint/) _2026-06-04_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
