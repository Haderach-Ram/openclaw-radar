---
layout: post
title: "Ecosystem Digest — 2026-07-03"
date: 2026-07-03 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-07-03
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 381,496 | 9 | 2 | 10 | 1 |
| **hermesagent** | 208,078 | 3 | 0 | 6 | 0 |
| **ZeroClaw** | 32,120 | 7 | 0 | 3 | 0 |
| **IronClaw** | 12,493 | 11 | 3 | 10 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 381,496 · **Open issues:** 6,925 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.7.1-beta.1](https://github.com/openclaw/openclaw/releases/tag/v2026.7.1-beta.1) — openclaw 2026.7.1-beta.1

### ✅ Merged PRs
- [#99303](https://github.com/openclaw/openclaw/pull/99303) test(qa): cover Crabline Zalo transport
- [#99302](https://github.com/openclaw/openclaw/pull/99302) refactor(shared): consolidate remaining channel lazy loaders
- [#99306](https://github.com/openclaw/openclaw/pull/99306) feat(auto-reply): persist ambient room events as transcript rows
- [#99307](https://github.com/openclaw/openclaw/pull/99307) fix(memory-wiki): avoid implicit error coercion
- [#99298](https://github.com/openclaw/openclaw/pull/99298) refactor(shared): consolidate Discord Slack and Telegram lazy loaders
- [#98768](https://github.com/openclaw/openclaw/pull/98768) Allow alternate Zalo Bot API roots
- [#99296](https://github.com/openclaw/openclaw/pull/99296) refactor(shared): consolidate gateway and stateful runtime lazy loaders
- [#99276](https://github.com/openclaw/openclaw/pull/99276) fix(memory-wiki): source imports crash on unreadable pages
- [#99294](https://github.com/openclaw/openclaw/pull/99294) fix(qa): stagger isolated worker startup
- [#98907](https://github.com/openclaw/openclaw/pull/98907) fix(telegram): distinguish and render streamed reasoning/commentary progress lanes

### 🐛 New Issues
- [#99314](https://github.com/openclaw/openclaw/issues/99314) Consolidate unknown-error normalization and serialization `maintainer`
- [#99311](https://github.com/openclaw/openclaw/issues/99311) Account-scoped config changes restart the whole channel, disconnecting every other account 💬1
- [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬2
- [#99288](https://github.com/openclaw/openclaw/issues/99288) Control UI: session-first sidebar, compact context ring, warmer light theme `enhancement` `maintainer` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:fix-shape-clear` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:linked-pr-open` `issue-rating: 🌊 off-meta tidepool` `impact:other` 💬1
- [#99286](https://github.com/openclaw/openclaw/issues/99286) [Bug]: macOS dashboard Web UI: deleting a selected session does nothing and no confirmation dialog appearsIn the Web UI opened from the macOS app dashboard `bug` 💬1
- [#99283](https://github.com/openclaw/openclaw/issues/99283) [Bug]: macOS app rewrites persisted App Group device identity after restart, causing new nodeId and repeated pairing prompts `bug` `regression` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:session-state` `impact:data-loss` `impact:auth-provider` `issue-rating: 🦐 gold shrimp` `maturity:stable` 💬1
- [#99280](https://github.com/openclaw/openclaw/issues/99280) config-health.json legacy-migration warning is permanent and unresolvable (regenerated + compared via raw string equality on every CLI invocation) 💬1
- [#99279](https://github.com/openclaw/openclaw/issues/99279) Mattermost: no inbound bot-identity facts — botLoopProtection can't cover it, bot↔bot loops unguarded `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `clawsweeper:source-repro` `impact:session-state` `impact:security` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1
- [#99277](https://github.com/openclaw/openclaw/issues/99277) Mattermost: ack reactions unimplemented — messages.ackReactionScope is a silent no-op `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:message-loss` `issue-rating: 🦞 diamond lobster` 💬1

### 🔒 Closed Issues
- [#99257](https://github.com/openclaw/openclaw/issues/99257) Persist observed room events as bare transcript rows for durable ambient group awareness
- [#90962](https://github.com/openclaw/openclaw/issues/90962) Telegram: inter-tool commentary clobbers tool progress in non-persist progress mode (diverges from other streaming channels)

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 208,078 · **Open issues:** 25,099 · **Last push:** <1h ago

### ✅ Merged PRs
- [#57455](https://github.com/NousResearch/hermes-agent/pull/57455) fix(desktop): stop macOS Tahoe misplacing the traffic lights
- [#57443](https://github.com/NousResearch/hermes-agent/pull/57443) feat(desktop): cap overlay inner-page width at 75rem
- [#57429](https://github.com/NousResearch/hermes-agent/pull/57429) fix(dump): flag API keys visible only to the shell, not the managed backend
- [#57428](https://github.com/NousResearch/hermes-agent/pull/57428) fix(desktop): extend startup long-timeout to the whole boot data burst (supersedes #48518, #48526)
- [#57423](https://github.com/NousResearch/hermes-agent/pull/57423) fix(webhook): close per-delivery session at the true end of the run
- [#57422](https://github.com/NousResearch/hermes-agent/pull/57422) fix(desktop): let settings content use full pane width

### 🐛 New Issues
- [#57452](https://github.com/NousResearch/hermes-agent/issues/57452) [Bug]: Discord guild mentions ignore pairing-approved users unless the Discord allowlist is populated `type/bug` `comp/gateway` `platform/discord` `area/auth` `P2` `sweeper:risk-security-boundary`
- [#57444](https://github.com/NousResearch/hermes-agent/issues/57444) Desktop app: /background completed tasks never show result panel `type/bug` `duplicate` `tool/delegate` `P3` `comp/desktop` 💬1
- [#57431](https://github.com/NousResearch/hermes-agent/issues/57431) [Feature]: Allow API clients to provide per-request custom tools `type/feature` `comp/gateway` `P3`

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,120 · **Open issues:** 436 · **Last push:** 12h ago

### ✅ Merged PRs
- [#7361](https://github.com/zeroclaw-labs/zeroclaw/pull/7361) feat(rfc-6969): per-turn output routing via send_via + voice delivery fixes
- [#8465](https://github.com/zeroclaw-labs/zeroclaw/pull/8465) fix(cron): thread CancellationToken through cron::run for explicit shutdown
- [#8606](https://github.com/zeroclaw-labs/zeroclaw/pull/8606) fix(config): guard the real config.toml against agent self-modification in nested layouts

### 🐛 New Issues
- [#8632](https://github.com/zeroclaw-labs/zeroclaw/issues/8632) [Bug]: Source install with embedded-web fails before generated web API client exists `bug`
- [#8631](https://github.com/zeroclaw-labs/zeroclaw/issues/8631) [Bug]: headless deterministic SOP steps recorded Completed without executing 💬1
- [#8627](https://github.com/zeroclaw-labs/zeroclaw/issues/8627) [Bug]: WhatsApp Web (whatsapp-web) device linking broken by WhatsApp's new passkey/SHORTCAKE companion-linking gate `bug`
- [#8626](https://github.com/zeroclaw-labs/zeroclaw/issues/8626) [Feature]: zerocode receives the full RPC spec from the daemon and validates against it `enhancement`
- [#8615](https://github.com/zeroclaw-labs/zeroclaw/issues/8615) [Bug]: compatible provider silently deletes content via unconditional `<think>` tag stripping `bug` `provider` `provider:compatible` `priority:p2` `status:accepted` `risk:medium` 💬1
- [#8603](https://github.com/zeroclaw-labs/zeroclaw/issues/8603) RFC: OpenAI Chat Completions compatibility adapter `gateway` `runtime` `domain:architecture` `priority:p2` `needs-maintainer-review` `type:rfc` `risk:high` 💬1
- [#8602](https://github.com/zeroclaw-labs/zeroclaw/issues/8602) [Feature]: Enhance file_read — default line cap, charset detection, paged PDF, notebook awareness, chunked binary `enhancement` `runtime` `tool` `priority:p2` `tool:file` `needs-maintainer-review` `risk:high` 💬1

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,493 · **Open issues:** 1,282 · **Last push:** <1h ago

### ✅ Merged PRs
- [#5548](https://github.com/nearai/ironclaw/pull/5548) test(reborn): C-TRACECAP + C-ATTACH — turn-event sink and attachment read-port coverage
- [#5573](https://github.com/nearai/ironclaw/pull/5573) [codex] fix exa mcp sse initialize parsing
- [#5559](https://github.com/nearai/ironclaw/pull/5559) scripts: enforce architecture sprawl checks
- [#5547](https://github.com/nearai/ironclaw/pull/5547) test(reborn): PR-C2 Tier-2 coverage — skill/durable/errors (C-SKILL, C-DURABLE, C-ERRORS)
- [#5526](https://github.com/nearai/ironclaw/pull/5526) fix(reborn-tests): resolve one-runtime owner-scope gap for multi-actor groups (E-MULTIUSER)
- [#5543](https://github.com/nearai/ironclaw/pull/5543) [codex] refresh Reborn agent guidance
- [#5549](https://github.com/nearai/ironclaw/pull/5549) [codex] Dedup WASM resource limiter
- [#5560](https://github.com/nearai/ironclaw/pull/5560) test(reborn): explain green WebUI v2 live QA runs
- [#5534](https://github.com/nearai/ironclaw/pull/5534) [codex] instrument first-party tool latency
- [#5515](https://github.com/nearai/ironclaw/pull/5515) fix(reborn): scheduled-trigger fires cannot create/mutate triggers (#5505)

### 🐛 New Issues
- [#5572](https://github.com/nearai/ironclaw/issues/5572) reborn: HookedLoopCheckpointPort does not forward stage_checkpoint_payload/load_checkpoint_payload — any hooks-enabled coordinator turn fails at Checkpoint stage
- [#5570](https://github.com/nearai/ironclaw/issues/5570) feat(reborn): stable OAuth auth-relay callback so every PR preview can test Google SSO `enhancement` `reborn`
- [#5558](https://github.com/nearai/ironclaw/issues/5558) Vision model hallucinates image contents and accepts false user corrections `bug_bash_P2`
- [#5557](https://github.com/nearai/ironclaw/issues/5557) Logs deep link requires opening twice to load selected conversation `bug_bash_P3`
- [#5556](https://github.com/nearai/ironclaw/issues/5556) Active chat remains highlighted in sidebar after navigating away `bug_bash_P3`
- [#5555](https://github.com/nearai/ironclaw/issues/5555) Terminal floating button overlaps chat composer `bug_bash_P2`
- [#5554](https://github.com/nearai/ironclaw/issues/5554) Mobile chat layout breaks with horizontal overflow `bug_bash_P2`
- [#5553](https://github.com/nearai/ironclaw/issues/5553) Approval notifications disappear instead of remaining in notification history `bug_bash_P2`
- [#5552](https://github.com/nearai/ironclaw/issues/5552) Run fails with generic "invalid result" after multiple tool failures `bug_bash_P2` 💬1
- [#5551](https://github.com/nearai/ironclaw/issues/5551) Automation posts intermediate progress message to Slack instead of final result `bug_bash_P2`
- [#5537](https://github.com/nearai/ironclaw/issues/5537) Daily ironclaw failure taxonomy — 2026-07-02

### 🔒 Closed Issues
- [#5571](https://github.com/nearai/ironclaw/issues/5571) web-access.search fails on Railway QA (Exa upstream IP throttling) — invalid_output aborts entire turn, cascades across 5 cases
- [#5479](https://github.com/nearai/ironclaw/issues/5479) Reborn one-runtime group harness: second thread with a distinct actor fails (driver_unavailable / unknown thread) — blocks E-MULTIUSER/C-MULTIUSER
- [#5505](https://github.com/nearai/ironclaw/issues/5505) [QA] Routine creation prompt is embedded inside the created routine

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬2 · <1h ago
- 🟢 [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬2 · 2d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 3d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 3d ago
- ⚫ [#94780](https://github.com/openclaw/openclaw/issues/94780) [Feature]: Per-cron model selection independent of agent default — run cheap/free models on automation jobs while keeping main agent on premium LLM — 💬1 · 7d ago
- ⚫ [#93032](https://github.com/openclaw/openclaw/issues/93032) [Bug] v2026.6.6: Cron scheduler loads 0 jobs after upgrade — SQLite WAL not committed at first startup — 💬2 · 7d ago
- ⚫ [#92974](https://github.com/openclaw/openclaw/issues/92974) Bug: v2026.6.6 getAttributionHeaders() crashes on Bedrock models — baseUrl undefined (null-guard missing) — 💬1 · 7d ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬4 · 9d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬7 · 10d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬1 · 11d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 1 new
- [[News] Fable Safeguards Jailbreak Framework](https://www.anthropic.com/news/fable-safeguards-jailbreak-framework) _2026-07-03_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Palantir CEO rages against closed models](https://reddit.com/r/LocalLLaMA/comments/1ulb4nx/palantir_ceo_rages_against_closed_models/) ↑911
- [Talking with Gemma 4 31B!](https://reddit.com/r/LocalLLaMA/comments/1ulgwld/talking_with_gemma_4_31b/) ↑672
- [It's officially over. One of the fathers of AI at Nvidia doesn't believe in AGI and compares OpenAI and Anthropic's closed models to AOL and Prodigy's closed internets. Says the future is every busine](https://reddit.com/r/LocalLLaMA/comments/1ult0f4/its_officially_over_one_of_the_fathers_of_ai_at/) ↑478
- [Z.ai launches ZCode to challenge Cursor, Claude Code and GitHub Copilot in AI coding](https://reddit.com/r/LocalLLaMA/comments/1ulfpfo/zai_launches_zcode_to_challenge_cursor_claude/) ↑203
- [Kimi K2.7 Code is generally available in GitHub Copilot](https://reddit.com/r/LocalLLaMA/comments/1ulm1gt/kimi_k27_code_is_generally_available_in_github/) ↑128

### r/singularity — top 3 new
- [Anthropic guardrails does it again](https://reddit.com/r/singularity/comments/1ulizqk/anthropic_guardrails_does_it_again/) ↑2161
- [Anthropic is now after Pharma](https://reddit.com/r/singularity/comments/1ulueu6/anthropic_is_now_after_pharma/) ↑470
- [Hierarchos: Preliminary Findings From a 232M Recurrent Memory-Augmented Assistant Model [P]](https://reddit.com/r/singularity/comments/1um12hd/hierarchos_preliminary_findings_from_a_232m/) ↑3

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [How we respond matters](https://reddit.com/r/openclaw/comments/1ulvzgl/how_we_respond_matters/) ↑12
- [AI Agent - but it functions like a old school gaming console...](https://reddit.com/r/openclaw/comments/1ulujo5/ai_agent_but_it_functions_like_a_old_school/) ↑6
- [How do you voice chat with your Agent?](https://reddit.com/r/openclaw/comments/1ulw3sq/how_do_you_voice_chat_with_your_agent/) ↑2
- [Updated openclaw, broke my project I spent a week on. Can anyone identify an error / solution?](https://reddit.com/r/openclaw/comments/1ulixsh/updated_openclaw_broke_my_project_i_spent_a_week/) ↑2
- [Claude CLI - Sonnet 5? Or stick to 4.6?](https://reddit.com/r/openclaw/comments/1ukl858/claude_cli_sonnet_5_or_stick_to_46/) ↑2

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
- [Thank you, 
@colinsolvely
, for helping move the needed iOS and Android UI improvements forward with this post.

We want](https://x.com/openclaw) ↑0 🔁0 · recent


### X — @steipete
- [yes](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
