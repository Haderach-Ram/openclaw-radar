---
layout: post
title: "Ecosystem Digest — 2026-11-16"
date: 2026-11-16 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-16
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 394,533 | 11 | 2 | 10 | 0 |
| **hermesagent** | 263,653 | 7 | 6 | 1 | 1 |
| **ZeroClaw** | 33,378 | 5 | 0 | 1 | 0 |
| **IronClaw** | 12,716 | 3 | 0 | 0 | 0 |
| **Moltis** | 2,962 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 394,533 · **Open issues:** 8,506 · **Last push:** <1h ago

### ✅ Merged PRs
- [#198302](https://github.com/openclaw/openclaw/pull/198302) fix(plugins): keep Gateway responsive during initial plugin loading
- [#199626](https://github.com/openclaw/openclaw/pull/199626) fix(memory-wiki): keep imported Markdown links pointing to generated pages
- [#199639](https://github.com/openclaw/openclaw/pull/199639) fix(cli): show actionable inference preflight errors with JSON
- [#199642](https://github.com/openclaw/openclaw/pull/199642) fix(cli): preserve Gmail setup remedies in JSON failures
- [#199650](https://github.com/openclaw/openclaw/pull/199650) fix(cli): show actionable QR pairing failures alongside JSON
- [#199215](https://github.com/openclaw/openclaw/pull/199215) fix(ui): publication status checks look idle while pending
- [#199219](https://github.com/openclaw/openclaw/pull/199219) fix(ui): saving feedback fades like an unavailable control
- [#199873](https://github.com/openclaw/openclaw/pull/199873) fix(sessions): transcript facts backfill replays every covered session after a restart
- [#199882](https://github.com/openclaw/openclaw/pull/199882) fix(a2a): inbound correlation test fails intermittently on unrelated PRs
- [#199218](https://github.com/openclaw/openclaw/pull/199218) fix(ui): embedded settings show oversized loading indicators

### 🐛 New Issues
- [#199893](https://github.com/openclaw/openclaw/issues/199893) Anthropic setup-token is unavailable in personal Connected accounts
- [#199888](https://github.com/openclaw/openclaw/issues/199888) Gateway memory import writes its pre-import backup to the Gateway's working directory `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#199886](https://github.com/openclaw/openclaw/issues/199886) [Bug]: Inbound Twilio call is accepted but returns only a silent 30-second pause `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` 💬1
- [#199885](https://github.com/openclaw/openclaw/issues/199885) Docs: make inbound Twilio setup explicit in Voice Call quick start `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#199883](https://github.com/openclaw/openclaw/issues/199883) OpenRouter image provider drops aspectRatio/resolution for non-Gemini models (e.g. Seedream 5.5 always square) `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#199880](https://github.com/openclaw/openclaw/issues/199880) Qualify watched-session prompts with PostgreSQL Gateway admission `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:linked-pr-open` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#199877](https://github.com/openclaw/openclaw/issues/199877) [Bug]: Supabase execute_sql returns "user rejected MCP tool call" without a visible approval prompt `bug` `bug:behavior` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#199876](https://github.com/openclaw/openclaw/issues/199876) [Bug]: MS Teams and Zalo (zalouser) still split fenced code blocks mid-fence — fix prepared, needs tenant-backed delivery proof `P2` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#199875](https://github.com/openclaw/openclaw/issues/199875) Control UI: a connection that died while you were in another app is not replaced for 40 s or more `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#199870](https://github.com/openclaw/openclaw/issues/199870) [Bug]: 2026.10.3 candidate snapshot queue failure blocks upgrade with large histories `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#199854](https://github.com/openclaw/openclaw/issues/199854) test(gateway): await real maintenance before pending-install reload assertion `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1

### 🔒 Closed Issues
- [#199614](https://github.com/openclaw/openclaw/issues/199614) perf(sessions): transcript facts backfill restarts from zero and starves gateway RPC on large databases
- [#199101](https://github.com/openclaw/openclaw/issues/199101) [Bug]: MCP Events accepts impossible calendar dates in callbacks and subscription expiry

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬82 · 3h ago
- [#116201](https://github.com/openclaw/openclaw/issues/116201) Realtime voice work can retain unbounded provider and consult state — 💬59 · 44d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 263,653 · **Open issues:** 53,350 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.23.1+canary.20261115T064406Z](https://github.com/NousResearch/hermes-agent/releases/tag/v0.23.1%2Bcanary.20261115T064406Z) — Hermes Agent canary v0.23.1+canary.20261115T064406Z

### ✅ Merged PRs
- [#155467](https://github.com/NousResearch/hermes-agent/pull/155467) fix(approval): heredoc-aware command floors; flag same-string fetch-then-run, group/interpreter pipe sinks, brace command words

### 🐛 New Issues
- [#156324](https://github.com/NousResearch/hermes-agent/issues/156324) [Bug]: iOS upward swipes activate bottom-bar menus in the browser-hosted Desktop `type/bug` `P2` `comp/desktop` 💬1
- [#156323](https://github.com/NousResearch/hermes-agent/issues/156323) fix(cron): a sync canonical fire inside a running loop books asyncio's own refusal as a job failure (gateway draining) `type/bug` `comp/cron` `P2` 💬1
- [#156320](https://github.com/NousResearch/hermes-agent/issues/156320) Kanban: chat-only board toolset, or keep kanban_* tools direct for dispatched workers under tool_search defer `type/feature` `comp/tools` `P3`
- [#156318](https://github.com/NousResearch/hermes-agent/issues/156318) Signed-in / session-expiry signal for saved vault logins (so the agent can say a site needs signing in again before a task fails) `type/feature` `tool/browser` `area/auth` `P2` `comp/desktop` `area/sessions`
- [#156316](https://github.com/NousResearch/hermes-agent/issues/156316) hermes vault import: bring existing logins in from a password-manager export (1Password, Bitwarden, Chrome) `type/feature` `area/auth` `P2` `comp/desktop`
- [#156315](https://github.com/NousResearch/hermes-agent/issues/156315) Feature: emit OSC 7501 state sequences when running inside a Herdr pane (HC_TERMINAL_ID) `type/feature` `comp/tui` `P3`
- [#156311](https://github.com/NousResearch/hermes-agent/issues/156311) check_runtime warns 'install out of sync' on a sealed Docker image: pnpm is never present, and the venv stamp ignores plugin members that runtime discovery adds `type/bug` `comp/cli` `P2` `area/install-update` 💬1

### 🔒 Closed Issues
- [#152148](https://github.com/NousResearch/hermes-agent/issues/152148) [Bug]: Fresh Telegram DM topics remain invisible/unopenable after recovery; inbound adoption and delivered replies mask failure
- [#140704](https://github.com/NousResearch/hermes-agent/issues/140704) [Bug]: command floors read heredoc bodies as shell: a quote in the body hides the next command from hardline and approvals.deny (rm -rf / approved under yolo)
- [#76883](https://github.com/NousResearch/hermes-agent/issues/76883) feat(memory): make memory mutations reversible — local archive for remove/replace (skill/memory delete asymmetry)
- [#142354](https://github.com/NousResearch/hermes-agent/issues/142354) [Bug][Desktop] Read-aloud cuts the first sentence of a short post-thinking reply and stamps a false user-interrupt
- [#84411](https://github.com/NousResearch/hermes-agent/issues/84411) [Bug]: Desktop hides background_review model pin and “Reset all to main” leaves it active
- [#136227](https://github.com/NousResearch/hermes-agent/issues/136227) [Bug]: copilot-acp returns 10 consecutive empty completions (finish=stop, no chunks); shim swallows chunk shapes and zeros usage

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,378 · **Open issues:** 1,272 · **Last push:** 3h ago

### ✅ Merged PRs
- [#12074](https://github.com/zeroclaw-labs/zeroclaw/pull/12074) fix(zerocode): refresh the context budget after a trim

### 🐛 New Issues
- [#12484](https://github.com/zeroclaw-labs/zeroclaw/issues/12484) [Bug]: remove() of a plugin whose directory is gone fails on Windows because rename_new loses ErrorKind::NotFound
- [#12483](https://github.com/zeroclaw-labs/zeroclaw/issues/12483) [Bug]: a_stopped_gateway_releases_its_port_before_its_drain_ends fails on Windows in every scheduled Platform Tests run
- [#12480](https://github.com/zeroclaw-labs/zeroclaw/issues/12480) [Feature]: Decide the default web search provider and how users are told `enhancement`
- [#12477](https://github.com/zeroclaw-labs/zeroclaw/issues/12477) [Bug]: cost.enforcement.mode is ignored, so an exceeded budget always stops the turn, even in the default "warn" mode
- [#12476](https://github.com/zeroclaw-labs/zeroclaw/issues/12476) [Bug]: gateway logs every connection at INFO through spawn!, flooding the runtime trace

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,716 · **Open issues:** 1,574 · **Last push:** 6d ago

### 🐛 New Issues
- [#8173](https://github.com/nearai/ironclaw/issues/8173) Support failover between registry providers (e.g. Ollama → Ollama)
- [#8172](https://github.com/nearai/ironclaw/issues/8172) [QA] Make PRIMARY_MODEL_CALL_IDLE_TIMEOUT configurable for slow local LLMs `qa-bug`
- [#2843](https://github.com/nearai/ironclaw/issues/2843) Cost-based budgeting: replace iteration/time caps with USD budgets cascading user → project → mission → thread `enhancement` `risk: high` `scope: agent` `scope: db` `scope: config` 💬1

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,962 · **Open issues:** 121 · **Last push:** 23d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬4 · 3d ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 13d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 22d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 41d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 49d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 51d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 61d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 69d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 71d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 79d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [EUROPA, the EU's open AI model, is aiming for nearly 1 trillion parameters](https://reddit.com/r/LocalLLaMA/comments/1xwr917/europa_the_eus_open_ai_model_is_aiming_for_nearly/) ↑740
- [I finally succeed the CMP 170HX voltage glitch and get 80GB VRAM + 126sm! !](https://reddit.com/r/LocalLLaMA/comments/1xwxzgj/i_finally_succeed_the_cmp_170hx_voltage_glitch/) ↑538
- [RASA will cause total chaos to open LLMs and beyond](https://reddit.com/r/LocalLLaMA/comments/1xwmnkw/rasa_will_cause_total_chaos_to_open_llms_and/) ↑216
- [Basalt 0.4.0: More models, still as fast - Qwen 27B up to 770 tok/s on a 5090](https://reddit.com/r/LocalLLaMA/comments/1xx1cu9/basalt_040_more_models_still_as_fast_qwen_27b_up/) ↑190
- [Latest version of strata made my Qwen3.8-Flash-Next dumb and useless](https://reddit.com/r/LocalLLaMA/comments/1xwttcw/latest_version_of_strata_made_my_qwen38flashnext/) ↑139

### r/singularity — top 3 new
- [Gemini 4 Hydrogen just DESTROYED Claude Fable 5.2 & all other models in the latest benchmark.](https://reddit.com/r/singularity/comments/1xwvg9b/gemini_4_hydrogen_just_destroyed_claude_fable_52/) ↑2630
- [Claude Fable 5.2 wrote a working Transformer AI, while Opus 5.5 generated its training data. The result: a 367,000-parameter language model that fits on a floppy disk and runs on a 1990s Pentium PC wi](https://reddit.com/r/singularity/comments/1xx8w9q/claude_fable_52_wrote_a_working_transformer_ai/) ↑402
- [Qwen4-Max: Your New Teammate Has Arrived](https://reddit.com/r/singularity/comments/1xxdj2b/qwen4max_your_new_teammate_has_arrived/) ↑2

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Openclaw Cron Fallback Provider Fix has been built!](https://reddit.com/r/openclaw/comments/1xwu0ui/openclaw_cron_fallback_provider_fix_has_been_built/) ↑12
- [OpenClaw showcase: version workspace instructions and check them for drift](https://reddit.com/r/openclaw/comments/1xx7v8f/openclaw_showcase_version_workspace_instructions/) ↑1

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [Gemini 4 Hydrogen is out and you can already use it in OpenClaw! 🦞


https://
x.com/OfficialLoganK
/status/2120940951292](https://x.com/openclaw/status/2121098531205501401)

### X — @steipete
_No new tweets since the last digest. Most recent:_
- [🍿](https://x.com/steipete/status/2121706904917520875)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
