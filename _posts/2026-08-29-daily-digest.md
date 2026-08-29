---
layout: post
title: "Ecosystem Digest — 2026-08-29"
date: 2026-08-29 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-08-29
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 387,941 | 10 | 4 | 10 | 1 |
| **hermesagent** | 237,775 | 5 | 2 | 4 | 0 |
| **ZeroClaw** | 32,668 | 12 | 6 | 10 | 0 |
| **IronClaw** | 12,603 | 9 | 2 | 10 | 1 |
| **Moltis** | 2,838 | 1 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 387,941 · **Open issues:** 5,737 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.9.1-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.9.1-beta.1) — openclaw 2026.9.1-beta.1

### ✅ Merged PRs
- [#132265](https://github.com/openclaw/openclaw/pull/132265) fix: accept canonical workspace paths for sandboxed sessions
- [#132210](https://github.com/openclaw/openclaw/pull/132210) fix(build): reject native declaration compiler failures
- [#132189](https://github.com/openclaw/openclaw/pull/132189) fix(codex): explicitly selected hidden models fail bounded turns
- [#132190](https://github.com/openclaw/openclaw/pull/132190) fix(compaction): preserve headroom for local chat follow-up turns
- [#131750](https://github.com/openclaw/openclaw/pull/131750) fix(ui): keep composer textarea native undo and redo working
- [#132268](https://github.com/openclaw/openclaw/pull/132268) fix(e2e): retain readable plugin update handoff evidence
- [#132169](https://github.com/openclaw/openclaw/pull/132169) fix(ci): stop Git descendants before standalone checkout reuse
- [#132267](https://github.com/openclaw/openclaw/pull/132267) test: select workspace mode for worker wire permission proof
- [#132252](https://github.com/openclaw/openclaw/pull/132252) fix: package inventory is skipped for symlinked source paths
- [#132198](https://github.com/openclaw/openclaw/pull/132198) chore(ui): refresh control ui locales

### 🐛 New Issues
- [#132281](https://github.com/openclaw/openclaw/issues/132281) spawn-worker / long-running detached processes have no way to wake the calling session on exit 💬1
- [#132280](https://github.com/openclaw/openclaw/issues/132280) Isolated cron with implicit delivery target silently refuses at fire-time 💬1
- [#132278](https://github.com/openclaw/openclaw/issues/132278) [Bug]: gateway install hides unsafe service directory permissions `bug` `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬1
- [#132270](https://github.com/openclaw/openclaw/issues/132270) [Feature]: State DB: fail-stop barriers against concurrent schema migration wiping operator data `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `impact:data-loss` `P0` `issue-rating: 🦞 diamond lobster` 💬1
- [#132263](https://github.com/openclaw/openclaw/issues/132263) [Bug]: Control UI renders the commentary portion of an assistant message three times (stored once) 💬1
- [#132262](https://github.com/openclaw/openclaw/issues/132262) fix(acp): abort cause (errorMessage) is silently dropped, IDE shows a bare cancel `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` `clawsweeper:bulk-filed` 💬1
- [#132258](https://github.com/openclaw/openclaw/issues/132258) fix(acp): user approval decisions made during a gateway disconnect are silently dropped 💬1
- [#132253](https://github.com/openclaw/openclaw/issues/132253) [Bug]: Codex Platform turns use default reasoning when thinking is off `bug` `maintainer` `P2` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#132247](https://github.com/openclaw/openclaw/issues/132247) Live presence merges qualified profiles with colliding unqualified IDs `bug` `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬1
- [#132243](https://github.com/openclaw/openclaw/issues/132243) Creator-based sharing confuses actor namespaces and loses merged profiles `bug` `maintainer` `P2` `clawsweeper:source-repro` `impact:session-state` `impact:security` `issue-rating: 🦞 diamond lobster` `maturity:stable` 💬2

### 🔒 Closed Issues
- [#132187](https://github.com/openclaw/openclaw/issues/132187) [Bug]: Explicit hidden Codex models fail bounded turns
- [#132245](https://github.com/openclaw/openclaw/issues/132245) [Bug]: sandboxed session creation rejects canonical macOS workspace paths
- [#131762](https://github.com/openclaw/openclaw/issues/131762) [Bug]: Local 32K chat fails its second turn at the compaction safeguard
- [#131708](https://github.com/openclaw/openclaw/issues/131708) WebChat textarea: native redo (Shift+Cmd+Z) broken — controlled re-rendering breaks the undo/redo chain

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 237,775 · **Open issues:** 37,146 · **Last push:** <1h ago

### ✅ Merged PRs
- [#97513](https://github.com/NousResearch/hermes-agent/pull/97513) fix(desktop): stop the workspace pane and pooled sockets flickering at idle
- [#97517](https://github.com/NousResearch/hermes-agent/pull/97517) fmt(js): `npm run fix` auto-fix
- [#97421](https://github.com/NousResearch/hermes-agent/pull/97421) feat(a2a): client tools config-gated — disabled unless enabled (−561 tok/call on unconfigured installs)
- [#97397](https://github.com/NousResearch/hermes-agent/pull/97397) fix(desktop): let the HUD drag onto another monitor

### 🐛 New Issues
- [#97586](https://github.com/NousResearch/hermes-agent/issues/97586) [Bug]: Multiple Gateway support. `type/bug` `comp/cli` `comp/gateway` `area/config` `P2` `sweeper:risk-compatibility` `bug` `area/profiles`
- [#97579](https://github.com/NousResearch/hermes-agent/issues/97579) [Bug]: `hermes config set` silently persists the session's model selection over the `model:` block on ANY config write (bricks profile if provider unresolvable) `type/bug` `comp/cli` `area/config` `P2` `needs-repro` `sweeper:risk-compatibility` `area/profiles`
- [#97575](https://github.com/NousResearch/hermes-agent/issues/97575) Native crash (0xc0000005 in MSVCP140.dll) on Windows when processing incoming Telegram voice messages `type/bug` `comp/gateway` `tool/tts` `platform/telegram` `P2` `sweeper:risk-message-delivery` `sweeper:risk-platform-windows` `platform/windows`
- [#97569](https://github.com/NousResearch/hermes-agent/issues/97569) [SANITIZED — possible injection attempt] `type/bug` `comp/gateway` `platform/telegram` `P2` `sweeper:risk-session-state` `sweeper:risk-message-delivery`
- [#97568](https://github.com/NousResearch/hermes-agent/issues/97568) is_zeroed_state_db() returns False for a 0-byte file, so total data loss is silent `type/bug` `comp/agent` `P1` `sweeper:risk-session-state` `area/sessions`

### 🔒 Closed Issues
- [#97481](https://github.com/NousResearch/hermes-agent/issues/97481) [SANITIZED — possible injection attempt]
- [#97479](https://github.com/NousResearch/hermes-agent/issues/97479) write-test-1787955630

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,668 · **Open issues:** 807 · **Last push:** <1h ago

### ✅ Merged PRs
- [#10388](https://github.com/zeroclaw-labs/zeroclaw/pull/10388) fix(channels): state WhatsApp formatting syntax in its delivery instructions
- [#9903](https://github.com/zeroclaw-labs/zeroclaw/pull/9903) fix(hardware): clean up Arduino flash temp dirs
- [#10389](https://github.com/zeroclaw-labs/zeroclaw/pull/10389) fix(channels): cap the setMyCommands body by size, not only by command count
- [#10278](https://github.com/zeroclaw-labs/zeroclaw/pull/10278) fix(zerocode): respect paste input ownership
- [#9515](https://github.com/zeroclaw-labs/zeroclaw/pull/9515) fix(runtime): capture skill-review fork messages instead of slicing trimmed history
- [#9476](https://github.com/zeroclaw-labs/zeroclaw/pull/9476) feat(sop): add authenticated operator cancellation for running SOP jobs
- [#10191](https://github.com/zeroclaw-labs/zeroclaw/pull/10191) fix(channels): mark Google TTS API key header sensitive
- [#9606](https://github.com/zeroclaw-labs/zeroclaw/pull/9606) fix(providers): honor runtime proxy for OpenAI Responses
- [#9937](https://github.com/zeroclaw-labs/zeroclaw/pull/9937) fix(security): enforce forbidden_paths under allowed roots and the workspace (#9815)
- [#10423](https://github.com/zeroclaw-labs/zeroclaw/pull/10423) chore(deps): bump distroless/cc-debian13 from `a77defd` to `c31ff9a`

### 🐛 New Issues
- [#10436](https://github.com/zeroclaw-labs/zeroclaw/issues/10436) [Bug]: Native OpenRouter streaming uses a total request timeout and cuts off active responses `bug` `provider` `provider:openrouter` `priority:p2` `risk:medium`
- [#10434](https://github.com/zeroclaw-labs/zeroclaw/issues/10434) [Task]: harden daemon startup deadlock guards under parallel load `bug` `ci` `runtime` `tests` `priority:p1` `risk:low` `type:test`
- [#10432](https://github.com/zeroclaw-labs/zeroclaw/issues/10432) [Bug]: Mark ElevenLabs TTS API key header as sensitive `bug` `channel` `domain:security` `priority:p2` `status:accepted` `follow-up` `risk:high`
- [#10429](https://github.com/zeroclaw-labs/zeroclaw/issues/10429) [Bug]: Deepgram and OpenAI transcription providers silently drop the configured language hint — non-English voice notes return empty transcripts and are skipped `bug` `channel` `config` `provider` `channel:telegram` `priority:p1` `risk:medium` 💬2
- [#10427](https://github.com/zeroclaw-labs/zeroclaw/issues/10427) ci: Advisory scan failed — 2026-08-28 `ci` `dependencies` `domain:security` `priority:p1` `status:in-progress` `risk:medium` `type:dependencies`
- [#10426](https://github.com/zeroclaw-labs/zeroclaw/issues/10426) [Feature]: Show user-facing agent progress in Telegram `enhancement` `channel` `config` `runtime` `channel:telegram` `priority:p2` `risk:high` 💬1
- [#10422](https://github.com/zeroclaw-labs/zeroclaw/issues/10422) [Feature]: Run SOP as heartbeat `enhancement` `config` `daemon` `heartbeat` `runtime` `tool:sop` `priority:p3` `risk:high` 💬1
- [#10421](https://github.com/zeroclaw-labs/zeroclaw/issues/10421) [Feature]: Paginate persisted ACP transcript restoration in ZeroCode `enhancement` `runtime` `priority:p2` `follow-up` `zerocode` `risk:high` `channel:acp`
- [#10419](https://github.com/zeroclaw-labs/zeroclaw/issues/10419) [Feature]: Stream agent-loop tokens from POST /webhook (SSE) `enhancement` `gateway` `runtime` `priority:p2` `risk:high` 💬2
- [#10409](https://github.com/zeroclaw-labs/zeroclaw/issues/10409) fix(channels): secure temp file handling with 0o600 permissions `bug` `channel` `domain:security` `priority:p1` `risk:high` 💬1
- [#10408](https://github.com/zeroclaw-labs/zeroclaw/issues/10408) [Bug]: second message during an active turn starts a parallel run in the same session → duplicate work and duplicate reply `bug` `channel` `runtime` `channel:core` `priority:p1` `status:in-progress` `risk:high` 💬2
- [#10405](https://github.com/zeroclaw-labs/zeroclaw/issues/10405) [Tracker]: Implement session-scoped prompt attachments (#9998) `enhancement` `agent` `channel` `config` `gateway` `memory` `runtime` `security` `agent:prompt` `domain:security` `domain:architecture` `priority:p2` `status:accepted` `status:no-stale` `zerocode` `risk:high` `channel:acp` `type:tracker` 💬1

### 🔒 Closed Issues
- [#9711](https://github.com/zeroclaw-labs/zeroclaw/issues/9711) bug(hardware): clean up Arduino flash temporary directories on every exit
- [#10180](https://github.com/zeroclaw-labs/zeroclaw/issues/10180) [Bug]: ZeroCode paste mutates the hidden composer while another surface owns input
- [#9425](https://github.com/zeroclaw-labs/zeroclaw/issues/9425) [Bug]: Running SOP jobs have no operator cancellation path
- [#8654](https://github.com/zeroclaw-labs/zeroclaw/issues/8654) [Bug]: skill-review fork panics (out-of-range slice at skills/review.rs:159) → daemon SIGSEGV after tool-heavy turn
- [#10175](https://github.com/zeroclaw-labs/zeroclaw/issues/10175) [Bug]: Mark Google TTS API key header as sensitive
- [#9815](https://github.com/zeroclaw-labs/zeroclaw/issues/9815) security: forbidden_paths is unreachable for any path under allowed_roots or the workspace

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,603 · **Open issues:** 1,478 · **Last push:** 2h ago

### 🚀 New Releases
- [ironclaw-v1.4.0](https://github.com/nearai/ironclaw/releases/tag/ironclaw-v1.4.0) — 1.4.0 - 2026-08-27

### ✅ Merged PRs
- [#7982](https://github.com/nearai/ironclaw/pull/7982) fix(tools): stop sending the model after a result_read budget it cannot reach
- [#7979](https://github.com/nearai/ironclaw/pull/7979) test(extensions): enforce encoded output ownership
- [#7980](https://github.com/nearai/ironclaw/pull/7980) ci: validate integration group topology
- [#7901](https://github.com/nearai/ironclaw/pull/7901) fix(notifications): persist auth gates before enrichment
- [#7965](https://github.com/nearai/ironclaw/pull/7965) perf(tool-search, github): stop offering tools that match one incidental query term
- [#7900](https://github.com/nearai/ironclaw/pull/7900) feat(notifications): publish durable resource blocks
- [#7973](https://github.com/nearai/ironclaw/pull/7973) fix(loop-host): deduplicate replayed tool results
- [#7962](https://github.com/nearai/ironclaw/pull/7962) fix(loop): compact and resume once on context overflow
- [#7966](https://github.com/nearai/ironclaw/pull/7966) chore(agents): refresh codebase knowledge graph
- [#7972](https://github.com/nearai/ironclaw/pull/7972) fix(threads): a scrubbed preview gives no signal, so the model retries forever

### 🐛 New Issues
- [#7987](https://github.com/nearai/ironclaw/issues/7987) tool schemas: flatten_top_level rebuilds from a whitelist, silently discarding every non-forbidden top-level constraint `bug` `scope: llm`
- [#7986](https://github.com/nearai/ironclaw/issues/7986) perf(github): list_repos ships 81 raw fields per repo — 519 KB for one listing, with the package's own projection seam unused `bug` `scope: extensions` `suggested_P2`
- [#7981](https://github.com/nearai/ironclaw/issues/7981) perf(github, tools): a raw list_repos payload plus an unhinted result_read schema cost 64 tool calls and 3m01s to list repos `bug` `scope: tool/builtin` `scope: extensions` `suggested_P2` 💬3
- [#7971](https://github.com/nearai/ironclaw/issues/7971) feat(webui): render model capability tags across Inference selectors
- [#7970](https://github.com/nearai/ironclaw/issues/7970) feat(llm): preserve NEAR AI model modalities through model discovery
- [#7969](https://github.com/nearai/ironclaw/issues/7969) feat(llm): surface NEAR AI model capabilities across model-selection UI
- [#7930](https://github.com/nearai/ironclaw/issues/7930) perf(tools): allow tool arguments to cite a prior result by reference instead of re-emitting it `p1`
- [#7903](https://github.com/nearai/ironclaw/issues/7903) Decision spike: persistent per-user sandboxed executor behind the trusted host kernel `enhancement` `risk: high` `scope: agent` `scope: sandbox` `reborn` 💬2
- [#7891](https://github.com/nearai/ironclaw/issues/7891) perf(extensions): unprojected capability payloads + blind 24 KiB head-slice cost 14.3s of inference on two emails `bug` `risk: medium` `scope: tool` `scope: extensions` `reborn` `performance` 💬10

### 🔒 Closed Issues
- [#7875](https://github.com/nearai/ironclaw/issues/7875) Publish run-bound extension authentication-required notifications
- [#7874](https://github.com/nearai/ironclaw/issues/7874) Publish resource and policy blocked-run notifications

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,838 · **Open issues:** 82 · **Last push:** 1d ago

### 🐛 New Issues
- [#1246](https://github.com/moltis-org/moltis/issues/1246) [Bug]: can't run on sandbox after a node is added `bug`

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 3h ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 20h ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 4d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 16d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 19d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 22d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 24d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 26d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 28d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 28d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Research] Automated Researchers Mitigate Alignment Failures](https://www.anthropic.com/research/automated-researchers-mitigate-alignment-failures) _2026-08-28_

### OpenAI — 3 new
- [Rosalind](https://openai.com/rosalind/) _2026-08-28_
- [[Index] Our Decision On Cursor Following Its Acquisition By Spacex](https://openai.com/index/our-decision-on-cursor-following-its-acquisition-by-spacex/) _2026-08-29_
- [[Index] Supporting Next Generation Ai Startups Thailand](https://openai.com/index/supporting-next-generation-ai-startups-thailand/) _2026-08-28_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [claude mods didn't like that, somehow 🤷‍♀️](https://reddit.com/r/LocalLLaMA/comments/1w0lz7e/claude_mods_didnt_like_that_somehow/) ↑1242
- [Tencent/Hy4-preview 770B-A49B weight dropped](https://reddit.com/r/LocalLLaMA/comments/1w0igxk/tencenthy4preview_770ba49b_weight_dropped/) ↑530
- [zai-org/GLM-5.3 · Hugging Face](https://reddit.com/r/LocalLLaMA/comments/1w0tgzl/zaiorgglm53_hugging_face/) ↑512
- [Micron: HBM Requires Three Times More Wafer Area Than DDR5](https://reddit.com/r/LocalLLaMA/comments/1w0mmk7/micron_hbm_requires_three_times_more_wafer_area/) ↑294
- [open source caught up because it's open](https://reddit.com/r/LocalLLaMA/comments/1w0kstl/open_source_caught_up_because_its_open/) ↑285

### r/singularity — top 5 new
- [Robot taunting opponent](https://reddit.com/r/singularity/comments/1w0l1di/robot_taunting_opponent/) ↑898
- [Judge says Pentagon’s measures against Anthropic were ‘illegal and baseless’](https://reddit.com/r/singularity/comments/1w0mn1a/judge_says_pentagons_measures_against_anthropic/) ↑426
- [Trump says NASA is building a nuclear-powered starship set for a 2028 Mars mission](https://reddit.com/r/singularity/comments/1w11kz8/trump_says_nasa_is_building_a_nuclearpowered/) ↑416
- [I Suspect the Same on Reddit as Well. Handful of Accounts have been Posting Dogmatic Anti-AI Rhetoric on All Popular Subs](https://reddit.com/r/singularity/comments/1w0fq6x/i_suspect_the_same_on_reddit_as_well_handful_of/) ↑360
- [Runway shares a video highlighting what you can do with current SOTA image gen models and tooling](https://reddit.com/r/singularity/comments/1w0rmif/runway_shares_a_video_highlighting_what_you_can/) ↑356

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Best model on Ollama Cloud to use with OpenClaw?](https://reddit.com/r/openclaw/comments/1w0rrkc/best_model_on_ollama_cloud_to_use_with_openclaw/) ↑4
- [Can a 64GB M5 Pro MacBook run a local OpenClaw setup for high-level copywriting?](https://reddit.com/r/openclaw/comments/1w18cta/can_a_64gb_m5_pro_macbook_run_a_local_openclaw/) ↑2
- [Is it possible to remove the message for using a fallback?](https://reddit.com/r/openclaw/comments/1w10ka6/is_it_possible_to_remove_the_message_for_using_a/) ↑2
- [What shared-file setup keeps OpenClaw and humans working from the same source of truth?](https://reddit.com/r/openclaw/comments/1w0tly0/what_sharedfile_setup_keeps_openclaw_and_humans/) ↑1
- [Zero Token Usage???](https://reddit.com/r/openclaw/comments/1w0egz8/zero_token_usage/) ↑1

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
_No new tweets in the last 7 days._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
