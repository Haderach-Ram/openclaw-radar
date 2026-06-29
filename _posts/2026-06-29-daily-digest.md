---
layout: post
title: "Ecosystem Digest — 2026-06-29"
date: 2026-06-29 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-06-29
*Generated 09:26 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 380,893 | 10 | 4 | 10 | 1 |
| **hermesagent** | 205,090 | 7 | 3 | 8 | 0 |
| **ZeroClaw** | 32,086 | 3 | 5 | 10 | 0 |
| **IronClaw** | 12,487 | 2 | 1 | 3 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 380,893 · **Open issues:** 6,599 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.6.11-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.6.11-beta.2) — openclaw 2026.6.11-beta.2

### ✅ Merged PRs
- [#97539](https://github.com/openclaw/openclaw/pull/97539) fix(signal): bound container REST reads so a hostile signal-cli-rest-api host cannot exhaust memory
- [#97547](https://github.com/openclaw/openclaw/pull/97547) fix(qa-matrix): bound Matrix homeserver response reads to prevent OOM
- [#97648](https://github.com/openclaw/openclaw/pull/97648) fix(mistral): bound streaming Mistral response bodies at 16 MiB
- [#97647](https://github.com/openclaw/openclaw/pull/97647) fix: make inbound document attachments readable by runners
- [#97599](https://github.com/openclaw/openclaw/pull/97599) fix(tlon): truncate approval message preview on UTF-16 boundary
- [#97615](https://github.com/openclaw/openclaw/pull/97615) fix(xai): bound OAuth response reads to prevent OOM
- [#97614](https://github.com/openclaw/openclaw/pull/97614) fix(provider-usage): bound Anthropic usage error response reads to prevent OOM
- [#97571](https://github.com/openclaw/openclaw/pull/97571) fix(failover): allow model_not_found to trigger fallback chain when configured (fixes #97564)
- [#97637](https://github.com/openclaw/openclaw/pull/97637) fix(macos): open dashboard when Dock or Finder relaunches app
- [#97620](https://github.com/openclaw/openclaw/pull/97620) fix(google-meet): bound Drive document export reads to prevent OOM

### 🐛 New Issues
- [#97651](https://github.com/openclaw/openclaw/issues/97651) [Bug]: Tool call output contaminates conversation prefix, collapsing DeepSeek prefix cache hit rate `bug` `regression` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` `maturity:stable` 💬1
- [#97650](https://github.com/openclaw/openclaw/issues/97650) Lock timeout in session store causes crash loop via unhandled rejection `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `impact:crash-loop` `issue-rating: 🐚 platinum hermit` `maturity:stable` 💬1
- [#97638](https://github.com/openclaw/openclaw/issues/97638) [Feature]: Add skipSkillsSync option to skip copying skills into sandbox workspaces `enhancement` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬2
- [#97636](https://github.com/openclaw/openclaw/issues/97636) [Bug]: Control UI can connect to the wrong gateway across base paths `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` `maturity:stable` 💬1
- [#97625](https://github.com/openclaw/openclaw/issues/97625) [Bug]: Qwen3:14b fails with CLI transcript compaction failed: Already compacted; identical MCP tool succeeds with Llama3.1:8b `bug` `bug:behavior` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:session-state` `impact:message-loss` `impact:auth-provider` `issue-rating: 🐚 platinum hermit` `maturity:stable` 💬1
- [#97621](https://github.com/openclaw/openclaw/issues/97621) xAI server-side tools (`code_execution` / `x_search`) are offered to agents on non-xAI models and silently bill xAI; they auto-enable from key presence `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:security` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#97616](https://github.com/openclaw/openclaw/issues/97616) [Bug]: OpenClaw leaks unreaped hook/tool child processes, causing zombie accumulation and runtime degradation `bug` 💬2
- [#97603](https://github.com/openclaw/openclaw/issues/97603) [Feature]: Dynamic per-invocation/per-session working directory that works under the sandbox backend `enhancement` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `impact:session-state` `issue-rating: 🌊 off-meta tidepool` `maturity:stable` 💬1
- [#97602](https://github.com/openclaw/openclaw/issues/97602) Control UI: Personal card avatar 401 due to inconsistent avatar resolution between agents.list and agent.identity.get `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `maturity:stable` 💬1
- [#97601](https://github.com/openclaw/openclaw/issues/97601) Add config toggle to suppress chat-visible fast auto-mode status updates `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1

### 🔒 Closed Issues
- [#97237](https://github.com/openclaw/openclaw/issues/97237) Inbound non-image attachments exposed to the model as unresolvable media://inbound/... URI (PDFs/docs unreadable)
- [#97645](https://github.com/openclaw/openclaw/issues/97645) bug: session compaction corrupts thinking blocks, causing permanent API rejection
- [#97564](https://github.com/openclaw/openclaw/issues/97564) [Bug]: Failover skips configured fallbacks when a model is decommissioned (model_not_found treated as terminal)
- [#97639](https://github.com/openclaw/openclaw/issues/97639) [Bug] Gateway restart spawns hanging findstr window on Windows

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 205,090 · **Open issues:** 24,044 · **Last push:** <1h ago

### ✅ Merged PRs
- [#54569](https://github.com/NousResearch/hermes-agent/pull/54569) fix(matrix,mattermost): invite auth check + API path traversal guard
- [#54567](https://github.com/NousResearch/hermes-agent/pull/54567) fix(lmstudio): normalize base URLs so chats/probes hit correct endpoints
- [#54564](https://github.com/NousResearch/hermes-agent/pull/54564) chore: remove committed PR infographics and gitignore the path
- [#54563](https://github.com/NousResearch/hermes-agent/pull/54563) fix(agent): limit .hermes.md parent walk to git repos only (salvage #6662)
- [#54517](https://github.com/NousResearch/hermes-agent/pull/54517) feat(desktop): multi-terminal panel with read-only agent terminals
- [#54558](https://github.com/NousResearch/hermes-agent/pull/54558) feat(desktop): shared overlay Panel primitive for cron/profiles/agents
- [#54546](https://github.com/NousResearch/hermes-agent/pull/54546) feat(dashboard): catalogue all memory-provider API keys in OPTIONAL_ENV_VARS
- [#54469](https://github.com/NousResearch/hermes-agent/pull/54469) fix(approvals): warn and default to manual on unknown approvals.mode

### 🐛 New Issues
- [#54601](https://github.com/NousResearch/hermes-agent/issues/54601) feat: declarative per-channel model routing (channel_model_map)
- [#54593](https://github.com/NousResearch/hermes-agent/issues/54593) [Bug] Ollama vision models silently strip image attachments `type/bug` `duplicate` `comp/agent` `tool/vision` `provider/ollama` `P2` 💬1
- [#54589](https://github.com/NousResearch/hermes-agent/issues/54589) [Bug]: OpenAI-compatible TTS backends without opus support fail on voice bubbles (_generate_openai_tts hardcodes response_format="opus" for .ogg) `type/bug` `tool/tts` `P2` `bug` 💬1
- [#54587](https://github.com/NousResearch/hermes-agent/issues/54587) [Bug]: TUI transcript partially blanks when resuming long sessions — mounted range too narrow `type/bug` `comp/tui` `P3`
- [#54579](https://github.com/NousResearch/hermes-agent/issues/54579) Long code blocks lose their indentation when a reply is split into multiple messages `type/bug` `comp/gateway` `P2` `sweeper:risk-message-delivery` 💬1
- [#54577](https://github.com/NousResearch/hermes-agent/issues/54577) bug(title_generation): `enabled: false` config is ignored, title generation always runs `type/bug` `duplicate` `comp/agent` `P3` 💬1
- [#54572](https://github.com/NousResearch/hermes-agent/issues/54572) patch tool (replace mode) can edit the wrong region when old_string is not an exact match `type/bug` `tool/file` `P2` 💬2

### 🔒 Closed Issues
- [#53256](https://github.com/NousResearch/hermes-agent/issues/53256) [Bug]: Hermes Desktop incorrectly constructs API paths and forces unsupported tool-calling when connecting to an LM Studio server
- [#54584](https://github.com/NousResearch/hermes-agent/issues/54584) [Skill]: dbx CLI integration — schema exploration, query execution, and context generation
- [#54578](https://github.com/NousResearch/hermes-agent/issues/54578) [Bug]: Feishu reply attachments not visible to agent

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,086 · **Open issues:** 453 · **Last push:** <1h ago

### ✅ Merged PRs
- [#8370](https://github.com/zeroclaw-labs/zeroclaw/pull/8370) test(mcp): regression-test mcp_bundles enforcement + warn on no-bundle misconfig (#7733)
- [#8437](https://github.com/zeroclaw-labs/zeroclaw/pull/8437) refactor(log): extract JSONL write pipeline into testable helper
- [#8404](https://github.com/zeroclaw-labs/zeroclaw/pull/8404) ci(release): cosign signing, SLSA provenance, and SBOM for release pipeline (#8058)
- [#8239](https://github.com/zeroclaw-labs/zeroclaw/pull/8239) feat(config): add independent delegate targets
- [#6966](https://github.com/zeroclaw-labs/zeroclaw/pull/6966) feat(obs): capture prompt/completion content on llm.response spans
- [#8436](https://github.com/zeroclaw-labs/zeroclaw/pull/8436) docs(runtime): document max_history_messages hard cap alongside whole-turn trim
- [#8326](https://github.com/zeroclaw-labs/zeroclaw/pull/8326) fix(acp-bridge): strip UTF-8 BOM from config.toml before TOML parsing
- [#8350](https://github.com/zeroclaw-labs/zeroclaw/pull/8350) perf(web-search): cache strip_tags regex in a LazyLock static
- [#8136](https://github.com/zeroclaw-labs/zeroclaw/pull/8136) feat(tool:browser): allow http:// URLs in browser_open (was https-only)
- [#8352](https://github.com/zeroclaw-labs/zeroclaw/pull/8352) ci(release): fail early on package token access

### 🐛 New Issues
- [#8462](https://github.com/zeroclaw-labs/zeroclaw/issues/8462) RFC: LLM Input/Output Content Capture for Observability
- [#8453](https://github.com/zeroclaw-labs/zeroclaw/issues/8453) log: replace #[allow(dead_code)] write_lock with concrete usage or delete
- [#8445](https://github.com/zeroclaw-labs/zeroclaw/issues/8445) [Feature]: Telegram channel multi-message mode (one message per agent turn) 💬1

### 🔒 Closed Issues
- [#7733](https://github.com/zeroclaw-labs/zeroclaw/issues/7733) [Bug]: mcp_bundles is parsed and shown in Config but never enforced at runtime — per-agent MCP scoping is a silent no-op
- [#8058](https://github.com/zeroclaw-labs/zeroclaw/issues/8058) CI: release-only — cosign signing, SLSA provenance, SBOM publication
- [#8238](https://github.com/zeroclaw-labs/zeroclaw/issues/8238) [Feature]: Add independent delegate mode for specialist handoffs
- [#8369](https://github.com/zeroclaw-labs/zeroclaw/issues/8369) [Bug]: max_history_messages hard cap still uses legacy message-count trimming after whole-turn trim rewrite
- [#8432](https://github.com/zeroclaw-labs/zeroclaw/issues/8432) bug(ci): package publish tokens fail late when push access is missing

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,487 · **Open issues:** 1,251 · **Last push:** <1h ago

### ✅ Merged PRs
- [#5388](https://github.com/nearai/ironclaw/pull/5388) [codex] fix reborn google oauth decode and preview host login
- [#5244](https://github.com/nearai/ironclaw/pull/5244) build(webui-v2): remove generated dist from source control
- [#5384](https://github.com/nearai/ironclaw/pull/5384) [codex] Pin WebUI v2 frontend Node tooling

### 🐛 New Issues
- [#5385](https://github.com/nearai/ironclaw/issues/5385) Add Capability Policy
- [#4108](https://github.com/nearai/ironclaw/issues/4108) Nightly E2E failed

### 🔒 Closed Issues
- [#5236](https://github.com/nearai/ironclaw/issues/5236) Stop committing WebUI v2 dist bundle artifacts

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 1h ago
- ⚫ [#94780](https://github.com/openclaw/openclaw/issues/94780) [Feature]: Per-cron model selection independent of agent default — run cheap/free models on automation jobs while keeping main agent on premium LLM — 💬1 · 3d ago
- ⚫ [#93032](https://github.com/openclaw/openclaw/issues/93032) [Bug] v2026.6.6: Cron scheduler loads 0 jobs after upgrade — SQLite WAL not committed at first startup — 💬2 · 3d ago
- ⚫ [#92974](https://github.com/openclaw/openclaw/issues/92974) Bug: v2026.6.6 getAttributionHeaders() crashes on Bedrock models — baseUrl undefined (null-guard missing) — 💬1 · 3d ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬4 · 5d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬7 · 6d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 7d ago
- 🟢 [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬1 · 7d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬2 · 7d ago
- 🟢 [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 7d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 1 new
- [[Index] Hp Frontier Partnership](https://openai.com/index/hp-frontier-partnership/) _2026-06-29_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/singularity — top 2 new
- [Meanwhile in China, 10,000+ delivery bots are transforming last-mile fulfillment by making deliveries faster, cheaper, and more autonomous](https://reddit.com/r/singularity/comments/1uhxshz/meanwhile_in_china_10000_delivery_bots_are/) ↑1350
- [Donald Trump Bench](https://reddit.com/r/singularity/comments/1ui5wgm/donald_trump_bench/) ↑639

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Thoughts on Microsoft's OpenClaw partnership announcement](https://reddit.com/r/openclaw/comments/1tw2jk9/thoughts_on_microsofts_openclaw_partnership/) ↑68
- [how the F* do I get claw to consistently do a daily journal?](https://reddit.com/r/openclaw/comments/1uhq63n/how_the_f_do_i_get_claw_to_consistently_do_a/) ↑19
- [Openclaw Life Pro Tip - A second instance is a lifesaver.](https://reddit.com/r/openclaw/comments/1uhu03z/openclaw_life_pro_tip_a_second_instance_is_a/) ↑18
- [Breaking Update Issue](https://reddit.com/r/openclaw/comments/1uibjih/breaking_update_issue/) ↑6
- [I built OpenClaw agents to find freelance work... but they're still worse than doing it myself.](https://reddit.com/r/openclaw/comments/1uhqtpp/i_built_openclaw_agents_to_find_freelance_work/) ↑4

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
- [Yes.](https://x.com/steipete) ↑0 🔁0 · recent
- [the dream](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
