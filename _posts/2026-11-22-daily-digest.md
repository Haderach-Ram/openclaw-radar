---
layout: post
title: "Ecosystem Digest — 2026-11-22"
date: 2026-11-22 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-22
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 394,997 | 14 | 5 | 10 | 0 |
| **hermesagent** | 265,214 | 11 | 4 | 8 | 0 |
| **ZeroClaw** | 33,558 | 11 | 5 | 10 | 0 |
| **IronClaw** | 12,714 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,982 | 1 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 394,997 · **Open issues:** 8,742 · **Last push:** <1h ago

### ✅ Merged PRs
- [#202733](https://github.com/openclaw/openclaw/pull/202733) fix(ui): keep the right-docked Home actions clear of the window controls
- [#203357](https://github.com/openclaw/openclaw/pull/203357) fix(ui): show app updates outside the conversation
- [#203358](https://github.com/openclaw/openclaw/pull/203358) feat: choose a harness for primary and fallback models in Settings
- [#203376](https://github.com/openclaw/openclaw/pull/203376) fix: remove overlapping lines from the OpenClaw tool icon
- [#203363](https://github.com/openclaw/openclaw/pull/203363) fix: hide Move to cloud when no cloud profile is available
- [#203356](https://github.com/openclaw/openclaw/pull/203356) fix: keep one model’s cooldown deadline off other models
- [#203368](https://github.com/openclaw/openclaw/pull/203368) fix(ui): skip archive exit animations outside the sidebar viewport
- [#203346](https://github.com/openclaw/openclaw/pull/203346) improve: show complete 30-day Usage reports sooner
- [#203366](https://github.com/openclaw/openclaw/pull/203366) chore(ui): refresh control ui locales
- [#203285](https://github.com/openclaw/openclaw/pull/203285) fix: keep Skill Workshop draft previews tidy and Undo on the skill page

### 🐛 New Issues
- [#203378](https://github.com/openclaw/openclaw/issues/203378) Replayed inter-session messages should carry original sentAt/acceptedAt metadata `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#203374](https://github.com/openclaw/openclaw/issues/203374) [Bug]: Chat image generation leaves the session stuck when the session model is text-only `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#203373](https://github.com/openclaw/openclaw/issues/203373) [data-loss] memoryFlush can commit empty or stale LLM output to MEMORY.md — agents' long-term memory truncated to 1 byte or silently rolled back `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `impact:data-loss` `issue-rating: 🦪 silver shellfish` 💬1
- [#203371](https://github.com/openclaw/openclaw/issues/203371) Make provider sign-in easy to find in plugin settings `P2` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1
- [#203367](https://github.com/openclaw/openclaw/issues/203367) Update failure: update (2026.11.5) `P2` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#203361](https://github.com/openclaw/openclaw/issues/203361) Isolated automations accumulate unbounded session windows, and an oversized automation history cannot be deleted (2026.11.6) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#203359](https://github.com/openclaw/openclaw/issues/203359) backup create fails on PostgreSQL store anchors and leaves the Gateway state lease held (2026.11.6) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:crash-loop` `issue-rating: 🐚 platinum hermit` 💬1
- [#203354](https://github.com/openclaw/openclaw/issues/203354) [Feature]: Finish a budgeted Goal with a partial handoff before spending the last tokens `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1
- [#203353](https://github.com/openclaw/openclaw/issues/203353) [Feature]: Retry one failed native child task without recreating the parent run `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1
- [#203352](https://github.com/openclaw/openclaw/issues/203352) [Feature]: Link command approval history to the exact execution outcome `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1
- [#203351](https://github.com/openclaw/openclaw/issues/203351) [Feature]: Bind Workboard verification verdicts to the artifact revision checked `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#203350](https://github.com/openclaw/openclaw/issues/203350) [Bug]: Goal token budgets undercount usage when context size stays flat `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#203343](https://github.com/openclaw/openclaw/issues/203343) [Bug]: macOS app loops on "client credentials need recovery"; asks for a "matching CLI" that can't be installed (app 2026.11.6, app-owned runtime 2026.10.7) `bug` `regression` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `P0` `issue-rating: 🦐 gold shrimp` `impact:ux-release-blocker` 💬1
- [#203342](https://github.com/openclaw/openclaw/issues/203342) [Feature]: test Chat Completions tool-result replay before a dependent tool call `no-stale` `P3` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `issue-rating: 🌊 off-meta tidepool` 💬1

### 🔒 Closed Issues
- [#162448](https://github.com/openclaw/openclaw/issues/162448) [Bug]: Linux desktop app minimize, maximize, and close buttons are overlapping side panel controls
- [#203381](https://github.com/openclaw/openclaw/issues/203381) [Bug]: openclaw-429-fallback-bug-report
- [#203365](https://github.com/openclaw/openclaw/issues/203365) Withdrawn
- [#200775](https://github.com/openclaw/openclaw/issues/200775) [Bug]: 2026.11.5 unbound claude-cli automations refused with "no recorded inference account"; doctor --fix doesn't detect or bind them, native CLI login ignored
- [#200749](https://github.com/openclaw/openclaw/issues/200749) models auth login: Gateway-backed login renders multi-line steps with literal \n (device-code box unreadable)

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬85 · 19h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 265,214 · **Open issues:** 54,242 · **Last push:** <1h ago

### ✅ Merged PRs
- [#157430](https://github.com/NousResearch/hermes-agent/pull/157430) feat(gateway): migrate --backends --apply/--restore/--status with rollback, a per-home run lock and the update marker (stacked on #157403)
- [#140837](https://github.com/NousResearch/hermes-agent/pull/140837) CLI and TUI report idle/working/blocked/done/error to the terminal over OSC 7501 (salvage #138152, #149976; port goose#12928)
- [#157596](https://github.com/NousResearch/hermes-agent/pull/157596) plugin-catalog: evalroute 0.7.0 (evalroute[hub,decide]>=0.11.0,<0.12)
- [#158139](https://github.com/NousResearch/hermes-agent/pull/158139) Prompt-cache follow-ups: zero-priced cache writes get no markers, learned rules survive one noisy chat, cwd keeps a trailing space
- [#158681](https://github.com/NousResearch/hermes-agent/pull/158681) fix(bundles): unblock Linux AppImage arm64 builds and x64 offline sandbox check
- [#158683](https://github.com/NousResearch/hermes-agent/pull/158683) fix(upgrade): guard lazy imports against cached v0.23.3 modules mid-update
- [#158272](https://github.com/NousResearch/hermes-agent/pull/158272) fix(profiles): a delete that did not finish says so instead of hiding the profile
- [#157287](https://github.com/NousResearch/hermes-agent/pull/157287) feat(gateway): report gateway status to a deployment-stamped URL

### 🐛 New Issues
- [#158746](https://github.com/NousResearch/hermes-agent/issues/158746) [Feature]: Desktop Capabilities → Skills opens as a store; installed skills and their on/off switches are hard to find `type/feature` `tool/skills` `P3` `comp/desktop` `area/profiles` `desktop/settings`
- [#158744](https://github.com/NousResearch/hermes-agent/issues/158744) [Feature]: Opt-in to fail closed when the managed scope is missing or malformed, and report it in config check / doctor `type/feature` `comp/cli` `area/config` `P3`
- [#158738](https://github.com/NousResearch/hermes-agent/issues/158738) [Bug]: Bot Desktop shared browser launches headless when browser.headed is unset, leaving Open Screen blank and breaking dock Browser with SingletonLock `type/bug` `comp/tools` `tool/browser` `tool/file` `P2`
- [#158737](https://github.com/NousResearch/hermes-agent/issues/158737) [Bug]: Smart approvals crashes with AttributeError when auxiliary LLM returns list content blocks `type/security` `comp/agent` `comp/tools` `tool/terminal` `P3`
- [#158736](https://github.com/NousResearch/hermes-agent/issues/158736) `[Windows] WhatsApp secondary profile bridge fails to start: [WinError 5] Access is denied (CREATE_BREAKAWAY_FROM_JOB)` `type/bug` `comp/cli` `comp/plugins` `platform/whatsapp` `P2` `area/profiles` `os/windows`
- [#158735](https://github.com/NousResearch/hermes-agent/issues/158735) [Feature]: multilingual auto voice switch `type/feature` `comp/cli` `tool/tts` `area/config` `P3`
- [#158734](https://github.com/NousResearch/hermes-agent/issues/158734) kimi-k3 (kimi-coding provider): tool_call bridge receives empty arguments {} for all argument-bearing deferred tool calls `type/bug` `comp/agent` `tool/mcp` `provider/kimi` `P2`
- [#158731](https://github.com/NousResearch/hermes-agent/issues/158731) [Bug]: tool call loses its name ("Unknown tool ''") when a chunk carries held-back text and the first tool_calls delta `type/bug` `comp/agent` `P2` `area/streaming`
- [#158729](https://github.com/NousResearch/hermes-agent/issues/158729) feat(desktop): hide Dictate button when STT is disabled (stt.enabled: false) `type/feature` `tool/file` `tool/tts` `area/config` `P3` `comp/desktop` `desktop/chat`
- [#158726](https://github.com/NousResearch/hermes-agent/issues/158726) [Bug]: gateway session-cache invalidation releases a mid-turn agent and aborts the in-flight stream (WinError 10058 / cache_evict_in_flight) `type/bug` `comp/gateway` `P2` `area/sessions` `area/streaming`
- [#158723](https://github.com/NousResearch/hermes-agent/issues/158723) An old worker that outlives `hermes update` lazily imports a new-tree module that needs a name its loaded sibling lacks (`release_replaced_skill_view`) `type/bug` `comp/agent` `P2`

### 🔒 Closed Issues
- [#156315](https://github.com/NousResearch/hermes-agent/issues/156315) Feature: emit OSC 7501 state sequences when running inside a Herdr pane (HC_TERMINAL_ID)
- [#138147](https://github.com/NousResearch/hermes-agent/issues/138147) [Feature]: Support OSC 7501 Program Status Protocol in the CLI/TUI
- [#157791](https://github.com/NousResearch/hermes-agent/issues/157791) Scratch prune deletes a live process's provider-plugin frozen copy → `No module named '<module>'` on every new agent after ~24h
- [#150515](https://github.com/NousResearch/hermes-agent/issues/150515) The install root is computed by counting folders in about a hundred places

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,558 · **Open issues:** 1,353 · **Last push:** <1h ago

### ✅ Merged PRs
- [#12519](https://github.com/zeroclaw-labs/zeroclaw/pull/12519) docs(runtime): record bounded channel progress localization
- [#12608](https://github.com/zeroclaw-labs/zeroclaw/pull/12608) docs(runtime): propose ADR-016 exception for Okta and Entra ID token compatibility
- [#12574](https://github.com/zeroclaw-labs/zeroclaw/pull/12574) test(ci): fail a stopped parallel runtime pass at a deadline
- [#11079](https://github.com/zeroclaw-labs/zeroclaw/pull/11079) docs(contributing): route ordinary work by what the author knows
- [#11078](https://github.com/zeroclaw-labs/zeroclaw/pull/11078) feat(intake): require alternatives on the RFC form
- [#12526](https://github.com/zeroclaw-labs/zeroclaw/pull/12526) fix(plugins): preserve Windows rename error codes during recovery
- [#10988](https://github.com/zeroclaw-labs/zeroclaw/pull/10988) feat(channels/whatsapp-web): read poll votes back as [choice] messages
- [#12496](https://github.com/zeroclaw-labs/zeroclaw/pull/12496) docs(adr): propose daemon-held OIDC refresh and Okta/Entra ID support in ADR-017
- [#10210](https://github.com/zeroclaw-labs/zeroclaw/pull/10210) fix(tools): bound agent-browser subprocess waits with a deadline and kill_on_drop
- [#12510](https://github.com/zeroclaw-labs/zeroclaw/pull/12510) test(gateway): skip the reply-end write-deadline test on Windows

### 🐛 New Issues
- [#12638](https://github.com/zeroclaw-labs/zeroclaw/issues/12638) [Bug]: Agent cards show "<$0.01" for an agent that has spent nothing
- [#12633](https://github.com/zeroclaw-labs/zeroclaw/issues/12633) [Bug]: A voice settings screen that hasn't refreshed can switch a device back to browser-service recognition `bug`
- [#12632](https://github.com/zeroclaw-labs/zeroclaw/issues/12632) [Bug]: Voice auto-send can send text typed after dictation ends `bug`
- [#12630](https://github.com/zeroclaw-labs/zeroclaw/issues/12630) [Bug]: Dashboard Overview Channels list shows only about four channels and leaves the rest of its card empty
- [#12628](https://github.com/zeroclaw-labs/zeroclaw/issues/12628) [Feature]: tell the session when cost.enforcement.mode = "warn" lets a call through past the limit `enhancement` `agent` `risk:medium` `zerocode`
- [#12627](https://github.com/zeroclaw-labs/zeroclaw/issues/12627) [Bug]: a sub-agent started with spawn_subagent inside a bounded delegation is not held by the delegate's per-hop cost ceiling `bug` `agent` `tool:delegate` `risk:medium`
- [#12626](https://github.com/zeroclaw-labs/zeroclaw/issues/12626) [Feature]: make cost.enforcement.mode = "route_down" switch to route_down_model past a cost limit `enhancement` `agent` `config` `risk:high`
- [#12625](https://github.com/zeroclaw-labs/zeroclaw/issues/12625) skills: let `shell`/`script` tools run a program without a shell, so arguments can carry free-form text
- [#12621](https://github.com/zeroclaw-labs/zeroclaw/issues/12621) [Feature]: Retire the Raspberry Pi deploy script in scripts/ `enhancement`
- [#12619](https://github.com/zeroclaw-labs/zeroclaw/issues/12619) gateway: a failed session-state write leaves `running` until restart, and Stop can't clear it
- [#12613](https://github.com/zeroclaw-labs/zeroclaw/issues/12613) [Tracker]: Deslop pass: dead code, inert features, comment slop and extra docs `dev` `priority:p2` `type:tracker` 💬1

### 🔒 Closed Issues
- [#12484](https://github.com/zeroclaw-labs/zeroclaw/issues/12484) [Bug]: remove() of a plugin whose directory is gone fails on Windows because rename_new loses ErrorKind::NotFound
- [#10987](https://github.com/zeroclaw-labs/zeroclaw/issues/10987) [Feature]: Surface WhatsApp Web poll votes as [choice] messages, like Signal
- [#9946](https://github.com/zeroclaw-labs/zeroclaw/issues/9946) [Bug]: agent-browser subprocess waits are unbounded in both the availability probe and run_command — same defect class as #8560
- [#12400](https://github.com/zeroclaw-labs/zeroclaw/issues/12400) [Task]: make the reply-end write-deadline dashboard test pass on Windows
- [#9896](https://github.com/zeroclaw-labs/zeroclaw/issues/9896) [Bug]: status/startup banner can report `Memory: none` when effective backend is sqlite

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,714 · **Open issues:** 1,575 · **Last push:** 12d ago

### 🐛 New Issues
- [#8174](https://github.com/nearai/ironclaw/issues/8174) feat: add LLMTR as a built-in OpenAI-compatible LLM provider 💬1

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,982 · **Open issues:** 122 · **Last push:** 29d ago

### 🐛 New Issues
- [#383](https://github.com/moltis-org/moltis/issues/383) [Feature]: Support Lark/Feishu `enhancement` 💬2

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬5 · 1d ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 19d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 28d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 47d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 55d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 57d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 67d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 75d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 77d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 85d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Basalt: Inkling 2 Mini on one 5090 at up to 613 tok/s decode and 14.100 tok/s prefill (NVFP4)](https://reddit.com/r/LocalLLaMA/comments/1y1x7zo/basalt_inkling_2_mini_on_one_5090_at_up_to_613/) ↑438
- [Wow, Inkling-2-Mini fix what Qwen3.8 Next Flash and GLM 5.3 Flash couldn’t](https://reddit.com/r/LocalLLaMA/comments/1y1s8oe/wow_inkling2mini_fix_what_qwen38_next_flash_and/) ↑320
- [Inkling simply *cheff kiss*](https://reddit.com/r/LocalLLaMA/comments/1y1y7rz/inkling_simply_cheff_kiss/) ↑319
- [Inkling-2-Mini-Unbound is live: the most useful uncensored Inkling 2 Mini, via conv-aware abliteration](https://reddit.com/r/LocalLLaMA/comments/1y22kzn/inkling2miniunbound_is_live_the_most_useful/) ↑230
- [OpenRouter requests to MiniMax models may have been read](https://reddit.com/r/LocalLLaMA/comments/1y1we95/openrouter_requests_to_minimax_models_may_have/) ↑215

### r/singularity — top 2 new
- [Old Reddit thread discussing if we will ever solve the Riemann Hypothesis](https://reddit.com/r/singularity/comments/1y22y94/old_reddit_thread_discussing_if_we_will_ever/) ↑1461
- [Redditors in their final moments](https://reddit.com/r/singularity/comments/1y2aa8b/redditors_in_their_final_moments/) ↑804

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw on Apple Vision Pro with 3 Modes](https://reddit.com/r/openclaw/comments/1y1pqks/openclaw_on_apple_vision_pro_with_3_modes/) ↑11
- [Local LLM and Openclaw](https://reddit.com/r/openclaw/comments/1y1rhco/local_llm_and_openclaw/) ↑5
- [Update story...](https://reddit.com/r/openclaw/comments/1y1t1vr/update_story/) ↑2

### X — @openclaw
- [What does a lobster do at work? 🦞

While 
@OmarShahine
 was out of the office, his Autopilot, Sebastian, drafted 40 Team](https://x.com/openclaw/status/2124155892543217970) ↑0 🔁0 · recent


### X — @steipete
_No new tweets since the last digest. Most recent:_
- [Landed a fix for that in OpenClaw yesterday (for the few folks using the embedded harness instead of codex, since it’s a](https://x.com/steipete/status/2123487048250327497)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
