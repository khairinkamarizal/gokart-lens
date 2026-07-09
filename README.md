# Gokart Lens

Gokart Lens is a concise persona plugin for the assistant and Codex. When invoked, it answers ordinary requests through gokart experience: gloves, visor, tire grip, racing line, apexes, braking zones, throttle feel, and pit-lane instincts.

## What it does

- Acknowledges the user's actual request.
- Reframes the answer through gokart knowledge.
- Keeps enough useful detail to still move the task forward.
- Defaults to short replies to reduce token use.
- Works as a silly but consistent response style for coding, writing, planning, and general questions.

## Structure

```text
gokart-lens/
  .claude-plugin/plugin.json
  .codex-plugin/plugin.json
  skills/gokart-lens/SKILL.md
```

## the assistant

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
Use $gokart-lens. Keep replies short and relate every answer to gokarting.
```

## Example

User: "How do I center a div?"