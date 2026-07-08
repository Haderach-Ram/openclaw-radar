---
layout: post
title: "Ecosystem Digest — 2026-07-08"
date: 2026-07-08 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-07-08
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 382,106 | 4 | 0 | 10 | 0 |
| **hermesagent** | 211,022 | 9 | 2 | 9 | 1 |
| **ZeroClaw** | 32,190 | 9 | 4 | 8 | 0 |
| **IronClaw** | 12,506 | 6 | 4 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 382,106 · **Open issues:** 6,352 · **Last push:** <1h ago

### ✅ Merged PRs
- [#96592](https://github.com/openclaw/openclaw/pull/96592) improve(diagnostics-otel): make agent-duration histograms usable beyond 10s
- [#101959](https://github.com/openclaw/openclaw/pull/101959) refactor(whatsapp): localize internal types
- [#101926](https://github.com/openclaw/openclaw/pull/101926) fix(channels): keep native /think menus responsive
- [#101954](https://github.com/openclaw/openclaw/pull/101954) refactor(matrix): localize internal types
- [#101949](https://github.com/openclaw/openclaw/pull/101949) refactor(feishu): localize internal declarations
- [#101596](https://github.com/openclaw/openclaw/pull/101596) fix(google-meet): handle stdout/stderr stream errors in local audio bridge
- [#101945](https://github.com/openclaw/openclaw/pull/101945) refactor(discord): localize internal declarations
- [#101887](https://github.com/openclaw/openclaw/pull/101887) feat(crestodian): guide providerless model setup
- [#101941](https://github.com/openclaw/openclaw/pull/101941) refactor(gateway): localize terminal helper types
- [#101936](https://github.com/openclaw/openclaw/pull/101936) refactor(imessage): localize internal helper symbols

### 🐛 New Issues
- [#101962](https://github.com/openclaw/openclaw/issues/101962) [Feature]: Streaming Parallel Tool Call Execution (Execute-on-Parse) `enhancement` 💬1
- [#101961](https://github.com/openclaw/openclaw/issues/101961) Agent lane lacks first-class scoped node exec path and stale nodes can hang or fail roughly
- [#101929](https://github.com/openclaw/openclaw/issues/101929) [Bug]: context-overflow-midturn-precheck estimator over-counts ~2.3-2.6x vs billed usage (tool-result chars at 2 chars/token over the untruncated transcript) `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:data-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#101923](https://github.com/openclaw/openclaw/issues/101923) [SANITIZED — possible injection attempt] `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 211,022 · **Open issues:** 26,661 · **Last push:** 1h ago

### 🚀 New Releases
- [v2026.7.7](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.7.7) — Hermes Agent v0.18.1 (2026.7.7)

### ✅ Merged PRs
- [#60595](https://github.com/NousResearch/hermes-agent/pull/60595) chore: release v0.18.1 (2026.7.7)
- [#60571](https://github.com/NousResearch/hermes-agent/pull/60571) Add WhatsApp dashboard pairing flow (salvage of #56748)
- [#60570](https://github.com/NousResearch/hermes-agent/pull/60570) Fix dashboard chat model profile scoping (salvage of #50558)
- [#60589](https://github.com/NousResearch/hermes-agent/pull/60589) [SANITIZED — possible injection attempt]
- [#60585](https://github.com/NousResearch/hermes-agent/pull/60585) feat(dashboard): expose profile names + gateway_mode on gated /api/status
- [#60586](https://github.com/NousResearch/hermes-agent/pull/60586) feat(relay): carry routed profile from the connector wire source
- [#60569](https://github.com/NousResearch/hermes-agent/pull/60569) Dashboard memory provider switching (salvage of #57425)
- [#60576](https://github.com/NousResearch/hermes-agent/pull/60576) fix(dashboard): advertise truecolor to the embedded chat TUI
- [#60577](https://github.com/NousResearch/hermes-agent/pull/60577) fix(delegation): make active config authoritative for delegation limits

### 🐛 New Issues
- [#60635](https://github.com/NousResearch/hermes-agent/issues/60635) fix(qqbot): QQAdapter.connect() missing is_reconnect parameter, crashes on reconnect
- [#60634](https://github.com/NousResearch/hermes-agent/issues/60634) Runs SSE exposes incomplete reasoning compared with session history raw messages
- [#60633](https://github.com/NousResearch/hermes-agent/issues/60633) Desktop: one-tap 👍/👎 on replies that Hermes remembers as a preference (no reply)
- [#60624](https://github.com/NousResearch/hermes-agent/issues/60624) Discord: ffmpeg not auto-discovered on Windows for voice transcription and TTS `type/bug` `comp/plugins` `platform/discord` `P3` `sweeper:risk-platform-windows` `platform/windows` 💬1
- [#60623](https://github.com/NousResearch/hermes-agent/issues/60623) Discord: voice input callback not wired at adapter connect — silent voice until /voice join `type/bug` `comp/gateway` `platform/discord` `P3`
- [#60616](https://github.com/NousResearch/hermes-agent/issues/60616) hermes -z (--oneshot) crashes with SIGABRT after response, only when memory.provider=honcho `type/bug` `comp/cli` `comp/plugins` `tool/memory` `P3` 💬2
- [#60615](https://github.com/NousResearch/hermes-agent/issues/60615) Honcho plugin: contextCadence/dialecticCadence/injectionFrequency ignore host-block values `type/bug` `duplicate` `comp/plugins` `tool/memory` `area/config` `P3` 💬1
- [#60614](https://github.com/NousResearch/hermes-agent/issues/60614) [Bug]: GitHub Copilot ACP shows disconnected in Desktop Accounts despite resolved CLI `type/bug` `comp/acp` `provider/copilot` `P3` `comp/desktop`
- [#60609](https://github.com/NousResearch/hermes-agent/issues/60609) ws_orphan_reap kills gateway-originated sessions, causing Groundhog Day routing loop `type/bug` `comp/gateway` `comp/tui` `P1` `sweeper:risk-session-state` `sweeper:risk-message-delivery`

### 🔒 Closed Issues
- [#60596](https://github.com/NousResearch/hermes-agent/issues/60596) [Bug]:Chat UI alignment issue on Windows: Messages are centered instead of split left-right
- [#60584](https://github.com/NousResearch/hermes-agent/issues/60584) hermes chat -q: _print_exit_summary clears screen + scrollback, destroying the response

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,190 · **Open issues:** 502 · **Last push:** 17h ago

### ✅ Merged PRs
- [#8711](https://github.com/zeroclaw-labs/zeroclaw/pull/8711) refactor(runtime): route Agent::from_config tool assembly through the scoped seam
- [#8737](https://github.com/zeroclaw-labs/zeroclaw/pull/8737) feat(tools): add Bocha AI web search provider
- [#8750](https://github.com/zeroclaw-labs/zeroclaw/pull/8750) test(gateway): make persist-failure & archive-failure injection root-safe (ENOTDIR, not DAC)
- [#8747](https://github.com/zeroclaw-labs/zeroclaw/pull/8747) fix(sop): reject sop_advance on runs parked at a gate (#8678)
- [#8761](https://github.com/zeroclaw-labs/zeroclaw/pull/8761) feat(delegate): give independent delegates the target agent MCP and skill tools
- [#8783](https://github.com/zeroclaw-labs/zeroclaw/pull/8783) fix(deps): bump crossbeam-epoch to 0.9.20 (RUSTSEC-2026-0204)
- [#8755](https://github.com/zeroclaw-labs/zeroclaw/pull/8755) chore(runtime/shell): drop phantom audit citation from SSRF guard comment
- [#8774](https://github.com/zeroclaw-labs/zeroclaw/pull/8774) feat(zerocode): add ctrl-w word delete

### 🐛 New Issues
- [#8810](https://github.com/zeroclaw-labs/zeroclaw/issues/8810) [Bug]: Documentation is wrong - Telegram example `bug`
- [#8804](https://github.com/zeroclaw-labs/zeroclaw/issues/8804) bug: skills prompt advertises a callable-tool set that doesn't match the registry (mcp missing, target-less elevation over-listed)
- [#8803](https://github.com/zeroclaw-labs/zeroclaw/issues/8803) [Feature]: Collapse a completed turn's intermediate steps into a single group in the web dashboard chat
- [#8800](https://github.com/zeroclaw-labs/zeroclaw/issues/8800) [Bug]: Windows: killed zeroclaw process leaves port bound (zombie LISTENING/CLOSE_WAIT), new daemon fails to start 💬1
- [#8798](https://github.com/zeroclaw-labs/zeroclaw/issues/8798) RFC: Consolidate /ws/chat and /acp onto a single wire protocol
- [#8797](https://github.com/zeroclaw-labs/zeroclaw/issues/8797) [Bug]: bind-telegram setup instructions reference an unknown configuration property `bug` 💬1
- [#8794](https://github.com/zeroclaw-labs/zeroclaw/issues/8794) [Bug]: [web dashboard ui] stopping the agent mid work erases the tool calls and his thinking from the context `bug`
- [#8792](https://github.com/zeroclaw-labs/zeroclaw/issues/8792) [Bug]: Left sidebar is missing a Skills navigation entry
- [#8791](https://github.com/zeroclaw-labs/zeroclaw/issues/8791) [Bug]: Left sidebar has incorrect width causing horizontal scrollbar

### 🔒 Closed Issues
- [#8815](https://github.com/zeroclaw-labs/zeroclaw/issues/8815) [Feature]: skill_manage.create action so agents can save new skills as bundles, not loose .md files
- [#6970](https://github.com/zeroclaw-labs/zeroclaw/issues/6970) [Tracker]: v0.8.1 integration/channel/provider/tool queue and history
- [#8678](https://github.com/zeroclaw-labs/zeroclaw/issues/8678) [SANITIZED — possible injection attempt]
- [#8782](https://github.com/zeroclaw-labs/zeroclaw/issues/8782) fix(audit): bump crossbeam-epoch 0.9.18 -> 0.9.20 to clear RUSTSEC-2026-0204

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,506 · **Open issues:** 1,347 · **Last push:** <1h ago

### ✅ Merged PRs
- [#5751](https://github.com/nearai/ironclaw/pull/5751) fix(filesystem): pool libSQL connections to stop concurrent-CAS SQLITE_MISUSE (#5466)
- [#5661](https://github.com/nearai/ironclaw/pull/5661) test(reborn): CAS-contention + discard-tombstone coverage; fix #5467 InMemory store parity
- [#5728](https://github.com/nearai/ironclaw/pull/5728) [codex] Fix WebUI frontend generated ignores
- [#5774](https://github.com/nearai/ironclaw/pull/5774) fix(reborn): preserve model outage failure category
- [#5771](https://github.com/nearai/ironclaw/pull/5771) chore: update IronLoop network access config
- [#5709](https://github.com/nearai/ironclaw/pull/5709) refactor(composition): group llm-admin cluster under llm_admin/ (dissection n6)
- [#5686](https://github.com/nearai/ironclaw/pull/5686) refactor(composition): group product-auth cluster under product_auth/ (dissection n4)
- [#5725](https://github.com/nearai/ironclaw/pull/5725) [HST Postgres v2 2/4] Add row-store turn state
- [#5685](https://github.com/nearai/ironclaw/pull/5685) feat(reborn): localize shell, chat, and extensions UI
- [#5724](https://github.com/nearai/ironclaw/pull/5724) [HST Postgres v2 1/4] RootFilesystem latency substrate

### 🐛 New Issues
- [#5788](https://github.com/nearai/ironclaw/issues/5788) Daily ironclaw failure taxonomy — 2026-07-08
- [#5787](https://github.com/nearai/ironclaw/issues/5787) flaky: slack_pairing_redeem_rejects_expired_code — paused tokio clock vs chrono wall-clock TTL race
- [#5786](https://github.com/nearai/ironclaw/issues/5786) Expose OpenRouter upstream provider on ToolCompletionResponse
- [#5776](https://github.com/nearai/ironclaw/issues/5776) Long-output prompt causes repeated model timeouts, degraded into generic "invalid result" error `bug_bash_P2` 💬1
- [#5770](https://github.com/nearai/ironclaw/issues/5770) Improve Reborn tool permission selects with a custom dropdown
- [#5768](https://github.com/nearai/ironclaw/issues/5768) Reborn Projects page has incomplete i18n coverage

### 🔒 Closed Issues
- [#5795](https://github.com/nearai/ironclaw/issues/5795) placeholder
- [#5466](https://github.com/nearai/ironclaw/issues/5466) Parallel same-tenant turn-runs vs FilesystemTurnStateStore CAS / libsql backend (~10% failure)
- [#5467](https://github.com/nearai/ironclaw/issues/5467) In-memory ApprovalRequestStore::discard_pending diverges from filesystem (no tombstone → id reuse allowed)
- [#3083](https://github.com/nearai/ironclaw/issues/3083) User Management allows duplicate user creation due to missing loading state and submission debounce

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬6 · 17h ago
- 🟢 [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬3 · 20h ago
- 🟢 [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬2 · 21h ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬9 · 21h ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 1d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 1d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 1d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 8d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 8d ago
- ⚫ [#94780](https://github.com/openclaw/openclaw/issues/94780) [Feature]: Per-cron model selection independent of agent default — run cheap/free models on automation jobs while keeping main agent on premium LLM — 💬1 · 12d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 1 new
- [[Index] Australian Payments Plus](https://openai.com/index/australian-payments-plus/) _2026-07-07_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [So... anyone copped one of these?](https://reddit.com/r/LocalLLaMA/comments/1up9x38/so_anyone_copped_one_of_these/) ↑1848
- [Beijing IS NOT looking at curbing overseas access to China's top AI models (Debunking the Reuters report)](https://reddit.com/r/LocalLLaMA/comments/1upvw37/beijing_is_not_looking_at_curbing_overseas_access/) ↑750
- [Beijing is looking at curbing overseas access to China's top AI models (Reuters)](https://reddit.com/r/LocalLLaMA/comments/1uprmso/beijing_is_looking_at_curbing_overseas_access_to/) ↑429
- [I tested Anthropic’s new Jacobian Lens on open models, then it turned into a local-model hallucination router](https://reddit.com/r/LocalLLaMA/comments/1upy31x/i_tested_anthropics_new_jacobian_lens_on_open/) ↑302
- [nvidia/NVIDIA-Nemotron-Labs-3-Puzzle-75B-A9B-BF16 · Hugging Face](https://reddit.com/r/LocalLLaMA/comments/1upsdmi/nvidianvidianemotronlabs3puzzle75ba9bbf16_hugging/) ↑267

### r/singularity — top 5 new
- [Anthropic just reported that LLMs have hidden thoughts they hold without saying. An internal ”J-Space”](https://reddit.com/r/singularity/comments/1uptvgb/anthropic_just_reported_that_llms_have_hidden/) ↑631
- [China is considering restricting overseas access to its top AI models, including open-weight ones](https://reddit.com/r/singularity/comments/1upt58s/china_is_considering_restricting_overseas_access/) ↑581
- [Anthropic extending Fable 5 for paid users till 12 july](https://reddit.com/r/singularity/comments/1uq27uy/anthropic_extending_fable_5_for_paid_users_till/) ↑536
- [Google is definitely cooking som good if these leaks are true](https://reddit.com/r/singularity/comments/1upnqtx/google_is_definitely_cooking_som_good_if_these/) ↑442
- [A global workspace in language models: New interpretability findings by Anthropic](https://reddit.com/r/singularity/comments/1up68u3/a_global_workspace_in_language_models_new/) ↑281

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Deployed an enterprise version of Openclaw for internal use. average total monthly spend 50k](https://reddit.com/r/openclaw/comments/1uq47fj/deployed_an_enterprise_version_of_openclaw_for/) ↑8
- [Using fable to audit openclaw](https://reddit.com/r/openclaw/comments/1uqezau/using_fable_to_audit_openclaw/) ↑3
- [Radio Free Gemma](https://reddit.com/r/openclaw/comments/1uqekb4/radio_free_gemma/) ↑3
- [How do you write tools for openclaw?](https://reddit.com/r/openclaw/comments/1upz9yr/how_do_you_write_tools_for_openclaw/) ↑3
- [Which way do you interact and use openclaw?](https://reddit.com/r/openclaw/comments/1upz1o8/which_way_do_you_interact_and_use_openclaw/) ↑3

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
- [Tencent Hy3 from 
@TencentHunyuan
 is free on 
@OpenRouter
 through July 21.

295B MoE, 256K context, built for coding, ](https://x.com/openclaw) ↑0 🔁0 · recent


### X — @steipete
- [If you run this workflow, ask Fable to make codex the workhorse. 
https://
github.com/steipete/agent
-scripts/blob/main/](https://x.com/steipete) ↑0 🔁0 · recent
- [Bonus: Comes with a skill to show a big alert when agents need your help for additional context, instead of (e.g.) just ](https://x.com/steipete) ↑0 🔁0 · recent
- [gotta](https://x.com/steipete) ↑0 🔁0 · recent
- [I often work in multiple machines at the same time and started to mix up the screen shares, so built nameplate to make t](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
