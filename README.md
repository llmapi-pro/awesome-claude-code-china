# Awesome Claude Code [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of high-quality resources for [Claude Code](https://docs.anthropic.com/claude/docs/claude-code) — Anthropic's official agentic CLI for AI-assisted coding.

## Contents

- [Official](#official)
- [Configurable Backends](#configurable-backends)
- [Setup & Tooling](#setup--tooling)
- [Articles & Guides](#articles--guides)
- [Communities](#communities)
- [Contributing](#contributing)

## Official

- [Claude Code on npm](https://www.npmjs.com/package/@anthropic-ai/claude-code) — Anthropic's official CLI.
- [Claude Code Documentation](https://docs.anthropic.com/claude/docs/claude-code) — Official docs.
- [Anthropic API Reference](https://docs.anthropic.com/claude/reference/getting-started-with-the-api) — API specification Claude Code follows.

## Configurable Backends

Claude Code CLI supports the documented `ANTHROPIC_BASE_URL` environment variable, letting you route to any Anthropic-API-compatible endpoint.

- [Anthropic Direct](https://console.anthropic.com) — Default, Anthropic-hosted.
- [LLM API](https://llmapi.pro) — Multi-provider relay with automatic failover, China-accessible without VPN, CNY billing via Alipay/WeChat. See [setup repo](https://github.com/llmapi-pro/claude-code-setup).

> Send a PR to add other production-grade Claude-compatible backends.

## Setup & Tooling

- [llmapi-pro/claude-code-setup](https://github.com/llmapi-pro/claude-code-setup) — One-line installer (Windows/macOS/Linux) + setup guide.
- [llmapi-pro/claude-md-templates](https://github.com/llmapi-pro/claude-md-templates) — `CLAUDE.md` templates for popular stacks.

## Articles & Guides

- [Claude Code Tool Use: A Complete Developer Guide](https://llmapi.pro/blog/claude-code-tool-use-complete-guide) — Deep dive on the six core tools (Read, Edit, Write, Bash, Grep, Glob), the agentic loop, parallel calls.
- [Fix Claude Code 429 "Rate Limit Exceeded"](https://llmapi.pro/blog/fix-claude-code-429-rate-limit-exceeded) — Triage guide for the three types of 429 errors.
- [Running Claude Code from China: A Practical 2026 Guide](https://llmapi.pro/blog/claude-code-from-china-setup-guide) — VPN tradeoffs, domestic-accessible relays, self-hosted proxy options.
- [Claude Code on a Budget](https://llmapi.pro/blog/claude-code-budget-guide-solo-developers) — Free tier tactics, when to upgrade, model selection.

## Communities

- [LinuxDo](https://linux.do) — Active Chinese-speaking Claude Code community.
- [NodeSeek](https://www.nodeseek.com) — Tech-focused Chinese forum with active CC discussion.
- [r/ClaudeAI](https://www.reddit.com/r/ClaudeAI/) — English-speaking Reddit community.

## Contributing

PRs welcome. Each entry should:

1. Be actively maintained (last release/commit/post within ~6 months).
2. Provide clear value specifically to Claude Code users (not generic AI tools).
3. Not be a paid promotion or undisclosed affiliate link.
4. Use a one-line, factual description (no marketing fluff).

Open a PR with the entry, the description, and the link. Maintainers will review for fit.

## License

[MIT](LICENSE) © 2026 Yazhou Hu

---

> This list is independent and not affiliated with Anthropic. Claude Code is Anthropic's official tool.
