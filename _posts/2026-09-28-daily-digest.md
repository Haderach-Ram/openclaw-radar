---
layout: post
title: "Ecosystem Digest — 2026-09-28"
date: 2026-09-28 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-28
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 390,665 | 8 | 7 | 10 | 0 |
| **hermesagent** | 249,518 | 8 | 7 | 10 | 0 |
| **ZeroClaw** | 32,900 | 5 | 5 | 10 | 0 |
| **IronClaw** | 12,632 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,875 | 1 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 390,665 · **Open issues:** 8,784 · **Last push:** <1h ago

### ✅ Merged PRs
- [#160030](https://github.com/openclaw/openclaw/pull/160030) perf(ui): stop re-parsing loaded tool output on every history page
- [#160031](https://github.com/openclaw/openclaw/pull/160031) chore(ui): refresh control ui locales
- [#159962](https://github.com/openclaw/openclaw/pull/159962) refactor(tool-search): name nested catalog call ids after tool_call
- [#160000](https://github.com/openclaw/openclaw/pull/160000) fix(ci): honor loaded stop policy in upgrade fixtures
- [#159798](https://github.com/openclaw/openclaw/pull/159798) refactor(extensions): deslop browser and memory plugins further
- [#159600](https://github.com/openclaw/openclaw/pull/159600) refactor(plugins): deslop plugin runtime fourth pass
- [#150605](https://github.com/openclaw/openclaw/pull/150605) feat(ui): organize sidebar session filters in one panel
- [#160019](https://github.com/openclaw/openclaw/pull/160019) fix(computer): unchanged window reads never reach critical loop detection
- [#160015](https://github.com/openclaw/openclaw/pull/160015) fix: fresh npm updates fail to load Undici
- [#159887](https://github.com/openclaw/openclaw/pull/159887) feat(ui): add a personal external browser preference

### 🐛 New Issues
- [#160037](https://github.com/openclaw/openclaw/issues/160037) MiniMax-M3.1-Flash-Preview: 5-level output_config.effort unreachable, off level returns 400, model missing from bundled catalog
- [#160028](https://github.com/openclaw/openclaw/issues/160028) Duplicate Telegram delivery of agent reply via wrong (default) account after session context reset `P2` `impact:message-loss` `issue-rating: 🦪 silver shellfish` 💬1
- [#160026](https://github.com/openclaw/openclaw/issues/160026) [Feature]: Create and use custom clawmoji avatars for Claws `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#160021](https://github.com/openclaw/openclaw/issues/160021) Update failure: unexpected-error (2026.9.4) `P0` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-release-blocker` 💬1
- [#160010](https://github.com/openclaw/openclaw/issues/160010) Type-aware lint can exhaust host memory despite Go heap tuning `bug` `P2` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` 💬1
- [#160006](https://github.com/openclaw/openclaw/issues/160006) Sidebar: page-row reorder grip takes space for pointer users `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1
- [#160004](https://github.com/openclaw/openclaw/issues/160004) [Bug]: sessions.abort loses the typed state-contention Stop outcome `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬1
- [#160003](https://github.com/openclaw/openclaw/issues/160003) [Bug]: A restart-safe terminal admission persists without an unread marker `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:session-state` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#159927](https://github.com/openclaw/openclaw/issues/159927) 2026.9.6 requires a credential-store schema migration but only `doctor --fix` can apply it, with no fallback path
- [#159926](https://github.com/openclaw/openclaw/issues/159926) `openclaw doctor --fix` refuses maintenance mode when env and paths are all canonical (2026.9.6 regression)
- [#159949](https://github.com/openclaw/openclaw/issues/159949) [Bug]: Strict dashboard schemas fabricate first-widget placement anchors
- [#159993](https://github.com/openclaw/openclaw/issues/159993) Unchanged computer observations stay at warning level when references refresh
- [#150456](https://github.com/openclaw/openclaw/issues/150456) Sidebar: give the session menu a clearer structure
- [#159884](https://github.com/openclaw/openclaw/issues/159884) [Feature]: Personal preference to open links in an external browser
- [#140075](https://github.com/openclaw/openclaw/issues/140075) [Bug]: Reported token usage is off (openclaw vs openai dashboard)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 249,518 · **Open issues:** 44,572 · **Last push:** <1h ago

### ✅ Merged PRs
- [#124859](https://github.com/NousResearch/hermes-agent/pull/124859) fix(desktop): interrupt a deleted session's runtime so no prompt outlives it
- [#124816](https://github.com/NousResearch/hermes-agent/pull/124816) fix(desktop): re-point the window route after a primary connection apply
- [#124815](https://github.com/NousResearch/hermes-agent/pull/124815) fix(desktop): never adopt a page from a backend that ignored order=latest
- [#124802](https://github.com/NousResearch/hermes-agent/pull/124802) fix(desktop): cron run rows carry their owning backend so the transcript opens
- [#125878](https://github.com/NousResearch/hermes-agent/pull/125878) feat(desktop): let the show-ignored toggle reveal hygiene dirs like out/ and vendor/
- [#125870](https://github.com/NousResearch/hermes-agent/pull/125870) fmt(js): `npm run fix` auto-fix
- [#125598](https://github.com/NousResearch/hermes-agent/pull/125598) fix(install): fresh Windows 10 installs no longer die unpacking pinned Git (PortableGit, salvage #123094)
- [#125800](https://github.com/NousResearch/hermes-agent/pull/125800) feat(desktop): reasoning level up/down keybind actions
- [#125797](https://github.com/NousResearch/hermes-agent/pull/125797) feat(tui_gateway): session.archive RPC + inline_images=false history reads
- [#125816](https://github.com/NousResearch/hermes-agent/pull/125816) feat(tui): attachments.storage config to stage attachments in the profile workspace

### 🐛 New Issues
- [#125923](https://github.com/NousResearch/hermes-agent/issues/125923) [SANITIZED — possible injection attempt]
- [#125922](https://github.com/NousResearch/hermes-agent/issues/125922) [Bug]: update failed `bug`
- [#125920](https://github.com/NousResearch/hermes-agent/issues/125920) xAI grok-4.7 compression no-ops on encrypted reasoning, then structural_backoff blocks retry `bug` 💬1
- [#125919](https://github.com/NousResearch/hermes-agent/issues/125919) Silent memory-provider disablement: a failed config load makes provider="" indistinguishable from the core sentinel
- [#125914](https://github.com/NousResearch/hermes-agent/issues/125914) [bug][security] upgrading hermes-agent python package, downgrades other packges to vulnerable versions `type/bug` `duplicate` `comp/cli` `P3` `area/install-update`
- [#125910](https://github.com/NousResearch/hermes-agent/issues/125910) Cloud gateway instance primus-7774.agents.nousresearch.com unresponsive (TLS accepts, HTTP hangs) since ~15:02 UTC Sep 27 `type/bug` `comp/gateway` `P2` `comp/portal`
- [#125909](https://github.com/NousResearch/hermes-agent/issues/125909) [security] internal python environments are all using outdated and multi-vulnerable hermes-agent python packages `type/security` `P3` `needs-repro` `area/install-update` 💬1
- [#125899](https://github.com/NousResearch/hermes-agent/issues/125899) Desktop Bot Mode: clicking a bot whose Bot Chat is hosted in the main workspace tab does nothing while another bot's tab is active `type/bug` `P2` `comp/desktop` `platform/windows`

### 🔒 Closed Issues
- [#75587](https://github.com/NousResearch/hermes-agent/issues/75587) [Bug]: Deleted session still surfaces permission/approval prompts while its agent turn is in flight
- [#63784](https://github.com/NousResearch/hermes-agent/issues/63784) [Bug]: Two stacked bugs that only become a hard failure on macOS 26:
- [#92352](https://github.com/NousResearch/hermes-agent/issues/92352) [Bug]: Desktop app doesn't refresh the sessions list when switching between local and remote gateways
- [#92508](https://github.com/NousResearch/hermes-agent/issues/92508) [Bug]: Desktop — transcript silently truncated to the OLDEST page against a backend that predates `order=latest` on GET /api/sessions/{id}/messages (REST skew not covered by DESKTOP_BACKEND_CONTRACT; 
- [#82527](https://github.com/NousResearch/hermes-agent/issues/82527) [Bug]: Desktop — cron run entries (sidebar peek + Cron page) select but never open the run session
- [#122424](https://github.com/NousResearch/hermes-agent/issues/122424) package.json pins js-yaml@4.3.1 / yaml<2.9 to known CVE ranges (GHSA-2883-xcg3-v3hh, GHSA-48c2-rrv3-qjmp)
- [#55169](https://github.com/NousResearch/hermes-agent/issues/55169) [Feature]: File visibility

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,900 · **Open issues:** 748 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11202](https://github.com/zeroclaw-labs/zeroclaw/pull/11202) fix(gateway): share one inbound-auth state between the gateway and RPC
- [#11121](https://github.com/zeroclaw-labs/zeroclaw/pull/11121) docs(zerocode): require a bearer token for remote WSS connections
- [#8909](https://github.com/zeroclaw-labs/zeroclaw/pull/8909) feat(plugins): add gateway and dashboard capability catalog
- [#11109](https://github.com/zeroclaw-labs/zeroclaw/pull/11109) fix(docs): publish the root llms pair on stable promotion
- [#11107](https://github.com/zeroclaw-labs/zeroclaw/pull/11107) fix(plugins): escape apostrophes in egress remedy commands
- [#11178](https://github.com/zeroclaw-labs/zeroclaw/pull/11178) feat(plugins): admit channel mirrors declared by manifest `provides`
- [#11086](https://github.com/zeroclaw-labs/zeroclaw/pull/11086) fix(release): publish the dashboard bundle preflight verified
- [#10070](https://github.com/zeroclaw-labs/zeroclaw/pull/10070) feat(tools): gate file_download against SSRF with private-host opt-in
- [#9197](https://github.com/zeroclaw-labs/zeroclaw/pull/9197) fix(channels): connect CLI Ctrl+C to supervisor lifecycle token
- [#11184](https://github.com/zeroclaw-labs/zeroclaw/pull/11184) fix(agent): attribute history-trim observer events

### 🐛 New Issues
- [#11204](https://github.com/zeroclaw-labs/zeroclaw/issues/11204) [Bug]: OpenRouter spend shows $0.00 and all tokens classified "free tok" — usage.cost never ingested `bug`
- [#11198](https://github.com/zeroclaw-labs/zeroclaw/issues/11198) [Bug]: Delegated memory tools lose principal scope `bug` `agent` `memory` `runtime` `tool` `tool:delegate` `domain:security` `priority:p0` `tool:memory` `status:accepted` `follow-up` `risk:high` `topic:identity-access` 💬1
- [#11197](https://github.com/zeroclaw-labs/zeroclaw/issues/11197) [Bug]: Session resume restores forwarded environment after admin revocation `bug` `agent` `runtime` `tool` `domain:security` `priority:p0` `tool:shell` `status:accepted` `follow-up` `risk:high` `topic:identity-access` 💬1
- [#11180](https://github.com/zeroclaw-labs/zeroclaw/issues/11180) [Bug]: Flaky: llm_request_payload_off_still_carries_prefix_fingerprints reads another test's record under the parallel runtime gate `bug` `ci` `agent` `runtime` `tests` `priority:p2` `status:in-progress` `risk:low` `type:test` 💬1
- [#11179](https://github.com/zeroclaw-labs/zeroclaw/issues/11179) [Bug]: Flaky: sop::engine pending_park_retry_respects_pending_pool_cap fails when the test crosses a second boundary `bug` `ci` `runtime` `tests` `priority:p2` `risk:low` `type:test`

### 🔒 Closed Issues
- [#11097](https://github.com/zeroclaw-labs/zeroclaw/issues/11097) [Bug]: Plugin egress remedy commands do not escape apostrophes in existing grants
- [#11093](https://github.com/zeroclaw-labs/zeroclaw/issues/11093) [Bug]: Stable docs promotion leaves root llms files out of sync
- [#9155](https://github.com/zeroclaw-labs/zeroclaw/issues/9155) [Bug]: WhatsApp Web Ctrl+C exits listener but supervisor restarts it indefinitely
- [#10523](https://github.com/zeroclaw-labs/zeroclaw/issues/10523) [Bug]: Bootstrap file truncation at 6000 chars is invisible to the operator
- [#9323](https://github.com/zeroclaw-labs/zeroclaw/issues/9323) [Feature]: Define execution-tree iteration budget ownership

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,632 · **Open issues:** 1,533 · **Last push:** 5h ago

### 🐛 New Issues
- [#8113](https://github.com/nearai/ironclaw/issues/8113) Proposal: opt-in turn-0 tool selection (BM25F + embeddings)

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,875 · **Open issues:** 98 · **Last push:** 5d ago

### 🐛 New Issues
- [#1286](https://github.com/moltis-org/moltis/issues/1286) [Bug]: DeepSeek-V4.1-Flash ("deepseek-flash") is not detected as a reasoning model — Reasoning Effort toggle missing

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 22h ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 1d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 2d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 12d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 20d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 22d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 30d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 34d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 46d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 49d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [FT: Corporate America rejects overpriced frontier, embraces open models](https://reddit.com/r/LocalLLaMA/comments/1wrzpzg/ft_corporate_america_rejects_overpriced_frontier/) ↑149
- [Qwen plays World of Warcraft](https://reddit.com/r/LocalLLaMA/comments/1wry136/qwen_plays_world_of_warcraft/) ↑91

### r/singularity — top 5 new
- [Video models are getting good](https://reddit.com/r/singularity/comments/1wqbytd/video_models_are_getting_good/) ↑1459
- [Five frontier AIs were told to engineer and 3D-print the strongest bridge they could with 500 g of plastic. Claude Opus 5.5’s design held ~130 lb, nearly 5× the runner-up](https://reddit.com/r/singularity/comments/1wrvki8/five_frontier_ais_were_told_to_engineer_and/) ↑657
- [Introducing Vitruvian, a genetic optimization model for optimizing human embryo DNA and reportedly being able to increase the IQ of a person by 14 points, nearly a standard deviation which is incredib](https://reddit.com/r/singularity/comments/1wrq633/introducing_vitruvian_a_genetic_optimization/) ↑492
- [Claude Opus 5.5 controlled a robot arm to copy Michelangelo, noticed it had left a broken line, and went back to fix the mistake on its own](https://reddit.com/r/singularity/comments/1wrgebj/claude_opus_55_controlled_a_robot_arm_to_copy/) ↑408
- [Claude Opus 5.5 designed a processor faster and smaller than the human-made one on the HWE benchmark](https://reddit.com/r/singularity/comments/1wrera2/claude_opus_55_designed_a_processor_faster_and/) ↑394

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [How is GPT-6-Luna so good?!](https://reddit.com/r/openclaw/comments/1wrgu8e/how_is_gpt6luna_so_good/) ↑26
- [Worktable: docs, plans and interactive tools for OpenClaw and other agents](https://reddit.com/r/openclaw/comments/1wr90up/worktable_docs_plans_and_interactive_tools_for/) ↑3
- [start with opencaw - hermes](https://reddit.com/r/openclaw/comments/1wrvbbh/start_with_opencaw_hermes/) ↑2
- [Which version of openclaw work with ollama and local models on windows?](https://reddit.com/r/openclaw/comments/1wrl3nu/which_version_of_openclaw_work_with_ollama_and/) ↑2
- [RDMA & Eco with OpenClaw](https://reddit.com/r/openclaw/comments/1ws1jmr/rdma_eco_with_openclaw/) ↑1

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [Today Microsoft announced Autopilot, an always on agent built on OpenClaw

The best part of this collaboration is how mu](https://x.com/openclaw/status/2103678752194703762)

### X — @steipete
- [Same. 
@useblacksmith
 has been an amazing sponsor but we need to distribute the load. 

My plan is to let codex decide ](https://x.com/steipete/status/2104305554760114488) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
