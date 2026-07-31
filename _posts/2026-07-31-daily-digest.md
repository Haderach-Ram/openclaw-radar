---
layout: post
title: "Ecosystem Digest — 2026-07-31"
date: 2026-07-31 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-07-31
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 384,622 | 4 | 7 | 10 | 0 |
| **hermesagent** | 222,914 | 10 | 5 | 5 | 1 |
| **ZeroClaw** | 32,452 | 5 | 1 | 1 | 0 |
| **IronClaw** | 12,578 | 15 | 1 | 10 | 0 |
| **Moltis** | 2,799 | 2 | 0 | 1 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 384,622 · **Open issues:** 5,867 · **Last push:** <1h ago

### ✅ Merged PRs
- [#116558](https://github.com/openclaw/openclaw/pull/116558) fix: gateway wedges on every startup when legacy runtime-state files conflict with SQLite
- [#116606](https://github.com/openclaw/openclaw/pull/116606) feat(setup): improve local model onboarding
- [#116565](https://github.com/openclaw/openclaw/pull/116565) fix(codex): /steer hangs indefinitely when the app-server does not answer turn/steer
- [#116617](https://github.com/openclaw/openclaw/pull/116617) fix(ci): stabilize Codex websocket heartbeat tests
- [#116510](https://github.com/openclaw/openclaw/pull/116510) fix(ci): run fs-safe removal Windows coverage
- [#116593](https://github.com/openclaw/openclaw/pull/116593) fix(android): preserve device work across lifecycle changes
- [#116609](https://github.com/openclaw/openclaw/pull/116609) fix(tui): release terminal after backend shutdown failures
- [#116216](https://github.com/openclaw/openclaw/pull/116216) fix(ai): prevent websocket cache clobber on concurrent acquire
- [#116613](https://github.com/openclaw/openclaw/pull/116613) fix(ci): settle custodian mobile layout assertions
- [#116605](https://github.com/openclaw/openclaw/pull/116605) fix(agents): resume Code Mode through gateway restarts

### 🐛 New Issues
- [#116615](https://github.com/openclaw/openclaw/issues/116615) [Feature]: Config-free pre-mutation guard for native apply_patch `enhancement` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#116601](https://github.com/openclaw/openclaw/issues/116601) [SANITIZED — possible injection attempt] `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬2
- [#116594](https://github.com/openclaw/openclaw/issues/116594) skills.load.extraDirs: hardlink guard (nlink≥2) breaks skill loading on NixOS with auto-optimise-store `P1` `clawsweeper:needs-info` `issue-rating: 🦪 silver shellfish` `impact:other` 💬3
- [#116588](https://github.com/openclaw/openclaw/issues/116588) [Bug]: reset-boundary projections drop required toolResult rows and trigger synthetic transcript repair `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `issue-rating: 🐚 platinum hermit` 💬2

### 🔒 Closed Issues
- [#112867](https://github.com/openclaw/openclaw/issues/112867) [Bug]:Voice Wake migration conflict causes permanent Gateway startup refusal
- [#115917](https://github.com/openclaw/openclaw/issues/115917) [Bug]: Codex /steer request can hang indefinitely and guard the Telegram control lane
- [#99903](https://github.com/openclaw/openclaw/issues/99903) [Bug]: Control UI WebChat repeatedly prompts for gateway token after mobile browser is briefly backgrounded
- [#99813](https://github.com/openclaw/openclaw/issues/99813) [SANITIZED — possible injection attempt]
- [#112667](https://github.com/openclaw/openclaw/issues/112667) mcp error with finlynq
- [#85637](https://github.com/openclaw/openclaw/issues/85637) bundle-mcp: remote streamable-http server connects but tools never materialize for a Pi agent (2026.5.7)
- [#102006](https://github.com/openclaw/openclaw/issues/102006) [BUG] exec tool: aborted run wedges subsequent exec calls in same session (regression from PR #94412)

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬116 · 1d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 222,914 · **Open issues:** 25,976 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.7.30](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.7.30) — Hermes Agent v0.19.1 (v2026.7.30)

### ✅ Merged PRs
- [#75069](https://github.com/NousResearch/hermes-agent/pull/75069) chore: release v0.19.1 (2026.7.30)
- [#75070](https://github.com/NousResearch/hermes-agent/pull/75070) Auto populate flux3 in tools for nous portal users
- [#75039](https://github.com/NousResearch/hermes-agent/pull/75039) FLUX3 integration messaging system fixes
- [#75055](https://github.com/NousResearch/hermes-agent/pull/75055) fmt(js): `npm run fix` auto-fix
- [#74938](https://github.com/NousResearch/hermes-agent/pull/74938) fix(desktop): a session's coding rail follows its own worktree

### 🐛 New Issues
- [#75134](https://github.com/NousResearch/hermes-agent/issues/75134) Bug: Logs pane renders partially under terminal overlay in desktop app
- [#75133](https://github.com/NousResearch/hermes-agent/issues/75133) [Bug]:  Stuck on "Hermes is still running" caused by stale .git/shallow.lock after interrupted update `bug`
- [#75131](https://github.com/NousResearch/hermes-agent/issues/75131) feat(cron): inject prior delivery context for reply continuity (attach_to_session amnesia)
- [#75130](https://github.com/NousResearch/hermes-agent/issues/75130) Pending skill-proposal queue grows unbounded and self-invalidates when skills.write_approval is enabled (357 in 8 days, 21% dead) `type/bug` `comp/agent` `tool/skills` `area/config` `P2` `sweeper:risk-compatibility` 💬1
- [#75128](https://github.com/NousResearch/hermes-agent/issues/75128) Desktop and CLI provider/model routing divergence after config changes `type/bug` `area/config` `P2` `sweeper:risk-session-state` `sweeper:risk-compatibility` `comp/desktop` 💬2
- [#75123](https://github.com/NousResearch/hermes-agent/issues/75123) Feature Request: Cron job output should appear as a session in the desktop sidebar with a notification dot `type/feature` `comp/cron` `P3` `needs-decision` `comp/desktop` `area/sessions`
- [#75121](https://github.com/NousResearch/hermes-agent/issues/75121) [Bug]: Thinking-only prefill sends a trailing model turn to Gemini and 400s the turn, because reasoning stripping runs before the thinking-only drop pass `type/bug` `comp/agent` `provider/gemini` `P2`
- [#75118](https://github.com/NousResearch/hermes-agent/issues/75118) [Bug]: post-setup can break a running Gateway by upgrading dependencies `type/bug` `comp/cli` `comp/gateway` `P2` `sweeper:risk-compatibility` `area/install-update`
- [#75108](https://github.com/NousResearch/hermes-agent/issues/75108) [Bug]: SOUL.md is loaded, assembled, and persisted correctly, but is not consistently respected during live CLI conversations with custom providers (Ollama) `type/bug` `comp/agent` `provider/ollama` `P2` `needs-repro` `bug`
- [#75107](https://github.com/NousResearch/hermes-agent/issues/75107) fix(buzz): channels joined while the gateway is running are never subscribed — live adoption only exists for DM-shaped conversations `type/bug` `comp/plugins` `P3`

### 🔒 Closed Issues
- [#75098](https://github.com/NousResearch/hermes-agent/issues/75098) feat(setup): detect model `response_format` support during onboarding and warn user
- [#74140](https://github.com/NousResearch/hermes-agent/issues/74140) [Bug]: Telegram gateway hangs at "Connecting to Telegram (attempt 1/8)" — fix #64370 confirmed present, still reproduces
- [#46260](https://github.com/NousResearch/hermes-agent/issues/46260) [Bug]: INSTALL DIDN'T FINISH. Hermes installer fails at "desktop" stage — npm install exit code 1 on Windows 10
- [#74851](https://github.com/NousResearch/hermes-agent/issues/74851) feat: Route explicit wake-word commands to existing Desktop sessions
- [#75064](https://github.com/NousResearch/hermes-agent/issues/75064) [Feature]: Native AgentMail email provider — receive, send, and auto-process emails

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,452 · **Open issues:** 660 · **Last push:** 1h ago

### ✅ Merged PRs
- [#9205](https://github.com/zeroclaw-labs/zeroclaw/pull/9205) feat(sop): centralize fan-in ingress adapters

### 🐛 New Issues
- [#9572](https://github.com/zeroclaw-labs/zeroclaw/issues/9572) [Bug]: debug gateway WebSocket turns can overflow the default Tokio worker stack
- [#9566](https://github.com/zeroclaw-labs/zeroclaw/issues/9566) [Bug]: uppercase allowed_commands entries never match on Unix (regressed from #4552) `bug`
- [#9565](https://github.com/zeroclaw-labs/zeroclaw/issues/9565) [Bug]: gateway webhook handlers do not fail closed (WhatsApp Cloud, Linq, WATI) `bug` 💬2
- [#9562](https://github.com/zeroclaw-labs/zeroclaw/issues/9562) [Support]: How to disable auto-scroll in WebChat while agent is streaming? `r:support`
- [#9545](https://github.com/zeroclaw-labs/zeroclaw/issues/9545) [Task]: gate rustdoc warnings in required PR CI `enhancement` `ci` `docs` `domain:ci` `priority:p2` `status:accepted` `risk:high` `type:ci` 💬2

### 🔒 Closed Issues
- [#8581](https://github.com/zeroclaw-labs/zeroclaw/issues/8581) feat(sop): centralize SOP ingress adapters for fan-in sources

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,578 · **Open issues:** 1,430 · **Last push:** <1h ago

### ✅ Merged PRs
- [#6934](https://github.com/nearai/ironclaw/pull/6934) refactor(host_api): de-wildcard the contract prelude (WS0)
- [#6931](https://github.com/nearai/ironclaw/pull/6931) feat(slack): native /ironclaw slash commands (PR-3 of command train)
- [#6862](https://github.com/nearai/ironclaw/pull/6862) fix(reborn): preserve terminal model error explanations
- [#6891](https://github.com/nearai/ironclaw/pull/6891) feat(webui): role-filtered command palette (PR-2 of command train)
- [#6883](https://github.com/nearai/ironclaw/pull/6883) ci(test): enforce hermetic deterministic Reborn suite
- [#6928](https://github.com/nearai/ironclaw/pull/6928) docs(testing): document epic confidence workflows
- [#6929](https://github.com/nearai/ironclaw/pull/6929) docs(target-arch): refresh north star against live main (#6919)
- [#6918](https://github.com/nearai/ironclaw/pull/6918) docs(reborn): target crate architecture — the north star (overview, family specs, checklist, plan, explorer)
- [#6882](https://github.com/nearai/ironclaw/pull/6882) test(e2e): compose provider journeys from typed facts
- [#6876](https://github.com/nearai/ironclaw/pull/6876) fix(webui): restore smooth streaming and preserve model phases

### 🐛 New Issues
- [#6940](https://github.com/nearai/ironclaw/issues/6940) Bug: IronHub skill CTA returns 404 across all skills `bug` `p2` `feedback`
- [#6939](https://github.com/nearai/ironclaw/issues/6939) Feature: Migration tool to port legacy agent setup and memory to IronClaw `p2` `feedback` `feature`
- [#6927](https://github.com/nearai/ironclaw/issues/6927) Finish target-architecture enforcement, agent guidance, and migration verification `documentation` `scope: ci` `scope: dependencies` `reborn`
- [#6926](https://github.com/nearai/ironclaw/issues/6926) Move IronClaw crates into the ten-family layout `scope: dependencies` `refactoring` `reborn`
- [#6925](https://github.com/nearai/ironclaw/issues/6925) Delete verified dead surface and enable workspace dead-code ratchets `refactoring` `reborn`
- [#6924](https://github.com/nearai/ironclaw/issues/6924) Complete composition, app, and domain ownership evictions and canonical renames `scope: dependencies` `refactoring` `reborn`
- [#6923](https://github.com/nearai/ironclaw/issues/6923) Narrow kernel, execution lanes, and loop hosting to eliminate layer exceptions `scope: dependencies` `refactoring` `reborn`
- [#6922](https://github.com/nearai/ironclaw/issues/6922) Restructure extension packages and invert product-facing ports `scope: extensions` `refactoring` `reborn`
- [#6921](https://github.com/nearai/ironclaw/issues/6921) Extract neutral loop, extension, and product contracts and seal evidence minting `scope: dependencies` `refactoring` `reborn`
- [#6920](https://github.com/nearai/ironclaw/issues/6920) Establish target-architecture baselines, prerequisite cleanup, and exception ratchets `scope: dependencies` `refactoring` `reborn`
- [#6919](https://github.com/nearai/ironclaw/issues/6919) Ratify and refresh the IronClaw target crate architecture north star `documentation` `scope: dependencies` `reborn`
- [#6916](https://github.com/nearai/ironclaw/issues/6916) Markdown files are rendered as plain text in the file preview modal
- [#6915](https://github.com/nearai/ironclaw/issues/6915) Workspace file links in assistant messages do not open the referenced file
- [#6910](https://github.com/nearai/ironclaw/issues/6910) Introduce a shared Switch component for settings controls
- [#6909](https://github.com/nearai/ironclaw/issues/6909) Migrate Admin deletion flows to the shared ConfirmDialog

### 🔒 Closed Issues
- [#4636](https://github.com/nearai/ironclaw/issues/4636) [Test] Add standalone SSO session and multi-user isolation E2E coverage

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,799 · **Open issues:** 96 · **Last push:** 1h ago

### ✅ Merged PRs
- [#1166](https://github.com/moltis-org/moltis/pull/1166) feat(slack): per-message acknowledgment reactions, phases, reconnect supervision, and Block Kit

### 🐛 New Issues
- [#1178](https://github.com/moltis-org/moltis/issues/1178) [Feature]: Let agents send Telegram inline buttons and receive structured callback responses
- [#1177](https://github.com/moltis-org/moltis/issues/1177) [SANITIZED — possible injection attempt] `bug`

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 9h ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬2 · 23h ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 1d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 1d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 3d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 9d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 11d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 20d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 21d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 24d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Investigating Incidents Cybersecurity Evals](https://www.anthropic.com/news/investigating-incidents-cybersecurity-evals) _2026-07-30_

### OpenAI — 5 new
- [[Index] Avatarin](https://openai.com/index/avatarin/) _2026-07-31_
- [[Partners] Mantel](https://openai.com/business/partners/mantel/) _2026-07-31_
- [[Partners] Booz Allen Hamilton](https://openai.com/business/partners/booz-allen-hamilton/) _2026-07-31_
- [Api Fast Mode](https://openai.com/api-fast-mode/) _2026-07-31_
- [[Plugins] Adobe](https://openai.com/business/plugins/adobe/) _2026-07-30_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Think of the children, another excuse for them to go after open source AI](https://reddit.com/r/LocalLLaMA/comments/1vapsbz/think_of_the_children_another_excuse_for_them_to/) ↑1052
- [Inkling-Small by thinkingmachines](https://reddit.com/r/LocalLLaMA/comments/1vb16gj/inklingsmall_by_thinkingmachines/) ↑376
- [Bought a 5090 to escape API fees. Ended up building a mini datacenter. Sound familiar?](https://reddit.com/r/LocalLLaMA/comments/1vacf09/bought_a_5090_to_escape_api_fees_ended_up/) ↑334
- [Software Engineers: Do you honestly get anything useful out of LLMs?](https://reddit.com/r/LocalLLaMA/comments/1vavh2h/software_engineers_do_you_honestly_get_anything/) ↑188
- [What actually happened to the whole Openclaw frenzy?](https://reddit.com/r/LocalLLaMA/comments/1vb8d2v/what_actually_happened_to_the_whole_openclaw/) ↑153

### r/singularity — top 5 new
- [Opus 5 Pokemon](https://reddit.com/r/singularity/comments/1vb5fhl/opus_5_pokemon/) ↑951
- [GPT‑5.6 Luna will cost 80% less, while GPT‑5.6 Terra will cost 20% less.](https://reddit.com/r/singularity/comments/1vb0giw/gpt56_luna_will_cost_80_less_while_gpt56_terra/) ↑553
- [Would you choose to live indefinitely in a robot body?](https://reddit.com/r/singularity/comments/1vasfzn/would_you_choose_to_live_indefinitely_in_a_robot/) ↑552
- [OpenAI beats DeepSeek on price/performance after 80% Luna price cut](https://reddit.com/r/singularity/comments/1vb1pen/openai_beats_deepseek_on_priceperformance_after/) ↑404
- [Anthropic says Claude hacked multiple companies starting in April](https://reddit.com/r/singularity/comments/1vbam9s/anthropic_says_claude_hacked_multiple_companies/) ↑398

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [OpenClaw is maturing 🦞 Extended-STABLE releases are HERE](https://reddit.com/r/openclaw/comments/1vaz5vl/openclaw_is_maturing_extendedstable_releases_are/) ↑81
- [OpenClaw saved the day](https://reddit.com/r/openclaw/comments/1vbc9mh/openclaw_saved_the_day/) ↑12
- [Openclaw (partially) succeeds where Gemini and Siri fail](https://reddit.com/r/openclaw/comments/1vb1hf1/openclaw_partially_succeeds_where_gemini_and_siri/) ↑7
- [Anyone using OC as a live service? How do you handle updates?](https://reddit.com/r/openclaw/comments/1vajsqm/anyone_using_oc_as_a_live_service_how_do_you/) ↑7
- [AntLing-3.0-flash from Ant Group is live on OpenClaw via OpenRouter](https://reddit.com/r/openclaw/comments/1vayqxh/antling30flash_from_ant_group_is_live_on_openclaw/) ↑5

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
- [OpenClaw is maturing.

Today we’re introducing monthly extended-stable releases with backported security and reliability](https://x.com/openclaw) ↑0 🔁0 · recent


### X — @steipete
_No new tweets in the last 7 days._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
