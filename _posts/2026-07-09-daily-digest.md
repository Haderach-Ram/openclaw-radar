---
layout: post
title: "Ecosystem Digest — 2026-07-09"
date: 2026-07-09 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-07-09
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 382,226 | 7 | 4 | 6 | 0 |
| **hermesagent** | 211,633 | 3 | 1 | 3 | 1 |
| **ZeroClaw** | 32,200 | 9 | 6 | 10 | 0 |
| **IronClaw** | 12,508 | 9 | 5 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 382,226 · **Open issues:** 6,507 · **Last push:** <1h ago

### ✅ Merged PRs
- [#99065](https://github.com/openclaw/openclaw/pull/99065) fix(comfy): allow private service hostnames
- [#99221](https://github.com/openclaw/openclaw/pull/99221) feat(github-copilot): support GitHub Enterprise data-residency Copilot auth
- [#102331](https://github.com/openclaw/openclaw/pull/102331) fix(google-meet): keep Meet sessions on the agent that joined them
- [#102316](https://github.com/openclaw/openclaw/pull/102316) feat(xai): add Grok 4.5 support
- [#100361](https://github.com/openclaw/openclaw/pull/100361) Doctor: audit lint default selection
- [#102289](https://github.com/openclaw/openclaw/pull/102289) fix(gateway): refresh model availability after OAuth renewal

### 🐛 New Issues
- [#102324](https://github.com/openclaw/openclaw/issues/102324) anthropic-messages transport sends tool_result image blocks to text-only models (input:[text]) -> 400 `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#102323](https://github.com/openclaw/openclaw/issues/102323) anthropic: within-limit HEIC/TIFF images 400 as media_type passes through verbatim (succeeds on OpenAI and Gemini) `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#102322](https://github.com/openclaw/openclaw/issues/102322) acp: assistant text corrupted when Gateway revises in-progress output (non-append revision mis-sliced) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` `maturity:stable` 💬1
- [#102321](https://github.com/openclaw/openclaw/issues/102321) openai-completions: chat-completions refusal field dropped, assistant turn resolves to empty content `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:message-loss` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#102320](https://github.com/openclaw/openclaw/issues/102320) Gemini provider-prefixed 2.x id defeats multimodal-functionResponse capability check, embedding image tool-result in functionResponse and disabling the image-turn fallback `no-stale` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#102318](https://github.com/openclaw/openclaw/issues/102318) retry.provider fields split across settings scopes are silently dropped (deepMergeSettings shallow-merges nested objects) `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#102317](https://github.com/openclaw/openclaw/issues/102317) heartbeat: activeHours start/end time strings skip validation when every is omitted (silently runs 24/7) `no-stale` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#77922](https://github.com/openclaw/openclaw/issues/77922) [SANITIZED — possible injection attempt]
- [#102219](https://github.com/openclaw/openclaw/issues/102219) [Feature]: GitHub Copilot provider cannot reach GitHub Enterprise data-residency (*.ghe.com) tenants
- [#102345](https://github.com/openclaw/openclaw/issues/102345) [Bug]: Open dashboard will show up the ws connect page when you restart the openclaw desktop
- [#102338](https://github.com/openclaw/openclaw/issues/102338) [Bug]: Exec approval denied, but assistant still claims it fetched external command results

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 211,633 · **Open issues:** 27,010 · **Last push:** 2h ago

### 🚀 New Releases
- [v2026.7.7.2](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.7.7.2) — Hermes Agent v0.18.2 (2026.7.7.2)

### ✅ Merged PRs
- [#57855](https://github.com/NousResearch/hermes-agent/pull/57855) feat(desktop): ts-ify everything
- [#61147](https://github.com/NousResearch/hermes-agent/pull/61147) feat(desktop): group tool calls across text-less assistant messages
- [#61139](https://github.com/NousResearch/hermes-agent/pull/61139) fix(cli): run /new session-boundary memory extraction off the command path (#16454 salvage)

### 🐛 New Issues
- [#61249](https://github.com/NousResearch/hermes-agent/issues/61249) [Feature]: Desktop approval bar truncates the approval description to one line — no way to review a multi-line change/diff before approving 💬1
- [#61246](https://github.com/NousResearch/hermes-agent/issues/61246) Feature Request: 关闭窗口时最小化到系统托盘（Minimize to System Tray on Close） `duplicate` `type/feature` `P3` `comp/desktop` 💬2
- [#61243](https://github.com/NousResearch/hermes-agent/issues/61243) [Feature]: self-hosted OIDC provider should support RP-Initiated Logout (end_session_endpoint) `duplicate` `type/feature` `comp/plugins` `area/auth` `P3` `comp/dashboard` 💬1

### 🔒 Closed Issues
- [#28260](https://github.com/NousResearch/hermes-agent/issues/28260) [Bug]: custom_providers with self-signed HTTPS endpoints fail with APIConnectionError (ssl verify)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,200 · **Open issues:** 469 · **Last push:** 1h ago

### ✅ Merged PRs
- [#8861](https://github.com/zeroclaw-labs/zeroclaw/pull/8861) fix(providers): resolve alias credential for model-catalog so native /models is used
- [#8639](https://github.com/zeroclaw-labs/zeroclaw/pull/8639) feat(zerocode): TodoWrite tracker for ZeroCode (RPC + ACP + durable persistence)
- [#8795](https://github.com/zeroclaw-labs/zeroclaw/pull/8795) fix(web): add Skills nav entry to left sidebar (#8792)
- [#8869](https://github.com/zeroclaw-labs/zeroclaw/pull/8869) fix(log): shut down previous writer worker on re-init
- [#8868](https://github.com/zeroclaw-labs/zeroclaw/pull/8868) fix(memory): make SqliteMemory: Clone valid by sharing one embedder lock
- [#8723](https://github.com/zeroclaw-labs/zeroclaw/pull/8723) fix(security): preserve generated file references in leak scans
- [#8427](https://github.com/zeroclaw-labs/zeroclaw/pull/8427) feat(whatsapp): add native location pin support to both backends
- [#8623](https://github.com/zeroclaw-labs/zeroclaw/pull/8623) feat(memory): persist embedding identity and auto-migrate vectors on change
- [#8683](https://github.com/zeroclaw-labs/zeroclaw/pull/8683) feat(commands): add built-in command catalogue
- [#8685](https://github.com/zeroclaw-labs/zeroclaw/pull/8685) feat(runtime): add goal task storage foundation

### 🐛 New Issues
- [#8875](https://github.com/zeroclaw-labs/zeroclaw/issues/8875) bug(config): degraded-section warning can point to config migrate without showing parse error `bug` `config` `priority:p2` `risk:medium`
- [#8871](https://github.com/zeroclaw-labs/zeroclaw/issues/8871) [Task]: Handle third-party API 429 rate-limit responses explicitly
- [#8860](https://github.com/zeroclaw-labs/zeroclaw/issues/8860) [Feature]: Per-Agent In-Flight Prompt Counter on the Web Gateway Dashboard `enhancement`
- [#8858](https://github.com/zeroclaw-labs/zeroclaw/issues/8858) [Tracker]: Audit existing drift surfaces across codebase `enhancement` `docs` `dev` `priority:p2` `status:accepted` `status:no-stale` `type:tracker`
- [#8850](https://github.com/zeroclaw-labs/zeroclaw/issues/8850) Move optional channels & tools from compile-time feature flags to runtime plugins `enhancement` `channel` `runtime` `tool` `runtime:wasm` `domain:architecture` `priority:p2` `status:in-progress` `type:rfc` `status:accepted` `risk:high` `type:tracker` 💬4
- [#8847](https://github.com/zeroclaw-labs/zeroclaw/issues/8847) bug(ci): cargo test --doc fails with duplicated rustdoc theme flag `bug` `ci` `docs` `tests` `status:accepted` `priority:p3` `follow-up` `risk:low` `type:test`
- [#8844](https://github.com/zeroclaw-labs/zeroclaw/issues/8844) feat(obs): add process_message turn lifecycle for memory span nesting `enhancement` `agent` `observability` `runtime` `observability:otel` `status:accepted` `priority:p3` `follow-up` `risk:medium`
- [#8843](https://github.com/zeroclaw-labs/zeroclaw/issues/8843) chore(ci): keep remaining local gate divergence explicit after workspace alignment `enhancement` `ci` `tests` `scripts` `dev` `domain:ci` `status:accepted` `priority:p3` `follow-up` `risk:low` `type:ci`
- [#8837](https://github.com/zeroclaw-labs/zeroclaw/issues/8837) [Bug]: history trimming occurs silently with history pruning disabled `bug` `agent` `runtime` `priority:p1` `r:needs-repro` `status:blocked` `needs-author-action` `web` `risk:high` 💬1

### 🔒 Closed Issues
- [#8401](https://github.com/zeroclaw-labs/zeroclaw/issues/8401) [Feature]: TodoWrite Tracker for ZeroCode
- [#8792](https://github.com/zeroclaw-labs/zeroclaw/issues/8792) [Bug]: Left sidebar is missing a Skills navigation entry
- [#8334](https://github.com/zeroclaw-labs/zeroclaw/issues/8334) [Bug]: `skills install`/`list`/`remove` target data_dir, which no multi-agent runtime loads
- [#7948](https://github.com/zeroclaw-labs/zeroclaw/issues/7948) [Feature]: Persist embedding identity and auto-migrate vectors when the embedding model changes
- [#7690](https://github.com/zeroclaw-labs/zeroclaw/issues/7690) feat(provider): cover responses-wire option propagation
- [#8722](https://github.com/zeroclaw-labs/zeroclaw/issues/8722) [Bug]: High-entropy detector redacts legitimate generated filenames

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,508 · **Open issues:** 1,364 · **Last push:** <1h ago

### ✅ Merged PRs
- [#5818](https://github.com/nearai/ironclaw/pull/5818) refactor(composition): group automation cluster under automation/ (dissection n9)
- [#5846](https://github.com/nearai/ironclaw/pull/5846) Fix Slack extension removal cleanup
- [#5841](https://github.com/nearai/ironclaw/pull/5841) ci: revive the nightly deep tier + make Platform & Compat and Reborn E2E requirable
- [#5772](https://github.com/nearai/ironclaw/pull/5772) fix(reborn): localize Projects page copy
- [#5765](https://github.com/nearai/ironclaw/pull/5765) fix(reborn): allow renaming automations
- [#5840](https://github.com/nearai/ironclaw/pull/5840) fix(ci): run the full clippy matrix in the merge queue + fix libsql-only dead code
- [#5764](https://github.com/nearai/ironclaw/pull/5764) fix(reborn): persist chat timeline timestamps
- [#5769](https://github.com/nearai/ironclaw/pull/5769) feat(reborn): replace tool permission selects with custom menu
- [#5785](https://github.com/nearai/ironclaw/pull/5785) refactor(composition): group slack cluster under slack/ (dissection n8)
- [#5775](https://github.com/nearai/ironclaw/pull/5775) Clean up WebUI frontend TSX semantics

### 🐛 New Issues
- [#5859](https://github.com/nearai/ironclaw/issues/5859) Daily ironclaw failure taxonomy — 2026-07-09
- [#5856](https://github.com/nearai/ironclaw/issues/5856) Admin panel: API-token re-issue is missing, and user-detail still shows an orphaned "Create Token" button
- [#5838](https://github.com/nearai/ironclaw/issues/5838) Run fails with context compaction error despite successful tool execution `bug_bash_P2`
- [#5837](https://github.com/nearai/ironclaw/issues/5837) Routine run actions (Open run, Logs) are not clickable `bug_bash_P2`
- [#5836](https://github.com/nearai/ironclaw/issues/5836) Routine fails on every scheduled run with "No thread attached" `bug_bash_P2`
- [#5835](https://github.com/nearai/ironclaw/issues/5835) "Jump to latest" button appears unnecessarily and is positioned too high `bug_bash_P3`
- [#5834](https://github.com/nearai/ironclaw/issues/5834) Slack disconnect request is incorrectly rejected by agent `bug_bash_P2`
- [#5828](https://github.com/nearai/ironclaw/issues/5828) Remove stale references to legacy v1 coverage tests
- [#5827](https://github.com/nearai/ironclaw/issues/5827) Clean up orphaned v1 coverage trace fixtures

### 🔒 Closed Issues
- [#4108](https://github.com/nearai/ironclaw/issues/4108) Nightly E2E failed
- [#5768](https://github.com/nearai/ironclaw/issues/5768) Reborn Projects page has incomplete i18n coverage
- [#5419](https://github.com/nearai/ironclaw/issues/5419) [QA] No option to rename an automation
- [#3535](https://github.com/nearai/ironclaw/issues/3535) [QA] UI Timestamps are incorrect for conversations
- [#5770](https://github.com/nearai/ironclaw/issues/5770) Improve Reborn tool permission selects with a custom dropdown

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬6 · 1d ago
- 🟢 [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬3 · 1d ago
- 🟢 [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬2 · 1d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬9 · 1d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 2d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 2d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 2d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 9d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 9d ago
- ⚫ [#94780](https://github.com/openclaw/openclaw/issues/94780) [Feature]: Per-cron model selection independent of agent default — run cheap/free models on automation jobs while keeping main agent on premium LLM — 💬1 · 13d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[Research] Off Switch Dual Use](https://www.anthropic.com/research/off-switch-dual-use) _2026-07-08_

### OpenAI — 3 new
- [[Form] Gpt Live 1 In The Api](https://openai.com/form/gpt-live-1-in-the-api/) _2026-07-08_
- [[Index] K 12 Educators Practical Skills](https://openai.com/index/k-12-educators-practical-skills/) _2026-07-09_
- [[Index] Government National Security Partnerships](https://openai.com/index/government-national-security-partnerships/) _2026-07-08_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [China’s MiniMax Plans to Launch 2.7-Trillion Parameter Model](https://reddit.com/r/LocalLLaMA/comments/1uqnqsc/chinas_minimax_plans_to_launch_27trillion/) ↑551
- [The standard free ChatGPT LLM you get after a few messages HAS to be some sub-20b model with online search enabled, no other way to explain how awful it is](https://reddit.com/r/LocalLLaMA/comments/1uqz1d4/the_standard_free_chatgpt_llm_you_get_after_a_few/) ↑313
- [Can you trust local models to answer accurately?](https://reddit.com/r/LocalLLaMA/comments/1uqpxgp/can_you_trust_local_models_to_answer_accurately/) ↑313
- [AI has completely revolutionized how I play RPGs](https://reddit.com/r/LocalLLaMA/comments/1ur0egl/ai_has_completely_revolutionized_how_i_play_rpgs/) ↑173
- [What China Said at the UN’s First Global Dialogue on AI Governance](https://reddit.com/r/LocalLLaMA/comments/1ur4tz5/what_china_said_at_the_uns_first_global_dialogue/) ↑137

### r/singularity — top 5 new
- [GPT-5.6 Sol, along with Terra and Luna, will launch publicly this Thursday. We’re expanding preview access globally now.](https://reddit.com/r/singularity/comments/1uqhthi/gpt56_sol_along_with_terra_and_luna_will_launch/) ↑485
- [Grok 4.5 is live](https://reddit.com/r/singularity/comments/1ur06sj/grok_45_is_live/) ↑429
- [Decently reliable leaker says GPT-6 will be a larger pretrain and is slated to launch in a month, possibly end of this month](https://reddit.com/r/singularity/comments/1uqxs8g/decently_reliable_leaker_says_gpt6_will_be_a/) ↑336
- [Minimax plans to release a 2.7-trillion parameter model.](https://reddit.com/r/singularity/comments/1uqueil/minimax_plans_to_release_a_27trillion_parameter/) ↑311
- [Introducing Grok 4.5](https://reddit.com/r/singularity/comments/1ur0ye6/introducing_grok_45/) ↑260

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Give your agent a phone - open source non-sass edition](https://reddit.com/r/openclaw/comments/1uqie8e/give_your_agent_a_phone_open_source_nonsass/) ↑45
- [Introducing the OpenClaw Foundation](https://reddit.com/r/openclaw/comments/1ur9n49/introducing_the_openclaw_foundation/) ↑22
- [Grok 4.5 from xAI is live on OpenClaw](https://reddit.com/r/openclaw/comments/1ur77sa/grok_45_from_xai_is_live_on_openclaw/) ↑20
- [My Agent is a little... different from the others...](https://reddit.com/r/openclaw/comments/1ur4zjp/my_agent_is_a_little_different_from_the_others/) ↑14
- [Your agent wakes up 48 times a day. what is it actually pursuing? I built a plugin that turns the wake-ups into follow-through](https://reddit.com/r/openclaw/comments/1uqv6ge/your_agent_wakes_up_48_times_a_day_what_is_it/) ↑9

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
- [The lobsters now live forever. Introducing the OpenClaw Foundation](https://x.com/openclaw) ↑0 🔁0 · recent
- [Grok 4.5 from 
@SpaceXAI
 is live on OpenClaw.

No OpenClaw update required, just connect your X Premium or SuperGrok su](https://x.com/openclaw) ↑0 🔁0 · recent


### X — @steipete
- [This is how you wanna talk with your claw.](https://x.com/steipete) ↑0 🔁0 · recent
- [soooon](https://x.com/steipete) ↑0 🔁0 · recent
- [Gosh I can't wait for all of you to play with this.](https://x.com/steipete) ↑0 🔁0 · recent
- [working on the tech part. availability might take a bit.](https://x.com/steipete) ↑0 🔁0 · recent
- [tomorrow!](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
