---
layout: post
title: "Ecosystem Digest — 2026-09-27"
date: 2026-09-27 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-27
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 390,599 | 11 | 5 | 10 | 0 |
| **hermesagent** | 249,253 | 5 | 9 | 10 | 0 |
| **ZeroClaw** | 32,895 | 3 | 6 | 10 | 0 |
| **IronClaw** | 12,630 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,872 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 390,599 · **Open issues:** 8,699 · **Last push:** <1h ago

### ✅ Merged PRs
- [#159248](https://github.com/openclaw/openclaw/pull/159248) fix: history reads fail after database reopens
- [#157577](https://github.com/openclaw/openclaw/pull/157577) fix(test): reap detached children in isolated Vitest runs
- [#159294](https://github.com/openclaw/openclaw/pull/159294) fix(chat): long chat sessions scroll at a few frames per second
- [#159207](https://github.com/openclaw/openclaw/pull/159207) fix(gateway): stop session terminals when resetting an Incognito session
- [#157713](https://github.com/openclaw/openclaw/pull/157713) feat(channels): configure mentions in bot-created threads
- [#159310](https://github.com/openclaw/openclaw/pull/159310) fix: update reports hide missing glibc requirements
- [#158703](https://github.com/openclaw/openclaw/pull/158703) feat(codex): enable Ultrafast for supported models
- [#159296](https://github.com/openclaw/openclaw/pull/159296) fix(ios): preserve chat typing during agent discovery
- [#159061](https://github.com/openclaw/openclaw/pull/159061) Fix flaky process-ownership test: wait for actual process-group absence, not just PID liveness
- [#158701](https://github.com/openclaw/openclaw/pull/158701) fix(ui): preserve reply targets for media-only assistant messages

### 🐛 New Issues
- [#159332](https://github.com/openclaw/openclaw/issues/159332) [Bug]: Collaborator typing previews overwhelm the conversation with 30 participants `bug`
- [#159330](https://github.com/openclaw/openclaw/issues/159330) [Bug]: Concurrent first sends to an empty shared conversation are rejected as branch changes `bug`
- [#159329](https://github.com/openclaw/openclaw/issues/159329) [Docs Bug]: Heartbeat runaway: agent loops exec("NO_REPLY") ~900 times across repeated heartbeat runs — no repetition circuit breaker `bug` `docs` 💬1
- [#159324](https://github.com/openclaw/openclaw/issues/159324) [Tracking]: Control UI concurrency hardening for 30 simultaneous users `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#159322](https://github.com/openclaw/openclaw/issues/159322) Update failure: runtime-verification-failed (2026.9.5) `clawsweeper:needs-info` `P0` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-release-blocker` 💬1
- [#159319](https://github.com/openclaw/openclaw/issues/159319) [Bug]: `openclaw skills verify` cannot resolve ClawHub skills installed before the ownerHandle fix (no repair path) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬2
- [#159317](https://github.com/openclaw/openclaw/issues/159317) Session SQLite migration recovery report (session-sqlite-1790473021568-67e14590) 💬1
- [#159313](https://github.com/openclaw/openclaw/issues/159313) [Bug]: Bun/macOS plugin capture fails with EBADF for valid /dev/fd copies over 128 KiB `bug` 💬2
- [#159305](https://github.com/openclaw/openclaw/issues/159305) chore(routing): retire oversized resolver and test exceptions `no-stale` `P3` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#159304](https://github.com/openclaw/openclaw/issues/159304) [Bug]: Incognito sessions.reset should share the delete lifecycle teardown `bug` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:session-state` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1
- [#159300](https://github.com/openclaw/openclaw/issues/159300) [SANITIZED — possible injection attempt] `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:message-loss` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#154323](https://github.com/openclaw/openclaw/issues/154323) Update failure: global-install-failed (2026.9.4)
- [#154077](https://github.com/openclaw/openclaw/issues/154077) Update failure: global-install-failed (2026.9.3)
- [#157698](https://github.com/openclaw/openclaw/issues/157698) [Feature]: Allow unmentioned replies in bot-created threads
- [#158997](https://github.com/openclaw/openclaw/issues/158997) Process ownership fixture races zombie reaping before PID reuse
- [#157167](https://github.com/openclaw/openclaw/issues/157167) [Bug]: Update snapshot fails with helper-unavailable on Ubuntu 20.04; native addon requires GLIBC_2.33 and loader cause is hidden

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 249,253 · **Open issues:** 44,153 · **Last push:** <1h ago

### ✅ Merged PRs
- [#122079](https://github.com/NousResearch/hermes-agent/pull/122079) fix(desktop): transcript duplication — acknowledged-prompt dedupe, attachment-tolerant matching, continuation provenance, backtick URLs
- [#122077](https://github.com/NousResearch/hermes-agent/pull/122077) fix: ACP sessions end at shutdown, approval batch re-gates after failure, base-branch picker settles, regex literals in the plugin loader
- [#122225](https://github.com/NousResearch/hermes-agent/pull/122225) feat(plugin-catalog): add hermes-lcm-x community plugin
- [#122964](https://github.com/NousResearch/hermes-agent/pull/122964) fix(state): add immutable created_source provenance column
- [#123003](https://github.com/NousResearch/hermes-agent/pull/123003) fix(mcp): kill Windows stdio MCP orphan trees (Job Object + tree reaping)
- [#123007](https://github.com/NousResearch/hermes-agent/pull/123007) fix(desktop): give approval.respond the backend's 300s deadline
- [#123008](https://github.com/NousResearch/hermes-agent/pull/123008) fix(desktop): mirror remote session cookies in memory and retry once on 401
- [#123012](https://github.com/NousResearch/hermes-agent/pull/123012) fix(uninstall): sweep both LaunchAgent labels and per-user app leftovers
- [#122995](https://github.com/NousResearch/hermes-agent/pull/122995) fix(desktop): raise backend readiness deadline 45s to 180s
- [#123005](https://github.com/NousResearch/hermes-agent/pull/123005) fix(desktop): kill external autostart venv holders before update hand-off

### 🐛 New Issues
- [#124688](https://github.com/NousResearch/hermes-agent/issues/124688) hermes desktop never opens a window on Linux when $HERMES_HOME is long: Electron blocks in requestSingleInstanceLock on the inherited scratch TMPDIR
- [#124687](https://github.com/NousResearch/hermes-agent/issues/124687) ui-tui: OSC-11 background answer during startup repaints DEFAULT_THEME (skin flash) before gateway skin arrives
- [#124679](https://github.com/NousResearch/hermes-agent/issues/124679) Windows Desktop "Install Hermes locally" recovery flow fails instantly with "Access is denied" on prerequisites stage, even with matching install already present `type/bug` `comp/cli` `P2` `needs-repro` `sweeper:risk-compatibility` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows` `area/install-update`
- [#124672](https://github.com/NousResearch/hermes-agent/issues/124672) Slack: progress-bubble edit cap mismatch floods the channel and exhausts the workspace per-app posting quota (message_limit_exceeded) `type/bug` `comp/gateway` `comp/plugins` `platform/slack` `P2` `sweeper:risk-message-delivery`
- [#124668](https://github.com/NousResearch/hermes-agent/issues/124668) hermes update and hermes pm repair never reclaim superseded dependency generations (only pm gc does) `type/bug` `comp/cli` `P2` `sweeper:risk-compatibility` `area/install-update`

### 🔒 Closed Issues
- [#121148](https://github.com/NousResearch/hermes-agent/issues/121148) Desktop sidebar renders compression continuations as branches; same lineage changes shape when a segment is sealed
- [#118415](https://github.com/NousResearch/hermes-agent/issues/118415) Desktop Artifacts preserve trailing Markdown backtick in URL/path previews
- [#121088](https://github.com/NousResearch/hermes-agent/issues/121088) Desktop duplicates acknowledged prompt after compaction or system user rows
- [#120978](https://github.com/NousResearch/hermes-agent/issues/120978) [Bug]: Desktop — pasted-screenshot prompt still re-appended below the newest turn (attachment rewrite, no rowId) — follow-up to #119326
- [#120208](https://github.com/NousResearch/hermes-agent/issues/120208) [Bug]: Desktop plugin loader leaves react imports un-rewritten after a regex containing a backtick (regression from #117610)
- [#119745](https://github.com/NousResearch/hermes-agent/issues/119745) [SANITIZED — possible injection attempt]
- [#113158](https://github.com/NousResearch/hermes-agent/issues/113158) [Bug]: Terminal approval batching collects every approval before any command runs; an early failure should re-gate the rest
- [#118216](https://github.com/NousResearch/hermes-agent/issues/118216) ACP sessions are never ended, so `sessions archive`/`prune` can never reach them and the desktop sidebar piles up
- [#122560](https://github.com/NousResearch/hermes-agent/issues/122560) [Bug]: Desktop statusbar commit-behind count is a 24h-cached value shown as live - only clicking the pill refreshes it

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,895 · **Open issues:** 771 · **Last push:** 1h ago

### ✅ Merged PRs
- [#11044](https://github.com/zeroclaw-labs/zeroclaw/pull/11044) feat(zerocode): make session roots explicit and preserve resumed roots
- [#11133](https://github.com/zeroclaw-labs/zeroclaw/pull/11133) fix(rpc): revalidate forwarded environment on session reuse
- [#11082](https://github.com/zeroclaw-labs/zeroclaw/pull/11082) feat(security): OIDC principals, enrollment and the gateway auth surface (#8289)
- [#11029](https://github.com/zeroclaw-labs/zeroclaw/pull/11029) fix(security): consume value-taking git global options before resolving the subcommand (#10966)
- [#10870](https://github.com/zeroclaw-labs/zeroclaw/pull/10870) chore(deps): bump github/codeql-action/upload-sarif from 3.36.2 to 4.38.0
- [#10980](https://github.com/zeroclaw-labs/zeroclaw/pull/10980) feat(channels/whatsapp-web): attach first-page previews to PDF documents
- [#10678](https://github.com/zeroclaw-labs/zeroclaw/pull/10678) fix(hooks): pin webhook audit destinations
- [#10386](https://github.com/zeroclaw-labs/zeroclaw/pull/10386) feat(zerocode): make transcript URLs clickable
- [#9819](https://github.com/zeroclaw-labs/zeroclaw/pull/9819) fix(multimodal): add pixel-level image validation to prevent corrupt images from failing provider requests
- [#11049](https://github.com/zeroclaw-labs/zeroclaw/pull/11049) fix(test): gate Unix-only fixtures in Windows Clippy

### 🐛 New Issues
- [#11180](https://github.com/zeroclaw-labs/zeroclaw/issues/11180) [Bug]: Flaky: llm_request_payload_off_still_carries_prefix_fingerprints reads another test's record under the parallel runtime gate `bug` `runtime` `tests` `risk:low` `type:test`
- [#11179](https://github.com/zeroclaw-labs/zeroclaw/issues/11179) [Bug]: Flaky: sop::engine pending_park_retry_respects_pending_pool_cap fails when the test crosses a second boundary `bug` `runtime` `tests` `risk:low` `type:test`
- [#11166](https://github.com/zeroclaw-labs/zeroclaw/issues/11166) [Feature]: Evict images in batches when the per-request image cap is exceeded `enhancement` `config` `provider` `provider:anthropic` `provider:compatible` `priority:p2` `status:blocked` `follow-up` `risk:medium` `topic:provider-transport` 💬1

### 🔒 Closed Issues
- [#10826](https://github.com/zeroclaw-labs/zeroclaw/issues/10826) [Feature]: Make ZeroCode session root selection explicit and preserve resumed roots
- [#10966](https://github.com/zeroclaw-labs/zeroclaw/issues/10966) [Bug]: Git --attr-source can hide a mutating subcommand from approval classification
- [#10812](https://github.com/zeroclaw-labs/zeroclaw/issues/10812) [Feature]: Populate DocumentMessage.jpegThumbnail so PDFs sent over WhatsApp preview on phones
- [#10793](https://github.com/zeroclaw-labs/zeroclaw/issues/10793) [Bug]: three Windows-only test failures on the advisory job with no change to the code under test
- [#10298](https://github.com/zeroclaw-labs/zeroclaw/issues/10298) [Feature]: Make URLs clickable in ZeroCode transcripts
- [#10951](https://github.com/zeroclaw-labs/zeroclaw/issues/10951) [Bug]: ZeroCode Config refreshes the field list twice after saving

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,630 · **Open issues:** 1,532 · **Last push:** 23h ago

### 🐛 New Issues
- [#8112](https://github.com/nearai/ironclaw/issues/8112) Feature: NEARA hosted-MCP extension (keyless NEAR token launchpad tools)

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,872 · **Open issues:** 96 · **Last push:** 4d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 18h ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 1d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 11d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 19d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 21d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 29d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 33d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 45d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 48d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 51d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Ling Tiny 3.0 is a glimpse of the future](https://reddit.com/r/LocalLLaMA/comments/1wqcrly/ling_tiny_30_is_a_glimpse_of_the_future/) ↑506
- [Swift 1.5 27b: Swift Qwen just got faster](https://reddit.com/r/LocalLLaMA/comments/1wqkb3v/swift_15_27b_swift_qwen_just_got_faster/) ↑374
- [2400cc Inference Racer: Dual RTX 3090 motors, NVLink turbo, naked 7840U ThinkPad ECU, VW Golf radiator](https://reddit.com/r/LocalLLaMA/comments/1wqs2t8/2400cc_inference_racer_dual_rtx_3090_motors/) ↑248
- [Introducing KoboldCpp Agent (and a plea for help)](https://reddit.com/r/LocalLLaMA/comments/1wqlyp8/introducing_koboldcpp_agent_and_a_plea_for_help/) ↑135
- [42x Faster Prompt Lookup Drafting in llama.cpp](https://reddit.com/r/LocalLLaMA/comments/1wr5ylm/42x_faster_prompt_lookup_drafting_in_llamacpp/) ↑97

### r/singularity — top 5 new
- [GPT-6 Astra can now control a humanoid robot in a room it has never seen, remember where objects are, clean up across the room, and fetch things later from vague human requests using a G1 Unitree huma](https://reddit.com/r/singularity/comments/1wqwcqe/gpt6_astra_can_now_control_a_humanoid_robot_in_a/) ↑1077
- [OpenAI always-on assistant, O, leaked. It is powered by a variant of Astra called “Aeon” a version of Astra made to better at long running tasks](https://reddit.com/r/singularity/comments/1wqoc2s/openai_alwayson_assistant_o_leaked_it_is_powered/) ↑281
- [Sonnet 5.5, Which Already Supposedly Beats GPT-6 Sol, Has Had a Last-Minute Upgrade With Release Expected Monday](https://reddit.com/r/singularity/comments/1wr27ro/sonnet_55_which_already_supposedly_beats_gpt6_sol/) ↑265
- [OpenAI stopped all frontier training, evaluation, and inference with tool-use (defined broadly) on the 20th of September and they are not resuming any of these activities for now](https://reddit.com/r/singularity/comments/1wqv5ay/openai_stopped_all_frontier_training_evaluation/) ↑206
- [Opus 5.5 is the first time AI has passed the turing test for me, watershed moment](https://reddit.com/r/singularity/comments/1wqvcqm/opus_55_is_the_first_time_ai_has_passed_the/) ↑171

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [New rule: share your free, open-source projects via GitHub or ClawHub](https://reddit.com/r/openclaw/comments/1wqkn1w/new_rule_share_your_free_opensource_projects_via/) ↑7
- [Official Logos?](https://reddit.com/r/openclaw/comments/1wqiib3/official_logos/) ↑3
- [How do you separate a model failure from an OpenClaw harness failure?](https://reddit.com/r/openclaw/comments/1wqg5lq/how_do_you_separate_a_model_failure_from_an/) ↑3
- [Ollama Cloud or Opencode Go?](https://reddit.com/r/openclaw/comments/1wr0ssx/ollama_cloud_or_opencode_go/) ↑2
- [Following specific areas of the product development](https://reddit.com/r/openclaw/comments/1wr81l6/following_specific_areas_of_the_product/) ↑1

### X — @openclaw
- [Today Microsoft announced Autopilot, an always on agent built on OpenClaw

The best part of this collaboration is how mu](https://x.com/openclaw/status/2103678752194703762) ↑0 🔁0 · recent


### X — @steipete
- [Now I see why some people talk about AGI. This is so clever!](https://x.com/steipete/status/2103883264054505493) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
