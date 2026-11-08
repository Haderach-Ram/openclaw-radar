---
layout: post
title: "Ecosystem Digest — 2026-11-08"
date: 2026-11-08 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-08
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 394,148 | 5 | 3 | 10 | 0 |
| **hermesagent** | 261,525 | 2 | 0 | 10 | 0 |
| **ZeroClaw** | 33,217 | 13 | 3 | 4 | 0 |
| **IronClaw** | 12,715 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,946 | 1 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 394,148 · **Open issues:** 7,756 · **Last push:** <1h ago

### ✅ Merged PRs
- [#194933](https://github.com/openclaw/openclaw/pull/194933) fix: keep lifecycle tests portable across runtimes
- [#194813](https://github.com/openclaw/openclaw/pull/194813) fix: compaction skips configured fallback after quota errors
- [#194921](https://github.com/openclaw/openclaw/pull/194921) fix(diagnostics): report full CPU capture duration
- [#194931](https://github.com/openclaw/openclaw/pull/194931) test(x): remove redundant midnight spend scenario
- [#194897](https://github.com/openclaw/openclaw/pull/194897) fix(doctor): settle state migrations for plugins with disabled channels
- [#194885](https://github.com/openclaw/openclaw/pull/194885) fix: keep sandboxes running during file and media reads
- [#194925](https://github.com/openclaw/openclaw/pull/194925) fix(ci): include auto-reply in release live test coverage
- [#194882](https://github.com/openclaw/openclaw/pull/194882) fix(hooks): reuse live gateway plugins for queued turns
- [#194908](https://github.com/openclaw/openclaw/pull/194908) refactor(oc-path): remove redundant JSONL assertions
- [#194898](https://github.com/openclaw/openclaw/pull/194898) fix(tokenjuice): preserve Code Mode tool results

### 🐛 New Issues
- [#194929](https://github.com/openclaw/openclaw/issues/194929) test: retain actionable boundary diagnostics for intermittent node-exec live non-start `P2` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#194928](https://github.com/openclaw/openclaw/issues/194928) test(ios): make managed-document session setup deterministic across relaunch `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` 💬1
- [#194926](https://github.com/openclaw/openclaw/issues/194926) test: avoid rebinding a released ephemeral port in Gateway startup recovery proof `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#194922](https://github.com/openclaw/openclaw/issues/194922) [Bug]: Canceling a shared Muse catalog read returns EOF instead of its cancellation reason `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#194918](https://github.com/openclaw/openclaw/issues/194918) [Feature]: WhatsApp outbound messages should follow the chat's disappearing-messages timer `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#194803](https://github.com/openclaw/openclaw/issues/194803) [Bug]: Compaction summary-error wrapping loses HTTP 429 classification and skips configured fallback
- [#194941](https://github.com/openclaw/openclaw/issues/194941) [Bug]: 2026.11.1 stable still returns outputSchema mismatch ("must not have additional properties: gated") instead of the owner-gated refusal — follow-up to #189488
- [#194875](https://github.com/openclaw/openclaw/issues/194875) [Bug]: Doctor cannot settle disabled iMessage state migration after successful repair

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬80 · 1d ago
- [#116201](https://github.com/openclaw/openclaw/issues/116201) Realtime voice work can retain unbounded provider and consult state — 💬59 · 36d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 261,525 · **Open issues:** 53,588 · **Last push:** <1h ago

### ✅ Merged PRs
- [#150796](https://github.com/NousResearch/hermes-agent/pull/150796) plugin-catalog: holographic 0.26.5
- [#150783](https://github.com/NousResearch/hermes-agent/pull/150783) feat(plugin-catalog): list SolverForge Routing
- [#150768](https://github.com/NousResearch/hermes-agent/pull/150768) feat(plugin-catalog): add munin
- [#150739](https://github.com/NousResearch/hermes-agent/pull/150739) feat(plugin-catalog): add sluice
- [#150681](https://github.com/NousResearch/hermes-agent/pull/150681) catalog: update hermes-dreaming to 3.8.6
- [#150666](https://github.com/NousResearch/hermes-agent/pull/150666) feat(plugin-catalog): add findbroadband-deals (FindBroadband)
- [#150665](https://github.com/NousResearch/hermes-agent/pull/150665) feat(plugin-catalog): add internet-outage-checker (Internet Outage Checker by FindBroadband)
- [#150643](https://github.com/NousResearch/hermes-agent/pull/150643) plugin-catalog: update kanban-empowered to 0.3.1
- [#150627](https://github.com/NousResearch/hermes-agent/pull/150627) plugin-catalog: add safe-swap
- [#150616](https://github.com/NousResearch/hermes-agent/pull/150616) catalog: limbic 0.9.5 — verified macOS support

### 🐛 New Issues
- [#150986](https://github.com/NousResearch/hermes-agent/issues/150986) [Bug]: `hermes cron create/edit --repeat forever` fails with argparse "invalid int value" although the cronjob tool and normalize_repeat_value accept it
- [#150981](https://github.com/NousResearch/hermes-agent/issues/150981) `--safe-mode` / `--ignore-user-config` sessions always get the `local` terminal: managed `terminal:` scope is ignored

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,217 · **Open issues:** 1,156 · **Last push:** 2h ago

### ✅ Merged PRs
- [#12157](https://github.com/zeroclaw-labs/zeroclaw/pull/12157) fix(oidc): bind enrollment callbacks to the initiating browser
- [#12239](https://github.com/zeroclaw-labs/zeroclaw/pull/12239) fix(rpc): hold current authority through session effects
- [#12274](https://github.com/zeroclaw-labs/zeroclaw/pull/12274) docs(runtime): record the relay-served dashboard placement exception
- [#11149](https://github.com/zeroclaw-labs/zeroclaw/pull/11149) fix(security): enforce cron approval and authority at the write across RPC, tools and token revocation

### 🐛 New Issues
- [#12285](https://github.com/zeroclaw-labs/zeroclaw/issues/12285) [Feature]: Refuse config writes to credential and sign-in paths on relay-served dashboard connections `enhancement` `gateway` `security`
- [#12284](https://github.com/zeroclaw-labs/zeroclaw/issues/12284) OIDC enrollment follow-up: refusal logs, duplicate-cookie regressions and HTTP guidance
- [#12283](https://github.com/zeroclaw-labs/zeroclaw/issues/12283) resolve_peer_set applies peer-group `ignore` per group, so outbound sends can reach ignored peers
- [#12280](https://github.com/zeroclaw-labs/zeroclaw/issues/12280) [Task]: don't treat a forwarded loopback address as local in SOP cancel authorization 💬1
- [#12235](https://github.com/zeroclaw-labs/zeroclaw/issues/12235) [Bug]: delegated agent returns raw text tool calls (native_tools not honoured in the delegate's loop) `bug` 💬1
- [#12228](https://github.com/zeroclaw-labs/zeroclaw/issues/12228) [Bug]: cron update --agent reports success but never reassigns the job's agent 💬2
- [#12227](https://github.com/zeroclaw-labs/zeroclaw/issues/12227) [Bug]: Shell approval depends on an "approved" value the model writes itself, so prompts appear inconsistently `bug` 💬1
- [#12221](https://github.com/zeroclaw-labs/zeroclaw/issues/12221) [Task]: show retired environment-variable warnings in zeroclaw config migrate 💬1
- [#12211](https://github.com/zeroclaw-labs/zeroclaw/issues/12211) [Bug]: delegated agents don't load TOOLS.md (delegate prompt uses its own file list, not PERSONALITY_FILES) 💬1
- [#12205](https://github.com/zeroclaw-labs/zeroclaw/issues/12205) [Bug]: Empty canvases are never removed, stay in the viewer list and count toward the 100-canvas limit 💬1
- [#12199](https://github.com/zeroclaw-labs/zeroclaw/issues/12199) config validate: warn on dead delegate grants (delegates roster unreachable under delegation_policy.mode = forbidden) 💬1
- [#12187](https://github.com/zeroclaw-labs/zeroclaw/issues/12187) [Bug]: Channel cached-turn normalization merges a user turn into a role=tool envelope, permanently poisoning the conversation on strict providers 💬3
- [#12048](https://github.com/zeroclaw-labs/zeroclaw/issues/12048) [Feature]: Validate the OIDC browser-flow redirect_uri against a configured dashboard origin instead of trusting the Host header `enhancement` `gateway` `security` `topic:identity-access` 💬1

### 🔒 Closed Issues
- [#12050](https://github.com/zeroclaw-labs/zeroclaw/issues/12050) [Bug]: The OIDC callback token page has no browser binding, allowing login CSRF
- [#11126](https://github.com/zeroclaw-labs/zeroclaw/issues/11126) [SANITIZED — possible injection attempt]
- [#12260](https://github.com/zeroclaw-labs/zeroclaw/issues/12260) [Bug]: RPC cron/add and cron/patch treat the request as an operator approval for the shell command

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,715 · **Open issues:** 1,571 · **Last push:** 3d ago

### 🐛 New Issues
- [#8115](https://github.com/nearai/ironclaw/issues/8115) Add a Tsubasa registry entry with an explicit 32K context-budget path

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,946 · **Open issues:** 121 · **Last push:** 15d ago

### 🐛 New Issues
- [#273](https://github.com/moltis-org/moltis/issues/273) Bug: v0.10.2 release has zero assets (breaks install script) 💬1

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬2 · 21h ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 5d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 14d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 33d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 41d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 43d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 53d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 61d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 63d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 71d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Good Luck Getting a Cheap GPU. AMD Is a 'Data Center First Company,' CEO Says](https://reddit.com/r/LocalLLaMA/comments/1xpx0on/good_luck_getting_a_cheap_gpu_amd_is_a_data/) ↑790
- [Use your phone to monitor anything with local models! Demo of my Open Source and 100% local agent (iOS and Android!)](https://reddit.com/r/LocalLLaMA/comments/1xqd058/use_your_phone_to_monitor_anything_with_local/) ↑249
- [llama_moe_cache: run missed experts on CPU, add tuning script by am17an · Pull Request #30966 · ggml-org/llama.cpp](https://reddit.com/r/LocalLLaMA/comments/1xqacka/llama_moe_cache_run_missed_experts_on_cpu_add/) ↑186
- [Effects of KV Cache Quantization on Qwen3.8 27B](https://reddit.com/r/LocalLLaMA/comments/1xqbesv/effects_of_kv_cache_quantization_on_qwen38_27b/) ↑130
- [testing Qoduck (Maybe qwen4) on Qoder](https://reddit.com/r/LocalLLaMA/comments/1xqafp1/testing_qoduck_maybe_qwen4_on_qoder/) ↑112

### r/singularity — top 5 new
- [AI Progress Is Now Six Weeks Ahead of the AI 2027 Timeline](https://reddit.com/r/singularity/comments/1xq9o88/ai_progress_is_now_six_weeks_ahead_of_the_ai_2027/) ↑565
- [Virginia's "Data Center Alley" generates $1.2 billion in annual tax revenue—40% of Loudoun County's entire tax revenue from just 3% of its land, according to the county's economic development chief.](https://reddit.com/r/singularity/comments/1xq4hp4/virginias_data_center_alley_generates_12_billion/) ↑460
- [The author of AI 2027 agrees to a ban on RSI.](https://reddit.com/r/singularity/comments/1xq1m8w/the_author_of_ai_2027_agrees_to_a_ban_on_rsi/) ↑364
- [Silicon Valley was so ahead of its time](https://reddit.com/r/singularity/comments/1xpv91b/silicon_valley_was_so_ahead_of_its_time/) ↑331
- [Theo, a wheeled humanoid robot, now works at a Zurich supermarket; at night in the dark it can restock 400 items an hour while handling online orders and other tasks by day](https://reddit.com/r/singularity/comments/1xqjk2e/theo_a_wheeled_humanoid_robot_now_works_at_a/) ↑218

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Flatcap, a dark and light theme for the OpenClaw Control UI](https://reddit.com/r/openclaw/comments/1xq82op/flatcap_a_dark_and_light_theme_for_the_openclaw/) ↑4
- [Cron jobs set to isolated that were quietly reusing one session until the context was full (the tell and the fix)](https://reddit.com/r/openclaw/comments/1xpysu1/cron_jobs_set_to_isolated_that_were_quietly/) ↑1
- [Is it me or OpenClaw lags on PC?](https://reddit.com/r/openclaw/comments/1xqe4o8/is_it_me_or_openclaw_lags_on_pc/) ↑1

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [How does one of the largest open source projects in history do releases? 🦞


@dallinfinite
  walks through how OpenClaw ](https://x.com/openclaw/status/2118803977882181986)

### X — @steipete
_No new tweets since the last digest. Most recent:_
- [Is my perception off or is Apple just lying here? Anytime I build for or use Safari, it’s slower, has fewer features, we](https://x.com/steipete/status/2118492097917628704)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
