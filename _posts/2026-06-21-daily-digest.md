---
layout: post
title: "Ecosystem Digest — 2026-06-21"
date: 2026-06-21 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-21
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 379,680 | 5 | 0 | 1 | 1 |
| **hermesagent** | 198,347 | 8 | 2 | 6 | 0 |
| **ZeroClaw** | 31,967 | 14 | 8 | 10 | 0 |
| **IronClaw** | 12,465 | 1 | 0 | 2 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 379,680 · **Open issues:** 6,460 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.9](https://github.com/openclaw/openclaw/releases/tag/v2026.6.9) — openclaw 2026.6.9

### ✅ Merged PRs
- [#95328](https://github.com/openclaw/openclaw/pull/95328) fix(sessions): reset stale per-channel origin fields on channel switch

### 🐛 New Issues
- [#95443](https://github.com/openclaw/openclaw/issues/95443) bug: 主 Telegram session 被 lifecycleGeneration 静默重置，上下文丢失 `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `issue-rating: 🐚 platinum hermit` 💬1
- [#95441](https://github.com/openclaw/openclaw/issues/95441) github-copilot/gpt-5.5 still persists/replays thinkingSignature encrypted_content after #84367/#90682/#92941, causing channel/direct LLM request failed `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#95440](https://github.com/openclaw/openclaw/issues/95440) [Bug]: Slack presentation payload never renders Block Kit — delivered as plain text despite capability + interactiveReplies enabled `bug` `no-stale` `bug:behavior` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#95429](https://github.com/openclaw/openclaw/issues/95429) [SANITIZED — possible injection attempt] `bug` `bug:behavior` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:session-state` `impact:message-loss` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬2
- [#95422](https://github.com/openclaw/openclaw/issues/95422) TUI/WebChat: Codex app-server streaming shows full reply at once (no incremental deltas) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬2

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 3d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 198,347 · **Open issues:** 22,646 · **Last push:** <1h ago

### ✅ Merged PRs
- [#49853](https://github.com/NousResearch/hermes-agent/pull/49853) test(web_server): make profile-wrapper alias test OS-aware
- [#49855](https://github.com/NousResearch/hermes-agent/pull/49855) fix(kanban): materialize per-task linked worktrees + anchor on board default_workdir
- [#49854](https://github.com/NousResearch/hermes-agent/pull/49854) docs(kanban-worker): document kanban_complete artifacts deliverable param
- [#49839](https://github.com/NousResearch/hermes-agent/pull/49839) fix(whatsapp): resolve bridge dir with HERMES_HOME mirror in read-only Docker (fix #49561)
- [#49840](https://github.com/NousResearch/hermes-agent/pull/49840) fix(chat-completions): strip internal timestamp field before strict providers
- [#49838](https://github.com/NousResearch/hermes-agent/pull/49838) fix(install): expand 8.3 short %TEMP% so Windows Node/Electron stages don't abort

### 🐛 New Issues
- [#49891](https://github.com/NousResearch/hermes-agent/issues/49891) [Bug]: Kanban dashboard COLUMN_ORDER is dead code with stale column list
- [#49888](https://github.com/NousResearch/hermes-agent/issues/49888) Windows Desktop update dialog hides action buttons when UI is zoomed
- [#49883](https://github.com/NousResearch/hermes-agent/issues/49883) [Bug]: voice.beep_enabled treats quoted false-like config strings as enabled `type/bug` `comp/cli` `area/config` `P3`
- [#49878](https://github.com/NousResearch/hermes-agent/issues/49878) [Bug]: Kanban board has no horizontal scrollbar — columns clipped on viewports under ~2400px `type/bug` `comp/plugins` `P3`
- [#49870](https://github.com/NousResearch/hermes-agent/issues/49870) [Bug]: '→ ready' button on Done tasks triggers false diagnostic and respawn guard blocks dispatcher `type/bug` `comp/cron` `P2`
- [#49867](https://github.com/NousResearch/hermes-agent/issues/49867) [Bug]: Hermes Agent Windows Desktop App is taking too much time to start. `type/bug` `comp/cli` `comp/tui` `P3` `needs-repro` 💬1
- [#49865](https://github.com/NousResearch/hermes-agent/issues/49865) feat: numeric shortcuts for command approval (1/2/3/4) `type/feature` `comp/gateway` `P3`
- [#49864](https://github.com/NousResearch/hermes-agent/issues/49864) [Proposal] Refactor run_conversation (complexity 411) + init_agent (31 params) `type/refactor` `comp/agent` `P3`

### 🔒 Closed Issues
- [#49561](https://github.com/NousResearch/hermes-agent/issues/49561) [Bug]: Regression - WhatsApp bridge cannot be installed
- [#47868](https://github.com/NousResearch/hermes-agent/issues/47868) Strict chat-completions providers reject leaked messages[].timestamp metadata

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,967 · **Open issues:** 465 · **Last push:** <1h ago

### ✅ Merged PRs
- [#7992](https://github.com/zeroclaw-labs/zeroclaw/pull/7992) chore(deps): unyank bitcoin crates in Cargo.lock
- [#7922](https://github.com/zeroclaw-labs/zeroclaw/pull/7922) feat(channels/discord): slash command localizations + guild scope
- [#7932](https://github.com/zeroclaw-labs/zeroclaw/pull/7932) fix(docker): correct Node 24 digest pins
- [#8036](https://github.com/zeroclaw-labs/zeroclaw/pull/8036) [SANITIZED — possible injection attempt]
- [#7616](https://github.com/zeroclaw-labs/zeroclaw/pull/7616) fix(providers): strip assistant reasoning on outbound replay for Groq
- [#8038](https://github.com/zeroclaw-labs/zeroclaw/pull/8038) feat(install): add zeroclaw to PATH automatically, with --no-modify-path opt-out
- [#8019](https://github.com/zeroclaw-labs/zeroclaw/pull/8019) fix(ci): pass provider-dispatch gate and --all-features build on master
- [#7967](https://github.com/zeroclaw-labs/zeroclaw/pull/7967) fix(tools): resolve external coding tool working_directory from project root
- [#7982](https://github.com/zeroclaw-labs/zeroclaw/pull/7982) fix(channels/voice): stop caching config-derived static_voice_peers on channel handle
- [#7998](https://github.com/zeroclaw-labs/zeroclaw/pull/7998) [SANITIZED — possible injection attempt]

### 🐛 New Issues
- [#8076](https://github.com/zeroclaw-labs/zeroclaw/issues/8076) [Feature]: local username/password AuthProvider — IdP-less browser login (child of #7141)
- [#8075](https://github.com/zeroclaw-labs/zeroclaw/issues/8075) Keybinds vs. OS globals `zerocode`
- [#8073](https://github.com/zeroclaw-labs/zeroclaw/issues/8073) [Tracker]: v0.8.3 observability, CI, docs, dependencies, and release support `enhancement` `ci` `risk: high` `docs` `dependencies` `observability` `priority:p2` `status:accepted`
- [#8072](https://github.com/zeroclaw-labs/zeroclaw/issues/8072) [Tracker]: v0.8.3 channels, providers, and config behavior `enhancement` `risk: high` `channel` `config` `provider` `priority:p2` `status:accepted`
- [#8071](https://github.com/zeroclaw-labs/zeroclaw/issues/8071) [Tracker]: v0.8.3 runtime, agent, tools, and execution stability `enhancement` `risk: high` `agent` `runtime` `tool` `priority:p2` `status:accepted`
- [#8070](https://github.com/zeroclaw-labs/zeroclaw/issues/8070) [Tracker]: v0.8.3 gateway, web, ZeroCode, and onboarding surfaces `enhancement` `risk: high` `gateway` `onboard` `priority:p2` `status:accepted` `web` `zerocode`
- [#8069](https://github.com/zeroclaw-labs/zeroclaw/issues/8069) [Bug]: RPC-triggered reload can restart the gateway before the old listener releases the port `bug` `risk: high` `daemon` `gateway` `runtime`
- [#8062](https://github.com/zeroclaw-labs/zeroclaw/issues/8062) [Feature]: Improve ZeroCode config editing for structured JSON fields `enhancement` `risk: medium` `config` `priority:p2` `status:in-progress` `status:accepted` `zerocode`
- [#8059](https://github.com/zeroclaw-labs/zeroclaw/issues/8059) Policy cleanup: deny.toml ignored-advisory tracking, multiple-versions, wildcard dependencies `enhancement` `type: ci` `ci` `risk: high` `dependencies` `security` `domain:ci` `domain:security` `priority:p2` `needs-maintainer-review` 💬2
- [#8058](https://github.com/zeroclaw-labs/zeroclaw/issues/8058) CI: release-only — cosign signing, SLSA provenance, SBOM publication `enhancement` `type: ci` `ci` `risk: high` `dependencies` `security` `domain:ci` `domain:security` `priority:p2` `needs-maintainer-review` 💬2
- [#8057](https://github.com/zeroclaw-labs/zeroclaw/issues/8057) CI: scheduled/manual security jobs — CodeQL, npm audit, cargo outdated, Trivy, SBOM `enhancement` `type: ci` `ci` `risk: high` `dependencies` `security` `domain:ci` `domain:security` `priority:p2` `needs-maintainer-review` 💬2
- [#8056](https://github.com/zeroclaw-labs/zeroclaw/issues/8056) CI: required PR gate — cargo audit, lockfile check, npm dependency review `enhancement` `type: ci` `ci` `risk: high` `dependencies` `security` `domain:ci` `domain:security` `priority:p2` `needs-maintainer-review` 💬2
- [#8054](https://github.com/zeroclaw-labs/zeroclaw/issues/8054) [SANITIZED — possible injection attempt] `bug` `risk: high` `agent` `channel` `gateway` `runtime` `security` `tool` `priority:p1` `status:blocked` `status:accepted`
- [#8049](https://github.com/zeroclaw-labs/zeroclaw/issues/8049) bug(channels): proactive_trim_turns drops whole turns, discarding tool results (context drift on long channel sessions) `bug` `risk: medium` `channel` `runtime` `priority:p2` `status:in-progress` `status:accepted`

### 🔒 Closed Issues
- [#7877](https://github.com/zeroclaw-labs/zeroclaw/issues/7877) [Bug]: external coding tools resolve relative working_directory from daemon cwd
- [#7795](https://github.com/zeroclaw-labs/zeroclaw/issues/7795) static_voice_peers caches config-derived voice peers on the channel handle (latent SSOT violation)
- [#6243](https://github.com/zeroclaw-labs/zeroclaw/issues/6243) [Bug]: : Streaming error: HTTP error: error decoding response body provider
- [#6036](https://github.com/zeroclaw-labs/zeroclaw/issues/6036) [Bug]: Agent enters infinite tool-call loop on Termux/Android — repeats identical message without terminating
- [#5883](https://github.com/zeroclaw-labs/zeroclaw/issues/5883) [Bug]: zeroclaw service start fails
- [#5686](https://github.com/zeroclaw-labs/zeroclaw/issues/5686) [Feature]: 添加QQ消息命令，文档未提及，如图
- [#7787](https://github.com/zeroclaw-labs/zeroclaw/issues/7787) Prebuilt v0.8.0 binaries ship without Slack/Discord channel features (regression from 0.7.x)
- [#7675](https://github.com/zeroclaw-labs/zeroclaw/issues/7675) RFC: Hardened CI pipeline — supply-chain scanning, provenance, and SBOM generation

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,465 · **Open issues:** 1,191 · **Last push:** <1h ago

### ✅ Merged PRs
- [#4829](https://github.com/nearai/ironclaw/pull/4829) ci: retire dormant reborn-integration workflow, add Reborn suites to nightly deep CI
- [#5105](https://github.com/nearai/ironclaw/pull/5105) test(safety,auth): fix three stale provider/OAuth guard tests broken on main

### 🐛 New Issues
- [#4108](https://github.com/nearai/ironclaw/issues/4108) Nightly E2E failed

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 8h ago
- 🟢 [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬1 · 8h ago
- 🟢 [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 14h ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬2 · 14h ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬2 · 14h ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 20h ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬5 · 20h ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 22h ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 1d ago
- ⚫ [#94780](https://github.com/openclaw/openclaw/issues/94780) [Feature]: Per-cron model selection independent of agent default — run cheap/free models on automation jobs while keeping main agent on premium LLM — 💬1 · 1d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/singularity — top 2 new
- [Five Chinese AI Labs Cut Token Prices Up to 99%](https://reddit.com/r/singularity/comments/1ub06rj/five_chinese_ai_labs_cut_token_prices_up_to_99/) ↑517
- [Why can't LLMs be trained to think in an optimized AI language rather than English?](https://reddit.com/r/singularity/comments/1ubdjso/why_cant_llms_be_trained_to_think_in_an_optimized/) ↑5

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Is OpenClaw still worth it now that I have Codex + Computer Use + Chrome Bridge?](https://reddit.com/r/openclaw/comments/1u93to2/is_openclaw_still_worth_it_now_that_i_have_codex/) ↑56
- [I want to move to paid models](https://reddit.com/r/openclaw/comments/1uao15s/i_want_to_move_to_paid_models/) ↑8
- [Non-technical person setting up OpenClaw. Is my security plan actually solid or am I missing something obvious?](https://reddit.com/r/openclaw/comments/1ub7eyw/nontechnical_person_setting_up_openclaw_is_my/) ↑7
- [Showcase Weekend! — Week 24, 2026](https://reddit.com/r/openclaw/comments/1uanol6/showcase_weekend_week_24_2026/) ↑7
- [built a project that visualizes your OC as a live lobster 🦞 (terminal pixel-art, open-source)](https://reddit.com/r/openclaw/comments/1uaz0hr/built_a_project_that_visualizes_your_oc_as_a_live/) ↑4

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
- [If you are in Japan or do business there, here's your chance to get lots of tokens!](https://x.com/steipete) ↑0 🔁0 · recent
- [yup. I sync them daily else they get lost](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
