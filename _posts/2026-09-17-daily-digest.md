---
layout: post
title: "Ecosystem Digest — 2026-09-17"
date: 2026-09-17 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-17
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 389,908 | 9 | 3 | 10 | 0 |
| **hermesagent** | 246,214 | 10 | 4 | 10 | 0 |
| **ZeroClaw** | 32,856 | 14 | 3 | 8 | 0 |
| **IronClaw** | 12,622 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,865 | 1 | 1 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 389,908 · **Open issues:** 7,577 · **Last push:** <1h ago

### ✅ Merged PRs
- [#150453](https://github.com/openclaw/openclaw/pull/150453) fix: restore initialization in fresh PR wrappers
- [#150222](https://github.com/openclaw/openclaw/pull/150222) improve(telegram): reduce formatting work for prose replies
- [#147581](https://github.com/openclaw/openclaw/pull/147581) fix(update): retain configuration and plugin failure details
- [#150243](https://github.com/openclaw/openclaw/pull/150243) improve: reduce audit event persistence overhead
- [#111148](https://github.com/openclaw/openclaw/pull/111148) fix(discord): rejoin threads on unarchive to restore MESSAGE_CREATE events
- [#150317](https://github.com/openclaw/openclaw/pull/150317) fix(browser): Space key from Control UI rejected as empty press
- [#150379](https://github.com/openclaw/openclaw/pull/150379) refactor: share invalid-config recovery test runtime
- [#149831](https://github.com/openclaw/openclaw/pull/149831) improve(sessions): avoid redundant inserts during transcript appends
- [#148683](https://github.com/openclaw/openclaw/pull/148683) fix(gateway-client): reconcile toolUse-persisted final answers with live projection
- [#150472](https://github.com/openclaw/openclaw/pull/150472) Restore quiet Slack previews and reliable follow-ups on the release branch

### 🐛 New Issues
- [#150508](https://github.com/openclaw/openclaw/issues/150508) Control UI: transcript jumps upward when a session opens `maintainer`
- [#150506](https://github.com/openclaw/openclaw/issues/150506) Control UI: wrong theme flashes during startup before the saved theme is applied `maintainer`
- [#150500](https://github.com/openclaw/openclaw/issues/150500) Control UI: closing an active split pane remounts its conversation in the surviving pane `maintainer` `P2` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#150498](https://github.com/openclaw/openclaw/issues/150498) [SANITIZED — possible injection attempt] `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `impact:security` `impact:message-loss` `issue-rating: 🦪 silver shellfish` 💬1
- [#150496](https://github.com/openclaw/openclaw/issues/150496) [Bug]: `openclaw channels logout --channel ""` clears the only configured channel's saved auth instead of failing `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:data-loss` `P0` `issue-rating: 🦞 diamond lobster` `maturity:stable` `clawsweeper:bulk-filed` 💬1
- [#150489](https://github.com/openclaw/openclaw/issues/150489) Bug: Codex context-engine compaction drops stable sender provenance `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#150488](https://github.com/openclaw/openclaw/issues/150488) Subagent coordination leaks into chat and triggers peer reply loops `maintainer` `P1` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#150487](https://github.com/openclaw/openclaw/issues/150487) [SANITIZED — possible injection attempt] `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` 💬1
- [#150486](https://github.com/openclaw/openclaw/issues/150486) Chat: reply attribution should name the user and quote the prompt being answered `maintainer` `P2` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#150449](https://github.com/openclaw/openclaw/issues/150449) Fresh PR wrapper snapshots fail to load plugin discovery
- [#150239](https://github.com/openclaw/openclaw/issues/150239) Audit writer repeatedly compiles fixed SQLite queries
- [#150298](https://github.com/openclaw/openclaw/issues/150298) [Bug]: Control UI Browser panel drops the Space key when typing into a page (regression in 2026.9.4)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 246,214 · **Open issues:** 43,589 · **Last push:** <1h ago

### ✅ Merged PRs
- [#112443](https://github.com/NousResearch/hermes-agent/pull/112443) fix(local-runtime): reject incomplete downloads before caching
- [#113266](https://github.com/NousResearch/hermes-agent/pull/113266) fix(desktop): Model settings reads for an "Applies to" profile dial the backend foreground (#111651)
- [#113234](https://github.com/NousResearch/hermes-agent/pull/113234) fix(cli): `hermes -z` exits non-zero for partial, failed and interrupted runs even when text was printed (#111770)
- [#113254](https://github.com/NousResearch/hermes-agent/pull/113254) fix(desktop): cold boot against an unreachable remote gateway shows the recovery screen instead of looping behind CONNECTING (#112899, salvage #73442)
- [#113257](https://github.com/NousResearch/hermes-agent/pull/113257) fix(approval): plugin sandbox backends that declare skip_container_guards skip dangerous-command prompts like built-in sandboxes (#112706, salvage #112711)
- [#113493](https://github.com/NousResearch/hermes-agent/pull/113493) test(code-kernel): remote eviction test no longer races its own worker thread
- [#113262](https://github.com/NousResearch/hermes-agent/pull/113262) fix(setup): SSH wizard resets a saved custom port back to the default (#112518, salvage #112519)
- [#113261](https://github.com/NousResearch/hermes-agent/pull/113261) fix(browser): browser_exec no longer echoes vault-filled passwords back to the model (#112693, salvage #112699)
- [#113250](https://github.com/NousResearch/hermes-agent/pull/113250) fix(terminal): singularity, daytona and vercel_sandbox backends create environments again instead of a TypeError (#112715, salvage #112723)
- [#113228](https://github.com/NousResearch/hermes-agent/pull/113228) fix(tools): self-repo guard blocks git mutations in heredoc bodies piped to a shell (#112441, supersedes #112442)

### 🐛 New Issues
- [#113677](https://github.com/NousResearch/hermes-agent/issues/113677) [Bug]: dashboard /api/dashboard/plugins/hub blocks the event loop for 90-300s - one synchronous catalog HTTPS request per installed plugin
- [#113673](https://github.com/NousResearch/hermes-agent/issues/113673) [Bug]: disk-cleanup's empty-dir sweep deletes PostgreSQL maintenance dirs under $HERMES_HOME/.pg0 — breaks Hindsight checkpoints and pg0 startup
- [#113672](https://github.com/NousResearch/hermes-agent/issues/113672) [Wave] Landed-but-open closes (5 verified rows)
- [#113670](https://github.com/NousResearch/hermes-agent/issues/113670) [Bug]: pre-hardening Windows Scheduled Task is never re-registered — live task has no <RestartOnFailure>, and the wscript launcher makes a restart policy unreachable anyway
- [#113669](https://github.com/NousResearch/hermes-agent/issues/113669) kanban CLI goal judge has no relay-affinity scope -> opencode-go 400 MissingSessionID turns a judge transport failure into a rejected human gate
- [#113667](https://github.com/NousResearch/hermes-agent/issues/113667) [Bug]: agent-issued `taskkill /F /IM python.exe` from inside the gateway kills the gateway — lifecycle guard has no image-name branch `type/bug` `comp/gateway` `tool/terminal` `P2` `sweeper:risk-platform-windows` `platform/windows` 💬2
- [#113665](https://github.com/NousResearch/hermes-agent/issues/113665) cron: a failing job re-alerts on every run, so operators mute failures entirely `type/bug` `comp/cron` `P2` 💬1
- [#113662](https://github.com/NousResearch/hermes-agent/issues/113662) [Bug]: Feishu WS mid-life loss is undetectable — lark-oapi start() never returns, so worker-exit detection can never fire `type/bug` `comp/plugins` `platform/feishu` `P3` `sweeper:risk-message-delivery` 💬2
- [#113658](https://github.com/NousResearch/hermes-agent/issues/113658) [Bug]: `hermes config set platform_toolsets.<platform> ...` warns "not a recognized config key" and suggests an unrelated key, while saving and resolving the value correctly `type/bug` `comp/cli` `area/config` `P3` 💬1
- [#113655](https://github.com/NousResearch/hermes-agent/issues/113655) iOS mobile app — Capacitor bridge + on-device MLX inference `type/feature` `P3` `comp/desktop`

### 🔒 Closed Issues
- [#112348](https://github.com/NousResearch/hermes-agent/issues/112348) `hermes config get` cannot tell a live value from a value nothing reads (phantom config keys)
- [#78103](https://github.com/NousResearch/hermes-agent/issues/78103) [Bug]: `hermes config set platform_toolsets.cli '["hermes-cli"]'` writes a literal string, silently discarding the explicit toolset selection
- [#112367](https://github.com/NousResearch/hermes-agent/issues/112367) test_delegate_timeout_cleanup is red on main: the test's 2s window expires inside the ~3.6s post-timeout teardown
- [#111770](https://github.com/NousResearch/hermes-agent/issues/111770) [Bug]: Incomplete, partial and interrupted turns are reported as `completed` with exit code 0

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,856 · **Open issues:** 813 · **Last push:** <1h ago

### ✅ Merged PRs
- [#9283](https://github.com/zeroclaw-labs/zeroclaw/pull/9283) fix(tools): decompress gzip/brotli/deflate web_fetch responses
- [#10304](https://github.com/zeroclaw-labs/zeroclaw/pull/10304) feat(docs): generate PR review policy zones
- [#10134](https://github.com/zeroclaw-labs/zeroclaw/pull/10134) fix(runtime): keep agent dispatch panic-free
- [#10896](https://github.com/zeroclaw-labs/zeroclaw/pull/10896) perf(ci): pin compile-job runner labels instead of reading fmt outputs
- [#10874](https://github.com/zeroclaw-labs/zeroclaw/pull/10874) perf(ci): stop queueing GitHub-hosted jobs behind fmt
- [#10590](https://github.com/zeroclaw-labs/zeroclaw/pull/10590) feat(dist): add canonical release target registry
- [#10120](https://github.com/zeroclaw-labs/zeroclaw/pull/10120) refactor(zerocode): remove unreachable TUI code
- [#9876](https://github.com/zeroclaw-labs/zeroclaw/pull/9876) feat(zerocode): report turn state to the terminal over OSC title and progress

### 🐛 New Issues
- [#10925](https://github.com/zeroclaw-labs/zeroclaw/issues/10925) [Feature]: Support input-driven mirror voice replies on Matrix `enhancement`
- [#10924](https://github.com/zeroclaw-labs/zeroclaw/issues/10924) [Bug]: Runtime-command replies enter conversational voice routing `bug`
- [#10923](https://github.com/zeroclaw-labs/zeroclaw/issues/10923) [Bug]: sandbox discovery ignores the TUI PATH that launcher resolution now honors `bug`
- [#10922](https://github.com/zeroclaw-labs/zeroclaw/issues/10922) [Bug]: WhatsApp Web ignores suppress_voice when queueing automatic TTS `bug`
- [#10921](https://github.com/zeroclaw-labs/zeroclaw/issues/10921) [Bug]: Qdrant time-bounded vector recall can omit eligible results `bug`
- [#10920](https://github.com/zeroclaw-labs/zeroclaw/issues/10920) [Docs]: Preserve fetch statuses in generated PR review recipe `docs` `type:docs`
- [#10919](https://github.com/zeroclaw-labs/zeroclaw/issues/10919) [Bug]: A2A and HTTP tool tests use separate locks for global proxy state `bug`
- [#10918](https://github.com/zeroclaw-labs/zeroclaw/issues/10918) [Bug]: Empty trailing chunk falsely marks an exact-fit HTTP response as truncated `bug`
- [#10912](https://github.com/zeroclaw-labs/zeroclaw/issues/10912) [Bug]: Streaming text guard suppresses whole replies when prose quotes a tool-result-shaped object; three retries then a generic format error `bug` `agent` `runtime`
- [#10909](https://github.com/zeroclaw-labs/zeroclaw/issues/10909) [Feature]: Standard text editing in the ZeroCode composer `enhancement`
- [#10908](https://github.com/zeroclaw-labs/zeroclaw/issues/10908) [Bug]: Image markers in tool-result text are promoted to attachments without provenance; literal source and log text is stripped or attached `bug` `provider` `runtime` `tool`
- [#10901](https://github.com/zeroclaw-labs/zeroclaw/issues/10901) [Bug]: Mattermost drops the first message in newly auto-discovered DMs `bug`
- [#10900](https://github.com/zeroclaw-labs/zeroclaw/issues/10900) [Feature]: transcription provider cascade (ordered fallback chain when the primary STT endpoint fails)
- [#10897](https://github.com/zeroclaw-labs/zeroclaw/issues/10897) [Bug]: daemon::tests::supervisor_preserves_component_error_chain flakes under parallel nextest (global log-broadcast race) `bug`

### 🔒 Closed Issues
- [#10764](https://github.com/zeroclaw-labs/zeroclaw/issues/10764) docs(review): bind generated freshness guidance to live GitHub state
- [#9207](https://github.com/zeroclaw-labs/zeroclaw/issues/9207) [Bug]: web_fetch returns garbage for compressed responses (gzip, brotli, deflate)
- [#6157](https://github.com/zeroclaw-labs/zeroclaw/issues/6157) [Bug]: Nextcloud Talk use correct bot message API

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,622 · **Open issues:** 1,524 · **Last push:** 3d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,865 · **Open issues:** 86 · **Last push:** 2d ago

### 🐛 New Issues
- [#1271](https://github.com/moltis-org/moltis/issues/1271) A remote MCP server that fails at startup is never retried, and a lost session ends every later call

### 🔒 Closed Issues
- [#1246](https://github.com/moltis-org/moltis/issues/1246) [Bug]: can't run on sandbox after a node is added

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬3 · 22h ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 1d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 9d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 11d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 17d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 19d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 23d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 35d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 38d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 41d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 10 new
- [[Index] Disrupting Malicious Uses Of Ai Silver Lining Playbook](https://openai.com/index/disrupting-malicious-uses-of-ai-silver-lining-playbook/) _2026-09-16_
- [[Index] Disrupting Malicious Uses Of Ai Romance Scam](https://openai.com/index/disrupting-malicious-uses-of-ai-romance-scam/) _2026-09-16_
- [[Index] Disrupting Malicious Uses Of Ai Trolling Stone](https://openai.com/index/disrupting-malicious-uses-of-ai-trolling-stone/) _2026-09-16_
- [[Index] Disrupting Malicious Uses Of Ai No Bell](https://openai.com/index/disrupting-malicious-uses-of-ai-no-bell/) _2026-09-16_
- [[Index] Disrupting Malicious Uses Of Ai Fish Food](https://openai.com/index/disrupting-malicious-uses-of-ai-fish-food/) _2026-09-16_
- [[Index] Disrupting Malicious Uses Of Ai False Witness](https://openai.com/index/disrupting-malicious-uses-of-ai-false-witness/) _2026-09-16_
- [[Index] Disrupting Malicious Uses Of Ai Date Bait](https://openai.com/index/disrupting-malicious-uses-of-ai-date-bait/) _2026-09-16_
- [[Index] Disrupting Malicious Uses Of Ai Cyber Special Operations](https://openai.com/index/disrupting-malicious-uses-of-ai-cyber-special-operations/) _2026-09-16_
- [[Index] Unlocking New Ways Of Working](https://openai.com/index/unlocking-new-ways-of-working/) _2026-09-16_
- [[Index] Helping Older Adults Use Ai In Everyday Life](https://openai.com/index/helping-older-adults-use-ai-in-everyday-life/) _2026-09-16_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Don’t buy a $9K RTX 5090.... instead.](https://reddit.com/r/LocalLLaMA/comments/1whf7ov/dont_buy_a_9k_rtx_5090_instead/) ↑1929
- [China's open-weight AI models are now just 4 months behind frontier US offerings, Mozilla report claims — models still lag in some benchmarks but are drastically cheaper to use](https://reddit.com/r/LocalLLaMA/comments/1wi32jg/chinas_openweight_ai_models_are_now_just_4_months/) ↑785
- [Hey, Meta. Where's those Muse Spark weights?](https://reddit.com/r/LocalLLaMA/comments/1whqm2c/hey_meta_wheres_those_muse_spark_weights/) ↑463
- [Apple May Return to Server Market With Nvidia Technology](https://reddit.com/r/LocalLLaMA/comments/1why9ao/apple_may_return_to_server_market_with_nvidia/) ↑345
- [Frontier LLM development simplified for politicians:](https://reddit.com/r/LocalLLaMA/comments/1wi5rx2/frontier_llm_development_simplified_for/) ↑230

### r/singularity — top 5 new
- [From Japanese twitter](https://reddit.com/r/singularity/comments/1wgok3w/from_japanese_twitter/) ↑2847
- [Google demonstrated RSI loop for AI discovery](https://reddit.com/r/singularity/comments/1whwy4m/google_demonstrated_rsi_loop_for_ai_discovery/) ↑945
- [Sam Altman: GPT 5.5 an average math professor. 5.6 top one or two percentile. Astra a little bit better. Internal model can do things that the best mathematicians in the world cannot.](https://reddit.com/r/singularity/comments/1whw6ej/sam_altman_gpt_55_an_average_math_professor_56/) ↑652
- [An unreleased Astra-family model added this to its persona during RL training.](https://reddit.com/r/singularity/comments/1wic0sx/an_unreleased_astrafamily_model_added_this_to_its/) ↑633
- [Finally understand why the higher-ups are freaking out](https://reddit.com/r/singularity/comments/1wi3sfs/finally_understand_why_the_higherups_are_freaking/) ↑515

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Which one of you is this?](https://reddit.com/r/openclaw/comments/1wi8j8l/which_one_of_you_is_this/) ↑115
- [Best hardware/OS for a local model (and best local LLM)](https://reddit.com/r/openclaw/comments/1whnooi/best_hardwareos_for_a_local_model_and_best_local/) ↑9
- [How to share artifacts with your agent?](https://reddit.com/r/openclaw/comments/1whwtgs/how_to_share_artifacts_with_your_agent/) ↑5
- [Openclaw repsonses painfully slow after 2.0 update](https://reddit.com/r/openclaw/comments/1wigmhi/openclaw_repsonses_painfully_slow_after_20_update/) ↑1
- [Thinking of making our OpenClaw wizard a standalone product. Would you pay for it?](https://reddit.com/r/openclaw/comments/1whxpt8/thinking_of_making_our_openclaw_wizard_a/) ↑0

### X — @openclaw
_No new tweets since the last digest. Most recent:_
- [Build your own local AI assistant 🦞

Join us, 
@huggingface
, 
@NVIDIAAI
 and 
@AntLingAGI
 for a practical session on L](https://x.com/openclaw/status/2099693949623689651)

### X — @steipete
_No new tweets since the last digest. Most recent:_
- [Excited to have you on board, Graham!](https://x.com/steipete/status/2099960081207242808)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
