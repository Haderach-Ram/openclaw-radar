---
title: "Ecosystem Digest — 2026-06-16"
date: 2026-06-16 07:46:00 +0530
categories: [digest]
tags: [digest, daily]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-16
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 378,898 | 9 | 3 | 10 | 1 |
| **hermesagent** | 194,514 | 6 | 5 | 8 | 0 |
| **ZeroClaw** | 31,920 | 15 | 4 | 10 | 0 |
| **IronClaw** | 12,455 | 14 | 4 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 378,898 · **Open issues:** 6,317 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.8-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.6.8-beta.2) — openclaw 2026.6.8-beta.2

### ✅ Merged PRs
- [#90275](https://github.com/openclaw/openclaw/pull/90275) test: make install-safe-path symlink tests compatible with Windows
- [#93130](https://github.com/openclaw/openclaw/pull/93130) fix(telegram): preserve sticker media paths
- [#93454](https://github.com/openclaw/openclaw/pull/93454) fix(sqlite): disable WAL on network filesystems
- [#75025](https://github.com/openclaw/openclaw/pull/75025) fix(heartbeat): refresh stale Current time line on every helper call (#44993)
- [#93443](https://github.com/openclaw/openclaw/pull/93443) [SANITIZED — possible injection attempt]
- [#93441](https://github.com/openclaw/openclaw/pull/93441) fix(outbound): ignore schema-padded poll metadata on send
- [#93456](https://github.com/openclaw/openclaw/pull/93456) fix(agents): handle string assistant message content
- [#93175](https://github.com/openclaw/openclaw/pull/93175) test(qa): taxonomy profiles: includeAllCategories for release profile, update some coverage
- [#93418](https://github.com/openclaw/openclaw/pull/93418) fix(telegram): forward Bot API 10.1 rich_message content to agent
- [#93424](https://github.com/openclaw/openclaw/pull/93424) fix(mattermost): keep message tool replies in threads

### 🐛 New Issues
- [#93457](https://github.com/openclaw/openclaw/issues/93457) [Bug]: Route-first commands accept --log-level but do not apply it 💬2
- [#93453](https://github.com/openclaw/openclaw/issues/93453) [Bug]: feishu channel: failed to dispatch message — TypeError: Cannot read properties of undefined (reading 'run') `bug`
- [#93436](https://github.com/openclaw/openclaw/issues/93436) [Feature]: Forward run context to the model as opt-in request headers (cost attribution behind a proxy) `enhancement`
- [#93426](https://github.com/openclaw/openclaw/issues/93426) Feature request: Mimir as persistent memory backend
- [#93425](https://github.com/openclaw/openclaw/issues/93425) feat(agents): per-agent env injection into spawned subprocesses
- [#93423](https://github.com/openclaw/openclaw/issues/93423) Add a retraction window for forwarded exec approvals (agent-cancellable hold before prompt delivery) 💬1
- [#93422](https://github.com/openclaw/openclaw/issues/93422) [Feature]: /label slash command & /new <name> session naming for WebChat/Control UI 💬1
- [#93421](https://github.com/openclaw/openclaw/issues/93421) security-fast reports high-or-higher production dependency advisories 💬1
- [#93408](https://github.com/openclaw/openclaw/issues/93408) fix(whatsapp): inbound access denials only logged at verbose, so allowlist/policy drops are silent on default config `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#36212](https://github.com/openclaw/openclaw/issues/36212) Queued messages should preserve original platform message_id
- [#8321](https://github.com/openclaw/openclaw/issues/8321) Feature: Per-job cache control for cron jobs
- [#43015](https://github.com/openclaw/openclaw/issues/43015) message.send schema overexposes poll/components/modal causing GPT auto-population breakages

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · <1h ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 194,514 · **Open issues:** 20,876 · **Last push:** <1h ago

### ✅ Merged PRs
- [#46951](https://github.com/NousResearch/hermes-agent/pull/46951) feat(desktop): hotkey to open a new session in a compact window
- [#46968](https://github.com/NousResearch/hermes-agent/pull/46968) fix(delegation): forward background flag so delegate_task(background=true) runs async
- [#46929](https://github.com/NousResearch/hermes-agent/pull/46929) fix(skills): guard recursive skill delete against tree-escape (port Kilo #11240)
- [#46244](https://github.com/NousResearch/hermes-agent/pull/46244) fix(desktop): keep file tree refresh clickable
- [#46909](https://github.com/NousResearch/hermes-agent/pull/46909) fix(desktop): coalesce interleaved reasoning/content stream parts
- [#31343](https://github.com/NousResearch/hermes-agent/pull/31343) feat(skills): add optional payments skills (Stripe Link, MPP, Projects)
- [#46885](https://github.com/NousResearch/hermes-agent/pull/46885) fix(mattermost): preserve thread-local delivery hygiene
- [#44431](https://github.com/NousResearch/hermes-agent/pull/44431) feat(honcho): gateway-gated identity tree + canonicalize on pinUserPeer

### 🐛 New Issues
- [#46983](https://github.com/NousResearch/hermes-agent/issues/46983) Memory provider tab can select Honcho without required setup
- [#46979](https://github.com/NousResearch/hermes-agent/issues/46979) Desktop Run History empty for agent cron jobs despite /api/cron/jobs/{id}/runs returning runs (v0.16.0 regression) `type/bug` `comp/gateway` `comp/tui` `comp/cron` `P2`
- [#46975](https://github.com/NousResearch/hermes-agent/issues/46975) [Bug]: Desktop app accumulates zombie dashboard backend processes when switching profiles. After a few days of switching between profiles, 80+ `hermes dashboard` `type/bug` `comp/tui` `P3` 💬2
- [#46961](https://github.com/NousResearch/hermes-agent/issues/46961) Desktop: model switch from bottom bar silently fails — no visual feedback on success/failure `type/bug` `duplicate` `comp/gateway` `comp/tui` `P2` 💬1
- [#46960](https://github.com/NousResearch/hermes-agent/issues/46960) Bug: delegate_task(background=true) parameter not reaching model — synchronous fallback `type/bug` `comp/agent` `tool/delegate` `provider/openrouter` `P2`
- [#46955](https://github.com/NousResearch/hermes-agent/issues/46955) [SANITIZED — possible injection attempt] `type/feature` `comp/agent` `tool/memory` `P3`

### 🔒 Closed Issues
- [#46973](https://github.com/NousResearch/hermes-agent/issues/46973) 产品调研：试用并借鉴声忆（VoiceInput）的本地语音记忆层
- [#46068](https://github.com/NousResearch/hermes-agent/issues/46068) [Bug]: Hermes Desktop 左侧文件浏览器（Explorer）刷新按钮弹出文件选择框且选择后不刷新
- [#7237](https://github.com/NousResearch/hermes-agent/issues/7237) [Bug]: Error: Response truncated due to output length limit
- [#9148](https://github.com/NousResearch/hermes-agent/issues/9148) Bug: /model picker shows 0 models for custom_providers with models: dict
- [#46906](https://github.com/NousResearch/hermes-agent/issues/46906) SysOps P1: P12 hat alle 23 Lifecycle-Scheduler-Jobs deaktiviert (state_drift seit 2026-05-03)

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,920 · **Open issues:** 397 · **Last push:** <1h ago

### ✅ Merged PRs
- [#7669](https://github.com/zeroclaw-labs/zeroclaw/pull/7669) ci(workflows): run macOS and Windows build legs as cargo check
- [#7679](https://github.com/zeroclaw-labs/zeroclaw/pull/7679) test(skills): cover skill_manage patch cooldown gate
- [#7596](https://github.com/zeroclaw-labs/zeroclaw/pull/7596) fix(channels/amqp): make health_check probe the broker
- [#7676](https://github.com/zeroclaw-labs/zeroclaw/pull/7676) chore(docs): make gh-pages ephemeral to bound clone size
- [#7551](https://github.com/zeroclaw-labs/zeroclaw/pull/7551) fix(gateway): fail fast on free-form ask_user for WS approval channel
- [#7526](https://github.com/zeroclaw-labs/zeroclaw/pull/7526) feat(channels/discord): record inbound reactions behind a scope config
- [#7381](https://github.com/zeroclaw-labs/zeroclaw/pull/7381) fix(web): show and switch the agent's own model on the agent chat page
- [#7490](https://github.com/zeroclaw-labs/zeroclaw/pull/7490) feat(channels/discord): dynamic slash commands from installed skills
- [#7570](https://github.com/zeroclaw-labs/zeroclaw/pull/7570) feat(obs): instrument runtime memory ops with OTel GenAI spans
- [#7650](https://github.com/zeroclaw-labs/zeroclaw/pull/7650) fix(quickstart): localize remaining CLI strings

### 🐛 New Issues
- [#7753](https://github.com/zeroclaw-labs/zeroclaw/issues/7753) Channel session persistence: pre-existing per-session ordering race across concurrent same-sender workers
- [#7749](https://github.com/zeroclaw-labs/zeroclaw/issues/7749) [SANITIZED — possible injection attempt]
- [#7746](https://github.com/zeroclaw-labs/zeroclaw/issues/7746) [Docs]: Document how to load and switch existing zerocode sessions `enhancement` `risk: low` `docs` `status:accepted` `priority:p3` `zerocode`
- [#7743](https://github.com/zeroclaw-labs/zeroclaw/issues/7743) [Feature]: support explicit target-profile authority for delegate handoffs `enhancement` `risk: high` `agent` `config` `runtime` `security` `tool` `tool:delegate` `priority:p2` `status:accepted`
- [#7742](https://github.com/zeroclaw-labs/zeroclaw/issues/7742) [SANITIZED — possible injection attempt] `bug` `risk: high` `agent` `runtime` `tool` `priority:p2`
- [#7741](https://github.com/zeroclaw-labs/zeroclaw/issues/7741) bug(runtime): skip response-cache hits for multimodal prompt markers `bug` `risk: high` `provider` `runtime` `priority:p2`
- [#7740](https://github.com/zeroclaw-labs/zeroclaw/issues/7740) bug(runtime): base missing-skill suggestions on effective tool set `bug` `risk: high` `runtime` `skills` `tool` `priority:p2`
- [#7739](https://github.com/zeroclaw-labs/zeroclaw/issues/7739) bug(channels/email): retry transient OAuth refresh failures `bug` `risk: medium` `channel` `provider` `priority:p2` `channel:email`
- [#7738](https://github.com/zeroclaw-labs/zeroclaw/issues/7738) bug(channels/email): use stable UID fallback when Message-ID is missing `bug` `risk: medium` `channel` `priority:p2` `channel:email`
- [#7737](https://github.com/zeroclaw-labs/zeroclaw/issues/7737) bug(channels): carry approval attribution without a global side channel `bug` `risk: high` `agent` `channel` `priority:p2`
- [#7736](https://github.com/zeroclaw-labs/zeroclaw/issues/7736) bug(runtime): forward trimming budgets through agent turn wrapper `bug` `risk: high` `agent` `runtime` `priority:p2`
- [#7735](https://github.com/zeroclaw-labs/zeroclaw/issues/7735) bug(runtime): handle poisoned activated-tool lock without panicking `bug` `risk: high` `runtime` `tool` `priority:p2`
- [#7733](https://github.com/zeroclaw-labs/zeroclaw/issues/7733) [Bug]: mcp_bundles is parsed and shown in Config but never enforced at runtime — per-agent MCP scoping is a silent no-op `bug` `risk: high` `config` `runtime` `security` `tool` `domain:security` `priority:p1` `tool:mcp` `status:accepted` 💬1
- [#7729](https://github.com/zeroclaw-labs/zeroclaw/issues/7729) test(runtime): cover RPC approval lifecycle cleanup `enhancement` `risk: high` `runtime` `security` `tests` `priority:p1` `status:accepted`
- [#7728](https://github.com/zeroclaw-labs/zeroclaw/issues/7728) bug(memory): prevent retrieval cache reuse across recall windows `bug` `risk: medium` `memory` `tests` `priority:p2` `status:accepted`

### 🔒 Closed Issues
- [#6683](https://github.com/zeroclaw-labs/zeroclaw/issues/6683) skill_manage `patch` ignores cooldown — unbounded patches per skill possible
- [#7542](https://github.com/zeroclaw-labs/zeroclaw/issues/7542) [Bug]: `ask_user` fails instantly with "Channel closed before receiving a response" in gateway web dashboard sessions
- [#1458](https://github.com/zeroclaw-labs/zeroclaw/issues/1458) [Feature]: Add support for local CA certificates for custom inference provider
- [#7005](https://github.com/zeroclaw-labs/zeroclaw/issues/7005) [Bug]: Quickstart CLI/runtime still has bare user-facing strings

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,455 · **Open issues:** 1,182 · **Last push:** <1h ago

### ✅ Merged PRs
- [#4947](https://github.com/nearai/ironclaw/pull/4947) ci(bench): validate /benchmark suite against benchmarks main, not a stale pin
- [#4871](https://github.com/nearai/ironclaw/pull/4871) feat(attachments): image attachment support for vision-capable models (#4644)
- [#4780](https://github.com/nearai/ironclaw/pull/4780) Steer routine delivery through outbound targets
- [#4559](https://github.com/nearai/ironclaw/pull/4559) feat(traces): agent-driven Trace Commons onboarding via invite link
- [#4936](https://github.com/nearai/ironclaw/pull/4936) ci(bench): let /benchmark select the framework (--framework ironclaw-reborn)
- [#4588](https://github.com/nearai/ironclaw/pull/4588) feat(reborn): observability seams — trajectory observer + LLM provider injection
- [#4827](https://github.com/nearai/ironclaw/pull/4827) fix(host-runtime): accept empty body/body_base64 in builtin.http
- [#4837](https://github.com/nearai/ironclaw/pull/4837) feat(agent-loop): gated final-answer nudge (reborn empty/canned turn endings)
- [#4900](https://github.com/nearai/ironclaw/pull/4900) fix(reborn): unify extension registry flow
- [#4888](https://github.com/nearai/ironclaw/pull/4888) fix(reborn): filter PRs from GitHub issue listings

### 🐛 New Issues
- [#4942](https://github.com/nearai/ironclaw/issues/4942) [Reborn WebUI] Tool calls failed won't appear until the re-fetch/reload 💬1
- [#4940](https://github.com/nearai/ironclaw/issues/4940) test(traces): cover the agent-invoked host-egress path for Trace Commons profile writes
- [#4935](https://github.com/nearai/ironclaw/issues/4935) Credentials are owner-scoped, not thread-scoped: OAuth account fork + cross-thread resolution (A+B+C)
- [#4931](https://github.com/nearai/ironclaw/issues/4931) test-support: teach MockAgentLoopDriverHost approval_resume scripting + run→resume payload store
- [#4926](https://github.com/nearai/ironclaw/issues/4926) [Reborn] Expanding capabilities stretches all cards in the same row `UX / Onboarding`
- [#4925](https://github.com/nearai/ironclaw/issues/4925)  [Reborn] NEAR AI MCP shows "SETUP NEEDED" and credential prompt despite being ready to use
- [#4923](https://github.com/nearai/ironclaw/issues/4923) [Reborn] Replace Logs/Docs icons with text labels to avoid misleading navigation cues `UX / Onboarding`
- [#4922](https://github.com/nearai/ironclaw/issues/4922) [Reborn] Extract local-dev capability composition out of runtime/composition hot paths `refactoring` `reborn` `module:M4-host-kernel`
- [#4921](https://github.com/nearai/ironclaw/issues/4921) [Reborn] Gmail extension run fails before producing a reply after successful authorization `bug`
- [#4918](https://github.com/nearai/ironclaw/issues/4918) [Reborn] Automations Findings 06/15/2026 - 06/21/2026
- [#4914](https://github.com/nearai/ironclaw/issues/4914) [Reborn] Gmail OAuth with no selected scopes returns raw malformed_callback error
- [#4913](https://github.com/nearai/ironclaw/issues/4913) [Reborn] Google Calendar authorization is not reused across conversations
- [#4908](https://github.com/nearai/ironclaw/issues/4908) [Reborn] Google Calendar extension shows "Activate" action after already being active `UX / Onboarding` 💬3
- [#4907](https://github.com/nearai/ironclaw/issues/4907) [Reborn] Run may fail after successful Google OAuth instead of resuming execution 💬2

### 🔒 Closed Issues
- [#4928](https://github.com/nearai/ironclaw/issues/4928) [Reborn] Notion OAuth redirects to localhost callback in Railway deployment
- [#4825](https://github.com/nearai/ironclaw/issues/4825) Reborn: persist "always allow" approvals across threads (drop thread_id from persistent approval scope)
- [#4917](https://github.com/nearai/ironclaw/issues/4917) Automations never run, and the panel's status numbers can be misleading
- [#4854](https://github.com/nearai/ironclaw/issues/4854) [Reborn] Simple GitHub Extension requests may require excessive approval prompts

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#93032](https://github.com/openclaw/openclaw/issues/93032) [Bug] v2026.6.6: Cron scheduler loads 0 jobs after upgrade — SQLite WAL not committed at first startup — 💬2 · 8h ago
- 🟢 [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 12h ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 21h ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬5 · 22h ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬1 · 22h ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 22h ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬1 · 22h ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 1d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 1d ago
- ⚫ [#92974](https://github.com/openclaw/openclaw/issues/92974) Bug: v2026.6.6 getAttributionHeaders() crashes on Bedrock models — baseUrl undefined (null-guard missing) — 💬1 · 1d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Stop using Ollama](https://reddit.com/r/LocalLLaMA/comments/1u6s6pm/stop_using_ollama/) ↑716
- [What's the lesson chat?](https://reddit.com/r/LocalLLaMA/comments/1u6azol/whats_the_lesson_chat/) ↑621
- [This is amazing. Token speed doubled + kv cache now need low vram - qwen 27b](https://reddit.com/r/LocalLLaMA/comments/1u6bca1/this_is_amazing_token_speed_doubled_kv_cache_now/) ↑379
- [Why there is a lack of new 100B-120B models?](https://reddit.com/r/LocalLLaMA/comments/1u6e0fo/why_there_is_a_lack_of_new_100b120b_models/) ↑314
- [Evalatro: an open benchmark where LLMs play the real Balatro](https://reddit.com/r/LocalLLaMA/comments/1u6qso1/evalatro_an_open_benchmark_where_llms_play_the/) ↑121

### r/singularity — top 5 new
- [Top cybersecurity leaders urge US government to unban Mythos.](https://reddit.com/r/singularity/comments/1u6hoim/top_cybersecurity_leaders_urge_us_government_to/) ↑592
- ["They screwed us": Personality clashes sent Anthropic's models offline](https://reddit.com/r/singularity/comments/1u6i9pu/they_screwed_us_personality_clashes_sent/) ↑325
- [Tensordyne announces Logarithmic AI compute chips. 17x more tokens per watt and 13x higher throughput than NVIDIA Blackwell.](https://reddit.com/r/singularity/comments/1u6u17i/tensordyne_announces_logarithmic_ai_compute_chips/) ↑280
- [Anthropic employees be like...](https://reddit.com/r/singularity/comments/1u6nl9f/anthropic_employees_be_like/) ↑250
- ["Elon Musk predicts that our current global economy will be comparable to cavemen throwing sticks into a fire given what the future holds and its current trajectory"](https://reddit.com/r/singularity/comments/1u6g1hr/elon_musk_predicts_that_our_current_global/) ↑130

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Am I the only one who can't find a killer use case for OpenClaw?](https://reddit.com/r/openclaw/comments/1u69jpj/am_i_the_only_one_who_cant_find_a_killer_use_case/) ↑40
- [Claude Code isn't gone quite yet!](https://reddit.com/r/openclaw/comments/1u6r7vn/claude_code_isnt_gone_quite_yet/) ↑11
- [What's the best "intelligence/agency per token/dollar" LLM for Open Claw?](https://reddit.com/r/openclaw/comments/1u6salg/whats_the_best_intelligenceagency_per_tokendollar/) ↑5
- [Is anyone using open claw on their primary system maybe as a secondary account on PC?](https://reddit.com/r/openclaw/comments/1u6ybu9/is_anyone_using_open_claw_on_their_primary_system/) ↑4
- [If you kept your OpenClaw agent on Claude, June 15 broke the workaround. Here's what still runs on your plan.](https://reddit.com/r/openclaw/comments/1u6r5yt/if_you_kept_your_openclaw_agent_on_claude_june_15/) ↑4

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
- [Wanted to buy a new Mac Studio for San Francisco.
We don’t even know how to make these anymore.](https://x.com/steipete) ↑0 🔁0 · recent
- [I have test automations that run through a large set of popular open models, many require careful harness engineering to](https://x.com/steipete) ↑0 🔁0 · recent
- [nope, limit is 96GB](https://x.com/steipete) ↑0 🔁0 · recent
- [I use it exactly to test local models.](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*