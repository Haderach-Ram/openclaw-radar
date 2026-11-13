---
layout: post
title: "Ecosystem Digest — 2026-11-13"
date: 2026-11-13 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-13
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 394,406 | 7 | 5 | 10 | 0 |
| **hermesagent** | 262,987 | 6 | 6 | 6 | 0 |
| **ZeroClaw** | 33,344 | 4 | 1 | 4 | 1 |
| **IronClaw** | 12,713 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,957 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 394,406 · **Open issues:** 8,069 · **Last push:** <1h ago

### ✅ Merged PRs
- [#198023](https://github.com/openclaw/openclaw/pull/198023) fix(ci): finish readiness fixture retries within the virtual deadline
- [#198008](https://github.com/openclaw/openclaw/pull/198008) fix(gateway): avoid redundant GitHub action authority work
- [#196200](https://github.com/openclaw/openclaw/pull/196200) fix(ui): manage agent GitHub accounts in Profile
- [#192242](https://github.com/openclaw/openclaw/pull/192242) improve: render chat composer mentions inline
- [#198017](https://github.com/openclaw/openclaw/pull/198017) fix(test): wait for Profile content before the first screenshot
- [#197906](https://github.com/openclaw/openclaw/pull/197906) feat(ui): choose the speech-to-text model from Settings → Talk
- [#198016](https://github.com/openclaw/openclaw/pull/198016) test(ui): honor reduced-motion transition timing
- [#198024](https://github.com/openclaw/openclaw/pull/198024) fix(ci): stop flagging the plugin-owned Codex benchmark dependency
- [#197904](https://github.com/openclaw/openclaw/pull/197904) feat(browser): open Chrome settings pages from the Control UI Browser panel
- [#197909](https://github.com/openclaw/openclaw/pull/197909) fix(status): cancel pending Gateway reads in status on Ctrl+C

### 🐛 New Issues
- [#198041](https://github.com/openclaw/openclaw/issues/198041) claude-cli: final assistant reply stored twice (imported CLI entry + live-run entry); iOS app shows duplicates
- [#198036](https://github.com/openclaw/openclaw/issues/198036) [Feature]: iOS Share Extension can't send to Cloudflare Access–protected Gateways (use the app's Access session or hand off to the app) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#198032](https://github.com/openclaw/openclaw/issues/198032) [Docs Bug]: Codex troubleshooting reads the retired host-wide log path `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#198026](https://github.com/openclaw/openclaw/issues/198026) Control UI Skills: "Needs Setup" counts skills excluded by the agent's skills allowlist `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#198021](https://github.com/openclaw/openclaw/issues/198021) OpenRouter STT ignores providerOptions, preventing Scribe audio-event tags from being disabled `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#198010](https://github.com/openclaw/openclaw/issues/198010) [Bug]: npm installs of 2026.11.5-beta.x: Bonjour discovery fails with ERR_MODULE_NOT_FOUND for `@homebridge/ciao/native.js` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:other` `maturity:stable` 💬1
- [#198004](https://github.com/openclaw/openclaw/issues/198004) Browser: scoped 1Password cooperation can prevent protected-frame attachment loss `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#197944](https://github.com/openclaw/openclaw/issues/197944) Markdown-table width regression on main after #197823
- [#196136](https://github.com/openclaw/openclaw/issues/196136) Control UI: make personal, shared, and per-agent GitHub accounts clear in Settings
- [#197859](https://github.com/openclaw/openclaw/issues/197859) [Feature]: Set up speech-to-text model and OpenRouter key from Settings → Talk
- [#197837](https://github.com/openclaw/openclaw/issues/197837) Control UI Browser: allow operator-only access to chrome://settings
- [#197982](https://github.com/openclaw/openclaw/issues/197982) Control UI desktop "Move to group" search finds no group when the name and the query use different Unicode forms of the same accented letter

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬81 · 1d ago
- [#116201](https://github.com/openclaw/openclaw/issues/116201) Realtime voice work can retain unbounded provider and consult state — 💬59 · 41d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 262,987 · **Open issues:** 53,986 · **Last push:** <1h ago

### ✅ Merged PRs
- [#154686](https://github.com/NousResearch/hermes-agent/pull/154686) fix(tui): a blank install on the shared gateway opens Setup Required
- [#154317](https://github.com/NousResearch/hermes-agent/pull/154317) fix(pm): fetch pnpm on demand on Termux instead of requiring it
- [#154540](https://github.com/NousResearch/hermes-agent/pull/154540) fix(pm): bump pinned npm 12.0.2 -> 12.2.2 for bundled-module CVEs
- [#152679](https://github.com/NousResearch/hermes-agent/pull/152679) docs(website): compare cross-links, sitemap cleanup, moved-skill redirects
- [#154501](https://github.com/NousResearch/hermes-agent/pull/154501) fix(dashboard): refuse a managed write through a credential name mid link chain
- [#154500](https://github.com/NousResearch/hermes-agent/pull/154500) fix(webhook): keep signature pins on dashboard re-save; pin new MCP event routes

### 🐛 New Issues
- [#154774](https://github.com/NousResearch/hermes-agent/issues/154774) [Bug][dashboard] Memory provider badge reads "unavailable" when PM's dependency snapshot is stale, even though the provider is serving (doctor disagrees) `type/bug` `comp/cli` `tool/memory` `P2`
- [#154768](https://github.com/NousResearch/hermes-agent/issues/154768) [Bug]: Weixin adapter 120-column hard-wrap splits inline code and prose paragraphs, and multi-backtick wrapped blocks render out of order in WeChat `type/bug` `platform/wecom` `P2`
- [#154763](https://github.com/NousResearch/hermes-agent/issues/154763) Desktop: a mid-turn message is re-injected into the live request multiple times (steer re-delivery; transcript stays clean) `type/perf` `comp/agent` `P2`
- [#154758](https://github.com/NousResearch/hermes-agent/issues/154758) [Bug]: Open WebUI chat returns HTTP 400 with trailing empty assistant message `type/bug` `comp/gateway` `P2`
- [#154753](https://github.com/NousResearch/hermes-agent/issues/154753) [Feature]: Multi-speaker streaming for the Radio plugin (cast PC audio to Echo / AirPlay / Bluetooth groups) `type/feature` `P3` `comp/desktop`
- [#154751](https://github.com/NousResearch/hermes-agent/issues/154751) [Feature]: Launch agent-run shell commands in their own systemd scope, so broad kill patterns can't reach unrelated processes `type/security` `comp/tools` `tool/terminal` `backend/local` `P3`

### 🔒 Closed Issues
- [#143037](https://github.com/NousResearch/hermes-agent/issues/143037) Desktop: running cron sessions are invisible in Sessions and the Bot roster (only reachable via Schedules → run history)
- [#142877](https://github.com/NousResearch/hermes-agent/issues/142877) Desktop SSH connection: pasted images never reach the backend (image not found)
- [#8720](https://github.com/NousResearch/hermes-agent/issues/8720) hermes agent 不支持windows是个败笔，这样怎么能好好的控制自己的电脑？
- [#153401](https://github.com/NousResearch/hermes-agent/issues/153401) [Bug]: fix(rooms): a probe timeout during a busy member turn marks the attempt member_unavailable and drops its reply, in version Hermes 0.23.x
- [#38128](https://github.com/NousResearch/hermes-agent/issues/38128) [Bug]: Docker Hindsight memory provider loses hindsight-client after container recreate/update
- [#89656](https://github.com/NousResearch/hermes-agent/issues/89656) [Feature]: Make Hermes notification / completion sound louder & add a volume control

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,344 · **Open issues:** 1,203 · **Last push:** 15h ago

### 🚀 New Releases
- [v0.9.0](https://github.com/zeroclaw-labs/zeroclaw/releases/tag/v0.9.0) — v0.9.0

### ✅ Merged PRs
- [#11842](https://github.com/zeroclaw-labs/zeroclaw/pull/11842) chore(deps): bump the web-minor-patch group across 1 directory with 21 updates
- [#12012](https://github.com/zeroclaw-labs/zeroclaw/pull/12012) chore(deps-dev): bump happy-dom from 20.11.6 to 21.0.4 in /web
- [#11936](https://github.com/zeroclaw-labs/zeroclaw/pull/11936) chore(deps-dev): bump vite from 8.0.16 to 8.3.5 in /web
- [#11282](https://github.com/zeroclaw-labs/zeroclaw/pull/11282) chore(deps-dev): bump brace-expansion from 2.1.4 to 2.1.7 in /web

### 🐛 New Issues
- [#12401](https://github.com/zeroclaw-labs/zeroclaw/issues/12401) [Bug]: Tool-context collapse (`keep_tool_context_turns`) breaks Claude Opus 5.5 chats with a thinking-signature 400 after a few tool-using turns
- [#12400](https://github.com/zeroclaw-labs/zeroclaw/issues/12400) [Task]: make the reply-end write-deadline dashboard test pass on Windows
- [#12373](https://github.com/zeroclaw-labs/zeroclaw/issues/12373) [Feature]: Write-only WebUI credential management and scoped secret references
- [#12320](https://github.com/zeroclaw-labs/zeroclaw/issues/12320) [Bug]: Security job fails on every build: RUSTSEC-2026-0459 (libsqlite3-sys 0.38.2, bundled SQLite 3.53.2) `bug` `dependencies` `release:v0.9.1` 💬3

### 🔒 Closed Issues
- [#11853](https://github.com/zeroclaw-labs/zeroclaw/issues/11853) ci: npm audit failed — 2026-10-19

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,713 · **Open issues:** 1,570 · **Last push:** 3d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,957 · **Open issues:** 121 · **Last push:** 20d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬4 · 4h ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 10d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 19d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 38d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 46d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 48d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 58d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 66d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 68d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 76d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Legal] Self Hosted Managed Agents License](https://www.anthropic.com/legal/self-hosted-managed-agents-license) _2026-11-12_

### OpenAI — 8 new
- [[Customer-Stories] Amplitude](https://openai.com/business/customer-stories/amplitude/) _2026-11-13_
- [[Daybreak] Defense Factory](https://openai.com/daybreak/defense-factory/) _2026-11-13_
- [[Customer-Stories] Holidays Extras Codex](https://openai.com/business/customer-stories/holidays-extras-codex/) _2026-11-13_
- [[Daybreak] Red Team](https://openai.com/daybreak/red-team/) _2026-11-12_
- [[Form] Daybreak Red Team](https://openai.com/form/daybreak-red-team/) _2026-11-12_
- [Proud Partner](https://openai.com/proud-partner/) _2026-11-12_
- [[Blog] Chatgpt Ads Increases Its Market Presence](https://openai.com/ads/blog/chatgpt-ads-increases-its-market-presence/)
- [[Index] Bloomsbury Football Foundation](https://openai.com/index/bloomsbury-football-foundation/) _2026-11-13_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/singularity — top 2 new
- [Judging by the current exponential rate, Jensen Huang's affairs should exceed all human population by December. We are not ready for what's coming](https://reddit.com/r/singularity/comments/1xuqlkb/judging_by_the_current_exponential_rate_jensen/) ↑3067
- [China offers Jensen new opportunities](https://reddit.com/r/singularity/comments/1xuhhvn/china_offers_jensen_new_opportunities/) ↑1985

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Starting to think I'm too dumb to use OpenClaw properly](https://reddit.com/r/openclaw/comments/1xubtc0/starting_to_think_im_too_dumb_to_use_openclaw/) ↑34
- [Swapped my local OpenClaw agent from Opus 5.5 to DeepSeek v4.1 Flash. Honestly can't tell the difference.](https://reddit.com/r/openclaw/comments/1xubh4h/swapped_my_local_openclaw_agent_from_opus_55_to/) ↑19
- [Free golf tee time finder…](https://reddit.com/r/openclaw/comments/1xuqdwc/free_golf_tee_time_finder/) ↑2
- [Suggestion before updating](https://reddit.com/r/openclaw/comments/1xubet4/suggestion_before_updating/) ↑2
- [Your email agent believes whoever an email says it's from](https://reddit.com/r/openclaw/comments/1xtk31q/your_email_agent_believes_whoever_an_email_says/) ↑2

### X — @openclaw
- [Looking for more detail on how OpenClaw Enterprise secures persistent agents? 


@kevins8
 breaks down the controls used](https://x.com/openclaw/status/2120979006250213651) ↑0 🔁0 · recent
- [Ever since they were announced, 
@obviyus
 has been working hard to add support for Telegram widgets 

Try it now, just ](https://x.com/openclaw/status/2120968028443889890) ↑0 🔁0 · recent


### X — @steipete
- [My team wrote about how we run persistent agents inside OpenAI.](https://x.com/steipete/status/2121058770767982997) ↑0 🔁0 · recent
- [Would you enable yolo mode for dots, even if your dot might do sth unwanted?](https://x.com/steipete/status/2121042215619510584) ↑0 🔁0 · recent
- [There’s some new agent launching later this week and marketers offer a lot of money to say nice things about it on X. Ke](https://x.com/steipete/status/2121009372470067544) ↑0 🔁0 · recent
- [“Don't worry, you don't need to learn how to write this. Your agents will. And we made them really good at it.”](https://x.com/steipete/status/2120974913679040680) ↑0 🔁0 · recent
- [If that Spy’s goal was to destabilize one of the most successful American companies, they achieved their goal. Ousting J](https://x.com/steipete/status/2120903527803564397) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
