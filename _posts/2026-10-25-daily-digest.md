---
layout: post
title: "Ecosystem Digest — 2026-10-25"
date: 2026-10-25 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-10-25
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 392,966 | 4 | 1 | 10 | 2 |
| **hermesagent** | 256,828 | 8 | 5 | 10 | 0 |
| **ZeroClaw** | 33,042 | 8 | 6 | 8 | 0 |
| **IronClaw** | 12,677 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,906 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 392,966 · **Open issues:** 7,823 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.10.7](https://github.com/openclaw/openclaw/releases/tag/v2026.10.7) — openclaw 2026.10.7
- [v2026.9.34](https://github.com/openclaw/openclaw/releases/tag/v2026.9.34) — openclaw 2026.9.34

### ✅ Merged PRs
- [#183123](https://github.com/openclaw/openclaw/pull/183123) feat(lint): default local lint to the pinned Bun fork
- [#182742](https://github.com/openclaw/openclaw/pull/182742) feat: record model changes in chat
- [#177577](https://github.com/openclaw/openclaw/pull/177577) fix(codex): unblock parents after native follow-up completion
- [#182295](https://github.com/openclaw/openclaw/pull/182295) fix(opencode-session-catalog): drive the pagination deadline from a monotonic clock
- [#183015](https://github.com/openclaw/openclaw/pull/183015) fix(postgres): avoid full-table sorts for limited ordered reads
- [#181585](https://github.com/openclaw/openclaw/pull/181585) fix(cli): escape terminal controls in DNS setup previews
- [#183064](https://github.com/openclaw/openclaw/pull/183064) fix: Windows workspace sync fails before lease acquisition
- [#183117](https://github.com/openclaw/openclaw/pull/183117) refactor: remove redundant pairing and plugin serialization
- [#183106](https://github.com/openclaw/openclaw/pull/183106) refactor(team-reports): use one API request deadline
- [#182846](https://github.com/openclaw/openclaw/pull/182846) perf(control-ui): remove a transcript readiness round trip

### 🐛 New Issues
- [#183141](https://github.com/openclaw/openclaw/issues/183141) [Feature]: Use existing edit masks with the bundled OpenAI image provider `clawsweeper:intake:feature` 💬1
- [#183138](https://github.com/openclaw/openclaw/issues/183138) macOS 2026.10.7: remote post-update recovery can label node-service inspection failure as a Gateway failure `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#183129](https://github.com/openclaw/openclaw/issues/183129) [Bug]: Linux subreaper kills intentionally detached exec children `bug` `regression` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:data-loss` `issue-rating: 🦐 gold shrimp` 💬1
- [#183112](https://github.com/openclaw/openclaw/issues/183112) [Bug]: Background exec completion is relayed again after the agent already read it with process log `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#183090](https://github.com/openclaw/openclaw/issues/183090) [Feature]: Docs page for using OpenLLM (local OpenAI-compatible endpoint) as a custom provider

### 🔥 Hot Issues (most commented)
- [#143524](https://github.com/openclaw/openclaw/issues/143524) [Bug]: Agent SQLite WAL grows to 1.4–2.8 GB in days despite wal_autocheckpoint=1000; blocks gateway startup (Windows, 2026.9.2/9.3) — 💬134 · 2d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 256,828 · **Open issues:** 50,853 · **Last push:** <1h ago

### ✅ Merged PRs
- [#144215](https://github.com/NousResearch/hermes-agent/pull/144215) Blank Slate: re-enabling web brings web_search back, and tools list/doctor flag partly disabled toolsets (#134593, salvage #140643)
- [#144180](https://github.com/NousResearch/hermes-agent/pull/144180) tool_search keeps small servers' descriptions beside a huge MCP server; an interactive plugin install loads into the running gateway
- [#129837](https://github.com/NousResearch/hermes-agent/pull/129837) fix(nix): extraPythonPackages no longer drops the default package's dependency groups
- [#140594](https://github.com/NousResearch/hermes-agent/pull/140594) fix(agent): record piped verification runs and stop the double nudge
- [#144211](https://github.com/NousResearch/hermes-agent/pull/144211) Model downloads keep their progress when the process is killed or the connection keeps dropping (salvage #143453)
- [#144216](https://github.com/NousResearch/hermes-agent/pull/144216) Prompt-trim follow-ups: one-shot-started sessions keep synchronous delegation; compression tail cap covers big windows
- [#144173](https://github.com/NousResearch/hermes-agent/pull/144173) browser_exec stops telling vision models they can't see, and 4 tool schemas shed 319 tokens per call (#131568, salvage #131698)
- [#144224](https://github.com/NousResearch/hermes-agent/pull/144224) The model-picker usage test and the ACP editor-MCP fork test no longer flake under CI load or a slow network
- [#144209](https://github.com/NousResearch/hermes-agent/pull/144209) test(gateway): compress-preview tests stop leaking owned/ into the repo root
- [#144177](https://github.com/NousResearch/hermes-agent/pull/144177) fix(prompt): one-shot runs drop steering, clarify and delegate live-control; skill-safety rule moves to compaction

### 🐛 New Issues
- [#144237](https://github.com/NousResearch/hermes-agent/issues/144237) Bots tab lists unmanaged profiles as normal bots while profiles.list hardcodes bot_mode_protocol:true — messaging silently disabled with no signal `type/bug` `comp/gateway` `P2` `comp/desktop` `area/profiles` `desktop/settings` `desktop/chat` `comp/tui-gateway` 💬1
- [#144236](https://github.com/NousResearch/hermes-agent/issues/144236) [Bug]: Codex CLI recovery refuses a valid token pair because the OAuth sub claim changes across IdP re-login `type/bug` `comp/cli` `provider/openai` `area/auth` `P2`
- [#144233](https://github.com/NousResearch/hermes-agent/issues/144233) Cron external worker sessions never register configured shell hooks — gateway, CLI and TUI all do `type/security` `comp/cron` `tool/terminal` `P3`
- [#144227](https://github.com/NousResearch/hermes-agent/issues/144227) API server returns HTTP 200 for a turn refused before dispatch, so OpenAI-compatible clients see success and show nothing `type/bug` `comp/gateway` `P2` `area/sessions` `area/streaming` 💬3
- [#144226](https://github.com/NousResearch/hermes-agent/issues/144226) Side environment selection from before the `gen-` schema is refused forever — the source-update tail can never complete `type/bug` `P2` `area/install-update`
- [#144223](https://github.com/NousResearch/hermes-agent/issues/144223) [Relay] Native pipeline threads busy-spin on socketpair event channels — ~80% of a core each, constant (v0.22.5) `type/perf` `comp/gateway` `P2`
- [#144213](https://github.com/NousResearch/hermes-agent/issues/144213) Windows Store build: bundled venv ships brotlicffi 1.2.0.2 (GHSA-9v8h-qqgm-4m35, critical) `type/security` `P3` `comp/desktop` `area/install-update` `os/windows`
- [#144208](https://github.com/NousResearch/hermes-agent/issues/144208) [Bug]: install.sh / pm install stalls ~24 min per URL on hosts with a dead IPv6 route (pm ignores force_ipv4) `type/bug` `P2` `area/install-update` 💬1

### 🔒 Closed Issues
- [#141820](https://github.com/NousResearch/hermes-agent/issues/141820) [Bug]: Infinite fallback loop to non-existent 'gpt-6.1-sol' on HTTP 400/404 errors in _mkm-integration branch
- [#42585](https://github.com/NousResearch/hermes-agent/issues/42585) [Bug]: web_search remains exposed via browser when the web toolset is disabled
- [#134593](https://github.com/NousResearch/hermes-agent/issues/134593) [Bug]: Invisible search toolset silently disables web_search via config, while the GUI offers only web
- [#131568](https://github.com/NousResearch/hermes-agent/issues/131568) [Bug] browser tool description tells vision-capable models "Your model cannot view images"
- [#134889](https://github.com/NousResearch/hermes-agent/issues/134889) Tracking: one gateway owns every local session (#106742) — post-merge fixes

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,042 · **Open issues:** 1,040 · **Last push:** 1h ago

### ✅ Merged PRs
- [#12011](https://github.com/zeroclaw-labs/zeroclaw/pull/12011) chore(release): bump version to v0.8.7
- [#11803](https://github.com/zeroclaw-labs/zeroclaw/pull/11803) fix(config): move the lifecycle lock into an owner-only data/.lifecycle directory
- [#11998](https://github.com/zeroclaw-labs/zeroclaw/pull/11998) fix(deps): bump ctutils to 0.4.5 for RUSTSEC-2026-0385
- [#10034](https://github.com/zeroclaw-labs/zeroclaw/pull/10034) fix(tools): probe the saved provider alias after a model-routing update
- [#12010](https://github.com/zeroclaw-labs/zeroclaw/pull/12010) fix(deps): bump ctutils and tokio for RUSTSEC-2026-0385 and RUSTSEC-2026-0386
- [#11925](https://github.com/zeroclaw-labs/zeroclaw/pull/11925) fix(containers): refresh runtime CA stores after emSign distrust
- [#11901](https://github.com/zeroclaw-labs/zeroclaw/pull/11901) fix(gateway): admit no new request after the gateway stops, and drain its connections
- [#11861](https://github.com/zeroclaw-labs/zeroclaw/pull/11861) fix(sop): keep a stale run copy from reviving or overwriting a run

### 🐛 New Issues
- [#12014](https://github.com/zeroclaw-labs/zeroclaw/issues/12014) [Bug]: Custom OpenAI-compatible provider with no context_window silently assumes 32,000, then rejects valid turns locally 💬2
- [#12006](https://github.com/zeroclaw-labs/zeroclaw/issues/12006) [Bug]: tool_search serves a deferred tool's schema as copied at registry build, so a schema that follows live config goes stale after a reload 💬1
- [#12005](https://github.com/zeroclaw-labs/zeroclaw/issues/12005) [Bug]: PowerShell dialect rejects any command with a bare `@` in an argument (allowlisted mail CLI unusable) 💬2
- [#11996](https://github.com/zeroclaw-labs/zeroclaw/issues/11996) [Feature]: send_via: explicit attachments checked under the read policy 💬1
- [#11992](https://github.com/zeroclaw-labs/zeroclaw/issues/11992) [Feature]: Email channel: operator templates and a sanitised HTML body for send_via 💬2
- [#11946](https://github.com/zeroclaw-labs/zeroclaw/issues/11946) [Task]: keep a stale deterministic SOP checkpoint copy from overwriting the run's state file `runtime` 💬1
- [#11945](https://github.com/zeroclaw-labs/zeroclaw/issues/11945) [Task]: cover the SOP stale-copy branches that no test fails on yet `runtime` 💬1
- [#11853](https://github.com/zeroclaw-labs/zeroclaw/issues/11853) ci: npm audit failed — 2026-10-19 `dependencies` `security` `risk:high` 💬2

### 🔒 Closed Issues
- [#12016](https://github.com/zeroclaw-labs/zeroclaw/issues/12016) [Feature]: let an embedding binary add hooks to chat and cron turns
- [#9592](https://github.com/zeroclaw-labs/zeroclaw/issues/9592) fix(tools): probe the saved provider alias after model-routing updates
- [#12009](https://github.com/zeroclaw-labs/zeroclaw/issues/12009) [Bug]: Security job fails on every build: RUSTSEC-2026-0385 (ctutils 0.4.2) and RUSTSEC-2026-0386 (tokio 1.53.1)
- [#11932](https://github.com/zeroclaw-labs/zeroclaw/issues/11932) [Bug]: container CA bundles still trust distrusted emSign chains
- [#11899](https://github.com/zeroclaw-labs/zeroclaw/issues/11899) [Bug]: after a daemon reload, the stopped gateway keeps serving the connections it already accepted
- [#10066](https://github.com/zeroclaw-labs/zeroclaw/issues/10066) [Bug]: SOP engine promotes and runs later steps before recording a step's output-schema rejection

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,677 · **Open issues:** 1,565 · **Last push:** 1d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,906 · **Open issues:** 120 · **Last push:** 1d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬2 · 10h ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 20h ago
- 🟢 [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬2 · 10d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 19d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 27d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 29d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 39d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 47d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 49d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 57d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Models disappearing from Huggingface](https://reddit.com/r/LocalLLaMA/comments/1xd7ptj/models_disappearing_from_huggingface/) ↑1095
- [Kimi K3.1 removes cyberattack training data from open weight release](https://reddit.com/r/LocalLLaMA/comments/1xecgrf/kimi_k31_removes_cyberattack_training_data_from/) ↑616
- [Qwen4-27B PR found](https://reddit.com/r/LocalLLaMA/comments/1xdwrak/qwen427b_pr_found/) ↑600
- [Meta trained small AI models to read raw bytes instead of tokens. They start out worse, but the paper predicts they end up better](https://reddit.com/r/LocalLLaMA/comments/1xe88ja/meta_trained_small_ai_models_to_read_raw_bytes/) ↑406
- [The RTX 5090 Isn't Gone, It's In Chinese Labs, Where Technicians Rip Off Its Die And 32GB VRAM For AI Servers](https://reddit.com/r/LocalLLaMA/comments/1xe1zsr/the_rtx_5090_isnt_gone_its_in_chinese_labs_where/) ↑391

### r/singularity — top 5 new
- [Dario Amodei, CEO of Anthropic, speaking out against the war in Iraq as a college student in 2003](https://reddit.com/r/singularity/comments/1xekblx/dario_amodei_ceo_of_anthropic_speaking_out/) ↑1047
- [Revenue: $16.3B Net loss: $80.7B IPO valuation: $2T](https://reddit.com/r/singularity/comments/1xe02h6/revenue_163b_net_loss_807b_ipo_valuation_2t/) ↑925
- [Altman: "I don't even know a dramatic enough word to use… models can find bugs that are outside of the normal threat model of what we think a hacker can do… hardware-level, insane stuff… I no longer t](https://reddit.com/r/singularity/comments/1xe5i3d/altman_i_dont_even_know_a_dramatic_enough_word_to/) ↑723
- [Absolutely crazy AI voice model by Block called Dessa.](https://reddit.com/r/singularity/comments/1xe8b2x/absolutely_crazy_ai_voice_model_by_block_called/) ↑665
- [Kimi AI told influencers not to disclose paid promotions and pushed specific narratives about their new model](https://reddit.com/r/singularity/comments/1xdquz5/kimi_ai_told_influencers_not_to_disclose_paid/) ↑452

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [8 ClawHub skills for running a creator workflow on OpenClaw](https://reddit.com/r/openclaw/comments/1xdzs9h/8_clawhub_skills_for_running_a_creator_workflow/) ↑5
- [Link with WhatsApp](https://reddit.com/r/openclaw/comments/1xdyn55/link_with_whatsapp/) ↑2
- [Is this impressive](https://reddit.com/r/openclaw/comments/1xbella/is_this_impressive/) ↑2
- [So Google changed their API header and it's futzed my websearch.](https://reddit.com/r/openclaw/comments/1xem4o0/so_google_changed_their_api_header_and_its_futzed/) ↑0

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [What is OpenClaw Enterprise, and why does it matter?


@heyneighbor
  sat down with 
@kevins8
 to talk about:

- What Op](https://x.com/openclaw/status/2113756866300010520)

### X — @steipete
_No new tweets since the last digest. Most recent:_
- [I’ll wait a bit before thinking about a new phone.](https://x.com/steipete/status/2113788999303385180)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
