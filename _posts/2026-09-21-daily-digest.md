---
layout: post
title: "Ecosystem Digest — 2026-09-21"
date: 2026-09-21 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-21
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 390,159 | 8 | 3 | 10 | 0 |
| **hermesagent** | 247,491 | 10 | 7 | 10 | 0 |
| **ZeroClaw** | 32,845 | 15 | 10 | 10 | 0 |
| **IronClaw** | 12,624 | 0 | 0 | 1 | 0 |
| **Moltis** | 2,865 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 390,159 · **Open issues:** 8,213 · **Last push:** <1h ago

### ✅ Merged PRs
- [#151457](https://github.com/openclaw/openclaw/pull/151457) fix(ui): match transcript bubble corners to code blocks
- [#153932](https://github.com/openclaw/openclaw/pull/153932) fix: keep model refresh indicators compact and accurate
- [#154260](https://github.com/openclaw/openclaw/pull/154260) fix: stabilize bounded Codex rollout preview test
- [#154178](https://github.com/openclaw/openclaw/pull/154178) perf(transcripts): move tool list and show reads off thread
- [#154270](https://github.com/openclaw/openclaw/pull/154270) test(models): advance the refresh deadline without sleeping
- [#154235](https://github.com/openclaw/openclaw/pull/154235) fix: make update test fixtures faster and independent of umask
- [#154187](https://github.com/openclaw/openclaw/pull/154187) fix(test): overlapping Windows checkout fixtures lose their temp mount
- [#154254](https://github.com/openclaw/openclaw/pull/154254) chore: share multi-file bootstrap test fixtures
- [#154206](https://github.com/openclaw/openclaw/pull/154206) fix(test): retire shared read pools between files
- [#154181](https://github.com/openclaw/openclaw/pull/154181) improve(ci): run Gateway server tests in parallel

### 🐛 New Issues
- [#154281](https://github.com/openclaw/openclaw/issues/154281) [Bug]: Gateway close after a sent CLI write reports a definite failure and advises retrying the command 💬1
- [#154278](https://github.com/openclaw/openclaw/issues/154278) secrets.egressProxy blocks ALL exec calls from cron/automation agentTurn runs ("Secret egress proxy requires an admitted agent run instance") 💬2
- [#154277](https://github.com/openclaw/openclaw/issues/154277) [Bug]: 2026.9.5 doctor --fix halts on active_sqlite_transcript_jsonl (422 JSONL transcripts already fully in SQLite); recover is a noop and nothing can settle it `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:session-state` `P0` `issue-rating: 🦐 gold shrimp` `impact:ux-release-blocker` 💬1
- [#154276](https://github.com/openclaw/openclaw/issues/154276) [Bug]: 2026.9.5 idle Gateway burns one core in a WorkerThread after a healthy start `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#154275](https://github.com/openclaw/openclaw/issues/154275) CI: plugin overview Settings click intermittently leaves the view query unset `maintainer` `P2` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#154271](https://github.com/openclaw/openclaw/issues/154271) Webchat: composer autosize forces per-keystroke layout that scales with draft size; a large per-session durable draft makes one session lag until site data is cleared `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#154264](https://github.com/openclaw/openclaw/issues/154264) [Bug]: Config write serialization crashes with RangeError on deeply nested documents `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:linked-pr-open` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` 💬1
- [#154252](https://github.com/openclaw/openclaw/issues/154252) [Bug]: requester settle-wake attempt exhaustion is unreachable for a batch stuck in dispatching `P1` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#151440](https://github.com/openclaw/openclaw/issues/151440) [Bug]: Transcript bubble corners differ from code blocks in rounded themes
- [#154280](https://github.com/openclaw/openclaw/issues/154280) Update failure: managed-service-handoff-unavailable (2026.9.5)
- [#153845](https://github.com/openclaw/openclaw/issues/153845) [Bug]: conversation listing fails after a Matrix, Telegram, or Slack account is removed

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 247,491 · **Open issues:** 43,021 · **Last push:** <1h ago

### ✅ Merged PRs
- [#117652](https://github.com/NousResearch/hermes-agent/pull/117652) fix(desktop): SSH connections learn their backend install id so duplicate addresses collapse (#117226, salvage #117228)
- [#117651](https://github.com/NousResearch/hermes-agent/pull/117651) fix(desktop): removing or re-pointing a connection forgets its cached roster and identity (#117227, salvage #117232)
- [#117649](https://github.com/NousResearch/hermes-agent/pull/117649) fix(kanban): completing a task with no result or summary is refused with an audit event (#117483, salvage #117511)
- [#117592](https://github.com/NousResearch/hermes-agent/pull/117592) fix(mcp): OAuth metadata shim no longer consumes MCP SSE responses, tools/list no longer hangs (#117414, salvage #117416)
- [#117680](https://github.com/NousResearch/hermes-agent/pull/117680) fix(lsp): one stalled request no longer silences a workspace for good — retry window, cold-root warm-up budget, per-root exclusion (#116446)
- [#117668](https://github.com/NousResearch/hermes-agent/pull/117668) fix(desktop): chat composer stays mounted through transient session loaders; no addRange on a detached editor (#117375, #117285)
- [#117665](https://github.com/NousResearch/hermes-agent/pull/117665) fix(compression): an auto-resolved summary model that fails falls back to the main model and is named in the warning (#116472, salvage #116592)
- [#117663](https://github.com/NousResearch/hermes-agent/pull/117663) fix(update): pending fleet restart leaves gateways already on the checkout code alone (#117051)
- [#117657](https://github.com/NousResearch/hermes-agent/pull/117657) feat(update): hermes update --list-venv-holders reports venv holders as JSON, exit 3 (#117246)
- [#117654](https://github.com/NousResearch/hermes-agent/pull/117654) feat(delegation): owner-death recovery event includes transcript tails and git state so the parent can continue without forensics (#116000)

### 🐛 New Issues
- [#117796](https://github.com/NousResearch/hermes-agent/issues/117796) [Bug]: Defender quarantines regenerated Windows CLI hermes.exe as Pomal!rfn (Hermes 0.21.3, uv 0.12.16)
- [#117795](https://github.com/NousResearch/hermes-agent/issues/117795) [Bug]: Telegram media_write_timeout is hardcoded (gateway) or unset entirely (standalone send), not env-overridable like the other timeouts
- [#117794](https://github.com/NousResearch/hermes-agent/issues/117794) [Bug]: tools/neutts_synth.py discards the real exception on a failed neutts import, always prints the same hardcoded message
- [#117793](https://github.com/NousResearch/hermes-agent/issues/117793) [Bug]: context-limit error parsing has no pattern for llama.cpp's "context size (N tokens)" phrasing
- [#117792](https://github.com/NousResearch/hermes-agent/issues/117792) [Bug]: classify_items.py cron script never includes its own required JSON schema in the prompt
- [#117791](https://github.com/NousResearch/hermes-agent/issues/117791) [Bug]: TASK_COMPLETION_GUIDANCE has no guard against fabricating a TOOL CALL when no matching tool exists
- [#117790](https://github.com/NousResearch/hermes-agent/issues/117790) [Bug]: fact_store.add stores raw tool-call payloads and self-narration as durable facts, category silently defaults to general
- [#117788](https://github.com/NousResearch/hermes-agent/issues/117788) [SANITIZED — possible injection attempt]
- [#117784](https://github.com/NousResearch/hermes-agent/issues/117784) [Bug]: surrogate stdin round-trip tests spawn bare "bash" — WSL stub writes drvfs-mangled files into the repo root, 3 tests red on Windows (test-only slice of #116818) `type/test` `comp/tools` `tool/file` `P3` `sweeper:risk-platform-windows` `platform/windows` 💬1
- [#117781](https://github.com/NousResearch/hermes-agent/issues/117781) [Bug]: Windows desktop app flashes ~7–8 console windows at startup (console-less backend spawns git/tasklist/powershell without CREATE_NO_WINDOW) `type/bug` `P2` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows` `bug`

### 🔒 Closed Issues
- [#117226](https://github.com/NousResearch/hermes-agent/issues/117226) [Bug]: SSH connections never learn their backend install_id, so the same-backend roster collapse never applies to them
- [#117227](https://github.com/NousResearch/hermes-agent/issues/117227) [Bug]: removing or re-pointing a connection leaves its SSH roster and install-id caches, and connection ids are recycled
- [#117483](https://github.com/NousResearch/hermes-agent/issues/117483) [Bug]: `kanban complete` accepts a completion with no evidence at all - the card lands in `done` carrying nothing
- [#117414](https://github.com/NousResearch/hermes-agent/issues/117414) MCP OAuth metadata compatibility shim consumes session-long SSE resource responses and deadlocks tool discovery
- [#116446](https://github.com/NousResearch/hermes-agent/issues/116446) LSP: one diagnostics timeout poisons an entire workspace (per-ROOT broken set), and a 5s steady-state budget is applied to a cold server that needs ~55s
- [#117285](https://github.com/NousResearch/hermes-agent/issues/117285) [Desktop] Chat area flickers / remounts — addRange(): The given range isn't in document
- [#117375](https://github.com/NousResearch/hermes-agent/issues/117375) [Bug]: Hermes Desktop chat composer disappears during transient loading state

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,845 · **Open issues:** 769 · **Last push:** 1h ago

### ✅ Merged PRs
- [#9830](https://github.com/zeroclaw-labs/zeroclaw/pull/9830) fix(browser): make full browser automation opt-in, separate from browser_open
- [#10722](https://github.com/zeroclaw-labs/zeroclaw/pull/10722) fix(runtime): deliver pre-tool narration and terminal fallback to event consumers
- [#9134](https://github.com/zeroclaw-labs/zeroclaw/pull/9134) fix(plugins): admit exact component payload bytes
- [#9713](https://github.com/zeroclaw-labs/zeroclaw/pull/9713) feat(runtime): expose token accounting on history-trim events
- [#10255](https://github.com/zeroclaw-labs/zeroclaw/pull/10255) feat(security): oidc.<alias> token-verification provider (#8289 stage 5, supersedes #8672 in part)
- [#10959](https://github.com/zeroclaw-labs/zeroclaw/pull/10959) fix(runtime): sort tool specs so the prompt-cache prefix is stable
- [#8561](https://github.com/zeroclaw-labs/zeroclaw/pull/8561) feat(channels/telegram): add multi_message streaming mode
- [#10928](https://github.com/zeroclaw-labs/zeroclaw/pull/10928) fix(runtime): recognize exited Windows task owners
- [#10811](https://github.com/zeroclaw-labs/zeroclaw/pull/10811) fix(tools): preserve Windows PowerShell analysis cache
- [#10677](https://github.com/zeroclaw-labs/zeroclaw/pull/10677) docs(governance): implement expedited merge lane

### 🐛 New Issues
- [#11021](https://github.com/zeroclaw-labs/zeroclaw/issues/11021) Guarantee exactly-once session_end delivery after ACP hard cancellation
- [#11020](https://github.com/zeroclaw-labs/zeroclaw/issues/11020) Surface ACP TodoWrite plan persistence failures
- [#11019](https://github.com/zeroclaw-labs/zeroclaw/issues/11019) Make ACP administrative removal transactional with active-turn cancellation
- [#11017](https://github.com/zeroclaw-labs/zeroclaw/issues/11017) RFC: Preserve applicable reviews and simplify expedited merge decisions `type:rfc`
- [#11016](https://github.com/zeroclaw-labs/zeroclaw/issues/11016) [Docs]: Document the lighter-core replacement-first integration policy `docs` `type:docs`
- [#11015](https://github.com/zeroclaw-labs/zeroclaw/issues/11015) [Tracker]: Desktop computer-use protocol and spike implementation
- [#11014](https://github.com/zeroclaw-labs/zeroclaw/issues/11014) [Tracker]: Composable WASM provider and service-graph implementation
- [#11013](https://github.com/zeroclaw-labs/zeroclaw/issues/11013) [Tracker]: Unified file intake, resolver, and delivery implementation
- [#11012](https://github.com/zeroclaw-labs/zeroclaw/issues/11012) [Tracker]: Runtime ingress and adapter migration implementation
- [#11009](https://github.com/zeroclaw-labs/zeroclaw/issues/11009) [Bug]: Agent alias rename does not cascade permission-profile selectors
- [#11006](https://github.com/zeroclaw-labs/zeroclaw/issues/11006) [Task]: Restack #10259 onto current master (12 hunks, two of them semantic)
- [#11005](https://github.com/zeroclaw-labs/zeroclaw/issues/11005) [Task]: Stable RPC denial reasons and localized selector denials
- [#11004](https://github.com/zeroclaw-labs/zeroclaw/issues/11004) [Feature]: Package and supervise separate core and gateway processes in Tauri `enhancement` `gateway` `status:blocked` `status:accepted` `desktop` `tauri` `risk:high` `topic:operator-ux`
- [#11003](https://github.com/zeroclaw-labs/zeroclaw/issues/11003) [Feature]: Carry plugin webhook registration and dispatch across IPC `enhancement` `gateway` `domain:security` `channel:webhook` `status:blocked` `status:accepted` `risk:high` `topic:plugins`
- [#11002](https://github.com/zeroclaw-labs/zeroclaw/issues/11002) [Feature]: Ship zeroclaw-gw as a standalone IPC client `enhancement` `gateway` `domain:architecture` `status:blocked` `status:accepted` `risk:high` `type:refactor`

### 🔒 Closed Issues
- [#10697](https://github.com/zeroclaw-labs/zeroclaw/issues/10697) [Bug]: ZeroCode ACP transcript drops assistant text emitted before a tool call; only post-last-tool text renders as the reply
- [#9619](https://github.com/zeroclaw-labs/zeroclaw/issues/9619) [Bug]: History-trim notice omits token counts before and after trimming
- [#9106](https://github.com/zeroclaw-labs/zeroclaw/issues/9106) RFC: A2A outbound client (A2ATool)
- [#9998](https://github.com/zeroclaw-labs/zeroclaw/issues/9998) RFC: Session-scoped persistent prompt attachments
- [#9621](https://github.com/zeroclaw-labs/zeroclaw/issues/9621) RFC: staged opt-in product telemetry with operator-reviewed reports
- [#9496](https://github.com/zeroclaw-labs/zeroclaw/issues/9496) RFC: Streamline RFC scope, discussion, voting, and assignment
- [#9346](https://github.com/zeroclaw-labs/zeroclaw/issues/9346) RFC: Define the unified package/capability/config/runtime-state catalog contract
- [#9330](https://github.com/zeroclaw-labs/zeroclaw/issues/9330) RFC: AI-assisted PR pre-review and re-review
- [#9127](https://github.com/zeroclaw-labs/zeroclaw/issues/9127) RFC: Abstract a `KeySource` trait — classify master-key material by source / deployment form
- [#9103](https://github.com/zeroclaw-labs/zeroclaw/issues/9103) RFC: separate authoritative memory storage from optional enrichment connectors

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,624 · **Open issues:** 1,526 · **Last push:** <1h ago

### ✅ Merged PRs
- [#8102](https://github.com/nearai/ironclaw/pull/8102) fix(extensions): resolve provider-instance readiness live, administrator configuration first

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,865 · **Open issues:** 93 · **Last push:** 2d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬3 · 2d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 5d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 13d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 15d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 21d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 23d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 27d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 39d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 42d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 45d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [Qwen-Image-2.1 released!](https://reddit.com/r/LocalLLaMA/comments/1wlgrft/qwenimage21_released/) ↑1528
- [Would you buy a Qwen3.8-27B Taalas chip for $1k if it could run at 7,000 TPS?](https://reddit.com/r/LocalLLaMA/comments/1wltts7/would_you_buy_a_qwen3827b_taalas_chip_for_1k_if/) ↑205

### r/singularity — top 2 new
- [Victory By Any Means](https://reddit.com/r/singularity/comments/1wla34t/victory_by_any_means/) ↑3015
- [Hospitals that adopted AI fastest saw the fewest deaths so far in 2026](https://reddit.com/r/singularity/comments/1wlnquc/hospitals_that_adopted_ai_fastest_saw_the_fewest/) ↑546

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Hermes vs OpenClaw, is there actually a meaningful difference?](https://reddit.com/r/openclaw/comments/1wlqz67/hermes_vs_openclaw_is_there_actually_a_meaningful/) ↑16
- [Updated from 2026.8.1 to 2026.9.5](https://reddit.com/r/openclaw/comments/1wlfp0m/updated_from_202681_to_202695/) ↑12
- [Openclaw is Adding Annoying Safety Limits! It should be Our Choice!!!](https://reddit.com/r/openclaw/comments/1wlvc04/openclaw_is_adding_annoying_safety_limits_it/) ↑8
- [Is it me or OpenClaw is becoming slow to start](https://reddit.com/r/openclaw/comments/1wlyigq/is_it_me_or_openclaw_is_becoming_slow_to_start/) ↑5
- [After 700+ changes, I finally got OpenClaw working the way I wanted](https://reddit.com/r/openclaw/comments/1wlwfoz/after_700_changes_i_finally_got_openclaw_working/) ↑1

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [OpenClaw 2026.9.5 is here 🦞

⚛️ Atomic updates
🔥 Plugin hot reload
🤝 Conversation sharing
🎙️ Expanded GPT Live
🌐 Shared ](https://x.com/openclaw/status/2101151415301456082)

### X — @steipete
- [Your claw can now FaceTime you!](https://x.com/steipete/status/2101748928274419843) ↑0 🔁0 · recent
- [New benchmark dropped](https://x.com/steipete/status/2101748820237500557) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
