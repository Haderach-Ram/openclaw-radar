---
layout: post
title: "Ecosystem Digest — 2026-11-15"
date: 2026-11-15 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-15
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 394,463 | 5 | 3 | 10 | 1 |
| **hermesagent** | 263,424 | 13 | 3 | 10 | 1 |
| **ZeroClaw** | 33,367 | 4 | 1 | 1 | 0 |
| **IronClaw** | 12,716 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,959 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 394,463 · **Open issues:** 8,470 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.11.5-beta.3](https://github.com/openclaw/openclaw/releases/tag/v2026.11.5-beta.3) — openclaw 2026.11.5-beta.3

### ✅ Merged PRs
- [#198598](https://github.com/openclaw/openclaw/pull/198598) fix(templates): invalid MCP declarations report only "Invalid input"
- [#198586](https://github.com/openclaw/openclaw/pull/198586) fix: templates build rejects BOOTSTRAP.md that passes validation
- [#199366](https://github.com/openclaw/openclaw/pull/199366) fix(ci): spread cold release work across existing jobs
- [#183729](https://github.com/openclaw/openclaw/pull/183729) fix: Doctor stays silent when personal recall lacks Active Memory
- [#199362](https://github.com/openclaw/openclaw/pull/199362) fix(ci): admit bounded Gateway audit captures
- [#199226](https://github.com/openclaw/openclaw/pull/199226) improve: use OpenClaw consistently as the app name
- [#199356](https://github.com/openclaw/openclaw/pull/199356) feat(gateway): identify the serving process in local startup probes
- [#198552](https://github.com/openclaw/openclaw/pull/198552) fix(openclaw-id): reopening an approved invite link is refused as already used
- [#199337](https://github.com/openclaw/openclaw/pull/199337) fix(update): runtime retention falls back from hard links without saying why
- [#199358](https://github.com/openclaw/openclaw/pull/199358) fix(ci): expose slow Bun staging phases

### 🐛 New Issues
- [#199378](https://github.com/openclaw/openclaw/issues/199378) Talk voice consults fail on Claude CLI and locked native-harness chats that answer typed messages `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#199373](https://github.com/openclaw/openclaw/issues/199373) [Bug]: 2026.11.1 Control UI lists ACP sessions of agents not in agents.entries but cannot open or delete them ("Unknown agent id") `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#199364](https://github.com/openclaw/openclaw/issues/199364) [Bug]: iOS dashboard view prevents opening the selected conversation chat `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬1
- [#199355](https://github.com/openclaw/openclaw/issues/199355) video_generate: OpenRouter returns HTTP 401 "User not found" while same key succeeds via curl `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `impact:security` `impact:auth-provider` `issue-rating: 🦪 silver shellfish` 💬2
- [#199350](https://github.com/openclaw/openclaw/issues/199350) Update failure: package-doctor (2026.11.5-beta.3) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#198554](https://github.com/openclaw/openclaw/issues/198554) [Bug]: Invalid Template MCP declarations report only "Invalid input"
- [#198559](https://github.com/openclaw/openclaw/issues/198559) [Bug]: `templates validate` accepts a `BOOTSTRAP.md` that `templates build` rejects
- [#183700](https://github.com/openclaw/openclaw/issues/183700) [Bug]: rememberAcrossConversations is on by default, but its required Active Memory plugin is disabled by default, so cross-conversation recall silently does nothing

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬81 · 3d ago
- [#116201](https://github.com/openclaw/openclaw/issues/116201) Realtime voice work can retain unbounded provider and consult state — 💬59 · 43d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 263,424 · **Open issues:** 53,097 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.23.1+canary.20261114T064334Z](https://github.com/NousResearch/hermes-agent/releases/tag/v0.23.1%2Bcanary.20261114T064334Z) — Hermes Agent canary v0.23.1+canary.20261114T064334Z

### ✅ Merged PRs
- [#154896](https://github.com/NousResearch/hermes-agent/pull/154896) feat(plugin-catalog): add eol plugin
- [#155753](https://github.com/NousResearch/hermes-agent/pull/155753) fix(desktop): Bot Mode lists the selected bot's Telegram sessions
- [#155378](https://github.com/NousResearch/hermes-agent/pull/155378) fix(skills): keep plaintext secrets out of oss-forensics working files
- [#155246](https://github.com/NousResearch/hermes-agent/pull/155246) fix(desktop): the external sign-in card fits, shows a runnable command, and a lapsed primary login names the primary
- [#155827](https://github.com/NousResearch/hermes-agent/pull/155827) fix(skills): name the upstream repo for live-upstream optional skills
- [#155249](https://github.com/NousResearch/hermes-agent/pull/155249) fix(skills): derive install trust from the serving adapter, not identifiers
- [#155396](https://github.com/NousResearch/hermes-agent/pull/155396) fix(docker): seed auth.json owner-only from the first instant
- [#155430](https://github.com/NousResearch/hermes-agent/pull/155430) fix(security): release-age gate for the standalone WhatsApp bridge and Photon sidecar npm packages
- [#155399](https://github.com/NousResearch/hermes-agent/pull/155399) fix(docker): sweep world-writable uv cache .lock files from the image
- [#155534](https://github.com/NousResearch/hermes-agent/pull/155534) fix(pm): bump the pinned Git for Windows 2.53.0.3 -> 2.56.1

### 🐛 New Issues
- [#155933](https://github.com/NousResearch/hermes-agent/issues/155933) fix(desktop): preserve multi-column layout and focused chat column when creating a session from a sidebar folder `type/bug` `P2` `comp/desktop` `area/sessions` `desktop/sessions`
- [#155932](https://github.com/NousResearch/hermes-agent/issues/155932) [Bug]: mid-turn steer on a yielded foreground command drops the replacement reply — turn ends interrupted_during_api_call and the yielded command renders Result unavailable `type/bug` `comp/agent` `tool/terminal` `P2` `area/streaming`
- [#155930](https://github.com/NousResearch/hermes-agent/issues/155930) `desktop_project` create/switch returns `success: true` even when the session's workspace wasn't moved (e.g. the primary folder doesn't exist) `type/bug` `comp/tools` `P2` `comp/tui-gateway`
- [#155928](https://github.com/NousResearch/hermes-agent/issues/155928) [SANITIZED — possible injection attempt] `type/feature` `comp/gateway` `tool/terminal` `platform/telegram` `area/config` `P3`
- [#155926](https://github.com/NousResearch/hermes-agent/issues/155926) bug: cache_document_from_bytes does not bound display-name length — ENAMETOOLONG drops inbound file messages (real WeCom percent-encoded CJK names, 470 bytes observed) `type/bug` `comp/gateway` `P2` 💬1
- [#155923](https://github.com/NousResearch/hermes-agent/issues/155923) [Feature]: Allow trusting a directory tree for project skills (one consent covers repos under it) `type/feature` `comp/cli` `tool/skills` `area/config` `P3`
- [#155920](https://github.com/NousResearch/hermes-agent/issues/155920) Update custody: "gateway restart owed" warning never discharges when the armed obligation owner PID is dead (v0.23.1) `type/bug` `comp/cli` `P2` `area/install-update`
- [#155919](https://github.com/NousResearch/hermes-agent/issues/155919) [Bug]: Sessions page sorts by created_at, so long-lived chats vanish under cron runs (order=recent never requested) `type/bug` `P2` `comp/dashboard` `area/sessions` 💬1
- [#155909](https://github.com/NousResearch/hermes-agent/issues/155909) 1Password vault backend: Logins without a website and non-Login items are silently unlisted `type/bug` `tool/file` `P2`
- [#155908](https://github.com/NousResearch/hermes-agent/issues/155908) [Feature]: Fail-closed policy seams for a plugin that gives server members a bot without its tools `type/security` `comp/cli` `comp/plugins` `platform/discord` `P3`
- [#155907](https://github.com/NousResearch/hermes-agent/issues/155907) cron: `database is locked` in `adopt_claimed_execution` under normal multi-job concurrency — schema DDL re-runs on every connection `type/bug` `comp/cron` `P2`
- [#155904](https://github.com/NousResearch/hermes-agent/issues/155904) [Bug]: Whats app blocker `type/bug` `comp/cli` `platform/whatsapp` `P2` `area/install-update` `os/windows`
- [#155903](https://github.com/NousResearch/hermes-agent/issues/155903) [Feature]: Desktop plugin SDK: a host-owned backdrop area behind the app `type/feature` `P3` `comp/desktop` `desktop/shell`

### 🔒 Closed Issues
- [#147212](https://github.com/NousResearch/hermes-agent/issues/147212) Primary provider auth failure is masked when the fallback provider fails (user sees out-of-credits, never told to re-login)
- [#136071](https://github.com/NousResearch/hermes-agent/issues/136071) [Bug]: Desktop generates invalid `agy auth add ...` login command for external-process Antigravity plugins
- [#134019](https://github.com/NousResearch/hermes-agent/issues/134019) `scripts/whatsapp-bridge` and `plugins/platforms/photon/sidecar` lockfiles are generated outside the repo's `min-release-age=14` cooldown

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,367 · **Open issues:** 1,232 · **Last push:** 7h ago

### ✅ Merged PRs
- [#12417](https://github.com/zeroclaw-labs/zeroclaw/pull/12417) docs(runtime): propose ADR-016 exception for plugin wake dispatch

### 🐛 New Issues
- [#12441](https://github.com/zeroclaw-labs/zeroclaw/issues/12441) [Feature]: Deliver the requesting user's identity to tool execution `enhancement`
- [#12425](https://github.com/zeroclaw-labs/zeroclaw/issues/12425) [Bug]:zeroclaw对耗时长的任务失去控制 `bug`
- [#12422](https://github.com/zeroclaw-labs/zeroclaw/issues/12422) RFC: Scoped use of operator-managed service credentials
- [#12421](https://github.com/zeroclaw-labs/zeroclaw/issues/12421) perf(cron): agent cron jobs run outside any session-key scope, so they get no provider prompt-cache affinity

### 🔒 Closed Issues
- [#12416](https://github.com/zeroclaw-labs/zeroclaw/issues/12416) [Feature]: ADR-016 holding-crate exception for host-mediated WASM plugin wake dispatch (zeroclaw-runtime)

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,716 · **Open issues:** 1,571 · **Last push:** 5d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,959 · **Open issues:** 121 · **Last push:** 22d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬4 · 2d ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 12d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 21d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 40d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 48d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 50d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 60d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 68d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 70d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 78d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Instead Of Lowering GPU Prices, Former NVIDIA CEO Jensen Huang Reportedly Financed AI Startups To Absorb Excess Silicon, Shattering The Shortage Perception](https://reddit.com/r/LocalLLaMA/comments/1xvsb5f/instead_of_lowering_gpu_prices_former_nvidia_ceo/) ↑2703
- [Hot take: frontier models haven’t actually become much smarter](https://reddit.com/r/LocalLLaMA/comments/1xwegdi/hot_take_frontier_models_havent_actually_become/) ↑225
- [Ai Rig finally done and stable, perfect winter heater](https://reddit.com/r/LocalLLaMA/comments/1xwc3m7/ai_rig_finally_done_and_stable_perfect_winter/) ↑188
- [The lawyer who posts here about his V100s got his story picked up by Tom’s Hardware](https://reddit.com/r/LocalLLaMA/comments/1xw2ogq/the_lawyer_who_posts_here_about_his_v100s_got_his/) ↑184
- [How long are we gonna depend bunch of model creators (like Qwen, Gemma, NVIDIA, etc.,) for ~100B models?](https://reddit.com/r/LocalLLaMA/comments/1xw0xeu/how_long_are_we_gonna_depend_bunch_of_model/) ↑176

### r/singularity — top 2 new
- [AI video has come pretty far](https://reddit.com/r/singularity/comments/1xw0rl8/ai_video_has_come_pretty_far/) ↑1664
- [Debunked: Ancient Maya Site claimed to have been discovered by AI agents was in fact already discovered by humans in 2025 (the guy who made the claim recognized he was wrong)](https://reddit.com/r/singularity/comments/1xw76xz/debunked_ancient_maya_site_claimed_to_have_been/) ↑537

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Gemini 4 Hydrogen is out and you can already use it in OpenClaw! 🦞](https://reddit.com/r/openclaw/comments/1xuyh66/gemini_4_hydrogen_is_out_and_you_can_already_use/) ↑11
- [Is anyone else having issues with OpenClaw agents unable to use web_search even though it’s installed and enabled?](https://reddit.com/r/openclaw/comments/1xw7bho/is_anyone_else_having_issues_with_openclaw_agents/) ↑5
- [My local OpenClaw architecture](https://reddit.com/r/openclaw/comments/1xv4kxn/my_local_openclaw_architecture/) ↑4
- [Securing persistent agents like OpenClaw at OpenAI](https://reddit.com/r/openclaw/comments/1xuwszf/securing_persistent_agents_like_openclaw_at_openai/) ↑3
- [Is OpenClaw worth it for development workflows, or is Claude Code CLI simply better?](https://reddit.com/r/openclaw/comments/1xv7uky/is_openclaw_worth_it_for_development_workflows_or/) ↑3

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [Gemini 4 Hydrogen is out and you can already use it in OpenClaw! 🦞


https://
x.com/OfficialLoganK
/status/2120940951292](https://x.com/openclaw/status/2121098531205501401)

### X — @steipete
- [🍿](https://x.com/steipete/status/2121706904917520875) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
