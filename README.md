# The hub

A public reference hub for my AI agents. It holds one canonical set of guidelines that govern how they write, store memories, and use tools, so every agent behaves the same way no matter which surface it runs on.

## Why this exists

I run Claude across several surfaces: Claude Code on more than one machine, claude.ai, the desktop and mobile apps, and Cowork. They all need the same rules. Keeping those rules in one public place means I edit a single file and every agent picks up the change, instead of pasting instructions into a dozen configs that drift apart over time.

## What is here

- `STYLE.md`: the writing style guide. Voice, tone, formatting, banned words and punctuation, and per-channel notes. This is the source of truth for how my agents write anything I will send or publish.

Same pattern, planned:

- Memory conventions: how agents record durable facts, decisions, and preferences so knowledge survives across sessions rather than getting re-derived every time.
- Tool conventions: which tools to reach for, when to reach for them, and the guardrails around them.

## How agents consume it

Two ways, both live off the `main` branch:

- Raw file. Fetch any file directly, for example the style guide at
  `https://raw.githubusercontent.com/jcaw07/thehub/main/STYLE.md`.
- MCP server. `STYLE.md` is also served as a remote MCP tool (`get_writing_style`) at
  `https://agent-guides.vercel.app/mcp`, so an agent can pull it on demand from any surface.

Edit a file here, push, and the change is live within about a minute. No redeploy.

## Using this yourself

This is built for my own use, but the guidelines are general enough that others may find them useful. If you want them, fork the repo or copy whatever helps. The license below is permissive, so you are free to adapt it. Attribution is appreciated but the terms are what they are.

## License

This repository is licensed under the MIT license. You are free to use, copy, modify, and distribute the contents, including for commercial purposes, as long as the copyright notice and permission notice are preserved. See `LICENSE` for the full text.

Copyright (c) 2026 Jim Wallace.
