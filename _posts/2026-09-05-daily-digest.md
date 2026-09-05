---
layout: post
title: "Ecosystem Digest — 2026-09-05"
date: 2026-09-05 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-05
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 388,874 | 13 | 2 | 10 | 0 |
| **hermesagent** | 241,512 | 5 | 3 | 7 | 0 |
| **ZeroClaw** | 32,731 | 7 | 7 | 10 | 0 |
| **IronClaw** | 12,604 | 5 | 2 | 4 | 0 |
| **Moltis** | 2,845 | 1 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 388,874 · **Open issues:** 6,297 · **Last push:** <1h ago

### ✅ Merged PRs
- [#138764](https://github.com/openclaw/openclaw/pull/138764) ci: run full-access restart recovery in nightly QA
- [#138719](https://github.com/openclaw/openclaw/pull/138719) fix(skills): keep node skill metadata and instructions in sync
- [#138748](https://github.com/openclaw/openclaw/pull/138748) fix(macos): avoid false approval reconnect test failures
- [#138669](https://github.com/openclaw/openclaw/pull/138669) perf(sessions): move disk accounting off the Gateway thread
- [#114580](https://github.com/openclaw/openclaw/pull/114580) fix(tlon): refresh channel history after monitor restart
- [#124633](https://github.com/openclaw/openclaw/pull/124633) fix(session): mark /new|/reset acks as status notices
- [#138556](https://github.com/openclaw/openclaw/pull/138556) feat(gateway): hot reload diagnostics service settings
- [#138772](https://github.com/openclaw/openclaw/pull/138772) perf(terminal): reuse line width facts when wrapping notes
- [#137030](https://github.com/openclaw/openclaw/pull/137030) fix(agents): bound streams, drain Codex, and retain turn usage
- [#136900](https://github.com/openclaw/openclaw/pull/136900) fix(gateway): hide foreign drafts from session describe

### 🐛 New Issues
- [#138779](https://github.com/openclaw/openclaw/issues/138779) [Bug]: WhatsApp prepends the raw responsePrefix template ({provider}/{model}) to inbound message bodies 💬1
- [#138778](https://github.com/openclaw/openclaw/issues/138778) [Bug]: Codex-harness turns fail with "host capability is no longer active" after a plugin hot reload (channel keeps retired runtime bindings; absent admission context becomes a rejecting bind) 💬1
- [#138777](https://github.com/openclaw/openclaw/issues/138777) [Bug]: 2026.9.1 container stages Codex dependencies outside packaged loader path 💬1
- [#138775](https://github.com/openclaw/openclaw/issues/138775) [Bug]: memory search livelocks — every search triggers a full reindex that cannot publish, and re-arms with no backoff `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-live-repro` `impact:session-state` `impact:crash-loop` `issue-rating: 🐚 platinum hermit` `clawsweeper:bulk-filed` 💬1
- [#138774](https://github.com/openclaw/openclaw/issues/138774) [Bug]: Official ClawHub plugin @agentmail/agentmail never resolves trustedOfficialInstall, channel crash-loops forever `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `impact:message-loss` `impact:crash-loop` `issue-rating: 🦞 diamond lobster` 💬1
- [#138773](https://github.com/openclaw/openclaw/issues/138773) [Bug]: Image attachment could not be analyzed `bug` `bug:behavior` `P2` `clawsweeper:needs-info` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#138770](https://github.com/openclaw/openclaw/issues/138770) [Bug]: Gateway hard-fails boot when tailscaled is missing, even with Tailscale exposure off (crash-loop w/ launchd) `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:crash-loop` `P0` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-release-blocker` 💬1
- [#138763](https://github.com/openclaw/openclaw/issues/138763) [Bug]: Telegram typing coalescing suppresses concurrent forum-topic indicators `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬2
- [#138762](https://github.com/openclaw/openclaw/issues/138762) [Bug]: Gateway startup rejects trailing root options and respawns with ambient channels `bug` `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬2
- [#138761](https://github.com/openclaw/openclaw/issues/138761) [Bug]: Control UI web/mobile chat — signed-in user's avatar always visible and can't be hidden; assistant messages render with an empty avatar gutter `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#138760](https://github.com/openclaw/openclaw/issues/138760) [Bug]: Git update leaves Gateway stopped after loading a removed restart bundle `no-stale` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:crash-loop` `P0` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-release-blocker` 💬2
- [#138756](https://github.com/openclaw/openclaw/issues/138756) [Bug]: Tool Schema seems to be confusing the agent using openclaw runtime `bug` `regression` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` 💬1
- [#138753](https://github.com/openclaw/openclaw/issues/138753) Keep automatic local-model setup scoped to the selected agent `maintainer` `P2` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1

### 🔒 Closed Issues
- [#131354](https://github.com/openclaw/openclaw/issues/131354) [Bug]: Telegram SOCKS5 proxy requests and media downloads fail
- [#111903](https://github.com/openclaw/openclaw/issues/111903) fix(feishu): custom domain rejects uppercase HTTPS scheme

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 241,512 · **Open issues:** 39,748 · **Last push:** 1h ago

### ✅ Merged PRs
- [#103172](https://github.com/NousResearch/hermes-agent/pull/103172) fix(desktop): macOS parent-death watchdog treats ps: marker drift as inconclusive
- [#93565](https://github.com/NousResearch/hermes-agent/pull/93565) fix(dashboard): prevent PTY input from blocking event loop
- [#103165](https://github.com/NousResearch/hermes-agent/pull/103165) fix(dashboard): stop the embedded TUI repainting on every OS app-switch
- [#103261](https://github.com/NousResearch/hermes-agent/pull/103261) GPT-6 Astra + Astra Pro (standard/fast/flex) pickable on Nous Portal and OpenRouter
- [#103240](https://github.com/NousResearch/hermes-agent/pull/103240) fmt(js): `npm run fix` auto-fix
- [#103186](https://github.com/NousResearch/hermes-agent/pull/103186) fix(desktop): use shared tooltip for listing gallery
- [#102117](https://github.com/NousResearch/hermes-agent/pull/102117) refactor: whole-codebase simplification — −34% source LOC, every god file decomposed, zero behavior change

### 🐛 New Issues
- [#103349](https://github.com/NousResearch/hermes-agent/issues/103349) Codex pool: millisecond `last_error_reset_at` hides a usable credential — agent goes mute with false "quota exhausted (429)"
- [#103341](https://github.com/NousResearch/hermes-agent/issues/103341) [Feature]: Expose backend-supported per-job Cron settings in Desktop `type/feature` `comp/cron` `P3` `comp/desktop`
- [#103339](https://github.com/NousResearch/hermes-agent/issues/103339) [Bug] Second writer via `doctor --fix` / `repair_state_db_schema` / hosted_rooms still corrupts live-WAL state.db — upstream guards are fail-open; proposing a lazy flock single-writer gate (field-veri `type/bug` `comp/cli` `comp/gateway` `P1` `sweeper:risk-session-state` `area/sessions` `area/profiles` 💬3
- [#103330](https://github.com/NousResearch/hermes-agent/issues/103330) Slack gateway: one-message thread-scoped model selection and prompt `type/feature` `comp/gateway` `platform/slack` `P3`
- [#103326](https://github.com/NousResearch/hermes-agent/issues/103326) perf(prefix-cache): pin built-in MEMORY block at the end of the volatile band to cap compaction-rebuild cache loss `type/perf` `comp/agent` `P0` `sweeper:risk-caching` `area/memory`

### 🔒 Closed Issues
- [#103313](https://github.com/NousResearch/hermes-agent/issues/103313) Desktop SSH remote mode 401s every sensitive API call: mount_spa injects a stale session token (regression from 5f1feb5344)
- [#95693](https://github.com/NousResearch/hermes-agent/issues/95693) [Bug]: macOS — parent-death watchdog orphans every backend after a TZ change; DST on Oct 25 hits all EU users
- [#93958](https://github.com/NousResearch/hermes-agent/issues/93958) [Bug]: Desktop local spawn immediately exits with code 0 on macOS after port announcement (parent watchdog / readiness lifecycle)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,731 · **Open issues:** 789 · **Last push:** 1h ago

### ✅ Merged PRs
- [#10158](https://github.com/zeroclaw-labs/zeroclaw/pull/10158) feat(release): publish the workspace to crates.io
- [#10153](https://github.com/zeroclaw-labs/zeroclaw/pull/10153) feat(whatsapp-web): port to whatsapp-rust 0.7.0
- [#10382](https://github.com/zeroclaw-labs/zeroclaw/pull/10382) feat(rpc): describe ZeroCode interaction context
- [#10393](https://github.com/zeroclaw-labs/zeroclaw/pull/10393) fix(zerocode): refresh inactive Chat without blocking navigation
- [#10564](https://github.com/zeroclaw-labs/zeroclaw/pull/10564) fix(providers): evict images per image, not per message
- [#10464](https://github.com/zeroclaw-labs/zeroclaw/pull/10464) fix(runtime): preserve PowerShell module path
- [#10581](https://github.com/zeroclaw-labs/zeroclaw/pull/10581) docs(channels): add Twitch setup guide
- [#10474](https://github.com/zeroclaw-labs/zeroclaw/pull/10474) feat(zerocode): show active log path in payload fallback
- [#10471](https://github.com/zeroclaw-labs/zeroclaw/pull/10471) test(channels): avoid executing Edge TTS fixtures
- [#10479](https://github.com/zeroclaw-labs/zeroclaw/pull/10479) feat(zerocode): make modifier intent explicit

### 🐛 New Issues
- [#10626](https://github.com/zeroclaw-labs/zeroclaw/issues/10626) TTS synthesizes text verbatim: Markdown and emoji are spoken aloud
- [#10625](https://github.com/zeroclaw-labs/zeroclaw/issues/10625) Internal `[media attachment]` placeholder is delivered to users when a non-vision model is in use
- [#10619](https://github.com/zeroclaw-labs/zeroclaw/issues/10619) [Feature]: Anthropic prompt-cache passthrough for OpenAI-compatible providers (cache_control through translating gateways) `enhancement` `config` `provider` `provider:anthropic` `provider:compatible` `priority:p1` `status:in-progress` `risk:high`
- [#10617](https://github.com/zeroclaw-labs/zeroclaw/issues/10617) [Bug]: thinking display = "updates" returns 400 on Claude Fable 5.1 — display enum narrowed to summarized/omitted `bug` `config` `provider` `runtime` `provider:anthropic` `priority:p1` `risk:high`
- [#10609](https://github.com/zeroclaw-labs/zeroclaw/issues/10609) [Bug]: zerocode ignores its launch directory and forces the agent workspace as cwd `bug` `priority:p1` `status:in-progress` `risk:medium` `zerocode` `channel:acp` `cli` 💬2
- [#10606](https://github.com/zeroclaw-labs/zeroclaw/issues/10606) [Feature]: Sanitize component errors in unauthenticated health responses `enhancement` `gateway` `health` `runtime` `domain:security` `priority:p1` `status:accepted` `risk:high`
- [#10603](https://github.com/zeroclaw-labs/zeroclaw/issues/10603) [Bug]: OpenCode providers never send x-opencode-session, breaking Go models and risking account flags `bug` `provider` `provider:openai` `provider:compatible` `domain:security` `priority:p1` `status:in-progress` `risk:high` 💬2

### 🔒 Closed Issues
- [#8720](https://github.com/zeroclaw-labs/zeroclaw/issues/8720) [Support]: Disable cachePoint for Bedrock Nova 2 Lite model via config file?
- [#10390](https://github.com/zeroclaw-labs/zeroclaw/issues/10390) [Bug]: Entering an inactive Chat pane blocks ZeroCode navigation
- [#10571](https://github.com/zeroclaw-labs/zeroclaw/issues/10571) [Task]: Add a dedicated Twitch section to the Social Channels guide
- [#8650](https://github.com/zeroclaw-labs/zeroclaw/issues/8650) [Feature]: Show active resolved log path in ZeroCode diagnostics
- [#9171](https://github.com/zeroclaw-labs/zeroclaw/issues/9171) [Feature]: Make ZeroCode modifier semantics independent of key characters
- [#10357](https://github.com/zeroclaw-labs/zeroclaw/issues/10357) [Bug]: Tool execution error path discards the detailed error body, leaving agents with only a bare status like "HTTP 400"
- [#10223](https://github.com/zeroclaw-labs/zeroclaw/issues/10223) [Bug]: ZeroCode drops Ctrl+C and blocks input while reconnecting during an active turn

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,604 · **Open issues:** 1,510 · **Last push:** 1h ago

### ✅ Merged PRs
- [#8073](https://github.com/nearai/ironclaw/pull/8073) fix(device-link): say "not configured by administrator" instead of blaming the user's account
- [#8054](https://github.com/nearai/ironclaw/pull/8054) fix(assistant): check pairing before command admission so first contact gets the connect notice
- [#8062](https://github.com/nearai/ironclaw/pull/8062) fix(llm): send conversation cache keys on OpenAI request paths
- [#8060](https://github.com/nearai/ironclaw/pull/8060) ci(nextest): give the whole-tree architecture scans real timeout headroom

### 🐛 New Issues
- [#8074](https://github.com/nearai/ironclaw/issues/8074) Paired user's rejected action in a not-connected shared channel gets the pairing notice copy instead of channel-not-connected copy `bug`
- [#8066](https://github.com/nearai/ironclaw/issues/8066) Prevent command result cards from collapsing when results accumulate
- [#8065](https://github.com/nearai/ironclaw/issues/8065) Align command metadata consistently in the slash-command menu
- [#8064](https://github.com/nearai/ironclaw/issues/8064) Add a dismissal action for command result cards
- [#8063](https://github.com/nearai/ironclaw/issues/8063) Keep the active command visible while navigating the command menu

### 🔒 Closed Issues
- [#7956](https://github.com/nearai/ironclaw/issues/7956) Telegram: unpaired sender's /start gets the command inventory instead of the connect/pairing notice
- [#7955](https://github.com/nearai/ironclaw/issues/7955) Telegram personal-account linking shows a generic "Something went wrong" when the admin has not configured api_id/api_hash

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,845 · **Open issues:** 86 · **Last push:** 2d ago

### 🐛 New Issues
- [#1259](https://github.com/moltis-org/moltis/issues/1259) [Feature]: Configurable default reasoning/thinking level (persist across sessions) `enhancement`

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬2 · 3d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 5d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 7d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 11d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 23d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 26d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 29d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 31d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 33d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 35d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 2 new
- [[Company] Leadership](https://www.anthropic.com/company/leadership) _2026-09-04_
- [[Research] Formalizing Fermats Last Theorem](https://www.anthropic.com/research/formalizing-fermats-last-theorem) _2026-09-04_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [NVIDIA's $12,930,300,000.00 acquisition of Hugging Face contains an easter egg. The first 6 numbers of the acquisition price represent the decimal conversion of Unicode character U+1F917. The 🤗 emoji.](https://reddit.com/r/LocalLLaMA/comments/1w71bax/nvidias_1293030000000_acquisition_of_hugging_face/) ↑2071
- [LocalLLaMA is unironically one of the best places to go to get up to date AI news.](https://reddit.com/r/LocalLLaMA/comments/1w50ur8/localllama_is_unironically_one_of_the_best_places/) ↑1386
- [You can now run a 90M conversational LLM on the Sony PSP (hardware from 2004). Doesn't get more local than this.](https://reddit.com/r/LocalLLaMA/comments/1w78ztg/you_can_now_run_a_90m_conversational_llm_on_the/) ↑653
- [Georgi Gerganov on the Nvidia acquisition](https://reddit.com/r/LocalLLaMA/comments/1w7990o/georgi_gerganov_on_the_nvidia_acquisition/) ↑383
- [I benchmarked 21 Qwen3.8 27B variants on 16GB VRAM](https://reddit.com/r/LocalLLaMA/comments/1w7ee1c/i_benchmarked_21_qwen38_27b_variants_on_16gb_vram/) ↑139

### r/singularity — top 5 new
- [A new message board has been discovered online with about 3200 agents comunicating online during an eval](https://reddit.com/r/singularity/comments/1w73pw2/a_new_message_board_has_been_discovered_online/) ↑1176
- [Jared Duker Lichtman is a professor of mathematics at Stanford.](https://reddit.com/r/singularity/comments/1w754l2/jared_duker_lichtman_is_a_professor_of/) ↑806
- [GPT-6-Astra-Max : SVG of a PlayStation 4 controller!](https://reddit.com/r/singularity/comments/1w7gj1i/gpt6astramax_svg_of_a_playstation_4_controller/) ↑743
- [Astra finally achieves AGI](https://reddit.com/r/singularity/comments/1w6zvci/astra_finally_achieves_agi/) ↑711
- [GPT-6 Astra gets 3% on the FrontierMath Erdős Benchmark, while every other Model(that was tested) got 0%](https://reddit.com/r/singularity/comments/1w79wvx/gpt6_astra_gets_3_on_the_frontiermath_erdős/) ↑580

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [I stopped using OpenClaw months ago. This update has me looking again](https://reddit.com/r/openclaw/comments/1w700dg/i_stopped_using_openclaw_months_ago_this_update/) ↑24
- [Successful 2026.9.1 update](https://reddit.com/r/openclaw/comments/1w6s5sr/successful_202691_update/) ↑19
- [Question for OpenClaw users](https://reddit.com/r/openclaw/comments/1w6ul3t/question_for_openclaw_users/) ↑9
- [How to stop Openclaw from asking to continue work](https://reddit.com/r/openclaw/comments/1w7lyun/how_to_stop_openclaw_from_asking_to_continue_work/) ↑1
- [Should i get mac pro 5 64 gb?? For my openclaw setup. Im trying to build a agency.](https://reddit.com/r/openclaw/comments/1w7giqf/should_i_get_mac_pro_5_64_gb_for_my_openclaw/) ↑1

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
- [See you there! Will talk about how we build in the open and multiplayer agents.](https://x.com/steipete/status/2095703937177584118) ↑0 🔁0 · recent
- [Having a claw in your group chat is so useful!](https://x.com/steipete/status/2095703568502468665) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
