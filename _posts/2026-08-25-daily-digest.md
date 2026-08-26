---
layout: post
title: "Ecosystem Digest — 2026-08-25"
date: 2026-08-25 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-08-25
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 387,438 | 14 | 2 | 10 | 1 |
| **hermesagent** | 235,852 | 3 | 3 | 6 | 0 |
| **ZeroClaw** | 32,646 | 15 | 7 | 10 | 0 |
| **IronClaw** | 12,604 | 12 | 7 | 10 | 0 |
| **Moltis** | 2,836 | 0 | 2 | 3 | 1 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 387,438 · **Open issues:** 5,919 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.8.1-beta.3](https://github.com/openclaw/openclaw/releases/tag/v2026.8.1-beta.3) — OpenClaw 2026.8.1-beta.3

### ✅ Merged PRs
- [#128896](https://github.com/openclaw/openclaw/pull/128896) fix: Telegram private topics resume after gateway restart
- [#128911](https://github.com/openclaw/openclaw/pull/128911) fix(ui): center completed progress marker
- [#128902](https://github.com/openclaw/openclaw/pull/128902) fix(media): preserve correct filenames for transparent image attachments
- [#126811](https://github.com/openclaw/openclaw/pull/126811) fix(macos): return paired-node Codex catalogs without native supervision
- [#128864](https://github.com/openclaw/openclaw/pull/128864) fix(gateway): surface cloud workspace recovery failures
- [#128874](https://github.com/openclaw/openclaw/pull/128874) test(ui): scope Claude session selection to sidebar links
- [#128873](https://github.com/openclaw/openclaw/pull/128873) fix(agents): keep Unicode filename reads inside workspace
- [#128958](https://github.com/openclaw/openclaw/pull/128958) fix(ui): explain why updates are unavailable
- [#128957](https://github.com/openclaw/openclaw/pull/128957) fix(crabbox): dispose heartbeat generations
- [#128937](https://github.com/openclaw/openclaw/pull/128937) fix: restore GitHub tools in managed Codex sessions

### 🐛 New Issues
- [#128967](https://github.com/openclaw/openclaw/issues/128967) Session layer silently front-truncates large tool results to 64KiB; surviving truncation marker accounts only for tail loss 💬1
- [#128963](https://github.com/openclaw/openclaw/issues/128963) [Bug]: Mid-turn overflow skips auto-compaction after settled replay-unsafe tools `bug` `maintainer` 💬1
- [#128962](https://github.com/openclaw/openclaw/issues/128962) Subagent result discarded and parent session hangs forever when an announce run compacts (`Cannot continue from message role: assistant`) `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬2
- [#128960](https://github.com/openclaw/openclaw/issues/128960) [Bug]: Slash command popup menu fails to show when typing "/" in a new session (Windows) `bug` `bug:behavior` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬2
- [#128956](https://github.com/openclaw/openclaw/issues/128956) Inbound attachment prompt note never includes the file name — `MediaFact.fileName` exists but is not rendered, and the Mattermost plugin never sets it `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#128938](https://github.com/openclaw/openclaw/issues/128938) [Bug]: Memory sync retries terminal OpenAI embeddings 429 (insufficient_quota) on every sync, starving the sync queue `bug` `maintainer` `P1` `clawsweeper:source-repro` `impact:session-state` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#128935](https://github.com/openclaw/openclaw/issues/128935) [Bug]: Telegram react tool schema never teaches models the custom_emoji_id syntax or unicode restrictions until reactions fail `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` `clawsweeper:bulk-filed` 💬1
- [#128934](https://github.com/openclaw/openclaw/issues/128934) [Bug]: Skills curator pin/unpin/restore replay gateway-answered failures against local state after a 1.5s timeout `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `maturity:stable` `clawsweeper:bulk-filed` 💬1
- [#128933](https://github.com/openclaw/openclaw/issues/128933) [Bug]: AskUserQuestion bounded-text caps exceed the upstream SDK schema and deny entire question sets on overflow `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `clawsweeper:bulk-filed` 💬1
- [#128932](https://github.com/openclaw/openclaw/issues/128932) [Bug]: Anthropic AskUserQuestion answers collapse when two questions share identical text `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `clawsweeper:bulk-filed` 💬1
- [#128931](https://github.com/openclaw/openclaw/issues/128931) [Bug]: Forward clock jumps expire all playback-transcode failure cooldowns simultaneously, causing synchronized ffmpeg retry bursts `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `clawsweeper:bulk-filed` 💬1
- [#128929](https://github.com/openclaw/openclaw/issues/128929) [Bug]: Reported ExecStart prefers stale systemd manager state until daemon-reload, and shared D-Bus deadline starves property reads `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:ux-friction` `clawsweeper:bulk-filed` 💬1
- [#128928](https://github.com/openclaw/openclaw/issues/128928) [Bug]: systemd service audit flags deliberately masked units with false repair recommendations `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` `clawsweeper:bulk-filed` 💬1
- [#128926](https://github.com/openclaw/openclaw/issues/128926) [Bug]: Android never listens for config.changed so gateway accent changes require reconnect to appear `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` `clawsweeper:bulk-filed` 💬1

### 🔒 Closed Issues
- [#128866](https://github.com/openclaw/openclaw/issues/128866) [Bug]: Telegram private-topic restart recovery rejects scoped/raw thread IDs and strands session
- [#128961](https://github.com/openclaw/openclaw/issues/128961) Compaction-count reconcile always throws `reconcile is not a function`: `export *` shim drops the default export

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 235,852 · **Open issues:** 35,483 · **Last push:** <1h ago

### ✅ Merged PRs
- [#94351](https://github.com/NousResearch/hermes-agent/pull/94351) Follow-ups to #93757: boundary test, skip warning, doc sync for secure_parent_dir install-tree exclusion
- [#94346](https://github.com/NousResearch/hermes-agent/pull/94346) fmt(js): `npm run fix` auto-fix
- [#94228](https://github.com/NousResearch/hermes-agent/pull/94228) feat(desktop): vibe hearts get an off switch in Appearance (salvage #84273)
- [#94333](https://github.com/NousResearch/hermes-agent/pull/94333) fix(desktop): HUD frost follows the scrim, and enumeration says why it failed
- [#94187](https://github.com/NousResearch/hermes-agent/pull/94187) fix(terminal): sweep setsid descendants after local timeout group-kill (#85125 4b)
- [#94184](https://github.com/NousResearch/hermes-agent/pull/94184) fix(mcp): recover poisoned connections + fail fast on dead stdio transports (#85125 3b)

### 🐛 New Issues
- [#94353](https://github.com/NousResearch/hermes-agent/issues/94353) Skill approval deadlock: scanner-refused writes cannot be human-approved
- [#94345](https://github.com/NousResearch/hermes-agent/issues/94345) [Bug]: broken line wrapping in 'hermes help' 80 column hardwrap is just wrong `type/bug` `comp/cli` `P3`
- [#94335](https://github.com/NousResearch/hermes-agent/issues/94335) [Bug] _stdio_children_dead() inverted liveness check fail-fasts every stdio MCP call in oneshot (-z) sessions `type/bug` `comp/agent` `tool/mcp` `P2`

### 🔒 Closed Issues
- [#84272](https://github.com/NousResearch/hermes-agent/issues/84272) [Feature]: Desktop vibe hearts should be toggleable (Message Reactions setting does not cover them)
- [#94323](https://github.com/NousResearch/hermes-agent/issues/94323) __perm_probe__
- [#92701](https://github.com/NousResearch/hermes-agent/issues/92701) docker backend: exit 125 "too many colons" — persistent sandbox path built from unsanitized task_id

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,646 · **Open issues:** 790 · **Last push:** 4h ago

### ✅ Merged PRs
- [#10208](https://github.com/zeroclaw-labs/zeroclaw/pull/10208) fix(tests): fix Windows platform test failures
- [#9563](https://github.com/zeroclaw-labs/zeroclaw/pull/9563) fix(channels): populate the typed media envelope from Telegram
- [#10027](https://github.com/zeroclaw-labs/zeroclaw/pull/10027) fix(providers): report the served model in reliable fallback failure logs
- [#10144](https://github.com/zeroclaw-labs/zeroclaw/pull/10144) fix(providers): complete lifecycle provider accounting
- [#10284](https://github.com/zeroclaw-labs/zeroclaw/pull/10284) chore(ci): remove dead labeler paths and correct moved-file labels
- [#9941](https://github.com/zeroclaw-labs/zeroclaw/pull/9941) fix(cron): default cron delivery to the originating channel alias
- [#9426](https://github.com/zeroclaw-labs/zeroclaw/pull/9426) docs(sop): add conditional routing example
- [#10254](https://github.com/zeroclaw-labs/zeroclaw/pull/10254) test(telegram): make the listen hang guards guards again
- [#10242](https://github.com/zeroclaw-labs/zeroclaw/pull/10242) fix(providers): simplify structured upstream errors
- [#10219](https://github.com/zeroclaw-labs/zeroclaw/pull/10219) fix(doctor): serialize model-cache refreshes with a cross-process lock

### 🐛 New Issues
- [#10334](https://github.com/zeroclaw-labs/zeroclaw/issues/10334) [Bug]: git_operations ignores allowed_roots for ordinary repository paths
- [#10333](https://github.com/zeroclaw-labs/zeroclaw/issues/10333) test
- [#10332](https://github.com/zeroclaw-labs/zeroclaw/issues/10332) [Task]: skip_missed_run next-run assertion flakes at minute boundary under Parallel Runtime Test gate `bug` `cron` `runtime` `tests` `domain:ci` `release-gate` `priority:p2` `status:accepted` `risk:low` `type:test`
- [#10331](https://github.com/zeroclaw-labs/zeroclaw/issues/10331) bug(runtime): recover terminal settlement intents abandoned by a dead worker `bug` `daemon` `runtime` `tool:delegate` `priority:p1` `needs-maintainer-review` `follow-up` `risk:high`
- [#10330](https://github.com/zeroclaw-labs/zeroclaw/issues/10330) [Tracker]: Accepted RFC implementation routing gaps `enhancement` `domain:architecture` `priority:p2` `status:no-stale` `risk:low` `type:tracker`
- [#10329](https://github.com/zeroclaw-labs/zeroclaw/issues/10329) [Bug]: Resilient wrapper truncation shadows loop-level context overflow recovery for OpenAI-compatible providers
- [#10327](https://github.com/zeroclaw-labs/zeroclaw/issues/10327) [Bug]: Discord URL fallback reports a false partial image-load failure `bug` `channel` `provider` `channel:discord` `priority:p3` `risk:medium`
- [#10326](https://github.com/zeroclaw-labs/zeroclaw/issues/10326) [Bug]: Reliable streaming errors report the requested model instead of the served pinned model `bug` `provider` `provider:reliable` `priority:p3` `risk:medium`
- [#10324](https://github.com/zeroclaw-labs/zeroclaw/issues/10324) [Bug]: cron manual trigger and run-history reads remain check-then-act across an agent rename `bug` `cron` `runtime` `security` `domain:security` `priority:p1` `tool:cron` `risk:high` 💬1
- [#10320](https://github.com/zeroclaw-labs/zeroclaw/issues/10320) [Bug]: config set and RPC config/set persist values without running validation `bug` `config` `runtime` `priority:p2` `risk:high` `cli`
- [#10318](https://github.com/zeroclaw-labs/zeroclaw/issues/10318) [Task]: serialize concurrent SOP authoring writes (create/save/delete/rename) `bug` `gateway` `runtime` `priority:p2` `tool:sop` `risk:high` `cli`
- [#10316](https://github.com/zeroclaw-labs/zeroclaw/issues/10316) SOP: step-budget exhaustion can overwrite an accepted cancellation as Failed `bug` `runtime` `tool:sop` `priority:p3` `risk:high`
- [#10315](https://github.com/zeroclaw-labs/zeroclaw/issues/10315) Re-add the browser enrollment frontdoor after #10142 — without hand-rolled TLS `enhancement` `gateway` `security` `domain:security` `priority:p2` `status:blocked` `web` `risk:high`
- [#10306](https://github.com/zeroclaw-labs/zeroclaw/issues/10306) [Task]: gate web/ TypeScript in required CI, and stop bare tsc from printing 75 misleading errors `enhancement` `ci` `domain:ci` `release-gate` `priority:p2` `status:accepted` `web` `risk:high` `type:ci` 💬1
- [#10305](https://github.com/zeroclaw-labs/zeroclaw/issues/10305) [Task]: generate the SOP syntax reference from source instead of hand-maintaining it `docs` `tool:sop` `priority:p3` `risk:low` `type:docs`

### 🔒 Closed Issues
- [#10023](https://github.com/zeroclaw-labs/zeroclaw/issues/10023) Failure logs claim the requested model, not the pinned fallback model
- [#10143](https://github.com/zeroclaw-labs/zeroclaw/issues/10143) [Task]: Make provider-call accounting lifecycle-complete
- [#10251](https://github.com/zeroclaw-labs/zeroclaw/issues/10251) Repeat parallel runtime tests: 17 telegram listen_* tests assert on wall-clock timeouts (same class as #9429)
- [#9590](https://github.com/zeroclaw-labs/zeroclaw/issues/9590) [Bug]: Concurrent models refresh runs can lose cache entries
- [#10224](https://github.com/zeroclaw-labs/zeroclaw/issues/10224) [Bug]: Custom provider 5xx errors are logged as duplicated escaped JSON
- [#10106](https://github.com/zeroclaw-labs/zeroclaw/issues/10106) [Bug]: Exact proxy selectors reject supported transcription services
- [#10190](https://github.com/zeroclaw-labs/zeroclaw/issues/10190) [Bug]: Reasoning fallback classifier matches unrelated compound error clauses

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,604 · **Open issues:** 1,533 · **Last push:** 1h ago

### ✅ Merged PRs
- [#7257](https://github.com/nearai/ironclaw/pull/7257) docs(design-system): proposal, plan & checklist for the WebUI design system (Epic #7038)
- [#7255](https://github.com/nearai/ironclaw/pull/7255) docs(governance): evaluate the APDD kit + propose scoped integration
- [#7821](https://github.com/nearai/ironclaw/pull/7821) ci: single setup-rust composite — toolchain pin, mold, centralized build profiles (T1)
- [#7857](https://github.com/nearai/ironclaw/pull/7857) fix(webui): refresh conversations after starting suggestion
- [#7854](https://github.com/nearai/ironclaw/pull/7854) fix(webui): remove Gateway v2 login eyebrow
- [#7833](https://github.com/nearai/ironclaw/pull/7833) feat(suggestions): generate over the user's no-approval, read-only tools (#7812)
- [#7794](https://github.com/nearai/ironclaw/pull/7794) refactor(webui): introduce shared page shell and loading primitives
- [#7001](https://github.com/nearai/ironclaw/pull/7001) feat(loop): keep the cached system prefix byte-stable across model calls
- [#7795](https://github.com/nearai/ironclaw/pull/7795) refactor(webui): migrate settings and admin notices
- [#7844](https://github.com/nearai/ironclaw/pull/7844) fix(ci): restore main coverage and WebUI checks

### 🐛 New Issues
- [#7862](https://github.com/nearai/ironclaw/issues/7862) Device link fails with generic "Something went wrong while linking" when telegram_api_id/api_hash are unconfigured 💬1
- [#7860](https://github.com/nearai/ironclaw/issues/7860) Decompose ironclaw_extension_manager::lifecycle_product_service (1,774 lines)
- [#7856](https://github.com/nearai/ironclaw/issues/7856) MCP tool discovery silently skips camelCase tool names
- [#7855](https://github.com/nearai/ironclaw/issues/7855) Add Italian language support for IronClaw
- [#7853](https://github.com/nearai/ironclaw/issues/7853) Telegram setup offers personal account linking but cannot complete it (missing tool) 💬2
- [#7849](https://github.com/nearai/ironclaw/issues/7849) feat(extensions): bundle an agent-first GSuite CLI for Google Workspace `enhancement` `risk: high` `scope: tool` `scope: extensions` `suggested_P1` `scope: skills` `v1.4.0`
- [#7848](https://github.com/nearai/ironclaw/issues/7848) Daily ironclaw failure taxonomy — 2026-08-24
- [#7843](https://github.com/nearai/ironclaw/issues/7843) Epic: Dogfooding & QA bug fixing 08/24/2026 - 08/30/2026 `epic`
- [#7825](https://github.com/nearai/ironclaw/issues/7825) Sandbox egress auth: native iron-proxy recipes with host credential broker (retire GitHub-specific carve-out) 💬1
- [#7815](https://github.com/nearai/ironclaw/issues/7815) Onboarding suggestions: cumulative net-new work to close the connect → suggest → thread flow `module:M1-webui-product` `scope: webui` `epic` `ux` 💬1
- [#7297](https://github.com/nearai/ironclaw/issues/7297) Error messages stack up in UI after every failed prompt `bug_bash_P2` `qa-bug` 💬2
- [#6774](https://github.com/nearai/ironclaw/issues/6774) Document Gmail terminal-based setup steps in Extensions > Registry UI `documentation` `enhancement` `gmail` `extensions` `webui` 💬1

### 🔒 Closed Issues
- [#7798](https://github.com/nearai/ironclaw/issues/7798) CI expedite T1: setup-rust composite — toolchain pin, mold, centralized build profiles
- [#7845](https://github.com/nearai/ironclaw/issues/7845) Activating a suggested task fails to create/render its thread entry in the left panel
- [#7812](https://github.com/nearai/ironclaw/issues/7812) Onboarding suggestions: respect user-level tool permissions, generate with read-only tool access
- [#7792](https://github.com/nearai/ironclaw/issues/7792) Introduce shared page-shell and loading primitives
- [#6985](https://github.com/nearai/ironclaw/issues/6985) Cache: stop mutating the prompt prefix (nudges before identity, timestamp in system block, per-run memory retrieval)
- [#7851](https://github.com/nearai/ironclaw/issues/7851) Fix main branch CI failures 20260824
- [#7793](https://github.com/nearai/ironclaw/issues/7793) Migrate remaining Settings and Admin feedback banners to InlineNotice

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,836 · **Open issues:** 87 · **Last push:** 7h ago

### 🚀 New Releases
- [20260824.01](https://github.com/moltis-org/moltis/releases/tag/20260824.01) — 20260824.01

### ✅ Merged PRs
- [#1237](https://github.com/moltis-org/moltis/pull/1237) Bound Apple container identifiers to 64 characters
- [#1238](https://github.com/moltis-org/moltis/pull/1238) Allow configured tools in shared Slack channels
- [#1233](https://github.com/moltis-org/moltis/pull/1233) fix(whatsapp): bound inbound media downloads while streaming

### 🔒 Closed Issues
- [#1137](https://github.com/moltis-org/moltis/issues/1137) [Bug]: Apple Container ID exceeds name limit
- [#1239](https://github.com/moltis-org/moltis/issues/1239) feat(providers): add xAI Grok subscription OAuth (SuperGrok / Heavy)

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 22h ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 3d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬2 · 3d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 12d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 15d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 18d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 20d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 22d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 24d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 24d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Team] Economics](https://www.anthropic.com/research/team/economics) _2026-08-24_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Xiaomi AI Cube announced with 1.2TB/s memory bandwidth](https://reddit.com/r/LocalLLaMA/comments/1vwvghi/xiaomi_ai_cube_announced_with_12tbs_memory/) ↑1584
- [Apple M5 Server](https://reddit.com/r/LocalLLaMA/comments/1vx6ivx/apple_m5_server/) ↑843
- [I irradiated LLMs and found that they die really quickly](https://reddit.com/r/LocalLLaMA/comments/1vx2fhz/i_irradiated_llms_and_found_that_they_die_really/) ↑475
- [Qwen 3.8 27B in 9th position on code arena. Gemma 4 31B is 80th.](https://reddit.com/r/LocalLLaMA/comments/1vx7pdh/qwen_38_27b_in_9th_position_on_code_arena_gemma_4/) ↑445
- [[Paper] ToMoE: Converting Dense Large Language Models to Mixture-of-Experts through Dynamic Structural Pruning](https://reddit.com/r/LocalLLaMA/comments/1vx3img/paper_tomoe_converting_dense_large_language/) ↑212

### r/singularity — top 2 new
- [100m Hurdles Final](https://reddit.com/r/singularity/comments/1vx7hk4/100m_hurdles_final/) ↑2134
- [WHRG'26 wrong turns](https://reddit.com/r/singularity/comments/1vxfgi4/whrg26_wrong_turns/) ↑186

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Still using OpenClaw](https://reddit.com/r/openclaw/comments/1vxccto/still_using_openclaw/) ↑14
- [Any way to talk to OpenClaw in the car?](https://reddit.com/r/openclaw/comments/1vwzpst/any_way_to_talk_to_openclaw_in_the_car/) ↑6
- [Active OC Users: How do you use cronjobs?](https://reddit.com/r/openclaw/comments/1vx9qf7/active_oc_users_how_do_you_use_cronjobs/) ↑5
- [When to use Cron vs new agent?](https://reddit.com/r/openclaw/comments/1vwsj25/when_to_use_cron_vs_new_agent/) ↑2
- [Stop OpenClaw from Creating Multiple Local Model LLM Instances](https://reddit.com/r/openclaw/comments/1vwr31d/stop_openclaw_from_creating_multiple_local_model/) ↑1

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
- [I added the rotation USB protocol to 
https://
github.com/steipete/camsn
ap
… and told my claw to look around- now it's ](https://x.com/steipete/status/2091639468935831910) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
