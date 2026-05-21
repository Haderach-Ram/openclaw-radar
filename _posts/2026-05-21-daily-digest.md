---
layout: post
title: "Ecosystem Digest — 2026-05-21"
date: 2026-05-21 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-21
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 373,584 | 13 | 6 | 9 | 2 |
| **hermesagent** | 159,782 | 9 | 0 | 4 | 0 |
| **ZeroClaw** | 31,500 | 5 | 10 | 5 | 1 |
| **IronClaw** | 12,304 | 9 | 2 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 373,584 · **Open issues:** 7,312 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.5.20-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.5.20-beta.1) — openclaw 2026.5.20-beta.1
- [v2026.5.19](https://github.com/openclaw/openclaw/releases/tag/v2026.5.19) — openclaw 2026.5.19

### ✅ Merged PRs
- [#84736](https://github.com/openclaw/openclaw/pull/84736) fix(codex): guard path-only bootstrap files [AI-assisted]
- [#84718](https://github.com/openclaw/openclaw/pull/84718) Warn on plaintext secret config in doctor
- [#84570](https://github.com/openclaw/openclaw/pull/84570) Remove skill prelude exec allowlist
- [#84701](https://github.com/openclaw/openclaw/pull/84701) perf(tui): defer EmbeddedTuiBackend import, drop dead warmup helpers
- [#84686](https://github.com/openclaw/openclaw/pull/84686) perf(tui): skip plugin metadata + provider catalog on remote TUI startup
- [#84741](https://github.com/openclaw/openclaw/pull/84741) Route JSON-mode plugin registration logs to stderr
- [#84592](https://github.com/openclaw/openclaw/pull/84592) build: suppress rolldown-plugin-dts CommonJS dts warnings from bundled zod locales
- [#84729](https://github.com/openclaw/openclaw/pull/84729) [codex] Fix macOS app copyright year
- [#84678](https://github.com/openclaw/openclaw/pull/84678) fix(approval): route /approve through approval resolver

### 🐛 New Issues
- [#84766](https://github.com/openclaw/openclaw/issues/84766) [Bug]: `sessions.patch` silently deletes user-set label when store entry exists but has no sessionId yet `bug` `bug:behavior`
- [#84755](https://github.com/openclaw/openclaw/issues/84755) [Bug]: Codex harness sessions stall with active_work_without_progress and stale running/hasActiveRun=false state on 2026.5.19 `bug` `bug:behavior` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬1
- [#84753](https://github.com/openclaw/openclaw/issues/84753) [Feature]: Show display name instead of user ID in session list `enhancement` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` 💬1
- [#84751](https://github.com/openclaw/openclaw/issues/84751) openclaw devices list times out under live-write races in device store 💬1
- [#84750](https://github.com/openclaw/openclaw/issues/84750) Stale .tmp orphans in ~/.openclaw/devices/ corrupt atomic file reads `P2` `clawsweeper:needs-live-repro` `impact:auth-provider` `impact:crash-loop` `issue-rating: 🐚 platinum hermit` 💬1
- [#84746](https://github.com/openclaw/openclaw/issues/84746) [Bug]: Auto-compaction crashes active responses after 5.18 transcript lock scope change (#13744) 💬1
- [#84745](https://github.com/openclaw/openclaw/issues/84745) [Bug]: cron preflight normalizes LiteLLM-backed Gemini model allowlist entries to Google preview IDs `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#84744](https://github.com/openclaw/openclaw/issues/84744) bootstrap-extra-files: user-configured paths silently dropped by VALID_BOOTSTRAP_NAMES whitelist `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:session-state` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1
- [#84743](https://github.com/openclaw/openclaw/issues/84743) [SANITIZED — possible injection attempt] `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:crash-loop` `issue-rating: 🦞 diamond lobster` 💬1
- [#84731](https://github.com/openclaw/openclaw/issues/84731) Slow /models command with LiteLLM model catalog appears to use full catalog refresh path `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#84727](https://github.com/openclaw/openclaw/issues/84727) Gateway restart can leave Codex custom tool call without output `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#84725](https://github.com/openclaw/openclaw/issues/84725) [Bug]: Codex warm turns spend ~7.5s in auth/start-options/tool setup before prompt submission `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` 💬3
- [#84724](https://github.com/openclaw/openclaw/issues/84724) Built-in cron tool should allow isolated cron runs to disable their current job `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#84759](https://github.com/openclaw/openclaw/issues/84759) Agent runtime JSON.parses gzipped HTTP responses (Unexpected token '\^_')
- [#84757](https://github.com/openclaw/openclaw/issues/84757) [Bug]: Telegram session can get stuck after compaction when encrypted reasoning content fails verification
- [#84754](https://github.com/openclaw/openclaw/issues/84754) [Bug]: WebChat typing indicator persists after assistant response completes
- [#84635](https://github.com/openclaw/openclaw/issues/84635) Add i18n / Chinese (zh-CN) localization support for WebChat Control UI
- [#12601](https://github.com/openclaw/openclaw/issues/12601) [Feature Request] Slack Canvas content read support
- [#84293](https://github.com/openclaw/openclaw/issues/84293) [Bug]: Suppress non-JSON output when CLI option `--json` is specified

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬105 · 1h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 159,782 · **Open issues:** 12,547 · **Last push:** <1h ago

### ✅ Merged PRs
- [#29585](https://github.com/NousResearch/hermes-agent/pull/29585) fix(gateway): prioritize Telegram command menu (salvage of #29495)
- [#29342](https://github.com/NousResearch/hermes-agent/pull/29342) fix(tui): clipboard copy on linux/wayland
- [#29490](https://github.com/NousResearch/hermes-agent/pull/29490) fix(skills-hub): deduplicate search results by identifier, not name
- [#29484](https://github.com/NousResearch/hermes-agent/pull/29484) fix(x_search): surface degraded results + validate dates

### 🐛 New Issues
- [#29588](https://github.com/NousResearch/hermes-agent/issues/29588) [i18n] clarify tool's reply-prompt template is hardcoded in English
- [#29584](https://github.com/NousResearch/hermes-agent/issues/29584) Bug: productivity/maps SKILL.md script path is wrong twice — missing category prefix and uses ~/ which sandboxed subprocesses can't resolve
- [#29582](https://github.com/NousResearch/hermes-agent/issues/29582) [Bug]: WeChat gateway fails to send .html files due to MEDIA extension allowlist
- [#29580](https://github.com/NousResearch/hermes-agent/issues/29580) [Feature]: upload owned skill with scripts not from bash mode
- [#29567](https://github.com/NousResearch/hermes-agent/issues/29567) background_review fork sends wider tools[] than parent, fragments Anthropic prefix cache (~50% wasted cache-write on long sessions) `type/perf` `comp/agent` `provider/anthropic` `P2` 💬1
- [#29565](https://github.com/NousResearch/hermes-agent/issues/29565) [Feature]: a Hermes-Canvas (Text Editing & Hybrid Completion Environment) on top of a well-built GUI for Hermes Agent `type/feature` `comp/gateway` `comp/tui` `P3` 💬2
- [#29562](https://github.com/NousResearch/hermes-agent/issues/29562) [Bug]: Dashboard TUI scroll regression in v0.14.0 — long sessions truncated / missing history `type/bug` `comp/tui` `P2` 💬1
- [#29559](https://github.com/NousResearch/hermes-agent/issues/29559) [Bug] Context compression silently drops summary on connection error, causing total context loss for long tasks `type/bug` `comp/agent` `P1` 💬1
- [#29557](https://github.com/NousResearch/hermes-agent/issues/29557) [Bug]: Mouse tracking escape sequences leak into input buffer (raw SGR mouse codes appear in prompt input) `type/bug` `comp/tui` `P2` 💬1

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,500 · **Open issues:** 495 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.8.0-beta-1](https://github.com/zeroclaw-labs/zeroclaw/releases/tag/v0.8.0-beta-1) — v0.8.0-beta-1

### ✅ Merged PRs
- [#6072](https://github.com/zeroclaw-labs/zeroclaw/pull/6072) feat(skills): emit positive log when skill tools are registered
- [#6736](https://github.com/zeroclaw-labs/zeroclaw/pull/6736) fix(runtime,channels): keep malformed tool protocol internal
- [#6625](https://github.com/zeroclaw-labs/zeroclaw/pull/6625) fix(tools/web_search): surface DuckDuckGo anomaly-modal block (#6373)
- [#6398](https://github.com/zeroclaw-labs/zeroclaw/pull/6398) feat!: multi-agent runtime and schema V3
- [#6776](https://github.com/zeroclaw-labs/zeroclaw/pull/6776) fix(web): 0.8.0 ui fixes

### 🐛 New Issues
- [#6813](https://github.com/zeroclaw-labs/zeroclaw/issues/6813) bug(tests): make channel parallel-dispatch test avoid brittle timing threshold `bug` `risk: low` `channel` `tests`
- [#6810](https://github.com/zeroclaw-labs/zeroclaw/issues/6810) [Feature]: Add a user-facing feature and support matrix `enhancement` `type: docs` `risk: low` `docs` `priority:p3`
- [#6808](https://github.com/zeroclaw-labs/zeroclaw/issues/6808) RFC: Work Lanes, Board Automation, and Label Cleanup `enhancement` `type: docs` `type:rfc` 💬2
- [#6807](https://github.com/zeroclaw-labs/zeroclaw/issues/6807) [Feature]: Telegram custom webapi endpoint `enhancement`
- [#6801](https://github.com/zeroclaw-labs/zeroclaw/issues/6801) [Bug]: purge_namespace deletes by category column on integration/v0.8.0  `bug` `risk: high` `memory` `tool` `priority:p1` `status:in-progress` `status:no-stale`

### 🔒 Closed Issues
- [#6734](https://github.com/zeroclaw-labs/zeroclaw/issues/6734) [Bug]: Qwen 3.6 tool-call envelopes can leak into Matrix replies
- [#6373](https://github.com/zeroclaw-labs/zeroclaw/issues/6373) [Bug]: Fresh install, web_search doesn't work, web_fetch does
- [#6270](https://github.com/zeroclaw-labs/zeroclaw/issues/6270) [Feature]: Configurable macro + onboarding support for v3 nested config shapes
- [#6053](https://github.com/zeroclaw-labs/zeroclaw/issues/6053) [Feature]: zeroclaw config set/init support for dynamic map entries (e.g. providers.models.<name>)
- [#6375](https://github.com/zeroclaw-labs/zeroclaw/issues/6375) [SANITIZED — possible injection attempt]
- [#5890](https://github.com/zeroclaw-labs/zeroclaw/issues/5890) RFC: Multi-agent UX flow — design
- [#5947](https://github.com/zeroclaw-labs/zeroclaw/issues/5947) [Feature]: schema v3 — batch breaking field migrations
- [#6273](https://github.com/zeroclaw-labs/zeroclaw/issues/6273) [Feature]: Typed-family split for model and TTS providers; dead Azure field deletion; qualified provider naming
- [#6272](https://github.com/zeroclaw-labs/zeroclaw/issues/6272) Multi-agent runtime: per-alias workspaces, permissions, and shared resources
- [#5891](https://github.com/zeroclaw-labs/zeroclaw/issues/5891) [Feature]: Multi-agent v1 — tracker

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,304 · **Open issues:** 952 · **Last push:** 1h ago

### ✅ Merged PRs
- [#3836](https://github.com/nearai/ironclaw/pull/3836) feat(ci): post "started" comment with link to dispatcher run
- [#3835](https://github.com/nearai/ironclaw/pull/3835) fix(ci): grant pull-requests:write for /benchmark reactions endpoint
- [#3808](https://github.com/nearai/ironclaw/pull/3808) ci: add /benchmark slash-command dispatcher
- [#3832](https://github.com/nearai/ironclaw/pull/3832) Expose shell in Reborn local-dev
- [#3816](https://github.com/nearai/ironclaw/pull/3816) [codex] Port shell to Reborn built-ins
- [#3820](https://github.com/nearai/ironclaw/pull/3820) Enforce runtime policy before host capability dispatch
- [#3818](https://github.com/nearai/ironclaw/pull/3818) [codex] Enforce staged credentials for production egress
- [#3782](https://github.com/nearai/ironclaw/pull/3782) feat(reborn): add CLI serve handoff
- [#3825](https://github.com/nearai/ironclaw/pull/3825) Require resolved runtime policy for Reborn live runtime
- [#3817](https://github.com/nearai/ironclaw/pull/3817) Port Reborn coding built-ins through v1 modules

### 🐛 New Issues
- [#3829](https://github.com/nearai/ironclaw/issues/3829) [Reborn] Lane 9: implement native Google Calendar and Gmail extension-v2 capabilities `reborn`
- [#3821](https://github.com/nearai/ironclaw/issues/3821) Thread::restore_from_messages drops orphan assistant rows, preventing out-of-band context injection
- [#3812](https://github.com/nearai/ironclaw/issues/3812) [Reborn] Step 3: Migrate OAuth callbacks and setup continuations to typed auth flows
- [#3811](https://github.com/nearai/ironclaw/issues/3811) [Reborn] Step 2: Wire product auth service seam into V1-compatible auth/setup flows 💬1
- [#3810](https://github.com/nearai/ironclaw/issues/3810) [Reborn] Step 1: Auth product contracts, V1 behavior inventory, and fake-service tests
- [#3807](https://github.com/nearai/ironclaw/issues/3807) [Reborn WebUI] Lane 7: finish beta route/tool surface path `scope: channel/web` `reborn`
- [#3805](https://github.com/nearai/ironclaw/issues/3805) [Reborn] Lane 5: implement Notion MCP capability path `reborn`
- [#3803](https://github.com/nearai/ironclaw/issues/3803) [Reborn] Lane 3: wire existing secrets/egress substrate through production tool composition `scope: secrets` `reborn` `module:M4-host-kernel` 💬2
- [#3798](https://github.com/nearai/ironclaw/issues/3798) Design: subagent spawn for the Reborn agent loop `enhancement` `scope: agent` `reborn`

### 🔒 Closed Issues
- [#3800](https://github.com/nearai/ironclaw/issues/3800) [Reborn] Lane 1: finish REPL golden path after composition PRs merge
- [#3734](https://github.com/nearai/ironclaw/issues/3734) v0.28.2 regression: provider config missing API Key and Fetch available models controls

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 4d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬2 · 5d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 8d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 4 new
- [[Index] Ramp](https://openai.com/index/ramp/) _2026-05-20_
- [[Index] Introducing Openai For Singapore](https://openai.com/index/introducing-openai-for-singapore/) _2026-05-21_
- [[Index] The Next Phase Of Education For Countries](https://openai.com/index/the-next-phase-of-education-for-countries/) _2026-05-20_
- [[Index] Model Disproves Discrete Geometry Conjecture](https://openai.com/index/model-disproves-discrete-geometry-conjecture/) _2026-05-20_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
