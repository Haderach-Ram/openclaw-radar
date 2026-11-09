---
layout: post
title: "Ecosystem Digest — 2026-11-09"
date: 2026-11-09 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-09
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 394,214 | 13 | 1 | 10 | 1 |
| **hermesagent** | 261,791 | 7 | 3 | 8 | 0 |
| **ZeroClaw** | 33,287 | 15 | 1 | 5 | 0 |
| **IronClaw** | 12,715 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,952 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 394,214 · **Open issues:** 7,818 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.11.2](https://github.com/openclaw/openclaw/releases/tag/v2026.11.2) — openclaw 2026.11.2

### ✅ Merged PRs
- [#195403](https://github.com/openclaw/openclaw/pull/195403) fix: explain workspace limit failures in desktop chat
- [#195487](https://github.com/openclaw/openclaw/pull/195487) fix: avoid update failures when header snapshot cleanup is denied
- [#195507](https://github.com/openclaw/openclaw/pull/195507) fix(openclaw-id): allow one automatic node pairing per approved listing
- [#195483](https://github.com/openclaw/openclaw/pull/195483) fix(ui): keep plugin credential drafts out of IME commits
- [#195506](https://github.com/openclaw/openclaw/pull/195506) fix(ui): make Details motion proof independent of frame cadence
- [#195444](https://github.com/openclaw/openclaw/pull/195444) fix(ui): keep IME composition Enter from connecting from the login form
- [#195450](https://github.com/openclaw/openclaw/pull/195450) fix(github): expire cached detail reads on elapsed time
- [#195472](https://github.com/openclaw/openclaw/pull/195472) fix(active-memory): expire recall circuit breaker on elapsed time
- [#195176](https://github.com/openclaw/openclaw/pull/195176) fix: show compaction notices during native history preparation
- [#195458](https://github.com/openclaw/openclaw/pull/195458) fix(worktrees): stop retrying oversized archived workspace results

### 🐛 New Issues
- [#195521](https://github.com/openclaw/openclaw/issues/195521) Muse: slow Muse starts are reported as a missing install
- [#195520](https://github.com/openclaw/openclaw/issues/195520) ACPX: the stalled-run watchdog stops long ACP turns after about six minutes
- [#195519](https://github.com/openclaw/openclaw/issues/195519) Skill Workshop: agents configured with no skills still pay for background experience reviews
- [#195518](https://github.com/openclaw/openclaw/issues/195518) Muse: the stalled-run watchdog stops long Muse turns after about six minutes
- [#195517](https://github.com/openclaw/openclaw/issues/195517) Agents: a shared OAuth account's token rotation fails other in-flight runs with 401
- [#195511](https://github.com/openclaw/openclaw/issues/195511) [Docs Bug]: Spawned child session key is unclear `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#195509](https://github.com/openclaw/openclaw/issues/195509) [Bug]: Talk realtime consults over the prompt budget are windowed but never compacted, so every consult misses the prompt cache `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#195502](https://github.com/openclaw/openclaw/issues/195502) [Bug]: Doctor's cron inference-account check copies the agent database about three times per automation, so updates time out on large state `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `maturity:stable` 💬1
- [#195501](https://github.com/openclaw/openclaw/issues/195501) Gateway: a fractional idle time in presence stops macOS and iOS apps from connecting `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬1
- [#195497](https://github.com/openclaw/openclaw/issues/195497) Memory growth to ~3G in 17h on gateway process (v2026.11.1) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#195494](https://github.com/openclaw/openclaw/issues/195494) [Bug]: Control UI chat drops the backslash from Windows paths before punctuation `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#195492](https://github.com/openclaw/openclaw/issues/195492) Windows: successful empty listener census can be mistaken for a free port `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#195491](https://github.com/openclaw/openclaw/issues/195491) [Bug]: infer model run (local transport) republishes workspace plugins on every call; slow and times out (2026.11.1, macOS) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1

### 🔒 Closed Issues
- [#188897](https://github.com/openclaw/openclaw/issues/188897) [Bug]: Update capture never seals on large state dirs — metadata inventory result exceeds the 1 MiB stdout cap

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬80 · 2d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 261,791 · **Open issues:** 53,865 · **Last push:** <1h ago

### ✅ Merged PRs
- [#151477](https://github.com/NousResearch/hermes-agent/pull/151477) fix(cron): a named DM topic created through a shared bot is saved in the bot owner's profile
- [#151534](https://github.com/NousResearch/hermes-agent/pull/151534) test(e2e-upgrade): start a merge release from its second parent, fail on CI with no release, run the oracle anywhere
- [#120478](https://github.com/NousResearch/hermes-agent/pull/120478) fix(kanban): pin the auto-decompose board for the tick's context only
- [#150980](https://github.com/NousResearch/hermes-agent/pull/150980) test(telegram): pin the 1024-code-point caption cap (tdlib utf8_length); no production change
- [#149757](https://github.com/NousResearch/hermes-agent/pull/149757) plugin-catalog: add epoch (calibrated Kanban estimates)
- [#151120](https://github.com/NousResearch/hermes-agent/pull/151120) Plugins can now act the moment a chat opens: on_session_open hook (#89385, salvage #118895)
- [#151528](https://github.com/NousResearch/hermes-agent/pull/151528) test(gateway): child-notice profile tests skip schema fsyncs on throwaway profile DBs
- [#151527](https://github.com/NousResearch/hermes-agent/pull/151527) test(gateway): cold /review test waits for the session to read idle, not just terminal rows

### 🐛 New Issues
- [#151605](https://github.com/NousResearch/hermes-agent/issues/151605) Desktop SDK: profile-bound provider settings and optional plugin secret writes
- [#151600](https://github.com/NousResearch/hermes-agent/issues/151600) Windows installer fails with "pinned git extracted without git-remote-https" when user profile path contains non-ASCII characters
- [#151586](https://github.com/NousResearch/hermes-agent/issues/151586) [Bug]: an unverified-admission pause is never lifted when the firer books its own terminal outcome - the job stays paused forever
- [#151585](https://github.com/NousResearch/hermes-agent/issues/151585) cron: canonical-dispatch path (scheduler_authority.run_canonical_job) never gets the unreachable-model retry ladder
- [#151584](https://github.com/NousResearch/hermes-agent/issues/151584) [Bug]: Classic CLI /resume, /sessions and -c/--resume latest hide Desktop (gui) sessions — no all-sources view
- [#151582](https://github.com/NousResearch/hermes-agent/issues/151582) [Bug]: Session delete/rename permanently 409 revision_conflict — /api/sessions serves in-memory revision while the fence validates the DB column (two counters desync in both directions)
- [#151581](https://github.com/NousResearch/hermes-agent/issues/151581) [Bug]: Windows install fails at "System prerequisites" with "pinned git extracted without git-remote-https" when the profile path has non-ASCII characters

### 🔒 Closed Issues
- [#151595](https://github.com/NousResearch/hermes-agent/issues/151595) [Bug]: plugin `ctx.llm.complete()` drops a named custom provider's `extra_body`
- [#138791](https://github.com/NousResearch/hermes-agent/issues/138791) [Bug]: Desktop boot fails with `Gateway starting (deadline)` when the sticky active_profile is a parked profile — regression after update
- [#65225](https://github.com/NousResearch/hermes-agent/issues/65225) KeyError: 'HERMES_KANBAN_BOARD' — kanban dispatcher mutates os.environ, racing dotenv's env.update(os.environ)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,287 · **Open issues:** 1,173 · **Last push:** <1h ago

### ✅ Merged PRs
- [#12270](https://github.com/zeroclaw-labs/zeroclaw/pull/12270) feat(relay): serve a daemon's web dashboard through the relay at a per-node host (#10315 phase 2)
- [#11406](https://github.com/zeroclaw-labs/zeroclaw/pull/11406) fix(config)!: refuse macOS broad roots in the filesystem channel
- [#11268](https://github.com/zeroclaw-labs/zeroclaw/pull/11268) docs(auth): align gateway policy publication guidance
- [#10502](https://github.com/zeroclaw-labs/zeroclaw/pull/10502) fix(mcp): relocate tool-result images to a user message (OpenAI-compatible 400)
- [#12286](https://github.com/zeroclaw-labs/zeroclaw/pull/12286) fix(acp): show the shell command as the tool-call title

### 🐛 New Issues
- [#12312](https://github.com/zeroclaw-labs/zeroclaw/issues/12312) [Bug]: OIDC enrollment uses a discovered `authorization_endpoint` without the endpoint URL policy `bug` `security` `risk:low`
- [#12311](https://github.com/zeroclaw-labs/zeroclaw/issues/12311) [Bug]: the macOS Seatbelt profile grants sandboxed commands read access to every home dotfile, including ~/.zeroclaw (PR #12150) `bug` `domain:security`
- [#12310](https://github.com/zeroclaw-labs/zeroclaw/issues/12310) [Bug]: the MCP config-control bridge gives the model unrestricted write access to every config path with no approval (PR #12275) `bug` `domain:security`
- [#12309](https://github.com/zeroclaw-labs/zeroclaw/issues/12309) [Bug]: sessions_prompt promises target scoping that no code in the PR enforces, and the head does not compile (PR #12258) `bug` `domain:security`
- [#12308](https://github.com/zeroclaw-labs/zeroclaw/issues/12308) [Bug]: session delete and TTL only close the session; transcript and payloads stay readable and no production erasure path exists (closed PR #11921, for the session event history re-slice) `bug` `domain:security`
- [#12307](https://github.com/zeroclaw-labs/zeroclaw/issues/12307) [Bug]: gateway sessions lose the gw_ namespace, so a paired WebSocket or webhook caller can attach to channel or cron sessions of the same agent (closed PR #11921, for the session event history re-sli `bug` `domain:security`
- [#12306](https://github.com/zeroclaw-labs/zeroclaw/issues/12306) [SANITIZED — possible injection attempt] `bug` `domain:security`
- [#12305](https://github.com/zeroclaw-labs/zeroclaw/issues/12305) [SANITIZED — possible injection attempt] `bug` `domain:security`
- [#12304](https://github.com/zeroclaw-labs/zeroclaw/issues/12304) [Bug]: colony channel replies are built from every conversation addressed to the agent, leaking operator messages to external channel members (PR #11560) `bug` `domain:security`
- [#12303](https://github.com/zeroclaw-labs/zeroclaw/issues/12303) [Bug]: zeroclaw-gw Quickstart apply admits principals the in-process gateway refuses: Quickstart:Execute only, no whole-config write check (PR #11417) `bug` `domain:security`
- [#12302](https://github.com/zeroclaw-labs/zeroclaw/issues/12302) [Bug]: bounded cross-profile delegation drops the caller's forbidden_paths, allowed_roots, workspace_only and OS sandbox (PR #10391) `bug` `domain:security`
- [#12301](https://github.com/zeroclaw-labs/zeroclaw/issues/12301) [Bug]: the Android SSH server trusts authorized_keys inside the agent's writable HOME on 0.0.0.0, so one shell command plants persistent remote access (PR #10205) `bug` `domain:security`
- [#12300](https://github.com/zeroclaw-labs/zeroclaw/issues/12300) [Bug]: VoiceHost trusts any remote endpoint: plain ws:// without credentials, no speaker allowlist, host replies count as operator approvals (PR #9740) `bug` `domain:security`
- [#12299](https://github.com/zeroclaw-labs/zeroclaw/issues/12299) [Bug]: /v1/chat/completions runs shell tool calls without the approval prompt the dashboard chat enforces (PR #8486) `bug` `domain:security`
- [#12296](https://github.com/zeroclaw-labs/zeroclaw/issues/12296) [Feature]: check commands in zsh's grammar when the runtime spawns zsh `enhancement` `security:policy` `tool:shell`

### 🔒 Closed Issues
- [#10501](https://github.com/zeroclaw-labs/zeroclaw/issues/10501) MCP tool-result images 400 on OpenAI-compatible providers (image part in a role:tool message)

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,715 · **Open issues:** 1,571 · **Last push:** 5h ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,952 · **Open issues:** 121 · **Last push:** 16d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬3 · 10h ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 6d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 15d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 34d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 42d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 44d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 54d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 62d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 64d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 72d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- ["Does censorship exist in [country]?", according to various LLMs](https://reddit.com/r/LocalLLaMA/comments/1xr09nq/does_censorship_exist_in_country_according_to/) ↑775
- [Users have started buying RTX 5060 Ti 16GB graphics cards en masse for the sake of AI.](https://reddit.com/r/LocalLLaMA/comments/1xr01bj/users_have_started_buying_rtx_5060_ti_16gb/) ↑591

### r/singularity — top 2 new
- [Apple researchers use a Mac mini running Qwen locally to control a Unitree G1 humanoid robot. Trained on 1,000 simulated homes, it autonomously sits, crawls under tables and navigates unfamiliar rooms](https://reddit.com/r/singularity/comments/1xr6w6w/apple_researchers_use_a_mac_mini_running_qwen/) ↑568
- [China masterstroke that will win them AI race?](https://reddit.com/r/singularity/comments/1xrezvl/china_masterstroke_that_will_win_them_ai_race/) ↑298

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw v2026.9.9 patch release is out: GPT-6.1 Sol, Haiku 5.5, and fixes for updates, replies, and scheduled jobs](https://reddit.com/r/openclaw/comments/1x0vt3s/openclaw_v202699_patch_release_is_out_gpt61_sol/) ↑37
- [How can OpenClaw be more proactive…](https://reddit.com/r/openclaw/comments/1xqpmh0/how_can_openclaw_be_more_proactive/) ↑14
- [Successful update from 9.9 to 11.1](https://reddit.com/r/openclaw/comments/1xr0ik3/successful_update_from_99_to_111/) ↑9
- [Since moving to Bun from Node openclaw takes 2gb of ram?](https://reddit.com/r/openclaw/comments/1xqxx7a/since_moving_to_bun_from_node_openclaw_takes_2gb/) ↑5
- [OpenClaw gateway keeps dying? The desktop app and the standalone CLI fight over the service (Linux Mint field notes)](https://reddit.com/r/openclaw/comments/1xqudt7/openclaw_gateway_keeps_dying_the_desktop_app_and/) ↑1

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [How does one of the largest open source projects in history do releases? 🦞


@dallinfinite
  walks through how OpenClaw ](https://x.com/openclaw/status/2118803977882181986)

### X — @steipete
- [The Asahi project was all about taking something closed and restricted and opening it up.

Adding new restrictions that ](https://x.com/steipete/status/2119264334627090514) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
