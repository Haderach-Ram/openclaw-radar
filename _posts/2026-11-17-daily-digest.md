---
layout: post
title: "Ecosystem Digest — 2026-11-17"
date: 2026-11-17 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-17
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 394,603 | 13 | 2 | 10 | 2 |
| **hermesagent** | 263,936 | 9 | 1 | 5 | 2 |
| **ZeroClaw** | 33,379 | 5 | 0 | 4 | 0 |
| **IronClaw** | 12,716 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,971 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 394,603 · **Open issues:** 8,252 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.11.4](https://github.com/openclaw/openclaw/releases/tag/v2026.11.4) — openclaw 2026.11.4
- [v2026.11.5-beta.4](https://github.com/openclaw/openclaw/releases/tag/v2026.11.5-beta.4) — openclaw 2026.11.5-beta.4

### ✅ Merged PRs
- [#200299](https://github.com/openclaw/openclaw/pull/200299) fix(worktrees): partial-clone removal times out scanning promisor packs
- [#200349](https://github.com/openclaw/openclaw/pull/200349) refactor(doctor): consolidate browser readiness tests
- [#200352](https://github.com/openclaw/openclaw/pull/200352) chore(ui): refresh control ui locales
- [#199123](https://github.com/openclaw/openclaw/pull/199123) fix(ui): selection stays stuck when clicking beside chat messages
- [#199111](https://github.com/openclaw/openclaw/pull/199111) fix(ui): restore control styling and truncate long branch names
- [#200348](https://github.com/openclaw/openclaw/pull/200348) chore(ui): refresh control ui locales
- [#200337](https://github.com/openclaw/openclaw/pull/200337) fix(ui): long tool activity summaries run past the reply text in Safari and Firefox
- [#200064](https://github.com/openclaw/openclaw/pull/200064) fix: compact tool input hints hide required arguments when a schema is wide
- [#200327](https://github.com/openclaw/openclaw/pull/200327) fix(browser): surface existing routes before access handoff
- [#200313](https://github.com/openclaw/openclaw/pull/200313) fix(ci): repair beta qualification boundaries

### 🐛 New Issues
- [#200357](https://github.com/openclaw/openclaw/issues/200357) [Bug]: Git install update refuses targets after #198661: "Declaration input escapes checkout" in preflight-build
- [#200356](https://github.com/openclaw/openclaw/issues/200356) [Bug]: Agent port back to SQLite is refused after an update ("observed changed canonical rows or allocations")
- [#200351](https://github.com/openclaw/openclaw/issues/200351) gateway status takes 16-22s on Windows 11 - blocked in spawnSync -> tasklist.exe `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#200347](https://github.com/openclaw/openclaw/issues/200347) [Bug]: Codex appServer.networkProxy permission profile drops the /tmp that workspace-write grants `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#200344](https://github.com/openclaw/openclaw/issues/200344) [Feature]: one-way A2A dispatch that also suppresses failure receipts (refile of #44309) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `issue-rating: 🐚 platinum hermit` 💬2
- [#200340](https://github.com/openclaw/openclaw/issues/200340) [Bug]: macOS app's first message fails with false "host is low on memory" because Bun's process.availableMemory() is free pages only `bug` `clawsweeper:source-repro` `P0` `issue-rating: 🦞 diamond lobster` `impact:ux-release-blocker` 💬1
- [#200336](https://github.com/openclaw/openclaw/issues/200336) Subagent completion held 30 min for an idle requester, then discarded when the requester's settle turn messages the source session ("source lifecycle changed before completion delivery") `P1` `clawsweeper:needs-info` `impact:session-state` `impact:message-loss` `issue-rating: 🦐 gold shrimp` 💬1
- [#200332](https://github.com/openclaw/openclaw/issues/200332) [Feature]: Bind explicit per-turn delivery consent to the accepted result in the plugin SDK `enhancement` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `impact:security` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#200325](https://github.com/openclaw/openclaw/issues/200325) [Bug]: Chat reports rejected saved credentials when no model is connected `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#200323](https://github.com/openclaw/openclaw/issues/200323) [Bug]: Chat shows an unconfigured built-in model as its selected default `no-stale` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#200316](https://github.com/openclaw/openclaw/issues/200316) PostgreSQL worktree cleanup fails with ambiguous value_json `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#200309](https://github.com/openclaw/openclaw/issues/200309) sessions.create fired from an authenticated Control UI client without user action resets the main session in place (context + cache prefix lost, senderId unknown) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `impact:session-state` `issue-rating: 🦪 silver shellfish` 💬1
- [#200308](https://github.com/openclaw/openclaw/issues/200308) [Feature]: Allow secret egress substitution over plain HTTP for operator-allowlisted private IPs `enhancement` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#200346](https://github.com/openclaw/openclaw/issues/200346) Control UI dictation discards long recordings on screen lock / blur, and audio is not retained for retry (mobile)
- [#44309](https://github.com/openclaw/openclaw/issues/44309) [Feature]: Add one-way dispatch mode for A2A handoffs without reply-back ping-pong

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬83 · 21h ago
- [#116201](https://github.com/openclaw/openclaw/issues/116201) Realtime voice work can retain unbounded provider and consult state — 💬59 · 45d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 263,936 · **Open issues:** 53,410 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.23.2](https://github.com/NousResearch/hermes-agent/releases/tag/v0.23.2) — Hermes Agent v0.23.2
- [v0.23.1+canary.20261116T070005Z](https://github.com/NousResearch/hermes-agent/releases/tag/v0.23.1%2Bcanary.20261116T070005Z) — Hermes Agent canary v0.23.1+canary.20261116T070005Z

### ✅ Merged PRs
- [#156554](https://github.com/NousResearch/hermes-agent/pull/156554) refactor(agent): checkpoint files move from tools/ to agent/checkpoints/
- [#156535](https://github.com/NousResearch/hermes-agent/pull/156535) refactor(plugins): plugin install scan moves from tools/ to hermes_cli/
- [#155522](https://github.com/NousResearch/hermes-agent/pull/155522) feat(plugins): catalog managed Rapid-MLX runtime
- [#156681](https://github.com/NousResearch/hermes-agent/pull/156681) fix(ci): Windows lane no longer times out replaying workflows or races a killed backup's lock
- [#156678](https://github.com/NousResearch/hermes-agent/pull/156678) fix(sessions): renaming a compressed chat from a stale tab sticks instead of reverting

### 🐛 New Issues
- [#156764](https://github.com/NousResearch/hermes-agent/issues/156764) patch: pick the edit format from the arguments and drop `mode` `type/refactor` `comp/tools` `tool/file`
- [#156763](https://github.com/NousResearch/hermes-agent/issues/156763) Tracker: a chat releases everything it started when it ends `type/bug` `comp/agent` `comp/gateway` `comp/tools`
- [#156760](https://github.com/NousResearch/hermes-agent/issues/156760) Background process wake-up renders an empty body when the output is one long line (>2000 chars) `type/bug` `comp/gateway` `tool/file` `P2`
- [#156757](https://github.com/NousResearch/hermes-agent/issues/156757) [Bug]: Desktop: a plugin page is lost on reload or when opened by its address `type/bug` `P2` `comp/desktop` `area/sessions` `desktop/settings` `desktop/sessions`
- [#156752](https://github.com/NousResearch/hermes-agent/issues/156752) [Feature]: Display-only transform hook for outbound gateway messages, plus multi-line expandable blockquotes on Telegram `type/feature` `comp/gateway` `comp/plugins` `platform/telegram` `P3`
- [#156750](https://github.com/NousResearch/hermes-agent/issues/156750) [Bug]: declared prompt-cache scope hashes two different `source` labels for one desktop conversation (gui vs local), so affinity/cache keys churn mid-session `type/bug` `comp/agent` `P2` `area/sessions`
- [#156748](https://github.com/NousResearch/hermes-agent/issues/156748) [Bug]: Named browser_exec sessions raise the headed browser window to the front (own-tab createTarget without background) `type/bug` `comp/tools` `tool/browser` `P2`
- [#156745](https://github.com/NousResearch/hermes-agent/issues/156745) [Bug]: API server 500s on a chat-completions request whose text contains a lone surrogate (session-id derivation) `type/bug` `comp/gateway` `P2` `area/sessions`
- [#156739](https://github.com/NousResearch/hermes-agent/issues/156739) Desktop renders internal context-compaction handoff summaries as normal user bubbles `type/perf` `tool/file` `P2` `comp/desktop` `area/sessions` `area/compression` `desktop/chat`

### 🔒 Closed Issues
- [#152624](https://github.com/NousResearch/hermes-agent/issues/152624) A rename sent to a compressed conversation lands on its live tip

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,379 · **Open issues:** 1,276 · **Last push:** <1h ago

### ✅ Merged PRs
- [#12335](https://github.com/zeroclaw-labs/zeroclaw/pull/12335) fix(web): keep paired WebSocket credentials out of URLs
- [#12375](https://github.com/zeroclaw-labs/zeroclaw/pull/12375) fix(web): close the model picker on Escape
- [#12374](https://github.com/zeroclaw-labs/zeroclaw/pull/12374) fix(web): show a check on the pressed "Keep thinking collapsed" button
- [#12379](https://github.com/zeroclaw-labs/zeroclaw/pull/12379) feat(providers): send output_config.effort on Anthropic requests

### 🐛 New Issues
- [#12494](https://github.com/zeroclaw-labs/zeroclaw/issues/12494) RFC: Per-agent isolated development build runner
- [#12492](https://github.com/zeroclaw-labs/zeroclaw/issues/12492) [Bug]: Dashboard chats ignore the runtime profile's thinking settings, so no native thinking config is ever sent
- [#12489](https://github.com/zeroclaw-labs/zeroclaw/issues/12489) [Bug]: cron scheduler waits for the whole due batch, so one long agent job delays all other cron jobs
- [#12477](https://github.com/zeroclaw-labs/zeroclaw/issues/12477) [Bug]: cost.enforcement.mode is ignored, so an exceeded budget always stops the turn, even in the default "warn" mode 💬1
- [#12476](https://github.com/zeroclaw-labs/zeroclaw/issues/12476) [Bug]: gateway logs every connection at INFO through spawn!, flooding the runtime trace 💬1

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,716 · **Open issues:** 1,574 · **Last push:** 7d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,971 · **Open issues:** 121 · **Last push:** 24d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬4 · 4d ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 14d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 23d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 42d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 50d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 52d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 62d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 70d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 72d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 80d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Research] Coordinated Vulnerability Disclosure Timelines](https://www.anthropic.com/research/coordinated-vulnerability-disclosure-timelines) _2026-11-16_

### OpenAI — 4 new
- [[Customer-Stories] Holiday Extras Dots](https://openai.com/business/customer-stories/holiday-extras-dots/) _2026-11-17_
- [[Science] Researcher Access](https://openai.com/science/researcher-access/) _2026-11-16_
- [[Form] Csam Classifier Intake](https://openai.com/form/csam-classifier-intake/) _2026-11-16_
- [[Index] Lvmh Media Division Partnership](https://openai.com/index/lvmh-media-division-partnership/) _2026-11-16_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [The beginning of the becoming of the beginning begins](https://reddit.com/r/LocalLLaMA/comments/1xxlich/the_beginning_of_the_becoming_of_the_beginning/) ↑1716
- [Introducing Hy4 flash](https://reddit.com/r/LocalLLaMA/comments/1xxlgpb/introducing_hy4_flash/) ↑322
- [Stop worrying about Qwen 4's AA index](https://reddit.com/r/LocalLLaMA/comments/1xxqfqr/stop_worrying_about_qwen_4s_aa_index/) ↑213
- [Open weight models account for 30% usage at enterprises to save money](https://reddit.com/r/LocalLLaMA/comments/1xxxbt9/open_weight_models_account_for_30_usage_at/) ↑163
- [Small Gemma 4 tokenizers were recently updated by Google - fix for an issue that caused nonsense output when encountering certain tokens](https://reddit.com/r/LocalLLaMA/comments/1xxxs0a/small_gemma_4_tokenizers_were_recently_updated_by/) ↑105

### r/singularity — top 2 new
- [Increase Productivity](https://reddit.com/r/singularity/comments/1xxolvw/increase_productivity/) ↑1155
- [Altman: "If the sales pitch is ... we are going to offer you a cure to cancer and cheap stuff, and the price of that is you are going to lose all agency and control and voice in the future. You are go](https://reddit.com/r/singularity/comments/1xy1q6z/altman_if_the_sales_pitch_is_we_are_going_to/) ↑305

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [What's the best place to host Claw now?](https://reddit.com/r/openclaw/comments/1xxmts5/whats_the_best_place_to_host_claw_now/) ↑15
- [Tencent’s new Hy4 Flash model is now available in OpenClaw](https://reddit.com/r/openclaw/comments/1xy60kq/tencents_new_hy4_flash_model_is_now_available_in/) ↑11
- [OpenClaw v2026.11.4 patch fixes Signal reconnects, WhatsApp replies and recovery copies](https://reddit.com/r/openclaw/comments/1xxvswh/openclaw_v2026114_patch_fixes_signal_reconnects/) ↑5
- [I changed from Sol 5.6 to 6.1 and what a downgrade](https://reddit.com/r/openclaw/comments/1xxzh1m/i_changed_from_sol_56_to_61_and_what_a_downgrade/) ↑4
- [How we’ve been getting OpenClaw’s CI under control](https://reddit.com/r/openclaw/comments/1xy53x0/how_weve_been_getting_openclaws_ci_under_control/) ↑3

### X — @openclaw
- [Hy4 Flash from 
@TencentHunyuan
 is now available in OpenClaw. 🦞

Tencent reports that, in WorkBuddy evaluations, it mat](https://x.com/openclaw/status/2122485133597114682) ↑0 🔁0 · recent
- [OpenClaw was spending a claw and a tail on CI 

Then 
@vincent_koc
 dug in and uncovered things that not only saved us m](https://x.com/openclaw/status/2122451216093573217) ↑0 🔁0 · recent
- [OpenClaw 2026.11.4 patch

📨 Fixes skipped buffered Signal messages on reconnect
💬 WhatsApp final replies survive unrelat](https://x.com/openclaw/status/2122379635434607039) ↑0 🔁0 · recent


### X — @steipete
- [People: Please reduce the number of permission alerts so agents can work on macOS without constant babysitting

Apple: I](https://x.com/steipete/status/2122463466304971068) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
