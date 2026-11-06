---
layout: post
title: "Ecosystem Digest — 2026-11-06"
date: 2026-11-06 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-06
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 393,997 | 6 | 3 | 10 | 1 |
| **hermesagent** | 260,896 | 13 | 3 | 10 | 1 |
| **ZeroClaw** | 33,142 | 9 | 5 | 2 | 0 |
| **IronClaw** | 12,713 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,941 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 393,997 · **Open issues:** 7,620 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.11.1](https://github.com/openclaw/openclaw/releases/tag/v2026.11.1) — openclaw 2026.11.1

### ✅ Merged PRs
- [#193881](https://github.com/openclaw/openclaw/pull/193881) fix(test): stop launcher disconnect fixture from timing out
- [#193781](https://github.com/openclaw/openclaw/pull/193781) perf: reduce style matching during Control UI interactions
- [#193778](https://github.com/openclaw/openclaw/pull/193778) feat: preview recommended templates in a compact dialog
- [#193784](https://github.com/openclaw/openclaw/pull/193784) fix: avoid full-tree work when refreshing prepared workers
- [#193835](https://github.com/openclaw/openclaw/pull/193835) fix: show manual-only skills in composer completions
- [#193883](https://github.com/openclaw/openclaw/pull/193883) perf(skills): avoid rebuilding row status on every search character
- [#193888](https://github.com/openclaw/openclaw/pull/193888) chore(ui): refresh control ui locales
- [#193849](https://github.com/openclaw/openclaw/pull/193849) fix: capitalize Search tooltip label
- [#192331](https://github.com/openclaw/openclaw/pull/192331) fix(onboarding): keep npx Gateway services running after cache cleanup
- [#193864](https://github.com/openclaw/openclaw/pull/193864) fix(ui): preserve compact task progress markers

### 🐛 New Issues
- [#193891](https://github.com/openclaw/openclaw/issues/193891) [Bug]: advisor review fork fails 100% of the time — prepared model runtime owner was not published (not fixed in 2026.11.1) `clawsweeper:intake:bug` 💬1
- [#193879](https://github.com/openclaw/openclaw/issues/193879) [Bug]: macOS node worker rescans Claude session folders every second after the Claude sessions list is shown once `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#193877](https://github.com/openclaw/openclaw/issues/193877) before_tool_call: ctx.requester empty for CLI-backend (claude-cli) tool calls `P2` `impact:security` `issue-rating: 🦪 silver shellfish` 💬1
- [#193868](https://github.com/openclaw/openclaw/issues/193868) [Bug]: exec code-mode bridge corrupts after hours of uptime — every shell call fails with zsh parse errors (2026.10.10 regression) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#193862](https://github.com/openclaw/openclaw/issues/193862) [Bug]: Native chat rebuilds every reply's source cards each time a transcript message arrives `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#193858](https://github.com/openclaw/openclaw/issues/193858) [Bug]: Every SQLite connection open on macOS forks `mount` synchronously, even for local APFS state `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1

### 🔒 Closed Issues
- [#192328](https://github.com/openclaw/openclaw/issues/192328) npx Quick start cannot keep the Gateway running after the terminal closes
- [#193811](https://github.com/openclaw/openclaw/issues/193811) [Bug]: Mattermost drops user posts that carry a message attachment (type "slack_attachment")
- [#193446](https://github.com/openclaw/openclaw/issues/193446) [Feature]: Preserve native browser identity for managed headless website logins

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬74 · 10h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 260,896 · **Open issues:** 53,084 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.23.0](https://github.com/NousResearch/hermes-agent/releases/tag/v0.23.0) — Hermes Agent v0.23.0 — The Hearth Release

### ✅ Merged PRs
- [#149763](https://github.com/NousResearch/hermes-agent/pull/149763) fix(memory): let subagents compact and withhold the prune under checkpoint_required
- [#149623](https://github.com/NousResearch/hermes-agent/pull/149623) fix(dashboard-auth): accept the Desktop's session-token header behind the gate
- [#149759](https://github.com/NousResearch/hermes-agent/pull/149759) fix(plugins): refuse to turn on a recalled plugin from the plugins picker
- [#148803](https://github.com/NousResearch/hermes-agent/pull/148803) refactor(plugins): dashboard plugin APIs import through the shared user-code helper
- [#148776](https://github.com/NousResearch/hermes-agent/pull/148776) fix(plugins): plugin packs and dashboard/TUI enable respect the plugin kill list
- [#148773](https://github.com/NousResearch/hermes-agent/pull/148773) feat(plugins): one published list of what plugins may import
- [#148807](https://github.com/NousResearch/hermes-agent/pull/148807) fix(plugins): run a failed hosted load's on_unload cleanup
- [#148804](https://github.com/NousResearch/hermes-agent/pull/148804) fix(plugins): show the get_session_env import that validate accepts
- [#148806](https://github.com/NousResearch/hermes-agent/pull/148806) fix(tui): config.set refuses administrator-managed keys
- [#148796](https://github.com/NousResearch/hermes-agent/pull/148796) fix(plugins): a plugin reload replaces its context reference once it loads

### 🐛 New Issues
- [#149799](https://github.com/NousResearch/hermes-agent/issues/149799) [Bug][iOS] SSH over WireGuard fails before connection with dashboard resolution error
- [#149798](https://github.com/NousResearch/hermes-agent/issues/149798) [Bug]: Desktop app TUI/PTY pane always disconnected (1006) — loopback WebSocket auth rejected (no_credential)
- [#149794](https://github.com/NousResearch/hermes-agent/issues/149794) [Bug]: Hosted-room rounds end with unheard seats — scheduling discards speaker order, stall is invisible
- [#149793](https://github.com/NousResearch/hermes-agent/issues/149793) [Bug]: Desktop model picker is silent with NVDA - search box has no combobox role or active-descendant `bug`
- [#149792](https://github.com/NousResearch/hermes-agent/issues/149792) [Bug]: Desktop Settings opens without moving keyboard or screen-reader focus into it (NVDA) `bug`
- [#149784](https://github.com/NousResearch/hermes-agent/issues/149784) Desktop sessions become unrecoverable (`admission_conflict`) after 90-day pruning — routing entries never refreshed by desktop turns, restore refuses to self-heal 💬1
- [#149779](https://github.com/NousResearch/hermes-agent/issues/149779) [Bug]: Desktop — cross-profile wake leaves $newChatProfile pinned, so New Session lands in the woken profile
- [#149778](https://github.com/NousResearch/hermes-agent/issues/149778) shell.exec redacts structured plugin stdout: a 32-hex token becomes "abcd12...ef34" 💬1
- [#149776](https://github.com/NousResearch/hermes-agent/issues/149776) [Bug]: Symlinked profile home loses its identity in three places under the 0.23 multiplexer — old sessions fail to reopen, Desktop sends refused (permission_denied)
- [#149774](https://github.com/NousResearch/hermes-agent/issues/149774) [Bug]: hermes doctor flags the desktop bundle's own ~/.local/bin/hermes link as "points to wrong target"
- [#149773](https://github.com/NousResearch/hermes-agent/issues/149773) [Bug]: Mirror-only networks: PM's locked syncs download from the files.pythonhosted.org URLs in uv.lock and never use the configured index
- [#149771](https://github.com/NousResearch/hermes-agent/issues/149771) [Bug]: mcp login stalls after the OAuth callback: an idle browser socket parks the callback listener and the synchronous server.shutdown() with it
- [#149770](https://github.com/NousResearch/hermes-agent/issues/149770) [Bug]: Desktop local image uploads fail with "session not found" after a legacy remote profile connects

### 🔒 Closed Issues
- [#149787](https://github.com/NousResearch/hermes-agent/issues/149787) Desktop Scheduled: script-only (no_agent) run rows can't be opened, and their preview is all header boilerplate
- [#134889](https://github.com/NousResearch/hermes-agent/issues/134889) Tracking: one gateway owns every local session (#106742) — post-merge fixes
- [#149195](https://github.com/NousResearch/hermes-agent/issues/149195) Hosted rooms: overlapping rooms reschedule each other forever via wakeup()

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,142 · **Open issues:** 1,166 · **Last push:** <1h ago

### ✅ Merged PRs
- [#12232](https://github.com/zeroclaw-labs/zeroclaw/pull/12232) fix(security): withhold principal-unaware tools and SOP execution from non-admin principals
- [#12253](https://github.com/zeroclaw-labs/zeroclaw/pull/12253) fix(ci): accept pin-utils maintenance advisory pending async-imap migration

### 🐛 New Issues
- [#12252](https://github.com/zeroclaw-labs/zeroclaw/issues/12252) [Task]: Accept the pin-utils maintenance advisory (RUSTSEC-2026-0441) until async-imap moves off it `ci` `dependencies` `security`
- [#12249](https://github.com/zeroclaw-labs/zeroclaw/issues/12249) [Task]: Dashboard: don't offer config pages to a signed-in account that can't read config `gateway` `follow-up` `web` `topic:identity-access`
- [#12248](https://github.com/zeroclaw-labs/zeroclaw/issues/12248) [Task]: Don't ask for approval of a tool call that can't run `runtime` `security` `follow-up`
- [#12247](https://github.com/zeroclaw-labs/zeroclaw/issues/12247) [Task]: Scoped dashboard chat: generic text for daemon refusals, and no agent list from before a reload `gateway` `follow-up`
- [#12246](https://github.com/zeroclaw-labs/zeroclaw/issues/12246) [Task]: Wipe bearer copies made during an RPC handshake `gateway` `runtime` `security` `follow-up`
- [#12245](https://github.com/zeroclaw-labs/zeroclaw/issues/12245) [Task]: Scoped dashboard chat: keep the sign-in through an identity provider outage, and bound how often a sign-in makes the daemon verify its token `gateway` `security` `follow-up` `topic:identity-access`
- [#12236](https://github.com/zeroclaw-labs/zeroclaw/issues/12236) [Bug]: cached HTTP clients are shared across test runtimes, so a mock request can fail with "dispatch task is gone" `bug` 💬1
- [#12228](https://github.com/zeroclaw-labs/zeroclaw/issues/12228) [Bug]: cron update --agent reports success but never reassigns the job's agent 💬1
- [#12225](https://github.com/zeroclaw-labs/zeroclaw/issues/12225) [Bug]: glob_search never lists files under allowed roots outside the workspace 💬1

### 🔒 Closed Issues
- [#12051](https://github.com/zeroclaw-labs/zeroclaw/issues/12051) [Bug]: sop_workshop apply lets a scoped principal author shared SOPs that later run with operator authority
- [#12046](https://github.com/zeroclaw-labs/zeroclaw/issues/12046) [Bug]: Non-admin principals with a wildcard tool selector keep principal-unaware tools (cron, schedule, peer messaging, SOP execution)
- [#11127](https://github.com/zeroclaw-labs/zeroclaw/issues/11127) [SANITIZED — possible injection attempt]
- [#11123](https://github.com/zeroclaw-labs/zeroclaw/issues/11123) [Bug]: SOP execution accepts wildcard tool selectors without tools:execute
- [#10526](https://github.com/zeroclaw-labs/zeroclaw/issues/10526) RFC: Append-only session event history, deterministic state replay, and derived agent streams

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,713 · **Open issues:** 1,571 · **Last push:** 1d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,941 · **Open issues:** 122 · **Last push:** 13d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 3d ago
- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬2 · 12d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 12d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 31d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 39d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 41d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 51d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 59d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 61d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 69d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 2 new
- [[Legal] Guest Pass Terms](https://www.anthropic.com/legal/guest-pass-terms) _2026-11-05_
- [[Research] How Researchers Use Claude](https://www.anthropic.com/research/how-researchers-use-claude) _2026-11-05_

### OpenAI — 6 new
- [Cybersecurity](https://openai.com/cybersecurity/) _2026-11-06_
- [Compute Campus](https://openai.com/compute-campus/) _2026-11-06_
- [[Index] Franklin Templeton](https://openai.com/index/franklin-templeton/) _2026-11-06_
- [[Index] Merge Builds With Openai](https://openai.com/index/merge-builds-with-openai/) _2026-11-06_
- [[Index] Cultfit Builds With Codex](https://openai.com/index/cultfit-builds-with-codex/) _2026-11-06_
- [[Index] Australian Universities Ai Native Graduates](https://openai.com/index/australian-universities-ai-native-graduates/) _2026-11-06_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [Maybe we'll get cheap RAM for Christmas after all!](https://reddit.com/r/LocalLLaMA/comments/1xovnaa/maybe_well_get_cheap_ram_for_christmas_after_all/) ↑888
- [Z.ai chief scientist Jie Tang just revealed the training pipeline behind the upcoming GLM-5.5 (32B, 122B, and 256B)](https://reddit.com/r/LocalLLaMA/comments/1xossr5/zai_chief_scientist_jie_tang_just_revealed_the/) ↑873

### r/singularity — top 5 new
- [Xiaomi's humanoid robots spotted doing their first 8-hour shift sorting EV parts at a rate of ~ 1 per minute](https://reddit.com/r/singularity/comments/1xn5g1f/xiaomis_humanoid_robots_spotted_doing_their_first/) ↑2407
- [Some positive news?](https://reddit.com/r/singularity/comments/1xovn11/some_positive_news/) ↑938
- [METR reveals Anthropic's unreleased Model 4, trained in September–October 2026, scored 178.6 on the AI capability index, a jump nearly 90% as large as the entire improvement from Opus 4.6 to Mythos 5.](https://reddit.com/r/singularity/comments/1xorf5c/metr_reveals_anthropics_unreleased_model_4/) ↑565
- [OpenAI has just announced GPT‑6 Cyber, a major step up from GPT‑5.6 Cyber and outperforms GPT‑6 Astra on most cyber tasks](https://reddit.com/r/singularity/comments/1xoo9ob/openai_has_just_announced_gpt6_cyber_a_major_step/) ↑429
- [Oh well...](https://reddit.com/r/singularity/comments/1xoqj9r/oh_well/) ↑350

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw 2026.10.10 broke every chat turn on my box (11/11 failed). Will updates ever not be gambling?](https://reddit.com/r/openclaw/comments/1xmq9vh/openclaw_20261010_broke_every_chat_turn_on_my_box/) ↑22
- [OpenClaw is not what you think it is](https://reddit.com/r/openclaw/comments/1xoensu/openclaw_is_not_what_you_think_it_is/) ↑15
- [OpenClaw v2026.11.1 patch fixes message refusals, Doctor reporting, and Gateway settings](https://reddit.com/r/openclaw/comments/1xorxaf/openclaw_v2026111_patch_fixes_message_refusals/) ↑14
- [Knowledge: A New Approach to Memory in OpenClaw](https://reddit.com/r/openclaw/comments/1xo702s/knowledge_a_new_approach_to_memory_in_openclaw/) ↑11
- [OpenClaw v2026.10.8 patch fixes installs, updates and stuck conversations](https://reddit.com/r/openclaw/comments/1xh6d5x/openclaw_v2026108_patch_fixes_installs_updates/) ↑11

### X — @openclaw
- [So many agents

So many features 

This thread is going to be 100 posts long soon](https://x.com/openclaw/status/2118434640977637850) ↑0 🔁0 · recent
- [OpenClaw v2026.11.1 patch is out 🦞

💬 Fixes false Telegram and Discord message refusals
🩺 Doctor stops reporting failed ](https://x.com/openclaw/status/2118416574004744245) ↑0 🔁0 · recent
- [Engineering, Product, Marketing, each in its own silo, with its own context

OpenClaw Multiplayer gives teams one shared](https://x.com/openclaw/status/2118404891911864536) ↑0 🔁0 · recent
- [Knowledge: A New Approach to Memory in OpenClaw


@hrudolph
 and 
@Pat_Erichsen
 welcome back 
@jlehman_
 for a demo of ](https://x.com/openclaw/status/2118166584623874319) ↑0 🔁0 · recent


### X — @steipete
- [Is my perception off or is Apple just lying here? Anytime I build for or use Safari, it’s slower, has fewer features, we](https://x.com/steipete/status/2118492097917628704) ↑0 🔁0 · recent
- [Just a normal Thursday.](https://x.com/steipete/status/2118380936882803044) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
