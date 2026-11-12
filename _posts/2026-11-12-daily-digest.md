---
layout: post
title: "Ecosystem Digest — 2026-11-12"
date: 2026-11-12 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-12
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 394,369 | 8 | 4 | 10 | 1 |
| **hermesagent** | 262,749 | 6 | 0 | 10 | 0 |
| **ZeroClaw** | 33,331 | 5 | 0 | 2 | 1 |
| **IronClaw** | 12,714 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,952 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 394,369 · **Open issues:** 8,090 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.11.5-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.11.5-beta.2) — openclaw 2026.11.5-beta.2

### ✅ Merged PRs
- [#197457](https://github.com/openclaw/openclaw/pull/197457) fix: shorten Gateway restart when active commands need cleanup
- [#197458](https://github.com/openclaw/openclaw/pull/197458) fix(ui): keep macOS font smoothing for chat text in sans-serif themes
- [#197428](https://github.com/openclaw/openclaw/pull/197428) refactor(update): reuse canonical path resolution
- [#197447](https://github.com/openclaw/openclaw/pull/197447) fix(ui): prevent cold-render chat activity test flakes
- [#197315](https://github.com/openclaw/openclaw/pull/197315) fix(cron): cancel interrupted status and history reads
- [#195782](https://github.com/openclaw/openclaw/pull/195782) fix(android): session catalog stays disabled after cancelling continuation
- [#192614](https://github.com/openclaw/openclaw/pull/192614) refactor(gateway): isolate agent text pacing
- [#196952](https://github.com/openclaw/openclaw/pull/196952) fix(ui): skip cache policy reads for private requests
- [#197431](https://github.com/openclaw/openclaw/pull/197431) fix(ci): report state-worker timing when the SIGUSR2 shutdown proof stalls
- [#196927](https://github.com/openclaw/openclaw/pull/196927) fix(agents): collect process results at suspended-run capacity

### 🐛 New Issues
- [#197463](https://github.com/openclaw/openclaw/issues/197463) [Feature]: Optional inline command trail in the Control UI
- [#197454](https://github.com/openclaw/openclaw/issues/197454) [Bug]: a delayed question answer can resolve a recreated question with the same ID `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#197452](https://github.com/openclaw/openclaw/issues/197452) [Feature]: Explicit, bounded Deep Research selection in chat `enhancement` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:linked-pr-open` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1
- [#197450](https://github.com/openclaw/openclaw/issues/197450) Add optional claim, execution-observation, and verification records to Workboard results `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1
- [#197443](https://github.com/openclaw/openclaw/issues/197443) Support restart-surviving durable exec and owning-session completion wakeups on macOS `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:other` 💬1
- [#197442](https://github.com/openclaw/openclaw/issues/197442) Allow `sessions_spawn` to target a named paired device `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1
- [#197437](https://github.com/openclaw/openclaw/issues/197437) [Bug]:Windows: managed GitHub identity blocks every exec ("credential is unavailable or insecure") `bug` `regression` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `impact:auth-provider` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#197430](https://github.com/openclaw/openclaw/issues/197430) [Bug]: 2026.11.3 usage-cost refresh still exhausts worker heap with bounded SQLite reader already present `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1

### 🔒 Closed Issues
- [#159638](https://github.com/openclaw/openclaw/issues/159638) Gateway boots ~7 short-lived SQLite store/read workers per minute (512 MB each), keeping V8 threads at ~80% CPU
- [#195759](https://github.com/openclaw/openclaw/issues/195759) Android: NodeRuntime.continueSessionCatalogEntryFromGateway leaves continuingEntryId busy state set when caller is cancelled
- [#166634](https://github.com/openclaw/openclaw/issues/166634) [Bug]: Late reclamation commit checkpoint failure leaves agent unavailable after crash recovery
- [#197444](https://github.com/openclaw/openclaw/issues/197444) [Bug]: Update rehearsal strips OPENCLAW_GATEWAY_TOKEN but keeps gateway.remote, so an env SecretRef in gateway.remote.token fails candidate-gateway-startup ("required secrets are unavailable")

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬81 · 6h ago
- [#116201](https://github.com/openclaw/openclaw/issues/116201) Realtime voice work can retain unbounded provider and consult state — 💬59 · 40d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 262,749 · **Open issues:** 54,149 · **Last push:** <1h ago

### ✅ Merged PRs
- [#154171](https://github.com/NousResearch/hermes-agent/pull/154171) fix(catalog): every PR's Repository guards job passes again (board-insights.yaml stored with LF)
- [#153672](https://github.com/NousResearch/hermes-agent/pull/153672) feat(plugin-catalog): update postkitty to 1.0.1
- [#153490](https://github.com/NousResearch/hermes-agent/pull/153490) feat(plugin-catalog): add read-once plugin
- [#153331](https://github.com/NousResearch/hermes-agent/pull/153331) docs(plugin-catalog): bump apinex sha for README links and set docs_url
- [#153191](https://github.com/NousResearch/hermes-agent/pull/153191) fix(plugin-catalog): update doc-markdown to e776b16
- [#153605](https://github.com/NousResearch/hermes-agent/pull/153605) feat(plugin-catalog): add treasury-cash-forecast
- [#153408](https://github.com/NousResearch/hermes-agent/pull/153408) feat(plugin-catalog): add mayar
- [#153407](https://github.com/NousResearch/hermes-agent/pull/153407) feat(plugin-catalog): add asyntai plugin
- [#153193](https://github.com/NousResearch/hermes-agent/pull/153193) catalog(vibecad): update hermes-r0b0t-vibecad to v0.4.1
- [#153106](https://github.com/NousResearch/hermes-agent/pull/153106) plugin-catalog: update hermes-kame-api-rotation + hermes-kame-provider to 1.8.4.1

### 🐛 New Issues
- [#154196](https://github.com/NousResearch/hermes-agent/issues/154196) [Feature]: /new in long-lived gateway chats: "Conversation started" should reflect the reset boundary (opt-in flag) `type/feature` `comp/agent` `P3` `area/sessions`
- [#154195](https://github.com/NousResearch/hermes-agent/issues/154195) [Bug]: Telegram adapter does not support clarify tool's multi_select (resolves on first button tap) `type/bug` `comp/plugins` `platform/telegram` `P2`
- [#154192](https://github.com/NousResearch/hermes-agent/issues/154192) Sessions moved from a Windows install to macOS/Linux fail every Desktop control with "storage unavailable" (restore_policy rejects C:\ cwd) `type/bug` `comp/gateway` `P2` `area/sessions`
- [#154187](https://github.com/NousResearch/hermes-agent/issues/154187) fix(cli): config startup warnings write ANSI SGR into a non-TTY stderr `type/bug` `comp/cli` `P3`
- [#154180](https://github.com/NousResearch/hermes-agent/issues/154180) [Bug]: Telegram group replay moves an addressed turn into passive observations `type/bug` `comp/gateway` `P2` `area/sessions`
- [#154175](https://github.com/NousResearch/hermes-agent/issues/154175) [Feature]: Public auth guard for dashboard plugin routes (avoid private _require_token import) `type/security` `comp/cli` `area/auth` `P3` `comp/dashboard`

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,331 · **Open issues:** 1,197 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.9.0](https://github.com/zeroclaw-labs/zeroclaw/releases/tag/v0.9.0) — v0.9.0

### ✅ Merged PRs
- [#12380](https://github.com/zeroclaw-labs/zeroclaw/pull/12380) chore(docs): pin translations to v0.9.0
- [#12392](https://github.com/zeroclaw-labs/zeroclaw/pull/12392) fix(deps): bump rustix to 1.1.6 for RUSTSEC-2026-0486

### 🐛 New Issues
- [#12397](https://github.com/zeroclaw-labs/zeroclaw/issues/12397) [Feature]: Distinguish agent task outcome from cron execution status `enhancement` 💬1
- [#12396](https://github.com/zeroclaw-labs/zeroclaw/issues/12396) [Bug]: history_pruning.keep_recent and collapse_tool_results are dead config knobs (no readers since #8196)
- [#12394](https://github.com/zeroclaw-labs/zeroclaw/issues/12394) [Feature]: Bound a SOP step agent's tool ceiling to the registry it holds, and pin the seal's deferred-MCP input
- [#12391](https://github.com/zeroclaw-labs/zeroclaw/issues/12391) [Bug]: runtime-trace.jsonl loses hours of events across daemon restarts (handoff buffer / queue drops / silent writer) 💬1
- [#12390](https://github.com/zeroclaw-labs/zeroclaw/issues/12390) shell tool returns empty error string on non-zero exit (stderr swallowed)

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,714 · **Open issues:** 1,571 · **Last push:** 2d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,952 · **Open issues:** 121 · **Last push:** 19d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬3 · 3d ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 9d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 18d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 37d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 45d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 47d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 57d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 65d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 67d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 75d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 3 new
- [[Index] Singapore Airlines Travel Work](https://openai.com/index/singapore-airlines-travel-work/) _2026-11-12_
- [[Index] Jiostar Vijay Seshadri](https://openai.com/index/jiostar-vijay-seshadri/) _2026-11-12_
- [[Index] Chatgpt Plus For Veterans](https://openai.com/index/chatgpt-plus-for-veterans/) _2026-11-11_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [Nvidia is Preparing to Oust Nvidia CEO Jensen Huang](https://reddit.com/r/LocalLLaMA/comments/1xtvsi7/nvidia_is_preparing_to_oust_nvidia_ceo_jensen/) ↑659
- [Open source self driving is here!](https://reddit.com/r/LocalLLaMA/comments/1xtmeif/open_source_self_driving_is_here/) ↑413

### r/singularity — top 2 new
- [Ts is too funny](https://reddit.com/r/singularity/comments/1xtjj5g/ts_is_too_funny/) ↑1897
- [A second affair has hit the Jensen](https://reddit.com/r/singularity/comments/1xtvbqj/a_second_affair_has_hit_the_jensen/) ↑657

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Claude Fable 5.2 from Anthropic is now available in OpenClaw.](https://reddit.com/r/openclaw/comments/1xtltcd/claude_fable_52_from_anthropic_is_now_available/) ↑22
- [OpenClaw v2026.11.3 patch fixes update recovery and backup timeouts](https://reddit.com/r/openclaw/comments/1xt7zlb/openclaw_v2026113_patch_fixes_update_recovery_and/) ↑21
- [been adding more skills to our OpenClaw agent, what else should i try? been messing around with our OpenClaw setup lately and trying to make it do more useful stuff without connecting 15 different ser](https://reddit.com/r/openclaw/comments/1xslj9l/been_adding_more_skills_to_our_openclaw_agent/) ↑2
- [Running without a sandbox](https://reddit.com/r/openclaw/comments/1xu04yp/running_without_a_sandbox/) ↑1
- [I added a Free Model Pool with tool-call verification and auto-failover that plugs directly into OpenClaw (relay-ai update)](https://reddit.com/r/openclaw/comments/1xstiwd/i_added_a_free_model_pool_with_toolcall/) ↑1

### X — @openclaw
- [Claude Fable 5.2 from 
@claudeai
 is now available in OpenClaw.

Anthropic reports up to 30% faster output generation th](https://x.com/openclaw/status/2120550160128467398) ↑0 🔁0 · recent
- [OpenClaw v2026.11.3 patch is out 🦞

🔄 Fixes interrupted-update recovery
💾 Fewer slow-storage backup timeouts
🔒 Fixes cre](https://x.com/openclaw/status/2120368851846381911) ↑0 🔁0 · recent


### X — @steipete
_No new tweets since the last digest. Most recent:_
- ["When the company ran diagnostics on about 700 systems, it found 10,500 vulnerabilities and held an emergency press conf](https://x.com/steipete/status/2120228665946710248)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
