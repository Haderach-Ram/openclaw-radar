---
layout: post
title: "Ecosystem Digest — 2026-09-04"
date: 2026-09-04 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-04
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 388,793 | 5 | 6 | 10 | 1 |
| **hermesagent** | 240,886 | 9 | 4 | 1 | 0 |
| **ZeroClaw** | 32,721 | 8 | 6 | 10 | 0 |
| **IronClaw** | 12,602 | 4 | 3 | 8 | 0 |
| **Moltis** | 2,844 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 388,793 · **Open issues:** 6,297 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.9.1](https://github.com/openclaw/openclaw/releases/tag/v2026.9.1) — openclaw 2026.9.1

### ✅ Merged PRs
- [#137666](https://github.com/openclaw/openclaw/pull/137666) fix(cron): let session automations refresh pinned widgets
- [#137730](https://github.com/openclaw/openclaw/pull/137730) perf(backup): reuse the entry index for duplicate validation
- [#137502](https://github.com/openclaw/openclaw/pull/137502) fix(macos): clear stale settings when switching gateways
- [#137718](https://github.com/openclaw/openclaw/pull/137718) fix(backup): reject invalid archive entry headers
- [#137635](https://github.com/openclaw/openclaw/pull/137635) perf(skills): prepare watch source paths once
- [#137638](https://github.com/openclaw/openclaw/pull/137638) perf(backup): refresh the archive-owned idle watchdog
- [#137626](https://github.com/openclaw/openclaw/pull/137626) perf(plugins): select prepared manifests in one pass
- [#137739](https://github.com/openclaw/openclaw/pull/137739) fix(agents): release obsolete description update targets
- [#137715](https://github.com/openclaw/openclaw/pull/137715) improve: reuse prepared memory prompts with less work
- [#137717](https://github.com/openclaw/openclaw/pull/137717) fix(gateway): avoid startup refusal after plugin policy migration

### 🐛 New Issues
- [#137799](https://github.com/openclaw/openclaw/issues/137799) [SANITIZED — possible injection attempt] 💬1
- [#137792](https://github.com/openclaw/openclaw/issues/137792) [Bug]: concurrent PR watchers multiply the four-load concurrency limit `bug` `maintainer` `P2` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `maturity:stable` 💬1
- [#137791](https://github.com/openclaw/openclaw/issues/137791) [Bug]: queued PR refresh starts after its watcher disconnects `bug` `maintainer` `P2` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#137781](https://github.com/openclaw/openclaw/issues/137781) WhatsApp group session gets a duplicate `direct`-kind conversation row (same peer_id as the group JID), causing UNIQUE constraint failures `bug` `bug:crash` `P1` `clawsweeper:needs-info` `impact:session-state` `impact:message-loss` `issue-rating: 🦐 gold shrimp` 💬2
- [#137773](https://github.com/openclaw/openclaw/issues/137773) [Bug]: Docker: OPENCLAW_INSTALL_BROWSER=1 creates root-owned /home/node/.cache, breaking Gateway startup (SQLite temp dir) `bug` `no-stale` `bug:crash` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:crash-loop` `issue-rating: 🦞 diamond lobster` 💬2

### 🔒 Closed Issues
- [#124177](https://github.com/openclaw/openclaw/issues/124177) Codex app-server strips OpenClaw `read` on container sandbox backends; #83667 only restored ssh
- [#137770](https://github.com/openclaw/openclaw/issues/137770) [Feature]: Add Gemini 3.8 Flash model catalog support
- [#137762](https://github.com/openclaw/openclaw/issues/137762) [Bug]: Fresh channel session starting with /new reset persists reset as seq 0 without header, crashing turns on legacy transcript assertion
- [#137760](https://github.com/openclaw/openclaw/issues/137760) [Bug] claude-cli backend: assistant turns persisted twice (per-segment imports + cli-assistant aggregate) — Control UI shows every reply duplicated
- [#137761](https://github.com/openclaw/openclaw/issues/137761) [Bug] Control UI: inbound webchat image previews show "Unavailable" without any server request (media://inbound facts lack artifactId)
- [#135900](https://github.com/openclaw/openclaw/issues/135900) [Bug]: 2026.8.2 session-manager regressions break interactive Telegram turns on /new reset boundaries & inbound message adoption

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 240,886 · **Open issues:** 39,181 · **Last push:** <1h ago

### ✅ Merged PRs
- [#101864](https://github.com/NousResearch/hermes-agent/pull/101864) feat(opencode): every OpenCode request now carries x-opencode-session for backend affinity (#81584)

### 🐛 New Issues
- [#102608](https://github.com/NousResearch/hermes-agent/issues/102608) [Bug]: TUI overwrites terminal pane/tab title (breaks tmux/zellij pane names); no opt-out `bug`
- [#102597](https://github.com/NousResearch/hermes-agent/issues/102597) [Feature]: Show a per-profile marker on every session row in the All-profiles recents list 💬1
- [#102593](https://github.com/NousResearch/hermes-agent/issues/102593) Local Models misprices BIOS-carve AMD APUs (Strix Halo): 96G carve / 32G RAM reads as a ~25 GiB machine `type/bug` `comp/cli` `P3`
- [#102592](https://github.com/NousResearch/hermes-agent/issues/102592) Plugin-registered hooks (pre_llm_call, …) never fire on `serve` / `dashboard` — plugin discovery is skipped at startup `type/bug` `comp/cli` `comp/plugins` `P2` `comp/dashboard` 💬1
- [#102589](https://github.com/NousResearch/hermes-agent/issues/102589) cron/lifecycle_guard raw-opens state.db when a command mentions its path, dropping the gateway's POSIX locks -> WAL split-brain `type/bug` `comp/gateway` `comp/cron` `P1` `sweeper:risk-session-state` `area/sessions`
- [#102586](https://github.com/NousResearch/hermes-agent/issues/102586) Tracking: expose and edit per-slot MoA tuning knobs (reasoning_effort, max_tokens) `type/feature` `comp/cli` `area/config` `P3`
- [#102585](https://github.com/NousResearch/hermes-agent/issues/102585) Allow editing an existing MoA slot's max_tokens/reasoning_effort without re-picking provider/model `type/feature` `comp/cli` `area/config` `P3` 💬1
- [#102584](https://github.com/NousResearch/hermes-agent/issues/102584) Expose per-slot `max_tokens` in `hermes moa configure` `type/feature` `comp/cli` `area/config` `P3` 💬1
- [#102582](https://github.com/NousResearch/hermes-agent/issues/102582) Expose per-slot reasoning effort in `hermes moa configure` `type/feature` `comp/cli` `area/config` `P3` 💬2

### 🔒 Closed Issues
- [#83993](https://github.com/NousResearch/hermes-agent/issues/83993) Cron delivery failures are silently swallowed — last_status:ok hides last_delivery_error, user never knows
- [#102570](https://github.com/NousResearch/hermes-agent/issues/102570) Bridge TUI slash commands (/btw, /bg, etc.) to messaging channels
- [#102544](https://github.com/NousResearch/hermes-agent/issues/102544) Feature Request: System Tray App for Hermes Agent Status
- [#102531](https://github.com/NousResearch/hermes-agent/issues/102531) Accidental connector test — please ignore

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,721 · **Open issues:** 798 · **Last push:** 4h ago

### ✅ Merged PRs
- [#9527](https://github.com/zeroclaw-labs/zeroclaw/pull/9527) ci(rust): bump routine toolchains and builders to 1.98.0
- [#10005](https://github.com/zeroclaw-labs/zeroclaw/pull/10005) fix(channels): base channel health on the channel, not on listener liveness
- [#10260](https://github.com/zeroclaw-labs/zeroclaw/pull/10260) fix(zerocode): clear dashboard data on disconnect
- [#10542](https://github.com/zeroclaw-labs/zeroclaw/pull/10542) feat(providers): support Anthropic thinking.display beta
- [#10482](https://github.com/zeroclaw-labs/zeroclaw/pull/10482) fix(config): keep cost cache aligned after append
- [#10490](https://github.com/zeroclaw-labs/zeroclaw/pull/10490) fix(runtime): say what an operator denial means instead of Denied by user.
- [#10494](https://github.com/zeroclaw-labs/zeroclaw/pull/10494) fix(channels/discord): bind routed transcription provider
- [#10403](https://github.com/zeroclaw-labs/zeroclaw/pull/10403) fix(tools): preserve Windows coding CLI environment
- [#9355](https://github.com/zeroclaw-labs/zeroclaw/pull/9355) feat(web): open the same agent in several chat tabs
- [#10514](https://github.com/zeroclaw-labs/zeroclaw/pull/10514) fix(ci): validate pull request head history

### 🐛 New Issues
- [#10609](https://github.com/zeroclaw-labs/zeroclaw/issues/10609) [Bug]: zerocode ignores its launch directory and forces the agent workspace as cwd 💬1
- [#10606](https://github.com/zeroclaw-labs/zeroclaw/issues/10606) [Feature]: Sanitize component errors in unauthenticated health responses `enhancement`
- [#10603](https://github.com/zeroclaw-labs/zeroclaw/issues/10603) [Bug]: OpenCode providers never send x-opencode-session, breaking Go models and risking account flags `bug` 💬1
- [#10594](https://github.com/zeroclaw-labs/zeroclaw/issues/10594) [Bug]: cron records nothing when a job does not run, so silent non-execution is invisible `bug`
- [#10593](https://github.com/zeroclaw-labs/zeroclaw/issues/10593) [Bug]: backup.schedule_cron silently schedules nothing when no agent claims __builtin_backup `bug`
- [#10588](https://github.com/zeroclaw-labs/zeroclaw/issues/10588) [Feature]: Raise the default multimodal.max_image_size_mb to 20 and document the ceiling `enhancement`
- [#10585](https://github.com/zeroclaw-labs/zeroclaw/issues/10585) [Bug]: new log sink regression races migration tests under the default parallel runner `bug`
- [#10580](https://github.com/zeroclaw-labs/zeroclaw/issues/10580) [Feature]: Docs links gate should catch dangling internal links repo-wide, not only added links `enhancement`

### 🔒 Closed Issues
- [#9811](https://github.com/zeroclaw-labs/zeroclaw/issues/9811) /health reports a channel healthy that has never connected
- [#10238](https://github.com/zeroclaw-labs/zeroclaw/issues/10238) [Bug]: ZeroCode shows stale Connected state after daemon exits
- [#10529](https://github.com/zeroclaw-labs/zeroclaw/issues/10529) [Feature]: Support Anthropic thinking.display progress updates (thinking-display-updates-2026-08-18 beta)
- [#9654](https://github.com/zeroclaw-labs/zeroclaw/issues/9654) [Bug]: a genuine operator denial reaches the model as three words with no semantics, and the model invents a cause
- [#9905](https://github.com/zeroclaw-labs/zeroclaw/issues/9905) [Bug]: Discord audio transcription manager is never bound to the active agent provider
- [#9510](https://github.com/zeroclaw-labs/zeroclaw/issues/9510) [Feature]: Reject PRs with no common ancestor with master (blame-collapse guard)

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,602 · **Open issues:** 1,503 · **Last push:** 2h ago

### ✅ Merged PRs
- [#8043](https://github.com/nearai/ironclaw/pull/8043) perf(loop-host): coalesce streamed text updates instead of re-sanitizing the full text per delta
- [#8046](https://github.com/nearai/ironclaw/pull/8046) feat(subagent): a child's approval/auth gate reaches the owner's inbox (R3 slice 3a)
- [#8058](https://github.com/nearai/ironclaw/pull/8058) test(webui): use the live extension id in the notification-setup boundary test
- [#8055](https://github.com/nearai/ironclaw/pull/8055) fix(webui): follow authorizeTraceHold to trace-api.ts in the asset test
- [#8037](https://github.com/nearai/ironclaw/pull/8037) chore(webui): ratchet TypeScript suppressions
- [#8038](https://github.com/nearai/ironclaw/pull/8038) refactor(webui): type and validate frontend API boundaries
- [#8040](https://github.com/nearai/ironclaw/pull/8040) test(webui): type frontend test infrastructure
- [#8039](https://github.com/nearai/ironclaw/pull/8039) refactor(webui): type production components and hooks

### 🐛 New Issues
- [#8057](https://github.com/nearai/ironclaw/issues/8057) Prompt budget should account for non-transcript prompt material (identity, skills, tool schemas) `enhancement`
- [#8052](https://github.com/nearai/ironclaw/issues/8052) Daily ironclaw failure taxonomy — 2026-09-03
- [#8009](https://github.com/nearai/ironclaw/issues/8009) MCP egress errors flatten to "response_error", making discovery failures undiagnosable 💬1
- [#7903](https://github.com/nearai/ironclaw/issues/7903) Decision spike: persistent per-user sandboxed executor behind the trusted host kernel `enhancement` `risk: high` `scope: agent` `scope: sandbox` `reborn` 💬2

### 🔒 Closed Issues
- [#8033](https://github.com/nearai/ironclaw/issues/8033) Remove Redundant `@ts-nocheck` Directives and Prevent New Suppressions
- [#8036](https://github.com/nearai/ironclaw/issues/8036) Type WebUI Test Infrastructure and Remove Remaining Test Suppressions
- [#8035](https://github.com/nearai/ironclaw/issues/8035) Remove `@ts-nocheck` from WebUI Production Components and Hooks

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,844 · **Open issues:** 84 · **Last push:** 1d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬2 · 2d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 4d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 6d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 10d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 22d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 25d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 28d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 30d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 32d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 34d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 1 new
- [[Learn] Intelligence At Work Financial Services](https://openai.com/business/learn/intelligence-at-work-financial-services/) _2026-09-04_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [It's official! Nvidia to acquire Hugging Face for 12.9 billion dollars.](https://reddit.com/r/LocalLLaMA/comments/1w65uhf/its_official_nvidia_to_acquire_hugging_face_for/) ↑1315
- [The benchmarks the big labs don't want you to see](https://reddit.com/r/LocalLLaMA/comments/1w6myn6/the_benchmarks_the_big_labs_dont_want_you_to_see/) ↑587

### r/singularity — top 5 new
- [Gpt 6 astra benchmarks](https://reddit.com/r/singularity/comments/1w6f9xo/gpt_6_astra_benchmarks/) ↑2009
- ["Welcome to the AGI era," OpenAI says as GPT-6 Astra debuts](https://reddit.com/r/singularity/comments/1w6f0jp/welcome_to_the_agi_era_openai_says_as_gpt6_astra/) ↑753
- [GPT-6 Astra Launch Video](https://reddit.com/r/singularity/comments/1w6gjmb/gpt6_astra_launch_video/) ↑622
- [Claude Fable 5.1 surpasses human average on SimpleBench](https://reddit.com/r/singularity/comments/1w68wt3/claude_fable_51_surpasses_human_average_on/) ↑575
- [Another OpenAI cryptic post 10 minutes ago with the number 6, GPT 6 coming today?](https://reddit.com/r/singularity/comments/1w6aeoo/another_openai_cryptic_post_10_minutes_ago_with/) ↑446

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [My OpenClaw agent got cited on a math records page and I can't stop laughing](https://reddit.com/r/openclaw/comments/1w6hjgq/my_openclaw_agent_got_cited_on_a_math_records/) ↑46
- [Inside OpenClaw 2.0: Multiplayer, Dashboards, and Worker Nodes](https://reddit.com/r/openclaw/comments/1w5uzww/inside_openclaw_20_multiplayer_dashboards_and/) ↑11
- [What's your experience with GPT 5.6 sol on Openclaw](https://reddit.com/r/openclaw/comments/1w62a38/whats_your_experience_with_gpt_56_sol_on_openclaw/) ↑10
- [we spent a full day migrating our fleet to openclaw 2.0. here's what actually broke](https://reddit.com/r/openclaw/comments/1w6fuu7/we_spent_a_full_day_migrating_our_fleet_to/) ↑9
- [Cheap Openclaw Models (Sept. 2026)](https://reddit.com/r/openclaw/comments/1w64ebp/cheap_openclaw_models_sept_2026/) ↑9

### X — @openclaw
- [OpenClaw v2026.9.1 is out 🦞

🧜 Mermaid joins the chat
⚡ Setup skips the small talk
🛟 Updates know when to stop
🪶 Long ch](https://x.com/openclaw/status/2095574976518816159) ↑0 🔁0 · recent
- [AgentCore Payments is now GA.

OpenClaw agents can use the 
@awscloud
 aws-agents-pay plugin to make bounded, human-appr](https://x.com/openclaw/status/2095541230793015684) ↑0 🔁0 · recent
- [Inside OpenClaw 2.0 🦞

OpenClaw founder 
@steipete
 joins 
@Pat_Erichsen
, 
@hrudolph
 and 
@jlehman_
 to discuss the re](https://x.com/openclaw/status/2095349641005170953) ↑0 🔁0 · recent


### X — @steipete
- [brilliant fit.](https://x.com/steipete/status/2095678161052901828) ↑0 🔁0 · recent
- [Been using Astra for the last few weeks and it’s so good and proactive. There’s a bunch of PRs on vitest, tsx or SwiftPM](https://x.com/steipete/status/2095600786264973822) ↑0 🔁0 · recent
- [can conform. amazing place to be!](https://x.com/steipete/status/2095541514785141138) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
