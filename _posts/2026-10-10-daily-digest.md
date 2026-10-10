---
layout: post
title: "Ecosystem Digest — 2026-10-10"
date: 2026-10-10 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-10
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 391,538 | 8 | 3 | 10 | 0 |
| **hermesagent** | 252,301 | 11 | 0 | 3 | 0 |
| **ZeroClaw** | 32,949 | 10 | 5 | 10 | 0 |
| **IronClaw** | 12,645 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,885 | 1 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 391,538 · **Open issues:** 9,376 · **Last push:** <1h ago

### ✅ Merged PRs
- [#168073](https://github.com/openclaw/openclaw/pull/168073) fix(control-ui): dashboard reloads flash the wrong layout
- [#168057](https://github.com/openclaw/openclaw/pull/168057) fix: honor non-streaming requests for compatible chat models
- [#168084](https://github.com/openclaw/openclaw/pull/168084) test: restore agent artifact and maintenance fixture contracts
- [#168062](https://github.com/openclaw/openclaw/pull/168062) fix(agents): deliver persistent reasoning before streamed answers
- [#167902](https://github.com/openclaw/openclaw/pull/167902) fix(llama-cpp): reclaim orphaned managed servers on macOS
- [#168025](https://github.com/openclaw/openclaw/pull/168025) fix(storage): publish sandbox, worktree, and GitHub authority receipts
- [#168071](https://github.com/openclaw/openclaw/pull/168071) feat(x): verify repository writers through GitHub profiles
- [#168067](https://github.com/openclaw/openclaw/pull/168067) fix(agentsapi): follow-up turns fail after native tool use
- [#168079](https://github.com/openclaw/openclaw/pull/168079) test(update): run the surviving process-group repair case only on POSIX
- [#167986](https://github.com/openclaw/openclaw/pull/167986) fix: background utility completions are missing from token and cost metrics

### 🐛 New Issues
- [#168092](https://github.com/openclaw/openclaw/issues/168092) [Bug]: macOS 2026.9.8 → 2026.9.9 update blocked by anchor-retired journal identity mismatch 💬1
- [#168089](https://github.com/openclaw/openclaw/issues/168089) [Bug]: Windows model directive tests remove session directories before database teardown `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬2
- [#168088](https://github.com/openclaw/openclaw/issues/168088) Default ChatGPT-login compaction to Codex-style remote compaction V2, built as the next normal turn `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `impact:session-state` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#168082](https://github.com/openclaw/openclaw/issues/168082) [Bug]: ask_user 900s timeout settlement writes the no_answer tool result with a stale expectedMutationAt fence and fails the run with SqliteTranscriptMutationConflictError `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:session-state` `issue-rating: 🦐 gold shrimp` 💬1
- [#168081](https://github.com/openclaw/openclaw/issues/168081) [Bug]: Mattermost agents are told to send typed callback buttons, which Mattermost sends as plain text `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬2
- [#168072](https://github.com/openclaw/openclaw/issues/168072) [Bug]: Startup cron host admission holds the state writer for 107s and blocks update receipts `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` `clawsweeper:bulk-filed` 💬2
- [#168070](https://github.com/openclaw/openclaw/issues/168070) Agent work keeps missing fundamentals (request parity, silent fallbacks, discarded paid work); add them to AGENTS.md `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#168066](https://github.com/openclaw/openclaw/issues/168066) Doctor run as another user deletes enabled flag of blocked path plugins (plugin silently stops loading after next restart) `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:data-loss` `issue-rating: 🦞 diamond lobster` `maturity:stable` 💬3

### 🔒 Closed Issues
- [#155769](https://github.com/openclaw/openclaw/issues/155769) Gateway restart orphans managed localService children; memory sync refused while status misreports
- [#164932](https://github.com/openclaw/openclaw/issues/164932) [Feature]: Reuse a same-process integrity proof for the shared state database during Gateway startup
- [#167913](https://github.com/openclaw/openclaw/issues/167913) [Bug]: runIsolatedCompletion emits no model.usage, so background utility completions (session titles, Activity recaps, session observer, progress narration, transcript summaries) are missing from open

### 🔥 Hot Issues (most commented)
- [#143524](https://github.com/openclaw/openclaw/issues/143524) [Bug]: Agent SQLite WAL grows to 1.4–2.8 GB in days despite wal_autocheckpoint=1000; blocks gateway startup (Windows, 2026.9.2/9.3) — 💬115 · 3h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 252,301 · **Open issues:** 48,121 · **Last push:** <1h ago

### ✅ Merged PRs
- [#135406](https://github.com/NousResearch/hermes-agent/pull/135406) Test runs no longer leave detached gateways running after they finish
- [#135834](https://github.com/NousResearch/hermes-agent/pull/135834) fix(skills-index): stop shipping ~1.9k skills.sh rows that cannot install
- [#135826](https://github.com/NousResearch/hermes-agent/pull/135826) fix(skills): community skills' inline shell no longer runs when nested, viewed via external_dirs, or under an unreadable hub lock

### 🐛 New Issues
- [#135921](https://github.com/NousResearch/hermes-agent/issues/135921) [Bug]: Weixin/iLink silently discards outbound messages when the peer reply window expires (no retry, no queue, no error surfaced) `type/bug` `comp/gateway` `platform/wecom` `P2` `sweeper:risk-message-delivery`
- [#135920](https://github.com/NousResearch/hermes-agent/issues/135920) [Feature]: Explicit remote-only Desktop mode: prevent unintended local backend activation `type/feature` `area/config` `P3` `comp/desktop`
- [#135916](https://github.com/NousResearch/hermes-agent/issues/135916) [Feature]: Change auxiliary models at runtime like /model does for the main model in TUI `type/feature` `comp/cli` `comp/tui` `P3`
- [#135910](https://github.com/NousResearch/hermes-agent/issues/135910) pm repair cannot commit a dependency environment on a case-insensitive filesystem: shutil.copytree dies with Errno 17 on the bundled CPython terminfo `type/bug` `comp/cli` `P2` `sweeper:risk-compatibility` `area/install-update`
- [#135905](https://github.com/NousResearch/hermes-agent/issues/135905) Approval buttons resolve the oldest pending approval, not the one clicked (Slack, Discord, other adapters) `type/bug` `duplicate` `comp/gateway` `comp/plugins` `platform/telegram` `platform/discord` `platform/slack` `platform/matrix` `platform/whatsapp` `platform/feishu` `platform/qqbot` `P2` `sweeper:risk-message-delivery`
- [#135904](https://github.com/NousResearch/hermes-agent/issues/135904) browser: use_real_profile path never applies the auto --no-sandbox workaround (AppArmor userns hosts) `type/bug` `tool/browser` `P2`
- [#135903](https://github.com/NousResearch/hermes-agent/issues/135903) feat(plugins): give dashboard plugin_api.py a supported ctx.llm facade `duplicate` `type/feature` `comp/plugins` `P3` `comp/dashboard`
- [#135900](https://github.com/NousResearch/hermes-agent/issues/135900) feat(memory): support lock-scoped precondition for MemoryStore.apply_batch `type/feature` `comp/agent` `comp/plugins` `tool/memory` `P3` `area/memory`
- [#135899](https://github.com/NousResearch/hermes-agent/issues/135899) Docker backend: skill_view returns host skill_dir / ${HERMES_SKILL_DIR}, so bundled skill scripts fail inside the sandbox `type/bug` `comp/agent` `tool/skills` `backend/docker` `P2`
- [#135898](https://github.com/NousResearch/hermes-agent/issues/135898) Matrix: captioned file is cached under the caption text, losing filename/extension (ignores content.filename) `type/bug` `comp/plugins` `platform/matrix` `P3` `sweeper:risk-message-delivery`
- [#135897](https://github.com/NousResearch/hermes-agent/issues/135897) [Feature]: Desktop Plugins page — copyable plugin source (repo + pinned commit) and a way to mirror a remote backend's plugin set onto a new device `type/feature` `comp/plugins` `P3` `comp/desktop`

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,949 · **Open issues:** 946 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11454](https://github.com/zeroclaw-labs/zeroclaw/pull/11454) fix(runtime): correlate conversation keys with turn traces
- [#11494](https://github.com/zeroclaw-labs/zeroclaw/pull/11494) refactor(zerocode): isolate client message queue ownership
- [#11582](https://github.com/zeroclaw-labs/zeroclaw/pull/11582) perf(multimodal): evict images in batches past the per-request cap
- [#11600](https://github.com/zeroclaw-labs/zeroclaw/pull/11600) refactor(runtime): remove obsolete stream error wrapper
- [#11543](https://github.com/zeroclaw-labs/zeroclaw/pull/11543) fix(tools): detach shell children from the controlling terminal
- [#11512](https://github.com/zeroclaw-labs/zeroclaw/pull/11512) fix(skills): bound HTTP calls with one deadline
- [#11603](https://github.com/zeroclaw-labs/zeroclaw/pull/11603) docs(runtime): propose a bounded exception for subagent model routes
- [#11479](https://github.com/zeroclaw-labs/zeroclaw/pull/11479) fix(runtime): recover structured native tool arguments
- [#11576](https://github.com/zeroclaw-labs/zeroclaw/pull/11576) fix(rpc): sign TUI identities with the install key next to config.toml
- [#11436](https://github.com/zeroclaw-labs/zeroclaw/pull/11436) docs(runtime): batch bounded holding-crate exceptions

### 🐛 New Issues
- [#11638](https://github.com/zeroclaw-labs/zeroclaw/issues/11638) [Tracker]: Restore stable community entry points `docs` `type:tracker`
- [#11632](https://github.com/zeroclaw-labs/zeroclaw/issues/11632) [Bug]: Desktop (Linux/Tauri): WebKitWebProcess repaints continuously (~100% GPU render engine) even when idle `bug` `priority:p2` `desktop` `risk:medium` `web` 💬1
- [#11623](https://github.com/zeroclaw-labs/zeroclaw/issues/11623) [Bug]: ZeroCode drops a pending ask_user prompt without replying, so the tool times out after 600 s and the question leaves no record `bug` `priority:p2` `risk:medium` `zerocode` 💬1
- [#11620](https://github.com/zeroclaw-labs/zeroclaw/issues/11620) [Feature]: Show message times in the ZeroCode transcript `enhancement` `runtime` `priority:p3` `risk:medium` `zerocode` 💬1
- [#11618](https://github.com/zeroclaw-labs/zeroclaw/issues/11618) [Bug]: ZeroCode drops a queued message when the daemon refuses it as SESSION_BUSY `bug` `priority:p1` `risk:medium` `zerocode` 💬1
- [#11615](https://github.com/zeroclaw-labs/zeroclaw/issues/11615) [Bug]: Telegram send path ignores 429 retry_after — immediate retries compound flood-limiting and the reply can be lost entirely `bug` `channel` `channel:telegram` `priority:p1` `risk:medium` 💬1
- [#11614](https://github.com/zeroclaw-labs/zeroclaw/issues/11614) [Bug]: map_key_sections leaks schema paths on every call, growing daemon memory `bug` `config` `priority:p1` `risk:medium` 💬1
- [#11613](https://github.com/zeroclaw-labs/zeroclaw/issues/11613) Cost ledger drops the provider's `total_tokens`, so models with hidden reasoning tokens (e.g. Gemini via an OpenAI-compatible provider) are under-counted `bug` `observability` `provider` `runtime` `provider:compatible` `priority:p2` `status:accepted` `risk:medium` 💬3
- [#11612](https://github.com/zeroclaw-labs/zeroclaw/issues/11612) [Bug]: Re-running an already-approved shell command in the same turn aborts the agent loop ("repeated prompt-required tool call 'shell' with identical arguments before approval") and ends the ACP sess `bug` `agent` `runtime` `priority:p1` `tool:shell` `risk:medium` `channel:acp` `topic:agent-loop` 💬2
- [#11608](https://github.com/zeroclaw-labs/zeroclaw/issues/11608) [Bug]: Telegram listener can wedge forever on a blackholed request — listener_health detects staleness but nothing recovers the channel `bug` `channel` `channel:telegram` `priority:p1` `risk:medium` 💬1

### 🔒 Closed Issues
- [#10700](https://github.com/zeroclaw-labs/zeroclaw/issues/10700) [Bug]: cost records carry a daemon-lifetime session id, so per-conversation spend cannot be separated
- [#11166](https://github.com/zeroclaw-labs/zeroclaw/issues/11166) [Feature]: Evict images in batches when the per-request image cap is exceeded
- [#11545](https://github.com/zeroclaw-labs/zeroclaw/issues/11545) [Task]: remove obsolete StreamErrorWithUsage after image recovery lands
- [#10550](https://github.com/zeroclaw-labs/zeroclaw/issues/10550) [Feature]: bound skill HTTP DNS resolution and test the full dispatch seam
- [#11371](https://github.com/zeroclaw-labs/zeroclaw/issues/11371) [Bug]: MCP nested object argument is serialized as string before tool execution

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,645 · **Open issues:** 1,547 · **Last push:** 2d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,885 · **Open issues:** 107 · **Last push:** 17d ago

### 🐛 New Issues
- [#1296](https://github.com/moltis-org/moltis/issues/1296) Test an A2Agent profile through Moltis provider setup

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬1 · 1d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 4d ago
- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 6d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 12d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 14d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 24d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 32d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 34d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 42d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 46d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Research] Investigating Unintended Model Actions](https://www.anthropic.com/research/investigating-unintended-model-actions) _2026-10-09_

### OpenAI — 3 new
- [[Index] Asana Browser Agent](https://openai.com/index/asana-browser-agent/) _2026-10-10_
- [[Partners] Affinda](https://openai.com/business/partners/affinda/) _2026-10-09_
- [[Index] Sophos](https://openai.com/index/sophos/) _2026-10-09_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Qwen/Qwen-Image-2.1-Turbo · Hugging Face](https://reddit.com/r/LocalLLaMA/comments/1x1ldef/qwenqwenimage21turbo_hugging_face/) ↑416
- [OpenAI's math findings built on stolen user data](https://reddit.com/r/LocalLLaMA/comments/1x1rk4o/openais_math_findings_built_on_stolen_user_data/) ↑320
- [Ahh, it all makes sense now for the 64Gb DGX Spark - [Samsung expects 780% quarterly operating profit jump on AI boom]](https://reddit.com/r/LocalLLaMA/comments/1x1fnsy/ahh_it_all_makes_sense_now_for_the_64gb_dgx_spark/) ↑283
- [Qwen-Image-2.1-Turbo released!](https://reddit.com/r/LocalLLaMA/comments/1x1lclx/qwenimage21turbo_released/) ↑241
- [GLM 5.3 Flash opensource @ the top of Artificial Analysis Cyber Index over Claude.](https://reddit.com/r/LocalLLaMA/comments/1x1rwof/glm_53_flash_opensource_the_top_of_artificial/) ↑159

### r/singularity — top 5 new
- [Hugo Duminil-Copin (2022 Fields Medalist): OpenAI's solving of 350 major problems feels as if I had been run over by trucks; all the problems (and thus research directions) that I used to mention in m](https://reddit.com/r/singularity/comments/1x1mzkn/hugo_duminilcopin_2022_fields_medalist_openais/) ↑641
- [Top executives at Anthropic, OpenAI and other AI companies are privately gaming out scenarios for a public and political revolt after a catastrophic AI event.](https://reddit.com/r/singularity/comments/1x1igx2/top_executives_at_anthropic_openai_and_other_ai/) ↑354
- [AI Could Allow For 3-Day Workweeks And Single-Income Households, Bezos Claims](https://reddit.com/r/singularity/comments/1x1vo9t/ai_could_allow_for_3day_workweeks_and/) ↑276
- [Introducing Microsoft-Decision-1, our model for fast decision-making](https://reddit.com/r/singularity/comments/1x1z0um/introducing_microsoftdecision1_our_model_for_fast/) ↑242
- [Seattle Becomes First City to Stop Grocery Stores from Using AI Based Personal Data to Set Prices - Office of the Mayor](https://reddit.com/r/singularity/comments/1x1kpmv/seattle_becomes_first_city_to_stop_grocery_stores/) ↑226

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [realtime Talk is unbelievably good](https://reddit.com/r/openclaw/comments/1x0q3jx/realtime_talk_is_unbelievably_good/) ↑33
- [Qwen Token Plan vs. MiMo Token Plan for OpenClaw](https://reddit.com/r/openclaw/comments/1x14vzq/qwen_token_plan_vs_mimo_token_plan_for_openclaw/) ↑3
- [Openclaw on Mac Mini M4 24 GB Ram](https://reddit.com/r/openclaw/comments/1x1ffx6/openclaw_on_mac_mini_m4_24_gb_ram/) ↑2
- [Best VPS hosting and providers for a growing project?](https://reddit.com/r/openclaw/comments/1wznric/best_vps_hosting_and_providers_for_a_growing/) ↑2
- [Token usage lower](https://reddit.com/r/openclaw/comments/1x0kzof/token_usage_lower/) ↑2

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [Just keep putting one claw in front of the other](https://x.com/openclaw/status/2108377842648330315)

### X — @steipete
_No new tweets since the last digest. Most recent:_
- [WE GOT IT! .claw incoming!](https://x.com/steipete/status/2108374513931165759)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
