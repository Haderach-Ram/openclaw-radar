---
layout: post
title: "Ecosystem Digest — 2026-08-24"
date: 2026-08-24 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-08-24
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 387,277 | 6 | 3 | 10 | 0 |
| **hermesagent** | 235,042 | 9 | 4 | 9 | 0 |
| **ZeroClaw** | 32,638 | 11 | 10 | 10 | 0 |
| **IronClaw** | 12,602 | 12 | 0 | 1 | 0 |
| **Moltis** | 2,834 | 2 | 0 | 9 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 387,277 · **Open issues:** 5,982 · **Last push:** <1h ago

### ✅ Merged PRs
- [#128415](https://github.com/openclaw/openclaw/pull/128415) test(nodes): pin trusted session identity against spoofed invoke params
- [#128413](https://github.com/openclaw/openclaw/pull/128413) fix(release): reuse canonical job log reader
- [#120331](https://github.com/openclaw/openclaw/pull/120331) [SANITIZED — possible injection attempt]
- [#128369](https://github.com/openclaw/openclaw/pull/128369) feat(ui): link chat and presence identities to their activity feed
- [#128404](https://github.com/openclaw/openclaw/pull/128404) fix(discord): refresh stale starter messages in active threads
- [#123975](https://github.com/openclaw/openclaw/pull/123975) fix(scripts): clean up tsgo process trees on timeout or signal
- [#128394](https://github.com/openclaw/openclaw/pull/128394) fix(tts): deliver voice-only replies when speech runtime is cold
- [#128405](https://github.com/openclaw/openclaw/pull/128405) fix(release): accept canonical skipped child evidence
- [#126589](https://github.com/openclaw/openclaw/pull/126589) fix(beam): stop mirroring after service shutdown
- [#128365](https://github.com/openclaw/openclaw/pull/128365) feat(ui): let admins dismiss the sidebar update indicator

### 🐛 New Issues
- [#128455](https://github.com/openclaw/openclaw/issues/128455) [Feature]: Propagate workflow lineage and report ownership across remote agent handoffs `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#128449](https://github.com/openclaw/openclaw/issues/128449) Failure-announce run inherits the failing model config and dies of the same error — subagent failures become silent; failed attempts logged as outcome='completed' `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬2
- [#128446](https://github.com/openclaw/openclaw/issues/128446) CIDR-auto-approved node pairing strands the node surface pending and invisible; inventory publication retries forever `maintainer` `P1` `issue-rating: 🦪 silver shellfish` `impact:other` `maturity:stable` `impact:ux-friction` 💬1
- [#128445](https://github.com/openclaw/openclaw/issues/128445) Worker-turn inference rejects catalog models that local turns accept, and swallows the actionable error `maintainer` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` `maturity:stable` 💬1
- [#128429](https://github.com/openclaw/openclaw/issues/128429) [Bug]: Matrix replies containing a non-spoiler `||` are replaced entirely by "[Spoiler]" `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬2
- [#128424](https://github.com/openclaw/openclaw/issues/128424) [Feature]: Anonymous usage telemetry: default-on update ping + opt-in feature stats `enhancement` `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `impact:security` `issue-rating: 🌊 off-meta tidepool` 💬1

### 🔒 Closed Issues
- [#126916](https://github.com/openclaw/openclaw/issues/126916) test(e2e): onboard auth-profile assertion reads the pre-migration per-agent store
- [#107528](https://github.com/openclaw/openclaw/issues/107528) [Architecture] Extract terminal execution drivers from agent-core packages
- [#107659](https://github.com/openclaw/openclaw/issues/107659) [Bug]: ACPX update expands to 2.1 GiB; OOM leaves core/plugin drift that startup does not repair

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 235,042 · **Open issues:** 35,046 · **Last push:** <1h ago

### ✅ Merged PRs
- [#93420](https://github.com/NousResearch/hermes-agent/pull/93420) feat: subagents inherit workspace context files; /review also carries loaded skills
- [#93433](https://github.com/NousResearch/hermes-agent/pull/93433) fix(codex): announced Responses tool calls no longer vanish when output_item.done is omitted (#92764, salvage #92767)
- [#93421](https://github.com/NousResearch/hermes-agent/pull/93421) fix(terminal): subagents no longer hijack the tty with an interactive sudo prompt
- [#93428](https://github.com/NousResearch/hermes-agent/pull/93428) fix(state): concurrent cross-process FTS rebuilds no longer corrupt state.db (salvage #93200)
- [#93430](https://github.com/NousResearch/hermes-agent/pull/93430) fix(sessions): gateway restarts no longer strand rows, and closing sockets can't unbind live sessions (ring 2, 5 salvages)
- [#93429](https://github.com/NousResearch/hermes-agent/pull/93429) fmt(js): `npm run fix` auto-fix
- [#93411](https://github.com/NousResearch/hermes-agent/pull/93411) [SANITIZED — possible injection attempt]
- [#93419](https://github.com/NousResearch/hermes-agent/pull/93419) fix(desktop): Anthropic quota exhaustion no longer shows as 'Gateway needs setup' (#93198, salvages #93218)
- [#93418](https://github.com/NousResearch/hermes-agent/pull/93418) [SANITIZED — possible injection attempt]

### 🐛 New Issues
- [#93437](https://github.com/NousResearch/hermes-agent/issues/93437) feat(code-intel): add an optional SCIP query skill for existing indexes `type/feature` `tool/skills` `P3`
- [#93436](https://github.com/NousResearch/hermes-agent/issues/93436) test(code-intel): benchmark behavior-owner localization before adding another index `type/test` `tool/skills` `P3`
- [#93435](https://github.com/NousResearch/hermes-agent/issues/93435) [Feature]: Desktop Skills page — optional grouped-by-category view for large skill collections `type/feature` `tool/skills` `P3` `comp/desktop`
- [#93425](https://github.com/NousResearch/hermes-agent/issues/93425) Credential pool: a single spurious 401 permanently poisons a key (no self-heal) `type/bug` `comp/agent` `area/auth` `P2` `sweeper:risk-security-boundary`
- [#93412](https://github.com/NousResearch/hermes-agent/issues/93412) [Bug]: Local context probe misreads max_tokens (output cap) as context length — 1M context endpoint detected as 393K `type/bug` `comp/agent` `provider/deepseek` `area/config` `P2` 💬1
- [#93406](https://github.com/NousResearch/hermes-agent/issues/93406) [Bug]: post-update fleet version check produces zero rows on a healthy resumed gateway — success path lacks the fail-closed check the restart-failure path already has `type/bug` `comp/cli` `P2` `sweeper:risk-compatibility` `area/install-update` 💬1
- [#93403](https://github.com/NousResearch/hermes-agent/issues/93403) [Feature]: Desktop — option to hide completed tool-call rows & thinking blocks for a clean transcript `type/feature` `area/config` `P3` `needs-decision` `comp/desktop`
- [#93392](https://github.com/NousResearch/hermes-agent/issues/93392) bug(approval): unanchored mkfs hardline pattern false-positives on quoted prose (echo/git commit/grep) `type/bug` `comp/tools` `P2` 💬1
- [#93389](https://github.com/NousResearch/hermes-agent/issues/93389) feat(hooks): add pre_compression hook at the context-compression boundary `type/feature` `comp/agent` `comp/plugins` `P3` `sweeper:risk-session-state` `area/compression` 💬1

### 🔒 Closed Issues
- [#24483](https://github.com/NousResearch/hermes-agent/issues/24483) Docker sandbox fails with exit 125 when container_persistent=true and credential files are registered
- [#92560](https://github.com/NousResearch/hermes-agent/issues/92560) [Bug]:  Lifecycle env gate (`_HERMES_GATEWAY`) fires on CLI/TUI agent sessions — terminal tool is the only unscrubbed spawn surface
- [#92764](https://github.com/NousResearch/hermes-agent/issues/92764) [Bug]: Codex Responses stream that completes without output_item.done silently drops the pending function call
- [#65194](https://github.com/NousResearch/hermes-agent/issues/65194) fix: no startup-time sweep for orphaned TUI/subagent sessions (timer dies with gateway restart)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,638 · **Open issues:** 786 · **Last push:** <1h ago

### ✅ Merged PRs
- [#10146](https://github.com/zeroclaw-labs/zeroclaw/pull/10146) feat(plugins): activate logical channel instances
- [#10217](https://github.com/zeroclaw-labs/zeroclaw/pull/10217) fix(channels): make the filesystem listener cancellation-aware
- [#10201](https://github.com/zeroclaw-labs/zeroclaw/pull/10201) feat(whatsapp-web): set the push name from channel config
- [#9831](https://github.com/zeroclaw-labs/zeroclaw/pull/9831) feat(web-search): cap result content and harden the DuckDuckGo scrape path
- [#10038](https://github.com/zeroclaw-labs/zeroclaw/pull/10038) fix(gateway/cron): reject invalid session_target instead of isolating
- [#9959](https://github.com/zeroclaw-labs/zeroclaw/pull/9959) fix(memory): reject Qdrant in builder-only factory without storage config
- [#9013](https://github.com/zeroclaw-labs/zeroclaw/pull/9013) refactor(config)!: move TodoWrite display config from the daemon into zerocode
- [#9957](https://github.com/zeroclaw-labs/zeroclaw/pull/9957) fix(sop): record why a failed run failed
- [#9938](https://github.com/zeroclaw-labs/zeroclaw/pull/9938) fix(cost): preserve full provider ref so multi-alias pricing resolves
- [#9129](https://github.com/zeroclaw-labs/zeroclaw/pull/9129) feat(plugins): add coherent channel config services

### 🐛 New Issues
- [#10290](https://github.com/zeroclaw-labs/zeroclaw/issues/10290) Thread live config handle through agent::run for detached peer/subagent turns
- [#10286](https://github.com/zeroclaw-labs/zeroclaw/issues/10286) [Bug]: Restored ZeroCode transcripts omit persisted turns after history trimming `bug` `runtime` `priority:p2` `risk:medium` `zerocode` `channel:acp`
- [#10285](https://github.com/zeroclaw-labs/zeroclaw/issues/10285) [Feature]: Allow renaming sessions from ZeroCode `enhancement` `runtime` `priority:p2` `follow-up` `risk:medium` `zerocode`
- [#10282](https://github.com/zeroclaw-labs/zeroclaw/issues/10282) [Bug]: hardware probe feature does not reach tool implementations `bug` `dependencies` `tool` `priority:p2` `risk:medium` `hardware`
- [#10281](https://github.com/zeroclaw-labs/zeroclaw/issues/10281) [Bug]: Copilot Responses-only models fail through hard-coded Chat Completions `bug`
- [#10280](https://github.com/zeroclaw-labs/zeroclaw/issues/10280) [Task]: Normalize web-search GET transport errors before model forwarding `bug` `tool` `priority:p2` `tool:web` `status:accepted` `follow-up` `risk:medium`
- [#10277](https://github.com/zeroclaw-labs/zeroclaw/issues/10277) Pin the published zerorelay image base tags by digest `security`
- [#10276](https://github.com/zeroclaw-labs/zeroclaw/issues/10276) CA passphrase opt-in after first boot does not migrate the existing plaintext key `security`
- [#10273](https://github.com/zeroclaw-labs/zeroclaw/issues/10273) [Bug]: apply the Hailo history cap after wire-role coalescing
- [#10272](https://github.com/zeroclaw-labs/zeroclaw/issues/10272) [Bug]: correlate Hailo log assertions under parallel tests 💬2
- [#10271](https://github.com/zeroclaw-labs/zeroclaw/issues/10271) chore(util): consolidate crate-local floor_char_boundary copies onto std `enhancement`

### 🔒 Closed Issues
- [#10287](https://github.com/zeroclaw-labs/zeroclaw/issues/10287) [Invalid]: SOP run was terminated by loop detector before sop_advance
- [#9666](https://github.com/zeroclaw-labs/zeroclaw/issues/9666) fix(channels): make the filesystem listener cancellation-aware
- [#10200](https://github.com/zeroclaw-labs/zeroclaw/issues/10200) WhatsApp Web has no way to set the bot's display name
- [#10037](https://github.com/zeroclaw-labs/zeroclaw/issues/10037) [Bug]: POST /api/cron silently stores invalid session_target as isolated
- [#9919](https://github.com/zeroclaw-labs/zeroclaw/issues/9919) fix(memory): reject Qdrant in builder-only factory without storage config
- [#2467](https://github.com/zeroclaw-labs/zeroclaw/issues/2467) [Feature]: Webhook tranforms
- [#7314](https://github.com/zeroclaw-labs/zeroclaw/issues/7314) [Tracker]: WASM plugin program
- [#2503](https://github.com/zeroclaw-labs/zeroclaw/issues/2503) [Feature]: where is napcat channel
- [#6441](https://github.com/zeroclaw-labs/zeroclaw/issues/6441) [Feature]: Add Lemmy channel (private-message polling MVP)
- [#7099](https://github.com/zeroclaw-labs/zeroclaw/issues/7099) [Feature]: Route zeroclaw status output through CLI i18n

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,602 · **Open issues:** 1,539 · **Last push:** <1h ago

### ✅ Merged PRs
- [#7750](https://github.com/nearai/ironclaw/pull/7750) chore(webui): integrate Storybook + design-system catalog (Epic phase 1)

### 🐛 New Issues
- [#7842](https://github.com/nearai/ironclaw/issues/7842) [x-ai-product-feedback] Generic invalid result error during request execution `bug`
- [#7841](https://github.com/nearai/ironclaw/issues/7841) [x-ai-product-feedback] Telegram setup dead-ends on admin must configure `bug`
- [#7840](https://github.com/nearai/ironclaw/issues/7840) [x-ai-product-feedback] Slack: connect guidance gap `enhancement`
- [#7836](https://github.com/nearai/ironclaw/issues/7836) Tool advertisement: filter by availability (installed + activated + credential-ready + authorized)
- [#7832](https://github.com/nearai/ironclaw/issues/7832) [x-ai-product-feedback] Slack thread: product feedback triage from last 3 hours
- [#7830](https://github.com/nearai/ironclaw/issues/7830) Notion extension fails to install in IronClaw
- [#7829](https://github.com/nearai/ironclaw/issues/7829) Gmail setup fails in web UI with auth popup disappearing
- [#7828](https://github.com/nearai/ironclaw/issues/7828) Slack feedback: unable to set up Slack in NEAR Foundation account
- [#7827](https://github.com/nearai/ironclaw/issues/7827) [x-ai feedback] Triage messages from #x-ai-product-feedback (last 3h) `x-ai-product-feedback` `triage`
- [#7825](https://github.com/nearai/ironclaw/issues/7825) Sandbox egress auth: native iron-proxy recipes with host credential broker (retire GitHub-specific carve-out)
- [#7812](https://github.com/nearai/ironclaw/issues/7812) Onboarding suggestions: respect user-level tool permissions, generate with read-only tool access 💬3
- [#7732](https://github.com/nearai/ironclaw/issues/7732) Epic: Persistent per-user sandbox with iron-proxy; defer loop executors `epic` `v1.4.0` 💬9

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,834 · **Open issues:** 88 · **Last push:** 1h ago

### ✅ Merged PRs
- [#1226](https://github.com/moltis-org/moltis/pull/1226) fix(cron): deliver scheduled output to the originating chat
- [#1225](https://github.com/moltis-org/moltis/pull/1225) fix(i18n): update and improve zh-TW Traditional Chinese locale
- [#1227](https://github.com/moltis-org/moltis/pull/1227) fix(browser): enable Obscura stealth mode by default
- [#1228](https://github.com/moltis-org/moltis/pull/1228) fix(whatsapp): persist inbound files for local tools
- [#1229](https://github.com/moltis-org/moltis/pull/1229) fix(browser): support Browserless v2 containers
- [#1231](https://github.com/moltis-org/moltis/pull/1231) fix(mcp): resolve current client after server restart
- [#1234](https://github.com/moltis-org/moltis/pull/1234) fix(skills): materialize recursive bundled sidecars
- [#1235](https://github.com/moltis-org/moltis/pull/1235) fix(memory): normalize built-in backend config value
- [#1236](https://github.com/moltis-org/moltis/pull/1236) fix(memory): bound local embedding encoder batches

### 🐛 New Issues
- [#1224](https://github.com/moltis-org/moltis/issues/1224) [Bug]: Tools stop working in shared Slack channels `bug`
- [#245](https://github.com/moltis-org/moltis/issues/245) fix(tls): h2 in ALPN breaks WebSocket — browser negotiates h2, WS upgrade returns 405 💬2

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 2d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬2 · 2d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬4 · 6d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 11d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 14d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 17d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 19d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 21d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 23d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 23d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Qwen 3.8 27B is a game changer.](https://reddit.com/r/LocalLLaMA/comments/1vvyacg/qwen_38_27b_is_a_game_changer/) ↑901
- [“The All Spark” Cluster: Upgrading from 16 - 36 DGX Sparks](https://reddit.com/r/LocalLLaMA/comments/1vvv7iv/the_all_spark_cluster_upgrading_from_16_36_dgx/) ↑709
- [Don't want to be this guy, but I need Qwen 3.8 35B A3B](https://reddit.com/r/LocalLLaMA/comments/1vw2cop/dont_want_to_be_this_guy_but_i_need_qwen_38_35b/) ↑504
- [New qwen3.8:27b on a 39k line C to single-file HTML / three.js port](https://reddit.com/r/LocalLLaMA/comments/1vwde84/new_qwen3827b_on_a_39k_line_c_to_singlefile_html/) ↑263
- [We quantized Qwen 3.8 27B and compared the quants on an RTX 6000](https://reddit.com/r/LocalLLaMA/comments/1vwh3u7/we_quantized_qwen_38_27b_and_compared_the_quants/) ↑107

### r/singularity — top 2 new
- [Sam Altman with some sad statements about AI](https://reddit.com/r/singularity/comments/1vwju3e/sam_altman_with_some_sad_statements_about_ai/) ↑418
- [He Can't Be Stopped.](https://reddit.com/r/singularity/comments/1vwkffs/he_cant_be_stopped/) ↑165

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [My 93 crons and automatizations in Open Claw](https://reddit.com/r/openclaw/comments/1vvzpah/my_93_crons_and_automatizations_in_open_claw/) ↑73
- [Vellum v/s Hermes v/s OpenClaw v/s Deepseek Harness](https://reddit.com/r/openclaw/comments/1vvvy9b/vellum_vs_hermes_vs_openclaw_vs_deepseek_harness/) ↑8
- [Trying to make Openclaw apply to jobs for me](https://reddit.com/r/openclaw/comments/1vwh8rs/trying_to_make_openclaw_apply_to_jobs_for_me/) ↑6
- [OpenClaw and Local Models](https://reddit.com/r/openclaw/comments/1vwbg1f/openclaw_and_local_models/) ↑6
- [Simple Lesson - Overnight Reconciliation](https://reddit.com/r/openclaw/comments/1vw1ysy/simple_lesson_overnight_reconciliation/) ↑3

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
- [dropping new skill brb](https://x.com/steipete/status/2090946181564440727) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
