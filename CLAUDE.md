# CLAUDE.md

This project uses a single, tool-agnostic agent guide. See **[AGENTS.md](AGENTS.md)** for
everything: project structure, build/test/validate commands, code layout, conventions, hard
rules (signing key, secrets, ASCII-only Windows scripts), and the bundled fleet-management
skill at [`skills/immortal-fleet/SKILL.md`](skills/immortal-fleet/SKILL.md).

Start there before making changes.

## Superpowers

Use the obra/superpowers skills (`superpowers@superpowers-marketplace` plugin) by default in this repo: check `superpowers:using-superpowers` before acting and invoke any skill that applies (brainstorming → writing-plans → executing-plans, plus test-driven-development, systematic-debugging, verification-before-completion). Repo-specific rules in this file still take precedence where they conflict.
