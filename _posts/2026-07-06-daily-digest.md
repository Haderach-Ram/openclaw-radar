---
layout: post
title: "Ecosystem Digest — 2026-07-06"
date: 2026-07-06 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-07-06
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 381,839 | 6 | 6 | 10 | 1 |
| **hermesagent** | 209,710 | 10 | 4 | 6 | 0 |
| **ZeroClaw** | 32,163 | 7 | 5 | 10 | 0 |
| **IronClaw** | 12,497 | 3 | 1 | 3 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 381,839 · **Open issues:** 6,568 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.7.1-beta.2](https://github.com/openclaw/openclaw/releases/tag/v2026.7.1-beta.2) — openclaw 2026.7.1-beta.2

### ✅ Merged PRs
- [#100482](https://github.com/openclaw/openclaw/pull/100482) fix(ollama): fall back when native streams end early
- [#97733](https://github.com/openclaw/openclaw/pull/97733) feat: add channel pairing request hook
- [#100434](https://github.com/openclaw/openclaw/pull/100434) feat(ui): preview GitHub issues and pull requests on hover
- [#100512](https://github.com/openclaw/openclaw/pull/100512) fix(ios): keep While Using selected after approval
- [#100505](https://github.com/openclaw/openclaw/pull/100505) fix(gateway): advertise exec approval node commands
- [#96917](https://github.com/openclaw/openclaw/pull/96917) fix(anthropic): keep OAuth callback on loopback
- [#100545](https://github.com/openclaw/openclaw/pull/100545) docs(changelog): credit landed reliability fixes
- [#100536](https://github.com/openclaw/openclaw/pull/100536) fix(agents): skip tool prep for toolless models
- [#98262](https://github.com/openclaw/openclaw/pull/98262) [codex] Fail closed pair slash command routing
- [#99564](https://github.com/openclaw/openclaw/pull/99564) fix(agents): prevent malformed HTML entities from breaking tool calls

### 🐛 New Issues
- [#100556](https://github.com/openclaw/openclaw/issues/100556) Codex-OAuth models fail over incorrectly — sibling model with healthy per-model quota still drops to non-codex fallback
- [#100547](https://github.com/openclaw/openclaw/issues/100547) [Feature]: Should OpenClaw support runtime safety classification alongside ClawScan?
- [#100538](https://github.com/openclaw/openclaw/issues/100538) [Feature]: Telegram onboarding: offer BotFather web app flow next to the chat flow `enhancement` `maintainer` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-product-decision` `clawsweeper:linked-pr-open` `issue-rating: 🌊 off-meta tidepool` `maturity:stable` `impact:ux-friction` 💬1
- [#100537](https://github.com/openclaw/openclaw/issues/100537) [Bug]: active-memory embedded run cannot resolve Lossless Claw lcm_* tools despite runtime plugin inspect showing them registered `bug` `regression` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `impact:session-state` `issue-rating: 🐚 platinum hermit` `maturity:stable` `impact:ux-friction` 💬1
- [#100534](https://github.com/openclaw/openclaw/issues/100534) Automatic git worktree management for agent tasks `maintainer` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `clawsweeper:linked-pr-open` `issue-rating: 🦞 diamond lobster` `impact:other` 💬1
- [#100529](https://github.com/openclaw/openclaw/issues/100529) Tool-result pruning silently omits results (reads as 'empty output'); maxActiveTranscriptBytes silently no-ops without truncateAfterCompaction `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:session-state` `impact:message-loss` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#100460](https://github.com/openclaw/openclaw/issues/100460) [Bug]:Ollama "stream ended without a final response" errors are not failover-eligible, causing dead-end failures with no fallback
- [#100412](https://github.com/openclaw/openclaw/issues/100412) Control UI: preview GitHub issues and pull requests on hover
- [#100477](https://github.com/openclaw/openclaw/issues/100477) [Bug]: macOS app leaks orphaned SSH tunnel processes; PortGuardian never reaps them and they squat the preferred local port
- [#97578](https://github.com/openclaw/openclaw/issues/97578) [Bug]: OpenClaw CLI should handle node lacks exec approvals capability gracefully
- [#57775](https://github.com/openclaw/openclaw/issues/57775) Windows headless node host supports exec approvals via CLI, but nodes describe / Control UI do not advertise system.execApprovals.get/set
- [#98239](https://github.com/openclaw/openclaw/issues/98239) [Bug]: /pair qr can change gateway.bind and break Tailscale Serve webchat

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 209,710 · **Open issues:** 26,022 · **Last push:** <1h ago

### ✅ Merged PRs
- [#59204](https://github.com/NousResearch/hermes-agent/pull/59204) fix(desktop): probe the venv python before trusting it so Repair can escape a broken venv
- [#59210](https://github.com/NousResearch/hermes-agent/pull/59210) fix(prompt-size): pass platform-resolved toolsets into the inspection agent
- [#59222](https://github.com/NousResearch/hermes-agent/pull/59222) fix(mcp): reconnect resilience — reset budget per healthy session, self-probe parked servers, re-register tools on revival (salvage #57615, #54139, #57477)
- [#59219](https://github.com/NousResearch/hermes-agent/pull/59219) fix(mcp): honor per-server connect_timeout in CLI/GUI probes (salvage #34276, #56699, #54494)
- [#58899](https://github.com/NousResearch/hermes-agent/pull/58899) refactor: consolidate gateway session metadata into state.db
- [#58801](https://github.com/NousResearch/hermes-agent/pull/58801) fix(computer-use): name the wedged startup phase in the session ready-timeout error

### 🐛 New Issues
- [#59293](https://github.com/NousResearch/hermes-agent/issues/59293) [SANITIZED — possible injection attempt] `type/security` `comp/cli` `area/auth` `P3` `sweeper:risk-security-boundary`
- [#59291](https://github.com/NousResearch/hermes-agent/issues/59291) Tool-call-shaped JSON envelope leaks into Telegram output when a local model emits it as assistant text `type/bug` `comp/agent` `platform/telegram` `provider/ollama` `P2` `sweeper:risk-message-delivery`
- [#59290](https://github.com/NousResearch/hermes-agent/issues/59290) Gateway systemd unit races DNS at boot — transient name-resolution failures for Telegram and HTTP MCP servers `type/bug` `comp/gateway` `area/config` `P3`
- [#59289](https://github.com/NousResearch/hermes-agent/issues/59289) hermes dashboard has no service installer — add --install-service to match the gateway `type/feature` `comp/cli` `P3` `comp/dashboard`
- [#59288](https://github.com/NousResearch/hermes-agent/issues/59288) Update can wipe web_dist, and --skip-build hard-fails when it's missing — auto-rebuild or ship the prebuilt dashboard UI `type/bug` `comp/cli` `P2` `comp/dashboard`
- [#59286](https://github.com/NousResearch/hermes-agent/issues/59286) [Bug]: terminal env_passthrough not honored by Daytona backend — allowlisted env never reaches the sandbox `type/bug` `backend/daytona` `tool/terminal` `area/config` `P2` `bug`
- [#59283](https://github.com/NousResearch/hermes-agent/issues/59283) Gemini OpenAI-compat: extra_body.google.thinking_config double-nested (400, surfaced as generic empty response) `type/bug` `comp/agent` `provider/gemini` `P2`
- [#59277](https://github.com/NousResearch/hermes-agent/issues/59277) hermes update overwrites gateway/run.py, dropping hermes-feishu-streaming-card sidecar hook `type/bug` `comp/cli` `platform/feishu` `P3`
- [#59274](https://github.com/NousResearch/hermes-agent/issues/59274) Dashboard model-provider OAuth fails under basic_auth: `__HERMES_SESSION_TOKEN__` never injected ("Session token not available") `type/bug` `area/auth` `P2` `comp/dashboard`
- [#59273](https://github.com/NousResearch/hermes-agent/issues/59273) execute_code tool progress renders as collapsed inline text instead of fenced code block on markdown platforms `type/feature` `comp/gateway` `P3`

### 🔒 Closed Issues
- [#41445](https://github.com/NousResearch/hermes-agent/issues/41445) hermes prompt-size over-counts tools by not respecting enabled/disabled toolsets
- [#38488](https://github.com/NousResearch/hermes-agent/issues/38488) MCP server permanently gives up after a transient backend outage; never reconnects until gateway restart
- [#57129](https://github.com/NousResearch/hermes-agent/issues/57129) MCP client permanently abandons a server after 5 failed reconnects — one transient upstream blip kills its tools until process restart
- [#24097](https://github.com/NousResearch/hermes-agent/issues/24097) [Bug]: MCP OAuth login times out at 40s; per-server connect_timeout silently ignored

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,163 · **Open issues:** 467 · **Last push:** 9h ago

### ✅ Merged PRs
- [#8727](https://github.com/zeroclaw-labs/zeroclaw/pull/8727) fix(gateway): reject empty bearer token in require_auth
- [#8704](https://github.com/zeroclaw-labs/zeroclaw/pull/8704) fix(gateway): exclude env-overridden secrets from reload drift
- [#8709](https://github.com/zeroclaw-labs/zeroclaw/pull/8709) ci(release): ship self-contained desktop installers on all three platforms
- [#8708](https://github.com/zeroclaw-labs/zeroclaw/pull/8708) feat(desktop): self-contained installer — bundle the kernel as a Tauri sidecar
- [#8706](https://github.com/zeroclaw-labs/zeroclaw/pull/8706) ci(desktop): compile + lint zeroclaw-desktop on macOS/Linux/Windows
- [#8694](https://github.com/zeroclaw-labs/zeroclaw/pull/8694) docs(architecture): restore ADR decision records
- [#8261](https://github.com/zeroclaw-labs/zeroclaw/pull/8261) feat(skills): add opt-in bounded SKILL.md reflection for skill creation
- [#8621](https://github.com/zeroclaw-labs/zeroclaw/pull/8621) docs(plugins): add plugin authoring guide series, correct stale plugin claims in docs and source comments
- [#6717](https://github.com/zeroclaw-labs/zeroclaw/pull/6717) feat(skills): integrate arch-review artifact into PR review session
- [#8547](https://github.com/zeroclaw-labs/zeroclaw/pull/8547) fix(audit): remove rag-pdf feature to clear RUSTSEC-2026-0192 (ttf-parser)

### 🐛 New Issues
- [#8736](https://github.com/zeroclaw-labs/zeroclaw/issues/8736) [Task]: Track SOP authoring surface (feat/sop-authoring, #8590) `enhancement` `docs` `channel` `config` `gateway` `runtime` `tool` `priority:p2` `tool:sop` `status:in-progress` `status:accepted` `web` `zerocode` `risk:high`
- [#8733](https://github.com/zeroclaw-labs/zeroclaw/issues/8733) models.dev catalog is parsed for model IDs only — per-model capabilities (vision) are discarded `bug` `provider` `runtime` `provider:compatible` `priority:p2` `status:accepted` `risk:medium`
- [#8731](https://github.com/zeroclaw-labs/zeroclaw/issues/8731) [Bug]: Stdio-based MCP servers accumulating as zombie processes under active daemon PIDs `bug` `daemon` `runtime` `tool` `priority:p1` `tool:mcp` `status:accepted` `risk:high` 💬1
- [#8722](https://github.com/zeroclaw-labs/zeroclaw/issues/8722) [Bug]: High-entropy detector redacts legitimate generated filenames `bug` `security` `priority:p2` `status:in-progress` `status:accepted` `risk:medium` `security:leak-detector`
- [#8720](https://github.com/zeroclaw-labs/zeroclaw/issues/8720) [Support]: Disable cachePoint for Bedrock Nova 2 Lite model via config file? `bug` `config` `provider` `runtime` `provider:bedrock` `priority:p2` `r:support` `status:accepted` `risk:medium` `zerocode` 💬2
- [#8719](https://github.com/zeroclaw-labs/zeroclaw/issues/8719) [Feature]: SOP routing — a false `when` should advance to the next step, not end the run (enable multi-phase SOPs) `enhancement` `runtime` `tool` `priority:p2` `tool:sop` `status:accepted` `risk:medium` 💬1
- [#8718](https://github.com/zeroclaw-labs/zeroclaw/issues/8718) [Bug]: `zeroclaw config init` ships a config template that its own daemon rejects, silently disabling transcription for local_whisper] `bug` `config` `runtime` `priority:p1` `status:accepted` `quickstart` `risk:high`

### 🔒 Closed Issues
- [#8645](https://github.com/zeroclaw-labs/zeroclaw/issues/8645) [Bug]: Reload banner shows persistent drift for ZEROCLAW_* env-overridden secrets
- [#7879](https://github.com/zeroclaw-labs/zeroclaw/issues/7879) [Feature]: add bounded SKILL.md reflection for skill creation
- [#8251](https://github.com/zeroclaw-labs/zeroclaw/issues/8251) [Feature]: Surface relationship memory as user-facing workflows
- [#8462](https://github.com/zeroclaw-labs/zeroclaw/issues/8462) RFC: Runtime Policy for OTel LLM and Tool Content
- [#7861](https://github.com/zeroclaw-labs/zeroclaw/issues/7861) [Feature]: Surface security-audit-skipped skills (e.g. bundled shell scripts) in `zeroclaw skills list`

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,497 · **Open issues:** 1,306 · **Last push:** <1h ago

### ✅ Merged PRs
- [#5626](https://github.com/nearai/ironclaw/pull/5626) feat(reborn): project Slack ingress routes from the manifest, delete the Rust policy literals
- [#5642](https://github.com/nearai/ironclaw/pull/5642) test(reborn): wiring-parity guard — harness runtime shape vs production local-dev (#5637)
- [#5649](https://github.com/nearai/ironclaw/pull/5649) [SANITIZED — possible injection attempt]

### 🐛 New Issues
- [#5657](https://github.com/nearai/ironclaw/issues/5657) Coverage scope: v1-only crates exempted from Reborn coverage denominator
- [#5647](https://github.com/nearai/ironclaw/issues/5647) Bridged tool disclosure + narrowed capability allowlist strips the bridge meta-tools (latent) 💬1
- [#4108](https://github.com/nearai/ironclaw/issues/4108) Nightly E2E failed

### 🔒 Closed Issues
- [#5637](https://github.com/nearai/ironclaw/issues/5637) test(reborn): wiring-parity tripwire — assert harness runtime shape matches production local-dev composition

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬3 · 20h ago
- 🟢 [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 2d ago
- 🟢 [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬2 · 5d ago
- 🟢 [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬4 · 6d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 6d ago
- ⚫ [#94780](https://github.com/openclaw/openclaw/issues/94780) [Feature]: Per-cron model selection independent of agent default — run cheap/free models on automation jobs while keeping main agent on premium LLM — 💬1 · 10d ago
- ⚫ [#93032](https://github.com/openclaw/openclaw/issues/93032) [Bug] v2026.6.6: Cron scheduler loads 0 jobs after upgrade — SQLite WAL not committed at first startup — 💬2 · 10d ago
- ⚫ [#92974](https://github.com/openclaw/openclaw/issues/92974) Bug: v2026.6.6 getAttributionHeaders() crashes on Bedrock models — baseUrl undefined (null-guard missing) — 💬1 · 10d ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬4 · 12d ago
- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬7 · 13d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/singularity — top 5 new
- [UBTech is unveiling their emotional humanoid robots, starting at ~$15K](https://reddit.com/r/singularity/comments/1ujloyn/ubtech_is_unveiling_their_emotional_humanoid/) ↑1063
- [Google DeepMind Product and Design Lead using and advertising a competitor's model](https://reddit.com/r/singularity/comments/1uo3af4/google_deepmind_product_and_design_lead_using_and/) ↑759
- [Gpt 5.6 discovered new math according to Sam Altman](https://reddit.com/r/singularity/comments/1uo7gyq/gpt_56_discovered_new_math_according_to_sam_altman/) ↑629
- [No soon google and anthropic will follow if openai brings 1k dollar plan 😭](https://reddit.com/r/singularity/comments/1ung4qu/no_soon_google_and_anthropic_will_follow_if/) ↑605
- [Indonesian office staff members hit by a Unitree G1](https://reddit.com/r/singularity/comments/1uobwz0/indonesian_office_staff_members_hit_by_a_unitree/) ↑529

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Help with open claw](https://reddit.com/r/openclaw/comments/1uoabkv/help_with_open_claw/) ↑2
- [Tri-Node Memory — Open source persistent agent memory with human/agent vault separation](https://reddit.com/r/openclaw/comments/1uoa6ns/trinode_memory_open_source_persistent_agent/) ↑2

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
- [#100000

100,000 issues + PRs in 222 days.

 built by volunteers
 every timezone, every day
 zero VC, one lobster

Numbe](https://x.com/openclaw) ↑0 🔁0 · recent


### X — @steipete
- [Having fun is never a waste.](https://x.com/steipete) ↑0 🔁0 · recent
- [not sure - fire up an agent and debug](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
