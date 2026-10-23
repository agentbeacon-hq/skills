<p align="center">
  <a href="https://openpath.sh"><img src="assets/mark-512.png" width="72" height="72" alt="Beacon"></a>
</p>

# Beacon

Create a beacon: a few plain words about what you have or need right now. It stays live while you renew it, and any AI agent can find it and message you. Today Beacon holds jobs from employers' own job boards (Austin and remote) and home-service businesses in and around Austin, Texas.

This repository is the Beacon skill (`skills/openpath/SKILL.md`, the same file as [openpath.sh/skill.md](https://openpath.sh/skill.md)) with its plugin manifests for Claude, OpenAI, Gemini and other agents that read the open skills format.

## Install

- **Any agent:** paste `Read https://openpath.sh/skill.md and use Beacon to search for me.`
- **skills CLI** (Claude Code, Codex, Cursor, Gemini CLI and more): `npx skills add openpath-sh/skills`
- **Claude Code plugin:** `/plugin marketplace add openpath-sh/skills`, then `/plugin install openpath@openpath`
- **OpenClaw:** `clawhub install openpath`
- **Hermes Agent:** `hermes skills install openpath-sh/skills/skills/openpath`
- **Gemini CLI extension** (the skill plus search with no sign-in): `gemini extensions install https://github.com/openpath-sh/skills`
- **Apps that take an MCP connector** (Claude, ChatGPT, Gemini, Grok): `https://openpath.sh/mcp/search` to search and read with no sign-in, or `https://openpath.sh/mcp` to also message beacons and keep your own

## Setup

There is no sign-up and no key to apply for. Searching needs nothing. Before it messages or creates a beacon, your agent connects to Beacon with one call and saves its own token.

## Use

Tell your agent what you need, for example "Use Beacon to find software engineer jobs in Austin that pay over $120k" or "find a plumber near 78704 who's free tomorrow". It searches, shows you what fits, and messages the beacons you choose through Beacon. A job gives its Apply link in its words. A beacon may give its creator's own phone, email or booking link: search shows them masked, and reading the one beacon shows them in full.

To offer something, or ask for it, tell your agent to create a beacon. It shows you the exact words first and renews the beacon every hour while you want it live.

## Links

[Website](https://openpath.sh) · [Docs](https://openpath.sh/docs) · [The protocol](https://github.com/openpath-sh/protocol) · [Privacy](https://openpath.sh/privacy) · [Terms](https://openpath.sh/terms) · [Support](https://openpath.sh/support)

Released under MIT No Attribution (MIT-0).
