---
layout: post
title: "Ecosystem Digest — 2026-07-07"
date: 2026-07-07 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-07-07
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 381,964 | 5 | 3 | 10 | 0 |
| **hermesagent** | 210,400 | 3 | 5 | 3 | 0 |
| **ZeroClaw** | 32,172 | 10 | 4 | 10 | 0 |
| **IronClaw** | 12,501 | 8 | 0 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 381,964 · **Open issues:** 6,340 · **Last push:** <1h ago

### ✅ Merged PRs
- [#98312](https://github.com/openclaw/openclaw/pull/98312) fix(agent-model): omit synthesized maxTokens fallback when nothing was configured
- [#101009](https://github.com/openclaw/openclaw/pull/101009) fix(agents): normalize surrogate cache fingerprints
- [#101222](https://github.com/openclaw/openclaw/pull/101222) fix(chat.abort): pass stored sessionId to match active embedded runs
- [#101210](https://github.com/openclaw/openclaw/pull/101210) refactor(codex): store app-server thread bindings in SQLite plugin state
- [#98639](https://github.com/openclaw/openclaw/pull/98639) fix(auto-reply): stop treating wait as abort trigger
- [#101106](https://github.com/openclaw/openclaw/pull/101106) [codex] retry whatsapp session init conflicts
- [#101076](https://github.com/openclaw/openclaw/pull/101076) test(qa): use qa flow for channel routing scenarios
- [#97732](https://github.com/openclaw/openclaw/pull/97732) fix(security): align browser audit with plugin policy
- [#98682](https://github.com/openclaw/openclaw/pull/98682) fix(discord): bound gateway metadata response body reads to prevent OOM
- [#101161](https://github.com/openclaw/openclaw/pull/101161) fix(android): stabilize recent sessions overview

### 🐛 New Issues
- [#101269](https://github.com/openclaw/openclaw/issues/101269) [infra] readResponseBodySnippet non-streaming fallback reads entire response without size bound
- [#101255](https://github.com/openclaw/openclaw/issues/101255) [Feature]: Global (IP-agnostic) auth rate limiting option for public-exposed deployments `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` `maturity:stable` 💬1
- [#101254](https://github.com/openclaw/openclaw/issues/101254) [Bug]: model picker stays stale after CLI auth changes `maintainer` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:auth-provider` `P0` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-release-blocker` 💬1
- [#101247](https://github.com/openclaw/openclaw/issues/101247) Docker sandbox exec cancellation doesn't stop the container-side command (orphan keeps running) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:session-state` `impact:data-loss` `impact:security` `issue-rating: 🦞 diamond lobster` `maturity:stable` 💬1
- [#101239](https://github.com/openclaw/openclaw/issues/101239) Android: Enter key should send message when physical keyboard is connected `enhancement` `no-stale` `P3` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `maturity:stable` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#100957](https://github.com/openclaw/openclaw/issues/100957) fix(agents): prompt-cache stability fails to normalize surrogate pairs in JSON
- [#101250](https://github.com/openclaw/openclaw/issues/101250) /new may fail with "reply session initialization conflicted" when session metadata is updated concurrently
- [#101073](https://github.com/openclaw/openclaw/issues/101073) qa: canonicalize channel canary and routing scenarios

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 210,400 · **Open issues:** 26,328 · **Last push:** 1h ago

### ✅ Merged PRs
- [#59837](https://github.com/NousResearch/hermes-agent/pull/59837) fix(auxiliary): auth recovery for auto routes and stale fallback candidates
- [#59790](https://github.com/NousResearch/hermes-agent/pull/59790) fix(web): refresh dashboard model picker
- [#59782](https://github.com/NousResearch/hermes-agent/pull/59782) fix(tui): support model picker refresh

### 🐛 New Issues
- [#59914](https://github.com/NousResearch/hermes-agent/issues/59914) Hybrid memory: outline-in-context + on-demand detail retrieval `type/feature` `tool/memory` `P3`
- [#59909](https://github.com/NousResearch/hermes-agent/issues/59909) [Feature]: Feature Request: Add ability to delete/manage cron job execution history entries in desktop GUI `type/feature` `comp/cron` `P3` `comp/desktop`
- [#59896](https://github.com/NousResearch/hermes-agent/issues/59896) [Bug] DaemonThreadPoolExecutor breaks on Python 3.14 — parallel tool calls fail with AttributeError `type/bug` `duplicate` `comp/agent` `P3` 💬2

### 🔒 Closed Issues
- [#39308](https://github.com/NousResearch/hermes-agent/issues/39308) [Bug]: Windows desktop installer fails at Node/Electron stages — 8.3 short name not resolved for profile path with space
- [#23670](https://github.com/NousResearch/hermes-agent/issues/23670) Preflight compression surfaces Codex OAuth 401 instead of falling back
- [#20832](https://github.com/NousResearch/hermes-agent/issues/20832) Auxiliary Copilot token refresh is skipped for provider:auto after IDE token expires
- [#59202](https://github.com/NousResearch/hermes-agent/issues/59202) Telegram gateway connect() hangs indefinitely on first attempt at container boot — 30s asyncio.wait_for timeout never fires
- [#40069](https://github.com/NousResearch/hermes-agent/issues/40069) Desktop (remote gateway, OAuth mode): saving settings fails with net::ERR_INVALID_ARGUMENT — manual Content-Length on Electron net.request

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,172 · **Open issues:** 478 · **Last push:** 7h ago

### ✅ Merged PRs
- [#8030](https://github.com/zeroclaw-labs/zeroclaw/pull/8030) feat(doctor): warn on OpenAI Codex profile/slot wiring mismatch
- [#7768](https://github.com/zeroclaw-labs/zeroclaw/pull/7768) feat(line): loading indicator, icon/nickname switch, and bind reply feedback
- [#8659](https://github.com/zeroclaw-labs/zeroclaw/pull/8659) test(agent): add the agent-policy parity harness scaffold
- [#7529](https://github.com/zeroclaw-labs/zeroclaw/pull/7529) fix(gateway): only print dashboard URL when web_dist_dir is available
- [#8724](https://github.com/zeroclaw-labs/zeroclaw/pull/8724) fix(sop): execute deterministic capability steps via a registry and fail closed on driverless steps
- [#8233](https://github.com/zeroclaw-labs/zeroclaw/pull/8233) feat(cost): fill unpriced models from live gateway pricing
- [#8729](https://github.com/zeroclaw-labs/zeroclaw/pull/8729) ci(security): add CodeQL analysis and scheduled Trivy image scan
- [#8487](https://github.com/zeroclaw-labs/zeroclaw/pull/8487) fix(web): point favicon and sidebar logos to existing logo.png
- [#7946](https://github.com/zeroclaw-labs/zeroclaw/pull/7946) feat(runtime): add model context window ctx bar to zerocode tui, gateway agent chat, and command line interactive mode.
- [#8618](https://github.com/zeroclaw-labs/zeroclaw/pull/8618) docs(channels): add Git channel + SOP fan-in pages

### 🐛 New Issues
- [#8782](https://github.com/zeroclaw-labs/zeroclaw/issues/8782) fix(audit): bump crossbeam-epoch 0.9.18 -> 0.9.20 to clear RUSTSEC-2026-0204
- [#8780](https://github.com/zeroclaw-labs/zeroclaw/issues/8780) [Feature]: Realtime speech-to-speech channel (Gemini Live) - model owns turn-taking/audio, sibling to voicehost (#7943)
- [#8766](https://github.com/zeroclaw-labs/zeroclaw/issues/8766) [Feature]: Add user-behavior E2E coverage for first-run setup `enhancement` `channel` `config` `doctor` `runtime` `tests` `priority:p1` `status:accepted` `follow-up` `quickstart` `zerocode` `risk:high` `type:test`
- [#8765](https://github.com/zeroclaw-labs/zeroclaw/issues/8765) [Bug]: ZeroCode queue and session picker overlays can inherit terminal background `bug` `priority:p2` `status:accepted` `zerocode` `risk:low`
- [#8763](https://github.com/zeroclaw-labs/zeroclaw/issues/8763) [Feature]: Show subagent activity and expandable tool results in ZeroCode `enhancement` `agent` `observability` `tool` `priority:p2` `status:accepted` `risk:medium` `zerocode`
- [#8762](https://github.com/zeroclaw-labs/zeroclaw/issues/8762) [Bug]: Anthropic provider uses a fixed total timeout for long turns `bug` `provider` `provider:reliable` `provider:anthropic` `priority:p2` `status:accepted` `risk:medium`
- [#8760](https://github.com/zeroclaw-labs/zeroclaw/issues/8760) bug(runtime): keep daemon-owned agent output out of daemon stdout `bug` `runtime` `tool` `priority:p2` `status:accepted` `zerocode` `risk:high`
- [#8758](https://github.com/zeroclaw-labs/zeroclaw/issues/8758) [Bug]: Agent returns idle after context exhaustion without a terminal status `bug` `agent` `observability` `runtime` `priority:p2` `status:accepted` `risk:medium`
- [#8757](https://github.com/zeroclaw-labs/zeroclaw/issues/8757) [Bug]: ZeroCode config hides root channel settings such as show_tool_calls `bug` `channel` `config` `priority:p2` `status:accepted` `risk:medium` `zerocode`
- [#8753](https://github.com/zeroclaw-labs/zeroclaw/issues/8753) chore(ci): rust_quality_gate.sh misses member-crate test targets (no --workspace), broken test code can land on master `bug` `ci` `tests` `domain:ci` `release-gate` `priority:p1` `status:accepted` `risk:high` `type:ci` 💬3

### 🔒 Closed Issues
- [#8193](https://github.com/zeroclaw-labs/zeroclaw/issues/8193) bug(zerocode): MCP tools/tool_search missing from TUI sessions while gateway sees them
- [#7523](https://github.com/zeroclaw-labs/zeroclaw/issues/7523) [Bug]: dashboard not valiable
- [#8631](https://github.com/zeroclaw-labs/zeroclaw/issues/8631) [Bug]: headless deterministic SOP steps recorded Completed without executing
- [#7882](https://github.com/zeroclaw-labs/zeroclaw/issues/7882) [Feature]: Add await_sessions to the delegate tool

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,501 · **Open issues:** 1,351 · **Last push:** <1h ago

### ✅ Merged PRs
- [#5746](https://github.com/nearai/ironclaw/pull/5746) fix(deps): RUSTSEC-2026-0204 crossbeam-epoch bump — unbreaks cargo-deny on every PR
- [#5719](https://github.com/nearai/ironclaw/pull/5719) test(reborn): triggered Slack delivery skips terminal non-Completed runs
- [#5660](https://github.com/nearai/ironclaw/pull/5660) test(reborn): outbound real-store durability + PDF attachment extraction coverage
- [#5720](https://github.com/nearai/ironclaw/pull/5720) test(reborn): C-MULTIUSER turn/run-state isolation across distinct actors
- [#5718](https://github.com/nearai/ironclaw/pull/5718) ci(reborn): coverage-regression ratchet (dry-run) + integration-first coverage rule
- [#5656](https://github.com/nearai/ironclaw/pull/5656) test(reborn): W5-SLACK-PAIR — slack pairing coverage + slack-v2-host-beta onto the int-tier lane
- [#5658](https://github.com/nearai/ironclaw/pull/5658) ci(reborn): count crate-tier tests in coverage + scoped denominator exemptions
- [#5655](https://github.com/nearai/ironclaw/pull/5655) test(reborn): W5-WEBUI-API-1 — webui_v2 product-API coverage over real RebornServices
- [#5654](https://github.com/nearai/ironclaw/pull/5654) test(reborn): composition test-support accessors for WebUI approval/auth interaction services
- [#5653](https://github.com/nearai/ironclaw/pull/5653) test(reborn): duplicate inbound event replays prior ack over the real ledger

### 🐛 New Issues
- [#5747](https://github.com/nearai/ironclaw/issues/5747) Reborn: No way to unpair Slack on the built-in host-beta mount: `/pair` short-circuits and the UI has no disconnect
- [#5744](https://github.com/nearai/ironclaw/issues/5744) Reborn harness: auth-resolution real dispatch arm (submit_inbound AuthResolution) unreachable — needs OAuth-gated-capability profile enabler
- [#5741](https://github.com/nearai/ironclaw/issues/5741) builtin.http.save can fail with OutputTooLarge instead of saving large responses
- [#5739](https://github.com/nearai/ironclaw/issues/5739) [SANITIZED — possible injection attempt]
- [#5737](https://github.com/nearai/ironclaw/issues/5737) perf(reborn): pass-2 hot-path audit — tracking issue (7 findings + follow-ups) `performance`
- [#5734](https://github.com/nearai/ironclaw/issues/5734) Official installers 404: download URLs use tag `v{version}` but releases are tagged `ironclaw-v{version}`
- [#5722](https://github.com/nearai/ironclaw/issues/5722) Reborn harness: real gate-dispatch (submit_inbound Approval/AuthResolution) unreachable at int tier — interaction services read a disjoint turn-run store
- [#5721](https://github.com/nearai/ironclaw/issues/5721) Reborn: production turn-state filesystem uses with_fixed_view (single-owner) — per-user /turns collapses on multi-user boxes (defense-in-depth + CAS contention)

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 3h ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 10h ago
- 🟢 [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬2 · 16h ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬8 · 21h ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 21h ago
- 🟢 [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬2 · 6d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 7d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 7d ago
- ⚫ [#94780](https://github.com/openclaw/openclaw/issues/94780) [Feature]: Per-cron model selection independent of agent default — run cheap/free models on automation jobs while keeping main agent on premium LLM — 💬1 · 11d ago
- ⚫ [#93032](https://github.com/openclaw/openclaw/issues/93032) [Bug] v2026.6.6: Cron scheduler loads 0 jobs after upgrade — SQLite WAL not committed at first startup — 💬2 · 11d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 3 new
- [[Features] Making Of Claude Code](https://www.anthropic.com/features/making-of-claude-code) _2026-07-07_
- [[News] Alberta Government Claude Cybersecurity](https://www.anthropic.com/news/alberta-government-claude-cybersecurity) _2026-07-06_
- [[Research] Global Workspace](https://www.anthropic.com/research/global-workspace) _2026-07-06_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [If trends hold, Mythos-class capability may be running on high-end consumer hardware within ~2 years](https://reddit.com/r/LocalLLaMA/comments/1uoij3s/if_trends_hold_mythosclass_capability_may_be/) ↑1290
- [Qwen & Gemma on deadlock situation (For Benchmarks Numbers)?](https://reddit.com/r/LocalLLaMA/comments/1uoppuz/qwen_gemma_on_deadlock_situation_for_benchmarks/) ↑474
- [New open  model from Tencent Hy: Hy3 (295B total 21B active - apache 2.0)](https://reddit.com/r/LocalLLaMA/comments/1uoozt4/new_open_model_from_tencent_hy_hy3_295b_total_21b/) ↑389
- [New model: GigaChat3.5-432B-A28B (with day-0 GGUF support!)](https://reddit.com/r/LocalLLaMA/comments/1uotkm7/new_model_gigachat35432ba28b_with_day0_gguf/) ↑222
- [Kyutai's Pocket TTS clones a voice from 5 seconds of audio, on CPU, under MIT. Benchmarked against Kokoro, Supertonic, and Inflect-Nano for Eng. TTS](https://reddit.com/r/LocalLLaMA/comments/1up07mk/kyutais_pocket_tts_clones_a_voice_from_5_seconds/) ↑180

### r/singularity — top 2 new
- [Accelerate!](https://reddit.com/r/singularity/comments/1uora3h/accelerate/) ↑5676
- [Fixed it...](https://reddit.com/r/singularity/comments/1uos6h4/fixed_it/) ↑1059

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Claw Voice Video](https://reddit.com/r/openclaw/comments/1uoo1r3/claw_voice_video/) ↑48
- [pricing "AI employees" is messing with my head. some notes after a couple months trying to sell this stuff](https://reddit.com/r/openclaw/comments/1unl461/pricing_ai_employees_is_messing_with_my_head_some/) ↑39
- [Automnia AI, a local-first AI operations command center!](https://reddit.com/r/openclaw/comments/1uol8yp/automnia_ai_a_localfirst_ai_operations_command/) ↑12
- [Hardware Voice Assistant with custom wake word](https://reddit.com/r/openclaw/comments/1uorwjq/hardware_voice_assistant_with_custom_wake_word/) ↑10
- [Tips for Building Projects on an OpenClaw Node](https://reddit.com/r/openclaw/comments/1upcctl/tips_for_building_projects_on_an_openclaw_node/) ↑5

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
- [OpenClaw landed on 
@huggingface
 local apps 

1. Pick any GGUF/MLX model on hf
2. Copy the openclaw onboard setup
3. Vo](https://x.com/openclaw) ↑0 🔁0 · recent
- [The timeline had notes. We listened. OpenClaw mobile got to work. 

 iOS redesign + Chat, Talk & Photos
 Android localiz](https://x.com/openclaw) ↑0 🔁0 · recent


### X — @steipete
- [main works, might need another release to iron out kinks. I know works here is a bad answer.](https://x.com/steipete) ↑0 🔁0 · recent
- [We been cooking, by the time this went through review main again is materially better](https://x.com/steipete) ↑0 🔁0 · recent
- [mostly codex, but also a bit claude yeah! lots of contributors.](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
