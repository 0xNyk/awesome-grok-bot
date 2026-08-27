<p align="center">
  <img src="assets/grok-bot-banner.png" alt="Grok Bot" width="800">
</p>

# Awesome Grok Bot

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE)
[![Validate](https://github.com/0xNyk/awesome-grok-bot/actions/workflows/validate.yml/badge.svg)](https://github.com/0xNyk/awesome-grok-bot/actions/workflows/validate.yml)

<p align="center">
  <a href="BRAND.md">Brand kit</a>
  ·
  <a href="assets/github-social.jpeg">Social preview</a>
</p>

> Curated skills, tools, integrations, and resources for [Grok Bot](https://docs.x.ai/grok-bot/overview), the autonomous AI agent from [xAI](https://x.ai).

Grok Bot is the autonomous AI agent product from xAI. Awesome Grok Bot is 0xNyk's independent open-source directory for the optional skills, plugins, MCP servers, and integrations around it. This directory is not an official Cursor or xAI project.

---

## Where Do I Start?

Three steps from zero to productive:

1. **Get Started with Grok Bot:** [Official getting started guide](https://docs.x.ai/grok-bot/get-started) (setup, first tasks, basic usage).
2. **Learn about Skills, Routines, and Automations:** [Skills and routines documentation](https://docs.x.ai/grok-bot/skills-routines-and-automations) (capabilities, workflow patterns).
3. **Connect Plugins:** [Plugin connection guide](https://cursor.com/help/grok-bot/connect-plugins) (extending Grok Bot with external tools).

Then use the full list. Every entry has a maturity tag:

| Tag | What it means |
|-----|---------------|
| **production** | Stable, documented, actively maintained; safe to build on |
| **beta** | Works but still evolving; expect some rough edges |
| **experimental** | Proof of concept or early-stage; learn before depending on it |

Tags are editorial snapshots based on documentation, setup evidence, maintenance, and adoption signals. Re-check the linked project before depending on it.

## Check the trust boundary

<p align="center">
  <img src="assets/trust-boundary.jpeg" alt="Listing is not a security endorsement" width="800">
</p>

An ecosystem listing is a discovery aid, not a security endorsement. Before enabling a community skill, plugin, MCP server, or unattended automation, verify who can trigger it, which tools it receives, where commands execute, what credentials it can read, and how you can stop it. Prefer the smallest toolset and an isolated backend for untrusted work.

Use the official [security and privacy guide](https://docs.x.ai/grok-bot/approvals-security-and-privacy) for current controls and best practices.

---

## Contents

- [Where Do I Start?](#where-do-i-start)
- [Check the Trust Boundary](#check-the-trust-boundary)
- [Official Resources](#official-resources)
- [Skills](#skills)
- [Plugins & Marketplace](#plugins--marketplace)
- [MCP Servers & Connectors](#mcp-servers--connectors)
- [Guides & Documentation](#guides--documentation)
- [Security](#security)
- [Related Projects](#related-projects)
- [Contributing](#contributing)
- [License](#license)

---

## Official Resources

> Core resources and documentation from xAI and Cursor.

- **[beta]** [Grok Bot Landing](https://x.ai/bot) - Official Grok Bot product page from xAI.
- **[beta]** [Documentation Index](https://docs.x.ai/grok-bot) - Complete documentation hub for Grok Bot.
- **[beta]** [Grok Bot Overview](https://docs.x.ai/grok-bot/overview) - Official product overview and capabilities documentation.
- **[beta]** [Getting Started Guide](https://docs.x.ai/grok-bot/get-started) - Quickstart guide for setting up and running Grok Bot.
- **[beta]** [Use Cases](https://docs.x.ai/grok-bot/use-cases) - Common use cases and workflow examples.
- **[beta]** [Mobile](https://docs.x.ai/grok-bot/mobile) - Using Grok Bot on mobile devices.
- **[beta]** [Bots](https://docs.x.ai/grok-bot/bots) - Managing multiple bots and bot configurations.
- **[beta]** [Computer and Apps](https://docs.x.ai/grok-bot/computer-and-apps) - Computer use, app control, and MCP integration.
- **[beta]** [Files and Results](https://docs.x.ai/grok-bot/files-and-results) - Working with files, artifacts, and results.
- **[beta]** [Chat and Collaboration](https://docs.x.ai/grok-bot/chat-and-collaboration) - Team chat and collaborative workflows.
- **[beta]** [Settings and Notifications](https://docs.x.ai/grok-bot/settings-and-notifications) - Configuration and notification management.
- **[beta]** [Teams and Enterprises](https://docs.x.ai/grok-bot/teams-and-enterprises) - Team deployment and enterprise features.
- **[beta]** [Troubleshooting](https://docs.x.ai/grok-bot/troubleshooting) - Common issues and solutions.
- **[beta]** [FAQ](https://docs.x.ai/grok-bot/faq) - Frequently asked questions about Grok Bot.
- **[beta]** [Introducing Grok Bot](https://x.ai/news/introducing-grok-bot) - Official product announcement from xAI.
- **[beta]** [Cursor Forum: Introducing Grok Bot](https://forum.cursor.com/t/introducing-grok-bot/168053) - Community discussion and announcements on the Cursor forum.
- **[beta]** [Cursor: Sign In](https://cursor.com/help/grok-bot/sign-in) - Sign in and authentication setup.
- **[beta]** [Cursor: Plans](https://cursor.com/help/grok-bot/plans) - Pricing plans and feature tiers.
- **[beta]** [Cursor: Secrets](https://cursor.com/help/grok-bot/secrets) - Managing secrets and credentials.
- **[beta]** [Cursor: Computer Recovery](https://cursor.com/help/grok-bot/computer-recovery) - Computer use recovery and troubleshooting.

<br>

## Skills

> Reusable capabilities and workflows for Grok Bot.

- **[beta]** [Official Skills Documentation](https://cursor.com/docs/skills) - Cursor's official skills documentation and guides.
- **[beta]** [Skills, Routines, and Automations](https://docs.x.ai/grok-bot/skills-routines-and-automations) - How to build and use skills, create routines, and set up automations.
- **[production]** [agent-security](https://github.com/0xNyk/agent-security) by [0xNyk](https://github.com/0xNyk) - Security framework and patterns for autonomous AI agents. CLEAN ≠ safe. MIT.
- **[experimental]** [unmachined](https://github.com/0xNyk/unmachined) by [0xNyk](https://github.com/0xNyk) - Tool-use and agent reasoning patterns for building autonomous systems. MIT.
- **[beta]** [council-of-high-intelligence](https://github.com/0xNyk/council-of-high-intelligence) by [0xNyk](https://github.com/0xNyk) - Multi-agent deliberation framework for complex decision-making. MIT.

<br>

## Plugins & Marketplace

> Extensions and integrations from the Grok Bot plugin ecosystem.

- **[beta]** [Cursor Marketplace](https://cursor.com/marketplace) - Browse and install plugins for Cursor and Grok Bot.
- **[beta]** [Cursor Plugins Documentation](https://cursor.com/docs/plugins) - Official plugin development and integration guide.
- **[beta]** [Cursor Plugin Connection Guide](https://cursor.com/help/grok-bot/connect-plugins) - Official guide for connecting plugins to Grok Bot through Cursor.

<br>

## MCP Servers & Connectors

> Model Context Protocol (MCP) servers and integration connectors for Grok Bot.

- **[beta]** [Cursor MCP Documentation](https://cursor.com/docs/mcp) - Official Model Context Protocol documentation for Cursor.
- **[beta]** [Computer and Apps](https://docs.x.ai/grok-bot/computer-and-apps) - Computer use, app control, and MCP integration guide.
- **[beta]** [Cursor Plugin Connection Guide](https://cursor.com/help/grok-bot/connect-plugins) - Covers MCP server integration with Grok Bot.

<br>

## Guides & Documentation

> Learning resources, tutorials, and operational guides.

- **[beta]** [Approvals, Security, and Privacy](https://docs.x.ai/grok-bot/approvals-security-and-privacy) - Security best practices and approval workflows.
- **[beta]** [Cursor: Getting Started with Grok Bot](https://cursor.com/help/grok-bot/getting-started) - Cursor-specific getting started guide.
- **[beta]** [Cursor: Connect Plugins to Grok Bot](https://cursor.com/help/grok-bot/connect-plugins) - How to extend Grok Bot with plugins through Cursor.

<br>

## Security

> Security resources and tools for operating Grok Bot safely.

- **[production]** [agent-security](https://github.com/0xNyk/agent-security) by [0xNyk](https://github.com/0xNyk) - Security framework and patterns for autonomous AI agents. CLEAN ≠ safe. MIT.
- **[production]** [Vetting Inbound Resources](https://github.com/0xNyk/agent-security/blob/main/references/vetting-inbound.md) - Checklist for vetting third-party skills, plugins, and integrations before use.
- **[beta]** [Official Approvals, Security, and Privacy Guide](https://docs.x.ai/grok-bot/approvals-security-and-privacy) - Security controls and privacy considerations from xAI.
- **[beta]** [Cursor: Secrets Management](https://cursor.com/help/grok-bot/secrets) - Managing secrets and credentials securely.
- **[beta]** [Marketplace Security](https://cursor.com/help/security-and-privacy/marketplace-security) - Security considerations for marketplace plugins and extensions.

<br>

## Related Projects

> Other projects from the 0xNyk ecosystem and related tools.

- **[production]** [awesome-hermes-agent](https://github.com/0xNyk/awesome-hermes-agent) - Curated directory for Hermes Agent ecosystem.
- **[production]** [awesome-agent-cortex](https://github.com/0xNyk/awesome-agent-cortex) - Curated directory for Agent Cortex ecosystem.
- **[production]** [agent-security](https://github.com/0xNyk/agent-security) - Security framework for autonomous AI agents.
- **[experimental]** [unmachined](https://github.com/0xNyk/unmachined) - Tool-use and reasoning patterns.
- **[production]** [llmquota](https://github.com/0xNyk/llmquota) - LLM usage tracking and quota management.
- **[beta]** [council-of-high-intelligence](https://github.com/0xNyk/council-of-high-intelligence) - Multi-agent deliberation framework.
- **[production]** [lacp](https://github.com/0xNyk/lacp) - Language Agent Communication Protocol.
- **[production]** [oneclaw](https://github.com/0xNyk/oneclaw) - Unified agent interface framework.
- **[production]** [xint](https://github.com/0xNyk/xint) - X (Twitter) integration toolkit for agents.
- **[production]** [xint-rs](https://github.com/0xNyk/xint-rs) - Rust implementation of X (Twitter) integration toolkit.

---

## Contributing

[Recommend a new resource here!](https://github.com/0xNyk/awesome-grok-bot/issues/new/choose)

Before submitting, please ensure:

1. The resource is directly related to the Grok Bot ecosystem
2. The resource has a clear README and is reasonably maintained
3. You've checked the list to avoid duplicates
4. The resource has an open-source license
5. You can suggest a maturity tag (production/beta/experimental)

For suggestions about the repository itself, please [open an issue](https://github.com/0xNyk/awesome-grok-bot/issues/new).

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting.

---

## License

[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This list is licensed under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/). You are free to share and adapt this material for any purpose, provided you give appropriate attribution.

All resources included in this list have their own license terms.
