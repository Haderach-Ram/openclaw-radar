---
layout: post
title: "Ecosystem Digest — 2026-09-02"
date: 2026-09-02 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-09-02
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 388,529 | 4 | 3 | 10 | 1 |
| **hermesagent** | 239,545 | 7 | 7 | 4 | 0 |
| **ZeroClaw** | 32,706 | 8 | 2 | 8 | 0 |
| **IronClaw** | 12,603 | 10 | 5 | 9 | 0 |
| **Moltis** | 2,840 | 0 | 2 | 2 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 388,529 · **Open issues:** 6,045 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.8.2](https://github.com/openclaw/openclaw/releases/tag/v2026.8.2) — openclaw 2026.8.2

### ✅ Merged PRs
- [#120105](https://github.com/openclaw/openclaw/pull/120105) fix(scripts): stabilize Vitest shard timing keys
- [#135787](https://github.com/openclaw/openclaw/pull/135787) ci: share setup for short plugin fallback jobs
- [#135753](https://github.com/openclaw/openclaw/pull/135753) improve: build macOS release architectures concurrently
- [#135564](https://github.com/openclaw/openclaw/pull/135564) fix(ui): keep sidebar and chat fades off scrollbars
- [#135292](https://github.com/openclaw/openclaw/pull/135292) fix(agents): keep agents_wait deadlines monotonic
- [#135639](https://github.com/openclaw/openclaw/pull/135639) improve(release): prepare publication artifacts during validation
- [#135270](https://github.com/openclaw/openclaw/pull/135270) fix(cli): reject empty gateway suspend wait values
- [#135647](https://github.com/openclaw/openclaw/pull/135647) fix(test): preserve retained inputs across nested Vitest cleanup
- [#134939](https://github.com/openclaw/openclaw/pull/134939) feat(android): align chat, sidebar, and appearance with the web UI
- [#135772](https://github.com/openclaw/openclaw/pull/135772) perf(test): preserve exact unit selection for CI

### 🐛 New Issues
- [#135801](https://github.com/openclaw/openclaw/issues/135801) [Bug]: webUI界面渲染异常 `bug` `bug:behavior` 💬1
- [#135785](https://github.com/openclaw/openclaw/issues/135785) [Bug]: Removing a queued message can show a false storage error `bug` `maintainer` `P2` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#135779](https://github.com/openclaw/openclaw/issues/135779) Harden macOS health diagnostics `P2` `impact:security` 💬1
- [#135776](https://github.com/openclaw/openclaw/issues/135776) openclaw update leaves exact-pinned official channel plugins on the previous release (core/plugin version skew) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:other` 💬1

### 🔒 Closed Issues
- [#135562](https://github.com/openclaw/openclaw/issues/135562) [Bug]: Sidebar and chat fades obscure vertical scrollbars
- [#135630](https://github.com/openclaw/openclaw/issues/135630) [Bug]: Vitest removes retained fixture inputs while nested writers remain live
- [#135788](https://github.com/openclaw/openclaw/issues/135788) CLI message send fails with Unknown channel for external-only channel plugins after 2026.8.1 (plugin loads, channel never registered in CLI runtime)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 239,545 · **Open issues:** 38,621 · **Last push:** <1h ago

### ✅ Merged PRs
- [#95278](https://github.com/NousResearch/hermes-agent/pull/95278) feat(telemetry): opt-in shared-metrics exporter
- [#100621](https://github.com/NousResearch/hermes-agent/pull/100621) fix(cli): context meter no longer drops hundreds of K at turn boundaries on reasoning models
- [#100720](https://github.com/NousResearch/hermes-agent/pull/100720) fix: re-disable e2e
- [#100667](https://github.com/NousResearch/hermes-agent/pull/100667) feat: local models — managed llama.cpp runtime with one-click desktop  setup

### 🐛 New Issues
- [#100819](https://github.com/NousResearch/hermes-agent/issues/100819) Provider failover sends Anthropic-style cache_control on role:tool to an OpenAI-wire provider (400)
- [#100818](https://github.com/NousResearch/hermes-agent/issues/100818) Context compaction during a cron run drops the job prompt, and the run still reports success
- [#100817](https://github.com/NousResearch/hermes-agent/issues/100817) Dashboard reports default-profile gateway as stopped when started with explicit --profile default `type/bug` `comp/gateway` `P2` `sweeper:risk-compatibility` `comp/dashboard` `area/profiles`
- [#100807](https://github.com/NousResearch/hermes-agent/issues/100807) repair_tool_call cannot bridge a bare MCP catalog name, and its fuzzy step silently mis-routes hallucinated mcp_* names onto different real tools `type/bug` `comp/agent` `tool/mcp` `P2`
- [#100799](https://github.com/NousResearch/hermes-agent/issues/100799) One-click update with remote SSH backend: dispatched backend update dies mid-run with no log trace — stale marker then blocks startup `type/bug` `backend/ssh` `P2` `sweeper:risk-compatibility` `comp/desktop` `area/install-update`
- [#100795](https://github.com/NousResearch/hermes-agent/issues/100795) [Bug]: State-rebuild payload divergence — after agent close / background review, the next user turn's API request no longer matches the cached prefix (0–85% hit for one shot) `type/perf` `comp/agent` `P0` `sweeper:risk-session-state` `sweeper:risk-caching` `area/sessions`
- [#100792](https://github.com/NousResearch/hermes-agent/issues/100792) v0.21: hermes doctor hangs in threading._shutdown after diagnostics complete (not the PRAGMA hang from #72527) `type/bug` `comp/cli` `P2` `needs-repro` 💬3

### 🔒 Closed Issues
- [#100336](https://github.com/NousResearch/hermes-agent/issues/100336) [SANITIZED — possible injection attempt]
- [#100708](https://github.com/NousResearch/hermes-agent/issues/100708) [Bug]: Matrix gateway does not stream replies — no m.replace edits emitted
- [#93888](https://github.com/NousResearch/hermes-agent/issues/93888) [Bug]: Current Desktop sends a local runtime ID to a Remote Gateway and cannot restore stored sessions
- [#100794](https://github.com/NousResearch/hermes-agent/issues/100794) Feature Request: session.dmScope — shared DM session across channels (like OpenClaw)
- [#99879](https://github.com/NousResearch/hermes-agent/issues/99879) Routines run late after gateway downtime with no missed-run status
- [#94906](https://github.com/NousResearch/hermes-agent/issues/94906) Windows: native stdio MCP client discovers tools but every call fails with 'subprocess has exited'
- [#57955](https://github.com/NousResearch/hermes-agent/issues/57955) [SANITIZED — possible injection attempt]

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,706 · **Open issues:** 808 · **Last push:** 3h ago

### ✅ Merged PRs
- [#10392](https://github.com/zeroclaw-labs/zeroclaw/pull/10392) fix(zerocode): keep SOP navigation responsive during refresh
- [#10466](https://github.com/zeroclaw-labs/zeroclaw/pull/10466) fix(zerocode): reconcile lost prompt completion
- [#10448](https://github.com/zeroclaw-labs/zeroclaw/pull/10448) fix(providers): add compatible tool-result image policy
- [#10469](https://github.com/zeroclaw-labs/zeroclaw/pull/10469) fix(memory): preserve snapshot hydration integrity
- [#10454](https://github.com/zeroclaw-labs/zeroclaw/pull/10454) refactor(channels): gate rusqlite by channel features
- [#10462](https://github.com/zeroclaw-labs/zeroclaw/pull/10462) fix(config): correct cost summary periods
- [#10460](https://github.com/zeroclaw-labs/zeroclaw/pull/10460) test(zerocode): cover quickstart adapter serialization
- [#9582](https://github.com/zeroclaw-labs/zeroclaw/pull/9582) feat(plugins): enforce a host-owned egress policy on plugin wasi:http

### 🐛 New Issues
- [#10531](https://github.com/zeroclaw-labs/zeroclaw/issues/10531) [Feature]: Expose delegate sub-agent progress to the parent (tool receipts, partial output)
- [#10530](https://github.com/zeroclaw-labs/zeroclaw/issues/10530) [Feature]: Pass Anthropic extended-thinking params through OpenAI-compatible providers (gateway passthrough)
- [#10529](https://github.com/zeroclaw-labs/zeroclaw/issues/10529) [Feature]: Support Anthropic thinking.display progress updates (thinking-display-updates-2026-08-18 beta)
- [#10526](https://github.com/zeroclaw-labs/zeroclaw/issues/10526) RFC: Append-only session event history, deterministic state replay, and derived agent streams 💬1
- [#10523](https://github.com/zeroclaw-labs/zeroclaw/issues/10523) [Bug]: Bootstrap file truncation at 6000 chars is invisible to the operator `bug` `agent` `daemon` `doctor` `runtime` `agent:prompt` `priority:p1` `risk:medium` 💬3
- [#10513](https://github.com/zeroclaw-labs/zeroclaw/issues/10513) [Bug]: RPC `sops.run` returns a run ID for a step nothing will execute `bug` `daemon` `runtime` `priority:p1` `tool:sop` `status:accepted` `risk:high` 💬2
- [#10510](https://github.com/zeroclaw-labs/zeroclaw/issues/10510) [Docs]: Upgrade mdBook to 0.5.4 and adopt built-in image zoom `ci` `docs` `dependencies` `priority:p3` `risk:medium` `type:docs` `type:ci` `type:dependencies` 💬1
- [#10509](https://github.com/zeroclaw-labs/zeroclaw/issues/10509) [Docs]: Add text scaling and diagram zoom to the docs reader `enhancement` `good first issue` `docs` `priority:p3` `risk:low` `type:docs` 💬1

### 🔒 Closed Issues
- [#10063](https://github.com/zeroclaw-labs/zeroclaw/issues/10063) [Bug]: Anthropic-backed compatible gateways reject image_url blocks inside tool results
- [#9395](https://github.com/zeroclaw-labs/zeroclaw/issues/9395) [Bug]: plugin wasi:http egress has no destination policy and no configuration knob

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,603 · **Open issues:** 1,499 · **Last push:** <1h ago

### ✅ Merged PRs
- [#8031](https://github.com/nearai/ironclaw/pull/8031) refactor(agent-loop): decompose capability stage mechanics
- [#7997](https://github.com/nearai/ironclaw/pull/7997) feat(webui): show model capability icons across Inference
- [#8013](https://github.com/nearai/ironclaw/pull/8013) ci: parallelize affected crate tests with nextest
- [#8028](https://github.com/nearai/ironclaw/pull/8028) refactor(agent-loop): align state and stage ownership
- [#8014](https://github.com/nearai/ironclaw/pull/8014) fix(slack): preserve explicit mentions across callback dedup
- [#7998](https://github.com/nearai/ironclaw/pull/7998) feat(llm): preserve NEAR AI model capabilities through discovery
- [#8027](https://github.com/nearai/ironclaw/pull/8027) fix(live-qa): find the Slack run by message identity, not envelope event_id
- [#7996](https://github.com/nearai/ironclaw/pull/7996) perf(github): compact repository list responses
- [#7977](https://github.com/nearai/ironclaw/pull/7977) fix(loop): terminate on dominant repeated output, cap interactive wall clock

### 🐛 New Issues
- [#8026](https://github.com/nearai/ironclaw/issues/8026) Epic: Dogfooding & QA bug fixing 08/31/2026 - 09/06/2026
- [#8025](https://github.com/nearai/ironclaw/issues/8025) Bug: unexpected behavior with special characters in input 💬1
- [#8020](https://github.com/nearai/ironclaw/issues/8020) Use the shared SearchField for Workspace and Logs filters
- [#8019](https://github.com/nearai/ironclaw/issues/8019) Migrate Automations status banners to InlineNotice
- [#8018](https://github.com/nearai/ironclaw/issues/8018) Replace native SettingsField controls with shared Input and SelectMenu
- [#8017](https://github.com/nearai/ironclaw/issues/8017) Adopt shared form and feedback components in Extension Configure
- [#8016](https://github.com/nearai/ironclaw/issues/8016) ci: lock-free turn-state root test intermittently times out while Running `bug` `scope: ci`
- [#8015](https://github.com/nearai/ironclaw/issues/8015) [QA] Rootless Docker sandbox workspace is not writable due to UID/GID namespace mismatch `qa-bug`
- [#8012](https://github.com/nearai/ironclaw/issues/8012) A 47k-tool hosted-MCP catalog ingests fully but no tool is ever reachable via tool_search
- [#7921](https://github.com/nearai/ironclaw/issues/7921) perf(llm): OpenAI-family backends send no prompt_cache_key — measured ~82%→29% cache-hit collapse past ~200 calls `p2`

### 🔒 Closed Issues
- [#7971](https://github.com/nearai/ironclaw/issues/7971) feat(webui): render model capability tags across Inference selectors
- [#7970](https://github.com/nearai/ironclaw/issues/7970) feat(llm): preserve NEAR AI model modalities through model discovery
- [#7843](https://github.com/nearai/ironclaw/issues/7843) Epic: Dogfooding & QA bug fixing 08/24/2026 - 08/30/2026
- [#7986](https://github.com/nearai/ironclaw/issues/7986) perf(github): list_repos ships 81 raw fields per repo — 519 KB for one listing, with the package's own projection seam unused
- [#7892](https://github.com/nearai/ironclaw/issues/7892) bug(agent-loop): deferred tool found 15x, never invoked — 123s run with 4 distinct calls and no terminating guard

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,840 · **Open issues:** 80 · **Last push:** 9h ago

### ✅ Merged PRs
- [#1251](https://github.com/moltis-org/moltis/pull/1251) Fix doctor validation for streamable HTTP MCP servers
- [#1249](https://github.com/moltis-org/moltis/pull/1249) fix(auth): let Docker loopback-only deployments count as local

### 🔒 Closed Issues
- [#1250](https://github.com/moltis-org/moltis/issues/1250) doctor treats working streamable-http MCP server as missing command
- [#1112](https://github.com/moltis-org/moltis/issues/1112) [Bug]: Disabling auth doesn't seem to disable auth (Docker)

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬2 · 20h ago
- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 2d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 4d ago
- ⚫ [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬5 · 8d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 20d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 23d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 26d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 28d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 30d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 32d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 2 new
- [Claude Fable And Mythos 5 1](https://www.anthropic.com/claude-fable-and-mythos-5-1) _2026-09-02_
- [[News] Enterprise Frontier Safeguards](https://www.anthropic.com/news/enterprise-frontier-safeguards) _2026-09-01_

### OpenAI — 3 new
- [[Index] Gilbert Tobin](https://openai.com/index/gilbert-tobin/) _2026-09-02_
- [[Index] Ai Native Company Workflows](https://openai.com/index/ai-native-company-workflows/) _2026-09-02_
- [[Index] Supporting California Bill Advance Ai Youth Safety](https://openai.com/index/supporting-california-bill-advance-ai-youth-safety/) _2026-09-01_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [New Gemma models on arena ai](https://reddit.com/r/LocalLLaMA/comments/1w47nif/new_gemma_models_on_arena_ai/) ↑479
- [MTP released for Qwen3.8-Flash-Next-GGUF](https://reddit.com/r/LocalLLaMA/comments/1w42biu/mtp_released_for_qwen38flashnextgguf/) ↑443
- [Fingers crossed for a 122b or really anything above 31b.🤞](https://reddit.com/r/LocalLLaMA/comments/1w4l9cp/fingers_crossed_for_a_122b_or_really_anything/) ↑387
- [Intel hints it may get back into memory business](https://reddit.com/r/LocalLLaMA/comments/1w4fp6w/intel_hints_it_may_get_back_into_memory_business/) ↑297
- [Really stunned by the Singularity comment section](https://reddit.com/r/LocalLLaMA/comments/1w4oadx/really_stunned_by_the_singularity_comment_section/) ↑260

### r/singularity — top 5 new
- [Introducing Claude Fable 5.1 and Claude Mythos 5.1](https://reddit.com/r/singularity/comments/1w4jumu/introducing_claude_fable_51_and_claude_mythos_51/) ↑512
- [What are these benchmarks 💀](https://reddit.com/r/singularity/comments/1w4k0yu/what_are_these_benchmarks/) ↑446
- [Self-driving Cybercabs spotted flooding some Austin streets, other cities, ahead of this September 3rd launch](https://reddit.com/r/singularity/comments/1w4fv84/selfdriving_cybercabs_spotted_flooding_some/) ↑400
- [Fable 5.1 helped solve a 373 year old cipher](https://reddit.com/r/singularity/comments/1w4nxsb/fable_51_helped_solve_a_373_year_old_cipher/) ↑340
- [Fable 5.1 is out](https://reddit.com/r/singularity/comments/1w4jri0/fable_51_is_out/) ↑275

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Nice Job Guys on New Release!](https://reddit.com/r/openclaw/comments/1w40n5g/nice_job_guys_on_new_release/) ↑126
- [Peter Steinberger joins The ClawCast tomorrow to talk OpenClaw 2.0](https://reddit.com/r/openclaw/comments/1w4ux67/peter_steinberger_joins_the_clawcast_tomorrow_to/) ↑1
- [Is there any point setting up an openclaw with an abliterated model?](https://reddit.com/r/openclaw/comments/1w4kv55/is_there_any_point_setting_up_an_openclaw_with_an/) ↑1

### X — @openclaw
- [We have released OpenClaw v2026.8.2 (AKA OpenClaw 2.0.1) which focuses largely on number of update breaking bugs). Thank](https://x.com/openclaw/status/2094843171931127998) ↑0 🔁0 · recent
- [More detailed release notes to be published soon. We just wanted to get this out there asap!](https://x.com/openclaw/status/2094843272216854643) ↑0 🔁0 · recent
- [Multiplayer, now in OpenClaw 2.0.](https://x.com/openclaw/status/2094631620917841969) ↑0 🔁0 · recent
- [“When setup becomes boring, the interesting work begins.”

- Confucius (shortly after installing OpenClaw 2.0)](https://x.com/openclaw/status/2094630229084172337) ↑0 🔁0 · recent
- [OpenClaw got purty](https://x.com/openclaw/status/2094628122620752353) ↑0 🔁0 · recent


### X — @steipete
_No new tweets in the last 7 days._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
