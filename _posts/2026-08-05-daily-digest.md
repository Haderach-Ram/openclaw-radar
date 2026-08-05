---
layout: post
title: "Ecosystem Digest — 2026-08-05"
date: 2026-08-05 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-08-05
*Generated 07:47 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 385,150 | 10 | 6 | 10 | 0 |
| **hermesagent** | 225,542 | 15 | 2 | 3 | 0 |
| **ZeroClaw** | 32,505 | 11 | 2 | 5 | 0 |
| **IronClaw** | 12,588 | 12 | 2 | 10 | 0 |
| **Moltis** | 2,807 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 385,150 · **Open issues:** 5,526 · **Last push:** <1h ago

### ✅ Merged PRs
- [#117550](https://github.com/openclaw/openclaw/pull/117550) fix(model-picker): preserve compatible auth profiles
- [#119396](https://github.com/openclaw/openclaw/pull/119396) fix(qa): stop zombie-only gateway process groups
- [#119150](https://github.com/openclaw/openclaw/pull/119150) fix(qa): repair release validation scenarios
- [#118787](https://github.com/openclaw/openclaw/pull/118787) fix(ui): clear split-pane questions after answers and cancellations
- [#119373](https://github.com/openclaw/openclaw/pull/119373) fix(slack): Fix bad escaping in slack tool commentary
- [#118736](https://github.com/openclaw/openclaw/pull/118736) fix(slack): authorize reaction and message reads before applying limits
- [#119381](https://github.com/openclaw/openclaw/pull/119381) fix(ci): isolate Vitest cache warmer configs
- [#117034](https://github.com/openclaw/openclaw/pull/117034) feat(audit): add execution identity inspection
- [#119363](https://github.com/openclaw/openclaw/pull/119363) fix(fs): adopt fs-safe 0.5.2 untrusted filename sanitization
- [#119380](https://github.com/openclaw/openclaw/pull/119380) fix(ci): preserve release evidence across reruns

### 🐛 New Issues
- [#119411](https://github.com/openclaw/openclaw/issues/119411) [Bug]: memory file watcher never reindexes, and `memory status` reports `Dirty: no` while indexed count is below on-disk count
- [#119407](https://github.com/openclaw/openclaw/issues/119407) [Bug]: same-run terminal lifecycle event is dropped as stale, leaving successful sessions running `bug` `maintainer` `P1` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` `maturity:stable` 💬2
- [#119404](https://github.com/openclaw/openclaw/issues/119404) Compaction: reserveTokensFloor (input budget) is reused as the summarization output cap, inflating per-chunk maxTokens ~16x over the 16k summary cap `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#119401](https://github.com/openclaw/openclaw/issues/119401) [Bug]: Direct/DM NO_REPLY suppression is unconditional and ignores silentReply policy — no way to force visible replies on small/local models `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#119393](https://github.com/openclaw/openclaw/issues/119393) Bundled skills reference files that no longer exist: openclaw-refactor-docs points at a skill removed in 0dabb70 `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#119387](https://github.com/openclaw/openclaw/issues/119387) System-agent UI approval reruns the model instead of applying the exact frozen operation `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#119386](https://github.com/openclaw/openclaw/issues/119386) [Bug]: Active Memory QA trace counts unrelated heartbeat requests `bug` `maintainer` `P2` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬2
- [#119385](https://github.com/openclaw/openclaw/issues/119385) [Bug]: Active Memory QA doctor migration times out under catalog concurrency `bug` `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#119383](https://github.com/openclaw/openclaw/issues/119383) [Bug]: final NO_REPLY is rewritten into the sessions_send body and delivered to the user's channel `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#119382](https://github.com/openclaw/openclaw/issues/119382) [Bug]: WhatsApp durable ingress lane hold starves inbound debounce — same-chat bursts never merge and each message pays the full window `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬3

### 🔒 Closed Issues
- [#92244](https://github.com/openclaw/openclaw/issues/92244) [SANITIZED — possible injection attempt]
- [#119405](https://github.com/openclaw/openclaw/issues/119405) sessions.compact --max-lines can hang indefinitely and silently on the exclusive session-store lock (LLM-free rescue path is unbounded)
- [#117994](https://github.com/openclaw/openclaw/issues/117994) [Bug]: Gateway agent timeout consumes internal execution queue wait
- [#92013](https://github.com/openclaw/openclaw/issues/92013) Active Memory `queryMode: "message"` can receive full assembled request envelopes; needs latest-message cap or slim-intent field
- [#105676](https://github.com/openclaw/openclaw/issues/105676) [Enhancement] Prepared Statement Compilation Overhead in executeCompiledSqliteQuerySync (Kysely Sync Facade)
- [#101446](https://github.com/openclaw/openclaw/issues/101446) Dropdown model switch to claude-cli causes "reply session initialization conflicted" on follow-up turns

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬116 · 3d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 225,542 · **Open issues:** 27,950 · **Last push:** 1h ago

### ✅ Merged PRs
- [#78976](https://github.com/NousResearch/hermes-agent/pull/78976) fix(git): kill the whole probe process tree on timeout (port of openai/codex#36793)
- [#77934](https://github.com/NousResearch/hermes-agent/pull/77934) test(install): prove updating from a release reaches this commit
- [#78909](https://github.com/NousResearch/hermes-agent/pull/78909) A model id missing its provider prefix says so instead of 404ing

### 🐛 New Issues
- [#79030](https://github.com/NousResearch/hermes-agent/issues/79030) [SANITIZED — possible injection attempt] `type/security` `comp/tools` `tool/terminal` `tool/file` `area/config` `P3` `sweeper:risk-security-boundary` `sweeper:risk-compatibility`
- [#79029](https://github.com/NousResearch/hermes-agent/issues/79029) Desktop session sidebar shows empty after `hermes update` until a new message triggers a session event `type/bug` `P3` `sweeper:risk-session-state` `sweeper:risk-compatibility` `comp/desktop` `area/sessions` `area/install-update` `area/profiles`
- [#79026](https://github.com/NousResearch/hermes-agent/issues/79026) Wake word completely non-functional on macOS ARM64 (Apple Silicon) — both engines fail `type/bug` `tool/tts` `P3` `needs-repro`
- [#79023](https://github.com/NousResearch/hermes-agent/issues/79023) codex_app_server migration duplicates unmanaged MCP tables and lacks a supported noninteractive entry point `type/bug` `comp/cli` `tool/mcp` `provider/openai` `area/config` `P2`
- [#79021](https://github.com/NousResearch/hermes-agent/issues/79021) Fix npm dependency vulnerabilities reported by hermes doctor `type/bug` `comp/cli` `comp/tui` `tool/browser` `P2` `area/install-update` 💬1
- [#79017](https://github.com/NousResearch/hermes-agent/issues/79017) prompt_cache_key loses continuity across context-compression session rotation (needs a logical cache-scope concept) `type/bug` `comp/agent` `provider/openai` `P0` `sweeper:risk-caching` `area/compression` 💬1
- [#79015](https://github.com/NousResearch/hermes-agent/issues/79015) x-grok-conv-id unstable across cron re-fires of the same job (native xAI Responses and OpenRouter) `type/bug` `comp/agent` `comp/cron` `comp/plugins` `provider/openrouter` `provider/xai` `P0` `sweeper:risk-caching`
- [#79014](https://github.com/NousResearch/hermes-agent/issues/79014) [SANITIZED — possible injection attempt] `type/bug` `comp/agent` `provider/xai` `P0` `sweeper:risk-caching`
- [#79013](https://github.com/NousResearch/hermes-agent/issues/79013) Codex session_id/x-client-request-id headers diverge from body prompt_cache_key, and session_id header lost physical identity `type/bug` `comp/agent` `provider/openai` `P2` `sweeper:risk-caching`
- [#79012](https://github.com/NousResearch/hermes-agent/issues/79012) Auxiliary Codex calls (compression/flush_memories/MoA/session_search) still derive prompt_cache_key content-only, no session scope `type/bug` `comp/agent` `provider/openai` `P0` `sweeper:risk-caching` `area/compression`
- [#79006](https://github.com/NousResearch/hermes-agent/issues/79006) Early-adopter feedback: what the current velocity costs downstream (3 local patches and counting) `type/feature` `tool/file` `tool/skills` `P3` `needs-decision` `comp/desktop` `area/install-update`
- [#79005](https://github.com/NousResearch/hermes-agent/issues/79005) [Bug]: Desktop profile swap can route session.create to the wrong backend — cross-profile state.db pollution `type/bug` `P2` `sweeper:risk-session-state` `comp/desktop` `area/sessions` `area/profiles`
- [#79004](https://github.com/NousResearch/hermes-agent/issues/79004) [Bug]: Curator background-review marks silently empty on worker threads (ContextVar lost) — affects the #69505 fix too `type/bug` `comp/agent` `tool/skills` `P3`
- [#79003](https://github.com/NousResearch/hermes-agent/issues/79003) [Bug]: Desktop — new chat from the all-profiles view always targets the startup profile, with no visible indication `type/bug` `P3` `sweeper:risk-session-state` `comp/desktop` `area/sessions` `area/profiles`
- [#79002](https://github.com/NousResearch/hermes-agent/issues/79002) [Bug]: Desktop focus mode — closing the active terminal tab freezes the view and the tab bar disappears `type/bug` `P3` `needs-decision` `comp/desktop`

### 🔒 Closed Issues
- [#18594](https://github.com/NousResearch/hermes-agent/issues/18594) [Bug]: get_hermes_home() silently falls back to ~/.hermes in profile mode and causes cross-profile data corruption
- [#12682](https://github.com/NousResearch/hermes-agent/issues/12682) TUI mode crashes with "JavaScript heap out of memory" after prolonged use

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,505 · **Open issues:** 721 · **Last push:** 2h ago

### ✅ Merged PRs
- [#9569](https://github.com/zeroclaw-labs/zeroclaw/pull/9569) fix(gateway): fail closed when a WhatsApp Cloud or Linq webhook cannot be verified
- [#9625](https://github.com/zeroclaw-labs/zeroclaw/pull/9625) fix(zerocode): allow selection drags from side whitespace
- [#9603](https://github.com/zeroclaw-labs/zeroclaw/pull/9603) fix(config): preserve Ollama dev template contracts
- [#9689](https://github.com/zeroclaw-labs/zeroclaw/pull/9689) fix(infra): make JSONL session rewrites atomic
- [#9430](https://github.com/zeroclaw-labs/zeroclaw/pull/9430) chore(deps): bump stagex/pallet-nodejs from `81bc04b` to `5c96b25`

### 🐛 New Issues
- [#9756](https://github.com/zeroclaw-labs/zeroclaw/issues/9756) [Bug]: daemon startup prints multiple independent Telegram pairing codes with no way to tell which is live
- [#9736](https://github.com/zeroclaw-labs/zeroclaw/issues/9736) runtime: RPC prompt path never writes persisted SessionState (idle/running/error) `bug`
- [#9735](https://github.com/zeroclaw-labs/zeroclaw/issues/9735) zerocode: keyboard navigation for agent sidebar rows `enhancement`
- [#9734](https://github.com/zeroclaw-labs/zeroclaw/issues/9734) zerocode: lazy background session rehydration on reconnect `enhancement`
- [#9733](https://github.com/zeroclaw-labs/zeroclaw/issues/9733) rpc: push a session/closed notification when the daemon drops a session `enhancement`
- [#9732](https://github.com/zeroclaw-labs/zeroclaw/issues/9732) rpc: structured failure reason on TurnComplete instead of sentinel string-matching `enhancement`
- [#9731](https://github.com/zeroclaw-labs/zeroclaw/issues/9731) zerocode: move Quickstart from the mode bar into the sidebar `enhancement`
- [#9730](https://github.com/zeroclaw-labs/zeroclaw/issues/9730) zerocode: agent sidebar with status dots, add-picker, and click-to-switch `enhancement`
- [#9729](https://github.com/zeroclaw-labs/zeroclaw/issues/9729) zerocode: track multiple concurrent live sessions per chat pane `enhancement`
- [#9728](https://github.com/zeroclaw-labs/zeroclaw/issues/9728) rpc: session/new needs an opt-out from idle-sibling eviction `enhancement`
- [#9727](https://github.com/zeroclaw-labs/zeroclaw/issues/9727) Epic: run and monitor multiple agents from a zerocode sidebar `enhancement`

### 🔒 Closed Issues
- [#8568](https://github.com/zeroclaw-labs/zeroclaw/issues/8568) [Feature]: Mixture-of-Agents (MoA) virtual model provider
- [#9630](https://github.com/zeroclaw-labs/zeroclaw/issues/9630) [Bug]: ZeroCode transcript selection cannot start from side whitespace

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,588 · **Open issues:** 1,516 · **Last push:** <1h ago

### ✅ Merged PRs
- [#7167](https://github.com/nearai/ironclaw/pull/7167) fix(ci): unbreak per-package clippy on bin-only crates; classify `.gitignore`
- [#7200](https://github.com/nearai/ironclaw/pull/7200) fix(composition): stop icacls writing to the CLI's stdout on Windows
- [#7197](https://github.com/nearai/ironclaw/pull/7197) ci: pass the Windows identity variables to the release smoke
- [#7170](https://github.com/nearai/ironclaw/pull/7170) Waves 0–4 batch: WS3/WS4 consolidation + lane governor port + conversations sever + WS10 inventory keying + enforcement gates
- [#7188](https://github.com/nearai/ironclaw/pull/7188) ci: quote the Windows test filter so the workflow file parses
- [#7182](https://github.com/nearai/ironclaw/pull/7182) fix(filesystem): skip the parent-directory fsync on Windows
- [#7173](https://github.com/nearai/ironclaw/pull/7173) ci: move coverage to main CI — PR and merge-queue lanes run uninstrumented (Ben+Firat decision)
- [#7158](https://github.com/nearai/ironclaw/pull/7158) docs(target-arch): truth pass — tick the done WS1 eviction row, de-rot three stale prose sites, drop host_api's dead tokio dep
- [#7139](https://github.com/nearai/ironclaw/pull/7139) refactor(ws6): consolidate the six Wave 4 PRs into one (#7124, #7117, #7106, #7099, #7101, #7128)
- [#7058](https://github.com/nearai/ironclaw/pull/7058) fix(projects): enable lifecycle deletion with E2E coverage

### 🐛 New Issues
- [#7199](https://github.com/nearai/ironclaw/issues/7199) Suggestion for ironclaw
- [#7194](https://github.com/nearai/ironclaw/issues/7194) feat(outbound): make an admin-allowed shared channel addressable as an outbound delivery target `enhancement` `size: M` `risk: high` `scope: extensions` 💬2
- [#7193](https://github.com/nearai/ironclaw/issues/7193) feat(automations): add run-now (manual fire) across trigger domain, product surface, capability, and WebUI `enhancement` `size: L` `risk: medium` `scope: agent` 💬2
- [#7192](https://github.com/nearai/ironclaw/issues/7192) fix(webui): anchor optimistic user messages so they stop rendering below the agent's output `bug` `size: M` `risk: low` `scope: channel/web` 💬2
- [#7191](https://github.com/nearai/ironclaw/issues/7191) fix(builtin.time): add relative-offset arithmetic and replace opaque input_error() with typed input issues `bug` `size: M` `risk: medium` `scope: tool/builtin` 💬2
- [#7185](https://github.com/nearai/ironclaw/issues/7185) Memory not reliably recalled across conversations `bug` `scope: workspace` `feedback`
- [#7183](https://github.com/nearai/ironclaw/issues/7183) Feature request: per-user LLM model selection (currently admin-only) `enhancement` `scope: llm` `scope: config`
- [#7180](https://github.com/nearai/ironclaw/issues/7180) Web scraping is hit-or-miss: agent uses http tool instead of web_search for data retrieval `bug` `scope: tool` `feedback`
- [#7178](https://github.com/nearai/ironclaw/issues/7178) Make the 1.0.0-rc.1 → 1.1.0-rc.1 startup migration lossless `v1.1.0`
- [#7177](https://github.com/nearai/ironclaw/issues/7177) Improve deferred tool retrieval with schema-aware ranked search `enhancement` `size: M` `risk: medium` `scope: agent` `scope: tool` `scope: evaluation` `suggested_P2` `reborn` `performance` 💬1
- [#7166](https://github.com/nearai/ironclaw/issues/7166) Tool disclosure follow-up `epic` `v1.2.0`
- [#7165](https://github.com/nearai/ironclaw/issues/7165) Customer Feedback Remedition `epic` `v1.2.0`

### 🔒 Closed Issues
- [#7168](https://github.com/nearai/ironclaw/issues/7168) Agent-installed skills are invisible: skill_install writes where discovery does not read
- [#6284](https://github.com/nearai/ironclaw/issues/6284) [EPIC] error-recoverability endgame — the model recovers from 100% of the errors it sees

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,807 · **Open issues:** 97 · **Last push:** 13h ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 21h ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 2d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 2d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 3d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 4d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 4d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 4d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬10 · 4d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 8d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 14d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Tino Cuellar](https://www.anthropic.com/news/tino-cuellar) _2026-08-04_

### OpenAI — 4 new
- [[Partners] Teamlab](https://openai.com/business/partners/teamlab/) _2026-08-05_
- [Education](https://openai.com/education/) _2026-08-05_
- [[Index] Introducing The Openai Economic Research Exchange](https://openai.com/index/introducing-the-openai-economic-research-exchange/) _2026-08-04_
- [[Index] Apple Is Getting This Wrong](https://openai.com/index/apple-is-getting-this-wrong/) _2026-08-04_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [Kimi K3 full model running on 16x GB10 cluster at 20+tps](https://reddit.com/r/LocalLLaMA/comments/1vfl525/kimi_k3_full_model_running_on_16x_gb10_cluster_at/) ↑748
- [White House AI Guidelines Exempt U.S. Open Models From Government Review](https://reddit.com/r/LocalLLaMA/comments/1vfqqdb/white_house_ai_guidelines_exempt_us_open_models/) ↑144

### r/singularity — top 2 new
- [Nope](https://reddit.com/r/singularity/comments/1vf6cpa/nope/) ↑2267
- [Ilya’s SSI (Safe Super Intelligence) to release their first model this month.](https://reddit.com/r/singularity/comments/1vffbbw/ilyas_ssi_safe_super_intelligence_to_release/) ↑708

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Groups with my friends and agents?](https://reddit.com/r/openclaw/comments/1vfru5m/groups_with_my_friends_and_agents/) ↑5
- [What's wrong with using openclaw on my main pc?](https://reddit.com/r/openclaw/comments/1vf0htn/whats_wrong_with_using_openclaw_on_my_main_pc/) ↑5
- [What are you running OpenClaw for other than coding?](https://reddit.com/r/openclaw/comments/1v8s45f/what_are_you_running_openclaw_for_other_than/) ↑5
- [Can someone please explain what my openclaw just did...](https://reddit.com/r/openclaw/comments/1vfq9ln/can_someone_please_explain_what_my_openclaw_just/) ↑3
- [Alternative Metrics for Evaluating LLM Inference Performance Beyond KV Cache Offloading](https://reddit.com/r/openclaw/comments/1vfkafy/alternative_metrics_for_evaluating_llm_inference/) ↑2

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
- [That's a fairly new kind of spam. 
https://
github.com/jinhaosong-sou
rce?tab=overview&from=2026-07-01&to=2026-07-31
…](https://x.com/steipete/status/2083976289485230449) ↑0 🔁0 · recent
- [After accepting for years that GMail is blinding me I finally asked my agent and it installed 
https://
darkreader.org f](https://x.com/steipete/status/2083759812970786997) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
