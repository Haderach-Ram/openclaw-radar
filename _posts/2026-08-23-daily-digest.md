---
layout: post
title: "Ecosystem Digest — 2026-08-23"
date: 2026-08-23 07:45:00 +0530
categories: [digest, daily]
tags: [openclaw, ecosystem, daily-digest]
---

# 🦞 OpenClaw Ecosystem Digest — 2026-08-23
*Generated 07:46 IST by [Haderach-Ram/openclaw-radar](https://github.com/Haderach-Ram/openclaw-radar)*

## 📊 24h Snapshot

| Framework | ⭐ Stars | New Issues | Closed | Merged PRs | New Releases |
|-----------|---------|-----------|--------|-----------|-------------|
| **OpenClaw** | 387,158 | 12 | 4 | 10 | 0 |
| **hermesagent** | 234,415 | 6 | 1 | 5 | 0 |
| **ZeroClaw** | 32,635 | 9 | 8 | 10 | 0 |
| **IronClaw** | 12,599 | 5 | 4 | 4 | 0 |
| **Moltis** | 2,833 | 0 | 1 | 0 | 0 |

---
## OpenClaw (`openclaw/openclaw`)
**Stars:** 387,158 · **Open issues:** 6,098 · **Last push:** <1h ago

### ✅ Merged PRs
- [#123046](https://github.com/openclaw/openclaw/pull/123046) fix(msteams): require dot boundary for shared-link host suffix match
- [#128070](https://github.com/openclaw/openclaw/pull/128070) fix(ui): sidebar collapse keeps pointer tooltips quiet
- [#123231](https://github.com/openclaw/openclaw/pull/123231) fix(matrix): guard malformed poll answers instead of throwing TypeError
- [#128048](https://github.com/openclaw/openclaw/pull/128048) perf(cron): skip history checks for future jobs
- [#128040](https://github.com/openclaw/openclaw/pull/128040) fix(ui): make multi-user session avatars legible
- [#128035](https://github.com/openclaw/openclaw/pull/128035) fix(sessions): show collaboration details in CLI
- [#128072](https://github.com/openclaw/openclaw/pull/128072) perf(qa-lab): avoid quadratic lane exclusions
- [#127818](https://github.com/openclaw/openclaw/pull/127818) perf(ui): stop long-lived request and session caches from growing forever
- [#128059](https://github.com/openclaw/openclaw/pull/128059) fix(ui): show busy avatar chooser as disabled
- [#128047](https://github.com/openclaw/openclaw/pull/128047) fix(ui): make login recovery commands copyable

### 🐛 New Issues
- [#128076](https://github.com/openclaw/openclaw/issues/128076) Credential-safety contract from #120728 cannot be overridden by the operator and has no opt-out 💬1
- [#128075](https://github.com/openclaw/openclaw/issues/128075) [Bug]: Heartbeat runs ignore models.providers.<id>.baseUrl and call the provider's default endpoint `P1` `impact:auth-provider` `issue-rating: 🦪 silver shellfish` 💬2
- [#128074](https://github.com/openclaw/openclaw/issues/128074) [Bug]: openclaw delegate tool fails inside channel turns: inference probe inherits admitted plugin generation and trips the admission guard 💬2
- [#128073](https://github.com/openclaw/openclaw/issues/128073) [Feature]: Allow permission-gated workspace plugins to use host-mediated session attachment delivery `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:needs-security-review` `impact:security` `issue-rating: 🌊 off-meta tidepool` 💬1
- [#128067](https://github.com/openclaw/openclaw/issues/128067) beta.7 field report: 6 reliability defect classes (persistence, delivery, restart-recovery) + 3 minor `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `impact:session-state` `impact:message-loss` `issue-rating: 🦪 silver shellfish` `impact:other` 💬1
- [#128055](https://github.com/openclaw/openclaw/issues/128055) [Bug]: Control UI deletes immutable assets while WebKit tabs still reference them `bug` `maintainer` `P1` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬2
- [#128052](https://github.com/openclaw/openclaw/issues/128052) [Feature]: Add a first-class session trajectory view `enhancement` `maintainer` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:linked-pr-open` `issue-rating: 🌊 off-meta tidepool` 💬2
- [#128045](https://github.com/openclaw/openclaw/issues/128045) [Feature]: Add per-session Tool mode through a bundled Developer Mode plugin `enhancement` `maintainer` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `clawsweeper:linked-pr-open` `issue-rating: 🌊 off-meta tidepool` `plugin: developer-mode` 💬1
- [#128041](https://github.com/openclaw/openclaw/issues/128041) [Bug]: Restart-recovered Control UI turn hides live progress after reconnect `bug` `maintainer` `bug:behavior` `P2` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#128039](https://github.com/openclaw/openclaw/issues/128039) [Bug]: Permission picker accepts root-dependent modes on rootless legacy sessions `bug` `maintainer` `bug:behavior` `P1` `clawsweeper:source-repro` `impact:session-state` `issue-rating: 🦞 diamond lobster` `maturity:stable` 💬1
- [#128038](https://github.com/openclaw/openclaw/issues/128038) [Bug]: Telegram progress draft repeats each commentary update twice `bug` `maintainer` `bug:behavior` `P2` `clawsweeper:source-repro` `issue-rating: 🦞 diamond lobster` `impact:ux-friction` 💬1
- [#128037](https://github.com/openclaw/openclaw/issues/128037) [Feature]: Control UI background session send with completion toasts `enhancement` `maintainer` `P3` `clawsweeper:no-new-fix-pr` `clawsweeper:needs-maintainer-review` `clawsweeper:needs-product-decision` `issue-rating: 🌊 off-meta tidepool` `impact:ux-friction` 💬1

### 🔒 Closed Issues
- [#128069](https://github.com/openclaw/openclaw/issues/128069) Sidebar collapse opens the Expand sidebar tooltip after touch
- [#78798](https://github.com/openclaw/openclaw/issues/78798) Feature Request: Plugin API for Registering Slash Commands with Pass-through to LLM
- [#127817](https://github.com/openclaw/openclaw/issues/127817) perf(ui): bound long-lived request and session state
- [#127843](https://github.com/openclaw/openclaw/issues/127843) perf(ui): pending approvals rerender the shell and chat panes every second

---
## hermesagent (`NousResearch/hermes-agent`)
**Stars:** 234,415 · **Open issues:** 34,825 · **Last push:** <1h ago

### ✅ Merged PRs
- [#92447](https://github.com/NousResearch/hermes-agent/pull/92447) feat(gateway): fleet consumers now ask the gateway itself — control socket with identify/status (#92091 step 1)
- [#92595](https://github.com/NousResearch/hermes-agent/pull/92595) fix(gateway): control socket never world-connectable; handler I/O off the adapter loop (#92447 review)
- [#88425](https://github.com/NousResearch/hermes-agent/pull/88425) fix(state): stop the unbounded state.db repair loop (salvage of #88224)
- [#92523](https://github.com/NousResearch/hermes-agent/pull/92523) fix(state): fail closed on unscoped SQLite corruption (salvage)
- [#92529](https://github.com/NousResearch/hermes-agent/pull/92529) chore: AUTHOR_MAP brucexu-eth

### 🐛 New Issues
- [#92629](https://github.com/NousResearch/hermes-agent/issues/92629) [Bug]: Desktop Settings Providers > Accounts and API keys render the same paste-key page
- [#92618](https://github.com/NousResearch/hermes-agent/issues/92618) security: establish a repository-wide assurance baseline and release security gate `type/feature` `comp/agent` `P3` `needs-decision` `sweeper:risk-automation`
- [#92611](https://github.com/NousResearch/hermes-agent/issues/92611) [Bug]: delegate child process completion can replace and end the human-facing gateway session `type/bug` `comp/agent` `comp/gateway` `tool/delegate` `P2` `sweeper:risk-session-state` `sweeper:risk-message-delivery`
- [#92608](https://github.com/NousResearch/hermes-agent/issues/92608) bug(memory): Hindsight local_embedded daemon fails to boot under multiplexing — get_secret('HINDSIGHT_LLM_API_KEY') raises UnscopedSecretError on background threads `type/bug` `comp/plugins` `tool/memory` `P3` `sweeper:risk-security-boundary` `sweeper:risk-compatibility` `area/memory` `area/profiles` 💬1
- [#92607](https://github.com/NousResearch/hermes-agent/issues/92607) [Bug]: Wispr Flow cannot insert text into Hermes Desktop composer on Windows `type/bug` `P3` `sweeper:risk-platform-windows` `comp/desktop` `platform/windows` 💬1
- [#92606](https://github.com/NousResearch/hermes-agent/issues/92606) Anthropic OAuth (hermes_pkce/dashboard_pkce): stale credential file overwrites rotated token and two pool rows share one single-use refresh token -> 401 revoked -> empty pool `type/bug` `comp/agent` `provider/anthropic` `area/auth` `P2` `sweeper:risk-security-boundary` 💬1

### 🔒 Closed Issues
- [#40391](https://github.com/NousResearch/hermes-agent/issues/40391) [Bug]: Hermes Desktop Remote Gateway — connects to REST but fails WebSocket / flaps back to local

---
## ZeroClaw (`zeroclaw-labs/zeroclaw`)
**Stars:** 32,635 · **Open issues:** 782 · **Last push:** <1h ago

### ✅ Merged PRs
- [#9938](https://github.com/zeroclaw-labs/zeroclaw/pull/9938) fix(cost): preserve full provider ref so multi-alias pricing resolves
- [#9013](https://github.com/zeroclaw-labs/zeroclaw/pull/9013) refactor(config)!: move TodoWrite display config from the daemon into zerocode
- [#9129](https://github.com/zeroclaw-labs/zeroclaw/pull/9129) feat(plugins): add coherent channel config services
- [#9281](https://github.com/zeroclaw-labs/zeroclaw/pull/9281) fix(config): roll back auto-created map aliases when config set fails
- [#9960](https://github.com/zeroclaw-labs/zeroclaw/pull/9960) fix(quickstart): reject duplicate enabled webhook ports
- [#9291](https://github.com/zeroclaw-labs/zeroclaw/pull/9291) fix(cli): detect installed AppImage and use a working desktop download URL
- [#9694](https://github.com/zeroclaw-labs/zeroclaw/pull/9694) feat(zerocode): expose the SOP pane as a read-only status view
- [#9203](https://github.com/zeroclaw-labs/zeroclaw/pull/9203) fix(sop): wire authenticated HTTP fan-in
- [#9128](https://github.com/zeroclaw-labs/zeroclaw/pull/9128) feat(plugins): add scoped tool secret service
- [#9403](https://github.com/zeroclaw-labs/zeroclaw/pull/9403) fix(plugins): bound WASM exports by a wall-clock deadline

### 🐛 New Issues
- [#10264](https://github.com/zeroclaw-labs/zeroclaw/issues/10264) [Task]: make Quickstart CLI validation tests locale-independent `ci` `runtime` `priority:p2` `quickstart` `risk:low`
- [#10261](https://github.com/zeroclaw-labs/zeroclaw/issues/10261) [Task]: make the filesystem dispatch-loop delivery regression load-bearing `channel` `priority:p2` `status:accepted` `follow-up` `risk:low` `size:XS` `type:test`
- [#10257](https://github.com/zeroclaw-labs/zeroclaw/issues/10257) [Bug]: cron update --command writes unused column on agent jobs 💬1
- [#10251](https://github.com/zeroclaw-labs/zeroclaw/issues/10251) Repeat parallel runtime tests: 17 telegram listen_* tests assert on wall-clock timeouts (same class as #9429) 💬2
- [#10249](https://github.com/zeroclaw-labs/zeroclaw/issues/10249) [Bug]: Duplicate webhook handling logs raw caller-controlled idempotency keys `bug` `gateway` `observability` `domain:security` `priority:p2`
- [#10247](https://github.com/zeroclaw-labs/zeroclaw/issues/10247) [Task]: harden MCP custom-CA platform evidence and docs `docs` `config` `tool` `tests` `domain:security` `priority:p2` `tool:mcp` `follow-up` `risk:high`
- [#10244](https://github.com/zeroclaw-labs/zeroclaw/issues/10244) [Feature]: Add agent deletion and bulk cleanup to ZeroCode `enhancement` `agent` `config` `priority:p2` `risk:medium` `zerocode`
- [#10243](https://github.com/zeroclaw-labs/zeroclaw/issues/10243) [Feature]: Retire or supersede the unused legacy HMAC node transport `enhancement` `config` `runtime` `security` `domain:architecture` `priority:p2` `risk:medium` `type:refactor` 💬1
- [#10238](https://github.com/zeroclaw-labs/zeroclaw/issues/10238) [Bug]: ZeroCode shows stale Connected state after daemon exits `bug` `priority:p2` `zerocode` 💬1

### 🔒 Closed Issues
- [#9573](https://github.com/zeroclaw-labs/zeroclaw/issues/9573) [Bug]: cost pricing lookup fails for multiple aliases of the same provider type
- [#9759](https://github.com/zeroclaw-labs/zeroclaw/issues/9759) bug(quickstart): reject duplicate enabled webhook ports
- [#9202](https://github.com/zeroclaw-labs/zeroclaw/issues/9202) [Bug]: `zeroclaw desktop` command uses dead download URL and does not detect installed AppImage on Linux
- [#9682](https://github.com/zeroclaw-labs/zeroclaw/issues/9682) [Task]: Tracker — zerocode SOP pane MVP (status visibility: list + live run-status icons)
- [#9237](https://github.com/zeroclaw-labs/zeroclaw/issues/9237) [Bug]: failed config updates leave phantom map aliases
- [#6685](https://github.com/zeroclaw-labs/zeroclaw/issues/6685) SOP HTTP fan-in (POST /sop/* and /webhook fallback) is documented but not wired
- [#9255](https://github.com/zeroclaw-labs/zeroclaw/issues/9255) [Bug]: WASM plugin calls have no wall-clock timeout; a dripping HTTP response runs unbounded
- [#9640](https://github.com/zeroclaw-labs/zeroclaw/issues/9640) WhatsApp Web policy doc comments cite `allowed_numbers`, a V2 key with no V3 field

---
## IronClaw (`nearai/ironclaw`)
**Stars:** 12,599 · **Open issues:** 1,527 · **Last push:** <1h ago

### ✅ Merged PRs
- [#7773](https://github.com/nearai/ironclaw/pull/7773) refactor(webui): remove duplicate Settings and Extensions tabs
- [#7774](https://github.com/nearai/ironclaw/pull/7774) test(webui): make automation presenter date assertions timezone-robust
- [#7772](https://github.com/nearai/ironclaw/pull/7772) fix(webui): surface extension setup phase and blockers in Configure
- [#7700](https://github.com/nearai/ironclaw/pull/7700) feat(notifications): publish authoritative run outcomes

### 🐛 New Issues
- [#7825](https://github.com/nearai/ironclaw/issues/7825) Sandbox egress auth: native iron-proxy recipes with host credential broker (retire GitHub-specific carve-out)
- [#7824](https://github.com/nearai/ironclaw/issues/7824) Context projection: Pi-style compaction barrier, structured summaries, overflow recovery 💬2
- [#7823](https://github.com/nearai/ironclaw/issues/7823) [x-ai-product-feedback] Notion install fails in IronClaw
- [#7822](https://github.com/nearai/ironclaw/issues/7822) [x-ai-product-feedback] Slack user: unable to set up Slack in IronClaw
- [#7815](https://github.com/nearai/ironclaw/issues/7815) Onboarding suggestions: cumulative net-new work to close the connect → suggest → thread flow `module:M1-webui-product` `scope: webui` `epic` `ux` 💬1

### 🔒 Closed Issues
- [#7768](https://github.com/nearai/ironclaw/issues/7768) Remove unused Settings and Extensions tabs and duplicate route metadata
- [#7767](https://github.com/nearai/ironclaw/issues/7767) Make Automation presenter date tests timezone-robust
- [#7769](https://github.com/nearai/ironclaw/issues/7769) Surface extension setup phase and blockers in Configure
- [#7691](https://github.com/nearai/ironclaw/issues/7691) Publish run outcome notifications and harden notification lifecycle behavior

---
## Moltis (`moltis-org/moltis`)
**Stars:** 2,833 · **Open issues:** 93 · **Last push:** 1d ago

### 🔒 Closed Issues
- [#1230](https://github.com/moltis-org/moltis/issues/1230) feat(hooks): add an opt-in fail-closed error policy for modifying security hooks

---
## 🎯 Our Filed Issues (Haderach-Ram on openclaw/openclaw)

- 🟢 [#86451](https://github.com/openclaw/openclaw/issues/86451) Bug: openclaw update creates duplicate cron entries — no deduplication check on re-creation — 💬2 · 1d ago
- 🟢 [#93033](https://github.com/openclaw/openclaw/issues/93033) [Bug] v2026.6.6: BWS secret resolution order changed — gateways without BWS_ACCESS_TOKEN in plist fail after cache expiry (~4h) — 💬2 · 1d ago
- 🟢 [#79607](https://github.com/openclaw/openclaw/issues/79607) [Feature]: Identity-based session unification — one session per user regardless of input channel (voice, Telegram, WhatsApp etc.) — 💬4 · 5d ago
- ⚫ [#98062](https://github.com/openclaw/openclaw/issues/98062) [Bug]: iOS app fails to connect over Tailscale CGNAT (100.x.x.x) — wss:// required but WebSocket upgrade silently dropped — 💬4 · 10d ago
- ⚫ [#93031](https://github.com/openclaw/openclaw/issues/93031) [Bug] v2026.6.6 cron migration: jobs migrated from jobs.json have blank agent_id — scheduler silently skips them — 💬3 · 13d ago
- ⚫ [#93139](https://github.com/openclaw/openclaw/issues/93139) Bug: write tool and exec heredocs insert literal \n instead of newlines in string content — 💬11 · 16d ago
- ⚫ [#99305](https://github.com/openclaw/openclaw/issues/99305) [Bug]: Bedrock provider — claude-sonnet-5 prompt caching broken (cache-control blocks not attached, zero cache hits) — 💬4 · 18d ago
- ⚫ [#87876](https://github.com/openclaw/openclaw/issues/87876) Bug: Bedrock Converse Streaming silently aborts on long-context agent sessions (~6 min timeout, no retry, no fallback) — 💬3 · 20d ago
- 🟢 [#93140](https://github.com/openclaw/openclaw/issues/93140) Bug: v2026.6.6 apply_patch and write tool fail for paths outside workspace sandbox (/tmp, absolute paths) — 💬3 · 22d ago
- ⚫ [#90531](https://github.com/openclaw/openclaw/issues/90531) Group chat session JSONL missing sender metadata (__openclaw / senderId) — 💬1 · 22d ago

---
## 🏛️ Official Content — Anthropic + OpenAI

_No new official content detected in the last 24h._

---
## 🤖 Reddit Pulse — r/LocalLLaMA · r/singularity

### r/LocalLLaMA — top 5 new
- [Qwen dev says not to wait for 35B-A3B](https://reddit.com/r/LocalLLaMA/comments/1vrdetw/qwen_dev_says_not_to_wait_for_35ba3b/) ↑1186
- [This is a great sub, regardless of what complaints people have about it.](https://reddit.com/r/LocalLLaMA/comments/1vveabg/this_is_a_great_sub_regardless_of_what_complaints/) ↑345
- [Think you're going to get cheap DDR5 RAM? Think again, even if prices fall, scalper bots now outnumber shoppers 10 to 1 and will keep prices high](https://reddit.com/r/LocalLLaMA/comments/1vv86lm/think_youre_going_to_get_cheap_ddr5_ram_think/) ↑299
- [New 100B Liquid AI model coming soon](https://reddit.com/r/LocalLLaMA/comments/1vvmxls/new_100b_liquid_ai_model_coming_soon/) ↑238
- [Artificial Analysis "Intelligence": A meaningless benchmark](https://reddit.com/r/LocalLLaMA/comments/1vv80xa/artificial_analysis_intelligence_a_meaningless/) ↑110

### r/singularity — top 5 new
- [9.3 seconds…Humanoid robots now run faster than humans](https://reddit.com/r/singularity/comments/1vvhlfi/93_secondshumanoid_robots_now_run_faster_than/) ↑2173
- [New anti-ai sloptube clickbait format just dropped](https://reddit.com/r/singularity/comments/1vv4dlc/new_antiai_sloptube_clickbait_format_just_dropped/) ↑947
- [The amount of activity on GitHub right now is crazy. Thoughts?](https://reddit.com/r/singularity/comments/1vv79k5/the_amount_of_activity_on_github_right_now_is/) ↑555
- [Moderna's Vaccine Breakthrough Supported by AI: Musk Praises mRNA Despite 'Obvious Misuse During COVID'](https://reddit.com/r/singularity/comments/1vvcmy2/modernas_vaccine_breakthrough_supported_by_ai/) ↑410
- [Let's hide data centers in cities with Greco-Deco data center designs, They will never see it comming](https://reddit.com/r/singularity/comments/1vvilkf/lets_hide_data_centers_in_cities_with_grecodeco/) ↑396

---
## 🌐 Community Pulse — OpenClaw Ecosystem

### r/openclaw — top new posts
- [My Cron jobs for OpenClaw](https://reddit.com/r/openclaw/comments/1vv0p3i/my_cron_jobs_for_openclaw/) ↑85
- [Building an OpenClaw-based multi-agent personal assistant on a Raspberry Pi 5](https://reddit.com/r/openclaw/comments/1vvgxwi/building_an_openclawbased_multiagent_personal/) ↑6
- [OpenClaw as a developer](https://reddit.com/r/openclaw/comments/1vva5fh/openclaw_as_a_developer/) ↑5
- [Change your model every once in a while!](https://reddit.com/r/openclaw/comments/1vvfnic/change_your_model_every_once_in_a_while/) ↑1
- [Does anyone use OC to manage their Unifi network?](https://reddit.com/r/openclaw/comments/1vvf6jx/does_anyone_use_oc_to_manage_their_unifi_network/) ↑1

### X — @openclaw
_No new tweets in the last 24h._

### X — @steipete
_No new tweets in the last 7 days._

---
*Next digest: tomorrow 07:45 IST · [Radar repo](https://github.com/Haderach-Ram/openclaw-radar)*
