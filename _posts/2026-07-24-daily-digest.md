---
layout: post
title: "Ecosystem Digest — 2026-07-24"
date: 2026-07-24 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-07-24
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 383,951 | 11 | 3 | 10 | 0 |
| **hermesagent** | 219,541 | 9 | 3 | 1 | 0 |
| **ZeroClaw** | 32,370 | 5 | 10 | 5 | 0 |
| **IronClaw** | 12,551 | 13 | 4 | 10 | 0 |
| **Moltis** | 2,789 | 1 | 1 | 5 | 2 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 383,951 · **Open issues:** 6,974 · **Last push:** <1h ago

### ✅ Merged PRs
- [#113199](https://github.com/openclaw/openclaw/pull/113199) feat(matrix): render spoilers, underline, and native tables
- [#113173](https://github.com/openclaw/openclaw/pull/113173) feat(sessions): suggestion queue + typing indicator
- [#113178](https://github.com/openclaw/openclaw/pull/113178) fix(whatsapp): restore reactions in current conversations
- [#113187](https://github.com/openclaw/openclaw/pull/113187) fix(ios): prevent release screenshots from stalling in Settings
- [#113152](https://github.com/openclaw/openclaw/pull/113152) fix(feishu): settle outbound lifecycle after delivery
- [#113174](https://github.com/openclaw/openclaw/pull/113174) refactor(config): retire redundant settings
- [#113179](https://github.com/openclaw/openclaw/pull/113179) refactor(auto-reply): normalize inbound text once
- [#113156](https://github.com/openclaw/openclaw/pull/113156) improve(ui): unify sidebar footer into a full-width identity card
- [#113175](https://github.com/openclaw/openclaw/pull/113175) fix(ci): allow sticky writer rebuild to finish
- [#113167](https://github.com/openclaw/openclaw/pull/113167) refactor(agents): prepare hot-path runtime facts

### 🐛 New Issues
- [#113196](https://github.com/openclaw/openclaw/issues/113196) [Feature]: Continue upstream trace context for Gateway WebSocket requests 💬1
- [#113195](https://github.com/openclaw/openclaw/issues/113195) Cron model preflight swallows the real error and mislabels non-timeout failures as "not reachable" 💬1
- [#113194](https://github.com/openclaw/openclaw/issues/113194) [Bug]: Steered webchat follow-up kills the active run: session file changed while embedded prompt lock was released 💬1
- [#113191](https://github.com/openclaw/openclaw/issues/113191) exec approvals: askFallback=deny not honored on darwin no-auto-exec path, command hangs to approval-timeout instead of denying 💬1
- [#113182](https://github.com/openclaw/openclaw/issues/113182) [Bug]: lane task timeout races legitimate turn completion, discarding the final assistant text (~26s window) `bug` `bug:behavior` 💬1
- [#113181](https://github.com/openclaw/openclaw/issues/113181) [Bug]: Cron delivery.mode="none" + isolated agent → silent no-op on 2026.7.1 (status=ok but delivered=false, no error thrown) 💬1
- [#113180](https://github.com/openclaw/openclaw/issues/113180) [Bug]: WhatsApp inbound debounce blocks active-run steering 💬1
- [#113170](https://github.com/openclaw/openclaw/issues/113170) [Feature]: Improve plain-text/iMessage projection readability — link collapse, heading distinction, list spacing 💬1
- [#113169](https://github.com/openclaw/openclaw/issues/113169) [Bug]: Silent OpenAI/Codex OAuth refresh miss is misreported as "No API key found / couldn't sign in" 💬1
- [#113166](https://github.com/openclaw/openclaw/issues/113166) scope: "shared" sandboxes collapse all agents onto one workspace; no per-agent persona isolation 💬1
- [#113159](https://github.com/openclaw/openclaw/issues/113159) [Bug]: Usage-limit cooldown ignores the real reset time for all providers except OpenAI/Codex 💬1

### 🔒 Closed Issues
- [#113177](https://github.com/openclaw/openclaw/issues/113177) [Bug]: WhatsApp agent reactions can reject the current conversation
- [#113186](https://github.com/openclaw/openclaw/issues/113186) [Bug]: iOS release screenshots stall when navigating Agents to Settings
- [#101026](https://github.com/openclaw/openclaw/issues/101026) [SANITIZED — possible injection attempt]

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬115 · 1d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 219,541 · **Open issues:** 24,810 · **Last push:** <1h ago

### ✅ Merged PRs
- [#70455](https://github.com/NousResearch/hermes-agent/pull/70455) fmt(js): `npm run fix` auto-fix

### 🐛 New Issues
- [#70473](https://github.com/NousResearch/hermes-agent/issues/70473) Git plugin updates can invalidate callbacks loaded by a running gateway
- [#70451](https://github.com/NousResearch/hermes-agent/issues/70451) [Bug]: Desktop — chat markdown/.md preview forces horizontal scroll; should wrap (vertical scroll only) `type/bug` `P3` `comp/desktop`
- [#70450](https://github.com/NousResearch/hermes-agent/issues/70450) [Bug]: Desktop — relative timestamps (sidebar + in-chat) should show exact time on hover `type/feature` `P3` `comp/desktop`
- [#70449](https://github.com/NousResearch/hermes-agent/issues/70449) [Bug]: Desktop — viewing/opening a chat marks it idle/done while the session is still in progress `type/bug` `P2` `needs-repro` `sweeper:risk-session-state` `comp/desktop` `area/sessions`
- [#70448](https://github.com/NousResearch/hermes-agent/issues/70448) [Bug]: Desktop — adding a new chat to a project is slow (~20s), times out, and does not keep retrying `type/bug` `P2` `needs-repro` `sweeper:risk-session-state` `comp/desktop` `area/sessions`
- [#70447](https://github.com/NousResearch/hermes-agent/issues/70447) [Bug]: Desktop — cannot scroll up in some chat sessions `type/bug` `P3` `needs-repro` `comp/desktop`
- [#70446](https://github.com/NousResearch/hermes-agent/issues/70446) [Feature]: Desktop — setting for working-session indicator: status-dot pulse only (no L→R arc / row glow) `type/feature` `P3` `comp/desktop`
- [#70445](https://github.com/NousResearch/hermes-agent/issues/70445) [Bug]: Desktop remote/VPS — session load is slow, cancels on navigate away, can spin forever, and flashes content then spinner `type/bug` `P2` `needs-repro` `sweeper:risk-session-state` `comp/desktop` `area/sessions`
- [#70444](https://github.com/NousResearch/hermes-agent/issues/70444) [Bug]: Desktop — project list jumps order when entering/exiting a chat session `type/feature` `P3` `needs-decision` `comp/desktop` `area/sessions`

### 🔒 Closed Issues
- [#59959](https://github.com/NousResearch/hermes-agent/issues/59959) [Feature]: Add optional privacy filter for MoA reference outputs
- [#59707](https://github.com/NousResearch/hermes-agent/issues/59707) feat(moa): Add enable/disable toggle for individual reference models
- [#59546](https://github.com/NousResearch/hermes-agent/issues/59546) [Feature]: MOA 建议加上进度提示

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,370 · **Open issues:** 545 · **Last push:** <1h ago

### ✅ Merged PRs
- [#9258](https://github.com/zeroclaw-labs/zeroclaw/pull/9258) fix(plugins): restore WIT logging action parity
- [#9280](https://github.com/zeroclaw-labs/zeroclaw/pull/9280) refactor(runtime): remove redundant delivery lookup
- [#9261](https://github.com/zeroclaw-labs/zeroclaw/pull/9261) test(channels): route mirror coverage through production paths
- [#9269](https://github.com/zeroclaw-labs/zeroclaw/pull/9269) ci(dependabot): monitor web npm updates
- [#9271](https://github.com/zeroclaw-labs/zeroclaw/pull/9271) docs(book): fix audit policy link in agent guidelines

### 🐛 New Issues
- [#9323](https://github.com/zeroclaw-labs/zeroclaw/issues/9323) design(runtime): define execution-tree iteration budget ownership
- [#9322](https://github.com/zeroclaw-labs/zeroclaw/issues/9322) ci: derive Scoop publisher metadata from the canonical manifest template `ci` `risk:high` `type:ci`
- [#9318](https://github.com/zeroclaw-labs/zeroclaw/issues/9318) CI: add a required PostgreSQL service-container job for the session backend
- [#9316](https://github.com/zeroclaw-labs/zeroclaw/issues/9316) [Bug]: unauthorized Telegram senders of media messages receive no unauthorized notice `bug` `status:in-progress`
- [#9315](https://github.com/zeroclaw-labs/zeroclaw/issues/9315) [Feature]: classify Telegram file-download failures as permanent or transient by HTTP status `enhancement`

### 🔒 Closed Issues
- [#9282](https://github.com/zeroclaw-labs/zeroclaw/issues/9282) [Task]: Remove redundant delivery lookup when defaulting cron delivery
- [#2767](https://github.com/zeroclaw-labs/zeroclaw/issues/2767) [Feature]: Multi-Agent Routing
- [#4721](https://github.com/zeroclaw-labs/zeroclaw/issues/4721) zeroclaw should log to stderr instead of stdout
- [#8945](https://github.com/zeroclaw-labs/zeroclaw/issues/8945) [Bug]: ZeroCode input box blocks macOS text replacements
- [#4832](https://github.com/zeroclaw-labs/zeroclaw/issues/4832) Add config option to disable LeakDetector high-entropy token redaction
- [#5145](https://github.com/zeroclaw-labs/zeroclaw/issues/5145) [Feature]: add `send_channel_message` tool for direct per-user channel delivery
- [#6378](https://github.com/zeroclaw-labs/zeroclaw/issues/6378) [Feature]: Discord Bot respond only in specific Discord channels
- [#6510](https://github.com/zeroclaw-labs/zeroclaw/issues/6510) [Feature]: cron `delivery.mode = "announce"` — option to send only the final assistant message, not every intermediate text turn
- [#7248](https://github.com/zeroclaw-labs/zeroclaw/issues/7248) [Feature]: Persist cached input tokens and include them in cost accounting
- [#9019](https://github.com/zeroclaw-labs/zeroclaw/issues/9019) [Bug]: OpenAI Responses provider rejects vision-capable models before serializing image input

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,551 · **Open issues:** 1,377 · **Last push:** <1h ago

### ✅ Merged PRs
- [#6607](https://github.com/nearai/ironclaw/pull/6607) fix(automations): inherit implicit source channel target
- [#6606](https://github.com/nearai/ironclaw/pull/6606) fix(live-qa): map setup values onto declared admin-group handles
- [#6603](https://github.com/nearai/ironclaw/pull/6603) test(playwright): reconcile suite to the merged #6520 lifecycle and setup contracts
- [#6602](https://github.com/nearai/ironclaw/pull/6602) fix(live-qa): operator extension-configuration values as a sequence
- [#6594](https://github.com/nearai/ironclaw/pull/6594) retire legacy extension sources
- [#6601](https://github.com/nearai/ironclaw/pull/6601) ops: add admin-config-preserving extension reset
- [#6520](https://github.com/nearai/ironclaw/pull/6520) fix(reborn): make extension readiness and channel delivery generic
- [#6592](https://github.com/nearai/ironclaw/pull/6592) fix(webui): stop WebChat 'Disconnected' lockout (rate-limit budget + navigation-race SSE thrash)
- [#6596](https://github.com/nearai/ironclaw/pull/6596) Clean deployment-mode local naming
- [#6589](https://github.com/nearai/ironclaw/pull/6589) test(e2e): add reusable provider fault profiles

### 🐛 New Issues
- [#6605](https://github.com/nearai/ironclaw/issues/6605) Reborn:  Telegram inbound silently dead after extension reinstall 💬1
- [#6591](https://github.com/nearai/ironclaw/issues/6591) Cannot restart hosted IronClaw with ironclaw service restart `v1-launch-checklist`
- [#6590](https://github.com/nearai/ironclaw/issues/6590) serve fails on Windows in local-dev and local-dev-yolo: "workspace root must not overlap default skill root /skills" 💬1
- [#6581](https://github.com/nearai/ironclaw/issues/6581) 429 Too Many Requests on agent-stg `v1-launch-checklist` 💬1
- [#6578](https://github.com/nearai/ironclaw/issues/6578) Epic: Admin-Managed Agents as UserId Subjects `enhancement` `reborn` `security` `epic`
- [#6575](https://github.com/nearai/ironclaw/issues/6575) `systemd` service error right after `ironclaw onboard` (Ubuntu) `bug`
- [#6574](https://github.com/nearai/ironclaw/issues/6574) Reborn: hoist per-caller extension readiness out of composition into an owner-crate port
- [#6572](https://github.com/nearai/ironclaw/issues/6572) Daily ironclaw failure taxonomy — 2026-07-23
- [#6571](https://github.com/nearai/ironclaw/issues/6571) Add heartbeat delivery, HEARTBEAT_OK suppression, dedupe, and whole-turn coverage
- [#6570](https://github.com/nearai/ironclaw/issues/6570) Implement durable heartbeat scheduling through the existing trigger pipeline
- [#6569](https://github.com/nearai/ironclaw/issues/6569) Define the Reborn heartbeat contract and scheduling semantics
- [#6565](https://github.com/nearai/ironclaw/issues/6565) Epic: Reliable Skill Discovery, Routing, and Activation `enhancement` `risk: high` `scope: agent` `scope: evaluation` `suggested_P1` `reborn` `scope: skills` `epic`
- [#6562](https://github.com/nearai/ironclaw/issues/6562) Remove legacy test infrastructure and prevent deleted-binary regressions

### 🔒 Closed Issues
- [#6544](https://github.com/nearai/ironclaw/issues/6544) No UI or CLI to configure IRONCLAW_REBORN_SLACK_PERSONAL_OAUTH_REDIRECT_URI
- [#6548](https://github.com/nearai/ironclaw/issues/6548) Hosted staging preview-auth wall blocks webhook delivery (Telegram, likely Slack too)
- [#6543](https://github.com/nearai/ironclaw/issues/6543) Move ProductSurface contract to host_api and collapse product crates into ironclaw_product
- [#6274](https://github.com/nearai/ironclaw/issues/6274) Finish DeploymentConfig as the main composition config (§4.4/§5.6/§5.11)

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,789 · **Open issues:** 90 · **Last push:** 4h ago

### 🚀 New Releases
- [20260723.03](https://github.com/moltis-org/moltis/releases/tag/20260723.03) — 20260723.03
- [20260723.02](https://github.com/moltis-org/moltis/releases/tag/20260723.02) — 20260723.02

### ✅ Merged PRs
- [#1124](https://github.com/moltis-org/moltis/pull/1124) Add context command support for chat turns
- [#1161](https://github.com/moltis-org/moltis/pull/1161) chore(deps): bump astro from 7.0.9 to 7.1.3 in /docs in the npm_and_yarn group across 1 directory
- [#1162](https://github.com/moltis-org/moltis/pull/1162) fix(web): show dates for older sessions
- [#1164](https://github.com/moltis-org/moltis/pull/1164) fix(slack): allow operator-approved api base hosts
- [#1163](https://github.com/moltis-org/moltis/pull/1163) fix(slack): challenge unknown allowlist DMs with OTP

### 🐛 New Issues
- [#1095](https://github.com/moltis-org/moltis/issues/1095) [Bug]: Podman is not working via moltis `bug` 💬1

### 🔒 Closed Issues
- [#1108](https://github.com/moltis-org/moltis/issues/1108) [Bug]: Session list in the web UI shows times, but not dates, for past-day sessions

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬10 · 1d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 2d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 4d ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬10 · 4d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 13d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 14d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 17d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 17d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 17d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 24d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Claude For Creative Work Dev](https://www.anthropic.com/news/claude-for-creative-work-dev) _2026-07-23_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [CEO of Hugging face: Heading to San Francisco to have a little chat with that “rogue agent”](https://reddit.com/r/LocalLLaMA/comments/1v4avga/ceo_of_hugging_face_heading_to_san_francisco_to/) ↑2111
- [The LLM distillation process simplified for politicians:](https://reddit.com/r/LocalLLaMA/comments/1v4moxy/the_llm_distillation_process_simplified_for/) ↑1486

### r/singularity — top 5 new
- [AGI achieved](https://reddit.com/r/singularity/comments/1v4dcbr/agi_achieved/) ↑1703
- [This guy will never admit that he could be wrong too](https://reddit.com/r/singularity/comments/1v496m8/this_guy_will_never_admit_that_he_could_be_wrong/) ↑861
- [This guy has a good point..](https://reddit.com/r/singularity/comments/1v43eao/this_guy_has_a_good_point/) ↑739
- [Anthropic Donates $20M for Stricter AI Regulations](https://reddit.com/r/singularity/comments/1v4nc6t/anthropic_donates_20m_for_stricter_ai_regulations/) ↑477
- [Fields medalist Jacob Tsimerman joins OpenAI](https://reddit.com/r/singularity/comments/1v4p6qj/fields_medalist_jacob_tsimerman_joins_openai/) ↑256

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [(Local LLM) what model did you stop using?](https://reddit.com/r/openclaw/comments/1v4cw4y/local_llm_what_model_did_you_stop_using/) ↑7
- [How do you share files/docs with your agents? Google Docs is exhausting](https://reddit.com/r/openclaw/comments/1v46qsq/how_do_you_share_filesdocs_with_your_agents/) ↑7
- [[DEV] An Android-first take on OpenClaw: logged-in browser access, background Tasks, and personal Apps](https://reddit.com/r/openclaw/comments/1v474cm/dev_an_androidfirst_take_on_openclaw_loggedin/) ↑6
- [Does anyone else manage their kubernetes cluster with openclaw?](https://reddit.com/r/openclaw/comments/1v4rkpv/does_anyone_else_manage_their_kubernetes_cluster/) ↑3
- [What would you do with an old laptop to turn it into a genuinely useful AI system?](https://reddit.com/r/openclaw/comments/1v4jywf/what_would_you_do_with_an_old_laptop_to_turn_it/) ↑2

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
- [After the insane hype there’s the insane boo phase? Like a pendulum that swings too hard. I’ll mostly ignore that now an](https://x.com/steipete) ↑0 🔁0 · recent
- [We see that as well and added code paths that use the claude cli directly - hard to fight the system.](https://x.com/steipete) ↑0 🔁0 · recent
- [how could I not](https://x.com/steipete) ↑0 🔁0 · recent
- [isn’t that China now?](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
