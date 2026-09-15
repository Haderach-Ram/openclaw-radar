---
layout: post
title: "Ecosystem Digest — 2026-09-15"
date: 2026-09-15 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-15
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 389,711 | 6 | 4 | 10 | 0 |
| **hermesagent** | 245,539 | 0 | 10 | 5 | 1 |
| **ZeroClaw** | 32,809 | 6 | 5 | 10 | 0 |
| **IronClaw** | 12,621 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,860 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 389,711 · **Open issues:** 7,317 · **Last push:** <1h ago

### ✅ Merged PRs
- [#148675](https://github.com/openclaw/openclaw/pull/148675) test(codex): stabilize delivery cache request proof
- [#139344](https://github.com/openclaw/openclaw/pull/139344) fix(windows): keep scheduled gateway running after restart
- [#148671](https://github.com/openclaw/openclaw/pull/148671) fix(gateway): restore Windows scheduled-task inspection
- [#148672](https://github.com/openclaw/openclaw/pull/148672) improve: reduce repeated sender reads in shared transcripts
- [#148678](https://github.com/openclaw/openclaw/pull/148678) test: reuse compiled SQLite readers in legacy finalization
- [#148665](https://github.com/openclaw/openclaw/pull/148665) test: retain output when root configuration resolution fails
- [#148404](https://github.com/openclaw/openclaw/pull/148404) test: release shared setup exit listener
- [#148666](https://github.com/openclaw/openclaw/pull/148666) fix(tests): drain workers before removing fixture state
- [#148673](https://github.com/openclaw/openclaw/pull/148673) refactor(ai): drop unused replay result metadata
- [#148401](https://github.com/openclaw/openclaw/pull/148401) test(ui): make session and WebSocket probes runtime-independent

### 🐛 New Issues
- [#148697](https://github.com/openclaw/openclaw/issues/148697) [Bug]: history prompt-cache rewritten on every call during a tool loop (cache read pinned at system prefix, ~4-8x cost) `bug` `regression`
- [#148693](https://github.com/openclaw/openclaw/issues/148693) [Bug]: Android stays Connected while node events repeatedly fail with PAIRING_CHANGED (2026.9.4) `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `maturity:stable` `impact:ux-friction` 💬1
- [#148681](https://github.com/openclaw/openclaw/issues/148681) Update failure: finalize:doctor (2026.9.4) `clawsweeper:needs-info` `P0` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-release-blocker` 💬2
- [#148680](https://github.com/openclaw/openclaw/issues/148680) Control UI TTS supplement does not merge with source message during live updates `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬4
- [#148659](https://github.com/openclaw/openclaw/issues/148659) [Bug]: macOS onboarding remains stuck after OpenRouter is configured and inference succeeds `bug` `bug:behavior` `P0` `issue-rating: 🦪 silver shellfish` `impact:ux-release-blocker` 💬1
- [#148658](https://github.com/openclaw/openclaw/issues/148658) [Bug]: macOS realtime Talk cancels multi-sentence replies with playback-overflow `bug` `bug:behavior`

### 🔒 Closed Issues
- [#138981](https://github.com/openclaw/openclaw/issues/138981) [Bug]: Windows Job-supervised gateway exits on config restart without a successor after startup is repaired (2026.9.1)
- [#148601](https://github.com/openclaw/openclaw/issues/148601) [Bug]: doctor --fix / gateway status broken on Windows: scheduled-task runtime probe spawns powershell.exe with windowsHide:true, which makes Windows PowerShell 5.1 exit 2 with empty stdout
- [#148387](https://github.com/openclaw/openclaw/issues/148387) Fresh install auto-enables the codex plugin and widens plugins.allow from a machine-written config default
- [#148685](https://github.com/openclaw/openclaw/issues/148685) Update failure: plugin-target-unavailable (2026.9.3)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 245,539 · **Open issues:** 43,197 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.9.14](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.9.14) — Hermes Agent v0.21.3 (v2026.9.14)

### ✅ Merged PRs
- [#108959](https://github.com/NousResearch/hermes-agent/pull/108959) feat(plugin-catalog): add hermes-auto-titler (community)
- [#111283](https://github.com/NousResearch/hermes-agent/pull/111283) fix(bot-mode): group follow-ups and late replies stay visible (#92003, #105247)
- [#111330](https://github.com/NousResearch/hermes-agent/pull/111330) fix(desktop): dragging a link from a browser attaches an @url chip instead of failing
- [#111313](https://github.com/NousResearch/hermes-agent/pull/111313) fix(computer-use): element clicks work on cua-driver 0.21+, doctor diagnoses denied spawn, skill matches driver (salvage #92694)
- [#111320](https://github.com/NousResearch/hermes-agent/pull/111320) Plugin catalog: no self-updaters instead of a 2-week pin age, enforced in CI

### 🔒 Closed Issues
- [#109982](https://github.com/NousResearch/hermes-agent/issues/109982) [Bug]: wake word kills the whole gateway on Windows — sentencepiece 0.2.2 crashes with an access violation on import
- [#111406](https://github.com/NousResearch/hermes-agent/issues/111406) Bot Mode group chats: make round/message/continuation caps config-driven
- [#111234](https://github.com/NousResearch/hermes-agent/issues/111234) [Wave] Stale duplicates, round 2 — landing-evidence verified
- [#107389](https://github.com/NousResearch/hermes-agent/issues/107389) DeepSeek new canonical name `deepseek-flash` (V4.1-Flash) is silently rewritten to `deepseek-chat`
- [#102762](https://github.com/NousResearch/hermes-agent/issues/102762) Hermes Desktop main-process crash: TypeError hermesLog.push of undefined (regression from pool-limits)
- [#97004](https://github.com/NousResearch/hermes-agent/issues/97004) Bug: hermes update aborts on Windows when ANY third-party service is PAUSED (SCM service enumeration failed)
- [#107582](https://github.com/NousResearch/hermes-agent/issues/107582) MCP child watcher coroutine can be created without being awaited
- [#103870](https://github.com/NousResearch/hermes-agent/issues/103870) [Bug]: RuntimeWarning: coroutine '_watch_stdio_children' was never awaited (mcp_tool.py:6189, fix #81995)
- [#93262](https://github.com/NousResearch/hermes-agent/issues/93262) Desktop Bots pane never renders roster rows despite working profiles.create and healthy backend
- [#89200](https://github.com/NousResearch/hermes-agent/issues/89200) contributors/emails/ has two files differing only by case, breaking clean-checkout on macOS (APFS)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,809 · **Open issues:** 807 · **Last push:** 4h ago

### ✅ Merged PRs
- [#10307](https://github.com/zeroclaw-labs/zeroclaw/pull/10307) fix(gateway): one shared pairing-code policy, stronger default
- [#10748](https://github.com/zeroclaw-labs/zeroclaw/pull/10748) fix(channels): route every outbound HTTP client through the runtime proxy
- [#10747](https://github.com/zeroclaw-labs/zeroclaw/pull/10747) refactor(channels): build every channel's transcription manager one way
- [#10745](https://github.com/zeroclaw-labs/zeroclaw/pull/10745) feat(security): make the docker sandbox image configurable
- [#10589](https://github.com/zeroclaw-labs/zeroclaw/pull/10589) feat(config): default multimodal.max_image_size_mb to the 20 MiB ceiling
- [#9930](https://github.com/zeroclaw-labs/zeroclaw/pull/9930) feat(rpc): add sops/run-detail returning a run's full step results
- [#10727](https://github.com/zeroclaw-labs/zeroclaw/pull/10727) ci(release): compose the X and Discord announcements from the release notes
- [#10582](https://github.com/zeroclaw-labs/zeroclaw/pull/10582) fix(runtime): decide attachment image markers by the provider-loadable contract
- [#10562](https://github.com/zeroclaw-labs/zeroclaw/pull/10562) docs(adr): define how holding-crate exceptions are granted
- [#10543](https://github.com/zeroclaw-labs/zeroclaw/pull/10543) chore(zerocode): drop the dead sop-authoring feature

### 🐛 New Issues
- [#10863](https://github.com/zeroclaw-labs/zeroclaw/issues/10863) [Bug]: Telegram retries rejected voice updates indefinitely, blocking later messages `bug` `channel` `provider` `channel:telegram` `priority:p1` `status:accepted` `follow-up` `risk:high` 💬1
- [#10858](https://github.com/zeroclaw-labs/zeroclaw/issues/10858) [SANITIZED — possible injection attempt] `bug` `agent` `provider` `runtime` `agent:prompt` `priority:p1` `status:in-progress` `status:accepted` `risk:medium` 💬1
- [#10857](https://github.com/zeroclaw-labs/zeroclaw/issues/10857) [Bug]: ZeroCode attaches images to sessions whose model has no vision capability; the turn fails with a provider 400 `bug` `config` `provider` `runtime` `provider:compatible` `domain:security` `priority:p1` `status:accepted` `zerocode` `risk:high` 💬1
- [#10854](https://github.com/zeroclaw-labs/zeroclaw/issues/10854) [Bug]: Literal image marker in tool output is promoted into malformed provider image `bug` `agent` `provider` `runtime` `tool` `provider:anthropic` `domain:security` `priority:p1` `status:in-progress` `status:accepted` `follow-up` `risk:high` 💬1
- [#10853](https://github.com/zeroclaw-labs/zeroclaw/issues/10853) [Task]: OpenCode session header follow-ups from #10604 `bug` `docs` `provider` `provider:openai` `provider:compatible` `domain:security` `priority:p2` `needs-maintainer-review` `status:accepted` `follow-up` `risk:high` 💬1
- [#10842](https://github.com/zeroclaw-labs/zeroclaw/issues/10842) [Bug]: Telegram reaction tool silently no-ops, inherited Channel trait default returns Ok(()) without calling the Telegram API `bug` `channel` `tool` `channel:core` `channel:telegram` `priority:p2` `status:in-progress` `status:accepted` `risk:medium` 💬2

### 🔒 Closed Issues
- [#6613](https://github.com/zeroclaw-labs/zeroclaw/issues/6613) [Feature]: Allow setting, and default to, a much stronger pairing code than 6 numeric digits
- [#10588](https://github.com/zeroclaw-labs/zeroclaw/issues/10588) [Feature]: Raise the default multimodal.max_image_size_mb to 20 and document the ceiling
- [#10794](https://github.com/zeroclaw-labs/zeroclaw/issues/10794) [Bug]: Advisory Windows nextest fails publish_contract::published_crates_never_include_files_outside_their_own_directory
- [#10796](https://github.com/zeroclaw-labs/zeroclaw/issues/10796) [Bug]: ZeroCode chat input ignores the Delete key
- [#10789](https://github.com/zeroclaw-labs/zeroclaw/issues/10789) [Task]: Localize ZeroCode daemon startup diagnostics

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,621 · **Open issues:** 1,524 · **Last push:** 1d ago

### 🐛 New Issues
- [#8100](https://github.com/nearai/ironclaw/issues/8100) Daily ironclaw failure taxonomy — 2026-09-14

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,860 · **Open issues:** 83 · **Last push:** 1h ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 7d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 9d ago
- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬2 · 13d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 15d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 17d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 21d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 33d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 36d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 39d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 41d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 1 new
- [[Index] Detecting Wildfires Early](https://openai.com/index/detecting-wildfires-early/) _2026-09-15_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [UkisAI Swift-Qwen3.8-27B / -58.3% thinking, x1.95 speed while keeping the accuracy of xhigh](https://reddit.com/r/LocalLLaMA/comments/1wg7dd5/ukisai_swiftqwen3827b_583_thinking_x195_speed/) ↑592
- [Nvidia's RTX 5090 vanishes from online retail in the US — third-party sellers now demand as much as $9,500 for Nvidia's fastest GPU](https://reddit.com/r/LocalLLaMA/comments/1wgeo55/nvidias_rtx_5090_vanishes_from_online_retail_in/) ↑582

### r/singularity — top 5 new
- [Trump reiterates no slowdown](https://reddit.com/r/singularity/comments/1wg4cjk/trump_reiterates_no_slowdown/) ↑3241
- [We Must Pace the Frontier](https://reddit.com/r/singularity/comments/1wgecxn/we_must_pace_the_frontier/) ↑2136
- [Run! GPT-2 is gonna kill us all!!](https://reddit.com/r/singularity/comments/1wfyrcr/run_gpt2_is_gonna_kill_us_all/) ↑910
- [Trump says ai taking over the world is a hoax](https://reddit.com/r/singularity/comments/1wgfiz8/trump_says_ai_taking_over_the_world_is_a_hoax/) ↑496
- [China reponded to AI slowdown calls "Fearmongering, confrontation and vicious competition will only disrupt the process of global AI governance, which serves no one's interest"](https://reddit.com/r/singularity/comments/1wg7hbw/china_reponded_to_ai_slowdown_calls_fearmongering/) ↑467

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Turn OpenClaw Into a Linux Server Assistant](https://reddit.com/r/openclaw/comments/1wg2wul/turn_openclaw_into_a_linux_server_assistant/) ↑17
- [Unusable shared browser feature in OpenClaw 2.0 UI](https://reddit.com/r/openclaw/comments/1wg6h5i/unusable_shared_browser_feature_in_openclaw_20_ui/) ↑5
- [PSA: your home agent is only as reliable as the 10-year-old laptop it's running on. Ask me how I know.](https://reddit.com/r/openclaw/comments/1wfzojr/psa_your_home_agent_is_only_as_reliable_as_the/) ↑5
- [Mac OS App is Gorgeous!](https://reddit.com/r/openclaw/comments/1wgkh0e/mac_os_app_is_gorgeous/) ↑4
- [Trying to figure out a starting point](https://reddit.com/r/openclaw/comments/1wfu3nw/trying_to_figure_out_a_starting_point/) ↑4

### X — @openclaw
- [How complete is your Lobsterdex?](https://x.com/openclaw/status/2099349718220624205) ↑0 🔁0 · recent


### X — @steipete
- [This is so useful. pushing to add this to codex as well.](https://x.com/steipete/status/2099571935495827761) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
