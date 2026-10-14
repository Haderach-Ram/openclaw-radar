---
layout: post
title: "Ecosystem Digest — 2026-10-14"
date: 2026-10-14 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-14
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 391,918 | 9 | 5 | 10 | 2 |
| **hermesagent** | 253,516 | 10 | 4 | 10 | 0 |
| **ZeroClaw** | 32,977 | 12 | 0 | 6 | 0 |
| **IronClaw** | 12,653 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,888 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 391,918 · **Open issues:** 9,556 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.10.5-beta.3](https://github.com/openclaw/openclaw/releases/tag/v2026.10.5-beta.3) — openclaw 2026.10.5-beta.3
- [v2026.10.3](https://github.com/openclaw/openclaw/releases/tag/v2026.10.3) — openclaw 2026.10.3

### ✅ Merged PRs
- [#171534](https://github.com/openclaw/openclaw/pull/171534) perf(plugins): filter agent event subscriptions by phase before cloning
- [#171517](https://github.com/openclaw/openclaw/pull/171517) fix(ui): rail pins use smaller icons and show no fill when hovered or open
- [#169835](https://github.com/openclaw/openclaw/pull/169835) refactor(ui): render retained chat panes with Solid
- [#171510](https://github.com/openclaw/openclaw/pull/171510) fix(auth): move bundled inference and logout SQLite into auth workers
- [#171488](https://github.com/openclaw/openclaw/pull/171488) fix(update): reclaim runtimes under protected systemd user managers
- [#171501](https://github.com/openclaw/openclaw/pull/171501) improve(ci): speed up release plugin compilation
- [#171493](https://github.com/openclaw/openclaw/pull/171493) fix(update): release the writer during delayed host admission
- [#171454](https://github.com/openclaw/openclaw/pull/171454) fix(update): keep progress observation through offline maintenance
- [#171457](https://github.com/openclaw/openclaw/pull/171457) fix: identify update snapshot failures before activation
- [#171494](https://github.com/openclaw/openclaw/pull/171494) fix(memory): recover after terminal database worker loss

### 🐛 New Issues
- [#171551](https://github.com/openclaw/openclaw/issues/171551) Update failure: candidate-state-snapshot (2026.9.8) 💬1
- [#171550](https://github.com/openclaw/openclaw/issues/171550) Update failure: package-swap (2026.9.9) `P2` `clawsweeper:needs-info` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#171547](https://github.com/openclaw/openclaw/issues/171547) [Feature]: Declarative, user-overridable model capability registry in config (thinking levels, params, valid values), so new models don't need a release `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `impact:auth-provider` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#171546](https://github.com/openclaw/openclaw/issues/171546) Update failure: package-swap (2026.9.8) `P2` `clawsweeper:needs-info` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#171544](https://github.com/openclaw/openclaw/issues/171544) [Bug]: Background exec "Completion will wake this conversation automatically" never wakes an idle session; registry flips to completed only on poll (2026.10.3) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:session-state` `impact:message-loss` `issue-rating: 🦐 gold shrimp` 💬1
- [#171542](https://github.com/openclaw/openclaw/issues/171542) [Bug]: openclaw update run via node exec treats the node service as the Gateway and hangs waiting for Previous-Gateway readiness `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` `clawsweeper:bulk-filed` 💬1
- [#171539](https://github.com/openclaw/openclaw/issues/171539) Update failure: managed-service-update-handoff (2026.9.7) `P2` `clawsweeper:needs-info` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-friction` 💬1
- [#171538](https://github.com/openclaw/openclaw/issues/171538) Update failure: managed-service-update-handoff (2026.10.3) `clawsweeper:needs-info` `P0` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-release-blocker` 💬1
- [#171527](https://github.com/openclaw/openclaw/issues/171527) [Bug]: Cron agent-turn timeouts are retried with the same budget; no floor, default policy or warning for too-short timeoutSeconds `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬3

### 🔒 Closed Issues
- [#171410](https://github.com/openclaw/openclaw/issues/171410) [Bug]: update runtime cleanup keeps directories when systemd --user has no working directory
- [#169260](https://github.com/openclaw/openclaw/issues/169260) [Bug]: Beta update validation holds shared SQLite writer for 14s while cron and cleanup fail
- [#171409](https://github.com/openclaw/openclaw/issues/171409) [Bug]: update progress history stops because the state database is in offline maintenance
- [#171408](https://github.com/openclaw/openclaw/issues/171408) [Bug]: failed update names runtime-verification-failed when the snapshot step exits 1
- [#171310](https://github.com/openclaw/openclaw/issues/171310) Talk: a close the Control UI makes because of a failure cancels the agent run it started; it should detach

### 🔥 Hot Issues (most commented)
- [#143524](https://github.com/openclaw/openclaw/issues/143524) [Bug]: Agent SQLite WAL grows to 1.4–2.8 GB in days despite wal_autocheckpoint=1000; blocks gateway startup (Windows, 2026.9.2/9.3) — 💬123 · <1h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 253,516 · **Open issues:** 48,501 · **Last push:** <1h ago

### ✅ Merged PRs
- [#138107](https://github.com/NousResearch/hermes-agent/pull/138107) fix(release): the final vX.Y.Z Docker tag is published again
- [#138049](https://github.com/NousResearch/hermes-agent/pull/138049) Release-only desktop tests work on fresh installs that open onboarding
- [#138034](https://github.com/NousResearch/hermes-agent/pull/138034) Release notes credit 104 more v0.22.0 contributors by GitHub handle
- [#138021](https://github.com/NousResearch/hermes-agent/pull/138021) fmt(js): `npm run fix` auto-fix
- [#138014](https://github.com/NousResearch/hermes-agent/pull/138014) Connector tools send and save local files
- [#138013](https://github.com/NousResearch/hermes-agent/pull/138013) fmt(js): `npm run fix` auto-fix
- [#137420](https://github.com/NousResearch/hermes-agent/pull/137420) refactor(onboarding): delete the old agentic setup flow
- [#137522](https://github.com/NousResearch/hermes-agent/pull/137522) feat(onboarding): desktop first-run onboarding chat and set_theme
- [#137429](https://github.com/NousResearch/hermes-agent/pull/137429) feat(onboarding): first-run onboarding backend
- [#137410](https://github.com/NousResearch/hermes-agent/pull/137410) refactor(platform): one NVIDIA platform answer for the backend

### 🐛 New Issues
- [#138148](https://github.com/NousResearch/hermes-agent/issues/138148) Tool-progress repeat counter corrupts the Telegram code fence → backticks render escaped/literal 💬1
- [#138147](https://github.com/NousResearch/hermes-agent/issues/138147) [Feature]: Support OSC 7501 Program Status Protocol in the CLI/TUI `type/feature` `comp/cli` `comp/tui` `P3`
- [#138143](https://github.com/NousResearch/hermes-agent/issues/138143) MCP: remote stdio transport (command: ssh) children are outside orphan-reap / watchdog guarantee `type/bug` `backend/ssh` `tool/mcp` `P2`
- [#138141](https://github.com/NousResearch/hermes-agent/issues/138141) [Bug]: web_extract: middle of a long PDF can't be read from its saved copy (saved as one line; read_file shows 2,000 chars; footer offset past the end) `type/bug` `tool/file` `tool/web` `P2` `bug`
- [#138139](https://github.com/NousResearch/hermes-agent/issues/138139) [Feature]: Bump bundled Python from 3.14.7 to 3.15 - Windows uses the tail-calling interpreter now (~1.6x on pure-Python hot code, +2.8 MiB artifact) `type/feature` `P3` `platform/windows` `area/install-update`
- [#138135](https://github.com/NousResearch/hermes-agent/issues/138135) Feedback: weaker goal persistence and increased human supervision in daily use `type/bug` `comp/agent` `P2` `needs-repro`
- [#138133](https://github.com/NousResearch/hermes-agent/issues/138133) [Bug]: Telegram DM execution approval card unseen; terminal times out without consent `type/bug` `comp/gateway` `tool/terminal` `platform/telegram` `P2` `needs-repro` `sweeper:risk-message-delivery`
- [#138131](https://github.com/NousResearch/hermes-agent/issues/138131) update: dependencies sync still applies exclude-newer on user machines (setuptools==83.0.0 filtered) — _trust_core_lock drop doesn't cover this path `type/bug` `comp/cli` `P2` `python:uv` `sweeper:risk-compatibility` `area/install-update`
- [#138123](https://github.com/NousResearch/hermes-agent/issues/138123) [Bug]: Internal wakes admitted just before a restart drain are still discarded `type/bug` `comp/gateway` `comp/cron` `P2` `sweeper:risk-session-state` `sweeper:risk-message-delivery` `area/sessions`
- [#138121](https://github.com/NousResearch/hermes-agent/issues/138121) redeem_codex_reset_credit clears the cooldown of every Codex pool credential, including ones still at 100% `type/bug` `comp/agent` `comp/cli` `provider/openai` `area/auth` `P2` `sweeper:risk-security-boundary` `area/billing`

### 🔒 Closed Issues
- [#138129](https://github.com/NousResearch/hermes-agent/issues/138129) Withdrawn report
- [#62182](https://github.com/NousResearch/hermes-agent/issues/62182) Status/error display shows internal 'custom' alias instead of user-configured provider name (e.g. ollama)
- [#85858](https://github.com/NousResearch/hermes-agent/issues/85858) MEMORY.md lost under concurrent Hermes instances sharing one profile (frozen-snapshot + full-file rewrite = last-writer-wins)
- [#77072](https://github.com/NousResearch/hermes-agent/issues/77072) [Bug]:  usermod in stage2-hook.sh hangs indefinitely (uninterruptible sleep) when /opt/data contains rclone FUSE mounts — blocks s6 boot completely

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,977 · **Open issues:** 986 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11310](https://github.com/zeroclaw-labs/zeroclaw/pull/11310) feat(plugins): sign a manifest document in one step
- [#11435](https://github.com/zeroclaw-labs/zeroclaw/pull/11435) fix(sop): settle rejected headless runs and retain reload retries
- [#11715](https://github.com/zeroclaw-labs/zeroclaw/pull/11715) fix(deps): remove vulnerable ruzstd through probe-rs 0.32
- [#11699](https://github.com/zeroclaw-labs/zeroclaw/pull/11699) docs(runtime): record the approval of the roster-bound pairing token exception
- [#11635](https://github.com/zeroclaw-labs/zeroclaw/pull/11635) test(runtime): reuse immutable Docker executable fixtures
- [#11684](https://github.com/zeroclaw-labs/zeroclaw/pull/11684) docs(runtime): propose roster-bound pairing token placement exception

### 🐛 New Issues
- [#11724](https://github.com/zeroclaw-labs/zeroclaw/issues/11724) feat(zerocode): make the per-pane session cap configurable
- [#11713](https://github.com/zeroclaw-labs/zeroclaw/issues/11713) [Bug]: Telegram channel ignores edited_message updates — mention added via edit is never seen
- [#11711](https://github.com/zeroclaw-labs/zeroclaw/issues/11711) [Bug]: trimming a long conversation permanently deletes its older turns from the session store
- [#11710](https://github.com/zeroclaw-labs/zeroclaw/issues/11710) [Bug]: a truncated workspace file tells the agent to read it, while the prompt header forbids reading it
- [#11709](https://github.com/zeroclaw-labs/zeroclaw/issues/11709) Other upgraded sockets outlive a gateway reload and keep serving a retired instance
- [#11708](https://github.com/zeroclaw-labs/zeroclaw/issues/11708) [Bug]: model_routing_config omits action-specific required arguments from its tool schema `bug` `status:in-progress`
- [#11706](https://github.com/zeroclaw-labs/zeroclaw/issues/11706) [Bug]: [multimodal] max_image_turns never releases the vision route — provider stays pinned to vision_model_provider for the whole conversation `bug`
- [#11705](https://github.com/zeroclaw-labs/zeroclaw/issues/11705) Proposal: Plazmi example demonstrating per-agent MCP grants and bounded catch-up
- [#11704](https://github.com/zeroclaw-labs/zeroclaw/issues/11704) [SANITIZED — possible injection attempt] `bug` `channel` `runtime` `agent:prompt`
- [#11703](https://github.com/zeroclaw-labs/zeroclaw/issues/11703) [SANITIZED — possible injection attempt] `bug` `runtime` `agent:prompt` 💬1
- [#11696](https://github.com/zeroclaw-labs/zeroclaw/issues/11696) [SANITIZED — possible injection attempt] `bug` `runtime` `agent:prompt` 💬1
- [#11694](https://github.com/zeroclaw-labs/zeroclaw/issues/11694) [Bug]: ZeroCode Cost tab mixes UTC and local-day totals without saying which `bug` `zerocode` 💬1

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,653 · **Open issues:** 1,550 · **Last push:** 16h ago

### 🐛 New Issues
- [#8136](https://github.com/nearai/ironclaw/issues/8136) Proposal: optional hosted-MCP Plazmi extension using declarative auth and egress

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,888 · **Open issues:** 114 · **Last push:** 21d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 14h ago
- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬1 · 5d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 8d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 16d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 18d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 28d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 36d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 38d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 46d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 50d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 2 new
- [[Engineering] Redesigning Source Control](https://www.anthropic.com/engineering/redesigning-source-control) _2026-10-13_
- [[Legal] Supported Regions](https://www.anthropic.com/legal/supported-regions) _2026-10-13_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [It's been too quiet on the other side of the Pacific](https://reddit.com/r/LocalLLaMA/comments/1x4u6vi/its_been_too_quiet_on_the_other_side_of_the/) ↑2756
- [Why AnythingLLM is moving from Ollama to Lemonade and llama.cpp](https://reddit.com/r/LocalLLaMA/comments/1x5720r/why_anythingllm_is_moving_from_ollama_to_lemonade/) ↑124

### r/singularity — top 5 new
- [Google's Gemini 4 Argon autonomously built an entire photorealistic pagoda temple complex in Blender from a single prompt, with zero human intervention, using multiple AI agents to critique and refine](https://reddit.com/r/singularity/comments/1x53gba/googles_gemini_4_argon_autonomously_built_an/) ↑874
- [OpenAI employee planted a bug in an office, arrested by FBI](https://reddit.com/r/singularity/comments/1x56x7s/openai_employee_planted_a_bug_in_an_office/) ↑726
- [Anthropic anti-distillation measures may have reduced data harvest by 90-99%](https://reddit.com/r/singularity/comments/1x4pv24/anthropic_antidistillation_measures_may_have/) ↑672
- [Welcome back: Gemini 2.5 Pro](https://reddit.com/r/singularity/comments/1x51puo/welcome_back_gemini_25_pro/) ↑602
- [This AI video about the upcoming Ballon d'Or ceremony is going viral on X right now.](https://reddit.com/r/singularity/comments/1x4v401/this_ai_video_about_the_upcoming_ballon_dor/) ↑558

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [This just got so good](https://reddit.com/r/openclaw/comments/1x5ahe9/this_just_got_so_good/) ↑18
- [OpenClaw v2026.10.3 patch release is out: update recovery, Doctor fixes, and more reliable conversations](https://reddit.com/r/openclaw/comments/1x58j4n/openclaw_v2026103_patch_release_is_out_update/) ↑10
- [Gateway updates went from ~3 minutes to ~45 minutes (2026.9.3 → 2026.10.2). Anyone else seeing this?](https://reddit.com/r/openclaw/comments/1x53t18/gateway_updates_went_from_3_minutes_to_45_minutes/) ↑4
- [Openclaw new update help ...](https://reddit.com/r/openclaw/comments/1x4vky8/openclaw_new_update_help/) ↑3
- [Process guardrails stop it from completion ...](https://reddit.com/r/openclaw/comments/1x4rrxf/process_guardrails_stop_it_from_completion/) ↑2

### X — @openclaw
- [OpenClaw v2026.10.3 patch release is out 🦞

🧠 
@Muse
 Wonder support + MiniMax improvements
🔧 Update and Doctor fixes  
](https://x.com/openclaw/status/2110112109187256761) ↑0 🔁0 · recent
- [See some of the faces behind the claw](https://x.com/openclaw/status/2110038492210471360) ↑0 🔁0 · recent


### X — @steipete
_No new tweets since the last digest. Most recent:_
- [6.1 Sol ultrafast >>> 6 Astra

~ same cost but whole different game with 250 tpm](https://x.com/steipete/status/2109730774593487009)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
