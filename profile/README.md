# TomeVault

Keep your agents behaving the way you taught them, on every model and tool.

The files that steer AI agents, `CLAUDE.md`, `AGENTS.md`, `GEMINI.md`, `SKILL.md`, Cursor rules, Copilot instructions, Windsurf rules, fail silently. They drift, and nothing tells you until the agent does the wrong thing. TomeVault watches how your setup behaves across models and reconciles it as they change. We are owned by no model vendor and we sell none of the tools we grade.

**[tomevault.io](https://tomevault.io)**

## What we do

**Scan.** Drop in a file and read the verdict. Does it load, is it clear enough to follow, is it safe, and does it hold up across models, with the exact fix for anything that's off. Every check is a deterministic pattern matcher against a public ruleset, never a model judging a model, so you can read the rule that made the grade rather than trust it. No sign-up, nothing uploaded.

**Watch.** A scan checks your setup once. Watchdog keeps it true. It watches the repo where your instructions live and re-checks them on every push and every model release, catches what drifted and fixes it in a pull request you merge, and signs the result. It acts when something changes, not on a schedule.

**Sign.** A verified setup carries a signed record in its repo: `signed_by: null` becomes `signed_by: tomevault`. `tome.lock` catches a changed byte. Watchdog catches a changed model. The signature makes the verdict portable, so anyone can prove the setup was graded against a public standard and is current.

**Translate.** Behaviour authored once, made to run everywhere. A file written for one agent renders to all of them and stays in sync, across Claude Code, Codex, GitHub Copilot, Cursor, Gemini CLI, and Windsurf. The easy part, handled.

> Symlinks keep your files looking the same. They can't keep your agents behaving the same.

## The repositories

| Repository | What it holds |
| --- | --- |
| [`security-rules`](https://github.com/tomevault-io/security-rules) | The public, versioned scan rules behind every verdict. Auditable, RFC-governed |
| [`claude-code-plugins`](https://github.com/tomevault-io/claude-code-plugins) | Instruction files in `CLAUDE.md` format, as a Claude Code plugin marketplace |
| [`codex-plugins`](https://github.com/tomevault-io/codex-plugins) | `AGENTS.md` files for OpenAI Codex |
| [`copilot-plugins`](https://github.com/tomevault-io/copilot-plugins) | `copilot-instructions.md` files for VS Code and GitHub Copilot |
| [`cursor-plugins`](https://github.com/tomevault-io/cursor-plugins) | `.cursor/rules/*.mdc` files for Cursor |
| [`gemini-extensions`](https://github.com/tomevault-io/gemini-extensions) | `GEMINI.md` files for the Gemini CLI |
| [`windsurf-plugins`](https://github.com/tomevault-io/windsurf-plugins) | Rules files for Windsurf |
| [`skills-registry`](https://github.com/tomevault-io/skills-registry) | Reusable `SKILL.md` files in the Agent Skills format |
| [`tomes`](https://github.com/tomevault-io/tomes) | Tomes: a config bundled with its related skills, installable as one unit |
| [`companyos`](https://github.com/tomevault-io/companyos) | CompanyOS, a forkable operating system for an AI-instructed company |

## Start here

- Scan a file in your browser: [tomevault.io/scan](https://tomevault.io/scan)
- Keep it true automatically: [tomevault.io/watchdog](https://tomevault.io/watchdog)
- A signed credential for your clients: [tomevault.io/agencies](https://tomevault.io/agencies)
- The standard behind every verdict: [tomevault.io/standards](https://tomevault.io/standards)
- Read the docs: [tomevault.io/docs](https://tomevault.io/docs)

---

One source of truth for your AI instructions. [tomevault.io](https://tomevault.io)
