---
layout: post
title: "Ecosystem Digest — 2026-06-26"
date: 2026-06-26 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-26
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 380,466 | 5 | 2 | 9 | 0 |
| **hermesagent** | 203,115 | 11 | 8 | 10 | 0 |
| **ZeroClaw** | 32,039 | 8 | 3 | 10 | 0 |
| **IronClaw** | 12,477 | 13 | 3 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 380,466 · **Open issues:** 6,627 · **Last push:** <1h ago

### ✅ Merged PRs
- [#94441](https://github.com/openclaw/openclaw/pull/94441) fix(exec): fail invalid explicit workdir before running
- [#96880](https://github.com/openclaw/openclaw/pull/96880) Fix Signal approval reactions for structured delivery
- [#92520](https://github.com/openclaw/openclaw/pull/92520) Fix Codex synthetic usage in status without local OpenAI profiles
- [#96143](https://github.com/openclaw/openclaw/pull/96143) fix(plugins): avoid spurious npm spec error after metadata failure
- [#96142](https://github.com/openclaw/openclaw/pull/96142) fix(failover): fallback on replay-safe prompt timeouts
- [#96141](https://github.com/openclaw/openclaw/pull/96141) fix(ui): reload Control UI when service worker updates
- [#96138](https://github.com/openclaw/openclaw/pull/96138) fix(diffs): reset viewer controllers on rehydrate
- [#96550](https://github.com/openclaw/openclaw/pull/96550) fix(telegram): topic replies stall after session conflicts
- [#96788](https://github.com/openclaw/openclaw/pull/96788) fix(gateway): report omitted chat-history messages in truncation log

### 🐛 New Issues
- [#96900](https://github.com/openclaw/openclaw/issues/96900) Bug: Large session JSON file causes Gateway timeout — compaction cannot prevent it 💬1
- [#96882](https://github.com/openclaw/openclaw/issues/96882) Feature Request: Group model dropdown by provider `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#96879](https://github.com/openclaw/openclaw/issues/96879) [Feature]:  Add Interactions API transport for Gemini provider `enhancement` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#96878](https://github.com/openclaw/openclaw/issues/96878) [Bug]: web_search providers, like searxng and tavily stopped working and the official plugins failed to install. `bug` `regression` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#96869](https://github.com/openclaw/openclaw/issues/96869) [Bug]: Reasoning+content streaming chunk loses visible content when an inline code span straddles the boundary (visible persisted with unclosed backtick, remainder routed to thinking) `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#96888](https://github.com/openclaw/openclaw/issues/96888) Feishu channel sends ghost interactive cards (empty body) instead of final assistant reply
- [#92506](https://github.com/openclaw/openclaw/issues/92506) [Bug]: /status usage missing for OpenAI Codex synthetic auth after 2026.6.6

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 203,115 · **Open issues:** 23,694 · **Last push:** <1h ago

### ✅ Merged PRs
- [#52760](https://github.com/NousResearch/hermes-agent/pull/52760) fix(auth): write rotated Codex/xAI pool grant through to global root (#48415)
- [#52789](https://github.com/NousResearch/hermes-agent/pull/52789) fix(docker): skip symlinked stage2 chown targets
- [#52795](https://github.com/NousResearch/hermes-agent/pull/52795) fix(agent): route reasoning-model thinking-timeouts to timeout, not phantom context_overflow (#52271)
- [#52761](https://github.com/NousResearch/hermes-agent/pull/52761) fix(gateway): defer cross-process cache cleanup off the cache lock (#52197)
- [#52671](https://github.com/NousResearch/hermes-agent/pull/52671) fix(cron): detect partial job loss in restore_cron_jobs_if_emptied (#52144)
- [#52744](https://github.com/NousResearch/hermes-agent/pull/52744) fix(telegram): persistent heartbeat loop to detect CLOSE-WAIT polling sockets (#48495)
- [#52772](https://github.com/NousResearch/hermes-agent/pull/52772) feat(desktop): in-app spot editor for the file preview pane
- [#52756](https://github.com/NousResearch/hermes-agent/pull/52756) feat(delegation): calm "will resume" affordance for background delegate_task
- [#52768](https://github.com/NousResearch/hermes-agent/pull/52768) fix(approval): fold Windows absolute home paths in dangerous-command detection
- [#52745](https://github.com/NousResearch/hermes-agent/pull/52745) desktop: bundle main.cjs for electron

### 🐛 New Issues
- [#52805](https://github.com/NousResearch/hermes-agent/issues/52805) Gateway: agent processes inbound messages but responses are never delivered to platform (WeChat/Telegram)
- [#52804](https://github.com/NousResearch/hermes-agent/issues/52804) fix(gateway): sessions.json stale entries after crash silently drop all messages until manual intervention
- [#52800](https://github.com/NousResearch/hermes-agent/issues/52800) Feature Request: Human-readable task progress narration instead of raw tool call previews `type/feature` `comp/cli` `P3`
- [#52796](https://github.com/NousResearch/hermes-agent/issues/52796) Gateway: multiplex_profiles config conflict causes fatal exit (should degrade, not die) `type/bug` `comp/gateway` `area/config` `P2` `needs-repro`
- [#52794](https://github.com/NousResearch/hermes-agent/issues/52794) BUG: Photon outbound drops after rate-limit; Desktop stale after gateway restart `type/bug` `comp/plugins` `P3` `sweeper:risk-message-delivery` `comp/desktop`
- [#52791](https://github.com/NousResearch/hermes-agent/issues/52791) [SANITIZED — possible injection attempt] `type/feature` `comp/agent` `P3`
- [#52788](https://github.com/NousResearch/hermes-agent/issues/52788) bug(desktop): CMD console window flashes on every terminal command on Windows `type/bug` `P2` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows`
- [#52787](https://github.com/NousResearch/hermes-agent/issues/52787) [Feature] Minimize to system tray instead of closing on Windows/Linux `duplicate` `type/feature` `P3` `comp/desktop` `platform/windows` 💬1
- [#52786](https://github.com/NousResearch/hermes-agent/issues/52786) Feishu adapter incorrectly downgrades markdown tables to plain text `type/bug` `duplicate` `comp/gateway` `platform/feishu` `P2` 💬1
- [#52777](https://github.com/NousResearch/hermes-agent/issues/52777) Bug: Credential pool checkout is provider-blind — causes cross-provider 403s `type/bug` `comp/agent` `area/auth` `P2` `needs-repro` `sweeper:risk-security-boundary`
- [#52773](https://github.com/NousResearch/hermes-agent/issues/52773) Support per-profile default skills in config.yaml `type/feature` `comp/cli` `tool/skills` `area/config` `P3`

### 🔒 Closed Issues
- [#48415](https://github.com/NousResearch/hermes-agent/issues/48415) [Bug]: openai-codex multi-profile rotation race — rotated grant not written through to global root (Codex analog of #43589)
- [#52803](https://github.com/NousResearch/hermes-agent/issues/52803) test issue — please ignore
- [#52781](https://github.com/NousResearch/hermes-agent/issues/52781) fix(docker): stage2-hook chown -R follows symlinks, can destroy user home directory
- [#52271](https://github.com/NousResearch/hermes-agent/issues/52271) [Bug]: Reasoning models hit phantom context-overflow on thinking-timeout (Nemotron 3 Ultra, OpenAI o1/o3, Opus 4.x thinking) — silent compression on large sessions + misleading file-write guidance
- [#52197](https://github.com/NousResearch/hermes-agent/issues/52197) [Bug]:  gateway cross-process agent-cache invalidation performs cleanup while holding _agent_cache_lock, stalling the event loop and blocking Discord heartbeats
- [#48137](https://github.com/NousResearch/hermes-agent/issues/48137) [Windows] Docker terminal backend: -w gets raw Windows path (exit 125), and docker_mount_cwd_to_workspace exposes entire home dir
- [#48495](https://github.com/NousResearch/hermes-agent/issues/48495) Telegram polling gateway silently stops receiving messages after TCP CLOSE-WAIT on long-poll socket (ep_poll on dead connection)
- [#49106](https://github.com/NousResearch/hermes-agent/issues/49106) Web/WeChat sessions leak history: turns from one Hermes session appear in another

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,039 · **Open issues:** 481 · **Last push:** 11h ago

### ✅ Merged PRs
- [#8232](https://github.com/zeroclaw-labs/zeroclaw/pull/8232) fix(providers): expose replay_assistant_reasoning and fallback tool_c…
- [#8274](https://github.com/zeroclaw-labs/zeroclaw/pull/8274) fix(gateway): require auth on A2A task invocation, leave discovery cards public
- [#8283](https://github.com/zeroclaw-labs/zeroclaw/pull/8283) fix(config): warn when a2a.exposed_skills resolves no skills
- [#8281](https://github.com/zeroclaw-labs/zeroclaw/pull/8281) fix(config): make the yolo preset fully unrestricted
- [#8254](https://github.com/zeroclaw-labs/zeroclaw/pull/8254) test(log): cover observability policy parsing edge cases
- [#8258](https://github.com/zeroclaw-labs/zeroclaw/pull/8258) test(log): cover legacy log action category mapping
- [#8246](https://github.com/zeroclaw-labs/zeroclaw/pull/8246) test(eval): cover suite report aggregation and rendering
- [#8244](https://github.com/zeroclaw-labs/zeroclaw/pull/8244) test(eval): cover evaluate_expects grading checks
- [#8188](https://github.com/zeroclaw-labs/zeroclaw/pull/8188) ci(deny): wildcards deny, advisory tracking, document multi-version debt
- [#7094](https://github.com/zeroclaw-labs/zeroclaw/pull/7094) fix(cli): make  persist the model in config

### 🐛 New Issues
- [#8334](https://github.com/zeroclaw-labs/zeroclaw/issues/8334) [Bug]: `skills install`/`list`/`remove` target data_dir, which no multi-agent runtime loads `bug` `config` `runtime` `skills`
- [#8327](https://github.com/zeroclaw-labs/zeroclaw/issues/8327) Native tool calling: [IMAGE:data:...] markers in tool results sent as plain text, inflating token count 💬1
- [#8321](https://github.com/zeroclaw-labs/zeroclaw/issues/8321) [RFC]: Define response-cache policy for volatile runtime context `enhancement` `risk: medium` `channel` `memory` `provider` `runtime` `agent:prompt` `priority:p2` `type:rfc` `status:accepted`
- [#8320](https://github.com/zeroclaw-labs/zeroclaw/issues/8320) [Bug]: Agent response cache key includes per-turn wall-clock timestamp, causing cache misses and flaky runtime test `bug` `risk: medium` `memory` `runtime` `tests` `agent:prompt` `priority:p2` `status:accepted`
- [#8314](https://github.com/zeroclaw-labs/zeroclaw/issues/8314) [Feature]: Hot-reload zeroclaw-log persistence and rotation config
- [#8312](https://github.com/zeroclaw-labs/zeroclaw/issues/8312) [Bug]: fill-translations leak-repair leaves stale translations-map entries that re-ship leaked text via write_po `bug` `risk: high` `docs` `security` `tool` `priority:p1` 💬1
- [#8310](https://github.com/zeroclaw-labs/zeroclaw/issues/8310) [Feature]: Remove deprecated skills prompt_injection_mode / full mode `enhancement` `risk: medium` `config` `runtime` `skills` `priority:p2`
- [#8309](https://github.com/zeroclaw-labs/zeroclaw/issues/8309) [Feature]: SkillForge (#144) is orphaned — wire up with safe defaults or remove? `enhancement` `risk: high` `runtime` `security` `skillforge` `priority:p2` `status:blocked` `needs-maintainer-review` 💬1

### 🔒 Closed Issues
- [#7087](https://github.com/zeroclaw-labs/zeroclaw/issues/7087) bug(cli): `zeroclaw models set` falls through to model doctor instead of saving config
- [#6714](https://github.com/zeroclaw-labs/zeroclaw/issues/6714) [Feature]: Remove remote-markdown-link block from skill audit
- [#8279](https://github.com/zeroclaw-labs/zeroclaw/issues/8279) [SANITIZED — possible injection attempt]

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,477 · **Open issues:** 1,241 · **Last push:** <1h ago

### ✅ Merged PRs
- [#5278](https://github.com/nearai/ironclaw/pull/5278) fix(webui-v2): make logs page scrollable
- [#5255](https://github.com/nearai/ironclaw/pull/5255) fix(filesystem): fold CAS put directory pre-check into one statement (3→1 round-trip)
- [#4997](https://github.com/nearai/ironclaw/pull/4997) add a seam for download_file to extract binary docs (PDF/PPTX/DOCX/XLSX) as text
- [#5222](https://github.com/nearai/ironclaw/pull/5222) fix(reborn): treat parked Blocked* triggered runs as terminal-for-delivery
- [#5206](https://github.com/nearai/ironclaw/pull/5206) fix(reborn): stop WASM execution from starving the tokio worker pool
- [#5258](https://github.com/nearai/ironclaw/pull/5258) fix(turns): exempt certified skill content from prompt content denylist (#5169)
- [#5256](https://github.com/nearai/ironclaw/pull/5256) feat(reborn): expose user-scoped tool settings
- [#5241](https://github.com/nearai/ironclaw/pull/5241) fix(reborn): keep approval gates visible on busy sends
- [#5245](https://github.com/nearai/ironclaw/pull/5245) fix(triggers): recover stale claim-only fires
- [#5248](https://github.com/nearai/ironclaw/pull/5248) fix(webui): keep streamed chat responses in view

### 🐛 New Issues
- [#5282](https://github.com/nearai/ironclaw/issues/5282) [Reborn] "Logs" entry appears inside the composer while the agent is running
- [#5276](https://github.com/nearai/ironclaw/issues/5276) Scheduled automation fails with "No thread attached" (Daily PR Digest, 0% success) 💬1
- [#5274](https://github.com/nearai/ironclaw/issues/5274) Migrate ironclaw_turns runner-lease sidecar CAS loops onto shared cas_update
- [#5273](https://github.com/nearai/ironclaw/issues/5273) [capability-policy] Four-dimension policy: delta store + PolicyResolver + config/identity/approval enforcement
- [#5272](https://github.com/nearai/ironclaw/issues/5272) [capability-policy] Minimal multi-user local auth (user-token → UserId + role)
- [#5268](https://github.com/nearai/ironclaw/issues/5268) [capability-policy] Admin REST surface (four dimensions) + REST action catalog `enhancement` `reborn`
- [#5267](https://github.com/nearai/ironclaw/issues/5267) [capability-policy] Availability resolver at the dispatch seam (ScopedLifecyclePolicyCapabilitySurfaceResolver) `enhancement` `reborn`
- [#5266](https://github.com/nearai/ironclaw/issues/5266) [capability-policy] Reborn DB-backed user role + admin gate (UserRole Owner>Admin>Member) `enhancement` `reborn`
- [#5264](https://github.com/nearai/ironclaw/issues/5264) Memory #3537 follow-ups: native SQL storage-port backing, host-managed flow, third-party lane, default flip, semantic search
- [#5261](https://github.com/nearai/ironclaw/issues/5261) [EPIC] Reborn capability policy: admin-shared tools & skills with per-user auth (continues #4628) `enhancement` `reborn`
- [#5260](https://github.com/nearai/ironclaw/issues/5260) [Tracking] Reborn personal memory & self-learning — full system
- [#5253](https://github.com/nearai/ironclaw/issues/5253) Heartbeat lease write-behind: move runner-lease renewal off the synchronous Postgres path
- [#5246](https://github.com/nearai/ironclaw/issues/5246) [Reborn] Add global auto-approve shortcut text under approval checkbox

### 🔒 Closed Issues
- [#5242](https://github.com/nearai/ironclaw/issues/5242) [Reborn] Tools page under Settings shows operator-only tools error for WebUI users
- [#5210](https://github.com/nearai/ironclaw/issues/5210) [Reborn] Sending a new message while an approval gate is open causes repeated warnings and lost message state
- [#5211](https://github.com/nearai/ironclaw/issues/5211) [Reborn] New responses do not automatically scroll into view

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#94780](https://github.com/openclaw/openclaw/issues/94780) [Feature]: Per-cron model selection independent of agent default — run cheap/free models on automation jobs while keeping main agent on premium LLM — 💬1 · 21h ago
- ⚫ [#93032](https://github.com/openclaw/openclaw/issues/93032) [Bug] v2026.6.6: Cron scheduler loads 0 jobs after upgrade — SQLite WAL not committed at first startup — 💬2 · 21h ago
- ⚫ [#92974](https://github.com/openclaw/openclaw/issues/92974) Bug: v2026.6.6 getAttributionHeaders() crashes on Bedrock models — baseUrl undefined (null-guard missing) — 💬1 · 21h ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬4 · 2d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬7 · 3d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 4d ago
- 🟢 [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬1 · 4d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬2 · 4d ago
- 🟢 [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 4d ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 4d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 11 new
- [[Form] Trademark Counterfeit Disputes](https://openai.com/form/trademark-counterfeit-disputes/) _2026-06-26_
- [[Solutions] Marketing](https://openai.com/business/solutions/marketing/) _2026-06-26_
- [[Solutions] Sales](https://openai.com/business/solutions/sales/) _2026-06-26_
- [[Solutions] Finance](https://openai.com/business/solutions/finance/) _2026-06-26_
- [[Solutions] Data](https://openai.com/business/solutions/data/) _2026-06-26_
- [[Solutions] Engineering](https://openai.com/business/solutions/engineering/) _2026-06-26_
- [[Solutions] Design](https://openai.com/business/solutions/design/) _2026-06-26_
- [[Why-Openai] Small Business](https://openai.com/business/why-openai/small-business/) _2026-06-25_
- [[Why-Openai] Enterprises](https://openai.com/business/why-openai/enterprises/) _2026-06-25_
- [[Why-Openai] Startups](https://openai.com/business/why-openai/startups/) _2026-06-25_
- [[Index] How Agents Are Transforming Work](https://openai.com/index/how-agents-are-transforming-work/) _2026-06-25_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/singularity — top 5 new
- [W iBM for this !! IBM is back (Efficiency is all we need)](https://reddit.com/r/singularity/comments/1ufh4ss/w_ibm_for_this_ibm_is_back_efficiency_is_all_we/) ↑599
- [TRUMP ADMINISTRATION ASKS OPENAI TO STAGGER RELEASE OF NEW MODEL OVER SECURITY CONCERNS](https://reddit.com/r/singularity/comments/1uflg8e/trump_administration_asks_openai_to_stagger/) ↑469
- [IBM Debuts World’s First Sub-1 Nanometer Chip Technology](https://reddit.com/r/singularity/comments/1ufbp4g/ibm_debuts_worlds_first_sub1_nanometer_chip/) ↑448
- [[Feel the singularity] I never thought a robot would replace me one day..what’s my purpose then.](https://reddit.com/r/singularity/comments/1uf3ybv/feel_the_singularity_i_never_thought_a_robot/) ↑361
- [AI takes the punches, the memory cartel takes the margins](https://reddit.com/r/singularity/comments/1ufdm4c/ai_takes_the_punches_the_memory_cartel_takes_the/) ↑167

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Still worth buying a Mac Mini for OpenClaw now that cloud options exist?](https://reddit.com/r/openclaw/comments/1ufewf8/still_worth_buying_a_mac_mini_for_openclaw_now/) ↑73
- [We’re sorry](https://reddit.com/r/openclaw/comments/1uezqx6/were_sorry/) ↑67
- [OpenClaw 6.10!](https://reddit.com/r/openclaw/comments/1ueyfzq/openclaw_610/) ↑27
- [email access - anyone crazy enough to give your mailbox access to OpenClaw? how to make it secure](https://reddit.com/r/openclaw/comments/1u9i33q/email_access_anyone_crazy_enough_to_give_your/) ↑14
- [The OpenClaw Podcast - The Clawcast - Episode 1](https://reddit.com/r/openclaw/comments/1uex90s/the_openclaw_podcast_the_clawcast_episode_1/) ↑9

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
- [Check out episode 1 of The Clawcast, our official OpenClaw podcast, with 
@hrudolph
, 
@Pat_Erichsen
, and 
@GosuCoder
!](https://x.com/openclaw) ↑0 🔁0 · recent


### X — @steipete
- [6 months](https://x.com/steipete) ↑0 🔁0 · recent
- [Thanks!](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
