# Awesome Claude Code · China [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of [Claude Code](https://docs.anthropic.com/claude/docs/claude-code) resources for developers in mainland China and Chinese-language users — tutorials, tools, integrations, mirror services, and CLAUDE.md templates.
>
> 给中国大陆与中文开发者的 Claude Code 资源列表 —— 教程、工具、集成、镜像服务、CLAUDE.md 模板。

[English](#english) | [中文](#chinese)

---

<a id="english"></a>

## Why a China-specific list?

Direct access to `anthropic.com` is restricted in mainland China. Chinese developers have built a parallel ecosystem of tutorials, mirror services, and tools to keep using Claude Code productively. This list collects the high-quality ones.

The **international** counterpart maintained by [@hesreallyhim](https://github.com/hesreallyhim/awesome-claude-code) covers global Claude Code plugins, skills, hooks, and slash commands. This list is its **regional companion** — focused on access patterns, mirror services, and Chinese-language guides that the main list does not cover in depth.

## Contents

- [Setup Guides](#setup-guides)
- [Mirror & Relay Services](#mirror--relay-services)
- [Provider Manager / Client Tools](#provider-manager--client-tools)
- [Self-Hosted Relay Tools](#self-hosted-relay-tools)
- [Chinese-Language Tutorials](#chinese-language-tutorials)
- [CLAUDE.md Templates](#claudemd-templates)
- [Communities](#communities)
- [International Resources](#international-resources)
- [Related Projects](#related-projects)
- [Contributing](#contributing)
- [License](#license)

## Setup Guides

- [llmapi-pro/claude-code-setup](https://github.com/llmapi-pro/claude-code-setup) — One-line installer (PowerShell / macOS / Linux) for Claude Code with a Claude-compatible relay backend; no VPN required.
- [Anthropic Official Docs](https://docs.anthropic.com/claude/docs/claude-code) — Official Claude Code documentation.
- [Claude Code on npm](https://www.npmjs.com/package/@anthropic-ai/claude-code) — Anthropic's official CLI package.

## Mirror & Relay Services

Anthropic-protocol-compatible API relay services accessible from China. **Listed alphabetically; no ranking implied.** Pricing and stability change frequently — verify before committing.

- [llmapi.pro](https://llmapi.pro) — Anthropic-protocol-compatible relay with native Claude Code support, monthly subscription model, MiniMax M2.7 single-base routing, China direct access. Open-source companion repos at [github.com/llmapi-pro](https://github.com/llmapi-pro). *(Disclosure: maintained by this list's author.)*
- [PackyCode](https://www.packyapi.com) — Multi-provider API relay focused on Claude Code.
- [AIGoCode](https://aigocode.com) — Integrated Claude Code / Codex / Gemini platform.
- [DMXAPI](https://www.dmxapi.cn) — Multi-model relay with enterprise plans.
- [hvoy.ai](https://hvoy.ai) — Public price-tracking and ranking dashboard for Claude API relay services.

> Want to suggest one? See [Contributing](#contributing). Entries must include a public homepage and an active maintainer.

## Provider Manager / Client Tools

Desktop and CLI tools that manage Claude Code configuration profiles, subscription switching, and multi-provider routing. Useful when you use more than one relay.

- [farion1231/cc-switch](https://github.com/farion1231/cc-switch) — Tauri-based desktop app for managing Claude Code / Codex / Gemini CLI / OpenCode / OpenClaw profiles. Most popular tool in this category (50k+ stars). Tracks active provider per session.
- [musistudio/claude-code-router](https://github.com/musistudio/claude-code-router) — Drop-in router that lets Claude Code talk to multiple model providers (OpenRouter, DeepSeek, Ollama, Gemini, Volcengine, SiliconFlow).
- [ding113/claude-code-hub](https://github.com/ding113/claude-code-hub) — Modern Claude Code & Codex API proxy with load balancing, user management, and usage stats.
- [npow/claude-relay](https://github.com/npow/claude-relay) — Drop-in OpenAI/Anthropic API server routed through Claude Code itself.
- [chadbyte/clay](https://github.com/chadbyte/claude-relay) — Turn Claude Code into a team workspace, single command across devices.

## Self-Hosted Relay Tools

Open-source projects to run your own Claude-compatible relay.

- [Wei-Shaw/claude-relay-service](https://github.com/Wei-Shaw/claude-relay-service) — Self-hosted Claude Code mirror with cost-sharing across subscriptions.
- [Wei-Shaw/sub2api](https://github.com/Wei-Shaw/sub2api) — Successor to claude-relay-service with broader subscription support.
- [ding113/claude-code-hub](https://github.com/ding113/claude-code-hub) — Modern Claude Code & Codex API proxy with load balancing and usage stats.
- [wakaka6/claude-code-relay](https://github.com/wakaka6/claude-code-relay) — Rust-implementation high-performance Claude Code relay.
- [yushangxiao/claude2api](https://github.com/yushangxiao/claude2api) — Bridge Claude web service to API format.

## Chinese-Language Tutorials

- [国内安装 Claude Code 完整指南 (Juejin)](https://juejin.cn/post/7611769471619645478) — Complete domestic Claude Code setup guide.
- [Claude API 国内使用全攻略 (SegmentFault)](https://segmentfault.com/a/1190000046913808) — Comprehensive Chinese-language API access tutorial.
- [Running Claude Code from China (llmapi.pro/blog)](https://llmapi.pro/blog/claude-code-from-china-setup-guide) — Practical 2026 guide.
- [Fix Claude Code 429 Rate Limit (llmapi.pro/blog)](https://llmapi.pro/blog/fix-claude-code-429-rate-limit-exceeded) — Rate-limit triage guide.

## CLAUDE.md Templates

- [llmapi-pro/claude-md-templates](https://github.com/llmapi-pro/claude-md-templates) — Drop-in templates for Next.js, FastAPI, Express+TS, Go.

## Communities

- [LinuxDo](https://linux.do) — Active Chinese-language forum where Claude Code users share guides and tips. Most organic referral traffic to Chinese Claude Code services originates here.
- [V2EX `/go/openai`](https://www.v2ex.com/go/openai) — Chinese developer community discussions.
- [r/ClaudeAI](https://www.reddit.com/r/ClaudeAI/) — English-speaking Reddit community (linked for cross-reference).
- [Claude Code Relay Hub (Discord)](https://discord.gg/jAXY9Eh5zZ) — English-friendly Discord for Claude Code users: relay APIs, multi-provider routing, configs, troubleshooting. Independent and not affiliated with Anthropic. *(Maintained by this list's author.)*

## International Resources

- [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) — The flagship international awesome list (40k+ stars). Skills, hooks, slash commands, plugins.
- [jqueryscript/awesome-claude-code](https://github.com/jqueryscript/awesome-claude-code) — Curated tools and integrations.
- [webfuse-com/awesome-claude](https://github.com/webfuse-com/awesome-claude) — Broader Anthropic Claude resource list.

## Related Projects

From the same maintainer:

- [llmapi-pro/claude-code-setup](https://github.com/llmapi-pro/claude-code-setup) — One-line Claude Code installer.
- [llmapi-pro/claude-md-templates](https://github.com/llmapi-pro/claude-md-templates) — `CLAUDE.md` templates by stack.
- [llmapi-pro/claude-next](https://github.com/llmapi-pro/claude-next) — One-key handoff for deep Claude Code sessions.

## Contributing

PRs welcome. Each entry should:

1. Be **actively maintained** (last release, commit, or post within ~6 months).
2. Provide **clear value to Chinese-language or China-based Claude Code users** (not generic AI tools).
3. **Disclose any affiliation** if you maintain or are commercially associated with the resource.
4. Use a **one-line factual description** (no marketing copy).
5. For paid services: include a public homepage with transparent pricing.

Open a PR with the entry, the description, and the link. Maintainers will review for fit.

## License

[MIT](LICENSE) © 2026 Yazhou Hu

---

<a id="chinese"></a>

## 为什么需要中国向的列表？

中国大陆无法直接访问 `anthropic.com`。中文开发者已经搭建出一套并行生态——教程、镜像服务、本地工具——用来正常使用 Claude Code。本列表收集其中**高质量**的资源。

[@hesreallyhim 维护的国际版](https://github.com/hesreallyhim/awesome-claude-code) 涵盖全球 Claude Code 插件、skills、hooks、slash commands 等。本列表是它的**地区配套**——专注访问方式、镜像服务、中文教程，主列表不覆盖的部分。

## 主要分类

- [安装指南](#setup-guides)
- [镜像与中转服务](#mirror--relay-services)
- [Provider 切换器与路由](#provider-switchers--routers)
- [自建中转工具](#self-hosted-relay-tools)
- [中文教程](#chinese-language-tutorials)
- [CLAUDE.md 模板](#claudemd-templates)
- [社区](#communities)
- [国际资源](#international-resources)
- [关联项目](#related-projects)
- [贡献](#contributing)

## 投稿规则

PR 欢迎。每个条目应：

1. **持续维护中**（最近 6 个月内有 release / commit / 文章更新）
2. **对中文或中国地区 Claude Code 用户有明确价值**（不是泛 AI 工具）
3. **披露任何关联关系**（如果你维护或商业关联该资源）
4. **一句话事实性描述**（不要营销话术）
5. **付费服务**：必须有公开主页 + 透明定价

---

## Sponsorship & Collaboration

This list is maintained alongside [llmapi.pro](https://llmapi.pro), an Anthropic-protocol-compatible API relay accessible from mainland China. We're an independent team, open to conversations on:

- **Sponsored placement** in this list (clearly disclosed) for tools serving Chinese-region Claude Code users.
- **Tooling partnerships** — your IDE extension, router, or agentic framework, listed as a tested companion.
- **Co-marketing** for tools and services in the same ecosystem — mutual discount codes, joint launches.
- **Acquisition / strategic conversations**.

**Contact:** [partnerships@llmapi.pro](mailto:partnerships@llmapi.pro) · or open a PR / issue.

---

<!-- recent-journal-posts-start -->
## Recent posts from the maintainer's journal

Engineering notes and postmortems from running the relay this list maintains alongside, hosted at [llmapi-pro/journal](https://github.com/llmapi-pro/journal):

- [Tool-use IDs in the wild: when the same id appears twice](https://github.com/llmapi-pro/journal/blob/main/articles/2026-05-06-tool-use-id-collisions-occurrence-counter.md)
- [Reasoning blocks at the relay: what changes when the upstream emits thinking](https://github.com/llmapi-pro/journal/blob/main/articles/2026-05-06-reasoning-blocks-at-the-relay.md)
- [A 15-second CPU stall from one unclosed XML tag](https://github.com/llmapi-pro/journal/blob/main/articles/2026-05-06-fifteen-second-cpu-stall-regex-backtracking.md)
- [Twelve protocol patches behind one relay](https://github.com/llmapi-pro/journal/blob/main/articles/2026-04-25-twelve-patches-behind-one-relay.md)
- [The backend trap: when your customers don't pick you, your distributors do](https://github.com/llmapi-pro/journal/blob/main/articles/2026-04-25-the-backend-trap.md)

<!-- recent-journal-posts-end -->
<!-- recent-journal-posts-end -->
<!-- recent-journal-posts-end -->
<!-- recent-journal-posts-end -->

---

> This list is independent and not affiliated with Anthropic. Claude Code is Anthropic's official tool; "Claude" and "Claude Code" are trademarks of Anthropic, PBC.
