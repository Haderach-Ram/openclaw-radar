---
layout: post
title: "Ecosystem Digest — 2026-06-11"
date: 2026-06-11 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-11
*Generated 07:45 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 378,030 | 15 | 3 | 10 | 1 |
| **hermesagent** | 190,044 | 9 | 0 | 4 | 0 |
| **ZeroClaw** | 31,865 | 8 | 5 | 10 | 0 |
| **IronClaw** | 12,439 | 15 | 6 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 378,030 · **Open issues:** 7,990 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.6-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.6.6-beta.1) — OpenClaw 2026.6.6-beta.1

### ✅ Merged PRs
- [#91296](https://github.com/openclaw/openclaw/pull/91296) fix: hand off supervised git updates
- [#91950](https://github.com/openclaw/openclaw/pull/91950) fix(web_fetch): sanitize URL whitespace from LLM tool call arguments (fixes #91651)
- [#92051](https://github.com/openclaw/openclaw/pull/92051) fix(fal): parse raw completed queue results
- [#90912](https://github.com/openclaw/openclaw/pull/90912) fix(agents): honor configured CLI resume timeouts
- [#91962](https://github.com/openclaw/openclaw/pull/91962) fix(agent): dampen Discord stale thread replies
- [#92055](https://github.com/openclaw/openclaw/pull/92055) fix(media): resolve state-relative inbound attachments
- [#92030](https://github.com/openclaw/openclaw/pull/92030) fix(cron): structural top-of-hour match in stagger heuristic
- [#91802](https://github.com/openclaw/openclaw/pull/91802) fix(diagnostics): release wedged session lane when stuck-session recovery aborts a run with queued session work
- [#91897](https://github.com/openclaw/openclaw/pull/91897) fix(memory): self-heal missing index identity by initializing provider during sync
- [#92056](https://github.com/openclaw/openclaw/pull/92056) fix(exec): honor state dir approvals

### 🐛 New Issues
- [#92069](https://github.com/openclaw/openclaw/issues/92069) bug(cli): usage errors exit 0 💬1
- [#92068](https://github.com/openclaw/openclaw/issues/92068) bug(telegram): ingress-spool writer never writes after 2026.5.28 → 2026.6.1 in-place update 💬1
- [#92067](https://github.com/openclaw/openclaw/issues/92067) fix(telegram): honor ingest config before the unaddressed-group-media skip 💬1
- [#92064](https://github.com/openclaw/openclaw/issues/92064) [Feature]: Connecting OpenClaw to live Rstudio session/Jupyter kernel `enhancement`
- [#92062](https://github.com/openclaw/openclaw/issues/92062) [Bug]: WebChat sessions_history misses prior history split into reset/archive session files for same visible dashboard conversation `bug` `regression` 💬1
- [#92061](https://github.com/openclaw/openclaw/issues/92061) memory-core: CJK text FTS5 search returns textScore=0 with trigram tokenizer `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `impact:session-state` `issue-rating: 🦪 silver shellfish` 💬1
- [#92060](https://github.com/openclaw/openclaw/issues/92060) Bug: Inter-session Echo Loop in webchat channel — agent text output auto-routed to other agents 💬1
- [#92058](https://github.com/openclaw/openclaw/issues/92058) failureAlert (after=1) never fires on 2026.6.5 — every errored run stuck at delivery_status 'not-requested' 💬1
- [#92057](https://github.com/openclaw/openclaw/issues/92057) Gateway becomes slow or times out under multi-session / multi-agent load 💬1
- [#92054](https://github.com/openclaw/openclaw/issues/92054) [Bug]: Windows 11 - Claude CLI provider fails with spawn claude ENOENT `bug` `regression` 💬1
- [#92050](https://github.com/openclaw/openclaw/issues/92050) memory-core: short-term-recall.json grows without rotation → permanent dreaming promotion deadlock once it crosses the 16MiB read limit 💬1
- [#92048](https://github.com/openclaw/openclaw/issues/92048) Telegram outbound leaked internal continuation text after tool-call hiccup `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-security-review` `clawsweeper:needs-info` `impact:security` `impact:message-loss` `issue-rating: 🦐 gold shrimp` 💬1
- [#92044](https://github.com/openclaw/openclaw/issues/92044) [Bug]: `openclaw workboard dispatch` fails with `missing scope: operator.admin` though the method is registered operator.write 💬1
- [#92043](https://github.com/openclaw/openclaw/issues/92043) Bug: 180s compaction timeout is a single wall clock over the whole chunk pipeline with no partial-progress reuse, so a legitimately-long compaction fails identically every turn  💬3
- [#92042](https://github.com/openclaw/openclaw/issues/92042) [Bug]: Single cron job exhibits recurring failures across multiple distinct error classes (overload, timeout, context-overflow, session-takeover) over a 6-week window `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `impact:session-state` `impact:auth-provider` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1

### 🔒 Closed Issues
- [#91651](https://github.com/openclaw/openclaw/issues/91651) bug(tools): web_fetch fails with 'Invalid URL' when LLM generates a space in the protocol scheme
- [#91700](https://github.com/openclaw/openclaw/issues/91700) Stuck-session recovery aborts the embedded run but never releases the session lane → group agent stays silent ~15 min after the run is dead
- [#66946](https://github.com/openclaw/openclaw/issues/66946) [Bug]: **Control UI路径重复导致404错误，聊天功能无法使用**

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 14h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 190,044 · **Open issues:** 19,886 · **Last push:** <1h ago

### ✅ Merged PRs
- [#42351](https://github.com/NousResearch/hermes-agent/pull/42351) desktop: registry-driven slash commands + first-class /resume & /handoff
- [#43570](https://github.com/NousResearch/hermes-agent/pull/43570) fix(streaming): stop socket read timeout from preempting stale-stream detector
- [#43858](https://github.com/NousResearch/hermes-agent/pull/43858) fix(web): profiles page modal
- [#43761](https://github.com/NousResearch/hermes-agent/pull/43761) fix(telegram): stop cutting long streamed responses (lost tails, deleted heads, raw markdown)

### 🐛 New Issues
- [#43904](https://github.com/NousResearch/hermes-agent/issues/43904) [Desktop v0.16.0] Remote backend "ready" but UI stuck on red error dialog, loops in reset/repair cycle
- [#43900](https://github.com/NousResearch/hermes-agent/issues/43900) [Bug] Ollama local models silently capped at 4096-token context — causes finish_reason=length and garbled retry responses
- [#43899](https://github.com/NousResearch/hermes-agent/issues/43899) [Bug]: Cron jobs fail with 'Model parameter is required' when model is not explicitly set on the job 💬1
- [#43897](https://github.com/NousResearch/hermes-agent/issues/43897) fix(feishu): Schema 2.0 — remove deprecated action tag wrapper for buttons
- [#43894](https://github.com/NousResearch/hermes-agent/issues/43894) [Feature]: Move the Honcho API key and Base URL settings off Tools and onto Memory
- [#43893](https://github.com/NousResearch/hermes-agent/issues/43893) Desktop: intermediate assistant text lost when messages have both content and tool_calls
- [#43891](https://github.com/NousResearch/hermes-agent/issues/43891) feat: Make Hindsight prefetch join timeout configurable
- [#43883](https://github.com/NousResearch/hermes-agent/issues/43883) [Bug]: web.backend=anysearch silently ignored — not in _get_backend() whitelist `type/bug` `comp/tools` `tool/web` `P3`
- [#43880](https://github.com/NousResearch/hermes-agent/issues/43880) [Setup]: using Claude Sub `question` `provider/anthropic` `P3`

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,865 · **Open issues:** 470 · **Last push:** 1h ago

### ✅ Merged PRs
- [#7446](https://github.com/zeroclaw-labs/zeroclaw/pull/7446) fix(multimodal): make image_info images reach vision models end-to-end
- [#7444](https://github.com/zeroclaw-labs/zeroclaw/pull/7444) fix(zerocode): dashboard distinguishes loading, error, and live/persisted states
- [#7365](https://github.com/zeroclaw-labs/zeroclaw/pull/7365) docs(book): rework the book and derive provider/config surfaces from source
- [#7466](https://github.com/zeroclaw-labs/zeroclaw/pull/7466) fix(ci): restore master compile after merge batch
- [#7352](https://github.com/zeroclaw-labs/zeroclaw/pull/7352) fix(web): log cron settings failures
- [#7353](https://github.com/zeroclaw-labs/zeroclaw/pull/7353) perf(runtime): avoid final CLI output clones
- [#7354](https://github.com/zeroclaw-labs/zeroclaw/pull/7354) feat(tools): add http_request auth secrets
- [#7375](https://github.com/zeroclaw-labs/zeroclaw/pull/7375) fix(docs): guard mdbook catalogs against literal corruption
- [#7234](https://github.com/zeroclaw-labs/zeroclaw/pull/7234) feat(memory): migrate gateway and channel consolidation to MemoryStrategy
- [#7363](https://github.com/zeroclaw-labs/zeroclaw/pull/7363) feat(channels/hardware/demo): add host Telegram ESP32 simulator harness

### 🐛 New Issues
- [#7470](https://github.com/zeroclaw-labs/zeroclaw/issues/7470) [Bug]: delegate agentic mode rejects empty risk_profile.allowed_tools and same-profile gating blocks stricter delegated targets
- [#7469](https://github.com/zeroclaw-labs/zeroclaw/issues/7469) [Bug]: Default using "vi" but container does not include it `bug`
- [#7468](https://github.com/zeroclaw-labs/zeroclaw/issues/7468) [Feature]: Allow aliases to be renamed `enhancement` `zerocode` 💬1
- [#7467](https://github.com/zeroclaw-labs/zeroclaw/issues/7467) [Feature]: More flexibility in edit strings `enhancement` `zerocode` 💬1
- [#7462](https://github.com/zeroclaw-labs/zeroclaw/issues/7462) [Bug]: 74 test failures on Windows — Unix-only test commands, path semantics, console encoding
- [#7461](https://github.com/zeroclaw-labs/zeroclaw/issues/7461) [Feature]: Run the test suite on Windows and macOS in CI, not just Linux
- [#7452](https://github.com/zeroclaw-labs/zeroclaw/issues/7452) [Bug]: AMQP channel cannot compile on Windows — tokio-reactor-trait's Reactor impl is Unix-only `bug` `ci` `risk: high` `dependencies` `channel` `priority:p2`
- [#7439](https://github.com/zeroclaw-labs/zeroclaw/issues/7439) [Bug]: Custom provider results in Doctor error model_provider "custom.<alias>" is invalid `bug` `risk: high` `config` `doctor` `provider` `runtime` `priority:p1` `status:in-progress`

### 🔒 Closed Issues
- [#7376](https://github.com/zeroclaw-labs/zeroclaw/issues/7376) [Bug]: zerocode Dashboard hides unavailable/error states and labels history as active sessions
- [#6222](https://github.com/zeroclaw-labs/zeroclaw/issues/6222) [Bug]: Config reference docs missing in github
- [#5269](https://github.com/zeroclaw-labs/zeroclaw/issues/5269) [Bug]: Improve Installation Documentation & Methods
- [#2973](https://github.com/zeroclaw-labs/zeroclaw/issues/2973) [Feature]: Optimize the print performance of loop run return results
- [#5810](https://github.com/zeroclaw-labs/zeroclaw/issues/5810) [Bug]: `security.otp.gated_actions` silently accepts unknown action names

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,439 · **Open issues:** 1,143 · **Last push:** <1h ago

### ✅ Merged PRs
- [#4745](https://github.com/nearai/ironclaw/pull/4745) refactor(reborn): back automations panel facade with TriggerRepository (drop capability dispatch from panel reads)
- [#4743](https://github.com/nearai/ironclaw/pull/4743) [codex] Fix NEAR context overflow classification
- [#4742](https://github.com/nearai/ironclaw/pull/4742) [codex] Fix manual token runtime credential selection
- [#4652](https://github.com/nearai/ironclaw/pull/4652) Document Reborn serve/WebUI testing flow + add run-reborn-webui.sh launcher
- [#4730](https://github.com/nearai/ironclaw/pull/4730) Personal triggered-event delivery: Slack DM end to end
- [#4739](https://github.com/nearai/ironclaw/pull/4739) Enable Slack for QA Railway Reborn
- [#4717](https://github.com/nearai/ironclaw/pull/4717) Restore WebUI v2 always approval affordance
- [#4608](https://github.com/nearai/ironclaw/pull/4608) [codex] Add Reborn operator observability route shells
- [#4716](https://github.com/nearai/ironclaw/pull/4716) [codex] Allow Reborn Postgres cleartext opt-in
- [#4602](https://github.com/nearai/ironclaw/pull/4602) [codex] Add Reborn unsupported config diagnostics

### 🐛 New Issues
- [#4747](https://github.com/nearai/ironclaw/issues/4747) agent_loop: unify pending gate-resume records and move replay payload out of checkpointed state
- [#4741](https://github.com/nearai/ironclaw/issues/4741) Reborn local-dev secret store: opaque "Invalid master key" on corrupt/low-entropy key file
- [#4740](https://github.com/nearai/ironclaw/issues/4740) slack tool: advertised parameters_schema only declares 'action' (other params untyped → models guess wrong, can't be coerced)
- [#4733](https://github.com/nearai/ironclaw/issues/4733) [Reborn] Clicking response links navigates away from the active conversation `ux`
- [#4729](https://github.com/nearai/ironclaw/issues/4729) [Reborn] NEAR AI login broken for local/desktop builds: private.near.ai rejects all non-private.near.ai frontend_callback values
- [#4725](https://github.com/nearai/ironclaw/issues/4725) [Reborn] Composer remains interactive while in Working state
- [#4724](https://github.com/nearai/ironclaw/issues/4724) [Reborn] Unsent draft is lost when leaving New Conversation
- [#4723](https://github.com/nearai/ironclaw/issues/4723) [Reborn] New conversation composer hover state only highlights the top border
- [#4722](https://github.com/nearai/ironclaw/issues/4722) [Reborn] Conversation messages do not display user or assistant identity
- [#4721](https://github.com/nearai/ironclaw/issues/4721) [Reborn] Sidebar "PINNED" section represents the active conversation instead of pinned conversations
- [#4720](https://github.com/nearai/ironclaw/issues/4720) [Reborn] Attachment warning persists across conversations and cannot be cleared
- [#4719](https://github.com/nearai/ironclaw/issues/4719) [Reborn] Conversation content area flickers when returning to a chat
- [#4714](https://github.com/nearai/ironclaw/issues/4714) [Reborn] Return failed and cancelled states from OpenAI Responses retrieve `suggested_P2` `reborn`
- [#4711](https://github.com/nearai/ironclaw/issues/4711) [Reborn] ChatGPT subscription device code flow is confusing in Web UI `enhancement`
- [#4708](https://github.com/nearai/ironclaw/issues/4708) Generated code blocks lack syntax highlighting in WebUI conversation page

### 🔒 Closed Issues
- [#4734](https://github.com/nearai/ironclaw/issues/4734) Reborn WebUI agent avatar shows IC instead of an IronClaw icon
- [#4594](https://github.com/nearai/ironclaw/issues/4594) [Reborn] Unsupported config diagnostics for not-yet-wired or ignored settings
- [#4673](https://github.com/nearai/ironclaw/issues/4673) [Reborn] NEAR AI provider configuration cannot be saved after successful Test connection
- [#3615](https://github.com/nearai/ironclaw/issues/3615) [Reborn WebUI Beta] Audit WebUI auth and security parity for Reborn routes
- [#4604](https://github.com/nearai/ironclaw/issues/4604) Reborn WebUI v2 lacks a browser-driven full-stack E2E
- [#4611](https://github.com/nearai/ironclaw/issues/4611) [Reborn WebUI Beta] Audit & test security headers + sanitized errors for WebChat v2

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 5d ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 6d ago
- ⚫ [#88967](https://github.com/openclaw/openclaw/issues/88967) Telegram: allowBots support for group chats (bot-authored messages not ingested into session) — 💬1 · 6d ago
- ⚫ [#88517](https://github.com/openclaw/openclaw/issues/88517) [SANITIZED — possible injection attempt] — 💬3 · 7d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 8d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 8d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬5 · 10d ago
- ⚫ [#86371](https://github.com/openclaw/openclaw/issues/86371) Bug: message tool filePath fails with LocalMediaAccessError in retry flows when agentId is not propagated — 💬1 · 13d ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 16d ago
- ⚫ [#79917](https://github.com/openclaw/openclaw/issues/79917) Haderach (OpenClaw bot) permanently auto-banned from OpenClaw Discord — ban reason: "Bot" — 💬3 · 29d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 6 new
- [Economic Index](https://www.anthropic.com/economic-index) _2026-06-11_
- [Institute](https://www.anthropic.com/institute) _2026-06-11_
- [[Institute] Recursive Self Improvement](https://www.anthropic.com/institute/recursive-self-improvement) _2026-06-11_
- [Policy](https://www.anthropic.com/policy) _2026-06-10_
- [Policy On The Ai Exponential](https://www.anthropic.com/policy-on-the-ai-exponential) _2026-06-10_
- [[Responsible-Scaling-Policy] Roadmap](https://www.anthropic.com/responsible-scaling-policy/roadmap) _2026-06-11_

### OpenAI — 7 new
- [[News] Applied Ai](https://openai.com/news/applied-ai/) _2026-06-11_
- [[Index] Creating New Simulations Black Holes](https://openai.com/index/creating-new-simulations-black-holes/) _2026-06-10_
- [[Index] Lseg](https://openai.com/index/lseg/) _2026-06-10_
- [[Index] Cycling Across Antarctica](https://openai.com/index/cycling-across-antarctica/) _2026-06-10_
- [[Index] Using Codex To Simulate Black Holes](https://openai.com/index/using-codex-to-simulate-black-holes/) _2026-06-10_
- [[Index] Openai On Oracle Cloud](https://openai.com/index/openai-on-oracle-cloud/) _2026-06-11_
- [[Index] Prc Linked Influence Operations Ai Debates](https://openai.com/index/prc-linked-influence-operations-ai-debates/) _2026-06-10_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Stop asking what model to run. There are literally only two.](https://reddit.com/r/LocalLLaMA/comments/1tu82wi/stop_asking_what_model_to_run_there_are_literally/) ↑2805
- [Heretic has been served a legal notice by Meta, Inc.](https://reddit.com/r/LocalLLaMA/comments/1tjmvx6/heretic_has_been_served_a_legal_notice_by_meta_inc/) ↑2347
- [PSA](https://reddit.com/r/LocalLLaMA/comments/1tr7hzw/psa/) ↑2090
- [Me visiting this sub](https://reddit.com/r/LocalLLaMA/comments/1tw8eul/me_visiting_this_sub/) ↑2058
- [I got a real transformer language model running locally on a stock Game Boy Color!](https://reddit.com/r/LocalLLaMA/comments/1tbi2n3/i_got_a_real_transformer_language_model_running/) ↑1552

### r/singularity — top 5 new
- [Token maxxing](https://reddit.com/r/singularity/comments/1tyketd/token_maxxing/) ↑2376
- [The New World Order](https://reddit.com/r/singularity/comments/1u0z3p4/the_new_world_order/) ↑2339
- [we're never getting a singularity bro🤦‍♂️](https://reddit.com/r/singularity/comments/1tyxreg/were_never_getting_a_singularity_bro/) ↑1857
- [Dario Amodei says he started Anthropic because Altman is liar not because of safety reasons.](https://reddit.com/r/singularity/comments/1u25uy6/dario_amodei_says_he_started_anthropic_because/) ↑1329
- [AGI 2030](https://reddit.com/r/singularity/comments/1u2dg2f/agi_2030/) ↑838

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
