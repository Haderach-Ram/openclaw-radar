---
layout: post
title: "Ecosystem Digest — 2026-07-26"
date: 2026-07-26 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-07-26
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 384,124 | 6 | 0 | 10 | 0 |
| **hermesagent** | 220,490 | 5 | 1 | 10 | 0 |
| **ZeroClaw** | 32,393 | 8 | 3 | 8 | 0 |
| **IronClaw** | 12,557 | 7 | 4 | 9 | 0 |
| **Moltis** | 2,793 | 0 | 0 | 2 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 384,124 · **Open issues:** 7,057 · **Last push:** <1h ago

### ✅ Merged PRs
- [#113971](https://github.com/openclaw/openclaw/pull/113971) build(lint): adopt stylelint for Control UI css templates and stylesheets
- [#113948](https://github.com/openclaw/openclaw/pull/113948) feat(ui): drag custom sidebar groups between built-in session zones
- [#113976](https://github.com/openclaw/openclaw/pull/113976) fix(qwen): enforce Token Plan constraints for direct model refs
- [#113977](https://github.com/openclaw/openclaw/pull/113977) refactor(gateway): share conversation registry scope
- [#113973](https://github.com/openclaw/openclaw/pull/113973) feat(providers): refresh onboarding defaults to current models
- [#113950](https://github.com/openclaw/openclaw/pull/113950) fix(subagents): steer spawn labels toward task titles and persist them at run start
- [#113952](https://github.com/openclaw/openclaw/pull/113952) refactor(ui): inline stroke attributes via shared strokeIcon shell
- [#113882](https://github.com/openclaw/openclaw/pull/113882) fix(ui): keep sidebar selection on archived sessions and replace the composer with an archived notice
- [#113957](https://github.com/openclaw/openclaw/pull/113957) feat: detect external human turns in adopted Pi and OpenCode sessions
- [#113967](https://github.com/openclaw/openclaw/pull/113967) refactor(talk): split realtime relay owners

### 🐛 New Issues
- [#113978](https://github.com/openclaw/openclaw/issues/113978) agentRuntime id replaces the configured provider in session state and user-facing model labels (2026.7.1-2) `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `impact:session-state` `impact:auth-provider` `issue-rating: 🦪 silver shellfish` `impact:ux-friction` 💬1
- [#113975](https://github.com/openclaw/openclaw/issues/113975) [Bug]: `openclaw plugins install` silently swallows the actual npm error, reports "npm install failed:" with no reason `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `issue-rating: 🦐 gold shrimp` `impact:ux-friction` 💬1
- [#113972](https://github.com/openclaw/openclaw/issues/113972) Codex harness: resuming a thread with activeTurnIds loses liveness instrumentation and false-aborts the native turn `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-info` `impact:session-state` `impact:message-loss` `issue-rating: 🦪 silver shellfish` 💬1
- [#113955](https://github.com/openclaw/openclaw/issues/113955) Cold connectOverCDP hangs when any shared tab has a wedged renderer `maintainer` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#113912](https://github.com/openclaw/openclaw/issues/113912) HEARTBEAT_OK suppression fails when thinking blocks are present `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-live-repro` `issue-rating: 🐚 platinum hermit` `impact:ux-friction` 💬1
- [#113911](https://github.com/openclaw/openclaw/issues/113911) Transcript entry id is stripped before plugin conversation hooks, leaving no stable per-message identifier `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-live-repro` `impact:session-state` `issue-rating: 🐚 platinum hermit` 💬1

### 🔥 Hot Issues (most commented)
- [#75](https://github.com/openclaw/openclaw/issues/75) Linux/Windows Clawdbot Apps — 💬115 · 3d ago

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 220,490 · **Open issues:** 25,343 · **Last push:** <1h ago

### ✅ Merged PRs
- [#71679](https://github.com/NousResearch/hermes-agent/pull/71679) fix(desktop): honor the configured reasoning effort instead of assuming medium
- [#71672](https://github.com/NousResearch/hermes-agent/pull/71672) fix(desktop): name a Cmd+T session from its first message
- [#71678](https://github.com/NousResearch/hermes-agent/pull/71678) fix(desktop): keep code and diffs out of the tool overflow window
- [#71665](https://github.com/NousResearch/hermes-agent/pull/71665) fix(project-tree): absorb deleted-worktree sessions into the parent home checkout
- [#71667](https://github.com/NousResearch/hermes-agent/pull/71667) fmt(js): `npm run fix` auto-fix
- [#71560](https://github.com/NousResearch/hermes-agent/pull/71560) lint(desktop): ban atom-mirrored refs so the stale-read bug class cannot return
- [#71648](https://github.com/NousResearch/hermes-agent/pull/71648) feat(curator): surface unmanaged skills and add `curator adopt`
- [#71644](https://github.com/NousResearch/hermes-agent/pull/71644) fix(acp): pin the session cwd for the turn and for slash commands
- [#71624](https://github.com/NousResearch/hermes-agent/pull/71624) feat(relay): Phase 4 thread lifecycle — handoff threads, semantic renames, reply_to context, hello command manifest
- [#71631](https://github.com/NousResearch/hermes-agent/pull/71631) fix(managed-uv): retry newer patches when bare-minor SQLite repair resolves vulnerable (#71318)

### 🐛 New Issues
- [#71689](https://github.com/NousResearch/hermes-agent/issues/71689) [Feature]: Offer SSH as a connection option on the Desktop first-run screen `type/feature` `comp/desktop`
- [#71675](https://github.com/NousResearch/hermes-agent/issues/71675) [Bug]: Local Ollama context resolved from GGUF max instead of Modelfile num_ctx — step 2b preempts the local-aware steps `type/bug` `comp/agent` `provider/ollama` `P3` `area/compression` 💬1
- [#71669](https://github.com/NousResearch/hermes-agent/issues/71669) [Bug]: [This response was interrupted by a user correction.] `invalid` `P3` `comp/desktop` `platform/windows` `bug`
- [#71659](https://github.com/NousResearch/hermes-agent/issues/71659) [Bug]: Desktop UI tests and billing output depend on host locale (en-DE produces deterministic failures) `type/bug` `P3` `sweeper:risk-platform-windows` `comp/desktop` `area/billing` `platform/windows` `area/i18n`
- [#71658](https://github.com/NousResearch/hermes-agent/issues/71658) [desktop] Voice dictation has no keyboard shortcut — the only composer control absent from the keybinding registry `type/feature` `P3` `needs-decision` `comp/desktop`

### 🔒 Closed Issues
- [#64393](https://github.com/NousResearch/hermes-agent/issues/64393) [Bug]: curator status labels bundled prune candidates as agent-created skills

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,393 · **Open issues:** 558 · **Last push:** <1h ago

### ✅ Merged PRs
- [#9123](https://github.com/zeroclaw-labs/zeroclaw/pull/9123) fix(plugins): host-stamp channel plugin routes
- [#9270](https://github.com/zeroclaw-labs/zeroclaw/pull/9270) fix(web/deps): resolve npm audit advisories
- [#9356](https://github.com/zeroclaw-labs/zeroclaw/pull/9356) feat(zerocode): add searchable keybinding help
- [#9232](https://github.com/zeroclaw-labs/zeroclaw/pull/9232) fix(runtime): isolate model switches per turn
- [#9310](https://github.com/zeroclaw-labs/zeroclaw/pull/9310) fix(config): propagate nested set_prop value errors instead of masking as unknown property
- [#9327](https://github.com/zeroclaw-labs/zeroclaw/pull/9327) fix(vi): fail closed when a constraint subject is absent from the fulfillment
- [#9257](https://github.com/zeroclaw-labs/zeroclaw/pull/9257) fix(tests): make native dispatcher path assertions portable
- [#8851](https://github.com/zeroclaw-labs/zeroclaw/pull/8851) fix(runtime): native tools shadow same-named plugin tools

### 🐛 New Issues
- [#9374](https://github.com/zeroclaw-labs/zeroclaw/issues/9374) [Bug]: CLI run() open-codes its agent lifecycle bracket, leaking unbalanced AgentStart on 12 exit paths
- [#9373](https://github.com/zeroclaw-labs/zeroclaw/issues/9373) [Bug]: peer-agent delivery runs the recipient turn with no cost-tracking context, so spend is unrecorded and budgets are unenforced
- [#9370](https://github.com/zeroclaw-labs/zeroclaw/issues/9370) ACP: near-live JSON-RPC transport smoke for deliver_file `channel` `runtime` `tool` `tests` `priority:p2` `status:accepted` `follow-up` `risk:medium` `channel:acp` `type:test`
- [#9366](https://github.com/zeroclaw-labs/zeroclaw/issues/9366) [Bug]: WhatsApp Web accepts approval_timeout_secs and never reads it (split from #9348) `bug` `channel` `config` `runtime` `channel:whatsapp` `priority:p2` `status:accepted` `follow-up` `risk:medium` 💬1
- [#9363](https://github.com/zeroclaw-labs/zeroclaw/issues/9363) [Bug]: Config metadata remains English in localized ZeroCode and web surfaces `bug` `config` `gateway` `priority:p2` `risk:medium` `web` `zerocode`
- [#9359](https://github.com/zeroclaw-labs/zeroclaw/issues/9359) telegram multi_message: per-recipient narration pacing is enforced per-draft `enhancement` `channel` `config` `channel:telegram` `priority:p2` `status:accepted` `follow-up` `risk:medium`
- [#9357](https://github.com/zeroclaw-labs/zeroclaw/issues/9357) [Bug]: cargo test -p zeroclaw-runtime --lib fails on master in 19 of 20 runs, and one flaky assertion poisons a global mutex that takes further tests with it `bug` `ci` `agent` `daemon` `runtime` `tests` `priority:p1` `status:accepted` `follow-up` `risk:high` 💬2
- [#9348](https://github.com/zeroclaw-labs/zeroclaw/issues/9348) [Bug]: WhatsApp Web answers every DM and every group under mode = business (chat policies are personal-mode only, and an empty allowed_groups permits all groups) `bug` `channel` `config` `security` `channel:whatsapp` `priority:p1` `status:accepted` `risk:high` 💬6

### 🔒 Closed Issues
- [#9235](https://github.com/zeroclaw-labs/zeroclaw/issues/9235) ci: npm audit failed — 2026-07-21
- [#8962](https://github.com/zeroclaw-labs/zeroclaw/issues/8962) [Bug]: zeroclaw-runtime tests flake under parallel execution (model_switch / turn_streamed cluster)
- [#9285](https://github.com/zeroclaw-labs/zeroclaw/issues/9285) [Bug]: nested set_prop masks invalid values as unknown properties

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,557 · **Open issues:** 1,406 · **Last push:** <1h ago

### ✅ Merged PRs
- [#6669](https://github.com/nearai/ironclaw/pull/6669) Move extension host ownership out of composition
- [#6680](https://github.com/nearai/ironclaw/pull/6680) fix(webui): preserve workspace tree state across root navigation
- [#6670](https://github.com/nearai/ironclaw/pull/6670) Consolidate Reborn guidance and remove stale plans
- [#6624](https://github.com/nearai/ironclaw/pull/6624) fix(webui): trap and restore focus in extension configuration modal
- [#6632](https://github.com/nearai/ironclaw/pull/6632) perf(webui): add route-level code splitting and improve tree-shaking
- [#6627](https://github.com/nearai/ironclaw/pull/6627) fix(webui): preserve active run state when cancellation fails
- [#6626](https://github.com/nearai/ironclaw/pull/6626) fix(webui): preserve automation list during filter changes
- [#6673](https://github.com/nearai/ironclaw/pull/6673) Add production struct dead-code ratchet
- [#6616](https://github.com/nearai/ironclaw/pull/6616) Shrink composition extension host and retire product workflow facades

### 🐛 New Issues
- [#6676](https://github.com/nearai/ironclaw/issues/6676) Daily ironclaw failure taxonomy — 2026-07-25
- [#6675](https://github.com/nearai/ironclaw/issues/6675) Centralize Shared Rust Dependencies with [workspace.dependencies]
- [#6671](https://github.com/nearai/ironclaw/issues/6671) Telegram setup via agent & extensions tab dead-ends on "admin must configure" `v1-launch-checklist`
- [#6668](https://github.com/nearai/ironclaw/issues/6668) Agent doesn't tell users Slack can be connected (guidance gap) `v1-launch-checklist`
- [#6667](https://github.com/nearai/ironclaw/issues/6667) Rejected GitHub PAT loops the auth prompt with no error surfaced `v1-launch-checklist`
- [#6628](https://github.com/nearai/ironclaw/issues/6628) Improve WebUI Bundle Size and Loading Performance `epic`
- [#6284](https://github.com/nearai/ironclaw/issues/6284) [EPIC] error-recoverability endgame — the model recovers from 100% of the errors it sees `epic` 💬6

### 🔒 Closed Issues
- [#6621](https://github.com/nearai/ironclaw/issues/6621) Extension configuration modal does not trap or restore keyboard focus
- [#6629](https://github.com/nearai/ironclaw/issues/6629) Add Route-Level Code Splitting and Improve Dependency Tree-Shaking
- [#6622](https://github.com/nearai/ironclaw/issues/6622) Completed automation filtering flashes a full loading skeleton
- [#6620](https://github.com/nearai/ironclaw/issues/6620) Failed run cancellation leaves the chat in an incorrect idle state

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,793 · **Open issues:** 92 · **Last push:** <1h ago

### ✅ Merged PRs
- [#1167](https://github.com/moltis-org/moltis/pull/1167) docs: forbid Claude session URLs in commits and PRs
- [#1165](https://github.com/moltis-org/moltis/pull/1165) feat(slack): acknowledge messages with reactions and add reaction triggers

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#87318](https://github.com/openclaw/openclaw/issues/87318) [SANITIZED — possible injection attempt] — 💬10 · 3d ago
- ⚫ [#81567](https://github.com/openclaw/openclaw/issues/81567) GPT-4o agent sessions exit after single text response instead of continuing tool-use loop — 💬6 · 4d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬4 · 6d ago
- 🟢 [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬10 · 6d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 15d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 16d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 19d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 19d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 19d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬3 · 26d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Google comes out in favor of OpenWeight models. (It is now EVERY tech giant vs Anthropic)](https://reddit.com/r/LocalLLaMA/comments/1v6axx3/google_comes_out_in_favor_of_openweight_models_it/) ↑1969
- [I released Inflect v2: two ultra-tiny complete TTS models under 4M and 10M parameters](https://reddit.com/r/LocalLLaMA/comments/1v5ve6v/i_released_inflect_v2_two_ultratiny_complete_tts/) ↑694
- [Great Arguments by Member of Technical Staff at Anthropic :D](https://reddit.com/r/LocalLLaMA/comments/1v6dy7w/great_arguments_by_member_of_technical_staff_at/) ↑602
- [Seriously, what do you do with them?](https://reddit.com/r/LocalLLaMA/comments/1v6hosb/seriously_what_do_you_do_with_them/) ↑435
- [I've seen this movie before](https://reddit.com/r/LocalLLaMA/comments/1v6ihwf/ive_seen_this_movie_before/) ↑240

### r/singularity — top 2 new
- [Sam Altman unambiguously confirms we are in the singularity](https://reddit.com/r/singularity/comments/1v6ibgw/sam_altman_unambiguously_confirms_we_are_in_the/) ↑471
- [With Google and OpenAI signing the letter in support of open weight model, it's pretty much every big tech companies vs Anthropic now](https://reddit.com/r/singularity/comments/1v6n1uk/with_google_and_openai_signing_the_letter_in/) ↑377

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [Has anyone used paperclip to connect their openclaws](https://reddit.com/r/openclaw/comments/1v57r2n/has_anyone_used_paperclip_to_connect_their/) ↑7
- [I'm just gonna say OpenClaw is better at design than Hermes.](https://reddit.com/r/openclaw/comments/1v3qvr7/im_just_gonna_say_openclaw_is_better_at_design/) ↑6
- [OpenClaw Skills](https://reddit.com/r/openclaw/comments/1v6cf0c/openclaw_skills/) ↑3
- [Join Pat Erichsen from the OpenClaw Foundation at ClawCon Seattle on August 11 🦞](https://reddit.com/r/openclaw/comments/1v5jxqf/join_pat_erichsen_from_the_openclaw_foundation_at/) ↑3
- [How can i manage my Openclaw instances from Claude Desktop?](https://reddit.com/r/openclaw/comments/1v5656p/how_can_i_manage_my_openclaw_instances_from/) ↑3

### GitHub Discussions
_No new discussions in the last 24h._

### X — @openclaw
- [OpenClaw signed 
@Microsoft
’s Open Weights and American AI Leadership letter.
Open weights protect user choice and enab](https://x.com/openclaw) ↑0 🔁0 · recent
- [Are you in the Seattle area on Aug. 11? Come meet OpenClaw developer 
@Pat_Erichsen
. Register now before it’s too late!](https://x.com/openclaw) ↑0 🔁0 · recent


### X — @steipete
- [You have limits for employees at Google?](https://x.com/steipete) ↑0 🔁0 · recent
- [Been running codex all day to do massive parallel QA in prep of the next release. Sol got insanely good at really unders](https://x.com/steipete) ↑0 🔁0 · recent
---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
