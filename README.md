# NO AI SLOP RULES

Strict AI design and development rules.

**by Putra Dev**

## What this rule pack does
This rule pack enforces strict design, UI, and coding guidelines on AI coding agents. It ensures agents produce premium, minimal, human-centered interfaces without relying on generic "AI slop" aesthetics (like excessive gradients, neon glows, and over-engineering).

## Installation
Ensure you have the NO AI SLOP CLI installed globally:
```bash
npm install -g no-ai-slop
```

Initialize it in your project and install these rules:
```bash
noslop init
noslop install https://github.com/putradev/no-ai-slop-rules
noslop apply --target all
```

Verify installation:
```bash
noslop list
```

## Default Design Philosophy
- **LESS EFFECTS, MORE HIERARCHY**
- **LESS DECORATION, MORE TYPOGRAPHY**
- **LESS COMPONENTS, MORE CLARITY**

## /liquid Mode
Liquid Glass mode is disabled by default. If you prompt the AI with `/liquid`, it allows the use of translucent surfaces, backdrop blur, and subtle Apple-inspired glass effects.

## Supported AI Agents
This rule pack integrates via the NO AI SLOP CLI into:
- Cursor (`.cursor/rules/noslop.mdc`)
- GitHub Copilot (`.github/copilot-instructions.md`)
- Generic Agents (`AGENTS.md`, `CLAUDE.md`)

## How to Contribute
Fork this repository, update the markdown files in the `rules/` directory with specific, actionable instructions, and submit a pull request.
