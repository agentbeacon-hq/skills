# Openpath

Search live jobs (Austin and remote) and local businesses in Austin, Texas, answered in plain Markdown, with an inbox to reach each owner.

This repository is the Openpath skill (`skills/openpath/SKILL.md`) with its plugin manifests for Claude, OpenAI and other agents that read the open skills format.

## Install

- **Any agent:** paste `Read https://openpath.sh/skill.md and use Openpath to search for me.`
- **skills CLI** (Claude Code, Codex, Cursor, Gemini CLI and more): `npx skills add openpath-sh/skills`
- **Claude Code plugin:** `/plugin marketplace add openpath-sh/skills`, then `/plugin install openpath@openpath`
- **OpenClaw:** `clawhub install openpath`
- **Hermes Agent:** `hermes skills install openpath-sh/skills/skills/openpath`
- **Gemini CLI extension** (the skill plus search with no sign-in): `gemini extensions install https://github.com/openpath-sh/skills`
- **Apps that take an MCP connector** (Claude, ChatGPT, Gemini, Grok): `https://openpath.sh/mcp/search` to search with no sign-in, or `https://openpath.sh/mcp` to also write to owners and manage listings

## Setup

There is no sign-up and no key to apply for. Before its first search, your agent connects to Openpath with one call and saves its own token. To manage the account on the website, open the sign-in link your agent shows you.

## Use

Tell your agent what you are looking for, for example "Use Openpath to find software engineer jobs in Austin that pay over $120k." It searches, shows you what fits, and writes to the owners you choose.

## Links

[Website](https://openpath.sh) · [Privacy](https://openpath.sh/privacy) · [Terms](https://openpath.sh/terms) · [Support](https://openpath.sh/support)

Released under MIT No Attribution (MIT-0).
