---
layout: post
title: "Ecosystem Digest — 2026-10-22"
date: 2026-10-22 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-22
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 392,707 | 3 | 1 | 10 | 1 |
| **hermesagent** | 255,981 | 9 | 0 | 2 | 2 |
| **ZeroClaw** | 33,018 | 14 | 9 | 8 | 0 |
| **IronClaw** | 12,665 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,906 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 392,707 · **Open issues:** 9,524 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.10.10-beta.3](https://github.com/openclaw/openclaw/releases/tag/v2026.10.10-beta.3) — openclaw 2026.10.10-beta.3

### ✅ Merged PRs
- [#180165](https://github.com/openclaw/openclaw/pull/180165) fix(ui): page-wide focus ring after uninstalling a plugin in Safari
- [#180077](https://github.com/openclaw/openclaw/pull/180077) refactor(ui): derive installed plugin inventory readiness
- [#180153](https://github.com/openclaw/openclaw/pull/180153) fix(ui): Ask OpenClaw sidebar opens by itself on plugin detail pages
- [#179940](https://github.com/openclaw/openclaw/pull/179940) refactor(ui): use Solid read boundaries in chat CI panels
- [#180101](https://github.com/openclaw/openclaw/pull/180101) fix(ui): recognize restored createDeferred in Solid lint
- [#179881](https://github.com/openclaw/openclaw/pull/179881) refactor(ui): use Solid async reads in session automation hovercards
- [#180150](https://github.com/openclaw/openclaw/pull/180150) fix(ui): plugin security audit hover is square and flush with its contents
- [#180100](https://github.com/openclaw/openclaw/pull/180100) fix(codex): recover managed startup after Homebrew Node upgrades
- [#179415](https://github.com/openclaw/openclaw/pull/179415) fix(lsp): bundle LSP servers inherit Gateway secrets
- [#179986](https://github.com/openclaw/openclaw/pull/179986) refactor(ui): pair Custodian surface cleanup with settled lifecycle

### 🐛 New Issues
- [#180171](https://github.com/openclaw/openclaw/issues/180171) Failed delivery queue rows lose their error cause when terminalized `clawsweeper:intake:bug` `clawsweeper:intake:needs-repro` 💬1
- [#180161](https://github.com/openclaw/openclaw/issues/180161) Feature: expose requester-scoped model catalogs to plugin commands and tools `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#180140](https://github.com/openclaw/openclaw/issues/180140) [Feature]: let agent-to-agent channel plugins offer ask_user, with questions going to the owner `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:other` 💬1

### 🔒 Closed Issues
- [#180152](https://github.com/openclaw/openclaw/issues/180152) Feishu: exec completion deliveries routed as replies with internal event UUID as open_message_id (400 / 99992354) — user replies lost until restart

### 🔥 Hot Issues (most commented)
- [#143524](https://github.com/openclaw/openclaw/issues/143524) [Bug]: Agent SQLite WAL grows to 1.4–2.8 GB in days despite wal_autocheckpoint=1000; blocks gateway startup (Windows, 2026.9.2/9.3) — 💬134 · 1h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 255,981 · **Open issues:** 50,393 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.22.4](https://github.com/NousResearch/hermes-agent/releases/tag/v0.22.4) — Hermes Agent v0.22.4
- [v0.22.3](https://github.com/NousResearch/hermes-agent/releases/tag/v0.22.3) — Hermes Agent v0.22.3

### ✅ Merged PRs
- [#140121](https://github.com/NousResearch/hermes-agent/pull/140121) feat(mcp): webhook-mode MCP events client (experimental)
- [#142672](https://github.com/NousResearch/hermes-agent/pull/142672) feat(desktop): drag sessions to pin / unpin in the sidebar

### 🐛 New Issues
- [#142836](https://github.com/NousResearch/hermes-agent/issues/142836) [Bug]: Dashboard mobile nav: page behind the menu still scrolls on iOS Safari `type/bug` `P2` `comp/dashboard`
- [#142835](https://github.com/NousResearch/hermes-agent/issues/142835) [Bug]: Dashboard Sessions > Overview: "Recent sessions" items look tappable but do nothing `type/bug` `tool/file` `P2` `comp/dashboard` `area/sessions` 💬1
- [#142834](https://github.com/NousResearch/hermes-agent/issues/142834) [Feature]: Approval gate for general write_file actions `type/security` `comp/tools` `tool/file` `area/config` `P2`
- [#142826](https://github.com/NousResearch/hermes-agent/issues/142826) [Bug]: Desktop sessions on the default branch get badged with a PR opened from the trunk `type/bug` `P2` `comp/desktop` `desktop/sessions` 💬1
- [#142822](https://github.com/NousResearch/hermes-agent/issues/142822) hermes gateway status/migrate crash with PermissionError on a root-owned 0640 systemd unit `type/bug` `comp/cli` `tool/file` `P2` `area/install-update` 💬1
- [#142820](https://github.com/NousResearch/hermes-agent/issues/142820) hermes cron run should refuse while the global emergency stop is engaged `type/bug` `comp/tools` `comp/cron` `tool/file` `P3` 💬4
- [#142817](https://github.com/NousResearch/hermes-agent/issues/142817) [Feature]: Desktop SDK — expose status bar visibility through host.settings `type/feature` `area/config` `P3` `comp/desktop` `desktop/settings` `desktop/shell` 💬1
- [#142813](https://github.com/NousResearch/hermes-agent/issues/142813) [Feature]: Desktop — name the prompt and magnify the selected mark in the conversation timeline rail `type/feature` `P3` `comp/desktop` `desktop/chat`
- [#142811](https://github.com/NousResearch/hermes-agent/issues/142811) [Bug]: clarify tool answers disappear from visible chat log after submission `type/bug` `P2` `comp/desktop` `area/sessions` `desktop/chat` `comp/tui-gateway` 💬1

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,018 · **Open issues:** 1,023 · **Last push:** <1h ago

### ✅ Merged PRs
- [#11438](https://github.com/zeroclaw-labs/zeroclaw/pull/11438) feat(channels): conversation binding port and channel conversation owner (RFC #6954, 2a/3)
- [#11141](https://github.com/zeroclaw-labs/zeroclaw/pull/11141) docs(review): preserve fetch command statuses
- [#11852](https://github.com/zeroclaw-labs/zeroclaw/pull/11852) fix(quickstart): ask for the endpoint before the model, and take a typed model
- [#11840](https://github.com/zeroclaw-labs/zeroclaw/pull/11840) docs(config): say provider api_key is stored encrypted, not in the OS keyring
- [#11814](https://github.com/zeroclaw-labs/zeroclaw/pull/11814) fix(plugins): stagger pinned egress dials so a silent address cannot stall the connect
- [#11808](https://github.com/zeroclaw-labs/zeroclaw/pull/11808) fix(plugins): count WebSocket and socket transports for a tool package's egress declaration
- [#11832](https://github.com/zeroclaw-labs/zeroclaw/pull/11832) ci(release): run the macOS plugin smoke on macos-15
- [#11924](https://github.com/zeroclaw-labs/zeroclaw/pull/11924) fix(deps): clear Wasmtime and TLS security advisories

### 🐛 New Issues
- [#11951](https://github.com/zeroclaw-labs/zeroclaw/issues/11951) [Bug]: gateway WebSocket upgrades fail over the built-in TLS listener `bug` `gateway` `release:v0.9.0`
- [#11950](https://github.com/zeroclaw-labs/zeroclaw/issues/11950) [Task]: localize the `config set` value prompts `config` `priority:p3` `follow-up` `cli`
- [#11949](https://github.com/zeroclaw-labs/zeroclaw/issues/11949) [Task]: report a refused `plugin remove` whose recovery transaction cannot be finished `bug` `priority:p3` `follow-up` `topic:plugins`
- [#11948](https://github.com/zeroclaw-labs/zeroclaw/issues/11948) [Task]: record the SOP step that ran when a cancel is finished after a refused write `runtime`
- [#11947](https://github.com/zeroclaw-labs/zeroclaw/issues/11947) [Task]: refuse SOP runs.db terminal 1 -> 0 in the SQLite schema `runtime`
- [#11946](https://github.com/zeroclaw-labs/zeroclaw/issues/11946) [Task]: keep a stale deterministic SOP checkpoint copy from overwriting the run's state file `runtime`
- [#11945](https://github.com/zeroclaw-labs/zeroclaw/issues/11945) [Task]: cover the SOP stale-copy branches that no test fails on yet `runtime`
- [#11944](https://github.com/zeroclaw-labs/zeroclaw/issues/11944) [Task]: forget SOP run_revisions entries when a run's start is rolled back `runtime`
- [#11943](https://github.com/zeroclaw-labs/zeroclaw/issues/11943) [Task]: refuse a Docker Publish dispatch that pushes a ref which is not a release tag `type:ci`
- [#11938](https://github.com/zeroclaw-labs/zeroclaw/issues/11938) [Feature]: Email channel: quote the original message in replies
- [#11932](https://github.com/zeroclaw-labs/zeroclaw/issues/11932) [Bug]: container CA bundles still trust distrusted emSign chains `bug` `domain:security` `risk:high`
- [#11930](https://github.com/zeroclaw-labs/zeroclaw/issues/11930) [Feature]: Support longer synchronous agent calls through the gateway webhook `enhancement`
- [#11928](https://github.com/zeroclaw-labs/zeroclaw/issues/11928) [Task]: remove the released-port race from the gateway bind test
- [#11926](https://github.com/zeroclaw-labs/zeroclaw/issues/11926) [Feature]: audit the full lockfile in the daily advisory scan `enhancement`

### 🔒 Closed Issues
- [#11540](https://github.com/zeroclaw-labs/zeroclaw/issues/11540) [Bug]: bubblewrap sandbox isn't detected on linux falling back to application-layer
- [#10854](https://github.com/zeroclaw-labs/zeroclaw/issues/10854) [Bug]: Literal image marker in tool output is promoted into malformed provider image
- [#10920](https://github.com/zeroclaw-labs/zeroclaw/issues/10920) [Docs]: Preserve fetch statuses in generated PR review recipe
- [#11819](https://github.com/zeroclaw-labs/zeroclaw/issues/11819) [Bug]: Quickstart lists models from the provider's default endpoint before asking for the URI, and the picker takes no typed model
- [#11831](https://github.com/zeroclaw-labs/zeroclaw/issues/11831) [Task]: move the macOS plugin smoke leg off `macos-14` before the October 19 brownout
- [#11813](https://github.com/zeroclaw-labs/zeroclaw/issues/11813) [Bug]: plugin egress connections stall when the first resolved address is blackholed and never try the others
- [#11552](https://github.com/zeroclaw-labs/zeroclaw/issues/11552) [Bug]: the tool egress ceremony ignores websocket_client and socket_client declarations
- [#11783](https://github.com/zeroclaw-labs/zeroclaw/issues/11783) [Bug]: Can't create Alpine container image
- [#11923](https://github.com/zeroclaw-labs/zeroclaw/issues/11923) [Bug]: update affected TLS certificate verifier and root packages

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,665 · **Open issues:** 1,561 · **Last push:** 1d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,906 · **Open issues:** 119 · **Last push:** <1h ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 7d ago
- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬1 · 13d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 16d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 24d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 26d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 36d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 44d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 46d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 54d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 58d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Christopher Stubbs Joins Long Term Benefit Trust](https://www.anthropic.com/news/christopher-stubbs-joins-long-term-benefit-trust) _2026-10-21_

### OpenAI — 8 new
- [[Form] Openai On Google Cloud](https://openai.com/form/openai-on-google-cloud/) _2026-10-22_
- [[Solutions] Legal](https://openai.com/business/solutions/legal/) _2026-10-22_
- [[Index] Att Legal](https://openai.com/index/att-legal/) _2026-10-22_
- [[Index] Cloudflare Cyber](https://openai.com/index/cloudflare-cyber/) _2026-10-22_
- [[Index] Openai Models Google Cloud](https://openai.com/index/openai-models-google-cloud/) _2026-10-22_
- [[Index] Broad Access Through Consistent Standards](https://openai.com/index/broad-access-through-consistent-standards/) _2026-10-22_
- [[Index] Building Chatgpt Ad Stack](https://openai.com/index/building-chatgpt-ad-stack/) _2026-10-22_
- [[Index] Empowering Cyber Defenders](https://openai.com/index/empowering-cyber-defenders/) _2026-10-22_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Be prepared, GPU price increase incoming --> Samsung sells out 100% of all 2027 HBM capacity - HBM prices expected to jump 200% next year, DRAM prices expected to see a double-digit price increase](https://reddit.com/r/LocalLLaMA/comments/1xbfhxp/be_prepared_gpu_price_increase_incoming_samsung/) ↑680
- [RecursiveSI/flint (40B A2.5B) · Hugging Face](https://reddit.com/r/LocalLLaMA/comments/1xbqik0/recursivesiflint_40b_a25b_hugging_face/) ↑414
- [When will we see these changes? --> China Is Doubling RAM Production to Keep Everyday Gadget Prices from Skyrocketing](https://reddit.com/r/LocalLLaMA/comments/1xbrh0s/when_will_we_see_these_changes_china_is_doubling/) ↑247
- [After using Flash next](https://reddit.com/r/LocalLLaMA/comments/1xc4mn5/after_using_flash_next/) ↑152
- [35B MoE running at 20.5 tok/s on an iPhone, without skipping experts](https://reddit.com/r/LocalLLaMA/comments/1xbmsgf/35b_moe_running_at_205_toks_on_an_iphone_without/) ↑152

### r/singularity — top 5 new
- [Unitree's newest robot: H2-X Kung Fu Legend Guardian](https://reddit.com/r/singularity/comments/1xbidfc/unitrees_newest_robot_h2x_kung_fu_legend_guardian/) ↑2275
- [As of 3 hours ago, the Linux Kernel no longer requires the usage of AI to be declared for new code submissions.](https://reddit.com/r/singularity/comments/1xbe2tf/as_of_3_hours_ago_the_linux_kernel_no_longer/) ↑800
- [Demis Hassabis now expects AGI in 2-3 years, down from 3-5 earlier this year](https://reddit.com/r/singularity/comments/1xbkhep/demis_hassabis_now_expects_agi_in_23_years_down/) ↑736
- [Anthropic unveils Claude Duet, a proactive AI agent powered by Opus 5.5. It works while you're away, monitors your apps, handles complex tasks using its own cloud computer, and alerts you when needed.](https://reddit.com/r/singularity/comments/1xbz98o/anthropic_unveils_claude_duet_a_proactive_ai/) ↑521
- [OpenAI's thousands of GPT-Rosalind agents analyzed millions of mouse brain cells in 32 minutes, completing research estimated to take humans months to a year. They uncovered new leads for neurodegener](https://reddit.com/r/singularity/comments/1xbx2x9/openais_thousands_of_gptrosalind_agents_analyzed/) ↑329

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Come watch us live!](https://reddit.com/r/openclaw/comments/1xbvi8f/come_watch_us_live/) ↑11
- [NVIDIA RTX Spark and the Case for Owning Your AI](https://reddit.com/r/openclaw/comments/1xc3dub/nvidia_rtx_spark_and_the_case_for_owning_your_ai/) ↑6
- [How does dreaming work? What are your experiences?](https://reddit.com/r/openclaw/comments/1xbnahm/how_does_dreaming_work_what_are_your_experiences/) ↑5
- [LinkedIN Feed scanning / scraping](https://reddit.com/r/openclaw/comments/1xbkgqv/linkedin_feed_scanning_scraping/) ↑3
- [Openclaw starting to provide diagnostics after enabled MiniMax 3.1 Flash](https://reddit.com/r/openclaw/comments/1xbz7nn/openclaw_starting_to_provide_diagnostics_after/) ↑2

### X — @openclaw
- [NVIDIA RTX Spark and the Case for Owning Your AI


@NVIDIAAI
’s Apoorv Chaudhary joins 
@hrudolph
 and 
@Pat_Erichsen
 t](https://x.com/openclaw/status/2113060682015162611) ↑0 🔁0 · recent
- [Come build OpenClaw along side our team! 

We're inviting people to join our Maintainers on our team server 

Come promp](https://x.com/openclaw/status/2113024625311686852) ↑0 🔁0 · recent
- [You're building in the terminal

OpenClaw users are building in the timeline

We are not the same

Watch Roboclaw & 
@vi](https://x.com/openclaw/status/2112990698131849368) ↑0 🔁0 · recent
- [[SANITIZED — possible injection attempt]](https://x.com/openclaw/status/2112974517387800888) ↑0 🔁0 · recent
- [One OpenClaw can kill 20 subscriptions

(and you can retain your data)](https://x.com/openclaw/status/2112961586617041042) ↑0 🔁0 · recent


### X — @steipete
- [That PHP vulnerability that’s gonna cause havoc this week was found with… GPT‑5.6 Sol.](https://x.com/steipete/status/2112913060709228764) ↑0 🔁0 · recent
- [See you at 
@Cloudflare
 Connect tomorrow! Will be chatting with 
@dok2001
 about agents](https://x.com/steipete/status/2112735411688857770) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
