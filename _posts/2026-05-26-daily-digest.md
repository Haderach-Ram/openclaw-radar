---
layout: post
title: "Ecosystem Digest — 2026-05-26"
date: 2026-05-26 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-05-26
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 374,654 | 5 | 3 | 10 | 0 |
| **hermesagent** | 167,362 | 4 | 3 | 9 | 0 |
| **ZeroClaw** | 31,581 | 9 | 5 | 10 | 0 |
| **IronClaw** | 12,346 | 8 | 0 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 374,654 · **Open issues:** 6,838 · **Last push:** <1h ago

### ✅ Merged PRs
- [#86621](https://github.com/openclaw/openclaw/pull/86621) refactor: use Rastermill for image processing
- [#86714](https://github.com/openclaw/openclaw/pull/86714) fix(build): pin synthetic auth runtime dist entry
- [#86427](https://github.com/openclaw/openclaw/pull/86427) fix(agents): release embedded-attempt session lock on every exit path
- [#86712](https://github.com/openclaw/openclaw/pull/86712) fix(plugin-sdk): preserve string-const unions as flat enum for deepseek tool schemas
- [#86575](https://github.com/openclaw/openclaw/pull/86575) fix(gateway): dampen repeated device-required probes
- [#86703](https://github.com/openclaw/openclaw/pull/86703) perf: speed up usage cost lookups
- [#86578](https://github.com/openclaw/openclaw/pull/86578) fix(cron): accept opaque session target keys
- [#86596](https://github.com/openclaw/openclaw/pull/86596) fix(update): avoid duplicate plugin smoke failures
- [#86191](https://github.com/openclaw/openclaw/pull/86191) Add OpenTelemetry LLM content spans
- [#84842](https://github.com/openclaw/openclaw/pull/84842) fix: honor skill source install aliases

### 🐛 New Issues
- [#86718](https://github.com/openclaw/openclaw/issues/86718) Gateway event loop starvation and HTTP/WS outage during sessions usage/cost under memory pressure `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:message-loss` `impact:crash-loop` `issue-rating: 🐚 platinum hermit` 💬1
- [#86707](https://github.com/openclaw/openclaw/issues/86707) [Bug]: canvas.* commands declared by macOS node are blocked by gateway platform allowlist (sister bug to #57169) 💬1
- [#86702](https://github.com/openclaw/openclaw/issues/86702) MemoryIndexManager.close() races with in-flight sync — provider/DB closed before sync settles `P2` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#86688](https://github.com/openclaw/openclaw/issues/86688) Gateway crashes with uncaught ENETDOWN inside SSRF guard's outbound connect; macOS launchd silently parks the LaunchAgent `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:needs-live-repro` `impact:message-loss` `impact:crash-loop` `issue-rating: 🐚 platinum hermit` 💬3
- [#86687](https://github.com/openclaw/openclaw/issues/86687) v5.22 regressions: group-chat over-suppression + sticky image re-attachment in always-on Discord channels `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:session-state` `impact:security` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#86143](https://github.com/openclaw/openclaw/issues/86143) [v2026.5.22] PM cron job fails: synthetic-auth.runtime.js does not export 'r'
- [#86468](https://github.com/openclaw/openclaw/issues/86468) fix: normalizeDeepSeekSchema drops all but first anyOf variant for const unions
- [#86704](https://github.com/openclaw/openclaw/issues/86704) [Bug]: Cron jobs fail with 503 overloaded error — no fallback model configured

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 167,362 · **Open issues:** 13,755 · **Last push:** <1h ago

### ✅ Merged PRs
- [#32336](https://github.com/NousResearch/hermes-agent/pull/32336) fix(skills-hub): show every catalog source on /docs/skills (skills.sh, ClawHub, browse.sh, OpenAI, …)
- [#32326](https://github.com/NousResearch/hermes-agent/pull/32326) fix(skills): reject symlinks in skill bundles before install
- [#32339](https://github.com/NousResearch/hermes-agent/pull/32339) fix(cron): split scanner so skill prose stops false-positiving exfil patterns
- [#32282](https://github.com/NousResearch/hermes-agent/pull/32282) fix(anthropic): API-key path skips OAuth autodiscovery + prunes stale entries
- [#32272](https://github.com/NousResearch/hermes-agent/pull/32272) fix(gateway): coerce scalar `model:` to dict before /model --global persist
- [#32261](https://github.com/NousResearch/hermes-agent/pull/32261) feat(skills): add optional openhands skill — closes #477
- [#32273](https://github.com/NousResearch/hermes-agent/pull/32273) feat(patch): indent preservation, CRLF preservation, per-file failure escalation
- [#32271](https://github.com/NousResearch/hermes-agent/pull/32271) fix(secrets): only apply external secrets once per HERMES_HOME per process
- [#32264](https://github.com/NousResearch/hermes-agent/pull/32264) fix(agent): log outer-loop exceptions at ERROR with traceback

### 🐛 New Issues
- [#32360](https://github.com/NousResearch/hermes-agent/issues/32360) fix: update default Gemini model from gemini-2.5-flash to gemini-3.5-flash (shutdown Oct 16 2026)
- [#32338](https://github.com/NousResearch/hermes-agent/issues/32338) Harden Google Workspace OAuth cache and callback recovery flows `type/feature` `comp/gateway` `area/auth` `P3` 💬1
- [#32337](https://github.com/NousResearch/hermes-agent/issues/32337) [Bug]: signal-cli-rest-api does not work `type/bug` `comp/gateway` `platform/signal` `P2` 💬1
- [#32334](https://github.com/NousResearch/hermes-agent/issues/32334) [Bug] Dashboard SET MAIN MODEL freezes/black screen when selecting named custom provider `type/bug` `comp/gateway` `area/config` `P2`

### 🔒 Closed Issues
- [#28970](https://github.com/NousResearch/hermes-agent/issues/28970) Feature Request: Make hermes backup exclusions configurable
- [#27856](https://github.com/NousResearch/hermes-agent/issues/27856) Gateway restart can lose long-running sessions during shutdown drain
- [#32291](https://github.com/NousResearch/hermes-agent/issues/32291) [Feature]: Add Antigravity toolset / skill

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,581 · **Open issues:** 518 · **Last push:** 2h ago

### ✅ Merged PRs
- [#6512](https://github.com/zeroclaw-labs/zeroclaw/pull/6512) fix(channels/email): html body rendering, subject threading, attachment path resolution
- [#6896](https://github.com/zeroclaw-labs/zeroclaw/pull/6896) fix(onboarding): restore Homebrew config dir detection
- [#6901](https://github.com/zeroclaw-labs/zeroclaw/pull/6901) fix(providers): preserve full reqwest error chains in transport/log diagnostics
- [#6752](https://github.com/zeroclaw-labs/zeroclaw/pull/6752) fix(ci): unblock pr-title workflow with inline regex check
- [#6867](https://github.com/zeroclaw-labs/zeroclaw/pull/6867) fix(setup): align Windows minimal install with core-only build
- [#6902](https://github.com/zeroclaw-labs/zeroclaw/pull/6902) fix(security): conditionally bind /lib64 and /lib in bubblewrap sandbox
- [#5120](https://github.com/zeroclaw-labs/zeroclaw/pull/5120) fix(memory): reject clear on append-only markdown backend
- [#6835](https://github.com/zeroclaw-labs/zeroclaw/pull/6835) fix(discord): resume gateway sessions after reconnect
- [#6872](https://github.com/zeroclaw-labs/zeroclaw/pull/6872) docs(review): update milestone fallback owner
- [#6860](https://github.com/zeroclaw-labs/zeroclaw/pull/6860) docs(skills): add current Python skills guide

### 🐛 New Issues
- [#6937](https://github.com/zeroclaw-labs/zeroclaw/issues/6937) docs(api): document attachment path validation boundary `enhancement` `risk: medium` `channel` `channel:email`
- [#6932](https://github.com/zeroclaw-labs/zeroclaw/issues/6932) [Feature]: persist gateway WebSocket sessions as full conversation transcripts `enhancement` `risk: high` `gateway` `memory` `runtime` `priority:p2` `status:accepted` `status:no-stale`
- [#6923](https://github.com/zeroclaw-labs/zeroclaw/issues/6923) [Bug]: OpenAI Codex OAuth works, but providers.models.openai.<alias> falls back to OPENAI_API_KEY at runtime `bug` 💬1
- [#6921](https://github.com/zeroclaw-labs/zeroclaw/issues/6921) [Feature]: Document minimum browser requirements and add an unsupported-browser banner
- [#6917](https://github.com/zeroclaw-labs/zeroclaw/issues/6917) feat: honor action-scope filter in Composio tool dispatch `enhancement` `risk: high` `config` `security` `tool` `tool: composio` `priority:p2` `status:blocked` `needs-maintainer-review`
- [#6916](https://github.com/zeroclaw-labs/zeroclaw/issues/6916) feat: process-memory limits on shell/skill_tool subprocess execution `enhancement` `risk: high` `config` `runtime` `security` `skills` `tool` `priority:p1` `tool:shell` `status:blocked` `needs-maintainer-review`
- [#6915](https://github.com/zeroclaw-labs/zeroclaw/issues/6915) feat: skill-scoped tool activation (temporary elevation during skill execution) `enhancement` `risk: high` `runtime` `security` `skills` `tool` `priority:p2` `tool:mcp` `status:blocked` `needs-maintainer-review`
- [#6914](https://github.com/zeroclaw-labs/zeroclaw/issues/6914) feat: enforce allowed_tools / denied_tools in main agent loop `enhancement` `risk: high` `agent` `config` `runtime` `security` `tool` `priority:p1` `tool:mcp` `status:blocked` `needs-maintainer-review` 💬1
- [#6909](https://github.com/zeroclaw-labs/zeroclaw/issues/6909) [Feature]: computer-use support (screen interaction like Codex / Peekaboo) `enhancement` `risk: high` `runtime` `security` `tool` `tool:browser` `priority:p2` `type:rfc` `status:accepted` 💬1

### 🔒 Closed Issues
- [#6889](https://github.com/zeroclaw-labs/zeroclaw/issues/6889) [Bug]: reqwest errors in provider only show top-level message, hiding root cause
- [#6751](https://github.com/zeroclaw-labs/zeroclaw/issues/6751) fix(ci): pr-title workflow has never run — startup_failure on every PR since #6396
- [#6836](https://github.com/zeroclaw-labs/zeroclaw/issues/6836) [Bug]: setup.bat --minimal produces ~26 MB build instead of ~6 MB on Windows
- [#6878](https://github.com/zeroclaw-labs/zeroclaw/issues/6878) [Bug]: Bubblewrap fails on Fedora 43 due to bwrap parameters missing /lib64 and therefore not allowing linked-libraries.  Linked to issue #5126
- [#5722](https://github.com/zeroclaw-labs/zeroclaw/issues/5722) Default shell sandbox configuration blocks all realistic Python skill patterns (v0.6.9)

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,346 · **Open issues:** 1,013 · **Last push:** <1h ago

### ✅ Merged PRs
- [#3961](https://github.com/nearai/ironclaw/pull/3961) feat(signing): canonical signing-bytes + ApprovedTxHash core (attested-signing PR2/10)
- [#4057](https://github.com/nearai/ironclaw/pull/4057) Add safe capability display previews
- [#4050](https://github.com/nearai/ironclaw/pull/4050) [codex] Emit capability lifecycle SSE events
- [#4007](https://github.com/nearai/ironclaw/pull/4007) [codex] Enable Reborn local yolo host access
- [#4056](https://github.com/nearai/ironclaw/pull/4056) [codex] Classify Reborn runtime failures for recovery
- [#4049](https://github.com/nearai/ironclaw/pull/4049) [Reborn] Add tenant sandbox broker affordances
- [#3867](https://github.com/nearai/ironclaw/pull/3867) [Draft] Subagent spawn phase 0 prerequisite
- [#3973](https://github.com/nearai/ironclaw/pull/3973) feat(first-party): add gsuite core handlers
- [#3971](https://github.com/nearai/ironclaw/pull/3971) feat(auth): add google oauth protocol helpers
- [#3972](https://github.com/nearai/ironclaw/pull/3972) test(first-party): cover gsuite handler shapes

### 🐛 New Issues
- [#4059](https://github.com/nearai/ironclaw/issues/4059) [Reborn] Enrich model-visible Reborn runtime errors with safe recovery context `reborn`
- [#4053](https://github.com/nearai/ironclaw/issues/4053) Attested-signing: harden custodial-mainnet KMS fail-closed guard
- [#4052](https://github.com/nearai/ironclaw/issues/4052) Attested-signing: TrustEnrollment ceremony + connected-wallet trust registration
- [#4051](https://github.com/nearai/ironclaw/issues/4051) [tracking] Attested-signing: multi-tenant operational model (per-tenant config + key/credential lifecycle) 💬1
- [#4043](https://github.com/nearai/ironclaw/issues/4043) Improve Credit / Rate Limit Transparency and Prevent Token Consumption on Failed Requests `enhancement`
- [#4042](https://github.com/nearai/ironclaw/issues/4042) [Reborn] Complete tenant sandbox process capabilities `enhancement` `risk: high` `suggested_P1` `reborn` `module:M4-host-kernel`
- [#4034](https://github.com/nearai/ironclaw/issues/4034) Feature Request: Custom Telegram API Host
- [#4030](https://github.com/nearai/ironclaw/issues/4030) [QA] Discord channel stops replying while ironclaw stays active with tokio workers pinned at 100% CPU

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 14h ago
- ⚫ [#86371](https://github.com/openclaw/openclaw/issues/86371) Bug: message tool filePath fails with LocalMediaAccessError in retry flows when agentId is not propagated — 💬1 · 18h ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬1 · 9d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬2 · 10d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 13d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Chris Olah Pope Leo Encyclical](https://www.anthropic.com/news/chris-olah-pope-leo-encyclical) _2026-05-25_

### OpenAI — 1 new
- [[Index] Grupo Folha Grupo Uol Partnership](https://openai.com/index/grupo-folha-grupo-uol-partnership/) _2026-05-25_

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
