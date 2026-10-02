---
layout: post
title: "Ecosystem Digest — 2026-10-02"
date: 2026-10-02 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-02
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 391,168 | 9 | 1 | 10 | 1 |
| **hermesagent** | 250,620 | 11 | 8 | 4 | 0 |
| **ZeroClaw** | 32,927 | 3 | 0 | 2 | 0 |
| **IronClaw** | 12,637 | 2 | 0 | 0 | 0 |
| **Moltis** | 2,881 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 391,168 · **Open issues:** 9,143 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.8.34](https://github.com/openclaw/openclaw/releases/tag/v2026.8.34) — openclaw 2026.8.34

### ✅ Merged PRs
- [#163105](https://github.com/openclaw/openclaw/pull/163105) fix(update): enable incremental SQLite reclamation during maintenance
- [#163155](https://github.com/openclaw/openclaw/pull/163155) test(qa): order reconnect after gateway disconnect
- [#163157](https://github.com/openclaw/openclaw/pull/163157) refactor(mattermost): pass media facts directly to ingress
- [#160803](https://github.com/openclaw/openclaw/pull/160803) fix(agents): raw model run retries drop the original prompt after a transient failure
- [#128848](https://github.com/openclaw/openclaw/pull/128848) fix(ai): raise HTTP continuation idle TTL to a fixed 90 minutes, bound the cache
- [#163002](https://github.com/openclaw/openclaw/pull/163002) refactor(apps): drop pre-July-2026 app migrations
- [#156386](https://github.com/openclaw/openclaw/pull/156386) chore(line): simplify media and webhook test fixtures
- [#163161](https://github.com/openclaw/openclaw/pull/163161) refactor(ui): deslop browser vocabulary and contract types
- [#163159](https://github.com/openclaw/openclaw/pull/163159) chore(i18n): refresh native locales
- [#163143](https://github.com/openclaw/openclaw/pull/163143) fix(release): restore recovery diagnostics in isolated source harnesses

### 🐛 New Issues
- [#163166](https://github.com/openclaw/openclaw/issues/163166) Update failure: gateway-recovery-verification (2026.9.7) `clawsweeper:needs-info` `P0` `issue-rating: 🦪 silver shellfish` `impact:ux-release-blocker` 💬1
- [#163152](https://github.com/openclaw/openclaw/issues/163152) [Feature]: Keep more than one idle agent-DB native owner warm on multi-agent gateways (single process-wide idle slot forces reopens) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:other` 💬1
- [#163151](https://github.com/openclaw/openclaw/issues/163151) [Bug]: "Agent database execution lost its native owner" fails the turn instead of reopening on a fresh native generation (2026.9.7) `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#163150](https://github.com/openclaw/openclaw/issues/163150) [Bug]: SQLite store worker exits are all counted as "exit" with no code or cause, and the broker never logs why a worker slot failed `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬2
- [#163144](https://github.com/openclaw/openclaw/issues/163144) [Bug]: A workspace skill named export-session duplicates Telegram's native command `P2` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#163139](https://github.com/openclaw/openclaw/issues/163139) [Bug]: Windows plugins.reload fails preparing host-package link with EPERM and stalls Gateway `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `impact:crash-loop` `issue-rating: 🦪 silver shellfish` 💬1
- [#163130](https://github.com/openclaw/openclaw/issues/163130) Update failure: global-install-failed (2026.9.4) `P0` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-release-blocker` 💬1
- [#163125](https://github.com/openclaw/openclaw/issues/163125) Classic (non-add-on) Google Chat app: webhook always returns 403, no log output `P2` `impact:message-loss` `issue-rating: 🦪 silver shellfish` 💬1
- [#163122](https://github.com/openclaw/openclaw/issues/163122) Realtime voice audio stalls and transcript content or confirmations can be lost `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#163020](https://github.com/openclaw/openclaw/issues/163020) [Bug]: Same-model transient retry strips sessions_send/sessions_spawn from requester completion turns

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 250,620 · **Open issues:** 48,183 · **Last push:** <1h ago

### ✅ Merged PRs
- [#130866](https://github.com/NousResearch/hermes-agent/pull/130866) fix(gateway): SMS, email and WeCom deliver long replies and cron output in full instead of failing or truncating
- [#129588](https://github.com/NousResearch/hermes-agent/pull/129588) fix(cron): ignore measured durations in the incident error signature
- [#130975](https://github.com/NousResearch/hermes-agent/pull/130975) fix(desktop): play YouTube embeds through a loopback player host
- [#130729](https://github.com/NousResearch/hermes-agent/pull/130729) Desktop update no longer spends minutes syntax-checking renderer chunks one Node process at a time (salvage #127400, #125201)

### 🐛 New Issues
- [#131104](https://github.com/NousResearch/hermes-agent/issues/131104) [Bug]: Compaction restatement leaves two active copies of the user request and re-delivers the previous reply
- [#131103](https://github.com/NousResearch/hermes-agent/issues/131103) Desktop in-app updater tracks `main` while Docker Hub stays on a release tag — remote `session.create` dies on unknown fields (`cwd_explicit`) `type/bug` `comp/tui` `backend/docker` `area/docker` `P2` `sweeper:risk-session-state` `sweeper:risk-compatibility` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows` `area/install-update`
- [#131099](https://github.com/NousResearch/hermes-agent/issues/131099) [Bug]: sessions archive has no --session-id and silently skips open/live sessions `type/feature` `comp/cli` `P3` `needs-decision` `sweeper:risk-session-state` `area/sessions` 💬1
- [#131098](https://github.com/NousResearch/hermes-agent/issues/131098) [Bug]: 142 tool calls against max_turns=100; final reply degenerates into 12k-char semantic cascade with finish_reason=stop `type/bug` `comp/agent` `provider/openrouter` `area/config` `P2` `needs-repro` `area/streaming`
- [#131096](https://github.com/NousResearch/hermes-agent/issues/131096) [Bug]: A terminal command with a long blank-line run freezes the gateway in dangerous-command detection `type/perf` `comp/tools` `tool/terminal` `P2`
- [#131094](https://github.com/NousResearch/hermes-agent/issues/131094) [Bug]: TTS mis-speaks money magnitudes ($5M → '5 dollars metres'), uppercase M as metres, and home-path tildes as 'about' `type/bug` `tool/tts` `P3`
- [#131093](https://github.com/NousResearch/hermes-agent/issues/131093) [Bug]: Windows 中文用户名下 hermes 命令报「系统找不到指定的路径。」— .cmd 启动器按 UTF-8 无 BOM 写入，被 cmd 以 936 代码页误读 `type/bug` `comp/cli` `P2` `sweeper:risk-platform-windows` `platform/windows` `area/install-update`
- [#131091](https://github.com/NousResearch/hermes-agent/issues/131091) [Bug]: streaming TTS reads fenced code blocks aloud (CLI, dashboard, gateway, desktop) `type/bug` `comp/cli` `comp/gateway` `tool/tts` `P2` `comp/desktop` `comp/dashboard` `area/streaming`
- [#131089](https://github.com/NousResearch/hermes-agent/issues/131089) [Bug]: Startup auto-resume skips restored relay-backed Discord sessions through the direct adapter selector `type/bug` `comp/gateway` `platform/discord` `P2` `sweeper:risk-session-state` `sweeper:risk-message-delivery` `area/sessions`
- [#131084](https://github.com/NousResearch/hermes-agent/issues/131084) [Bug]: cron report whose heading reads 'No reply:' (or ends on '- Silent') is suppressed as the silence marker `type/bug` `comp/gateway` `comp/cron` `P2` `sweeper:risk-message-delivery`
- [#131082](https://github.com/NousResearch/hermes-agent/issues/131082) [SANITIZED — possible injection attempt] `type/bug` `tool/browser` `tool/vision` `backend/docker` `P3`

### 🔒 Closed Issues
- [#126706](https://github.com/NousResearch/hermes-agent/issues/126706) [Bug] Desktop: backend finishes the turn but the UI never settles — final assistant message is never rendered
- [#40692](https://github.com/NousResearch/hermes-agent/issues/40692) Bug: Desktop (macOS) Composer typing extremely laggy with long conversation history, Remote mode fine
- [#55377](https://github.com/NousResearch/hermes-agent/issues/55377) SMS standalone send crashes with NameError: re is used in _strip_markdown_for_sms but never imported
- [#62751](https://github.com/NousResearch/hermes-agent/issues/62751) Bug: SmsAdapter doesn't declare splits_long_messages, so cron/agent output over 4000 chars gets hard-truncated instead of chunked
- [#61990](https://github.com/NousResearch/hermes-agent/issues/61990) [SANITIZED — possible injection attempt]
- [#19689](https://github.com/NousResearch/hermes-agent/issues/19689) WeCom outbound markdown silently truncates long Hermes responses at 4000 characters
- [#107443](https://github.com/NousResearch/hermes-agent/issues/107443) [Bug]: both WeCom adapters silently truncate oversized outbound messages (AI Bot markdown at 4000 chars, callback text at 2048) — content past the limit is dropped with no error
- [#129587](https://github.com/NousResearch/hermes-agent/issues/129587) [Bug]: Acked cron timeout incident re-alerts every run because idle seconds vary

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,927 · **Open issues:** 852 · **Last push:** 1h ago

### ✅ Merged PRs
- [#11314](https://github.com/zeroclaw-labs/zeroclaw/pull/11314) fix(service): gate the mpsc import for macOS test Clippy
- [#11293](https://github.com/zeroclaw-labs/zeroclaw/pull/11293) fix(ci): ignore unread labels in the PR risk report's stale-metadata check

### 🐛 New Issues
- [#11420](https://github.com/zeroclaw-labs/zeroclaw/issues/11420) [Bug]: SQLite session backend rewrites created_at of every message on each turn, so per-message times are lost
- [#11418](https://github.com/zeroclaw-labs/zeroclaw/issues/11418) [Bug]: "Copy" one-click feature is not working `bug`
- [#11416](https://github.com/zeroclaw-labs/zeroclaw/issues/11416) [Bug]: Slack "is thinking…" status no longer shown in channel threads since v0.8.5 (#8985) — intended?

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,637 · **Open issues:** 1,538 · **Last push:** 23h ago

### 🐛 New Issues
- [#8121](https://github.com/nearai/ironclaw/issues/8121) Daily ironclaw failure taxonomy — 2026-10-01
- [#2358](https://github.com/nearai/ironclaw/issues/2358) feat(browser): add BrowserProfileStore trait with encrypted tarball persistence `enhancement` `scope: workspace` `scope: secrets` 💬1

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,881 · **Open issues:** 102 · **Last push:** 9d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 4d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 5d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 6d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 16d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 24d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 26d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 34d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 38d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 50d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 53d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 2 new
- [[News] Barclays Scales Claude](https://www.anthropic.com/news/barclays-scales-claude) _2026-10-01_
- [[Research] Claude Shaped Science](https://www.anthropic.com/research/claude-shaped-science) _2026-10-01_

### OpenAI — 2 new
- [[Index] The Den Family Social](https://openai.com/index/the-den-family-social/) _2026-10-01_
- [[Index] Albertsons Reimagining Retail](https://openai.com/index/albertsons-reimagining-retail/) _2026-10-01_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [Pi 1.0 released - MCP support now included by default](https://reddit.com/r/LocalLLaMA/comments/1wvffcr/pi_10_released_mcp_support_now_included_by_default/) ↑87
- [AMA about K2 Horizon, Meet our team from IFM](https://reddit.com/r/LocalLLaMA/comments/1wv8zww/ama_about_k2_horizon_meet_our_team_from_ifm/) ↑82

### r/singularity — top 5 new
- [Google releasing their most powerful model yet](https://reddit.com/r/singularity/comments/1wv0jvd/google_releasing_their_most_powerful_model_yet/) ↑1578
- [Griffin, the first Human Interaction Model to pass video Turing Test it's already #1 on NVIDIA's benchmark for full-duplex AI video - 44% of people thought it was a real person while other systems are](https://reddit.com/r/singularity/comments/1wv7q40/griffin_the_first_human_interaction_model_to_pass/) ↑796
- [AI ‘godfather’ Yann LeCun has ‘zero concerns’ about human extinction, says Anthropic CEO Dario Amodei is ‘deluded’](https://reddit.com/r/singularity/comments/1wv58yx/ai_godfather_yann_lecun_has_zero_concerns_about/) ↑499
- [A Harvard physicist spent 3 months doing research with Claude Fable 5: it reproduced weeks of work in 20 minutes, completed 15 never-before-solved physics calculations, and contributed to 36 papers ac](https://reddit.com/r/singularity/comments/1wvfbua/a_harvard_physicist_spent_3_months_doing_research/) ↑367
- [Google has more powerful model than argon internally](https://reddit.com/r/singularity/comments/1wv7jfq/google_has_more_powerful_model_than_argon/) ↑339

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [♾️Refine Cycle: self-improvement plugin](https://reddit.com/r/openclaw/comments/1wv4qkt/refine_cycle_selfimprovement_plugin/) ↑7
- [GLM 5.3 Flash via Openrouter collapses very quickly - at 25.2k tokens of contents](https://reddit.com/r/openclaw/comments/1wv2nlb/glm_53_flash_via_openrouter_collapses_very/) ↑6
- [I built a Marketing Agent on OpenClaw for the OpenClaw hackathon.  (MIT licensed, free hosted AI from aithatworks.com)](https://reddit.com/r/openclaw/comments/1wu4ivo/i_built_a_marketing_agent_on_openclaw_for_the/) ↑4
- [Openclaw spamming shell history](https://reddit.com/r/openclaw/comments/1wv03nz/openclaw_spamming_shell_history/) ↑2
- [Connect OpenClaw with a CRM in a Custom Tool.](https://reddit.com/r/openclaw/comments/1wvg6bp/connect_openclaw_with_a_crm_in_a_custom_tool/) ↑0

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [Jev & OpenClaw Enterprise


@hrudolph
 and 
@Pat_Erichsen
 talk decision models with 
@allietheicon
 from 
@typesafeai
 ](https://x.com/openclaw/status/2105475400797413578)

### X — @steipete
- [holy](https://x.com/steipete/status/2105805164305359019) ↑0 🔁0 · recent
- ["Today, we’re releasing two Cloudflare-trained decision models, Clef and Clef-flash" 

https://
blog.cloudflare.com/clef](https://x.com/steipete/status/2105778011635400949) ↑0 🔁0 · recent
- ["the Waymo effect is what happens when a technology removes the friction of dealing with another human being"](https://x.com/steipete/status/2105739667174019491) ↑0 🔁0 · recent
- ["AI agents are aeroplanes for the mind: faster and more powerful than the bicycle, harder to control, costlier when they](https://x.com/steipete/status/2105773541652308145) ↑0 🔁0 · recent
- [i have so many questions](https://x.com/steipete/status/2105728299255415134) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
