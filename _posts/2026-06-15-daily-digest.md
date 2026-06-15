---
layout: post
title: "Ecosystem Digest — 2026-06-15"
date: 2026-06-15 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-15
*Generated 12:44 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 378,749 | 5 | 9 | 6 | 1 |
| **hermesagent** | 193,812 | 8 | 2 | 7 | 0 |
| **ZeroClaw** | 31,908 | 1 | 5 | 10 | 0 |
| **IronClaw** | 12,453 | 15 | 7 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 378,749 · **Open issues:** 6,510 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.8-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.6.8-beta.1) — openclaw 2026.6.8-beta.1

### ✅ Merged PRs
- [#93073](https://github.com/openclaw/openclaw/pull/93073) fix(agents): retry empty post-tool final turns
- [#93130](https://github.com/openclaw/openclaw/pull/93130) fix(telegram): preserve sticker media paths
- [#93164](https://github.com/openclaw/openclaw/pull/93164) fix(telegram): preserve rich markdown line breaks
- [#93119](https://github.com/openclaw/openclaw/pull/93119) fix: accept mixed source/dist bundled roots
- [#93153](https://github.com/openclaw/openclaw/pull/93153) simplify QA evidence profile and mappings/coverage shape
- [#92738](https://github.com/openclaw/openclaw/pull/92738) Forward suppressed-source progress for message-tool channel replies

### 🐛 New Issues
- [#93199](https://github.com/openclaw/openclaw/issues/93199) memory_search fails in non-default agent session while CLI --agent search works; current session resolves inconsistently `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:session-state` `issue-rating: 🐚 platinum hermit` 💬1
- [#93197](https://github.com/openclaw/openclaw/issues/93197) [Bug]: Feishu message.edit fails with 'parse card json err' when presentation has empty blocks `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:message-loss` `issue-rating: 🦐 gold shrimp` 💬1
- [#93193](https://github.com/openclaw/openclaw/issues/93193) fix(agents): prompt-released session control entries can trigger EmbeddedAttemptSessionTakeoverError `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#93173](https://github.com/openclaw/openclaw/issues/93173) Skill Workshop apply popup carries no proposal details + fixed 60s TTL `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:security` `issue-rating: 🦞 diamond lobster` 💬1
- [#93169](https://github.com/openclaw/openclaw/issues/93169) [Show and tell] Giraffe Agent — an OpenClaw-compatible skill layer for industrial procurement and order execution `P3` `impact:other` 💬2

### 🔒 Closed Issues
- [#93191](https://github.com/openclaw/openclaw/issues/93191) memory-core dreaming: PR #87206 is a workaround, not an architectural fix for the session-archive race in #87182
- [#83748](https://github.com/openclaw/openclaw/issues/83748) Telegram inbound stickers are not hydrated as agent-readable media
- [#86195](https://github.com/openclaw/openclaw/issues/86195) [Telegram] nativeToolProgress/sendMessageDraft blocks user input on Android; document interactive-control tradeoff
- [#93165](https://github.com/openclaw/openclaw/issues/93165) @openclaw/bluebubbles 2026.5.7 breaks all inbound on 2026.6.6 core (processMessage TypeError reading 'run')
- [#91269](https://github.com/openclaw/openclaw/issues/91269) [Feature]: 请增加一个功能从.openclaw > agents > main > sessions >里的sessions文件里提取会话内容并整理做日期记忆文件的能力
- [#88728](https://github.com/openclaw/openclaw/issues/88728) [Bug]:Discord WebSocket closes (1006) simultaneously with Telegram getUpdates stalls — isolation not working in         2026.5.28
- [#88383](https://github.com/openclaw/openclaw/issues/88383) Session file lock timeout when multiple subagent completion events arrive concurrently
- [#88369](https://github.com/openclaw/openclaw/issues/88369) [Bug]: isolated cron can still self-conflict on a dedicated cron agent with EmbeddedAttemptSessionTakeoverError
- [#88335](https://github.com/openclaw/openclaw/issues/88335) [feishu] Streaming card sends incremental diff instead of full text to CardKit API

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬109 · 3d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 193,812 · **Open issues:** 20,703 · **Last push:** <1h ago

### ✅ Merged PRs
- [#46483](https://github.com/NousResearch/hermes-agent/pull/46483) fix(s6): reserved default gateway must not follow sticky active_profile
- [#46487](https://github.com/NousResearch/hermes-agent/pull/46487) fix(dashboard): pin machine-dashboard reroute to the machine root, not $HOME/.hermes
- [#46289](https://github.com/NousResearch/hermes-agent/pull/46289) fix(s6): clear stale log lock before startup
- [#46292](https://github.com/NousResearch/hermes-agent/pull/46292) fix(s6): persist profile gateway desired state
- [#46291](https://github.com/NousResearch/hermes-agent/pull/46291) fix(s6): make profile gateway log parent writable
- [#45120](https://github.com/NousResearch/hermes-agent/pull/45120) fix(windows): kill hermes before recreating venv to release _bcrypt.pyd lock
- [#44159](https://github.com/NousResearch/hermes-agent/pull/44159) fix(desktop): inset hover-reveal trigger past the adjacent scrollbar

### 🐛 New Issues
- [#46517](https://github.com/NousResearch/hermes-agent/issues/46517) [Bug]: TUI (Desktop App) shows "Running Code..." indicator indefinitely after session has completed 💬1
- [#46516](https://github.com/NousResearch/hermes-agent/issues/46516) [Bug]: [OpenAI API] HTTP 400 for gpt-4.1 and gpt-4o-mini on Hermes 0.16.0 (Windows) while direct API calls work
- [#46515](https://github.com/NousResearch/hermes-agent/issues/46515) Telegram: sendRichMessageDraft works but final message falls back to MarkdownV2 (expect_edits kills rich path)
- [#46512](https://github.com/NousResearch/hermes-agent/issues/46512) bug(tui-gateway): `reload.mcp` (a.k.a. `/reload-mcp`) leaves all stdio MCP servers in CancelledError state
- [#46511](https://github.com/NousResearch/hermes-agent/issues/46511) Cron jobs don't fallback when credential pool is exhausted (OAuth providers)
- [#46510](https://github.com/NousResearch/hermes-agent/issues/46510) [Bug]: 为什么state.db中sessions表中的user_id是一些乱七八糟的数据，而且格式不统一
- [#46506](https://github.com/NousResearch/hermes-agent/issues/46506) [SANITIZED — possible injection attempt]
- [#46490](https://github.com/NousResearch/hermes-agent/issues/46490) [Feature]: Allow matrix users to use clarify like they do for approvals - with reactions

### 🔒 Closed Issues
- [#45258](https://github.com/NousResearch/hermes-agent/issues/45258) [Bug]: gateway per-profile log/run leaves logs/gateways/ parent root-owned → s6-log fatal mkdir loop for profiles added after first boot
- [#45865](https://github.com/NousResearch/hermes-agent/issues/45865) [Feature]: Add ability to remove provider accounts

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 31,908 · **Open issues:** 387 · **Last push:** <1h ago

### ✅ Merged PRs
- [#7634](https://github.com/zeroclaw-labs/zeroclaw/pull/7634) [SANITIZED — possible injection attempt]
- [#7419](https://github.com/zeroclaw-labs/zeroclaw/pull/7419) fix(providers): fail loudly for unusable fallback providers
- [#7208](https://github.com/zeroclaw-labs/zeroclaw/pull/7208) fix(cron): correct weekday range normalization for Sunday-alias endpoints
- [#7207](https://github.com/zeroclaw-labs/zeroclaw/pull/7207) fix(gateway): point paircode recovery hint at loopback for non-loopback binds
- [#7556](https://github.com/zeroclaw-labs/zeroclaw/pull/7556) feat(config): declarative section grouping for the Config menu
- [#6667](https://github.com/zeroclaw-labs/zeroclaw/pull/6667) feat(skills): background review fork + skill_manage tool (agentskills.io SKILL.md)
- [#7571](https://github.com/zeroclaw-labs/zeroclaw/pull/7571) docs(maintainers): define stale exemption routing evidence
- [#7594](https://github.com/zeroclaw-labs/zeroclaw/pull/7594) feat(config): type-driven alias-ref pickers and self-declaring config enums
- [#7566](https://github.com/zeroclaw-labs/zeroclaw/pull/7566) fix(config): redact bearer tokens in file-transfer header maps
- [#7590](https://github.com/zeroclaw-labs/zeroclaw/pull/7590) feat(agents): per-agent delegate roster with cross-profile reach

### 🐛 New Issues
- [#7623](https://github.com/zeroclaw-labs/zeroclaw/issues/7623) [Bug]: delegate to a Codex/OAuth (`requires_openai_auth`) sub-agent still fails after #7266 — `resolve_brain` forwards the coordinator's API key `bug` `risk: high` `config` `provider` `runtime` `security` `tool` `tool:delegate` `priority:p1` `status:in-progress`

### 🔒 Closed Issues
- [#6561](https://github.com/zeroclaw-labs/zeroclaw/issues/6561) fix(gateway): non-loopback --host recovery hint advertises admin URL that admin guard rejects
- [#7452](https://github.com/zeroclaw-labs/zeroclaw/issues/7452) [Bug]: AMQP channel cannot compile on Windows — tokio-reactor-trait's Reactor impl is Unix-only
- [#6989](https://github.com/zeroclaw-labs/zeroclaw/issues/6989) config: extend #[secret] (or add a header-token field) so headers maps redact bearer tokens
- [#7514](https://github.com/zeroclaw-labs/zeroclaw/issues/7514) [Feature]: change `delegate` tool semantics to allow subagents with different risk profiles
- [#5528](https://github.com/zeroclaw-labs/zeroclaw/issues/5528) [Bug]: Improper logic of email channel config

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,453 · **Open issues:** 1,191 · **Last push:** <1h ago

### ✅ Merged PRs
- [#4899](https://github.com/nearai/ironclaw/pull/4899) fix(agent-loop): surface resume-origin capability failures instead of dying as scope_mismatch
- [#4840](https://github.com/nearai/ironclaw/pull/4840) fix: surface missing-credential auth gate before the approval gate
- [#4895](https://github.com/nearai/ironclaw/pull/4895) fix(runtime-context): key comms preferences by run owner + cover JoinError gaps
- [#4738](https://github.com/nearai/ironclaw/pull/4738) feat(reborn): attachment web UX on the WebChat v2 SPA (#4644)
- [#4836](https://github.com/nearai/ironclaw/pull/4836) feat(runtime-context): surface connected channels, delivery state, and run origin
- [#4873](https://github.com/nearai/ironclaw/pull/4873) test(slack): re-home approval→auth→final-reply delivery e2e (#4847)
- [#4844](https://github.com/nearai/ironclaw/pull/4844) fix(slack): filter delivered gate routes by raw gate string (auth vs approval)
- [#3680](https://github.com/nearai/ironclaw/pull/3680) docs: document WeChat and WeCom channels
- [#4805](https://github.com/nearai/ironclaw/pull/4805) fix(reborn): repair oversized provider tool arguments
- [#4866](https://github.com/nearai/ironclaw/pull/4866) ci(review): keep CodeRabbit summaries out of PR descriptions

### 🐛 New Issues
- [#4904](https://github.com/nearai/ironclaw/issues/4904) [Reborn] Google Calendar installation flow may dispatch duplicate extension_install actions
- [#4901](https://github.com/nearai/ironclaw/issues/4901) Thread surface_kinds through extension wire types instead of overloading `kind`
- [#4898](https://github.com/nearai/ironclaw/issues/4898) Live verify WebUI approval grants are reused in Slack DM `e2e-coverage` `live-test` `reborn`
- [#4897](https://github.com/nearai/ironclaw/issues/4897) Cache connected-channel surface projection to avoid per-turn ExtensionList scan
- [#4896](https://github.com/nearai/ironclaw/issues/4896) host-runtime: collapse the credential-presence double-read between pre-flight and dispatch obligation
- [#4892](https://github.com/nearai/ironclaw/issues/4892) WebUI v2 Logs link is visible to non-operators and swallows 403 as an empty log stream
- [#4890](https://github.com/nearai/ironclaw/issues/4890) [Reborn] Extension setup flow is fragmented between Registry, Installed, Configure, and Chat auth
- [#4887](https://github.com/nearai/ironclaw/issues/4887) [Reborn] Provider-backed MCP tool approval resume can fail with stale capability input_ref 💬1
- [#4886](https://github.com/nearai/ironclaw/issues/4886) [Reborn] Installed extensions provide limited guidance for required post-install setup `ux`
- [#4885](https://github.com/nearai/ironclaw/issues/4885) [Reborn] Extensions Findings 06/15/2026 - 06/21/2026
- [#4884](https://github.com/nearai/ironclaw/issues/4884) [Reborn] Google Calendar auth prompt requests access token instead of guiding users through OAuth flow
- [#4883](https://github.com/nearai/ironclaw/issues/4883) Improve Test Coverage Tracking and Regression Protection
- [#4882](https://github.com/nearai/ironclaw/issues/4882) Build Coding Agent Cloud Workflow
- [#4881](https://github.com/nearai/ironclaw/issues/4881) Add Preview Deployments for IronClaw PRs
- [#4880](https://github.com/nearai/ironclaw/issues/4880) Automate Code Review and Review Comment Resolution

### 🔒 Closed Issues
- [#4847](https://github.com/nearai/ironclaw/issues/4847) Re-home approval→auth→final-reply Slack delivery e2e onto the delivery/single-flight PR
- [#4851](https://github.com/nearai/ironclaw/issues/4851) Trusted-trigger origin is laundered through adapter_kind string — thread classification as a type (Option 7)
- [#4848](https://github.com/nearai/ironclaw/issues/4848) auth-resume: match pending resume by per-invocation identity (input_ref), not just capability_id
- [#4751](https://github.com/nearai/ironclaw/issues/4751) [Reborn] Large response request fails with provider tool arguments exceed 16384 bytes
- [#3515](https://github.com/nearai/ironclaw/issues/3515) docs: wechat channel
- [#4707](https://github.com/nearai/ironclaw/issues/4707) Conversation page font size is too small in WebUI
- [#4708](https://github.com/nearai/ironclaw/issues/4708) Generated code blocks lack syntax highlighting in WebUI conversation page

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬2 · 2h ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬5 · 3h ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬1 · 3h ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬1 · 3h ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal 
 instead of newlines in string content — 💬1 · 3h ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 6h ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 10h ago
- ⚫ [#92974](https://github.com/openclaw/openclaw/issues/92974) Bug: v2026.6.6 getAttributionHeaders() crashes on Bedrock models — baseUrl undefined (null-guard missing) — 💬1 · 12h ago
- 🟢 [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬1 · 13h ago
- 🟢 [#93032](https://github.com/openclaw/openclaw/issues/93032) [Bug] v2026.6.6: Cron scheduler loads 0 jobs after upgrade — SQLite WAL not committed at first startup — 💬1 · 13h ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [100M model recommendation?](https://reddit.com/r/LocalLLaMA/comments/1u66zjv/100m_model_recommendation/) ↑8
- [UI/svg block rendering by ServeurpersoCom · Pull Request #24080 · ggml-org/llama.cpp](https://reddit.com/r/LocalLLaMA/comments/1u68cm4/uisvg_block_rendering_by_serveurpersocom_pull/) ↑4
- [I made a private on-device LLM app for Android (notes + recall, nothing leaves the phone)](https://reddit.com/r/LocalLLaMA/comments/1u67pw3/i_made_a_private_ondevice_llm_app_for_android/) ↑1
- [An agent that plans with a frontier model but runs most of tokens locally (built it for my own dual-3090 rig)](https://reddit.com/r/LocalLLaMA/comments/1u698b1/an_agent_that_plans_with_a_frontier_model_but/) ↑0
- [moar QAT stuff and hairy ticks](https://reddit.com/r/LocalLLaMA/comments/1u690rz/moar_qat_stuff_and_hairy_ticks/) ↑0

### r/singularity — top 5 new
- [Amazon CEO's Talks With U.S. Officials, Triggered Crackdown on Anthropic Model Fable 5](https://reddit.com/r/singularity/comments/1u4wrxb/amazon_ceos_talks_with_us_officials_triggered/) ↑423
- [Robot Spotted Begging For Money 💀](https://reddit.com/r/singularity/comments/1u61j8u/robot_spotted_begging_for_money/) ↑89
- [Does Openai have Mythos class model?](https://reddit.com/r/singularity/comments/1u5zcr0/does_openai_have_mythos_class_model/) ↑41
- [Business Insider Visits Reflex Robotics](https://reddit.com/r/singularity/comments/1u5ysbb/business_insider_visits_reflex_robotics/) ↑23
- [The ban on Mythos is entirely performative.](https://reddit.com/r/singularity/comments/1u5wgc9/the_ban_on_mythos_is_entirely_performative/) ↑14

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [External re-ranker for memory-core](https://reddit.com/r/openclaw/comments/1u4p4al/external_reranker_for_memorycore/) ↑2
- [How to pair your OpenClaw bot without leaving groups exposed](https://reddit.com/r/openclaw/comments/1u4ju4a/how_to_pair_your_openclaw_bot_without_leaving/) ↑2
- [I built an A2A plugin for OpenClaw that lets it delegate work to remote agents and replay continuation state](https://reddit.com/r/openclaw/comments/1u521ss/i_built_an_a2a_plugin_for_openclaw_that_lets_it/) ↑1
- [Anyone tried openclaw with mythos/fable?](https://reddit.com/r/openclaw/comments/1u4slcy/anyone_tried_openclaw_with_mythosfable/) ↑1
- [I think workflow memory matters more than adding another tool](https://reddit.com/r/openclaw/comments/1u4it5q/i_think_workflow_memory_matters_more_than_adding/) ↑1

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
- [OpenClaw 2026.6.6 

 Tighter security boundaries
 Safer Telegram + iMessage delivery
 Claude Fable 5 + OpenRouter OAuth
](https://x.com/openclaw) ↑0 🔁0 · recent
- [MCP gets Streamable HTTP loopback transport, OAuth/SSE auth fixes, and broader schema compatibility, so external clients](https://x.com/openclaw) ↑0 🔁0 · recent
- [Control UI starts faster and answers sooner: cached model metadata, no startup catalog wait, lazy slash commands, first-](https://x.com/openclaw) ↑0 🔁0 · recent
- [OpenClaw 2026.6.5 

 Parallel web search bundled
 security.installPolicy for skill/plugin installs
 Matrix voice + threa](https://x.com/openclaw) ↑0 🔁0 · recent


### X — @steipete
- [Got a PayPal verification text and thought I been hacked, but it was just codex signing up for a web service it needed.](https://x.com/steipete) ↑0 🔁0 · recent
- [it runs on codex now. or copilot. or our own harness!](https://x.com/steipete) ↑0 🔁0 · recent
- [Any larger sum has 2-factor through my phone with biometric that the agent can't work around.](https://x.com/steipete) ↑0 🔁0 · recent
- [codex update mondays](https://x.com/steipete) ↑0 🔁0 · recent
- [is load-bearing a Claude thing? Haven’t seen that on Codex. Maybe I don’t have enough load](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
