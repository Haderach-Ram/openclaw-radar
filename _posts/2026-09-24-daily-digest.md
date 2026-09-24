---
layout: post
title: "Ecosystem Digest — 2026-09-24"
date: 2026-09-24 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-24
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 390,349 | 8 | 3 | 10 | 1 |
| **hermesagent** | 248,425 | 6 | 1 | 8 | 0 |
| **ZeroClaw** | 32,877 | 6 | 0 | 3 | 0 |
| **IronClaw** | 12,631 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,869 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 390,349 · **Open issues:** 8,418 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.9.6](https://github.com/openclaw/openclaw/releases/tag/v2026.9.6) — openclaw 2026.9.6

### ✅ Merged PRs
- [#156872](https://github.com/openclaw/openclaw/pull/156872) perf(agents): prepare workers before run cleanup
- [#156918](https://github.com/openclaw/openclaw/pull/156918) fix(ui): keep failed sidebar sessions on one line
- [#156916](https://github.com/openclaw/openclaw/pull/156916) fix(docs): link release notes to the alternate reading format
- [#155259](https://github.com/openclaw/openclaw/pull/155259) improve(plugins): give bundled logos consistent white icon tiles
- [#156824](https://github.com/openclaw/openclaw/pull/156824) fix(state): observe foreign commits on the next database read
- [#156922](https://github.com/openclaw/openclaw/pull/156922) perf(state): share freshness probes within session reads
- [#156677](https://github.com/openclaw/openclaw/pull/156677) refactor: restore max-lines headroom in tests and state worker dispatch
- [#156921](https://github.com/openclaw/openclaw/pull/156921) fix(ui): remove blank space from nested tool groups
- [#156686](https://github.com/openclaw/openclaw/pull/156686) refactor(agents): read sandbox reporting asynchronously
- [#156811](https://github.com/openclaw/openclaw/pull/156811) fix(release): require Gateway and Telegram validation

### 🐛 New Issues
- [#156930](https://github.com/openclaw/openclaw/issues/156930) [Bug]: Codex resident catalog PLUGIN_STATE_OPEN_FAILED every 30s on 2026.9.6 despite successful DB/catalog reads; persists after restart `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#156925](https://github.com/openclaw/openclaw/issues/156925) Webchat renders assistant replies twice on turns that use tool calls `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:session-state` `issue-rating: 🐚 platinum hermit` `impact:ux-friction` 💬1
- [#156917](https://github.com/openclaw/openclaw/issues/156917) State-lifecycle lease has no holder heartbeat or forced takeover: one hung client blocks gateway startup for 47 minutes (crash-restart loop) `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:crash-loop` `P0` `issue-rating: 🐚 platinum hermit` `impact:ux-release-blocker` `clawsweeper:manual-only` 💬2
- [#156910](https://github.com/openclaw/openclaw/issues/156910) Update failure: global-install-failed (2026.9.4) `P0` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-release-blocker` `clawsweeper:manual-only` 💬2
- [#156898](https://github.com/openclaw/openclaw/issues/156898) [Bug] 2026.9.6: usage-cost background refresh repeatedly exhausts worker heap; SQLite refresh materializes full transcript `P1` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` `maturity:stable` `clawsweeper:manual-only` 💬2
- [#156896](https://github.com/openclaw/openclaw/issues/156896) [Bug]: Doctor legacy capture cleanup misidentifies unrelated Node.js services as OpenClaw processes `P1` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `maturity:stable` `clawsweeper:manual-only` 💬2
- [#156895](https://github.com/openclaw/openclaw/issues/156895) [automations] Agent-created jobs fail closed in ~20ms with "Scheduled account ... is unavailable" although the account is configured `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:needs-live-repro` `impact:security` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬4
- [#156893](https://github.com/openclaw/openclaw/issues/156893) [Bug]: git update exits 79 as already-current when dist was built from another commit `clawsweeper:source-repro` `P0` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-release-blocker` `clawsweeper:manual-only` 💬2

### 🔒 Closed Issues
- [#151137](https://github.com/openclaw/openclaw/issues/151137) Control UI shows a view_image result as a non-recoverable "Omitted from history" placeholder
- [#156912](https://github.com/openclaw/openclaw/issues/156912) [Bug]: OpenClaw.app 2026.9.6 (arm64) aborts at launch — swift_task_dealloc fatal error in ChildProcessExit.wait(timeout:)
- [#156920](https://github.com/openclaw/openclaw/issues/156920) [update] In-chat /update handoff fails at managed-service-preflight: helper cannot detach from the gateway process tree

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 248,425 · **Open issues:** 44,047 · **Last push:** <1h ago

### ✅ Merged PRs
- [#117550](https://github.com/NousResearch/hermes-agent/pull/117550) fix(tui-gateway): bind profile secret scope around Desktop /review
- [#120864](https://github.com/NousResearch/hermes-agent/pull/120864) test(e2e): two-tenant gateway test survives a port taken before bind
- [#120002](https://github.com/NousResearch/hermes-agent/pull/120002) Catalog Little Canary native prompt screening plugin
- [#120843](https://github.com/NousResearch/hermes-agent/pull/120843) fix(update): launches racing an interrupted-update restore take turns and keep edits (follow-up #120339)
- [#120850](https://github.com/NousResearch/hermes-agent/pull/120850) plugin-catalog: bump mnemosyne to 0.7.3 (salvage of #120765)
- [#120738](https://github.com/NousResearch/hermes-agent/pull/120738) fix(plugin-catalog): persist TamaHermes session-end events
- [#120673](https://github.com/NousResearch/hermes-agent/pull/120673) chore(catalog): add AgentPlaybooks memory artwork and current README
- [#120611](https://github.com/NousResearch/hermes-agent/pull/120611) feat(plugin-catalog): bump bot-forge to v0.5.0

### 🐛 New Issues
- [#120906](https://github.com/NousResearch/hermes-agent/issues/120906) bug(context): /context reports a deduplicated AGENTS.md copy as loaded `type/bug` `comp/agent` `P2`
- [#120904](https://github.com/NousResearch/hermes-agent/issues/120904) bug(gateway): fence-balanced chunks exceed the caller's limit for language tags over 8 characters `type/bug` `comp/gateway` `P2` `sweeper:risk-message-delivery`
- [#120897](https://github.com/NousResearch/hermes-agent/issues/120897) [Bug]: Kaspersky false positive: desktop electron-main.mjs flagged as HEUR:Trojan-PSW.JS.Disco.gen (Windows, build-from-source) `type/bug` `P3` `comp/desktop` `platform/windows`
- [#120892](https://github.com/NousResearch/hermes-agent/issues/120892) [Feature]: Teams — processing acknowledgement in channel threads (on_processing_start is a no-op; typing indicator can't render there) `type/feature` `comp/plugins` `P3`
- [#120888](https://github.com/NousResearch/hermes-agent/issues/120888) Full backup can run indefinitely under concurrent writes despite BUSY/LOCKED timeout `type/bug` `comp/cli` `P2` `area/install-update`
- [#120887](https://github.com/NousResearch/hermes-agent/issues/120887) Desktop SSH model picker omits external-process provider when backend PATH excludes user-local CLI `type/bug` `backend/ssh` `comp/cli` `area/auth` `P2` `comp/desktop`

### 🔒 Closed Issues
- [#117544](https://github.com/NousResearch/hermes-agent/issues/117544) [Bug]: /review fails UnscopedSecretError on HERMES_CODEX_BASE_URL when auxiliary.review.provider is openai-codex (multiplexed Desktop serve)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,877 · **Open issues:** 753 · **Last push:** 3h ago

### ✅ Merged PRs
- [#10818](https://github.com/zeroclaw-labs/zeroclaw/pull/10818) perf(docs): promote stable metadata without rebuilding
- [#10816](https://github.com/zeroclaw-labs/zeroclaw/pull/10816) fix(release): check Apple notarization before compilation
- [#10815](https://github.com/zeroclaw-labs/zeroclaw/pull/10815) fix(release): order versioned dev dependencies before publication

### 🐛 New Issues
- [#11075](https://github.com/zeroclaw-labs/zeroclaw/issues/11075) [Feature]: Add `agy_cli` coding-CLI tool for Antigravity CLI (peer of `codex_cli` / `claude_code`)
- [#11074](https://github.com/zeroclaw-labs/zeroclaw/issues/11074) RFC: search_routes — hint-based provider routing for web_search_tool
- [#11059](https://github.com/zeroclaw-labs/zeroclaw/issues/11059) [Bug]: WhatsApp Web ignores force_voice, so send_via cannot route a turn to voice 💬1
- [#11055](https://github.com/zeroclaw-labs/zeroclaw/issues/11055) [Bug]: The daemon never registers the channel-map factory, so webhook, cron and SOP turns have no channels 💬2
- [#11052](https://github.com/zeroclaw-labs/zeroclaw/issues/11052) [Feature]: Render thematic breaks and setext headings for WhatsApp `enhancement` 💬4
- [#11050](https://github.com/zeroclaw-labs/zeroclaw/issues/11050) [Feature]: Pace native polls with other outbound channel messages `enhancement` `channel` `tool` `channel:core` `channel:whatsapp` `priority:p3` `follow-up` `risk:medium` 💬1

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,631 · **Open issues:** 1,530 · **Last push:** 2h ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,869 · **Open issues:** 96 · **Last push:** 1d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 1d ago
- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬3 · 5d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 8d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 16d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 18d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 26d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 30d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 42d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 45d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 48d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Claude Discovers Novel Enzyme System](https://www.anthropic.com/news/claude-discovers-novel-enzyme-system) _2026-09-23_

### OpenAI — 7 new
- [[Index] Ringg](https://openai.com/index/ringg/) _2026-09-23_
- [[Index] Invideo Builds With Gpt 6 Astra](https://openai.com/index/invideo-builds-with-gpt-6-astra/) _2026-09-23_
- [[Index] Airbnb Gpt 6 Astra](https://openai.com/index/airbnb-gpt-6-astra/) _2026-09-23_
- [[Index] Two Years Of Openai Academy](https://openai.com/index/two-years-of-openai-academy/) _2026-09-23_
- [[Index] Openai Extends Cyber Access To Ukraine For Civilian Defense](https://openai.com/index/openai-extends-cyber-access-to-ukraine-for-civilian-defense/) _2026-09-24_
- [[Index] Sam Altman Un Security Council Remarks](https://openai.com/index/sam-altman-un-security-council-remarks/) _2026-09-23_
- [[Index] Grab Openai Ai Skills Southeast Asia](https://openai.com/index/grab-openai-ai-skills-southeast-asia/) _2026-09-23_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Qwen 4 Announced at Apsara Conference](https://reddit.com/r/LocalLLaMA/comments/1wmxfjs/qwen_4_announced_at_apsara_conference/) ↑2003
- [Mods: can we do something about half the forum getting filled with these advertising posts for Jev?](https://reddit.com/r/LocalLLaMA/comments/1wo6o0f/mods_can_we_do_something_about_half_the_forum/) ↑952
- [Pirate Face - pirate bay for LLMs](https://reddit.com/r/LocalLLaMA/comments/1wnxhji/pirate_face_pirate_bay_for_llms/) ↑812
- [this is not even a competition at this point ... this is embarrassing](https://reddit.com/r/LocalLLaMA/comments/1wnzlav/this_is_not_even_a_competition_at_this_point_this/) ↑478
- [Jev isn't new tech. Its marketing targets people who think AI started with LLMs.](https://reddit.com/r/LocalLLaMA/comments/1woe70t/jev_isnt_new_tech_its_marketing_targets_people/) ↑407

### r/singularity — top 2 new
- [I asked Claude to show me the inside of its own mind. Built by Opus 5.5](https://reddit.com/r/singularity/comments/1wok9tq/i_asked_claude_to_show_me_the_inside_of_its_own/) ↑822
- [The moment Claude agents discover a new molecular mechanism, talking as if they were human, using interjections and cues](https://reddit.com/r/singularity/comments/1wognfz/the_moment_claude_agents_discover_a_new_molecular/) ↑518

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Openclaw agents](https://reddit.com/r/openclaw/comments/1wo85if/openclaw_agents/) ↑10
- [PinchBench Tests for QWEN & Nemotron - Surprising Results](https://reddit.com/r/openclaw/comments/1wo5yha/pinchbench_tests_for_qwen_nemotron_surprising/) ↑6
- [Has anyone been able to get gpt6 Luna CLI (subscription) to work with openclaw?](https://reddit.com/r/openclaw/comments/1wo8ooi/has_anyone_been_able_to_get_gpt6_luna_cli/) ↑4
- [Can you use multiple subscriptions ie both Claude and chatgpt in same OpenClaw instance](https://reddit.com/r/openclaw/comments/1wnz8ib/can_you_use_multiple_subscriptions_ie_both_claude/) ↑3
- [So i did nothing aside installed v5](https://reddit.com/r/openclaw/comments/1woan3d/so_i_did_nothing_aside_installed_v5/) ↑2

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [Everything's coming up Jev!

Last week 
@jlehman_
 pushed support for decision models in OpenClaw core and for plugins

](https://x.com/openclaw/status/2102488199486656862)

### X — @steipete
- [Huh. There is a catch.](https://x.com/steipete/status/2102889319849713698) ↑0 🔁0 · recent
- [So cool to have 
@allietheicon
 [from Jev/TypeSafe] be part of our ClawCast on Discord! 
https://
discord.com/invite/cla](https://x.com/steipete/status/2102839395766472969) ↑0 🔁0 · recent
- [CodexBar learned a few new tricks in the last few weeks!

TypeSafe, Nous Portal, Muse Code, CodeRabbit, Replicate, Huggi](https://x.com/steipete/status/2102672670689275965) ↑0 🔁0 · recent
- [There's also a new plugin system where you can write new providers as JS plugins to make the app more modular.](https://x.com/steipete/status/2102672956271083858) ↑0 🔁0 · recent
- [Next version of OpenClaw uses a decision model to automatically decide between steer or queue. 

(Lab feature, we suppor](https://x.com/steipete/status/2102667004557832497) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
