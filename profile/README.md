# TomeVault

TomeVault indexes the files that steer AI agents: `CLAUDE.md`, `AGENTS.md`, `GEMINI.md`, `SKILL.md`, Cursor rules, Copilot instructions, Windsurf rules. We pull them from public GitHub, scan and grade them for safety, convert them across every major agent format, and publish them where developers install them.

These files have no type signature and no test suite. They are prose, and prose drifts as the model underneath it changes. TomeVault is the neutral layer that shows which of them are safe, current, and worth trusting, across every model vendor and owned by none of them.

**[tomevault.io](https://tomevault.io)**

## What we do

**Index.** One searchable view across the skill and instruction-file registries, not GitHub alone.

**Verify.** Every indexed file is scanned for credential leaks, prompt injection, and unsafe shell patterns, then graded bronze, silver, or gold. The scan rules are public and version-controlled (see [`vault-rules`](https://github.com/tomevault-io/vault-rules)).

**Convert.** A file authored for one agent is made to run on all of them. Behaviour authored once, portable across Claude Code, Codex, GitHub Copilot, Cursor, Gemini CLI, and Windsurf.

**Distribute.** Converted files are published to per-platform marketplaces, installable where developers already work.

## The repositories

| Repository | What it holds |
| --- | --- |
| [`claude-code-plugins`](https://github.com/tomevault-io/claude-code-plugins) | Instruction files in `CLAUDE.md` format, as a Claude Code plugin marketplace |
| [`codex-plugins`](https://github.com/tomevault-io/codex-plugins) | `AGENTS.md` files for OpenAI Codex |
| [`copilot-plugins`](https://github.com/tomevault-io/copilot-plugins) | `copilot-instructions.md` files for VS Code and GitHub Copilot |
| [`cursor-plugins`](https://github.com/tomevault-io/cursor-plugins) | `.cursor/rules/*.mdc` files for Cursor |
| [`gemini-extensions`](https://github.com/tomevault-io/gemini-extensions) | `GEMINI.md` files for the Gemini CLI |
| [`windsurf-plugins`](https://github.com/tomevault-io/windsurf-plugins) | Rules files for Windsurf |
| [`skills-registry`](https://github.com/tomevault-io/skills-registry) | Reusable `SKILL.md` files in the Agent Skills format |
| [`tomes`](https://github.com/tomevault-io/tomes) | Tomes: a config bundled with its related skills, installable as one unit |
| [`vault-rules`](https://github.com/tomevault-io/vault-rules) | The public scan rules behind every verification grade. Auditable, RFC-governed |
| [`companyos`](https://github.com/tomevault-io/companyos) | CompanyOS, a forkable operating system for an AI-instructed company |

## Start here

- Search the index: [tomevault.io](https://tomevault.io)
- Convert a file across formats: [tomevault.io/convert](https://tomevault.io/convert)
- Read the docs: [tomevault.io/docs](https://tomevault.io/docs)
- Standards and verification policy: [tomevault.io/standards](https://tomevault.io/standards)
- How scanning works: [tomevault.io/security](https://tomevault.io/security)

---

Indexed, verified, and distributed by TomeVault.
