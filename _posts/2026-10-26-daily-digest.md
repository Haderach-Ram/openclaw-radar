---
layout: post
title: "Ecosystem Digest — 2026-10-26"
date: 2026-10-26 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-26
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 393,055 | 4 | 0 | 10 | 0 |
| **hermesagent** | 257,077 | 7 | 3 | 10 | 0 |
| **ZeroClaw** | 33,042 | 3 | 1 | 0 | 0 |
| **IronClaw** | 12,675 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,911 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 393,055 · **Open issues:** 7,852 · **Last push:** <1h ago

### ✅ Merged PRs
- [#184048](https://github.com/openclaw/openclaw/pull/184048) test(agents,channels,chat): remove low-value tests (batch d582)
- [#184054](https://github.com/openclaw/openclaw/pull/184054) perf(core): remove redundant cron and config object copies
- [#183827](https://github.com/openclaw/openclaw/pull/183827) feat(sessions): archive oversized transcripts as bounded cold chunks
- [#184072](https://github.com/openclaw/openclaw/pull/184072) perf(plugins): reduce repeated catalog work when listing plugins
- [#184055](https://github.com/openclaw/openclaw/pull/184055) perf(sessions): avoid copying contained archive records
- [#182859](https://github.com/openclaw/openclaw/pull/182859) fix(daemon): keep scheduled-task fallback waits on the monotonic clock
- [#184003](https://github.com/openclaw/openclaw/pull/184003) perf: reduce Talk caption and hidden meter CPU
- [#184029](https://github.com/openclaw/openclaw/pull/184029) test: remove low-value tests (batch d581)
- [#183193](https://github.com/openclaw/openclaw/pull/183193) fix(logging): Google OAuth client secrets appear unmasked in log output
- [#184074](https://github.com/openclaw/openclaw/pull/184074) perf(plugins): remove redundant outbound object copies

### 🐛 New Issues
- [#184095](https://github.com/openclaw/openclaw/issues/184095) [Feature]: Read Discord scheduled-event subscribers through the message tool
- [#184068](https://github.com/openclaw/openclaw/issues/184068) [Bug]: Skills prompt says to call `skills_read` directly, but default Tool Search does not send it to the model, so the call fails `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬2
- [#184067](https://github.com/openclaw/openclaw/issues/184067) [Bug]: macOS bundled Bun Gateway retains 3.9–4.5 GB after tool work and config reloads `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#184060](https://github.com/openclaw/openclaw/issues/184060) [Bug]: Discord outbound projections drop AbortSignal before abort-aware client `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `maturity:stable` 💬1

### 🔥 Hot Issues (most commented)
- [#143524](https://github.com/openclaw/openclaw/issues/143524) [Bug]: Agent SQLite WAL grows to 1.4–2.8 GB in days despite wal_autocheckpoint=1000; blocks gateway startup (Windows, 2026.9.2/9.3) — 💬137 · <1h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 257,077 · **Open issues:** 51,103 · **Last push:** <1h ago

### ✅ Merged PRs
- [#134362](https://github.com/NousResearch/hermes-agent/pull/134362) Route every config.yaml read and write through a ConfigBackend seam (salvage #122245)
- [#144759](https://github.com/NousResearch/hermes-agent/pull/144759) Stopping a turn no longer kills background subagents like /review (salvage #50453)
- [#144630](https://github.com/NousResearch/hermes-agent/pull/144630) optimize-storage shows progress in every phase and finishes several times faster
- [#144647](https://github.com/NousResearch/hermes-agent/pull/144647) Git version lookups stay fast: Hermes keeps the commit graph fresh and clears stale commit-graph locks
- [#144640](https://github.com/NousResearch/hermes-agent/pull/144640) Hermes starts ~1 s faster from a git checkout: provider plugins and the restart check no longer run the git version walk
- [#144625](https://github.com/NousResearch/hermes-agent/pull/144625) Startup no longer waits for the scratch-dir prune (fixes #143397, salvage #143398)
- [#144710](https://github.com/NousResearch/hermes-agent/pull/144710) fix(tts): find_voices={} browses voices instead of falling to speech
- [#144594](https://github.com/NousResearch/hermes-agent/pull/144594) fix(gateway): settle a sibling profile's server request from the shared socket
- [#144593](https://github.com/NousResearch/hermes-agent/pull/144593) fix(gateway): run managed workers on WSL2 and on their resolved provider route
- [#144596](https://github.com/NousResearch/hermes-agent/pull/144596) fix(gateway): remote Desktop session edits for served logins and SSH serve

### 🐛 New Issues
- [#144766](https://github.com/NousResearch/hermes-agent/issues/144766) Browser readiness: native READY can precede cold dashboard/WebSocket preparation `type/bug` `comp/cli` `comp/gateway` `tool/browser` `P2`
- [#144761](https://github.com/NousResearch/hermes-agent/issues/144761) [Bug]: API reports cancelled while owned background processes survive stop or SSE disconnect (v0.22.5) `type/bug` `comp/gateway` `tool/terminal` `backend/local` `backend/docker` `P2` `area/streaming`
- [#144754](https://github.com/NousResearch/hermes-agent/issues/144754) Update-restart obligation undischargeable on launchd hosts: one PID recorded as both mapped and stopped_unmapped; fails closed even when restarted.sha == HEAD `type/bug` `comp/cli` `P2` `area/install-update` `os/macos` 💬1
- [#144753](https://github.com/NousResearch/hermes-agent/issues/144753) gateway stop --yes crashes with TypeError: ManagedWorker.interrupt() takes 1 positional argument but 2 were given (v0.22.5) `type/bug` `comp/gateway` `P2` 💬2
- [#144750](https://github.com/NousResearch/hermes-agent/issues/144750) checkout_lock_held() probe is observable: parallel readers turn each other's probe into 'Gateway draining: update_paused' `type/bug` `comp/cli` `P2` 💬1
- [#144749](https://github.com/NousResearch/hermes-agent/issues/144749) anthropic_messages wire dies at worker boot after a re-seed drops the anthropic extra; error names 'the Anthropic provider' on non-Anthropic routes `type/bug` `comp/agent` `P2` `area/install-update` `provider/other` 💬1
- [#144748](https://github.com/NousResearch/hermes-agent/issues/144748) `hermes update` pre-update sibling snapshots adopt a deleted (tombstoned) profile dir — `_sibling_profile_homes` is tombstone-unaware `type/bug` `comp/cli` `tool/file` `P3` `area/install-update` `area/profiles`

### 🔒 Closed Issues
- [#142606](https://github.com/NousResearch/hermes-agent/issues/142606) [Bug]: Desktop Stop terminates previous-turn background tasks and subagents when interrupting the current reply
- [#143397](https://github.com/NousResearch/hermes-agent/issues/143397) First system-prompt build runs the scratch prune synchronously and can stall a user turn for tens of seconds (macOS launchd / Windows)
- [#144743](https://github.com/NousResearch/hermes-agent/issues/144743) browser_vault: can't fill saved cards from 1Password or into hosted payment iframes

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,042 · **Open issues:** 1,058 · **Last push:** 11h ago

### 🐛 New Issues
- [#12035](https://github.com/zeroclaw-labs/zeroclaw/issues/12035) knowledge_bundles is validated but never consumed at runtime, with no warning
- [#12022](https://github.com/zeroclaw-labs/zeroclaw/issues/12022) [Feature]: memory recall: an opt-in external rerank stage over the eligible candidate pool
- [#12021](https://github.com/zeroclaw-labs/zeroclaw/issues/12021) [Bug]: When saving configuration settings via the banner in the web ui, the config group save button is still highlighted afterwards `bug`

### 🔒 Closed Issues
- [#12034](https://github.com/zeroclaw-labs/zeroclaw/issues/12034) RFC: Personal Agent MVP: visitor-facing knowledge-and-request subsystem

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,675 · **Open issues:** 1,565 · **Last push:** 5h ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,911 · **Open issues:** 119 · **Last push:** 2d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬2 · 1d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 1d ago
- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 11d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 20d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 28d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 30d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 40d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 48d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 50d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 58d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

_No new posts in the last 24h._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
