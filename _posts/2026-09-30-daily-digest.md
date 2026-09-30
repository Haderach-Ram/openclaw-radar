---
layout: post
title: "Ecosystem Digest — 2026-09-30"
date: 2026-09-30 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-30
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 390,801 | 5 | 2 | 10 | 1 |
| **hermesagent** | 250,096 | 6 | 6 | 10 | 0 |
| **ZeroClaw** | 32,917 | 8 | 4 | 10 | 0 |
| **IronClaw** | 12,637 | 2 | 0 | 1 | 1 |
| **Moltis** | 2,877 | 1 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 390,801 · **Open issues:** 9,083 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.8.33](https://github.com/openclaw/openclaw/releases/tag/v2026.8.33) — openclaw 2026.8.33

### ✅ Merged PRs
- [#161498](https://github.com/openclaw/openclaw/pull/161498) improve(tests): make update lifecycle proof capture opt-in
- [#159999](https://github.com/openclaw/openclaw/pull/159999) refactor(gateway): deslop gateway core files
- [#161471](https://github.com/openclaw/openclaw/pull/161471) refactor(providers): deslop provider plugins fourth pass
- [#161490](https://github.com/openclaw/openclaw/pull/161490) refactor(plugins): deslop feature plugins fifth pass
- [#161495](https://github.com/openclaw/openclaw/pull/161495) perf(memory): reuse resolved watcher selection paths
- [#160930](https://github.com/openclaw/openclaw/pull/160930) perf(test): speed up cold source selection
- [#161089](https://github.com/openclaw/openclaw/pull/161089) fix(logging): redaction stalls for seconds on long plus-joined text
- [#160996](https://github.com/openclaw/openclaw/pull/160996) feat(cron): teach the automations tool to script repeatable job logic
- [#161500](https://github.com/openclaw/openclaw/pull/161500) chore(ui): refresh control ui locales
- [#160066](https://github.com/openclaw/openclaw/pull/160066) improve(ui): show tool icons in sidebar progress previews

### 🐛 New Issues
- [#161506](https://github.com/openclaw/openclaw/issues/161506) Session lane task stuck active (activeAhead=1 activeNow=0) starves queued turns; scheduled runs burn their wall clock with zero dispatch `P1` `impact:session-state` `impact:message-loss` 💬1
- [#161505](https://github.com/openclaw/openclaw/issues/161505) [Feature]: hold a media-only inbound message briefly so the text that follows joins the same turn (Element Web sends the attachment before the composer text) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬2
- [#161487](https://github.com/openclaw/openclaw/issues/161487) Add CI popup controls for PR repair, merge, and archive `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬2
- [#161481](https://github.com/openclaw/openclaw/issues/161481) Session SQLite migration recovery report (session-sqlite-1790727796813-13aba4f8) `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:session-state` `P0` `issue-rating: 🦐 gold shrimp` `impact:ux-release-blocker` 💬1
- [#161477](https://github.com/openclaw/openclaw/issues/161477) [Bug]: MCP OAuth server logs "expired credentials" continuously (848x/day) while live connections authorize fine `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` 💬1

### 🔒 Closed Issues
- [#161507](https://github.com/openclaw/openclaw/issues/161507) Update failure: not-git-install (2026.9.4)
- [#160063](https://github.com/openclaw/openclaw/issues/160063) Show tool icons only in sidebar progress previews

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 250,096 · **Open issues:** 47,212 · **Last push:** <1h ago

### ✅ Merged PRs
- [#128330](https://github.com/NousResearch/hermes-agent/pull/128330) fix(desktop): stop ambient window raises from stealing the Windows foreground during streaming
- [#128009](https://github.com/NousResearch/hermes-agent/pull/128009) fix(desktop): a reused tool call id no longer overwrites a finished tool row
- [#128511](https://github.com/NousResearch/hermes-agent/pull/128511) fix(update): decide ancestry link by link so an unreadable /proc/1 cannot hide the orchestrator
- [#128563](https://github.com/NousResearch/hermes-agent/pull/128563) fix(update): restore cron agent-job prompts degraded during the update window
- [#128499](https://github.com/NousResearch/hermes-agent/pull/128499) fix(desktop): detect attached-backend token drift, not just liveness (#121988)
- [#128470](https://github.com/NousResearch/hermes-agent/pull/128470) fix(providers): keep built-in routing and validation for settings-only provider blocks
- [#128446](https://github.com/NousResearch/hermes-agent/pull/128446) fix(desktop,pm): stop the boot parking on a failed update receipt and bound completion retries (#122206)
- [#128443](https://github.com/NousResearch/hermes-agent/pull/128443) fix(skills-guard): detect bare-~ destructive rm and inline-shell auto-exec DSL
- [#128417](https://github.com/NousResearch/hermes-agent/pull/128417) fix(desktop): drop dead pooled remote backends and tolerate slow remote cold boots
- [#128281](https://github.com/NousResearch/hermes-agent/pull/128281) fix(serve): retire desktop-owned backends on code skew; guard every model-mutating path (#99859)

### 🐛 New Issues
- [#128787](https://github.com/NousResearch/hermes-agent/issues/128787) [Bug]: Discord slash commands, /thread starters and voice input drop the channel's skill and flip the pinned session-context prompt `type/bug` `comp/gateway` `comp/plugins` `platform/discord` `P0` `sweeper:risk-caching`
- [#128786](https://github.com/NousResearch/hermes-agent/issues/128786) Compressed tool-result summaries drop the persisted-output path `type/bug` `comp/agent` `tool/terminal` `tool/code-exec` `P2` `sweeper:risk-session-state` `area/compression`
- [#128782](https://github.com/NousResearch/hermes-agent/issues/128782) [Bug]: hermes update hangs at autostash when repo has huge untracked files (core dumps) `type/bug` `comp/cli` `P2` `sweeper:risk-compatibility` `area/install-update`
- [#128770](https://github.com/NousResearch/hermes-agent/issues/128770) Bug: desktop app spawns wsl.exe install prompt on WSL-less Windows when switching/creating sessions `type/bug` `P3` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows`
- [#128769](https://github.com/NousResearch/hermes-agent/issues/128769) [Bug]: `hermes pm doctor` reports a declined/removed optional default as `outdated` `type/bug` `comp/cli` `P3` `area/install-update`
- [#128766](https://github.com/NousResearch/hermes-agent/issues/128766) [Bug]: Slack slash commands in a group DM run as a channel: a separate session from the group DM's messages, and disable_dms does not apply `type/bug` `comp/plugins` `platform/slack` `P3`

### 🔒 Closed Issues
- [#83998](https://github.com/NousResearch/hermes-agent/issues/83998) Desktop app steals foreground focus during active conversation streaming, dismissing Windows save/confirm dialog
- [#87514](https://github.com/NousResearch/hermes-agent/issues/87514) [Bug]: Desktop update always fails under firejail/sandboxed /proc — _is_ancestor_pid() dies on unreadable PID 1 (regression of #75847)
- [#82990](https://github.com/NousResearch/hermes-agent/issues/82990) Cron agent-job prompts silently replaced with job name after `hermes update`
- [#67368](https://github.com/NousResearch/hermes-agent/issues/67368) [Bug]: Desktop sidepanel PROJECTS tab flashes then disappears, only SESSIONS tab remains after re-render
- [#121988](https://github.com/NousResearch/hermes-agent/issues/121988) Desktop: served-token re-auth is indirect + detection-gated — externally-supervized (launchd) backend recycle is invisible to both recovery triggers, stranded 401
- [#120020](https://github.com/NousResearch/hermes-agent/issues/120020) [Bug]: A settings-only `providers.<slug>` block routes openai-codex model validation to the custom-endpoint branch and rejects the model (desktop onboarding: "Connected, but Hermes still cannot resolv

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,917 · **Open issues:** 715 · **Last push:** 3h ago

### ✅ Merged PRs
- [#11260](https://github.com/zeroclaw-labs/zeroclaw/pull/11260) fix(config): stop clamping explicit context budgets to the 32k fallback stub
- [#10592](https://github.com/zeroclaw-labs/zeroclaw/pull/10592) feat(relay): self-serve enrollment via `relay claim`
- [#10553](https://github.com/zeroclaw-labs/zeroclaw/pull/10553) feat(zerocode): add selected text to chat
- [#11227](https://github.com/zeroclaw-labs/zeroclaw/pull/11227) fix(runtime): repair logs_subscribe_carries_observer_frames_without_a_gateway on master
- [#11167](https://github.com/zeroclaw-labs/zeroclaw/pull/11167) feat(rpc): serve subscriptions from a bounded, replayable hub
- [#11222](https://github.com/zeroclaw-labs/zeroclaw/pull/11222) fix(rpc): keep session environment immutable
- [#11253](https://github.com/zeroclaw-labs/zeroclaw/pull/11253) fix(deps): bump wasmtime to 48.0.x for RUSTSEC-2026-0313..0316
- [#10425](https://github.com/zeroclaw-labs/zeroclaw/pull/10425) feat(runtime): internal-principal envelope and separated cron run outcomes (RFC #6954, 1/3)
- [#11191](https://github.com/zeroclaw-labs/zeroclaw/pull/11191) fix(config): remove the retired [security.nevis] table on incremental saves (#8289 stage 6 close-out)
- [#11196](https://github.com/zeroclaw-labs/zeroclaw/pull/11196) feat(build): stamp daemon and relay binaries with their build commit

### 🐛 New Issues
- [#11257](https://github.com/zeroclaw-labs/zeroclaw/issues/11257) [Bug]: WhatsApp Web drops the caption of inbound images, videos and documents
- [#11256](https://github.com/zeroclaw-labs/zeroclaw/issues/11256) [Bug]: initial_prompt is documented but never sent to Groq or OpenAI transcription
- [#11255](https://github.com/zeroclaw-labs/zeroclaw/issues/11255) [Feature]: Save inbound WhatsApp Web images to the workspace and mark them like Telegram
- [#11254](https://github.com/zeroclaw-labs/zeroclaw/issues/11254) RFC: A2A protocol crate (zeroclaw-a2a) `type:rfc`
- [#11239](https://github.com/zeroclaw-labs/zeroclaw/issues/11239) [Bug]: owned sessions reach the shared memory plane through spawn_subagent and execute_pipeline `bug` `memory` `security` `tool:delegate` `risk:high`
- [#11237](https://github.com/zeroclaw-labs/zeroclaw/issues/11237) [Bug]: config editor cannot write declarative cron schedule
- [#11235](https://github.com/zeroclaw-labs/zeroclaw/issues/11235) RFC: Knowledge corpus — document retrieval (RAG) for the agent `type:rfc` 💬1
- [#11233](https://github.com/zeroclaw-labs/zeroclaw/issues/11233) [Bug]: Validation results are written to reports without running the checks, or with unmeasured computed values 💬1

### 🔒 Closed Issues
- [#10068](https://github.com/zeroclaw-labs/zeroclaw/issues/10068) [Bug]: Interactive agent session caps context at 32,000 tokens, ignoring max_context_tokens = 131072
- [#10051](https://github.com/zeroclaw-labs/zeroclaw/issues/10051) [Feature]: Add selected transcript text to the ZeroCode composer
- [#11197](https://github.com/zeroclaw-labs/zeroclaw/issues/11197) [Bug]: Session resume restores forwarded environment after admin revocation
- [#10909](https://github.com/zeroclaw-labs/zeroclaw/issues/10909) [Feature]: Standard text editing in the ZeroCode composer

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,637 · **Open issues:** 1,537 · **Last push:** 5h ago

### 🚀 New Releases
- [ironclaw-v1.4.1](https://github.com/nearai/ironclaw/releases/tag/ironclaw-v1.4.1) — 1.4.1 - 2026-09-29

### ✅ Merged PRs
- [#8120](https://github.com/nearai/ironclaw/pull/8120) chore(release): promote 1.4.1-rc.2 to 1.4.1

### 🐛 New Issues
- [#8113](https://github.com/nearai/ironclaw/issues/8113) Proposal: opt-in turn-0 tool selection (BM25F + embeddings)
- [#7889](https://github.com/nearai/ironclaw/issues/7889) RFC: extend the scheduler/orchestrator with opt-in remote edge workers 💬1

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,877 · **Open issues:** 100 · **Last push:** 7d ago

### 🐛 New Issues
- [#1289](https://github.com/moltis-org/moltis/issues/1289) [Feature]: Goal mode or ralph loop `enhancement`

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 2d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬3 · 3d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 4d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 14d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 22d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 24d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 32d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 36d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 48d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 51d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 2 new
- [[Research] Glm 5 3 And The Spread Of Advanced Cyber Capabilities](https://www.anthropic.com/research/glm-5-3-and-the-spread-of-advanced-cyber-capabilities) _2026-09-29_
- [[Research] Your Thoughts On Ai](https://www.anthropic.com/research/your-thoughts-on-ai) _2026-09-29_

### OpenAI — 7 new
- [[Policies] Sign In With Chatgpt Terms](https://openai.com/policies/sign-in-with-chatgpt-terms/) _2026-09-29_
- [[Devday] 2026](https://openai.com/devday/2026/) _2026-09-29_
- [[Business] Marketplace](https://openai.com/business/marketplace/) _2026-09-29_
- [[Form] Sign In With Chatgpt Interest](https://openai.com/form/sign-in-with-chatgpt-interest/) _2026-09-29_
- [[Form] Private Intelligence Interest](https://openai.com/form/private-intelligence-interest/) _2026-09-29_
- [[Index] Introducing Dots](https://openai.com/index/introducing-dots/) _2026-09-29_
- [[Index] Devday 2026 Recap](https://openai.com/index/devday-2026-recap/) _2026-09-29_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Anthropic just dropped the greatest advertisement for GLM ever.](https://reddit.com/r/LocalLLaMA/comments/1wth4iz/anthropic_just_dropped_the_greatest_advertisement/) ↑1374
- [Looks like the era of subsidised compute is coming to an end. The old ChatGPT Pro $200 20x plan will be halved. The new $500 plan will have similar limits as the (old) $200 plan.](https://reddit.com/r/LocalLLaMA/comments/1wt5f4e/looks_like_the_era_of_subsidised_compute_is/) ↑1063
- [AMD's new 256 core  EPYC has 16-channel DDR5-12800, 91% memory bandwidth of an RTX 5090](https://reddit.com/r/LocalLLaMA/comments/1wtc4j9/amds_new_256_core_epyc_has_16channel_ddr512800_91/) ↑833
- [GLM-5.3 and the Spread of Advanced Cyber Capabilities \ Anthropic](https://reddit.com/r/LocalLLaMA/comments/1wtg0vd/glm53_and_the_spread_of_advanced_cyber/) ↑294
- [Reflection 70B was released two years ago (September 2024)](https://reddit.com/r/LocalLLaMA/comments/1wt7e94/reflection_70b_was_released_two_years_ago/) ↑199

### r/singularity — top 5 new
- [Someone using Opus 5.5 ports the entire game of Minecraft into Elden Ring, running on Mac](https://reddit.com/r/singularity/comments/1wtiubh/someone_using_opus_55_ports_the_entire_game_of/) ↑1722
- [AI is basically ubiquitous in all corporate work but reddit is convinced AI is useless, how do those 2 things co-exists?](https://reddit.com/r/singularity/comments/1wtbhb5/ai_is_basically_ubiquitous_in_all_corporate_work/) ↑644
- [GPT-6.1 Sol - Apparently near-Astra performance for complex work at a lower cost.](https://reddit.com/r/singularity/comments/1wtftlt/gpt61_sol_apparently_nearastra_performance_for/) ↑643
- [AI Gave my brother independence](https://reddit.com/r/singularity/comments/1wtq09e/ai_gave_my_brother_independence/) ↑238
- [Scientists recently gave mice without prefrontal cortexes human brain implants - and after seeing these developing connections to the mice’s brains and spinal cords - now they're wondering if these or](https://reddit.com/r/singularity/comments/1wthlb0/scientists_recently_gave_mice_without_prefrontal/) ↑187

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Phone Number for Openclaw Agent?](https://reddit.com/r/openclaw/comments/1wtq9j7/phone_number_for_openclaw_agent/) ↑4
- [Can I migrate my OpenClaw memory and agent rules to Claude Code?](https://reddit.com/r/openclaw/comments/1wtm28n/can_i_migrate_my_openclaw_memory_and_agent_rules/) ↑4
- [I ran Francis as a 1M context Discord agent for 23 hours and watched it go properly bonkers at 65% context window](https://reddit.com/r/openclaw/comments/1wtobdc/i_ran_francis_as_a_1m_context_discord_agent_for/) ↑3
- [Yolo Mode - Low Budget Boss Edition](https://reddit.com/r/openclaw/comments/1wtqvxi/yolo_mode_low_budget_boss_edition/) ↑1
- [Trying to understand ollama config](https://reddit.com/r/openclaw/comments/1wt5l3n/trying_to_understand_ollama_config/) ↑1

### X — @openclaw
- [Today we’re announcing OpenClaw Enterprise

In collaboration with 
@RedHat
 , 
@nvidia
  and 
@OpenAI
  the OpenClaw Fou](https://x.com/openclaw/status/2105023990607786313) ↑0 🔁0 · recent


### X — @steipete
- [This is pretty amazing.](https://x.com/steipete/status/2105048996549116268) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
