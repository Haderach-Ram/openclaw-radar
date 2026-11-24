---
layout: post
title: "Ecosystem Digest — 2026-11-24"
date: 2026-11-24 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-24
*Generated 09:59 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 395,122 | 11 | 6 | 10 | 2 |
| **hermesagent** | 265,695 | 9 | 10 | 5 | 1 |
| **ZeroClaw** | 33,591 | 9 | 5 | 10 | 0 |
| **IronClaw** | 12,719 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,986 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 395,122 · **Open issues:** 8,970 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.11.10-beta.3](https://github.com/openclaw/openclaw/releases/tag/v2026.11.10-beta.3) — openclaw 2026.11.10-beta.3
- [v2026.11.10-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.11.10-beta.2) — openclaw 2026.11.10-beta.2

### ✅ Merged PRs
- [#204352](https://github.com/openclaw/openclaw/pull/204352) fix(ui): clarify pending guest suggestions
- [#204380](https://github.com/openclaw/openclaw/pull/204380) test(browser): forward lstat options in install-layout ownership mocks
- [#202514](https://github.com/openclaw/openclaw/pull/202514) fix(ci): run the builds selected tests need
- [#204304](https://github.com/openclaw/openclaw/pull/204304) fix(tests): stop recovery and output checks racing lazy UI loads
- [#203952](https://github.com/openclaw/openclaw/pull/203952) fix: read GitHub previews with the connected GitHub CLI account
- [#204329](https://github.com/openclaw/openclaw/pull/204329) fix: recognize valid Git plugin installation provenance
- [#204277](https://github.com/openclaw/openclaw/pull/204277) improve: welcome guests in the agent's own voice
- [#204367](https://github.com/openclaw/openclaw/pull/204367) test(qa): assert the failed child status lands once in parent history
- [#204219](https://github.com/openclaw/openclaw/pull/204219) feat(agents): keep idle prompt caches warm with read-only prewarms
- [#204360](https://github.com/openclaw/openclaw/pull/204360) fix(release): reuse child evidence across release tooling changes

### 🐛 New Issues
- [#204376](https://github.com/openclaw/openclaw/issues/204376) Docs external links: audit cancelled at its time limit on every scheduled run since 2026-08-31 `P3` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#204375](https://github.com/openclaw/openclaw/issues/204375) OpenClaw performance: scheduled Kova live OpenAI lane fails after producing its bundle `P2` `issue-rating: 🦪 silver shellfish` `impact:other` 💬2
- [#204374](https://github.com/openclaw/openclaw/issues/204374) CI test timings refit: daily job times out or fails 5 of the last 8 runs `P2` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#204373](https://github.com/openclaw/openclaw/issues/204373) CodeQL macOS critical security: Analyze reaches the 90-minute job limit `P2` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#204372](https://github.com/openclaw/openclaw/issues/204372) QA live transports (Convex): all five live channel lanes red on every scheduled run `P2` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#204368](https://github.com/openclaw/openclaw/issues/204368) OpenAI-compatible speech is unavailable to streaming TTS callers `enhancement` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#204366](https://github.com/openclaw/openclaw/issues/204366) CI: thousands of test files run on no scheduled lane of main; add an every-file lane and a plan test `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#204363](https://github.com/openclaw/openclaw/issues/204363) update: on PostgreSQL, a crash after migration leaves no Gateway running `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:crash-loop` `issue-rating: 🦞 diamond lobster` `maturity:stable` 💬1
- [#204356](https://github.com/openclaw/openclaw/issues/204356) Show context compaction inline with chat activity `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#204354](https://github.com/openclaw/openclaw/issues/204354) [Feature]: Agent Profiles: a smaller prompt for small local models, chosen per agent or by model size `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:linked-pr-open` `impact:session-state` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#204347](https://github.com/openclaw/openclaw/issues/204347) [Bug]: [Control UI] zh-CN translation: "People" shown as 人力资源 (Human Resources) in session details `bug` `no-stale` `bug:behavior` `P3` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#200340](https://github.com/openclaw/openclaw/issues/200340) [Bug]: macOS app's first message fails with false "host is low on memory" because Bun's process.availableMemory() is free pages only
- [#202501](https://github.com/openclaw/openclaw/issues/202501) [Bug] Selected CI tests can inherit an unnecessary runtime build
- [#204312](https://github.com/openclaw/openclaw/issues/204312) Recovery and inline-output UI tests race lazy module loading
- [#204324](https://github.com/openclaw/openclaw/issues/204324) Valid pinned Git plugin installs are reported as provenance-invalid
- [#204269](https://github.com/openclaw/openclaw/issues/204269) [Feature]: Make guest welcomes speak in the agent’s own voice
- [#204267](https://github.com/openclaw/openclaw/issues/204267) QA smoke: subagent-empty-completion-recovery fails on main since child history delivery

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬85 · 2d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 265,695 · **Open issues:** 54,217 · **Last push:** <1h ago

### 🚀 New Releases
- [canary.20261123T065600Z-v0.23.3](https://github.com/NousResearch/hermes-agent/releases/tag/canary.20261123T065600Z-v0.23.3) — Hermes Agent canary canary.20261123T065600Z-v0.23.3

### ✅ Merged PRs
- [#153223](https://github.com/NousResearch/hermes-agent/pull/153223) feat(plugins): tell plugins which prompt a gateway session is waiting on
- [#156725](https://github.com/NousResearch/hermes-agent/pull/156725) feat(profiles): never run a profile on the host while a plugin runs it elsewhere
- [#152432](https://github.com/NousResearch/hermes-agent/pull/152432) feat(shared-metrics): count group chats and say who hosts the install in the daily snapshot
- [#158714](https://github.com/NousResearch/hermes-agent/pull/158714) feat(release): commit builds run Stable Release with isolated caches and signing
- [#159168](https://github.com/NousResearch/hermes-agent/pull/159168) fix(profiles): platform adapters never recreate a deleted profile home

### 🐛 New Issues
- [#159470](https://github.com/NousResearch/hermes-agent/issues/159470) /model switch to a custom provider whose name has spaces fails with model_resolution_failed (and --global can persist a corrupted model.default) `type/bug` `comp/cli` `area/config` `P2`
- [#159459](https://github.com/NousResearch/hermes-agent/issues/159459) [Bug]: Discord progress cleanup can delete messages without complete final delivery `type/bug` `comp/gateway` `comp/plugins` `platform/discord` `P2`
- [#159456](https://github.com/NousResearch/hermes-agent/issues/159456) [Bug]: Telegram gateway times out while standalone requests from same venv succeed (macOS) `type/bug` `comp/gateway` `comp/plugins` `platform/telegram` `P3` `os/macos`
- [#159451](https://github.com/NousResearch/hermes-agent/issues/159451) [Bug]: hermes-gateway RSS grows ~1 GB/hr on multi-profile hosts (change_watcher re-parses config.yaml via ruamel.yaml XLoader ~590/min) `type/perf` `comp/gateway` `area/config` `P2` `area/profiles` `comp/tui-gateway`
- [#159448](https://github.com/NousResearch/hermes-agent/issues/159448) Desktop: while a chat compresses its context you can't switch to another agent/session, and there's no progress `type/bug` `P2` `comp/desktop` `area/sessions` `area/profiles` `area/compression` `desktop/sessions`
- [#159447](https://github.com/NousResearch/hermes-agent/issues/159447) Desktop: no live progress for cron jobs; a long run looks like nothing is happening `type/bug` `P2` `comp/desktop` `area/sessions` `desktop/chat` `area/webapp`
- [#159446](https://github.com/NousResearch/hermes-agent/issues/159446) Bot Mode: a message refused by the hop cap disappears silently; the owner is never told `type/bug` `comp/agent` `area/config` `P2`
- [#159444](https://github.com/NousResearch/hermes-agent/issues/159444) [Bug]: Cross-model fallback to Gemini on Vertex OpenAI-compat endpoint 400s when primary's tool-call history has no thought_signature `type/bug` `comp/agent` `provider/gemini` `P3`
- [#159442](https://github.com/NousResearch/hermes-agent/issues/159442) [Bug]: Concurrent scans of two different profile homes race on the process-global `_discovering` flag: a provider row is skipped or the flag sticks at True (provider missing from picker / Accounts unt `type/bug` `comp/plugins` `P2` `area/profiles`

### 🔒 Closed Issues
- [#155854](https://github.com/NousResearch/hermes-agent/issues/155854) hermes_tools.search_files docstring promises `matches` but densified ≥5-match responses omit the key entirely
- [#14614](https://github.com/NousResearch/hermes-agent/issues/14614) resolve_alias() reverse lookup returns wrong provider when multiple providers share the same model
- [#5197](https://github.com/NousResearch/hermes-agent/issues/5197) Automatically run "npm audit" to identify security issues
- [#17497](https://github.com/NousResearch/hermes-agent/issues/17497) Research disclosure: static review observations for agent-facing skill artifacts
- [#28992](https://github.com/NousResearch/hermes-agent/issues/28992) [Feature]: Use -z (oneshot) mode for kanban worker spawn instead of chat -q
- [#24782](https://github.com/NousResearch/hermes-agent/issues/24782) [Bug]: [subagent] Fallback model uses parent's base_url instead of fallback's base_url
- [#22754](https://github.com/NousResearch/hermes-agent/issues/22754) Feature: Make unconditional blocklist configurable (default: disabled)
- [#24284](https://github.com/NousResearch/hermes-agent/issues/24284) Allow cron jobs to safely self-schedule or opt into cronjob tool access
- [#24092](https://github.com/NousResearch/hermes-agent/issues/24092) [Bug]: fallback_providers with provider: custom + explicit base_url falls back to OpenRouter when main model.provider is a named provider
- [#20984](https://github.com/NousResearch/hermes-agent/issues/20984) feat: add cron_mode: allowlist to restrict cron jobs to command_allowlist only

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,591 · **Open issues:** 1,255 · **Last push:** <1h ago

### ✅ Merged PRs
- [#12644](https://github.com/zeroclaw-labs/zeroclaw/pull/12644) chore(lint): fix clippy lints introduced by Rust 1.99
- [#12609](https://github.com/zeroclaw-labs/zeroclaw/pull/12609) docs(runtime): propose ADR-016 exception for daemon-held OIDC refresh grants
- [#12498](https://github.com/zeroclaw-labs/zeroclaw/pull/12498) feat(oidc): accept untyped access tokens and declared claim names for JWKS
- [#12535](https://github.com/zeroclaw-labs/zeroclaw/pull/12535) fix(web): announce completed full-page sign-ins to other tabs
- [#11918](https://github.com/zeroclaw-labs/zeroclaw/pull/11918) fix(cron): keep quiet NO_REPLY results out of live cron_result events
- [#12545](https://github.com/zeroclaw-labs/zeroclaw/pull/12545) fix(runtime): resolve configured Agent routes through the provider source
- [#12398](https://github.com/zeroclaw-labs/zeroclaw/pull/12398) fix(runtime): surface exit status and stderr on failed shell runs
- [#11826](https://github.com/zeroclaw-labs/zeroclaw/pull/11826) fix(config): publish the secret key with renameat2 on Android
- [#11718](https://github.com/zeroclaw-labs/zeroclaw/pull/11718) fix(gateway): keep a streamed webhook turn running when its SSE client disconnects
- [#12565](https://github.com/zeroclaw-labs/zeroclaw/pull/12565) fix(channels): require patched lettre for downstream consumers

### 🐛 New Issues
- [#12699](https://github.com/zeroclaw-labs/zeroclaw/issues/12699) [Feature]: Make Docker dependency caching reliable across CI builders and review stub prefetch
- [#12697](https://github.com/zeroclaw-labs/zeroclaw/issues/12697) [Tracker]: Split zeroclaw-runtime into smaller crates `runtime` `domain:architecture` `status:no-stale` `type:tracker`
- [#12693](https://github.com/zeroclaw-labs/zeroclaw/issues/12693) [Bug]: RUSTSEC-2026-0594 (cookie) fails the Security job on every PR and merge group `bug`
- [#12690](https://github.com/zeroclaw-labs/zeroclaw/issues/12690) [RFC] Remote Files tool with native host integration and scoped credential grants 💬1
- [#12686](https://github.com/zeroclaw-labs/zeroclaw/issues/12686) [Feature]: Retire the unreachable hardware tool registry in zeroclaw-hardware `enhancement`
- [#12685](https://github.com/zeroclaw-labs/zeroclaw/issues/12685) [Bug]: Telegram callback_query with arbitrary callback_data is silently dropped (no pass-through to agent)
- [#12681](https://github.com/zeroclaw-labs/zeroclaw/issues/12681) [Task]: Bug waa
- [#12666](https://github.com/zeroclaw-labs/zeroclaw/issues/12666) [Bug]: `delegate` accepts an unknown argument and drops it without an error `bug` 💬6
- [#12660](https://github.com/zeroclaw-labs/zeroclaw/issues/12660) [Bug]: Agent cards' "this month" spend is all-time spend 💬1

### 🔒 Closed Issues
- [#12092](https://github.com/zeroclaw-labs/zeroclaw/issues/12092) [Task]: resolve Agent route selections through the capability source
- [#11525](https://github.com/zeroclaw-labs/zeroclaw/issues/11525) [Bug]: quickstart fails on Android/Termux
- [#11858](https://github.com/zeroclaw-labs/zeroclaw/issues/11858) [Bug]: send_via advertises reply routing in headless turns with no reply consumer
- [#12604](https://github.com/zeroclaw-labs/zeroclaw/issues/12604) [Bug]: MCP results from FastMCP tools that return a string still reach the model twice
- [#12559](https://github.com/zeroclaw-labs/zeroclaw/issues/12559) [Bug]: Config setters store `inf` and `NaN` for a decimal setting

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,719 · **Open issues:** 1,575 · **Last push:** 14d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,986 · **Open issues:** 123 · **Last push:** 31d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬5 · 3d ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 21d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 30d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 49d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 58d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 60d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 70d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 77d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 79d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 87d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Research] Working With Ai](https://www.anthropic.com/research/working-with-ai) _2026-11-23_

### OpenAI — 1 new
- [Openworks](https://openai.com/openworks/) _2026-11-23_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [The US-China Open-Weight Feedback Loop](https://reddit.com/r/LocalLLaMA/comments/1y3q68f/the_uschina_openweight_feedback_loop/) ↑760
- [GLM 5.4 is great at coding. But absolutely garbage at writing and anything but that. Are future open weight models going to be just codemaxxed??](https://reddit.com/r/LocalLLaMA/comments/1y3lqu3/glm_54_is_great_at_coding_but_absolutely_garbage/) ↑723

### r/singularity — top 5 new
- [Employees welcome back Jensen to Nvidia](https://reddit.com/r/singularity/comments/1y3s3m3/employees_welcome_back_jensen_to_nvidia/) ↑3457
- [Something just happened.](https://reddit.com/r/singularity/comments/1y14vi5/something_just_happened/) ↑1998
- [Anthropic claimed to have proved VP ≠ VNP over every field, the algebraic counterpart to the P vs NP problem](https://reddit.com/r/singularity/comments/1y3w34p/anthropic_claimed_to_have_proved_vp_vnp_over/) ↑1039
- [Nvidia reinstates Jensen Huang as CEO](https://reddit.com/r/singularity/comments/1y3jbnj/nvidia_reinstates_jensen_huang_as_ceo/) ↑783
- [Meanwhile, on Truth Social.](https://reddit.com/r/singularity/comments/1y3rlrn/meanwhile_on_truth_social/) ↑751

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw 2026.11.7 adds conversation recovery and automation repair](https://reddit.com/r/openclaw/comments/1y3ank8/openclaw_2026117_adds_conversation_recovery_and/) ↑14
- [The OpenClaw 2026.11.7 patch is out 🦞](https://reddit.com/r/openclaw/comments/1y3mpfa/the_openclaw_2026117_patch_is_out/) ↑13
- [Signed up online for a subscription](https://reddit.com/r/openclaw/comments/1y3q5nm/signed_up_online_for_a_subscription/) ↑5
- [Lobster workflow](https://reddit.com/r/openclaw/comments/1y3v5q4/lobster_workflow/) ↑4
- [Microsoft’s Omar Shahine wrote about how he uses Autopilot day to day](https://reddit.com/r/openclaw/comments/1y43glm/microsofts_omar_shahine_wrote_about_how_he_uses/) ↑1

### X — @openclaw
_No tweets found on profile (fetch may have failed)._

### X — @steipete
_No tweets found on profile (fetch may have failed)._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
