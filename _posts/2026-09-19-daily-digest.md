---
layout: post
title: "Ecosystem Digest — 2026-09-19"
date: 2026-09-19 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-19
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 390,059 | 4 | 1 | 10 | 1 |
| **hermesagent** | 246,928 | 9 | 8 | 6 | 0 |
| **ZeroClaw** | 32,835 | 11 | 4 | 10 | 0 |
| **IronClaw** | 12,622 | 1 | 0 | 0 | 0 |
| **Moltis** | 2,865 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 390,059 · **Open issues:** 7,910 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.9.5](https://github.com/openclaw/openclaw/releases/tag/v2026.9.5) — openclaw 2026.9.5

### ✅ Merged PRs
- [#149449](https://github.com/openclaw/openclaw/pull/149449) fix(update): avoid rehearsal failures while databases are active
- [#152342](https://github.com/openclaw/openclaw/pull/152342) fix(qa): avoid cold-start timeouts in Mantis signal tests
- [#152305](https://github.com/openclaw/openclaw/pull/152305) perf(config): resolve logging paths without config I/O
- [#152306](https://github.com/openclaw/openclaw/pull/152306) test: restore triage environment before fixture cleanup
- [#152334](https://github.com/openclaw/openclaw/pull/152334) fix(github): publish recreated branches using commit ancestry
- [#152320](https://github.com/openclaw/openclaw/pull/152320) improve(gateway): reduce allocations in clean session reads
- [#152244](https://github.com/openclaw/openclaw/pull/152244) refactor: keep plugin metadata reads independent of install roots
- [#152303](https://github.com/openclaw/openclaw/pull/152303) chore(ui): refresh control ui locales
- [#152149](https://github.com/openclaw/openclaw/pull/152149) test: collect UI garbage without heap enumeration
- [#152261](https://github.com/openclaw/openclaw/pull/152261) perf(process): reduce allocation while processing command output

### 🐛 New Issues
- [#152360](https://github.com/openclaw/openclaw/issues/152360) Plugin runtime.llm.complete never rotates auth profiles: a rate-limited first profile fails every plugin completion while agent turns fail over `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#152358](https://github.com/openclaw/openclaw/issues/152358) [Bug]: memory path search and schema check full-scan on a one-row sqlite_stat1 estimate; Gateway event loop blocked for 36 minutes `P1` `clawsweeper:needs-live-repro` `impact:crash-loop` `issue-rating: 🐚 platinum hermit` 💬2
- [#152351](https://github.com/openclaw/openclaw/issues/152351) subagent run that ended OK and was delivered keeps re-arming requester settle wake forever `P2` `clawsweeper:needs-info` `impact:session-state` `issue-rating: 🦐 gold shrimp` 💬1
- [#152338](https://github.com/openclaw/openclaw/issues/152338) [Feature]: Support Luna Reserve in Codex harness and distinguish it from credit-billed Luna `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `impact:auth-provider` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬2

### 🔒 Closed Issues
- [#152356](https://github.com/openclaw/openclaw/issues/152356) Update failure: plugin-target-unavailable (2026.9.4)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 246,928 · **Open issues:** 43,570 · **Last push:** <1h ago

### ✅ Merged PRs
- [#113439](https://github.com/NousResearch/hermes-agent/pull/113439) fix(bot-screen): stale portal status replies are dropped and a deleted-connection bot no longer throws from screen listeners (#110037, #110002)
- [#115529](https://github.com/NousResearch/hermes-agent/pull/115529) plugin-catalog: add search1api, you, prism, aihubmix (salvage #113739 #113715 #112375 #113886)
- [#112395](https://github.com/NousResearch/hermes-agent/pull/112395) feat(catalog): add pinned artifact-relay plugin
- [#113336](https://github.com/NousResearch/hermes-agent/pull/113336) Add morning-briefing to plugin catalog
- [#112847](https://github.com/NousResearch/hermes-agent/pull/112847) feat(plugin-catalog): add hermes-security-audit
- [#112610](https://github.com/NousResearch/hermes-agent/pull/112610) feat(catalog): add OpenAlex research tools

### 🐛 New Issues
- [#115572](https://github.com/NousResearch/hermes-agent/issues/115572) Bug: NameError in _apply_live_compression_config — is_truthy_value undefined (live config apply crashes for all engines)
- [#115571](https://github.com/NousResearch/hermes-agent/issues/115571) Bug: worker transcript write fails with structural corruption in messages table and indexes (v0.21.0)
- [#115570](https://github.com/NousResearch/hermes-agent/issues/115570) Relay scope-handle race on concurrent Hermes turns (shared-metrics close failure, orphan drain)
- [#115568](https://github.com/NousResearch/hermes-agent/issues/115568) Kanban dashboard: tapping a card on a touch device moves it instead of opening it
- [#115563](https://github.com/NousResearch/hermes-agent/issues/115563) [Bug]: Windows "Already up to date" update aborts (exit 1) on a relaunch-verification failure the pull path treats as non-fatal — and the atexit callback re-raises it `type/bug` `comp/cli` `P2` `sweeper:risk-compatibility` `sweeper:risk-platform-windows` `platform/windows` `area/install-update`
- [#115558](https://github.com/NousResearch/hermes-agent/issues/115558) [Feature] `hermes auth rename` — allow renaming a pooled credential's label after creation `type/feature` `comp/cli` `area/auth` `P3`
- [#115556](https://github.com/NousResearch/hermes-agent/issues/115556) Delegated batches left in non-terminal state (error/unknown) render as a phantom "subagent running" in the desktop UI `type/bug` `tool/delegate` `P2` `sweeper:risk-session-state` `comp/desktop` `area/sessions`
- [#115554](https://github.com/NousResearch/hermes-agent/issues/115554) [Feature]: make blocking-capable hook events configurable (pre_llm_call currently cannot block) `type/feature` `comp/agent` `comp/plugins` `area/config` `P3` `needs-decision`
- [#115542](https://github.com/NousResearch/hermes-agent/issues/115542) Gateway restart loop on large state.db: unclean-exit quick_check lacks progress lease `type/bug` `comp/gateway` `P2` `sweeper:risk-session-state` `sweeper:risk-message-delivery` `area/sessions`

### 🔒 Closed Issues
- [#113887](https://github.com/NousResearch/hermes-agent/issues/113887) [Wave] Refactor PR triage: superseded/stale (268 rows; corrected 2026-09-18 after maintainer re-verify)
- [#112095](https://github.com/NousResearch/hermes-agent/issues/112095) [Bug]: delegated subagent loops on vision_analyze (155 API calls / 158 vision calls in 15 min, ~4M input tokens) — no repeat guard, /steer ignored, images not prompt-cached
- [#112729](https://github.com/NousResearch/hermes-agent/issues/112729) [Bug]: Restart-safe external cron worker fails on dispatch due to symlink resolution in sys.executable
- [#111910](https://github.com/NousResearch/hermes-agent/issues/111910) Kanban: active_pr blocks authorized Closer recovery and suppression reasons are hidden
- [#112684](https://github.com/NousResearch/hermes-agent/issues/112684) [Bug]: Telegram clarify prompt is not delivered before the tool timeout
- [#111922](https://github.com/NousResearch/hermes-agent/issues/111922) [Bug]: terminal pre-guard chain (psutil proc_kinfo_oneshot) has no wall-clock bound — wedges cron run uninterruptibly; inactivity watchdog masked by tool-activity heartbeat
- [#114510](https://github.com/NousResearch/hermes-agent/issues/114510) [Wave] "Supersedes #N" watch-list — 137 rows, re-sliced by what is actionable now (corrected 2026-09-18)
- [#114012](https://github.com/NousResearch/hermes-agent/issues/114012) Codex OAuth: per-profile frozen refresh tokens race each other; self-heal only reads ~/.codex, and the goal judge misattributes the 401 to GitHub

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,835 · **Open issues:** 786 · **Last push:** <1h ago

### ✅ Merged PRs
- [#9635](https://github.com/zeroclaw-labs/zeroclaw/pull/9635) fix(config): resolve git subcommand past global options in risk classifier
- [#10648](https://github.com/zeroclaw-labs/zeroclaw/pull/10648) fix(zerocode): reduce repeated label and pinned-preview rendering work
- [#10910](https://github.com/zeroclaw-labs/zeroclaw/pull/10910) test(agent): record the sealed tool-registry parity contract
- [#10907](https://github.com/zeroclaw-labs/zeroclaw/pull/10907) feat(channels): stamp external ingress provenance
- [#10890](https://github.com/zeroclaw-labs/zeroclaw/pull/10890) fix(runtime): charge image markers a fixed per-image cost in the history token estimate
- [#10946](https://github.com/zeroclaw-labs/zeroclaw/pull/10946) feat(channels): inject Mattermost channel purpose
- [#10774](https://github.com/zeroclaw-labs/zeroclaw/pull/10774) docs(skills): correct configuration and security guidance
- [#10809](https://github.com/zeroclaw-labs/zeroclaw/pull/10809) fix(zerocode): restore macOS Control shortcut aliases
- [#10831](https://github.com/zeroclaw-labs/zeroclaw/pull/10831) docs(adr): record inbound authentication principal authority
- [#10882](https://github.com/zeroclaw-labs/zeroclaw/pull/10882) fix(zerocode): preserve provider aliases in model discovery

### 🐛 New Issues
- [#10966](https://github.com/zeroclaw-labs/zeroclaw/issues/10966) [Bug]: Git --attr-source can hide a mutating subcommand from approval classification `bug`
- [#10963](https://github.com/zeroclaw-labs/zeroclaw/issues/10963) [Feature]: Forward session identity to delegate sub-agents
- [#10962](https://github.com/zeroclaw-labs/zeroclaw/issues/10962) [Feature]: Forward tool result payloads over the gateway /ws/chat stream
- [#10952](https://github.com/zeroclaw-labs/zeroclaw/issues/10952) Seam sanitizers rewrite signed reasoning inside the assistant tool-call envelope; Anthropic rejects the replayed thinking `bug` `provider` `runtime` `provider:anthropic` 💬1
- [#10951](https://github.com/zeroclaw-labs/zeroclaw/issues/10951) [Bug]: ZeroCode Config refreshes the field list twice after saving `bug` `status:in-progress` `priority:p3` `risk:medium` `zerocode` 💬1
- [#10950](https://github.com/zeroclaw-labs/zeroclaw/issues/10950) [Bug]: cost.warn_at_percent warnings are ignored by the runtime `bug` `agent` `config` `observability` `runtime` `priority:p2` `risk:medium` `zerocode` 💬1
- [#10948](https://github.com/zeroclaw-labs/zeroclaw/issues/10948) [Bug]: interruption-scope keys collide across component boundaries `bug` `channel` `channel:core` `priority:p2` `status:in-progress` `risk:medium` 💬1
- [#10930](https://github.com/zeroclaw-labs/zeroclaw/issues/10930) RFC: One durable primitive for questions an agent asks a human `agent` `channel` `gateway` `runtime` `security` `tool` `channel:core` `domain:security` `domain:architecture` `priority:p2` `tool:sop` `needs-maintainer-review` `type:rfc` `risk:high` 💬2
- [#10929](https://github.com/zeroclaw-labs/zeroclaw/issues/10929) RFC: Delivery receipts for outbound messages `channel` `gateway` `runtime` `security` `channel:core` `domain:security` `domain:architecture` `priority:p2` `needs-maintainer-review` `type:rfc` `risk:high` 💬2
- [#10908](https://github.com/zeroclaw-labs/zeroclaw/issues/10908) [Bug]: Image markers in tool-result text are promoted to attachments without provenance; literal source and log text is stripped or attached `bug` `agent` `provider` `runtime` `tool` `domain:security` `domain:architecture` `priority:p1` `status:blocked` `status:accepted` `follow-up` `risk:high` 💬3
- [#10891](https://github.com/zeroclaw-labs/zeroclaw/issues/10891) [Feature]: Carry channel provenance through runtime admission and steering `enhancement` `channel` `runtime` `domain:security` `domain:architecture` `priority:p2` `status:in-progress` `status:accepted` `follow-up` `risk:high` 💬2

### 🔒 Closed Issues
- [#9627](https://github.com/zeroclaw-labs/zeroclaw/issues/9627) [SANITIZED — possible injection attempt]
- [#9649](https://github.com/zeroclaw-labs/zeroclaw/issues/9649) test(agent): flip parity row 1 to the tested sealed state after the registry seal
- [#10736](https://github.com/zeroclaw-labs/zeroclaw/issues/10736) [Bug]: Pre-output stream failure skips advertised non-streaming fallback
- [#10772](https://github.com/zeroclaw-labs/zeroclaw/issues/10772) [Task]: Make zeroclaw-eval archive tests independent of workspace fixtures

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,622 · **Open issues:** 1,526 · **Last push:** 2h ago

### 🐛 New Issues
- [#7537](https://github.com/nearai/ironclaw/issues/7537) feat(llm): generic per-request thinking/effort control (provider-native mapping incl. DeepSeek chat_template_kwargs) `enhancement` `scope: llm` 💬2

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,865 · **Open issues:** 90 · **Last push:** 23h ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬3 · 22h ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 3d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 11d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 13d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 19d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 21d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 25d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 37d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 40d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 43d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Accenture Embedded Evaluation](https://www.anthropic.com/news/accenture-embedded-evaluation) _2026-09-18_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [I literally built the Jev architecture one year back and completely open-sourced it with model, dataset and paper](https://reddit.com/r/LocalLLaMA/comments/1wijo3e/i_literally_built_the_jev_architecture_one_year/) ↑1926
- [768gb vram for less than the price of one RTX 6000](https://reddit.com/r/LocalLLaMA/comments/1wjr59t/768gb_vram_for_less_than_the_price_of_one_rtx_6000/) ↑700
- [Made the horizontal open-source model for Jev with RLCD, and it surpasses all the Jev benchmarks. HF space, benchmark, model, repo](https://reddit.com/r/LocalLLaMA/comments/1wjieap/made_the_horizontal_opensource_model_for_jev_with/) ↑575
- [Is HF starting to move against abliterated models?](https://reddit.com/r/LocalLLaMA/comments/1wjyn95/is_hf_starting_to_move_against_abliterated_models/) ↑254
- [M5 Ultra and M6 Chip Benchmark Results Reveal Graphics Performance](https://reddit.com/r/LocalLLaMA/comments/1wk11dq/m5_ultra_and_m6_chip_benchmark_results_reveal/) ↑153

### r/singularity — top 5 new
- [Sam, Dario and Elon have all agreed to slow down on AI acceleration](https://reddit.com/r/singularity/comments/1wekeow/sam_dario_and_elon_have_all_agreed_to_slow_down/) ↑1721
- [Neuralink’s VOICE trial is helping people with disabilities find their voice again](https://reddit.com/r/singularity/comments/1wjxket/neuralinks_voice_trial_is_helping_people_with/) ↑711
- [OpenAI: "Introducing GPT-6 Astra for Law" (new model "gpt-6-astra-law")](https://reddit.com/r/singularity/comments/1wjlmzx/openai_introducing_gpt6_astra_for_law_new_model/) ↑693
- [Running away is mathematically impossible, so stay calm.](https://reddit.com/r/singularity/comments/1wjwral/running_away_is_mathematically_impossible_so_stay/) ↑254
- [FrontierMath’s First “Major Advance” Problem Has Been Solved](https://reddit.com/r/singularity/comments/1wjvprk/frontiermaths_first_major_advance_problem_has/) ↑247

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [A new version is out—though it's not Openclaw 2.0 yet (2026.7.33)!](https://reddit.com/r/openclaw/comments/1wjlblt/a_new_version_is_outthough_its_not_openclaw_20/) ↑13
- [Complete beginner here—can someone explain OpenClaw to me in-depth? How do you actually use it?](https://reddit.com/r/openclaw/comments/1wjso0s/complete_beginner_herecan_someone_explain/) ↑11
- [WRW I am at 3% weekly GPT Pro subscription usage with 5 days until reset](https://reddit.com/r/openclaw/comments/1wjs3qv/wrw_i_am_at_3_weekly_gpt_pro_subscription_usage/) ↑7
- [Living Dangerously](https://reddit.com/r/openclaw/comments/1wjiewe/living_dangerously/) ↑6
- [Shipping OpenClaw updates that don’t break w/Jason Sy](https://reddit.com/r/openclaw/comments/1wk3k9r/shipping_openclaw_updates_that_dont_break_wjason/) ↑3

### X — @openclaw
- [The Death of the Meat Proxy is here

Welcome to Multiplayer Mode from OpenClaw


@jlehman_
 and 
@heyneighbor
 sat down ](https://x.com/openclaw/status/2101071501785276914) ↑0 🔁0 · recent
- [Last week 
@FullerStackDev
 took on the issue of updates breaking your OpenClaw

Learn what lead to this issue and how J](https://x.com/openclaw/status/2101023336252027020) ↑0 🔁0 · recent
- [Holding claws and ripping PRs together

The post meat proxy era is here](https://x.com/openclaw/status/2101019751481020674) ↑0 🔁0 · recent


### X — @steipete
- [Just landed a new feature, in the latest OC you can now ask your agent “Run this [web app] in crabbox and show me [vnc /](https://x.com/steipete/status/2101114996629570013) ↑0 🔁0 · recent
- [... works with Linux, macOS and Windows boxes ofc!](https://x.com/steipete/status/2101115571286974886) ↑0 🔁0 · recent
- [good riddance.](https://x.com/steipete/status/2101113900632772732) ↑0 🔁0 · recent
- [Our team's working hard to make OC easier to update!](https://x.com/steipete/status/2101015845652812089) ↑0 🔁0 · recent
- [gog has an mcp server now! 
https://
gogcli.sh/mcp.html](https://x.com/steipete/status/2100990473083232633) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
