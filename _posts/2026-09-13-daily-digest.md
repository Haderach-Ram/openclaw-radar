---
layout: post
title: "Ecosystem Digest — 2026-09-13"
date: 2026-09-13 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-13
*Generated 21:22 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 389,588 | 4 | 1 | 10 | 0 |
| **hermesagent** | 245,081 | 11 | 2 | 8 | 0 |
| **ZeroClaw** | 32,786 | 9 | 1 | 10 | 0 |
| **IronClaw** | 12,619 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,858 | 0 | 1 | 3 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 389,588 · **Open issues:** 7,146 · **Last push:** <1h ago

### ✅ Merged PRs
- [#147002](https://github.com/openclaw/openclaw/pull/147002) perf(discord): reuse candidate frame text
- [#144790](https://github.com/openclaw/openclaw/pull/144790) fix(channels): show progress-card notes in drafts
- [#147056](https://github.com/openclaw/openclaw/pull/147056) refactor: share sessions and transport test runtimes
- [#146671](https://github.com/openclaw/openclaw/pull/146671) fix(mcp): enforce requester policy on managed tools
- [#146409](https://github.com/openclaw/openclaw/pull/146409) fix(outbound): guard cross-provider topic mutations
- [#146389](https://github.com/openclaw/openclaw/pull/146389) fix(security): block HOMEBREW_CURL_PATH and HOMEBREW_GIT_PATH from workspace .env
- [#146356](https://github.com/openclaw/openclaw/pull/146356) fix(nextcloud-talk): reject excess concurrent webhook reads
- [#146352](https://github.com/openclaw/openclaw/pull/146352) fix(plugins): keep workspace plugins out of auto-enable
- [#146297](https://github.com/openclaw/openclaw/pull/146297) fix(browser): guard explicit download navigation
- [#146084](https://github.com/openclaw/openclaw/pull/146084) fix(gateway): honor actions.sendMessage for update lifecycle notices

### 🐛 New Issues
- [#147161](https://github.com/openclaw/openclaw/issues/147161) [Bug]: Sidebar parent row shows "execution failed" from a two-day-old child session with no age or origin cue
- [#147160](https://github.com/openclaw/openclaw/issues/147160) Update failure: finalize:doctor (2026.9.4)
- [#147157](https://github.com/openclaw/openclaw/issues/147157) memory-core dreaming-narrative hangs 994s per run and starves turn-slot budget across all agents
- [#147149](https://github.com/openclaw/openclaw/issues/147149) [Bug]: signed node clients using default backend metadata disconnect before pairing `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#143431](https://github.com/openclaw/openclaw/issues/143431) [Bug]: Discord shows “Progress updated” but provides no access to progress-card text

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 245,081 · **Open issues:** 42,626 · **Last push:** 1h ago

### ✅ Merged PRs
- [#109977](https://github.com/NousResearch/hermes-agent/pull/109977) gateway migrate --standalone refuses a malformed manifest before mutating; dry-run plan matches the run (follow-up #109962)
- [#109963](https://github.com/NousResearch/hermes-agent/pull/109963) fix(discord): unusable liveness knob values warn instead of disabling the watchdog silently (#109521, salvage #109782)
- [#109957](https://github.com/NousResearch/hermes-agent/pull/109957) fix(auxiliary): /reasoning reaches CommandCode Anthropic-wire aux calls again (follow-up #109530)
- [#109962](https://github.com/NousResearch/hermes-agent/pull/109962) gateway migrate --standalone completes and --dry-run no longer mutates (#109473, salvage #109478 + #109490)
- [#109320](https://github.com/NousResearch/hermes-agent/pull/109320) Resumed sessions and live requests send identical history bytes (#105236 §6, salvage #105308)
- [#109947](https://github.com/NousResearch/hermes-agent/pull/109947) fix(copilot-acp): fetch_models None-on-failure contract; bounded probe budget; refresh-proof memo (follow-up #108874)
- [#109567](https://github.com/NousResearch/hermes-agent/pull/109567) refactor(ts): seven duplicate TS clusters collapse into @hermes/shared; dead web slash re-implementation deleted; desktop slash block-list derives from the Python command registry
- [#108874](https://github.com/NousResearch/hermes-agent/pull/108874) fix(models): copilot-acp picker lists the signed-in session's models; one CLI probe per 5 min, not per /model switch (salvage #108614)

### 🐛 New Issues
- [#110039](https://github.com/NousResearch/hermes-agent/issues/110039) Bot Screen: `-AcceptSetDesktopSize` lets a client send type 251, which the RFB filter refuses as unknown
- [#110038](https://github.com/NousResearch/hermes-agent/issues/110038) [Bug]: Slack compact tool previews show redundant quotes outside inline code
- [#110037](https://github.com/NousResearch/hermes-agent/issues/110037) Bot Screen: the portal's `display.status` fetch carries no request token, so a stale snapshot can move the runtime fields backwards
- [#110036](https://github.com/NousResearch/hermes-agent/issues/110036) [SANITIZED — possible injection attempt]
- [#110035](https://github.com/NousResearch/hermes-agent/issues/110035) `wait_for_human` asks for 600s while the sequential tool runner allows 420s, and `computer_use` is not deadline-exempt
- [#110033](https://github.com/NousResearch/hermes-agent/issues/110033) [Bug][Desktop/macOS] Narrow sidebar overlay tab strip slides under the traffic lights
- [#110032](https://github.com/NousResearch/hermes-agent/issues/110032) browser and computer_use caches are keyed by session id alone, so one profile can receive another profile's session and backend
- [#110029](https://github.com/NousResearch/hermes-agent/issues/110029) Bot Screen: `AGENT_BROWSER_PROFILE` silently ignores a relative or `~` path, and the docs say it just works `type/bug` `comp/tools` `tool/browser` `P3`
- [#110027](https://github.com/NousResearch/hermes-agent/issues/110027) Bot Screen: `test_status_reports_the_headed_browser_or_its_absence` fails off Linux and carries no OS marker `type/test` `comp/tools` `tool/browser` `P3`
- [#110015](https://github.com/NousResearch/hermes-agent/issues/110015) [Bug]: MoA fan-out never stamps `_touch_activity` — turn-liveness watchdog kills healthy advisor streams at 600s while the aux stream ceiling permits 3600s `type/bug` `comp/agent` `area/config` `P2` 💬1
- [#110014](https://github.com/NousResearch/hermes-agent/issues/110014) opencode-free rate-limits all models + picker shows models that 401 `type/bug` `comp/cli` `P3` `needs-repro`

### 🔒 Closed Issues
- [#109331](https://github.com/NousResearch/hermes-agent/issues/109331) Curator backup can create a snapshot its rollback rejects on absolute symlinks
- [#109473](https://github.com/NousResearch/hermes-agent/issues/109473) [Bug]: `hermes gateway migrate --standalone` ignores --dry-run, kills itself mid-rollback, and leaves a stale served_profiles that blocks every repair with exit 78

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,786 · **Open issues:** 823 · **Last push:** <1h ago

### ✅ Merged PRs
- [#10686](https://github.com/zeroclaw-labs/zeroclaw/pull/10686) fix(config): map openai-chat/openai_chat V2 kind to canonical openai family
- [#10016](https://github.com/zeroclaw-labs/zeroclaw/pull/10016) fix(hooks): correlate webhook audit calls by identity
- [#10554](https://github.com/zeroclaw-labs/zeroclaw/pull/10554) fix(tools): reuse configured provider refs for agents
- [#10240](https://github.com/zeroclaw-labs/zeroclaw/pull/10240) docs(contributing): narrow screenshot evidence rule
- [#9927](https://github.com/zeroclaw-labs/zeroclaw/pull/9927) feat(intake): narrow RFC routing across intake surfaces
- [#10598](https://github.com/zeroclaw-labs/zeroclaw/pull/10598) chore(deps): bump docker/setup-buildx-action from 3.11.1 to 4.3.0
- [#10248](https://github.com/zeroclaw-labs/zeroclaw/pull/10248) feat(security): canonical principals and shared grant resolution (#8289 stage 2, supersedes #8672 in part)
- [#8908](https://github.com/zeroclaw-labs/zeroclaw/pull/8908) feat(plugins): add package catalog to plugin list
- [#9139](https://github.com/zeroclaw-labs/zeroclaw/pull/9139) feat(plugins): add durable scheduler outbox foundation
- [#10751](https://github.com/zeroclaw-labs/zeroclaw/pull/10751) fix(plugins): report a full plugin connection budget as connection-limit-reached, not a denial

### 🐛 New Issues
- [#10826](https://github.com/zeroclaw-labs/zeroclaw/issues/10826) [Feature]: Make ZeroCode session root selection explicit and preserve resumed roots `enhancement`
- [#10822](https://github.com/zeroclaw-labs/zeroclaw/issues/10822) [Feature]: `config/set-many` — atomic batch config mutation over RPC `enhancement`
- [#10821](https://github.com/zeroclaw-labs/zeroclaw/issues/10821) [Bug]: `zeroclaw service logs` shows stale stderr as current — service-installed daemon emits no tracing to stderr without `--verbose` `bug` `daemon` `observability` `runtime`
- [#10814](https://github.com/zeroclaw-labs/zeroclaw/issues/10814) [Tracker]: Release efficiency and repeatable publication `priority:p1` `risk:high` `type:ci` `type:tracker`
- [#10812](https://github.com/zeroclaw-labs/zeroclaw/issues/10812) [Feature]: Populate DocumentMessage.jpegThumbnail so PDFs sent over WhatsApp preview on phones
- [#10807](https://github.com/zeroclaw-labs/zeroclaw/issues/10807) [Bug]: MCP connection is permanently poisoned by one failed recovery attempt `bug`
- [#10805](https://github.com/zeroclaw-labs/zeroclaw/issues/10805) [Bug]: control_plane liveness tests race process teardown on Windows (Advisory Windows nextest) `bug` `ci` `runtime`
- [#10802](https://github.com/zeroclaw-labs/zeroclaw/issues/10802) [Bug]: `session/list-acp` reports a different `message_count` than `turn_end` for the same session `bug` `runtime` `status:in-progress` `status:accepted` `priority:p3` `risk:medium` `zerocode` `channel:acp` 💬2
- [#10797](https://github.com/zeroclaw-labs/zeroclaw/issues/10797) [Bug]: markdown memory backend silently loses stored entries when `store()` calls overlap `bug` `memory` `runtime` `memory:backend` `priority:p1` `tool:memory` `status:accepted` `risk:high` 💬1

### 🔒 Closed Issues
- [#10533](https://github.com/zeroclaw-labs/zeroclaw/issues/10533) [Bug]: model_routing_config rejects custom.* (and other valid) provider slots — tool validation diverges from config schema

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,619 · **Open issues:** 1,523 · **Last push:** 2d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,858 · **Open issues:** 83 · **Last push:** 9h ago

### ✅ Merged PRs
- [#1263](https://github.com/moltis-org/moltis/pull/1263) chore(deps): bump the npm_and_yarn group across 2 directories with 4 updates
- [#1253](https://github.com/moltis-org/moltis/pull/1253) feat(reasoning): add max effort level
- [#1265](https://github.com/moltis-org/moltis/pull/1265) fix(telegram): expose shared-chat tool policy controls

### 🔒 Closed Issues
- [#1264](https://github.com/moltis-org/moltis/issues/1264) [Bug]: Tools stop working in shared Telegram channels

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 5d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 8d ago
- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬2 · 12d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 14d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 16d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 20d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 32d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 35d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 38d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 40d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/singularity — top 2 new
- [They’re colluding to kill open source](https://reddit.com/r/singularity/comments/1wf4hl5/theyre_colluding_to_kill_open_source/) ↑708
- [Feels like the big 3 (Elon, Dario, and Sam Altman) all know about a more serious AI incident than Hugging face and that is why they are calling for a slowdown.  This is one of the only times all 3 hav](https://reddit.com/r/singularity/comments/1wewa50/feels_like_the_big_3_elon_dario_and_sam_altman/) ↑651

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [I trusted ChatGPT to help me build an AI assistant. Now I have a second job I don’t understand, and I need a human.](https://reddit.com/r/openclaw/comments/1we0450/i_trusted_chatgpt_to_help_me_build_an_ai/) ↑13
- [Open Claw Just Saves So Much Time At My  Digital Marketing Work!](https://reddit.com/r/openclaw/comments/1webmdy/open_claw_just_saves_so_much_time_at_my_digital/) ↑11
- [Is it just me or the new OC is way slower?](https://reddit.com/r/openclaw/comments/1wekbl1/is_it_just_me_or_the_new_oc_is_way_slower/) ↑9
- [Need a solution to accurately track cost (skill or GitHub repo or other)](https://reddit.com/r/openclaw/comments/1we9vfn/need_a_solution_to_accurately_track_cost_skill_or/) ↑3
- [Another update; another headache 2026.9.3](https://reddit.com/r/openclaw/comments/1wfb5r6/another_update_another_headache_202693/) ↑2

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [🦞 OpenClaw v2026.9.4 is out, thank you to all 293 contributors!

🧩 Find your next plugin or skill
🧠 Turn old chats into ](https://x.com/openclaw/status/2098449762119020926)

### X — @steipete
- [Anyone got an invite code for Meta's Muse? 👉👈

I saw their Soul.md file and now i'm curious.](https://x.com/steipete/status/2098931686042210381) ↑0 🔁0 · recent
- [all sorted out. they defo been cookin!](https://x.com/steipete/status/2098995230314037516) ↑0 🔁0 · recent
- [This is amazing. Add Master of Orion 2 next!](https://x.com/steipete/status/2098784877495939145) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
