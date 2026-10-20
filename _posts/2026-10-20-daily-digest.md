---
layout: post
title: "Ecosystem Digest — 2026-10-20"
date: 2026-10-20 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-20
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 392,713 | 3 | 0 | 10 | 1 |
| **hermesagent** | 255,296 | 13 | 0 | 0 | 0 |
| **ZeroClaw** | 33,006 | 6 | 2 | 10 | 0 |
| **IronClaw** | 12,666 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,902 | 0 | 0 | 0 | 1 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 392,713 · **Open issues:** 9,587 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.10.10-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.10.10-beta.2) — openclaw 2026.10.10-beta.2

### ✅ Merged PRs
- [#177843](https://github.com/openclaw/openclaw/pull/177843) fix(doctor): preserve node-only identities during Mac packaging
- [#177907](https://github.com/openclaw/openclaw/pull/177907) refactor(shared): reuse tracked cancellation resource ownership
- [#177660](https://github.com/openclaw/openclaw/pull/177660) refactor(ui): derive page views from canonical owners
- [#177890](https://github.com/openclaw/openclaw/pull/177890) refactor(ui): infer composer controls from their producer
- [#177900](https://github.com/openclaw/openclaw/pull/177900) refactor: derive chat view contracts from their owners
- [#177895](https://github.com/openclaw/openclaw/pull/177895) refactor(ui): simplify chat send staging and delivery
- [#177912](https://github.com/openclaw/openclaw/pull/177912) refactor(ui): trust leaf owners and remove unused state
- [#177819](https://github.com/openclaw/openclaw/pull/177819) fix: keep session files within permitted workspaces
- [#177901](https://github.com/openclaw/openclaw/pull/177901) fix(lmstudio): retry model loading after correcting credentials
- [#177793](https://github.com/openclaw/openclaw/pull/177793) refactor(ui): render panel placeholders directly

### 🐛 New Issues
- [#177952](https://github.com/openclaw/openclaw/issues/177952) Update failure: requested (2026.9.9) 💬1
- [#177930](https://github.com/openclaw/openclaw/issues/177930) [Bug]: Telegram automation list/get succeeds but many existing jobs reject run-history access; owner recovery unclear (2026.10.5) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#177927](https://github.com/openclaw/openclaw/issues/177927) [Feature]: Per-agent access control for paired nodes (personal devices in multi-person Gateways) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `impact:security` `issue-rating: 🌊 off-meta tidepool` `clawsweeper:bulk-filed` 💬1

### 🔥 Hot Issues (most commented)
- [#143524](https://github.com/openclaw/openclaw/issues/143524) [Bug]: Agent SQLite WAL grows to 1.4–2.8 GB in days despite wal_autocheckpoint=1000; blocks gateway startup (Windows, 2026.9.2/9.3) — 💬131 · 3d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 255,296 · **Open issues:** 50,076 · **Last push:** <1h ago

### 🐛 New Issues
- [#141826](https://github.com/NousResearch/hermes-agent/issues/141826) Bot chats resolve /model against the provider registry frozen at creation; providers added later always fail with model_resolution_failed (lineage children inherit the stale snapshot) `type/bug` `comp/gateway` `area/config` `P2` `area/sessions` 💬1
- [#141824](https://github.com/NousResearch/hermes-agent/issues/141824) [Bug]: High aggregate usage and incomplete delegation handoffs in multi-lane Discord operation `type/bug` `comp/agent` `tool/delegate` `P2` `area/billing`
- [#141822](https://github.com/NousResearch/hermes-agent/issues/141822) [Bug]: Human messages starve behind internal background-process wakes; depth-cap requeue and the shared queue cap can drop them `type/bug` `comp/gateway` `P2` 💬1
- [#141821](https://github.com/NousResearch/hermes-agent/issues/141821) [Bug]: Slack file captions are sent unformatted (markdown kept as written, broadcast mentions not escaped) `type/bug` `comp/plugins` `platform/slack` `P2`
- [#141820](https://github.com/NousResearch/hermes-agent/issues/141820) [Bug]: Infinite fallback loop to non-existent 'gpt-6.1-sol' on HTTP 400/404 errors in _mkm-integration branch `type/bug` `comp/agent` `comp/cli` `area/auth` `area/config` `P2`
- [#141819](https://github.com/NousResearch/hermes-agent/issues/141819) [Bug]: Linux x64 CUDA engine (b11370) requires GLIBC_2.38 — managed local runtime is uninstallable on Ubuntu 22.04/Debian 12/RHEL 9 NVIDIA hosts, and `auto` won't fall back to the working Vulkan build `type/bug` `P2` `area/install-update` `area/local-models` `cause/upstream` 💬2
- [#141816](https://github.com/NousResearch/hermes-agent/issues/141816) [Feature]: Translate the reasoning/thinking display (opt-in) — and a reasoning contribution area for the desktop plugin SDK `type/feature` `P3` `comp/desktop` `area/streaming` `area/i18n` `desktop/settings` `desktop/chat`
- [#141813](https://github.com/NousResearch/hermes-agent/issues/141813) Stock Desktop conversations can remain on Loading session when switching tabs `type/bug` `P2` `comp/desktop` `area/sessions` `desktop/sessions`
- [#141808](https://github.com/NousResearch/hermes-agent/issues/141808) Cron loses typed connection-failure classification when a failed turn is returned as a dict `type/bug` `comp/agent` `comp/cron` `P2` 💬1
- [#141807](https://github.com/NousResearch/hermes-agent/issues/141807) [Bug]: ChatGPT OAuth gpt-image-2 requests disconnect near 60s despite 300s read timeout (v0.22.2) `type/bug` `comp/plugins` `tool/vision` `provider/openai` `P2`
- [#141806](https://github.com/NousResearch/hermes-agent/issues/141806) [Bug]: streamed replies skip extract_images — markdown images arrive as '!alt' text on Discord `type/bug` `comp/gateway` `platform/discord` `P2` `area/streaming` 💬3
- [#141803](https://github.com/NousResearch/hermes-agent/issues/141803) [Bug]: v0.22.2 release follow-up: onboarding Path import still breaks supported Python 3.12 (fix already on main) `type/bug` `P2` `comp/tui-gateway` 💬1
- [#141799](https://github.com/NousResearch/hermes-agent/issues/141799) Desktop 'Branch in new chat': branch mis-positioned when the clicked message lies inside a compacted region `type/bug` `P2` `comp/desktop` `area/sessions` `area/compression` `desktop/chat` `desktop/sessions`

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,006 · **Open issues:** 982 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11726](https://github.com/zeroclaw-labs/zeroclaw/pull/11726) fix(tunnel): supervise and verify the tailscale gateway serve process
- [#11157](https://github.com/zeroclaw-labs/zeroclaw/pull/11157) test(codex): cover empty prompt argument
- [#11155](https://github.com/zeroclaw-labs/zeroclaw/pull/11155) test(browser): cover normalized backend aliases
- [#11154](https://github.com/zeroclaw-labs/zeroclaw/pull/11154) test(runtime): cover missing follow log streams
- [#11148](https://github.com/zeroclaw-labs/zeroclaw/pull/11148) fix(cli): enable UTF-8 erase mode in interactive REPL
- [#11143](https://github.com/zeroclaw-labs/zeroclaw/pull/11143) fix(memory): apply time bounds to qdrant vector search
- [#11140](https://github.com/zeroclaw-labs/zeroclaw/pull/11140) test(tools): share runtime proxy state guard
- [#11595](https://github.com/zeroclaw-labs/zeroclaw/pull/11595) test(channels): cover the daemon's live channel-map factory
- [#11637](https://github.com/zeroclaw-labs/zeroclaw/pull/11637) fix(providers): stop charging JPEG coefficient planes zune-jpeg never allocates
- [#11399](https://github.com/zeroclaw-labs/zeroclaw/pull/11399) fix(zerocode): save sidebar changes while another reader has the config open

### 🐛 New Issues
- [#11876](https://github.com/zeroclaw-labs/zeroclaw/issues/11876) RFC: Focus PR review on purpose, safety, and quality `type:rfc`
- [#11873](https://github.com/zeroclaw-labs/zeroclaw/issues/11873) [Bug]: long channel turns remain silent and whole-turn timeout blames the model
- [#11870](https://github.com/zeroclaw-labs/zeroclaw/issues/11870) RFC: Per-user pairing sessions for browser login and outage-safe KB delegation 💬2
- [#11867](https://github.com/zeroclaw-labs/zeroclaw/issues/11867) [Feature]: task-scoped SSH reuse, deterministic cleanup and idle watchdog
- [#11866](https://github.com/zeroclaw-labs/zeroclaw/issues/11866) [Bug]: loop detector executes blocked repeats and loses partial task closeout
- [#11864](https://github.com/zeroclaw-labs/zeroclaw/issues/11864) [Feature]: Fail closed when the locked zune-jpeg version changes under the JPEG memory projection

### 🔒 Closed Issues
- [#11865](https://github.com/zeroclaw-labs/zeroclaw/issues/11865) [Bug]: WhatsApp Web allowlist rejects senders on a linked device (device suffix kept in the JID digits)
- [#11087](https://github.com/zeroclaw-labs/zeroclaw/issues/11087) [Bug]: Windows — after closing the window the app can be neither reopened nor quit

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,666 · **Open issues:** 1,555 · **Last push:** 4h ago

### 🐛 New Issues
- [#8143](https://github.com/nearai/ironclaw/issues/8143) Daily ironclaw failure taxonomy — 2026-10-19

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,902 · **Open issues:** 115 · **Last push:** 17h ago

### 🚀 New Releases
- [20261019.01](https://github.com/moltis-org/moltis/releases/tag/20261019.01) — 20261019.01

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 5d ago
- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬1 · 11d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 14d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 22d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 24d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 34d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 42d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 44d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 52d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 56d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 2 new
- [[Partners] Insight Enterprises](https://openai.com/business/partners/insight-enterprises/) _2026-10-20_
- [[Business] Contact Sales Retail](https://openai.com/business/contact-sales-retail/) _2026-10-20_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [MiniMax M3.1 Flash released, Model weights Oct 23](https://reddit.com/r/LocalLLaMA/comments/1x9uzv9/minimax_m31_flash_released_model_weights_oct_23/) ↑542
- [Let's delve into the tapestry of AI slop on r/LocalLLaMA](https://reddit.com/r/LocalLLaMA/comments/1xa7hi8/lets_delve_into_the_tapestry_of_ai_slop_on/) ↑121

### r/singularity — top 2 new
- [Rumours are floating](https://reddit.com/r/singularity/comments/1xa73il/rumours_are_floating/) ↑798
- [2026 Fields Medalist John Pardon says AI now understands even his messiest mathematical proofs, catches subtle errors, and proves nontrivial results. “The AI understands. 100%.” Just a year ago, he wo](https://reddit.com/r/singularity/comments/1xaernx/2026_fields_medalist_john_pardon_says_ai_now/) ↑123

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw v2026.10.5 | Refreshed sidebar, Skill Workshop 2.0, public conversation links and MORE!!](https://reddit.com/r/openclaw/comments/1xa77t8/openclaw_v2026105_refreshed_sidebar_skill/) ↑19
- [Openclaw ram usage](https://reddit.com/r/openclaw/comments/1x9qc1v/openclaw_ram_usage/) ↑13
- [Hermes is a Lobster's Best Friend.](https://reddit.com/r/openclaw/comments/1xa91i3/hermes_is_a_lobsters_best_friend/) ↑8
- [Exec approval, gog](https://reddit.com/r/openclaw/comments/1xad4ot/exec_approval_gog/) ↑4
- [Openclaw Home wifi defender](https://reddit.com/r/openclaw/comments/1xa6q2k/openclaw_home_wifi_defender/) ↑4

### X — @openclaw
- [🦞 OpenClaw v2026.10.5 is out!

🤖 Sidebar keeps your agents within reach
↩️ Skill Workshop 2.0 gets Undo
🔗 Public convers](https://x.com/openclaw/status/2112260434116108528) ↑0 🔁0 · recent


### X — @steipete
_No new tweets since the last digest. Most recent:_
- [AI;DR](https://x.com/steipete/status/2111918049116987476)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
