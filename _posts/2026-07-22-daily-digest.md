---
layout: post
title: "Ecosystem Digest — 2026-07-22"
date: 2026-07-22 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-07-22
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 383,733 | 7 | 2 | 10 | 0 |
| **hermesagent** | 218,436 | 11 | 4 | 10 | 0 |
| **ZeroClaw** | 32,353 | 12 | 3 | 10 | 0 |
| **IronClaw** | 12,546 | 9 | 8 | 10 | 1 |
| **Moltis** | 2,788 | 1 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 383,733 · **Open issues:** 7,024 · **Last push:** <1h ago

### ✅ Merged PRs
- [#102228](https://github.com/openclaw/openclaw/pull/102228) Install ClawHub packages for new Claw agents
- [#112471](https://github.com/openclaw/openclaw/pull/112471) fix(gateway): read control-UI descriptors from the pinned session-extension registry
- [#112457](https://github.com/openclaw/openclaw/pull/112457) fix(agents): enforce Claude CLI cron tool policies
- [#112434](https://github.com/openclaw/openclaw/pull/112434) feat(dashboard): plugin widget kinds — native WorkBoard card and mini-board widgets
- [#112467](https://github.com/openclaw/openclaw/pull/112467) fix: keep replies working after config reload
- [#112412](https://github.com/openclaw/openclaw/pull/112412) feat: discover models from live provider catalogs
- [#112443](https://github.com/openclaw/openclaw/pull/112443) [SANITIZED — possible injection attempt]
- [#112415](https://github.com/openclaw/openclaw/pull/112415) fix(cron): honor script limits and permanent failures
- [#101973](https://github.com/openclaw/openclaw/pull/101973) Create Claw-managed workspace files
- [#109875](https://github.com/openclaw/openclaw/pull/109875) fix(config): reject gateway.port values outside the 1–65535 TCP range

### 🐛 New Issues
- [#112475](https://github.com/openclaw/openclaw/issues/112475) [Bug]: [Support] Device pairing recovery fails after removal (Gateway 2026.7.1 / CLI 2026.6.9) `bug` `bug:behavior` 💬1
- [#112470](https://github.com/openclaw/openclaw/issues/112470) [Bug]: Media Understanding fails under Clash/Mihomo Fake-IP due to SSRF protection（ai写的） `bug` `regression` 💬1
- [#112468](https://github.com/openclaw/openclaw/issues/112468) Codex app-server: trailing NO_REPLY to a late-injected completion event swallows the turn's already-emitted final answer (silent success) 💬1
- [#112466](https://github.com/openclaw/openclaw/issues/112466) Plugin hooks: allow before_prompt_build to narrow the submitted tool surface per turn (toolsAllow) 💬1
- [#112450](https://github.com/openclaw/openclaw/issues/112450) [Bug]: Matrix startup migration scans legacy roots but skips dedupe state 💬1
- [#112445](https://github.com/openclaw/openclaw/issues/112445) OpenAI Codex OAuth token refresh ignores env proxy → 403 unsupported_country_region_territory behind geo-restricted egress 💬1
- [#112440](https://github.com/openclaw/openclaw/issues/112440) [Feature]: Project native harness children onto portable subagent progress `enhancement` `maintainer` 💬1

### 🔒 Closed Issues
- [#112454](https://github.com/openclaw/openclaw/issues/112454) Cron toolsAllow cannot be enforced by claude-cli runtime
- [#112405](https://github.com/openclaw/openclaw/issues/112405) [Feature]: Discover provider models from live catalogs

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬114 · 2d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 218,436 · **Open issues:** 24,556 · **Last push:** <1h ago

### ✅ Merged PRs
- [#68999](https://github.com/NousResearch/hermes-agent/pull/68999) fix(ui-tui): widget-grid hardening — review fast-follow for #20379
- [#69019](https://github.com/NousResearch/hermes-agent/pull/69019) fix(desktop): stop long-session transcript from drifting to old turns
- [#68997](https://github.com/NousResearch/hermes-agent/pull/68997) fix(windows): share one bounded, tree-killing git probe across both probe call sites
- [#69003](https://github.com/NousResearch/hermes-agent/pull/69003) test(mcp): fix monotonic-clock flake in circuit-breaker cooldown test
- [#20379](https://github.com/NousResearch/hermes-agent/pull/20379) feat(ui-tui): widget-grid layout engine + background-aware theme engine
- [#68977](https://github.com/NousResearch/hermes-agent/pull/68977) fmt(js): `npm run fix` auto-fix
- [#68976](https://github.com/NousResearch/hermes-agent/pull/68976) fmt(js): `npm run fix` auto-fix
- [#68938](https://github.com/NousResearch/hermes-agent/pull/68938) fmt(js): `npm run fix` auto-fix
- [#68918](https://github.com/NousResearch/hermes-agent/pull/68918) feat(desktop): type-to-focus the composer from empty chat chrome
- [#68657](https://github.com/NousResearch/hermes-agent/pull/68657) fix(status): stable RFC3339-or-null contract for gateway_updated_at

### 🐛 New Issues
- [#69043](https://github.com/NousResearch/hermes-agent/issues/69043) Feature: Ephemeral session mode (--ephemeral flag)
- [#69039](https://github.com/NousResearch/hermes-agent/issues/69039) [Bug] usePet.ts: pet.cells RPC polling lacks enabled guard — timeout spam when pet disabled
- [#69038](https://github.com/NousResearch/hermes-agent/issues/69038) Desktop: browser-generated local HTML previews leak as duplicate composer includes across sessions
- [#69033](https://github.com/NousResearch/hermes-agent/issues/69033) [Bug]: Local terminal tool orphans bash/find/grep/head children on Windows (missing process-group/job-object detachment in _popen_bash) `type/bug` `tool/terminal` `backend/local` `P2` `needs-repro` `sweeper:risk-platform-windows` `platform/windows` 💬1
- [#69031](https://github.com/NousResearch/hermes-agent/issues/69031) fix(agent): resolve Gemini native v1beta 401 Auth error and 400 Invalid Argument schema error `type/bug` `comp/agent` `tool/mcp` `provider/gemini` `P2` `needs-repro`
- [#69027](https://github.com/NousResearch/hermes-agent/issues/69027) [Bug]: Multi-task popup overlaps chat history when scrolling `type/bug` `P3` `comp/desktop` `bug`
- [#69026](https://github.com/NousResearch/hermes-agent/issues/69026) [Feature]: Desktop – Stabilize theme selector in Appearance settings `type/feature` `P3` `comp/desktop`
- [#69025](https://github.com/NousResearch/hermes-agent/issues/69025) feat(desktop): settings search bar for quick setting discovery `type/feature` `P3` `comp/desktop` 💬1
- [#69021](https://github.com/NousResearch/hermes-agent/issues/69021) Kanban tutorial Story 3: How does reviewer feedback reach the dev worker before dev completes? `type/docs` `question` `comp/cron` `P3` 💬1
- [#69016](https://github.com/NousResearch/hermes-agent/issues/69016) Desktop renderer memory leak: render process OOM-killed (render-process-gone, exitCode -36861) roughly every 60s `type/bug` `P2` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows`
- [#69014](https://github.com/NousResearch/hermes-agent/issues/69014) fix(desktop): expand tilde paths in desktop.readDir & fallback to global desktop-plugins across agent profiles `type/bug` `comp/plugins` `P3` `needs-decision` `comp/desktop` `area/profiles` 💬1

### 🔒 Closed Issues
- [#27683](https://github.com/NousResearch/hermes-agent/issues/27683) web_tools.py: missing _ensure_plugins_discovered() at search/extract/crawl dispatch sites causes web tools to silently fail
- [#38786](https://github.com/NousResearch/hermes-agent/issues/38786) [Bug]: Hermes Desktop shows generated local images as [Image blocked: ...] even though image generation succeeds
- [#68952](https://github.com/NousResearch/hermes-agent/issues/68952) Incident: delegation/review loop consumed ~50% of weekly usage on an unvalidated premise
- [#54675](https://github.com/NousResearch/hermes-agent/issues/54675) [SANITIZED — possible injection attempt]

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,353 · **Open issues:** 516 · **Last push:** 6h ago

### ✅ Merged PRs
- [#8756](https://github.com/zeroclaw-labs/zeroclaw/pull/8756) fix(tests): make media marker assertions portable on Windows
- [#9011](https://github.com/zeroclaw-labs/zeroclaw/pull/9011) feat(zerocode): show active runtime context in dashboard
- [#9055](https://github.com/zeroclaw-labs/zeroclaw/pull/9055) fix(docs): make translation refresh reproducible
- [#9183](https://github.com/zeroclaw-labs/zeroclaw/pull/9183) [SANITIZED — possible injection attempt]
- [#8770](https://github.com/zeroclaw-labs/zeroclaw/pull/8770) docs(review): document typed dispatch expectation
- [#9140](https://github.com/zeroclaw-labs/zeroclaw/pull/9140) fix(channels): clear branch-isolated clippy warnings
- [#9141](https://github.com/zeroclaw-labs/zeroclaw/pull/9141) feat(channel/mattermost): add WebSocket listener mode
- [#9145](https://github.com/zeroclaw-labs/zeroclaw/pull/9145) fix(channels): bound ffmpeg transcode waits
- [#9159](https://github.com/zeroclaw-labs/zeroclaw/pull/9159) fix(quickstart): map WhatsApp Web setup to WhatsApp config
- [#8979](https://github.com/zeroclaw-labs/zeroclaw/pull/8979) feat(sop): channel gate prompts with checkpoint edit and revise for deterministic pipelines

### 🐛 New Issues
- [#9247](https://github.com/zeroclaw-labs/zeroclaw/issues/9247) [SANITIZED — possible injection attempt] `bug`
- [#9246](https://github.com/zeroclaw-labs/zeroclaw/issues/9246) RFC: Preserve Todo tracker configuration during ZeroCode ownership migration `config` `type:rfc` `zerocode` `risk:high`
- [#9240](https://github.com/zeroclaw-labs/zeroclaw/issues/9240) save_dirty silently drops every write whose map key contains a dot (gpt-4.1, claude-3.5-sonnet, gemini-1.5-pro)
- [#9239](https://github.com/zeroclaw-labs/zeroclaw/issues/9239) config patch --json still emits anyhow plaintext for two error paths (#6252 incompletely fixed)
- [#9238](https://github.com/zeroclaw-labs/zeroclaw/issues/9238) config_save_isolation architecture gate silently skips every tests/ file on Windows
- [#9237](https://github.com/zeroclaw-labs/zeroclaw/issues/9237) Config::ensure_map_key_for_path leaves a phantom alias behind when the follow-up set_prop fails
- [#9236](https://github.com/zeroclaw-labs/zeroclaw/issues/9236) config set on a fresh channels.telegram.<alias> writes a bot_token-less table that salvage drops on the next load
- [#9235](https://github.com/zeroclaw-labs/zeroclaw/issues/9235) ci: npm audit failed — 2026-07-21 `dependencies` `security` `risk:high`
- [#9231](https://github.com/zeroclaw-labs/zeroclaw/issues/9231) [Bug]: docker runtime cannot run shell commands `bug` `config` `runtime` `security` `tool` `security:docker` `priority:p1` `tool:shell` `status:accepted` `risk:high` 💬1
- [#9228](https://github.com/zeroclaw-labs/zeroclaw/issues/9228) [Follow-up] Eval harness: results dashboard / trend tracking `enhancement` `observability` `tests` `status:accepted` `priority:p3` `follow-up` `risk:medium` `web` 💬1
- [#9227](https://github.com/zeroclaw-labs/zeroclaw/issues/9227) [Follow-up] Eval harness: LLM-judge calibration tooling `enhancement` `config` `provider` `tests` `dev` `status:accepted` `priority:p3` `follow-up` `risk:medium`
- [#9226](https://github.com/zeroclaw-labs/zeroclaw/issues/9226) [Follow-up] Eval harness: memory seeding + memory side-effect graders `enhancement` `config` `memory` `runtime` `security` `tests` `status:accepted` `priority:p3` `follow-up` `risk:high` 💬1

### 🔒 Closed Issues
- [#9086](https://github.com/zeroclaw-labs/zeroclaw/issues/9086) RFC: Structured Security Audit Pipeline — Tamper-Evident Logging, Resilient Upload & Anomaly Detection
- [#9120](https://github.com/zeroclaw-labs/zeroclaw/issues/9120) [Bug]: SOP routing evaluates switch after a false top-level when
- [#7082](https://github.com/zeroclaw-labs/zeroclaw/issues/7082) feat(channel/mattermost): add optional WebSocket listener mode

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,546 · **Open issues:** 1,296 · **Last push:** <1h ago

### 🚀 New Releases
- [ironclaw-v1.0.0-rc.1](https://github.com/nearai/ironclaw/releases/tag/ironclaw-v1.0.0-rc.1) — 1.0.0-rc.1 - 2026-07-20

### ✅ Merged PRs
- [#6116](https://github.com/nearai/ironclaw/pull/6116) feat(reborn): unified generic extension runtime + Option A honest state machine (reconcile main)
- [#6430](https://github.com/nearai/ironclaw/pull/6430) Remove in-memory ratchet stores
- [#6432](https://github.com/nearai/ironclaw/pull/6432) feat(reborn): witness always-present + §5.2.1 origin→gate matrix + dispatch-through-witness (#6396)
- [#6429](https://github.com/nearai/ironclaw/pull/6429) Always compile database backends
- [#6427](https://github.com/nearai/ironclaw/pull/6427) Remove advisory runtime idempotency DTO field
- [#6410](https://github.com/nearai/ironclaw/pull/6410) feat(composition): run the trigger poller on production-shaped runtimes (opt-in) (#5013)
- [#6400](https://github.com/nearai/ironclaw/pull/6400) test(stores): FaultInjecting backend decorator; drive store fault tests through the real store
- [#6405](https://github.com/nearai/ironclaw/pull/6405) Harden legacy migration against real data
- [#6407](https://github.com/nearai/ironclaw/pull/6407) fix(ci): resolve main branch CI failures
- [#6404](https://github.com/nearai/ironclaw/pull/6404) fix(release): synchronize WiX package description

### 🐛 New Issues
- [#6434](https://github.com/nearai/ironclaw/issues/6434) Reborn §5.3.2/§9: seal process re-dispatch — re-mintable process-lifetime authority (continuation model) to delete the loose CapabilityDispatchRequest
- [#6433](https://github.com/nearai/ironclaw/issues/6433) Feature: Dedicated custom instructions / master prompt section `enhancement`
- [#6424](https://github.com/nearai/ironclaw/issues/6424) Agent read_file tool fails on image attachments (PNG) `bug_bash_P2`
- [#6418](https://github.com/nearai/ironclaw/issues/6418) Extension configuration and OAuth flows contain hard-coded English text
- [#6417](https://github.com/nearai/ironclaw/issues/6417) Session check failures silently leave the app in anonymous scope
- [#6416](https://github.com/nearai/ironclaw/issues/6416) Admin user management actions fail without feedback
- [#6394](https://github.com/nearai/ironclaw/issues/6394) Epic: Dogfooding & QA bug fixing 07/20/2026 - 07/24/2026 `bug` `UX / Onboarding` `epic`
- [#6393](https://github.com/nearai/ironclaw/issues/6393) [EPIC] Dogfooding & QA bug fixing `epic`
- [#6389](https://github.com/nearai/ironclaw/issues/6389) Phase 4 (§5.11): collapse build_local_runtime + build_production_shaped into one build_runtime(cfg) 💬10

### 🔒 Closed Issues
- [#6263](https://github.com/nearai/ironclaw/issues/6263) §4.3 final store consolidation: retire InMemoryTurnStateStore (needs Slice 0 oracle + no-livelock evidence)
- [#6396](https://github.com/nearai/ironclaw/issues/6396) Reborn §5.2.1/§9: witness always-present + dispatch-routes-through-witness (authorize() consolidation follow-up)
- [#4533](https://github.com/nearai/ironclaw/issues/4533) Epic: Reborn operator setup, config, diagnostics, and service lifecycle
- [#4597](https://github.com/nearai/ironclaw/issues/4597) [Reborn] Logs query, tail, and follow API with redaction and CLI wrapper
- [#4596](https://github.com/nearai/ironclaw/issues/4596) [Reborn] Operator doctor diagnostics and thin CLI wrapper
- [#3026](https://github.com/nearai/ironclaw/issues/3026) Epic: Reborn production wiring and cutover readiness
- [#2767](https://github.com/nearai/ironclaw/issues/2767) Epic: Separate engine v2 capability background from callable tool schemas
- [#5261](https://github.com/nearai/ironclaw/issues/5261) [EPIC] Reborn capability policy: admin-shared tools & skills with per-user auth (continues #4628)

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,788 · **Open issues:** 93 · **Last push:** 15h ago

### 🐛 New Issues
- [#574](https://github.com/moltis-org/moltis/issues/574) [Feature]: Model Routing Per topic `enhancement` 💬5

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 21h ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 2d ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬10 · 2d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 11d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 12d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬9 · 14d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 15d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 15d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 15d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 22d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Skills](https://www.anthropic.com/news/skills) _2026-07-22_

### OpenAI — 4 new
- [[Partners] Algorithmic Intelligence](https://openai.com/business/partners/algorithmic-intelligence/) _2026-07-21_
- [[Leads] Small Business](https://openai.com/leads/small-business/) _2026-07-21_
- [[Index] Introducing Chatgpt Small Business Program](https://openai.com/index/introducing-chatgpt-small-business-program/) _2026-07-22_
- [[Index] David Velez Robin Vince Join Openai Boards](https://openai.com/index/david-velez-robin-vince-join-openai-boards/) _2026-07-22_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [CEO of Hugging Face: Banning open-source AI would hurt defenders 10x more than attackers, which would make the world 10x more dangerous and this is a good example why!](https://reddit.com/r/LocalLLaMA/comments/1v2g9bc/ceo_of_hugging_face_banning_opensource_ai_would/) ↑2272
- [US gov't lobbied by major US labs is about to ban open source models.](https://reddit.com/r/LocalLLaMA/comments/1v2bf3t/us_govt_lobbied_by_major_us_labs_is_about_to_ban/) ↑1666
- [OpenAI admits responsibility for HuggingFace Attack - an agent from an internal evaluation is reportedly the cause.](https://reddit.com/r/LocalLLaMA/comments/1v2w7jl/openai_admits_responsibility_for_huggingface/) ↑996
- [Anthropic claims local models are stealing from it, meanwhile it pays $1.5B for theft](https://reddit.com/r/LocalLLaMA/comments/1v2ky1e/anthropic_claims_local_models_are_stealing_from/) ↑971
- [Laguna S 2.1 Released: Cheaper than Deepseek v4 Flash, Better than V4 Pro](https://reddit.com/r/LocalLLaMA/comments/1v2pg99/laguna_s_21_released_cheaper_than_deepseek_v4/) ↑628

### r/singularity — top 5 new
- [in a not so distance future](https://reddit.com/r/singularity/comments/1v2ng7a/in_a_not_so_distance_future/) ↑1749
- [New insights into recent DeepMind staff departures](https://reddit.com/r/singularity/comments/1v2ird9/new_insights_into_recent_deepmind_staff_departures/) ↑1588
- [OpenAI's Internal Model Is Responsible This Week's Hugging Face Hack](https://reddit.com/r/singularity/comments/1v2txp7/openais_internal_model_is_responsible_this_weeks/) ↑852
- [Gemini 3.6 Flash benchmarks](https://reddit.com/r/singularity/comments/1v2l6sm/gemini_36_flash_benchmarks/) ↑543
- [Sam Altman to brief Trump admin next week on GPT-6 and its capabilities/potential job impact, according to Bloomberg](https://reddit.com/r/singularity/comments/1v2onp4/sam_altman_to_brief_trump_admin_next_week_on_gpt6/) ↑423

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Is OpenClaw Dead?](https://reddit.com/r/openclaw/comments/1v2o94l/is_openclaw_dead/) ↑249
- [What do you use OpenClaw for? (Actual Use Case)](https://reddit.com/r/openclaw/comments/1v2e5kr/what_do_you_use_openclaw_for_actual_use_case/) ↑25
- [Document creation using claw](https://reddit.com/r/openclaw/comments/1v2m3yw/document_creation_using_claw/) ↑5
- [Best budget friendly configuration for open claw?](https://reddit.com/r/openclaw/comments/1v2b0jn/best_budget_friendly_configuration_for_open_claw/) ↑5
- [Is gogcli insecure?](https://reddit.com/r/openclaw/comments/1v27e0q/is_gogcli_insecure/) ↑4

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
- [congrats!](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
