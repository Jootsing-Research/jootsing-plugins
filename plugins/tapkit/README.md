# TapKit Plugin for Claude Code

Control a physical iPhone from Claude Code. See the screen via screenshots and interact through taps, swipes, typing, and other gestures.

## What's Included

- **MCP Server** — Connects Claude to your iPhone via the TapKit API (`https://mcp.tapkit.ai/mcp`)
- **Skill File** — Teaches Claude how to use the phone effectively: coordinate systems, navigation patterns, text input, iOS conventions

## Installation

```
/plugin marketplace add jootsing-research/jootsing-plugins
/plugin install tapkit@jootsing-plugins
```

## Requirements

- A [TapKit](https://tapkit.ai) account
- An iPhone connected via the TapKit companion app
- Claude Code with MCP support

## How It Works

Once installed, Claude gets access to TapKit MCP tools (screenshot, tap, swipe, type, etc.) and a skill file that teaches it how to use them effectively. Just ask Claude to do something on your phone:

- "Open Settings and turn on Dark Mode"
- "Send a message to John on iMessage"
- "Take a screenshot and tell me what's on screen"

Claude will take screenshots to see the phone, identify UI elements visually, and interact via coordinates — no accessibility tree or DOM needed.

## Links

- [TapKit](https://tapkit.ai) — Get started
- [Documentation](https://docs.tapkit.ai) — API docs
