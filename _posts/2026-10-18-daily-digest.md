---
layout: post
title: "Ecosystem Digest — 2026-10-18"
date: 2026-10-18 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-18
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 392,291 | 2 | 4 | 10 | 0 |
| **hermesagent** | 254,709 | 9 | 3 | 5 | 0 |
| **ZeroClaw** | 32,990 | 15 | 3 | 10 | 0 |
| **IronClaw** | 12,660 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,897 | 0 | 0 | 1 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 392,291 · **Open issues:** 9,377 · **Last push:** <1h ago

### ✅ Merged PRs
- [#175993](https://github.com/openclaw/openclaw/pull/175993) refactor(ui): retire legacy session-group downgrades
- [#175987](https://github.com/openclaw/openclaw/pull/175987) fix(sessions): preserve readers across maintenance refusal
- [#175983](https://github.com/openclaw/openclaw/pull/175983) refactor(backup): remove pre-payload allocation retries
- [#175988](https://github.com/openclaw/openclaw/pull/175988) refactor(test): remove unused fixture helpers
- [#175888](https://github.com/openclaw/openclaw/pull/175888) refactor(shared): remove redundant schema synopsis
- [#175911](https://github.com/openclaw/openclaw/pull/175911) refactor(gateway): simplify config restart ownership
- [#175962](https://github.com/openclaw/openclaw/pull/175962) test(agents,gateway,ui): remove low-value tests (batch d248)
- [#175965](https://github.com/openclaw/openclaw/pull/175965) fix: guests cannot select pasted Git URLs in new chats
- [#175938](https://github.com/openclaw/openclaw/pull/175938) refactor(browser): centralize action and act-kind facts
- [#175759](https://github.com/openclaw/openclaw/pull/175759) docs(agents): make the stable prompt prefix an invariant

### 🐛 New Issues
- [#175961](https://github.com/openclaw/openclaw/issues/175961) [Bug]: pinned Bun intermittently SIGTRAPs during SQLite worker startup on macOS arm64 `P2` `impact:crash-loop` `issue-rating: 🦪 silver shellfish` 💬1
- [#175954](https://github.com/openclaw/openclaw/issues/175954) Update failure: gateway-recovery-verification (2026.10.3) `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `P0` `issue-rating: 🦪 silver shellfish` `impact:ux-release-blocker` 💬1

### 🔒 Closed Issues
- [#1754](https://github.com/openclaw/openclaw/issues/1754) Proposal: Add `computer` Tool for Agentic UI Automation
- [#124244](https://github.com/openclaw/openclaw/issues/124244) Timeout paths produce wrong output, not absent output: duplicate sends, a fabricated user turn, and a non-clearing restart loop
- [#175974](https://github.com/openclaw/openclaw/issues/175974) [Feature]: Hive of Minds - Real-Time Cognitive Orchestration Toward Gestalt Intelligence
- [#175956](https://github.com/openclaw/openclaw/issues/175956) [Bug]: Guest dependency preparation fails when tool caches become workspace results

### 🔥 Hot Issues (most commented)
- [#143524](https://github.com/openclaw/openclaw/issues/143524) [Bug]: Agent SQLite WAL grows to 1.4–2.8 GB in days despite wal_autocheckpoint=1000; blocks gateway startup (Windows, 2026.9.2/9.3) — 💬131 · 1d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 254,709 · **Open issues:** 49,801 · **Last push:** <1h ago

### ✅ Merged PRs
- [#140376](https://github.com/NousResearch/hermes-agent/pull/140376) fix(ssl): keep TLS working after an install-environment rotation (salvage #137341)
- [#140701](https://github.com/NousResearch/hermes-agent/pull/140701) test(windows): live Windows proof for W3 and W4, plus a Windows packaging fix
- [#140699](https://github.com/NousResearch/hermes-agent/pull/140699) fix: pre-upgrade sessions follow a moved custom endpoint; no setup card over a configured Desktop boot (T21)
- [#140700](https://github.com/NousResearch/hermes-agent/pull/140700) fix(desktop): show a lost turn and its Discard after the gateway dies mid-turn (NF2)
- [#140624](https://github.com/NousResearch/hermes-agent/pull/140624) Platform plugins get public core helpers for authz, HTTP, setup and clarify (QQ Bot handoff)

### 🐛 New Issues
- [#140838](https://github.com/NousResearch/hermes-agent/issues/140838) [Bug]: Revoked Codex OAuth credential causes missing models in model pickers `bug` 💬1
- [#140835](https://github.com/NousResearch/hermes-agent/issues/140835) Prepared-image recovery card offers "Restore image draft" but no way to dismiss it
- [#140831](https://github.com/NousResearch/hermes-agent/issues/140831) Windows: _read_process_cmdline joins argv parts without re-quoting — profile paths with spaces break strict gateway identity and abort hermes update
- [#140828](https://github.com/NousResearch/hermes-agent/issues/140828) Dashboard chat startup waits for unrelated plugins and a 300 ms Suspense retry
- [#140825](https://github.com/NousResearch/hermes-agent/issues/140825) [Bug][Desktop] `--composer-input-min-height` has no effect (hardcoded `min-h-[1.625rem]` wins)
- [#140824](https://github.com/NousResearch/hermes-agent/issues/140824) [Bug][Desktop] New Project folder picker can't navigate to a non-default local drive (e.g. D:\)
- [#140823](https://github.com/NousResearch/hermes-agent/issues/140823) Gateway messages (WeChat/Telegram) not persisted to state.db since v0.22.1 -- sessions.json updated but SQLite sessions/messages tables empty
- [#140821](https://github.com/NousResearch/hermes-agent/issues/140821) [Feature]: support extra env-var credential sources for a provider's credential pool (keep all keys in .env) 💬1
- [#140818](https://github.com/NousResearch/hermes-agent/issues/140818) [Feature]: Allow custom llama-server binary path — users need to run their own forks

### 🔒 Closed Issues
- [#139160](https://github.com/NousResearch/hermes-agent/issues/139160) Gateway fixes (#134889), package 2: session creation, model picks and credentials
- [#140337](https://github.com/NousResearch/hermes-agent/issues/140337) Gateway fixes (#134889), package 9: detach and lost connections, Ink and Desktop leftovers, classic CLI leftovers, Windows, and new regressions
- [#137255](https://github.com/NousResearch/hermes-agent/issues/137255) [Bug]: TLS clients die after an install-environment rotation — certifi's CA bundle path stays in the deleted directory

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,990 · **Open issues:** 1,002 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11221](https://github.com/zeroclaw-labs/zeroclaw/pull/11221) feat(tools): add an opt-in minimal built-in tool setting
- [#11347](https://github.com/zeroclaw-labs/zeroclaw/pull/11347) feat(release): ship the WASM plugin host in supported release artifacts
- [#11262](https://github.com/zeroclaw-labs/zeroclaw/pull/11262) feat(cli): add zeroclaw plugin update with verified replacement
- [#11402](https://github.com/zeroclaw-labs/zeroclaw/pull/11402) fix(plugins): discard a memory plugin's instance after a failed call
- [#11516](https://github.com/zeroclaw-labs/zeroclaw/pull/11516) feat(runtime): add effort-aware local and cloud routing
- [#11791](https://github.com/zeroclaw-labs/zeroclaw/pull/11791) docs(runtime): record file_read pattern allowlist exception
- [#11725](https://github.com/zeroclaw-labs/zeroclaw/pull/11725) fix(runtime): deliver mid-turn steering at the next step, not after the final answer
- [#11506](https://github.com/zeroclaw-labs/zeroclaw/pull/11506) feat(zerocode): show saved and applied config status
- [#11460](https://github.com/zeroclaw-labs/zeroclaw/pull/11460) feat(zerocode): rename provider aliases in Config
- [#10567](https://github.com/zeroclaw-labs/zeroclaw/pull/10567) feat(memory): stamp recalled entries with their storage date

### 🐛 New Issues
- [#11834](https://github.com/zeroclaw-labs/zeroclaw/issues/11834) [Bug]: Workspace is not clippy-clean on Rust 1.99 (18 new findings; CI still pins 1.98.0) `bug`
- [#11831](https://github.com/zeroclaw-labs/zeroclaw/issues/11831) [Task]: move the macOS plugin smoke leg off `macos-14` before the October 19 brownout `type:ci` `release:v0.8.6`
- [#11830](https://github.com/zeroclaw-labs/zeroclaw/issues/11830) [Task]: drop the whole-file digest of the Stable workflow from the release workflow architecture test `tests` `release:v0.8.7`
- [#11829](https://github.com/zeroclaw-labs/zeroclaw/issues/11829) [Task]: confirm plugins run in the notarized macOS desktop app, and add the JIT entitlement if they don't `topic:plugins` `release:v0.8.7`
- [#11828](https://github.com/zeroclaw-labs/zeroclaw/issues/11828) [Task]: the arm64 `dist` image runs out of memory in docker-publish.yml, so v0.8.6 can ship without its `dist` image `type:ci` `release:v0.8.6`
- [#11825](https://github.com/zeroclaw-labs/zeroclaw/issues/11825) [Bug]: codex_cli test empties process PATH and breaks parallel cargo test -p zeroclaw-tools `bug`
- [#11824](https://github.com/zeroclaw-labs/zeroclaw/issues/11824) [Bug]: cmd.exe parenthesized blocks hide commands from risk classification `bug`
- [#11823](https://github.com/zeroclaw-labs/zeroclaw/issues/11823) [Bug]: Shell scanner skips command substitution in unquoted-delimiter heredoc bodies `bug`
- [#11821](https://github.com/zeroclaw-labs/zeroclaw/issues/11821) [Bug]: plugin_channel_sender_denied records do not name the sender, so the operator cannot tell whom to admit `bug` `observability:log` `priority:p3` `risk:low` `topic:plugins` `topic:operator-ux` `release:v0.8.7`
- [#11820](https://github.com/zeroclaw-labs/zeroclaw/issues/11820) [Bug]: config set of a plugin instance's settings or egress grant is written to disk only and never reaches a running daemon `bug` `config` `priority:p2` `risk:medium` `cli` `topic:plugins` `topic:operator-ux` `release:v0.8.7`
- [#11819](https://github.com/zeroclaw-labs/zeroclaw/issues/11819) [Bug]: Quickstart lists models from the provider's default endpoint before asking for the URI, and the picker takes no typed model `bug` `priority:p3` `quickstart` `risk:low` `topic:operator-ux` `release:v0.8.7`
- [#11818](https://github.com/zeroclaw-labs/zeroclaw/issues/11818) [Bug]: config set agents.* without a daemon fails with a bare "path must be shorter than SUN_LEN" for a long config dir `bug` `priority:p3` `risk:low` `cli` `topic:operator-ux` `release:v0.8.7`
- [#11817](https://github.com/zeroclaw-labs/zeroclaw/issues/11817) [Bug]: under signature_mode = strict, plugin info and plugin list --verify report an installed unsigned package as not installed `bug` `priority:p3` `risk:low` `cli` `topic:plugins` `topic:operator-ux` `release:v0.8.7`
- [#11813](https://github.com/zeroclaw-labs/zeroclaw/issues/11813) [Bug]: plugin egress connections stall when the first resolved address is blackholed and never try the others `bug` `priority:p1` `topic:plugins` `release:v0.8.6`
- [#11810](https://github.com/zeroclaw-labs/zeroclaw/issues/11810) [Task]: put an interrupted remove's claim back where it came from `release:v0.8.7`

### 🔒 Closed Issues
- [#10995](https://github.com/zeroclaw-labs/zeroclaw/issues/10995) [Feature]: Add verified plugin update with failure rollback
- [#9624](https://github.com/zeroclaw-labs/zeroclaw/issues/9624) [Bug]: Registry WIT pin diverges from master and breaks published components
- [#11491](https://github.com/zeroclaw-labs/zeroclaw/issues/11491) [Feature]: Show saved versus applied config status in ZeroCode Config

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,660 · **Open issues:** 1,551 · **Last push:** 4d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,897 · **Open issues:** 115 · **Last push:** 1h ago

### ✅ Merged PRs
- [#1307](https://github.com/moltis-org/moltis/pull/1307) feat(gateway): open the browser on first run and make the URL hard to miss

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 3d ago
- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬1 · 9d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 12d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 20d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 22d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 32d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 40d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 42d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 50d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 54d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 1 new
- [[Index] Benefit Street Partners](https://openai.com/index/benefit-street-partners/) _2026-10-17_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/singularity — top 2 new
- [Terrence Tao remarks](https://reddit.com/r/singularity/comments/1x8oxmp/terrence_tao_remarks/) ↑404
- [Researchers connected a simulated fruit fly brain to Odyssey-3, an AI that generates entire virtual worlds. The fly is now navigating these imagined environments completely on its own. A biological br](https://reddit.com/r/singularity/comments/1x8qyc7/researchers_connected_a_simulated_fruit_fly_brain/) ↑170

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Help with free tier agents](https://reddit.com/r/openclaw/comments/1x88mrq/help_with_free_tier_agents/) ↑5
- [How do you track your tasks?](https://reddit.com/r/openclaw/comments/1x8i0bc/how_do_you_track_your_tasks/) ↑3
- [Openclaw for the win - Android App (Play Store Version), SMS appoinments and reminders into my outlook.com calendar via Local LLm and Thunderbird IMAP](https://reddit.com/r/openclaw/comments/1x88nqd/openclaw_for_the_win_android_app_play_store/) ↑3
- [OpenClaw 2026.9.8 on macOS: Codex won’t load, repair tool says “Plugin codex is retiring”](https://reddit.com/r/openclaw/comments/1x8nad9/openclaw_202698_on_macos_codex_wont_load_repair/) ↑2
- [real question: OC vs muse](https://reddit.com/r/openclaw/comments/1x8m718/real_question_oc_vs_muse/) ↑2

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [Set up OpenClaw out of the box on the new 
@nvidia
 RTX Spark laptops.

Choose a local model or connect a cloud provider](https://x.com/openclaw/status/2111190844225306694)

### X — @steipete
_No new tweets since the last digest. Most recent:_
- [crabbox is underrated](https://x.com/steipete/status/2110795475075084471)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
