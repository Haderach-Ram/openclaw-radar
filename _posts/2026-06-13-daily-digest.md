---
layout: post
title: "Ecosystem Digest — 2026-06-13"
date: 2026-06-13 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-13
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 378,406 | 11 | 1 | 8 | 2 |
| **hermesagent** | 192,031 | 11 | 3 | 10 | 0 |
| **ZeroClaw** | 31,889 | 9 | 3 | 1 | 0 |
| **IronClaw** | 12,445 | 15 | 8 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 378,406 · **Open issues:** 7,983 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.6](https://github.com/openclaw/openclaw/releases/tag/v2026.6.6) — openclaw 2026.6.6
- [v2026.6.6-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.6.6-beta.2) — openclaw 2026.6.6-beta.2

### ✅ Merged PRs
- [#92396](https://github.com/openclaw/openclaw/pull/92396) fix(moonshot): backfill reasoning_content on assistant tool-call replay messages
- [#92229](https://github.com/openclaw/openclaw/pull/92229) Fix doctor preview channel SecretRef resolution
- [#92566](https://github.com/openclaw/openclaw/pull/92566) Fix lifecycle timeout cleanup after leader exit
- [#92554](https://github.com/openclaw/openclaw/pull/92554) feat(moonshot): add Kimi K2.7 Code support
- [#84082](https://github.com/openclaw/openclaw/pull/84082) fix(telegram): allow expandable blockquotes
- [#91500](https://github.com/openclaw/openclaw/pull/91500) Add QA scorecard taxonomy validation
- [#91484](https://github.com/openclaw/openclaw/pull/91484) Add QA evidence artifact output
- [#92540](https://github.com/openclaw/openclaw/pull/92540) chore: fix esbuild production audit failure

### 🐛 New Issues
- [#92572](https://github.com/openclaw/openclaw/issues/92572) [Bug]: Claude Opus 4.6 via `agy` CLI returns 404 in web UI despite working in terminal `bug` `bug:behavior` 💬1
- [#92569](https://github.com/openclaw/openclaw/issues/92569) MCP server processes leaked across sessions — stale PID holds file lock on next reconnect 💬1
- [#92567](https://github.com/openclaw/openclaw/issues/92567) [Bug]: iOS node (2026.6.5) never presents device identity over Tailscale Serve — DEVICE_IDENTITY_REQUIRED loop, no pairing request created 💬1
- [#92563](https://github.com/openclaw/openclaw/issues/92563) session-memory hook duplicates assistant messages when thinking is stripped 💬1
- [#92562](https://github.com/openclaw/openclaw/issues/92562) [SANITIZED — possible injection attempt] `bug` `bug:behavior` 💬1
- [#92561](https://github.com/openclaw/openclaw/issues/92561) [Security]: loadProjectContextFiles walks ancestor directories to filesystem root — untrusted file injection outside workspace boundary 💬1
- [#92559](https://github.com/openclaw/openclaw/issues/92559) Feature: Session-aware template variables in extra_body (e.g. {{session.channel}}) 💬1
- [#92553](https://github.com/openclaw/openclaw/issues/92553) ModelRegistry: a single invalid plugin catalog aborts the entire custom-models load, leaving zero models and an unlogged error 💬1
- [#92551](https://github.com/openclaw/openclaw/issues/92551) Docker image ships an extraneous stale openclaw in /app/node_modules (extensions pin the published release) 💬1
- [#92549](https://github.com/openclaw/openclaw/issues/92549) Small note from HVTracker: would you be open to adding your trust badge? 💬1
- [#92546](https://github.com/openclaw/openclaw/issues/92546) [Bug]: `openclaw plugins update whatsapp` silently wipes Baileys session — full QR re-pair required after every minor plugin update 💬1

### 🔒 Closed Issues
- [#71491](https://github.com/openclaw/openclaw/issues/71491) Kimi K2.6 reasoning_content 400 regression in long conversations after LCM compaction (follow-up #70392)

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 1d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 192,031 · **Open issues:** 20,133 · **Last push:** <1h ago

### ✅ Merged PRs
- [#45273](https://github.com/NousResearch/hermes-agent/pull/45273) feat(desktop): worktree-aware sidebar grouping + composer/sidebar UX fixes
- [#45281](https://github.com/NousResearch/hermes-agent/pull/45281) fix(agent): metadata flag on compression summary messages, wire-safe key (salvages #38434)
- [#45283](https://github.com/NousResearch/hermes-agent/pull/45283) chore: add Kimi K2.7 code catalog slug
- [#45262](https://github.com/NousResearch/hermes-agent/pull/45262) fix(skills): run youtube transcript helper through uv
- [#45260](https://github.com/NousResearch/hermes-agent/pull/45260) fix(agent): clamp and rewind session flush cursor after repair_message_sequence compaction (#44837)
- [#45259](https://github.com/NousResearch/hermes-agent/pull/45259) fix(agent): honor protect_last_n (capped) as the compaction tail floor (salvages #39170)
- [#45263](https://github.com/NousResearch/hermes-agent/pull/45263) feat(desktop): follow streaming output at bottom + jump-to-bottom button
- [#45246](https://github.com/NousResearch/hermes-agent/pull/45246) fix(profiles): exclude session history, backups, and snapshots from --clone-all
- [#45247](https://github.com/NousResearch/hermes-agent/pull/45247) fix(profiles): backfill .env for pre-existing profiles on hermes update
- [#45249](https://github.com/NousResearch/hermes-agent/pull/45249) fix(compressor,webui): keep last visible assistant reply readable after compaction (salvages #29862)

### 🐛 New Issues
- [#45342](https://github.com/NousResearch/hermes-agent/issues/45342) [Bug]: Desktop Language switcher row missing from Appearance settings (component doesn't render)
- [#45340](https://github.com/NousResearch/hermes-agent/issues/45340) [Feature]: anyone ready to make money through hacking 💬1
- [#45336](https://github.com/NousResearch/hermes-agent/issues/45336) TUI can route follow-up user prompts into delegated child/subagent sessions
- [#45335](https://github.com/NousResearch/hermes-agent/issues/45335) hermes cron edit --profile <name> returns "Job not found" for all jobs
- [#45333](https://github.com/NousResearch/hermes-agent/issues/45333) Rapport : Financements et Régulations AI (13 juin 2026)
- [#45332](https://github.com/NousResearch/hermes-agent/issues/45332) fix: Strip `reasoning_content` from messages on cross-provider fallback to non-thinking providers
- [#45331](https://github.com/NousResearch/hermes-agent/issues/45331) plur memory provider — YAML+git-backed persistent memory for cross-device context sync
- [#45328](https://github.com/NousResearch/hermes-agent/issues/45328) fix(auxiliary_client): cache eviction calls async close without awaiting 💬1
- [#45325](https://github.com/NousResearch/hermes-agent/issues/45325) [Bug]: Weixin gateway restart leaves zombie sessions — at_end null, double AIAgent instances per chat `type/bug` `comp/gateway` `platform/wecom` `P2`
- [#45323](https://github.com/NousResearch/hermes-agent/issues/45323) [Bug]: Telegram rich tables are rewritten into bullets by the shared formatter `type/bug` `comp/gateway` `comp/tools` `platform/telegram` `P2` 💬2
- [#45321](https://github.com/NousResearch/hermes-agent/issues/45321) Termux: $PREFIX/bin/hermes wrapper shebang #!/usr/bin/env bash does not work `type/bug` `comp/cli` `area/config` `P3`

### 🔒 Closed Issues
- [#7237](https://github.com/NousResearch/hermes-agent/issues/7237) [Bug]: Error: Response truncated due to output length limit
- [#45242](https://github.com/NousResearch/hermes-agent/issues/45242) auxiliary_client.py: unhandled auth_type 'oauth_minimax' breaks all auxiliary tasks for minimax-oauth users
- [#38392](https://github.com/NousResearch/hermes-agent/issues/38392) Context compression summaries injected as regular assistant messages, polluting visible conversation

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,889 · **Open issues:** 471 · **Last push:** 6h ago

### ✅ Merged PRs
- [#7517](https://github.com/zeroclaw-labs/zeroclaw/pull/7517) fix(runtime/subagent): inherit ACP session cwd into spawn_subagent and delegate

### 🐛 New Issues
- [#7543](https://github.com/zeroclaw-labs/zeroclaw/issues/7543) [Feature]: Multi-session support in the gateway web chat UI (session sidebar: new / switch / rename / delete)
- [#7542](https://github.com/zeroclaw-labs/zeroclaw/issues/7542) [Bug]: `ask_user` fails instantly with "Channel closed before receiving a response" in gateway web dashboard sessions
- [#7541](https://github.com/zeroclaw-labs/zeroclaw/issues/7541) [Bug]: V3 legacy paths still use shared data_dir as agent workspace_dir: gateway WS chat default session cwd + one-shot channel send builder
- [#7539](https://github.com/zeroclaw-labs/zeroclaw/issues/7539) [Feature]: llama.cpp model router `enhancement`
- [#7537](https://github.com/zeroclaw-labs/zeroclaw/issues/7537) [Bug]: zeroclaw quickstart cannot install the agent and said no map-keyed/list section at peer-groups  `bug`
- [#7533](https://github.com/zeroclaw-labs/zeroclaw/issues/7533) [Bug]: Docker Build Failure during cargo web build due to missing ++ `bug`
- [#7531](https://github.com/zeroclaw-labs/zeroclaw/issues/7531) [Feature]: Support streaming card messages for QQ/DingTalk/WeChat/Feishu to reduce user wait time and anxiety `enhancement`
- [#7527](https://github.com/zeroclaw-labs/zeroclaw/issues/7527) [Bug]: macos app not work `bug`
- [#7523](https://github.com/zeroclaw-labs/zeroclaw/issues/7523) [Bug]: dashboard not valiable `bug` 💬1

### 🔒 Closed Issues
- [#6443](https://github.com/zeroclaw-labs/zeroclaw/issues/6443) [Feature]: Add Twitch chat channel (thin IRC adapter)
- [#7112](https://github.com/zeroclaw-labs/zeroclaw/issues/7112) [Tracker]: v0.8.0 release queue and Stable-tier blockers
- [#7263](https://github.com/zeroclaw-labs/zeroclaw/issues/7263) [Bug]: Subagents do not inherit "cwd" in ACP sessions

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,445 · **Open issues:** 1,157 · **Last push:** <1h ago

### ✅ Merged PRs
- [#4773](https://github.com/nearai/ironclaw/pull/4773) test: record/replay machinery for QA-phrase traces on the Reborn runtime
- [#4568](https://github.com/nearai/ironclaw/pull/4568) [hooks] Bound before-capability dispatch fan-out
- [#4562](https://github.com/nearai/ironclaw/pull/4562) [hooks] Record auth continuation dispatch failures
- [#4569](https://github.com/nearai/ironclaw/pull/4569) [hooks] Enforce aggregate tenant predicate key caps
- [#4769](https://github.com/nearai/ironclaw/pull/4769) test: add Reborn QA use-case e2e suites on the binary-E2E harness
- [#4826](https://github.com/nearai/ironclaw/pull/4826) fix(deps): update postgres crates for RUSTSEC-2026-0178/0179/0180
- [#4811](https://github.com/nearai/ironclaw/pull/4811) Post Slack feedback when a message is deferred behind a pending gate
- [#4799](https://github.com/nearai/ironclaw/pull/4799) Slack gate routing Phase B (revival of #4753): delivered-route resolution with one-to-many conversation index
- [#4808](https://github.com/nearai/ironclaw/pull/4808) Recover auth flows, tool-activity stream, and LLM test connection
- [#4795](https://github.com/nearai/ironclaw/pull/4795) feat(reborn): surface loop-start runtime context (time) in prompt bundles

### 🐛 New Issues
- [#4828](https://github.com/nearai/ironclaw/issues/4828) Surface connected channels, outbound delivery state, and run origin as a runtime-context slice
- [#4825](https://github.com/nearai/ironclaw/issues/4825) Reborn: persist "always allow" approvals across threads (drop thread_id from persistent approval scope) 💬3
- [#4824](https://github.com/nearai/ironclaw/issues/4824) cargo-deny failing repo-wide: new RUSTSEC advisories against postgres crates
- [#4823](https://github.com/nearai/ironclaw/issues/4823) [Reborn] No UI feedback when deleting a running conversation fails
- [#4822](https://github.com/nearai/ironclaw/issues/4822) Track Engine V2 LLM usage in /api/admin/usage
- [#4819](https://github.com/nearai/ironclaw/issues/4819) [Reborn] Attachment warning banner is difficult to read in Light theme
- [#4818](https://github.com/nearai/ironclaw/issues/4818) Decompose slack_delivery.rs (~4k lines) into focused modules
- [#4817](https://github.com/nearai/ironclaw/issues/4817) DeferredBusy drain follow-ups: trusted-resubmit seam, stale-intent policy, startup sweep 💬3
- [#4816](https://github.com/nearai/ironclaw/issues/4816) Further partition Reborn root tests
- [#4815](https://github.com/nearai/ironclaw/issues/4815) Shard Tests (Reborn) ironclaw_webui_v2 package job
- [#4814](https://github.com/nearai/ironclaw/issues/4814) Shard Tests (Legacy) all-features job
- [#4813](https://github.com/nearai/ironclaw/issues/4813) Split long CI test jobs into smaller shards
- [#4810](https://github.com/nearai/ironclaw/issues/4810) [Reborn] Conversation Testing Findings 06/08/2026 - 06/14/2026
- [#4809](https://github.com/nearai/ironclaw/issues/4809) [Reborn] GitHub Extension Testing Findings 06/08/2026 - 06/14/2026
- [#4807](https://github.com/nearai/ironclaw/issues/4807) [Reborn] github.list_issues returns pull requests together with issues

### 🔒 Closed Issues
- [#4833](https://github.com/nearai/ironclaw/issues/4833) Filesystem backend: per-thread DeferredBusy index to avoid full transcript scans
- [#4832](https://github.com/nearai/ironclaw/issues/4832) Batch drained DeferredBusy messages into a single run
- [#4831](https://github.com/nearai/ironclaw/issues/4831) Route DeferredBusy drain resubmission through a product_workflow replay entry point
- [#4733](https://github.com/nearai/ironclaw/issues/4733) [Reborn] Clicking response links navigates away from the active conversation
- [#4722](https://github.com/nearai/ironclaw/issues/4722) [Reborn] Conversation messages do not display user or assistant identity
- [#4721](https://github.com/nearai/ironclaw/issues/4721) [Reborn] Sidebar "PINNED" section represents the active conversation instead of pinned conversations
- [#4719](https://github.com/nearai/ironclaw/issues/4719) [Reborn] Conversation content area flickers when returning to a chat
- [#4725](https://github.com/nearai/ironclaw/issues/4725) [Reborn] Composer remains interactive while in Working state

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 7d ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 8d ago
- ⚫ [#88967](https://github.com/openclaw/openclaw/issues/88967) Telegram: allowBots support for group chats (bot-authored messages not ingested into session) — 💬1 · 8d ago
- ⚫ [#88517](https://github.com/openclaw/openclaw/issues/88517) [SANITIZED — possible injection attempt] — 💬3 · 9d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 10d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 10d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬5 · 12d ago
- ⚫ [#86371](https://github.com/openclaw/openclaw/issues/86371) Bug: message tool filePath fails with LocalMediaAccessError in retry flows when agentId is not propagated — 💬1 · 15d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 18d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 31d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 3 new
- [[News] Anthropic Public Record](https://www.anthropic.com/news/anthropic-public-record) _2026-06-12_
- [[News] Fable Mythos Access](https://www.anthropic.com/news/fable-mythos-access) _2026-06-13_
- [[News] Tcs Anthropic Partnership](https://www.anthropic.com/news/tcs-anthropic-partnership) _2026-06-12_

### OpenAI — 5 new
- [[Policies] Ad Tools Subprocessors](https://openai.com/policies/ad-tools-subprocessors/) _2026-06-13_
- [[Policies] Ad Tools Terms](https://openai.com/policies/ad-tools-terms/) _2026-06-13_
- [[Index] Preply](https://openai.com/index/preply/) _2026-06-13_
- [[Policies] Ad Tools Dpa](https://openai.com/policies/ad-tools-dpa/) _2026-06-12_
- [[Index] Academy Courses Applying Ai At Work](https://openai.com/index/academy-courses-applying-ai-at-work/) _2026-06-12_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [moonshotai/Kimi-K2.7-Code · Hugging Face](https://reddit.com/r/LocalLLaMA/comments/1u3rdk9/moonshotaikimik27code_hugging_face/) ↑657
- [MiniMaxAI/MiniMax-M3 · Hugging Face](https://reddit.com/r/LocalLLaMA/comments/1u3wagy/minimaxaiminimaxm3_hugging_face/) ↑562
- [We should heavily discourage and moderate cloud API (deepseek api, GLM api, etc.) topics and discussion. This is LOCAL first.](https://reddit.com/r/LocalLLaMA/comments/1u3vrrk/we_should_heavily_discourage_and_moderate_cloud/) ↑493
- [[NEW MODEL] Supra-Title-0.3B Just released!](https://reddit.com/r/LocalLLaMA/comments/1u3tvgh/new_model_supratitle03b_just_released/) ↑293
- [Local LLMs aren't democratic anymore... the hardware barrier has gotten out of hand.](https://reddit.com/r/LocalLLaMA/comments/1u479jf/local_llms_arent_democratic_anymore_the_hardware/) ↑236

### r/singularity — top 5 new
- [Forbes Declares Elon Musk As The World’s First Trillionaire](https://reddit.com/r/singularity/comments/1u4018a/forbes_declares_elon_musk_as_the_worlds_first/) ↑1691
- [Happy 9th Birthday to the Paper That Set All This Off](https://reddit.com/r/singularity/comments/1u42n1y/happy_9th_birthday_to_the_paper_that_set_all_this/) ↑782
- [US government directive to suspend access to Fable 5 and Mythos 5](https://reddit.com/r/singularity/comments/1u4cxr8/us_government_directive_to_suspend_access_to/) ↑557
- [Google DeepMind published a 60-page paper mapping the road from AGI to ASI](https://reddit.com/r/singularity/comments/1u42yx8/google_deepmind_published_a_60page_paper_mapping/) ↑407
- [Kimi 2.7 code is released & open-sourced, latest coding model by Kimi](https://reddit.com/r/singularity/comments/1u3rdvs/kimi_27_code_is_released_opensourced_latest/) ↑405

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
