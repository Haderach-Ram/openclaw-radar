---
layout: post
title: "Ecosystem Digest — 2026-08-22"
date: 2026-08-22 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-08-22
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 387,050 | 8 | 3 | 10 | 0 |
| **hermesagent** | 234,011 | 8 | 7 | 4 | 1 |
| **ZeroClaw** | 32,633 | 11 | 8 | 7 | 0 |
| **IronClaw** | 12,599 | 11 | 4 | 10 | 0 |
| **Moltis** | 2,832 | 2 | 0 | 1 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 387,050 · **Open issues:** 6,183 · **Last push:** <1h ago

### ✅ Merged PRs
- [#126424](https://github.com/openclaw/openclaw/pull/126424) fix(gateway): keep conversation delivery within agent bindings
- [#127469](https://github.com/openclaw/openclaw/pull/127469) fix(memory): respect provenance in automatic context
- [#127343](https://github.com/openclaw/openclaw/pull/127343) fix(release): preserve validation plan across reruns
- [#127738](https://github.com/openclaw/openclaw/pull/127738) fix(ui): align page titles with page content
- [#127744](https://github.com/openclaw/openclaw/pull/127744) improve(gateway): reduce health snapshot session work
- [#127734](https://github.com/openclaw/openclaw/pull/127734) fix(config): match the config directory through symlinks when diagnosing permissions
- [#127740](https://github.com/openclaw/openclaw/pull/127740) fix(ui): stop empty protected secrets before Gateway save
- [#127737](https://github.com/openclaw/openclaw/pull/127737) fix: current chat attachments fail after send acknowledgement
- [#127739](https://github.com/openclaw/openclaw/pull/127739) fix(agents): preserve authoritative child completion results
- [#127727](https://github.com/openclaw/openclaw/pull/127727) [SANITIZED — possible injection attempt]

### 🐛 New Issues
- [#127756](https://github.com/openclaw/openclaw/issues/127756) [Bug]: Build validation spends minutes rescanning emitted runtime artifacts `maintainer`
- [#127753](https://github.com/openclaw/openclaw/issues/127753) Long open code fences stall streaming updates in the Control UI `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬2
- [#127747](https://github.com/openclaw/openclaw/issues/127747) Long streaming responses stall the Control UI on each update `maintainer` 💬1
- [#127743](https://github.com/openclaw/openclaw/issues/127743) [Bug]: Expired sessions.catalog.list cache blocks Control UI on slow external catalog scans `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#127742](https://github.com/openclaw/openclaw/issues/127742) skill_usage is never populated, so the skill curator never archives anything and workspace skills grow unbounded `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#127728](https://github.com/openclaw/openclaw/issues/127728) [Bug]: Remote extension pairing: gateway rejects browser.request ~10ms after starting the relay, before the extension can attach `bug` `no-stale` `bug:behavior` `P1` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` 💬3
- [#127710](https://github.com/openclaw/openclaw/issues/127710) prepared-model-runtime fails closed on transient generation churn: one fingerprint drift permanently wedges the gateway; owner-commit race silently drops messages `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:message-loss` `issue-rating: 🐚 platinum hermit` 💬2
- [#127702](https://github.com/openclaw/openclaw/issues/127702) [Bug]: Discord set-presence fails from main:main when default accountId is omitted `bug` `no-stale` `bug:behavior` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:other` `maturity:stable` 💬3

### 🔒 Closed Issues
- [#71066](https://github.com/openclaw/openclaw/issues/71066) Telegram subsystem: getUpdates polling silently non-functional despite reachable API
- [#127741](https://github.com/openclaw/openclaw/issues/127741) Session-store writes reload and deep-clone the entire store, causing multi-minute event-loop stalls
- [#127736](https://github.com/openclaw/openclaw/issues/127736) [Bug]: Session persistence failure: user messages lost across days, 4x reproduced, Gateway restart ineffective

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 234,011 · **Open issues:** 34,413 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.8.19](https://github.com/NousResearch/hermes-agent/releases/tag/v2026.8.19) — Hermes Agent v0.20.5 (v2026.8.19)

### ✅ Merged PRs
- [#91869](https://github.com/NousResearch/hermes-agent/pull/91869) fix(update): Windows venv-holder guard names holders correctly and can see the gateway it must pause (#90778, #87594 — proven live on windows-latest)
- [#91915](https://github.com/NousResearch/hermes-agent/pull/91915) feat(bot-mode): @mentions identify who you mean — the agent composes and sends, the renderer never delivers
- [#91921](https://github.com/NousResearch/hermes-agent/pull/91921) feat(desktop): cloud-agent-down boot failures get actionable recovery (#85335, salvage #85373)
- [#91936](https://github.com/NousResearch/hermes-agent/pull/91936) fix(telegram): omit topic routing from rich edits

### 🐛 New Issues
- [#91997](https://github.com/NousResearch/hermes-agent/issues/91997) Desktop speak-stream falls back to whole-text POST for Edge TTS — long replies wait for full synthesis before any audio `type/bug` `duplicate` `tool/tts` `P2` `comp/desktop` `area/streaming` 💬1
- [#91996](https://github.com/NousResearch/hermes-agent/issues/91996) [Bug]: delegation live transcripts resolve HERMES_HOME after a thread hop and can write to another profile `type/bug` `comp/tools` `tool/delegate` `P2` `sweeper:risk-session-state` `area/profiles`
- [#91995](https://github.com/NousResearch/hermes-agent/issues/91995) [Bug] OpenViking plugin uses uid-less viking://user/<segment> URIs that upstream removed in #4196 — will 400 on next OV release `type/bug` `comp/plugins` `tool/memory` `P3` `area/memory`
- [#91991](https://github.com/NousResearch/hermes-agent/issues/91991) Spoken reply jumps back — reads old reply from several turns ago during hands-free voice conversation (after barge-in) `type/bug` `tool/tts` `P2` `comp/desktop` `platform/windows`
- [#91987](https://github.com/NousResearch/hermes-agent/issues/91987) Hands-free voice conversation doesn't release microphone after 'stop' — wake word unresponsive until app restart `type/bug` `tool/tts` `P2` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows`
- [#91980](https://github.com/NousResearch/hermes-agent/issues/91980) fix(approvals): approval prompts delivered onto a disconnected client transport time out silently — no birth log, no retry, no fallback channel `type/bug` `comp/tui` `P2` `sweeper:risk-session-state` `sweeper:risk-message-delivery`
- [#91976](https://github.com/NousResearch/hermes-agent/issues/91976) A2A v1.0 conformance: outbound results never use data Parts; protocolBinding is a bare string; skills carry no I/O modes (0.20.4) `type/bug` `comp/plugins` `P3`
- [#91969](https://github.com/NousResearch/hermes-agent/issues/91969) Unbounded Telegram flood-control sleep on the boot path freezes inbound on ALL platforms for the full penalty (97 min observed) `type/bug` `comp/gateway` `comp/plugins` `platform/telegram` `P1` `sweeper:risk-session-state` `sweeper:risk-message-delivery`

### 🔒 Closed Issues
- [#78089](https://github.com/NousResearch/hermes-agent/issues/78089) Windows: venv-blocker preflight still aborts desktop Update for .hermes-runtime gateways — cmdline truncated at 120 chars defeats the pausable-gateway exemption added by #75881
- [#87594](https://github.com/NousResearch/hermes-agent/issues/87594) Windows: `hermes update` spawned from the gateway's own /update command can't pause the gateway — ancestor-exclusion in `_scan_gateway_pids` excludes the gateway itself
- [#90778](https://github.com/NousResearch/hermes-agent/issues/90778) Windows venv-holder message mislabels `hermes dashboard` as the Desktop backend, and matches subcommands by substring
- [#91105](https://github.com/NousResearch/hermes-agent/issues/91105) Bot-to-bot @mention messages silently drop after v0.20.4 update (composer middleware still uses unsafe -q instead of --query-file)
- [#91397](https://github.com/NousResearch/hermes-agent/issues/91397) [Bug]: fix(desktop) remote @mention delivery forwards the routing token in the body, so the recipient re-routes instead of answering
- [#85335](https://github.com/NousResearch/hermes-agent/issues/85335) Desktop: cloud agent 503/backend unreachable produces non-actionable boot-loop with opaque error
- [#85974](https://github.com/NousResearch/hermes-agent/issues/85974) [Setup]: Confusing Blind Updating Process

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,633 · **Open issues:** 795 · **Last push:** <1h ago

### ✅ Merged PRs
- [#10174](https://github.com/zeroclaw-labs/zeroclaw/pull/10174) test(ci): verify release tools on native runners
- [#10095](https://github.com/zeroclaw-labs/zeroclaw/pull/10095) ci(docker): enforce non-root production image
- [#10092](https://github.com/zeroclaw-labs/zeroclaw/pull/10092) fix(providers): redact Anthropic credential fragments
- [#10150](https://github.com/zeroclaw-labs/zeroclaw/pull/10150) fix(zerocode): accept paste during active turns
- [#9715](https://github.com/zeroclaw-labs/zeroclaw/pull/9715) fix(infra): make JSONL session migration retry-safe
- [#10107](https://github.com/zeroclaw-labs/zeroclaw/pull/10107) fix(channels): keep Google STT API keys out of URLs
- [#10033](https://github.com/zeroclaw-labs/zeroclaw/pull/10033) fix(config): source channel Rust defaults from their serde defaults

### 🐛 New Issues
- [#10238](https://github.com/zeroclaw-labs/zeroclaw/issues/10238) [Bug]: ZeroCode shows stale Connected state after daemon exits `bug` `priority:p2` `zerocode`
- [#10237](https://github.com/zeroclaw-labs/zeroclaw/issues/10237) [Bug]: Telegram reply-threads fragment conversation memory into per-thread history buckets
- [#10235](https://github.com/zeroclaw-labs/zeroclaw/issues/10235) [Docs]: update SECURITY.md distroless base to Debian 13 `docs` `security:docker` `domain:security` `priority:p2` `risk:low` `type:docs`
- [#10232](https://github.com/zeroclaw-labs/zeroclaw/issues/10232) [Bug]: Daemon diagnostics drop the underlying error chain `bug` `daemon` `observability` `runtime` `observability:log` `priority:p2` `status:accepted` `follow-up` `risk:medium`
- [#10231](https://github.com/zeroclaw-labs/zeroclaw/issues/10231) [Bug]: Channels supervisor retries stale configuration `bug` `channel` `config` `daemon` `runtime` `priority:p1` `r:needs-repro` `risk:high`
- [#10230](https://github.com/zeroclaw-labs/zeroclaw/issues/10230) [Bug]: Daemon startup or reload can overflow during agent initialization `bug` `daemon` `priority:p1` `r:needs-repro` `quickstart` `zerocode` `risk:high` 💬2
- [#10225](https://github.com/zeroclaw-labs/zeroclaw/issues/10225) [Bug]: ZeroCode RPC sessions cannot reach configured channels through channel-backed tools `bug` `channel` `runtime` `tool` `priority:p1` `status:accepted` `zerocode` `risk:high`
- [#10224](https://github.com/zeroclaw-labs/zeroclaw/issues/10224) [Bug]: Custom provider 5xx errors are logged as duplicated escaped JSON `bug` `observability` `provider` `provider:compatible` `priority:p2` `status:accepted` `follow-up` `risk:medium`
- [#10223](https://github.com/zeroclaw-labs/zeroclaw/issues/10223) [Bug]: ZeroCode drops Ctrl+C and blocks input while reconnecting during an active turn `bug` `priority:p1` `status:accepted` `follow-up` `risk:medium` `zerocode`
- [#10222](https://github.com/zeroclaw-labs/zeroclaw/issues/10222) [Feature]: Add opt-in single-tool provider rounds for interactive agents `enhancement` `agent` `provider` `runtime` `tool` `domain:architecture` `priority:p2` `needs-maintainer-review` `risk:medium`
- [#10212](https://github.com/zeroclaw-labs/zeroclaw/issues/10212) [Docs]: document `switch` and its routing precedence in sop/syntax.md `docs` `tool:sop` `priority:p3` `risk:low` `type:docs`

### 🔒 Closed Issues
- [#10159](https://github.com/zeroclaw-labs/zeroclaw/issues/10159) [Task]: Verify pinned release tools on native Linux and Windows runners
- [#10074](https://github.com/zeroclaw-labs/zeroclaw/issues/10074) SECURITY.md documents a CI job that was removed in April, so the container checks are convention now
- [#9976](https://github.com/zeroclaw-labs/zeroclaw/issues/9976) bug(provider): stop logging Anthropic credential fragments
- [#9925](https://github.com/zeroclaw-labs/zeroclaw/issues/9925) [Bug]: model thinking output sometimes leaks to daemon stdiout
- [#9832](https://github.com/zeroclaw-labs/zeroclaw/issues/9832) zeroclaw-hardware fails to compile with --features hardware: unresolved import aardvark_sys::AardvarkHandle
- [#10089](https://github.com/zeroclaw-labs/zeroclaw/issues/10089) [Bug]: ZeroCode ignores paste while an agent turn is running
- [#9315](https://github.com/zeroclaw-labs/zeroclaw/issues/9315) [Feature]: classify Telegram file-download failures as permanent or transient by HTTP status
- [#9614](https://github.com/zeroclaw-labs/zeroclaw/issues/9614) [Bug]: Channel Rust defaults disagree with serde approval timeouts for generated aliases

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,599 · **Open issues:** 1,524 · **Last push:** <1h ago

### ✅ Merged PRs
- [#7804](https://github.com/nearai/ironclaw/pull/7804) fix(workspace): honor IRONCLAW_REBORN_WORKSPACE_ROOT on 1.3
- [#7797](https://github.com/nearai/ironclaw/pull/7797) docs(guidance): repo-wide agent-guidance audit — fix drift, prune 21.5k lines, consolidate tests/ onto AGENTS.md convention
- [#7803](https://github.com/nearai/ironclaw/pull/7803) fix(telegram): keep paired channels ready and collapse reply drafts
- [#7805](https://github.com/nearai/ironclaw/pull/7805) fix(ci): forward-port the clippy 1.98 lint fixes to 1.3
- [#7796](https://github.com/nearai/ironclaw/pull/7796) fix(sandbox): preserve failed Railway audit appends
- [#7699](https://github.com/nearai/ironclaw/pull/7699) feat(notifications): publish actionable run gates
- [#7766](https://github.com/nearai/ironclaw/pull/7766) fix(telegram): separate bot pairing from personal device linking
- [#7779](https://github.com/nearai/ironclaw/pull/7779) feat(sandbox): route user-sandbox egress through a managed per-user proxy (#7732 Step 2)
- [#7787](https://github.com/nearai/ironclaw/pull/7787) chore(agents): refresh codebase knowledge graph
- [#7791](https://github.com/nearai/ironclaw/pull/7791) fix(llm): preserve OpenAI-compatible reasoning-only responses

### 🐛 New Issues
- [#7813](https://github.com/nearai/ironclaw/issues/7813) UI: heading gets cropped when the suggestions panel appears
- [#7812](https://github.com/nearai/ironclaw/issues/7812) Onboarding suggestions: respect user-level tool permissions, generate with read-only tool access
- [#7808](https://github.com/nearai/ironclaw/issues/7808) Memory write path: redaction + taint metadata required before any external provider binds `bug`
- [#7801](https://github.com/nearai/ironclaw/issues/7801) CI expedite T4: canonical preflight — one gate list, worktree-safe hooks, self-printing REPRO 💬3
- [#7800](https://github.com/nearai/ironclaw/issues/7800) CI expedite T3: PR/queue convergence — planner drift guard, default-features clippy, frontend dedup 💬2
- [#7799](https://github.com/nearai/ironclaw/issues/7799) CI expedite T2: nextest pipeline, full-failure signal, PR unthrottle, measured test consolidation 💬3
- [#7798](https://github.com/nearai/ironclaw/issues/7798) CI expedite T1: setup-rust composite — toolchain pin, mold, centralized build profiles 💬2
- [#7793](https://github.com/nearai/ironclaw/issues/7793) Migrate remaining Settings and Admin feedback banners to InlineNotice
- [#7792](https://github.com/nearai/ironclaw/issues/7792) Introduce shared page-shell and loading primitives
- [#7687](https://github.com/nearai/ironclaw/issues/7687) Generalize the WebUI notification center into a durable user inbox `epic`
- [#7664](https://github.com/nearai/ironclaw/issues/7664) Pluggable memory over MCP: wire the provider, land Mnesis as first consumer, publish the contract `enhancement` 💬2

### 🔒 Closed Issues
- [#7690](https://github.com/nearai/ironclaw/issues/7690) Publish approval, authentication, and blocked-run notifications to the user inbox
- [#7715](https://github.com/nearai/ironclaw/issues/7715) Telegram connection flow lacks consent/selection between bot and personal account
- [#7689](https://github.com/nearai/ironclaw/issues/7689) Generalize the WebUI notification center and consume the server-backed inbox
- [#7783](https://github.com/nearai/ironclaw/issues/7783) LLM timeout policy: finalization can't measure TTFT, and the retry budget can't fit the deadline

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,832 · **Open issues:** 90 · **Last push:** 21h ago

### ✅ Merged PRs
- [#1220](https://github.com/moltis-org/moltis/pull/1220) fix(whatsapp): render Markdown in outbound messages

### 🐛 New Issues
- [#1224](https://github.com/moltis-org/moltis/issues/1224) [Bug]: Tools stop working in shared Slack channels `bug`
- [#1223](https://github.com/moltis-org/moltis/issues/1223) heartbeat active_hours has no effect on a default config

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 3h ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬2 · 22h ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬4 · 4d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 9d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 12d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 15d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 17d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 19d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 21d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 21d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### OpenAI — 2 new
- [[Partners] Quantium](https://openai.com/business/partners/quantium/) _2026-08-21_
- [[Partners] Tcs](https://openai.com/business/partners/tcs/) _2026-08-21_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 2 new
- [Qwen3.8-27B Q6 is a beast at agentic coding](https://reddit.com/r/LocalLLaMA/comments/1vuotqr/qwen3827b_q6_is_a_beast_at_agentic_coding/) ↑288
- [Qwen3.8-27B different thinking levels](https://reddit.com/r/LocalLLaMA/comments/1vusds8/qwen3827b_different_thinking_levels/) ↑114

### r/singularity — top 2 new
- [NVIDIA’s coding agent scored 100% on ARC-AGI-3 interactive reasoning benchmark](https://reddit.com/r/singularity/comments/1vuhlhn/nvidias_coding_agent_scored_100_on_arcagi3/) ↑972
- [Hello Qwen... I mean Claude... I mean Qwen...](https://reddit.com/r/singularity/comments/1vutyjz/hello_qwen_i_mean_claude_i_mean_qwen/) ↑127

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Ox-Alpha/chinese models with openclaw?](https://reddit.com/r/openclaw/comments/1vur0m7/oxalphachinese_models_with_openclaw/) ↑2
- [Any Maintainers in here, Or anyone with an older OpenClaw-iOS.ipa care to share?](https://reddit.com/r/openclaw/comments/1vu3vvz/any_maintainers_in_here_or_anyone_with_an_older/) ↑2
- [Just a lucky prediction?](https://reddit.com/r/openclaw/comments/1vux4nw/just_a_lucky_prediction/) ↑1
- [Muse Spark 1.2 Contributor Cache not working well?](https://reddit.com/r/openclaw/comments/1vudz9x/muse_spark_12_contributor_cache_not_working_well/) ↑1
- [Beste Hardware für Open Claw](https://reddit.com/r/openclaw/comments/1vubgpa/beste_hardware_für_open_claw/) ↑0

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
- [I had the pleasure of speaking at the Agentic AI Summit in Berkeley alongside an incredible bunch of folks. My talk was ](https://x.com/steipete/status/2090898421108605078) ↑0 🔁0 · recent
- [Can’t wait to show you all what we been cookin’!](https://x.com/steipete/status/2090162595257102731) ↑0 🔁0 · recent
- [512GB RAM Studios. Apple was good to us.](https://x.com/steipete/status/2089877190422974974) ↑0 🔁0 · recent
- [pssst, you wake the cli people that will give you $reasons why this can’t work.

I was one of them before I saw the ligh](https://x.com/steipete/status/2089804281331548280) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
