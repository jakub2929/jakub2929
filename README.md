# Hi, I'm Jakub

I look for authorization bugs in open-source software and report them to the maintainers.
The rest of the time I build things: web apps, tooling for AI agents, and a game.

## Security research

I focus on access control, OAuth flows and anything that sits between a user and a credential,
mostly in authentication libraries and AI-agent / MCP infrastructure.

Published advisories I am credited in as a reporter:

- **better-auth** — [GHSA-x8j7-xh58-rv6x](https://github.com/better-auth/better-auth/security/advisories/GHSA-x8j7-xh58-rv6x): billing actions in `@better-auth/stripe` could target another customer's Stripe account
- **client-certificate-auth** — [GHSA-vhr5-98cq-p3qx](https://github.com/tgies/client-certificate-auth/security/advisories/GHSA-vhr5-98cq-p3qx): authorization bypass via SAN type confusion in `allowSAN`

More reports are in coordinated disclosure and will be listed here once the maintainers publish them.

How I work: I read the code, reproduce every finding against a running deployment before I report it,
and report privately through the project's own channel.

## Things I build

- [claude-airlock](https://github.com/jakub2929/claude-airlock) — a reference setup for running untrusted work inside a Claude Code subagent, with a black-box study of what actually confines one
- [AnonChat](https://github.com/jakub2929/E2EAnon) — end-to-end encrypted, ephemeral group chat in Go; no accounts, no database, the server is a blind relay
- [cesky-hlas-navod](https://github.com/jakub2929/cesky-hlas-navod) — a write-up (in Czech) on training a TTS voice: what did not work, what does, with code and numbers
- [HorizonStrike](https://github.com/jakub2929/HorizonStrike) — a game in Godot

## What I work with

Go · TypeScript / JavaScript · Python · GDScript and C# (Godot) · Astro · Docker · Shell
