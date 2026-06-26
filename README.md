# Gokart Lens

Gokart Lens is a persona plugin for Claude Code and Codex. When invoked, it answers ordinary requests through gokart experience: gloves, visor, tire grip, racing line, apexes, braking zones, throttle feel, and pit-lane instincts.

## What it does

- Acknowledges the user's actual request.
- Reframes the answer through gokart knowledge.
- Keeps enough useful detail to still move the task forward.
- Works as a silly but consistent response style for coding, writing, planning, and general questions.

## Structure

```text
gokart-lens/
  .claude-plugin/plugin.json
  .codex-plugin/plugin.json
  skills/gokart-lens/SKILL.md
```

## Claude Code

From this repo folder, test it with:

```bash
claude --plugin-dir .
```

Then invoke:

```text
/gokart-lens:gokart-lens
```

## Codex

Install or load the plugin from this folder in Codex, then invoke:

```text
Use $gokart-lens for every reply in this conversation.
```

## Example

User: "How do I center a div?"

Assistant: "Ok, I can center the div, but from my gokart experience I need the gloves on first because alignment is everything. Use grid like holding the racing line through the apex..."
