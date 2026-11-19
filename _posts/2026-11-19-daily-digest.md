---
layout: post
title: "Ecosystem Digest — 2026-11-19"
date: 2026-11-19 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-11-19
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 394,765 | 9 | 5 | 10 | 1 |
| **hermesagent** | 264,514 | 9 | 3 | 5 | 1 |
| **ZeroClaw** | 33,443 | 7 | 6 | 10 | 0 |
| **IronClaw** | 12,718 | 0 | 0 | 0 | 0 |
| **Moltis** | 2,972 | 0 | 0 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 394,765 · **Open issues:** 8,371 · **Last push:** <1h ago

### 🚀 New Releases
- [v2026.10.33](https://github.com/openclaw/openclaw/releases/tag/v2026.10.33) — openclaw 2026.10.33

### ✅ Merged PRs
- [#201557](https://github.com/openclaw/openclaw/pull/201557) fix(sqlite): let nested page reclamation finish
- [#186942](https://github.com/openclaw/openclaw/pull/186942) fix(ai): round-trip LiteLLM thought signatures on openai-completions routes
- [#196367](https://github.com/openclaw/openclaw/pull/196367) fix: reject message tables without a caption instead of silently dropping them
- [#201555](https://github.com/openclaw/openclaw/pull/201555) fix: open OpenClaw ID sign-in in your default browser from the macOS app
- [#201544](https://github.com/openclaw/openclaw/pull/201544) fix: preserve subagent outcomes across Gateway interruptions
- [#201550](https://github.com/openclaw/openclaw/pull/201550) fix: explain why Doctor cannot restore a scheduled job’s account
- [#197394](https://github.com/openclaw/openclaw/pull/197394) feat(cron): add up to eight runs past the default when memory is free
- [#200978](https://github.com/openclaw/openclaw/pull/200978) fix: remove updater-only restrictions from agent maintenance guidance
- [#201548](https://github.com/openclaw/openclaw/pull/201548) fix(ci): register published plugin driver entry
- [#201546](https://github.com/openclaw/openclaw/pull/201546) fix: avoid full sandbox checkouts when lockfiles change

### 🐛 New Issues
- [#201565](https://github.com/openclaw/openclaw/issues/201565) [Feature]: Live MCP reconnect for Codex conversations, including external credential changes `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#201561](https://github.com/openclaw/openclaw/issues/201561) Windows npm upgrade to 2026.11.5: doctor --fix leaves Gateway stopped; abandoned update still targets 2026.11.3 `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `impact:crash-loop` `issue-rating: 🦪 silver shellfish` `maturity:stable` `impact:ux-friction` 💬1
- [#201558](https://github.com/openclaw/openclaw/issues/201558) [Bug]: OpenAI OAuth re-login (`openclaw models auth login --provider openai --method oauth`) rewrites configured model rows' `thinkingLevelMap` (adds `{}`, drops `off: null`) `bug` `no-stale` `regression` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `impact:data-loss` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` 💬1
- [#201552](https://github.com/openclaw/openclaw/issues/201552) [SANITIZED — possible injection attempt] `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:ux-friction` 💬1
- [#201549](https://github.com/openclaw/openclaw/issues/201549) kimi-claw: image_generate tool calls dropped (xml_tool_call heuristic treats registered tool call as text) `P2` `clawsweeper:needs-info` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬3
- [#201543](https://github.com/openclaw/openclaw/issues/201543) Update failure: gateway-recovery-verification (2026.11.4) `P2` `clawsweeper:needs-info` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#201541](https://github.com/openclaw/openclaw/issues/201541) /btw side questions ignore the model fallback chain: fail on 429 while main turns succeed via fallback `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `impact:auth-provider` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#201540](https://github.com/openclaw/openclaw/issues/201540) [Bug]: Main session actor permanently rejects all turns via session-rebound; heartbeat and memory dreaming blocked with no operator recovery path `bug` `bug:behavior` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:session-state` `impact:message-loss` `issue-rating: 🦪 silver shellfish` 💬4
- [#201530](https://github.com/openclaw/openclaw/issues/201530) [Bug]: 2026.11.3 to 2026.11.5 update blocked by legacy sqlite_stat4 on official Node 26.13.0 `no-stale` `P2` `clawsweeper:fix-shape-clear` `clawsweeper:queueable-fix` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `maturity:stable` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#186842](https://github.com/openclaw/openclaw/issues/186842) [Bug]: Gemini 3 behind a LiteLLM `openai-completions` provider stops thinking after the first tool call (thought signature lost, LiteLLM substitutes a placeholder)
- [#196312](https://github.com/openclaw/openclaw/issues/196312) Slack: presentation table block without caption is silently dropped while delivery reports sent
- [#201559](https://github.com/openclaw/openclaw/issues/201559) [Bug]: Ollama Cloud balance silently missing from `/status` and `status --usage` when `models.providers.ollama.apiKey` is a file SecretRef
- [#172986](https://github.com/openclaw/openclaw/issues/172986) [Bug]: WebChat renders long paths middle-truncated (U+2026) for file: links to OpenClaw special dirs; intermittent payload mutation
- [#140308](https://github.com/openclaw/openclaw/issues/140308) [Feature]: Fallback model pin is "sticky" — sessions never return to primary model after provider recovers

### 🔥 Hot Issues (most commented)
- [#160959](https://github.com/openclaw/openclaw/issues/160959) [Bug]: Gateway blocks for minutes while capturing large external plugins (2026.9.6 regression) — 💬83 · 2d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 264,514 · **Open issues:** 53,818 · **Last push:** <1h ago

### 🚀 New Releases
- [v0.23.2+canary.20261118T064620Z](https://github.com/NousResearch/hermes-agent/releases/tag/v0.23.2%2Bcanary.20261118T064620Z) — Hermes Agent canary v0.23.2+canary.20261118T064620Z

### ✅ Merged PRs
- [#157377](https://github.com/NousResearch/hermes-agent/pull/157377) Agent instructions point at the file tools instead of terminal grep, cat and sed
- [#156455](https://github.com/NousResearch/hermes-agent/pull/156455) Prompt cache kept warm while it pays, then the idle chat compacts or offloads (tool output archived on the local backend)
- [#157538](https://github.com/NousResearch/hermes-agent/pull/157538) Computer use: cua-driver updates again; pin 0.21.0 → 0.52.0 with element clicks working (salvage #126611, #134857, #138596)
- [#157551](https://github.com/NousResearch/hermes-agent/pull/157551) ci(docker): manifest-list jobs back on Blacksmith; PR image builds get the Blacksmith builder
- [#157493](https://github.com/NousResearch/hermes-agent/pull/157493) fix(gateway): keep the Windows listener open when a client resets before accept

### 🐛 New Issues
- [#157635](https://github.com/NousResearch/hermes-agent/issues/157635) [Feature]: config default for the ACP edit-approval policy (acp.edit_approval_policy) `type/feature` `comp/gateway` `comp/acp` `area/config` `P2` `area/sessions`
- [#157633](https://github.com/NousResearch/hermes-agent/issues/157633) Local terminal tool runs commands uncapped in the user's session scope — a heavy build can OOM-kill the whole desktop session `type/bug` `comp/tools` `tool/terminal` `backend/local` `P2` `backend/other`
- [#157632](https://github.com/NousResearch/hermes-agent/issues/157632) [Bug]: Classic CLI one-shot (chat -q … --oneshot) prints inline-image transmits as Python tuple text instead of drawing the image `type/bug` `comp/cli` `tool/vision` `P2` 💬1
- [#157629](https://github.com/NousResearch/hermes-agent/issues/157629) [Feature]: Add Haven as a messaging platform `type/feature` `comp/gateway` `P3`
- [#157628](https://github.com/NousResearch/hermes-agent/issues/157628) [Feature]: Full-resolution inline images inside Zellij (kitty transmit-by-id + placements) `type/feature` `comp/cli` `P3`
- [#157627](https://github.com/NousResearch/hermes-agent/issues/157627) [Bug]: Post-interrupt redraw in the classic CLI repaints the transcript offset (unrecorded hint, off-loop redraw) `type/bug` `comp/cli` `P2`
- [#157626](https://github.com/NousResearch/hermes-agent/issues/157626) kanban: allow `create --initial-status scheduled` so a parked card never emits a `blocked` event `type/feature` `comp/cli` `comp/cron` `tool/file` `P3`
- [#157625](https://github.com/NousResearch/hermes-agent/issues/157625) [Bug]: Desktop remote gateway over HTTPS LAN IP: every ws-ticket rejected no_cookie from first sign-in (Windows + macOS), browser tabs on the same URL work `type/bug` `area/auth` `P2` `comp/desktop` `area/sessions` `desktop/connection`
- [#157615](https://github.com/NousResearch/hermes-agent/issues/157615) [Bug]: secret redaction misses label-prefixed field dumps: mid-line "field password: TYPE = "value"" passes verbatim `type/security` `comp/agent` `P3` 💬1

### 🔒 Closed Issues
- [#132876](https://github.com/NousResearch/hermes-agent/issues/132876) computer_use sends unsupported element_index to strict token-only CUA action schemas
- [#135872](https://github.com/NousResearch/hermes-agent/issues/135872) computer_use element clicks refused on cua-driver 0.34: 'unknown argument element_index'
- [#126587](https://github.com/NousResearch/hermes-agent/issues/126587) pm(cua-driver): pin can never advance — every upstream cua-driver-rs release is flagged `prerelease`, so `latest_versions()` always returns []

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 33,443 · **Open issues:** 1,314 · **Last push:** <1h ago

### ✅ Merged PRs
- [#12237](https://github.com/zeroclaw-labs/zeroclaw/pull/12237) fix(sop): use the fail-closed mode when the decision answers are unusable
- [#11994](https://github.com/zeroclaw-labs/zeroclaw/pull/11994) feat(security): read POSIX commands in bash's grammar when bash runs them
- [#12395](https://github.com/zeroclaw-labs/zeroclaw/pull/12395) docs(runtime): correct the shell-grammar binding row before recording approval
- [#12552](https://github.com/zeroclaw-labs/zeroclaw/pull/12552) fix(deps): patch SMTP advisories with a bounded base64 duplicate
- [#12170](https://github.com/zeroclaw-labs/zeroclaw/pull/12170) fix(tools): inherit headless SOP step scope on peer-send turns
- [#12166](https://github.com/zeroclaw-labs/zeroclaw/pull/12166) fix(install): verify Windows prebuilt release checksums
- [#12281](https://github.com/zeroclaw-labs/zeroclaw/pull/12281) fix(gateway): treat forwarded loopback as non-local for SOP cancel
- [#12151](https://github.com/zeroclaw-labs/zeroclaw/pull/12151) fix(tools): require read access before uploads and edits
- [#12149](https://github.com/zeroclaw-labs/zeroclaw/pull/12149) fix(mcp): confine SSE endpoints and redirects to the server origin
- [#12115](https://github.com/zeroclaw-labs/zeroclaw/pull/12115) fix(gateway): pin Scalar docs bundle with Subresource Integrity

### 🐛 New Issues
- [#12562](https://github.com/zeroclaw-labs/zeroclaw/issues/12562) [Feature]: Telegram: trusted_groups — trusted groups for talking to the agent `enhancement`
- [#12561](https://github.com/zeroclaw-labs/zeroclaw/issues/12561) [Feature]: Matrix: clean up room invites the bot has declined, so they don't pile up `enhancement`
- [#12559](https://github.com/zeroclaw-labs/zeroclaw/issues/12559) [Bug]: Config setters store `inf` and `NaN` for a decimal setting `bug`
- [#12558](https://github.com/zeroclaw-labs/zeroclaw/issues/12558) [Bug]: Matrix tool-approval prompts are posted to the room timeline instead of the thread the turn runs in `bug`
- [#12557](https://github.com/zeroclaw-labs/zeroclaw/issues/12557) [Feature]: Simplify approvals for Discord and Matrix channels `enhancement`
- [#12551](https://github.com/zeroclaw-labs/zeroclaw/issues/12551) Track the bounded base64 0.22.1 duplicate needed by the patched SMTP graph
- [#12548](https://github.com/zeroclaw-labs/zeroclaw/issues/12548) ci: npm audit failed — 2026-11-18 `dependencies` `security` `risk:high`

### 🔒 Closed Issues
- [#12169](https://github.com/zeroclaw-labs/zeroclaw/issues/12169) [Bug]: send_message_to_peer starts the recipient's turn outside the tool scope of the headless SOP step that called it
- [#12122](https://github.com/zeroclaw-labs/zeroclaw/issues/12122) [Bug]: the Windows prebuilt installers (setup.bat --prebuilt and the documented PowerShell block) skip the SHA256SUMS verification that install.sh and `zeroclaw update` perform
- [#12280](https://github.com/zeroclaw-labs/zeroclaw/issues/12280) [Task]: don't treat a forwarded loopback address as local in SOP cancel authorization
- [#12146](https://github.com/zeroclaw-labs/zeroclaw/issues/12146) [Bug]: the MCP SSE client accepts an absolute URL from the server's `endpoint` event and posts there with the configured secret headers, so a server can redirect the daemon's requests and bearer token
- [#12144](https://github.com/zeroclaw-labs/zeroclaw/issues/12144) [Bug]: `file_upload`, `file_upload_bundle` and `file_edit` authorize through the write tier, so a sibling workspace granted `Write` only can be read: uploads transmit its files and edit diagnostics co
- [#12053](https://github.com/zeroclaw-labs/zeroclaw/issues/12053) [Bug]: /api/docs loads an unpinned third-party script without integrity checks on the dashboard origin

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,718 · **Open issues:** 1,574 · **Last push:** 9d ago

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,972 · **Open issues:** 120 · **Last push:** 26d ago

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#167320](https://github.com/openclaw/openclaw/issues/167320) Telegram delivery silently stalls: session-admission race ('session changed before durable user-turn admission') rejects valid retries — 💬4 · 6d ago
- ⚫ [#164461](https://github.com/openclaw/openclaw/pull/164461) fix: surface holder pid/createdAt in offline-maintenance lock error — 💬3 · 16d ago
- ⚫ [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 25d ago
- ⚫ [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 44d ago
- ⚫ [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬12 · 52d ago
- ⚫ [#134866](https://github.com/openclaw/openclaw/pull/134866) fix(agents): trust sandbox bridge for apply_patch on writable bind mounts — 💬4 · 54d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 64d ago
- ⚫ [#139026](https://github.com/openclaw/openclaw/issues/139026) Internal runtime-context block (<<<BEGIN_OPENCLAW_INTERNAL_CONTEXT>>>) leaks visibly into Telegram on stalled/partial-turn replies — 💬2 · 72d ago
- ⚫ [#139028](https://github.com/openclaw/openclaw/issues/139028) [SANITIZED — possible injection attempt] — 💬1 · 74d ago
- ⚫ [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬3 · 82d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

### Anthropic — 2 new
- [[News] Anthropic Prices Initial Public Offering](https://www.anthropic.com/news/anthropic-prices-initial-public-offering) _2026-11-18_
- [[Research] Claude Black Hole Physics](https://www.anthropic.com/research/claude-black-hole-physics) _2026-11-18_

### OpenAI — 3 new
- [[Customer-Stories] Sumitomo Life](https://openai.com/business/customer-stories/sumitomo-life/) _2026-11-19_
- [[Solutions] Accounting](https://openai.com/business/solutions/accounting/) _2026-11-19_
- [[Index] Le Groupe Figaro And Openai Announce Partnership](https://openai.com/index/le-groupe-figaro-and-openai-announce-partnership/) _2026-11-19_

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Qwen 4 35B is not ruled out](https://reddit.com/r/LocalLLaMA/comments/1xzbkwp/qwen_4_35b_is_not_ruled_out/) ↑910
- [SSDs, laptops, and phones may get cheaper as consumer NAND spot pricing drops 20% — Bank of America expects contract price drops, report cites oversupply in consumer market amid declining demand and g](https://reddit.com/r/LocalLLaMA/comments/1xzixp0/ssds_laptops_and_phones_may_get_cheaper_as/) ↑425
- [Nvidia driver 621.24 leads to constant writing of drives](https://reddit.com/r/LocalLLaMA/comments/1xzke1g/nvidia_driver_62124_leads_to_constant_writing_of/) ↑370
- [Nvidia says its open source AI strategy remains intact after Jensen Huang's exit](https://reddit.com/r/LocalLLaMA/comments/1xzb9rz/nvidia_says_its_open_source_ai_strategy_remains/) ↑358
- [New voice isolation model from Inworld](https://reddit.com/r/LocalLLaMA/comments/1xzqpzu/new_voice_isolation_model_from_inworld/) ↑252

### r/singularity — top 5 new
- [Jensen Huang Resigns](https://reddit.com/r/singularity/comments/1xudfv3/jensen_huang_resigns/) ↑2735
- [ETH Zurich researchers use reinforcement learning to teach a 5-ton John Deere loader to perform wheelies, balance on two wheels, navigate 75 cm obstacles, and land safely. The AI transferred directly ](https://reddit.com/r/singularity/comments/1xz88ri/eth_zurich_researchers_use_reinforcement_learning/) ↑1126
- [Google researchers demonstrate AI that improves its own software, remembers what worked, and builds on past improvements even when switching from Claude to Gemini or upgrading to newer models, allowin](https://reddit.com/r/singularity/comments/1xzfv9g/google_researchers_demonstrate_ai_that_improves/) ↑608
- [Introducing Gemini 4 Neon.](https://reddit.com/r/singularity/comments/1xzrjzx/introducing_gemini_4_neon/) ↑551
- [Gemini Neon Benchmarks](https://reddit.com/r/singularity/comments/1xzrlbh/gemini_neon_benchmarks/) ↑409

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Finally ditching Open Claw](https://reddit.com/r/openclaw/comments/1xz9qqc/finally_ditching_open_claw/) ↑36
- [Credit Burn recently](https://reddit.com/r/openclaw/comments/1xzr4py/credit_burn_recently/) ↑4
- [Ant Ling now documents Ling-3.2-flash setup through OpenClaw's custom provider](https://reddit.com/r/openclaw/comments/1xslutv/ant_ling_now_documents_ling32flash_setup_through/) ↑4
- [Aetheris Microbrains v0.6.4: Sub-2ms pure-NumPy pre-flight safety gate (full-file AST, secret & allowlist-first shlex shell parser) + retry-aware MCP-Zero tool narrowing for LLM agents](https://reddit.com/r/openclaw/comments/1xze8y5/aetheris_microbrains_v064_sub2ms_purenumpy/) ↑2
- [Mission Control Panel - Advice](https://reddit.com/r/openclaw/comments/1xzj62z/mission_control_panel_advice/) ↑1

### X — @openclaw
- [The ClawCast — Episode 17](https://x.com/openclaw/status/2123136511910576608) ↑0 🔁0 · recent
- [Today in 2025 (2/7):  The question wasn't whether agents could code. It was which window to open. Cursor, Claude Code, C](https://x.com/openclaw/status/2123113128313655468) ↑0 🔁0 · recent
- [Yesterday in 2025 ->](https://x.com/openclaw/status/2123113357893087695) ↑0 🔁0 · recent
- [Microsoft’s Autopilot is built on OpenClaw, and it’s now rolling out in preview to eligible Frontier customers. 

Pretty](https://x.com/openclaw/status/2122877394331811874) ↑0 🔁0 · recent


### X — @steipete
_No new tweets since the last digest. Most recent:_
- [People: Please reduce the number of permission alerts so agents can work on macOS without constant babysitting

Apple: I](https://x.com/steipete/status/2122463466304971068)
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
