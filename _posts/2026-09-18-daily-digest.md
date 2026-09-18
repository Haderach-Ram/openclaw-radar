---
layout: post
title: "Ecosystem Digest — 2026-09-18"
date: 2026-09-18 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-18
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 390,015 | 8 | 2 | 10 | 0 |
| **hermesagent** | 246,575 | 7 | 2 | 5 | 0 |
| **ZeroClaw** | 32,827 | 15 | 6 | 10 | 0 |
| **IronClaw** | 12,623 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,865 | 2 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 390,015 · **Open issues:** 7,667 · **Last push:** <1h ago

### ✅ Merged PRs
- [#151211](https://github.com/openclaw/openclaw/pull/151211) fix(doctor): own legacy title and ACP key repair
- [#151302](https://github.com/openclaw/openclaw/pull/151302) test(fs): route Bun race spies through node fs
- [#151304](https://github.com/openclaw/openclaw/pull/151304) fix(release): review the Codex catalog performance support spawn
- [#150628](https://github.com/openclaw/openclaw/pull/150628) perf(gateway): move managed image metadata reads to workers
- [#151270](https://github.com/openclaw/openclaw/pull/151270) fix: stop directory lookups after caller cancellation
- [#151290](https://github.com/openclaw/openclaw/pull/151290) fix: avoid rebuilding session lists for unchanged catalog refreshes
- [#151161](https://github.com/openclaw/openclaw/pull/151161) test(cli): diagnose stalled Doctor test children
- [#151293](https://github.com/openclaw/openclaw/pull/151293) fix(tests): prevent stray heartbeat work in cron reload tests
- [#151003](https://github.com/openclaw/openclaw/pull/151003) fix(update): restore Gateway and clear stale warnings after repair
- [#147881](https://github.com/openclaw/openclaw/pull/147881) perf(windows): avoid full-chunk copies during UTF-8 decoding

### 🐛 New Issues
- [#151315](https://github.com/openclaw/openclaw/issues/151315) Anthropic direct API path doesn't reliably apply ephemeral cache_control, causing O(n^2) cache-write cost blowup in long sessions 💬1
- [#151311](https://github.com/openclaw/openclaw/issues/151311) Scheduled cron agent turns intermittently fail with Async work scope is closed; possible inherited timer scope (2026.9.4) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` 💬1
- [#151308](https://github.com/openclaw/openclaw/issues/151308) Control UI WebChat: transcript scrolls back to top after long tool-using replies complete `P2` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#151307](https://github.com/openclaw/openclaw/issues/151307) Update failure: readyz-unhealthy (2026.9.4) `P0` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-release-blocker` 💬2
- [#151306](https://github.com/openclaw/openclaw/issues/151306) [Feature]: Per-account inbound debounce for multi-account channels (retired as redundant in #113174) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#151301](https://github.com/openclaw/openclaw/issues/151301) [Bug]: Browser storage commands read or overwrite the wrong key when it has surrounding spaces `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:data-loss` `issue-rating: 🦞 diamond lobster` `clawsweeper:bulk-filed` 💬1
- [#151295](https://github.com/openclaw/openclaw/issues/151295) [Bug]: Large fleets cannot upgrade from 2026.9.4: candidate Doctor exhausts the installed updater's 300 s canary budget, then writes a migration marker the installed runtime rejects `maintainer` `P1` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` `maturity:stable` 💬2
- [#151280](https://github.com/openclaw/openclaw/issues/151280) [Bug]: Teams personal-chat replies lose explicit reply placement `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬3

### 🔒 Closed Issues
- [#151264](https://github.com/openclaw/openclaw/issues/151264) [Bug]: canceled message actions can still start directory lookups
- [#151271](https://github.com/openclaw/openclaw/issues/151271) [Bug]: Catalog attempt notifications repeatedly rebuild all resident session rows

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 246,575 · **Open issues:** 43,838 · **Last push:** <1h ago

### ✅ Merged PRs
- [#113524](https://github.com/NousResearch/hermes-agent/pull/113524) fix(slack): reopen a native task card when Slack seals the stream mid-turn
- [#114539](https://github.com/NousResearch/hermes-agent/pull/114539) fix: installed directory plugin keeps its identity over a same-name pip entry point
- [#111219](https://github.com/NousResearch/hermes-agent/pull/111219) fix(bedrock): restore Grok context and preserve confirmed cache limits
- [#114483](https://github.com/NousResearch/hermes-agent/pull/114483) fix(slack): retain bearer on validated Enterprise Grid file redirects
- [#114261](https://github.com/NousResearch/hermes-agent/pull/114261) catalog: mnemosyne key goes to mnemosyne-oss; unaffiliated Devs-Foundation entry delisted

### 🐛 New Issues
- [#114579](https://github.com/NousResearch/hermes-agent/issues/114579) [Bug]: Web Dashboard Chat tab freezes completely on image paste (PTY timing race & orphan process leak) `bug`
- [#114576](https://github.com/NousResearch/hermes-agent/issues/114576) Feature request: per-prompt opt-out to skip MoA reference fan-out (solo aggregator for trivial prompts)
- [#114574](https://github.com/NousResearch/hermes-agent/issues/114574) [Bug]: "OpenRouter provider fails with empty HTTP 400 on every model — Gemini works fine" `bug`
- [#114572](https://github.com/NousResearch/hermes-agent/issues/114572) Custom endpoint delete fails for stored provider keys containing dots
- [#114571](https://github.com/NousResearch/hermes-agent/issues/114571) macOS: launchctl exit 5 over a live supervised gateway brands the host unsupported and starts a detached duplicate
- [#114564](https://github.com/NousResearch/hermes-agent/issues/114564) [Bug]: kanban delete_attachment() unlinks a blob another row still references — silent data loss (shared stored_path) `type/bug` `comp/cron` `P3`
- [#114552](https://github.com/NousResearch/hermes-agent/issues/114552) [Bug]: disk-cleanup's tracked-item delete path rmtree's protected top-level dirs — wipes $HERMES_HOME/cache (breaks terminal snapshots) and kanban attachments `type/bug` `comp/plugins` `P2` 💬2

### 🔒 Closed Issues
- [#110912](https://github.com/NousResearch/hermes-agent/issues/110912) Nous Portal: full/list price charged on some model routes (glm/glm-flash/kimi) while subscription credits active — likely a discount-route bug, not credit exhaustion
- [#114114](https://github.com/NousResearch/hermes-agent/issues/114114) [Closed / Unconfirmed]: Custom GSV TTS may add Chinese filler interjections

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,827 · **Open issues:** 799 · **Last push:** 2h ago

### ✅ Merged PRs
- [#10618](https://github.com/zeroclaw-labs/zeroclaw/pull/10618) feat(maintainers): surface approval carry-forward candidates
- [#10894](https://github.com/zeroclaw-labs/zeroclaw/pull/10894) fix(runtime): normalize image markers on the run_model_query seam
- [#10899](https://github.com/zeroclaw-labs/zeroclaw/pull/10899) fix(channels): alias-aware sender scope keys and lane regressions
- [#9854](https://github.com/zeroclaw-labs/zeroclaw/pull/9854) fix(providers): derive context-window discovery from the family registry
- [#10468](https://github.com/zeroclaw-labs/zeroclaw/pull/10468) fix(tools): expose owned ACP sessions to session tools
- [#10886](https://github.com/zeroclaw-labs/zeroclaw/pull/10886) fix(providers): let timeout_secs raise the streaming idle bound
- [#10859](https://github.com/zeroclaw-labs/zeroclaw/pull/10859) fix(runtime): gate Unix-only test support on Windows
- [#10868](https://github.com/zeroclaw-labs/zeroclaw/pull/10868) ci(tests): parallelize channel feature and plugin runtime tests
- [#10556](https://github.com/zeroclaw-labs/zeroclaw/pull/10556) fix(runtime): honor allowed roots in Seatbelt
- [#10862](https://github.com/zeroclaw-labs/zeroclaw/pull/10862) [SANITIZED — possible injection attempt]

### 🐛 New Issues
- [#10952](https://github.com/zeroclaw-labs/zeroclaw/issues/10952) Seam sanitizers rewrite signed reasoning inside the assistant tool-call envelope; Anthropic rejects the replayed thinking `bug` `provider` `runtime` `provider:anthropic`
- [#10951](https://github.com/zeroclaw-labs/zeroclaw/issues/10951) [Bug]: ZeroCode Config refreshes the field list twice after saving `bug`
- [#10950](https://github.com/zeroclaw-labs/zeroclaw/issues/10950) [Bug]: cost.warn_at_percent warnings are ignored by the runtime `bug`
- [#10948](https://github.com/zeroclaw-labs/zeroclaw/issues/10948) [Bug]: interruption-scope keys collide across component boundaries `bug`
- [#10933](https://github.com/zeroclaw-labs/zeroclaw/issues/10933) [Feature]: Add MiniMax TTS and STT provider families (T2A v2 + speech_to_text) `enhancement` `config` `provider` `provider:minimax` `priority:p2` `needs-maintainer-review` `risk:medium` 💬1
- [#10932](https://github.com/zeroclaw-labs/zeroclaw/issues/10932) [Feature]: Surface the voice-note transcript to the user (STT echo) `enhancement` `channel` `config` `channel:telegram` `priority:p2` `status:accepted` `follow-up` `risk:medium` 💬2
- [#10930](https://github.com/zeroclaw-labs/zeroclaw/issues/10930) RFC: One durable primitive for questions an agent asks a human `type:rfc` 💬2
- [#10929](https://github.com/zeroclaw-labs/zeroclaw/issues/10929) RFC: Delivery receipts for outbound messages `type:rfc` 💬2
- [#10927](https://github.com/zeroclaw-labs/zeroclaw/issues/10927) [Bug]: Telegram voice preferences match destination chats instead of sender identities `bug` `channel` `channel:core` `channel:telegram` `priority:p2` `status:in-progress` `follow-up` `risk:medium` 💬1
- [#10926](https://github.com/zeroclaw-labs/zeroclaw/issues/10926) [Bug]: Matrix send_via treats peer user identities as room destinations `bug` `channel` `tool` `channel:matrix` `priority:p2` `needs-maintainer-review` `follow-up` `risk:medium` 💬2
- [#10925](https://github.com/zeroclaw-labs/zeroclaw/issues/10925) [Feature]: Support input-driven mirror voice replies on Matrix `enhancement` `channel` `channel:core` `channel:matrix` `priority:p2` `status:accepted` `follow-up` `risk:medium` `breaking-change` 💬3
- [#10924](https://github.com/zeroclaw-labs/zeroclaw/issues/10924) [Bug]: Runtime-command replies enter conversational voice routing `bug` `channel` `channel:core` `channel:telegram` `priority:p2` `follow-up` `risk:medium` 💬2
- [#10923](https://github.com/zeroclaw-labs/zeroclaw/issues/10923) [Bug]: sandbox discovery ignores the TUI PATH that launcher resolution now honors `bug` `config` `runtime` `security` `tool` `security:bubblewrap` `security:docker` `security:policy` `domain:security` `priority:p1` `tool:shell` `status:blocked` `status:accepted` `follow-up` `risk:high` 💬1
- [#10922](https://github.com/zeroclaw-labs/zeroclaw/issues/10922) [Bug]: WhatsApp Web ignores suppress_voice when queueing automatic TTS `bug` `channel` `channel:whatsapp` `priority:p2` `follow-up` `risk:medium` 💬2
- [#10921](https://github.com/zeroclaw-labs/zeroclaw/issues/10921) [Bug]: Qdrant time-bounded vector recall can omit eligible results `bug` `memory` `memory:backend` `priority:p2` `follow-up` `risk:medium` `topic:memory` 💬1

### 🔒 Closed Issues
- [#9882](https://github.com/zeroclaw-labs/zeroclaw/issues/9882) [SANITIZED — possible injection attempt]
- [#10292](https://github.com/zeroclaw-labs/zeroclaw/issues/10292) [Bug]: ACP session tools cannot list or inspect Code sessions
- [#10858](https://github.com/zeroclaw-labs/zeroclaw/issues/10858) [SANITIZED — possible injection attempt]
- [#5269](https://github.com/zeroclaw-labs/zeroclaw/issues/5269) [Bug]: validate and document the nix run installation path
- [#10939](https://github.com/zeroclaw-labs/zeroclaw/issues/10939) [Bug]: media_group_stays_pending_when_a_later_unsupported_member_follows_an_ordinary_update is flaky under the parallel runtime gate
- [#9370](https://github.com/zeroclaw-labs/zeroclaw/issues/9370) ACP: near-live JSON-RPC transport smoke for deliver_file

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,623 · **Open issues:** 1,525 · **Last push:** 4d ago

### 🐛 New Issues
- [#8101](https://github.com/nearai/ironclaw/issues/8101) Daily ironclaw failure taxonomy — 2026-09-17

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,865 · **Open issues:** 88 · **Last push:** 3d ago

### 🐛 New Issues
- [#1274](https://github.com/moltis-org/moltis/issues/1274) Prepaid search hop for Moltis wasm-web-search? `enhancement`
- [#1273](https://github.com/moltis-org/moltis/issues/1273) Nix flake cannot build the published tag: missing vendored-crate hashes and web assets

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬3 · 1d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 2d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 10d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 12d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 18d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 20d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 24d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 36d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 39d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 42d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 3 new
- [[Institute] Measuring Pace Of Ai Development](https://www.anthropic.com/institute/measuring-pace-of-ai-development) _2026-09-18_
- [[News] Life Sciences Verification Program](https://www.anthropic.com/news/life-sciences-verification-program) _2026-09-17_
- [[Research] Claude Uplifts Biomolecular Modeling](https://www.anthropic.com/research/claude-uplifts-biomolecular-modeling) _2026-09-17_

### OpenAI — 4 new
- [[Industries] Law](https://openai.com/solutions/industries/law/) _2026-09-18_
- [[Index] Cooley Gopublic](https://openai.com/index/cooley-gopublic/) _2026-09-17_
- [[Business] Contact Sales Legal](https://openai.com/business/contact-sales-legal/) _2026-09-17_
- [[Index] Astra For Law](https://openai.com/index/astra-for-law/) _2026-09-17_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [Ternary Bonsai 2 (27B) just released on Hugging Face. At <6GB in size, it can even run locally in-browser on WebGPU.](https://reddit.com/r/LocalLLaMA/comments/1wj6c4l/ternary_bonsai_2_27b_just_released_on_hugging/) ↑603
- [Thank you :) Swift Qwen 3.8 27B now has 100k+ downloads, is #1 finetune and #9 model on HuggingFace Trending](https://reddit.com/r/LocalLLaMA/comments/1wj3s31/thank_you_swift_qwen_38_27b_now_has_100k/) ↑601

### r/singularity — top 5 new
- [Ppl on this sub basically every other hour](https://reddit.com/r/singularity/comments/1wiqg8i/ppl_on_this_sub_basically_every_other_hour/) ↑7727
- [Virtual Nuclear Fusion reactor lab built using Astra in 4 hours](https://reddit.com/r/singularity/comments/1wip92j/virtual_nuclear_fusion_reactor_lab_built_using/) ↑782
- [Dario: “We need to pace the frontier.” The frontier, 48 hours later:](https://reddit.com/r/singularity/comments/1wij3qw/dario_we_need_to_pace_the_frontier_the_frontier/) ↑497
- [Anthropic open-sources Claude-written GPU optimizations that make 30+ biomolecular models ~4× faster on average](https://reddit.com/r/singularity/comments/1wj7beg/anthropic_opensources_claudewritten_gpu/) ↑335
- [Astra is porting my dual screen phone from Android 9 to Android 17](https://reddit.com/r/singularity/comments/1wiskdl/astra_is_porting_my_dual_screen_phone_from/) ↑233

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Free to use - But free to speak?](https://reddit.com/r/openclaw/comments/1wir789/free_to_use_but_free_to_speak/) ↑33
- [What’s the most useful OpenClaw automation you’ve built?](https://reddit.com/r/openclaw/comments/1wisesf/whats_the_most_useful_openclaw_automation_youve/) ↑25
- [Who else finds their agent's dreams kinda cute?](https://reddit.com/r/openclaw/comments/1wj67tj/who_else_finds_their_agents_dreams_kinda_cute/) ↑9
- [Getting locked out 3x a day on Claude Pro using OpenClaw + Sonnet 5 (Low Effort). Any tips to tame the 300k context bloat?](https://reddit.com/r/openclaw/comments/1wixyjb/getting_locked_out_3x_a_day_on_claude_pro_using/) ↑4
- [OpenClaw Skills: Reusable Workflows, a Fly Brain & Community Stories](https://reddit.com/r/openclaw/comments/1wilkaa/openclaw_skills_reusable_workflows_a_fly_brain/) ↑4

### X — @openclaw
- [OpenClaw Skills: Reusable Workflows, a Fly Brain & Community Stories


@hrudolph
 and 
@Pat_Erichsen
 talk skills with 
](https://x.com/openclaw/status/2100463500476956846) ↑0 🔁0 · recent


### X — @steipete
_No new tweets since the last digest. Most recent:_
- [Excited to have you on board, Graham!](https://x.com/steipete/status/2099960081207242808)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
