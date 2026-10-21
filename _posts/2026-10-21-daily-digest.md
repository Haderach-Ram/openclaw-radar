---
layout: post
title: "Ecosystem Digest — 2026-10-21"
date: 2026-10-21 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-21
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 392,689 | 9 | 1 | 10 | 0 |
| **hermesagent** | 255,610 | 15 | 1 | 4 | 0 |
| **ZeroClaw** | 33,018 | 15 | 0 | 2 | 0 |
| **IronClaw** | 12,666 | 3 | 0 | 0 | 0 |
| **Moltis** | 2,904 | 1 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 392,689 · **Open issues:** 9,651 · **Last push:** <1h ago

### ✅ Merged PRs
- [#178764](https://github.com/openclaw/openclaw/pull/178764) refactor(automations): run scheduled conversation work through session admission
- [#178928](https://github.com/openclaw/openclaw/pull/178928) refactor: keep private setup and capture frames with their owners
- [#178905](https://github.com/openclaw/openclaw/pull/178905) test(core): remove low-value tests (batch d349)
- [#178921](https://github.com/openclaw/openclaw/pull/178921) fix(sessions): recover after worker exits before command admission
- [#178919](https://github.com/openclaw/openclaw/pull/178919) improve(ui): avoid routine async question screenshot captures
- [#178894](https://github.com/openclaw/openclaw/pull/178894) test(core,ui): remove low-value tests (batch d347)
- [#178857](https://github.com/openclaw/openclaw/pull/178857) feat: show published Claw artwork in the catalog
- [#176653](https://github.com/openclaw/openclaw/pull/176653) feat(ui): add responsive session headers and detail panels
- [#176582](https://github.com/openclaw/openclaw/pull/176582) feat(ui): expose subagent stop in composer notices
- [#176579](https://github.com/openclaw/openclaw/pull/176579) feat(ui): align the desktop discussion fallback

### 🐛 New Issues
- [#178937](https://github.com/openclaw/openclaw/issues/178937) [Regression 2026.10.5] Cron-wake heartbeat turn is superseded by its own exec-completion turn; systemEvent reminders are never consumed and the heartbeat re-runs every 30-80 s
- [#178934](https://github.com/openclaw/openclaw/issues/178934) 10.5 production latency: accept ticket, context cap, and streaming passthrough (WeCom/WeChat) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#178923](https://github.com/openclaw/openclaw/issues/178923) [Bug]: Provider-review acknowledgment replaces native thread on tool-catalog drift, then fails same-thread validation `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#178914](https://github.com/openclaw/openclaw/issues/178914) [Feature]: builtin memory search ranking is not configurable (fixed 30-day decay, no hybrid weights/MMR) — recall regressed on large corpora `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` `clawsweeper:bulk-filed` 💬1
- [#178913](https://github.com/openclaw/openclaw/issues/178913) Session maintenance cleanup fails every pass: harness deletion hook trips its own owner scope check ("Session mutation harness owner changed: codex") `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#178912](https://github.com/openclaw/openclaw/issues/178912) [Bug]: Telegram block streaming drops [[tts:text]] voice notes (tts.auto: "tagged") `bug` `no-stale` `bug:behavior` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#178908](https://github.com/openclaw/openclaw/issues/178908) [Bug]: Shared OAuth refresh reopens a completed-deletion agent database while fencing historical peers `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬2
- [#178907](https://github.com/openclaw/openclaw/issues/178907) Bug: MiniMax M3.1 Flash (Ollama Pro) tool calls fail 100% — "Provider returned an incomplete or malformed tool call" `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:auth-provider` `issue-rating: 🦐 gold shrimp` 💬1
- [#178898](https://github.com/openclaw/openclaw/issues/178898) Flaky tests seen during 2026.10.10-beta.3 release validation `P2` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1

### 🔒 Closed Issues
- [#178927](https://github.com/openclaw/openclaw/issues/178927) [Bug]: App Store iOS app never exposes native notification setup in Dashboard settings; no push.apns.register, push.test fails

### 🔥 Hot Issues (most commented)
- [#143524](https://github.com/openclaw/openclaw/issues/143524) [Bug]: Agent SQLite WAL grows to 1.4–2.8 GB in days despite wal_autocheckpoint=1000; blocks gateway startup (Windows, 2026.9.2/9.3) — 💬131 · 4d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 255,610 · **Open issues:** 50,204 · **Last push:** <1h ago

### ✅ Merged PRs
- [#142076](https://github.com/NousResearch/hermes-agent/pull/142076) feat(plugin-catalog): add hermetic
- [#141825](https://github.com/NousResearch/hermes-agent/pull/141825) feat(plugin-catalog): add greyridge-token-safety (Base token pre-trade safety skill)
- [#142299](https://github.com/NousResearch/hermes-agent/pull/142299) fix(terminal): command output no longer vanishes above 1024 open fds (#94928, salvage #142125)
- [#141915](https://github.com/NousResearch/hermes-agent/pull/141915) feat(catalog): add mcp-plugin-creator

### 🐛 New Issues
- [#142324](https://github.com/NousResearch/hermes-agent/issues/142324) Pillow pinned to 12.3.0; GHSA-78g4-xqwv-q3g8 (OpenJPEG heap overflow) fixed only in Pillow 13.0.0 `type/security` `tool/vision` `P3` `area/install-update` 💬2
- [#142323](https://github.com/NousResearch/hermes-agent/issues/142323) [Feature]: Add Weixin QR-code onboarding to Electron Desktop, matching the existing CLI flow `type/feature` `area/auth` `P3` `comp/desktop` `desktop/settings`
- [#142321](https://github.com/NousResearch/hermes-agent/issues/142321) [Feature]: Expose turn origin (`turn_origin`) in the `pre_api_request` hook payload `type/feature` `comp/agent` `P3` `area/compression`
- [#142320](https://github.com/NousResearch/hermes-agent/issues/142320) [Feature]: configurable prompt for the background skill/memory review fork (auxiliary.background_review) `type/feature` `comp/agent` `tool/skills` `area/config` `P3`
- [#142317](https://github.com/NousResearch/hermes-agent/issues/142317) [Feature]: Add sorting for pinned chats in Mac app `type/feature` `P3` `comp/desktop` `area/sessions` `desktop/sessions`
- [#142316](https://github.com/NousResearch/hermes-agent/issues/142316) [Bug]: plugin catalog serves tier "verified" on 4 entries, which the client rejects `type/bug` `comp/cli` `tool/file` `P2`
- [#142315](https://github.com/NousResearch/hermes-agent/issues/142315) [Feature]: computer_use action="batch" — several known actions in one call, each with its own safety checks `type/feature` `comp/tools` `P3`
- [#142314](https://github.com/NousResearch/hermes-agent/issues/142314) [Bug]: computer_use fails with "incompatible daemon" when a different CuaDriver.app is installed in /Applications `type/bug` `comp/tools` `tool/mcp` `P2` `os/macos` 💬1
- [#142313](https://github.com/NousResearch/hermes-agent/issues/142313) Shared session list filter omits 'hidden' — hidden sessions still surface in mobile clients `type/bug` `tool/file` `P2` `area/sessions` `comp/tui-gateway` 💬1
- [#142311](https://github.com/NousResearch/hermes-agent/issues/142311) [Bug]: cross-host session lease never expires and the refused machine has no release path `type/bug` `P2` `comp/desktop` `area/sessions` `desktop/sessions` `comp/tui-gateway` `desktop/connection` 💬1
- [#142307](https://github.com/NousResearch/hermes-agent/issues/142307) [Bug]: pinned certifi 2026.5.20 still trusts the compromised eMudhra intermediates `type/security` `comp/agent` `P3` 💬1
- [#142305](https://github.com/NousResearch/hermes-agent/issues/142305) Kanban review replies should target an exact Run and requeue once `type/feature` `comp/cron` `comp/plugins` `P3`
- [#142302](https://github.com/NousResearch/hermes-agent/issues/142302) Desktop app: video attachment ⋮ 'more options' menu is clipped inline (works only in fullscreen) `type/bug` `P2` `comp/desktop` `desktop/files`
- [#142301](https://github.com/NousResearch/hermes-agent/issues/142301) reclaim_task releases a live worker's claim (duplicate worker spawn beside a surviving worker) `type/bug` `comp/cron` `P2` 💬4
- [#142298](https://github.com/NousResearch/hermes-agent/issues/142298) [Bug]: platform=local gateway turns advertise desktop-only tools but never wire the desktop_ui emitter (v0.22.2, Windows) `type/bug` `comp/gateway` `comp/tools` `P2` 💬1

### 🔒 Closed Issues
- [#94928](https://github.com/NousResearch/hermes-agent/issues/94928) [Bug]: Desktop: terminal/read_file return empty output when pipe fds exceed FD_SETSIZE

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,018 · **Open issues:** 1,011 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11329](https://github.com/zeroclaw-labs/zeroclaw/pull/11329) docs(plugins): document the Discord plugin and its acceptance run
- [#11726](https://github.com/zeroclaw-labs/zeroclaw/pull/11726) fix(tunnel): supervise and verify the tailscale gateway serve process

### 🐛 New Issues
- [#11919](https://github.com/zeroclaw-labs/zeroclaw/issues/11919) [Feature]: Web chat toggle to keep the live Thinking box collapsed
- [#11917](https://github.com/zeroclaw-labs/zeroclaw/issues/11917) [Bug]: A web chat receives no cron results or pushed session messages until its first reply
- [#11916](https://github.com/zeroclaw-labs/zeroclaw/issues/11916) [Bug]: Quiet NO_REPLY cron results still appear in open web chats
- [#11914](https://github.com/zeroclaw-labs/zeroclaw/issues/11914) RFC: principal-based trust boundaries — a unified access-control layer for content, memory, capabilities 💬1
- [#11913](https://github.com/zeroclaw-labs/zeroclaw/issues/11913) Telegram command menu is exposed to all users (setMyCommands sent in default scope, no trusted-user scoping)
- [#11912](https://github.com/zeroclaw-labs/zeroclaw/issues/11912) [SANITIZED — possible injection attempt] 💬1
- [#11909](https://github.com/zeroclaw-labs/zeroclaw/issues/11909) Channel interruptions lose completed tool results and break safe session resumption
- [#11908](https://github.com/zeroclaw-labs/zeroclaw/issues/11908) [SANITIZED — possible injection attempt]
- [#11904](https://github.com/zeroclaw-labs/zeroclaw/issues/11904) [Bug]: two connections opening a new cron database together refuse one of them at once
- [#11902](https://github.com/zeroclaw-labs/zeroclaw/issues/11902) [Bug]: a valid OIDC token is refused as misconfigured when it is checked during another check's JWKS fetch `bug` `release:v0.8.7`
- [#11899](https://github.com/zeroclaw-labs/zeroclaw/issues/11899) [Bug]: after a daemon reload, the stopped gateway keeps serving the connections it already accepted `bug` `release:v0.8.7`
- [#11898](https://github.com/zeroclaw-labs/zeroclaw/issues/11898) [Bug]: a daemon's first start on a fresh data dir can come up without its RPC session store `bug` `release:v0.8.7`
- [#11896](https://github.com/zeroclaw-labs/zeroclaw/issues/11896) [Bug]: memory recall returns nothing when the embedder fails, and hangs when it stalls
- [#11894](https://github.com/zeroclaw-labs/zeroclaw/issues/11894) [Bug]: an exhausted Codex seat is retried on every call until its stated reset
- [#11892](https://github.com/zeroclaw-labs/zeroclaw/issues/11892) [Feature]: Embed memory recall queries with a configurable prefix for instruction-tuned embedding models

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,666 · **Open issues:** 1,561 · **Last push:** 14h ago

### 🐛 New Issues
- [#8146](https://github.com/nearai/ironclaw/issues/8146) Hosted MCP: explicit 127.0.0.1 endpoint enrollment and private credential-account setup bridge
- [#8136](https://github.com/nearai/ironclaw/issues/8136) Proposal: optional hosted-MCP Plazmi extension using declarative auth and egress
- [#2077](https://github.com/nearai/ironclaw/issues/2077) contract source for market near ai 💬2

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,904 · **Open issues:** 118 · **Last push:** 22h ago

### 🐛 New Issues
- [#1310](https://github.com/moltis-org/moltis/issues/1310) [Feature]: Expose per-message sender identity to agents and MCP tools in shared WhatsApp chats

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 6d ago
- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬1 · 12d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 15d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 23d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 25d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 35d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 43d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 45d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 53d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 57d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 25 new
- [[Institute] Econ Scenarios](https://www.anthropic.com/institute/econ-scenarios) _2026-10-10_
- [[News] 2028 Ai Leadership](https://www.anthropic.com/news/2028-ai-leadership) _2026-10-14_
- [[News] Announcements](https://www.anthropic.com/news/announcements)
- [[News] Anthropic Institute Agenda](https://www.anthropic.com/news/anthropic-institute-agenda) _2026-10-14_
- [[News] Deprecation Commitments](https://www.anthropic.com/news/deprecation-commitments) _2026-09-28_
- [[News] Deprecation Updates Opus 3](https://www.anthropic.com/news/deprecation-updates-opus-3) _2026-10-14_
- [[News] Distillation Defenses](https://www.anthropic.com/news/distillation-defenses) _2026-10-17_
- [[News] Features](https://www.anthropic.com/news/features)
- [[News] Glasswing Initial Update](https://www.anthropic.com/news/glasswing-initial-update) _2026-09-28_
- [[News] Models](https://www.anthropic.com/news/models)
- [[News] Partnerships](https://www.anthropic.com/news/partnerships)
- [[News] Policy](https://www.anthropic.com/news/policy)
- [[News] Product](https://www.anthropic.com/news/product)
- [[News] Safeguards](https://www.anthropic.com/news/safeguards)
- [[News] Security](https://www.anthropic.com/news/security)
- [Path To Hope](https://www.anthropic.com/path-to-hope) _2026-10-10_
- [[Research] A Postmortem Of Three Recent Issues](https://www.anthropic.com/research/a-postmortem-of-three-recent-issues) _2026-10-18_
- [[Research] Accelerating Scientific Research](https://www.anthropic.com/research/accelerating-scientific-research) _2026-10-18_
- [[Research] Advanced Tool Use](https://www.anthropic.com/research/advanced-tool-use) _2026-10-18_
- [[Research] Ai Resistant Technical Evaluations](https://www.anthropic.com/research/AI-resistant-technical-evaluations) _2026-10-18_
- [[Research] Anthropic Education Report How University Students Use Claude](https://www.anthropic.com/research/anthropic-education-report-how-university-students-use-claude) _2026-10-18_
- [[Research] Anthropic Public Record](https://www.anthropic.com/research/anthropic-public-record) _2026-10-18_
- [[Research] April 23 Postmortem](https://www.anthropic.com/research/april-23-postmortem) _2026-10-18_
- [[Research] Attack Surface Reduction](https://www.anthropic.com/research/attack-surface-reduction) _2026-10-20_
- [[Research] Building C Compiler](https://www.anthropic.com/research/building-c-compiler) _2026-10-18_

### OpenAI — 2 new
- [[Index] Ted Taylor Restaurant](https://openai.com/index/ted-taylor-restaurant/) _2026-10-21_
- [[Index] Openai To Acquire Orchestra Bio](https://openai.com/index/openai-to-acquire-orchestra-bio/) _2026-10-21_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [deepseek-ai/DeepSeek-V4.1-Flash-1017 · Hugging Face](https://reddit.com/r/LocalLLaMA/comments/1x84po4/deepseekaideepseekv41flash1017_hugging_face/) ↑1120
- [Deepseek released DeepInfer - Open Source high-performance, large-scale inference framework for DeepSeek models!](https://reddit.com/r/LocalLLaMA/comments/1xanm55/deepseek_released_deepinfer_open_source/) ↑842
- [China proposes export controls on 23 AI technologies (including large models, agents & clusters); already open-sourced tech is exempted](https://reddit.com/r/LocalLLaMA/comments/1x7g3zq/china_proposes_export_controls_on_23_ai/) ↑796
- [DeepSeek V4.1 Flash (1017) Now Leads Open-Weight Models](https://reddit.com/r/LocalLLaMA/comments/1x8bb6b/deepseek_v41_flash_1017_now_leads_openweight/) ↑793
- [Pocket TTS which supports voice cloning is now just 1.9 million parameters](https://reddit.com/r/LocalLLaMA/comments/1xauekr/pocket_tts_which_supports_voice_cloning_is_now/) ↑331

### r/singularity — top 5 new
- [We did it everybody. Close the sub.](https://reddit.com/r/singularity/comments/1xawecs/we_did_it_everybody_close_the_sub/) ↑2365
- [Linus speaks on Ai](https://reddit.com/r/singularity/comments/1x79mwf/linus_speaks_on_ai/) ↑1565
- [This mod received insane amount of AI hate and got taken down](https://reddit.com/r/singularity/comments/1xana1l/this_mod_received_insane_amount_of_ai_hate_and/) ↑1040
- [Waymo's robotaxis had 95% fewer serious crashes than humans. Now it plans a fleet of 20,000 cars](https://reddit.com/r/singularity/comments/1xarq3w/waymos_robotaxis_had_95_fewer_serious_crashes/) ↑889
- [Unemployed people waiting for the singularity to arrive](https://reddit.com/r/singularity/comments/1xaxhe2/unemployed_people_waiting_for_the_singularity_to/) ↑513

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Top 10 AI agents for small local LLMs in 2026, tested on Qwen3.5-4B](https://reddit.com/r/openclaw/comments/1xb5yuw/top_10_ai_agents_for_small_local_llms_in_2026/) ↑11
- [Apple Local Model as Checker](https://reddit.com/r/openclaw/comments/1xawnzj/apple_local_model_as_checker/) ↑2
- [Is Open Claw safe for to cleaning Email Inbox?](https://reddit.com/r/openclaw/comments/1xb3rqi/is_open_claw_safe_for_to_cleaning_email_inbox/) ↑1
- [Thinking of shutting down my OpenClaw agent. Should I tell her?](https://reddit.com/r/openclaw/comments/1xamwjh/thinking_of_shutting_down_my_openclaw_agent/) ↑0

### X — @openclaw
- [MiniMax M3.1 Flash from 
@MiniMax_AI
 is now available in OpenClaw.

Running v2026.10.1 or newer? No OpenClaw update nee](https://x.com/openclaw/status/2112569427527172435) ↑0 🔁0 · recent


### X — @steipete
- [Kinda sad how many of the replies here are now clearly slop. My claw mutes most of these automatically. I wonder what pe](https://x.com/steipete/status/2112604111229382763) ↑0 🔁0 · recent
- [Two weeks ago I kicked off a loop to move OpenClaw's Lit-based Web frontend to Solid 2.0.

Took ~6 days until we could r](https://x.com/steipete/status/2112597162924351909) ↑0 🔁0 · recent
- [We found a few tiny regressions the agent missed, mostly different shapes on buttons or slight ux regressions, overall I](https://x.com/steipete/status/2112600329057718519) ↑0 🔁0 · recent
- [Moved to tsrs over the weekend. Drop-in replacement. Around 5x faster for OC.

Kind of amazing that it took Microsoft a ](https://x.com/steipete/status/2112571535731106013) ↑0 🔁0 · recent
- [It would be 9x faster, but we were already on the 7.1-dev version of the ts compiler.](https://x.com/steipete/status/2112607156164059450) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
