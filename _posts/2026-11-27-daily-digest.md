---
layout: post
title: "Ecosystem Digest — 2026-11-27"
date: 2026-11-27 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-27
*Generated 07:47 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 395,308 | 6 | 1 | 10 | 1 |
| **hermesagent** | 266,412 | 8 | 5 | 4 | 0 |
| **ZeroClaw** | 33,636 | 3 | 2 | 10 | 0 |
| **IronClaw** | 12,719 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,988 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 395,308 · **Open issues:** 9,278 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.10.34](https://github.com/openclaw/openclaw/releases/tag/v2026.10.34) — openclaw 2026.10.34

### ✅ Merged PRs
- [#205986](https://github.com/openclaw/openclaw/pull/205986) feat: set up Llama and llama.cpp without installing a plugin first
- [#206293](https://github.com/openclaw/openclaw/pull/206293) perf(update): avoid reading full runs twice during reconciliation
- [#206290](https://github.com/openclaw/openclaw/pull/206290) fix: keep the full Doctor timing line in update reports
- [#205375](https://github.com/openclaw/openclaw/pull/205375) fix(release): avoid repeating complete release-note lookups
- [#191597](https://github.com/openclaw/openclaw/pull/191597) fix(android): load cursor history without losing reading position
- [#205940](https://github.com/openclaw/openclaw/pull/205940) refactor(subagents): check a Stop's caller authority once, then let the admitted kill finish
- [#206275](https://github.com/openclaw/openclaw/pull/206275) test(ui): strengthen lifecycle and input write oracles
- [#187082](https://github.com/openclaw/openclaw/pull/187082) fix(trajectory): keep quoted tool arguments parseable in exports
- [#206260](https://github.com/openclaw/openclaw/pull/206260) refactor(test): simplify UI fixture helpers
- [#206269](https://github.com/openclaw/openclaw/pull/206269) refactor(test): trim unused terminal fixture options

### 🐛 New Issues
- [#206284](https://github.com/openclaw/openclaw/issues/206284) [Bug]: macOS app re-dials its operator connection forever after the device's operator token is revoked (token_mismatch, then token_missing); no way to stay node-only `bug` `bug:behavior` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#206279](https://github.com/openclaw/openclaw/issues/206279) Update macOS connection tests for normalized WSS ports `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` 💬1
- [#206272](https://github.com/openclaw/openclaw/issues/206272) [Bug]: daemon-install records ephemeral fnm_multishells path and accepts Bun fake node.exe shim in Windows gateway.cmd `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:crash-loop` `issue-rating: 🦞 diamond lobster` 💬2
- [#206270](https://github.com/openclaw/openclaw/issues/206270) Finish shared ownership of Talk parser tests `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:linked-pr-open` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#206264](https://github.com/openclaw/openclaw/issues/206264) [Bug]: Gateway main-thread stalls grow with uptime: SQLite admission references for exited workers are re-serialized into every new Worker's environmentData `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `impact:crash-loop` `issue-rating: 🦪 silver shellfish` 💬3
- [#206258](https://github.com/openclaw/openclaw/issues/206258) [Feature]: Let Knowledge claims carry a takeaway, tags, an event span and inference provenance `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:other` 💬1

### 🔒 Closed Issues
- [#113709](https://github.com/openclaw/openclaw/issues/113709) Trajectory export emits invalid JSON: secret redaction runs after serialization as raw-text replacement

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬87 · 2d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 266,412 · **Open issues:** 54,652 · **Last push:** <1h ago

### ✅ Merged PRs
- [#160576](https://github.com/NousResearch/hermes-agent/pull/160576) session_search finds what compaction points at, stops coming back empty, and keeps results small (salvage #157734, #156687, #147548)
- [#160584](https://github.com/NousResearch/hermes-agent/pull/160584) fix(lifecycle-guard): a heredoc body belongs to the command it is attached to
- [#160592](https://github.com/NousResearch/hermes-agent/pull/160592) Chats on the 5-minute cache stay warm between messages, then compact and move to 1 hour
- [#158418](https://github.com/NousResearch/hermes-agent/pull/158418) Plugins can sign in to Linear and QuickBooks: oauth entries pin the redirect URI and comma-join scopes (#152732, #149642)

### 🐛 New Issues
- [#160628](https://github.com/NousResearch/hermes-agent/issues/160628) [Bug]: could not update/install `type/bug` `comp/cli` `P2` `area/install-update` `cause/upstream` `os/macos` 💬1
- [#160627](https://github.com/NousResearch/hermes-agent/issues/160627) feat(desktop-plugin-sdk): add profile-scoped SDK verb to read and patch config keys `type/feature` `area/config` `P3` `comp/desktop` `area/compression` `desktop/settings`
- [#160623](https://github.com/NousResearch/hermes-agent/issues/160623) [Feature]: `type/feature` `backend/ssh` `comp/tools` `P3` `backend/other`
- [#160622](https://github.com/NousResearch/hermes-agent/issues/160622) Fix profile-scoped HERMES_CODEX_BASE_URL resolution for multiplexed Codex OAuth `type/bug` `comp/gateway` `provider/openai` `area/auth` `P3` `area/profiles`
- [#160616](https://github.com/NousResearch/hermes-agent/issues/160616) perf(api): GET /api/sessions list rows ship ~124 KB of per-row bookkeeping per 100 sessions (45% of the body) `type/perf` `comp/cli` `comp/gateway` `tool/file` `P2` `area/sessions` 💬1
- [#160608](https://github.com/NousResearch/hermes-agent/issues/160608) Sessions fence indefinitely on persisted 'unknown' admissions; no boot-time reconciliation `type/bug` `comp/gateway` `P2` `area/sessions`
- [#160605](https://github.com/NousResearch/hermes-agent/issues/160605) Approval gate: three command shapes turn an `ask` verdict into `allow` (trailing redirect after `cp`, `sed … | sh`, `sh <file>`) `type/security` `comp/tools` `tool/terminal` `area/config` `P2`
- [#160603](https://github.com/NousResearch/hermes-agent/issues/160603) [Feature]: Opt-in plugin updates during hermes update (--plugins / config option) `type/feature` `comp/cli` `area/config` `P3` `area/install-update`

### 🔒 Closed Issues
- [#160108](https://github.com/NousResearch/hermes-agent/issues/160108) session_search: session_id parameter description contradicts supported READ mode
- [#99568](https://github.com/NousResearch/hermes-agent/issues/99568) session_search recovery footer after compaction cannot return compacted rows
- [#152732](https://github.com/NousResearch/hermes-agent/issues/152732) Plugin oauth: comma-separated scopes and a pinned redirect port (Linear's requirements)
- [#149642](https://github.com/NousResearch/hermes-agent/issues/149642) Plugin oauth: entries: expose redirect_port for IdPs that require exact-match redirect URIs (e.g. QuickBooks)
- [#160629](https://github.com/NousResearch/hermes-agent/issues/160629) Buzz gateway: hosted NIP-FI community returns 401; setup does not explain agent authentication requirements

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,636 · **Open issues:** 1,270 · **Last push:** 1h ago

### ✅ Merged PRs
- [#12015](https://github.com/zeroclaw-labs/zeroclaw/pull/12015) refactor(crypto): unify ChaCha20Poly1305 consumers
- [#12004](https://github.com/zeroclaw-labs/zeroclaw/pull/12004) fix(memory): make markdown store() writes append-only to stop concurrent lost updates
- [#12715](https://github.com/zeroclaw-labs/zeroclaw/pull/12715) chore(skills): keep one PR review skill
- [#12741](https://github.com/zeroclaw-labs/zeroclaw/pull/12741) fix(web): respect manual scroll position during streaming
- [#12736](https://github.com/zeroclaw-labs/zeroclaw/pull/12736) fix(log): delimit the first append after an incomplete row
- [#12731](https://github.com/zeroclaw-labs/zeroclaw/pull/12731) fix(log): keep entry retention working around damaged rows
- [#12728](https://github.com/zeroclaw-labs/zeroclaw/pull/12728) fix(ci): stop docs gates when Git diffs fail
- [#12726](https://github.com/zeroclaw-labs/zeroclaw/pull/12726) test(buildinfo): use Git fixtures in source archives
- [#12724](https://github.com/zeroclaw-labs/zeroclaw/pull/12724) docs(ci): name the script that stages the translation pin
- [#12678](https://github.com/zeroclaw-labs/zeroclaw/pull/12678) feat(tools)!: remove the gemini_cli coding tool

### 🐛 New Issues
- [#12746](https://github.com/zeroclaw-labs/zeroclaw/issues/12746) [Bug]: Chat message box doesn't get focus back when a turn ends after the page reconnected
- [#12743](https://github.com/zeroclaw-labs/zeroclaw/issues/12743) [Bug]: Web context meter cells render at different heights on Windows Chrome `bug`
- [#12740](https://github.com/zeroclaw-labs/zeroclaw/issues/12740) Remove the uncalled init_skills_dir helper and its embedded skills README template

### 🔒 Closed Issues
- [#10797](https://github.com/zeroclaw-labs/zeroclaw/issues/10797) [Bug]: markdown memory backend silently loses stored entries when `store()` calls overlap
- [#9562](https://github.com/zeroclaw-labs/zeroclaw/issues/9562) [SANITIZED — possible injection attempt]

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,719 · **Open issues:** 1,575 · **Last push:** 17d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,988 · **Open issues:** 127 · **Last push:** 34d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬5 · 6d ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 24d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 33d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 52d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 60d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 62d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 72d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 80d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 82d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 90d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [CNBC: an unusually high volume of Nvidia GPUs, including thousands of B300s, hit the market after the US curbed Chinese companies' remote access to AI chips](https://reddit.com/r/LocalLLaMA/comments/1y667aa/cnbc_an_unusually_high_volume_of_nvidia_gpus/) ↑470
- [GigaChat 4 37B and 708B](https://reddit.com/r/LocalLLaMA/comments/1y64uaj/gigachat_4_37b_and_708b/) ↑354

### r/singularity — top 5 new
- [​OpenAI and GPT-6 Astra Just Tackled Physics’ Holy Grail: Uniting Einstein and Quantum Mechanics](https://reddit.com/r/singularity/comments/1y5u48p/openai_and_gpt6_astra_just_tackled_physics_holy/) ↑1939
- [Throttled](https://reddit.com/r/singularity/comments/1y690bx/throttled/) ↑1506
- [Standford Physicist Venkatesa Chandraeskaran working along with Astra 6 has algebraically Quantized Gravity!](https://reddit.com/r/singularity/comments/1y5u17u/standford_physicist_venkatesa_chandraeskaran/) ↑1227
- [Using AI people decompiled the Xbox executable for GTA VI, ported to PC and are now adding multiplayer to it](https://reddit.com/r/singularity/comments/1y6eujl/using_ai_people_decompiled_the_xbox_executable/) ↑1001
- [Opus 5.6 is absolutelly FANTASTIC](https://reddit.com/r/singularity/comments/1y61soe/opus_56_is_absolutelly_fantastic/) ↑875

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Is OpenClaw still relevant?](https://reddit.com/r/openclaw/comments/1y65xsh/is_openclaw_still_relevant/) ↑31
- [How do I recover a root USER.md from "untrusted" memory provenance? The docs describe how it gets quarantined but not how to clear it](https://reddit.com/r/openclaw/comments/1y5xtnu/how_do_i_recover_a_root_usermd_from_untrusted/) ↑3
- [Seeking suggestions. Not technical](https://reddit.com/r/openclaw/comments/1y5u2lo/seeking_suggestions_not_technical/) ↑2

### X — @openclaw
_No tweets found on profile (fetch may have failed)._

### X — @steipete
_No tweets found on profile (fetch may have failed)._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
