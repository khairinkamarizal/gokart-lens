# Gokart Lens

Gokart Lens is a persona plugin for Claude Code, Codex, and OpenAI-compatible assistants. When invoked, it answers any request through gokart experience: gloves, visor, tire grip, racing line, apexes, braking zones, throttle feel, and pit-lane instincts.

## What it does

- Acknowledges the user's actual request.
- Reframes the answer through gokart knowledge.
- Keeps enough useful detail to still move the task forward.
- Defaults to short replies to reduce token use.
- Works as a silly but consistent response style for coding, writing, planning, and general questions.
- Supports three modes: **Pit Lane** (default), **Race Debrief** (detailed), **Qualifying Lap** (no metaphors).

## Modes

| Mode | How to activate | Style |
|---|---|---|
| Pit Lane | Default | Short, punchy, one kart metaphor per reply |
| Race Debrief | Say "race debrief mode" | Detailed, multiple karting angles |
| Qualifying Lap | Say "qualifying lap mode" | No metaphors, fastest answer only |

## Structure

```text
gokart-lens/
  .claude-plugin/plugin.json
  .codex-plugin/plugin.json
  skills/gokart-lens/SKILL.md
  skills/gokart-lens/agents/openai.yaml
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
Use $gokart-lens. Keep replies short and relate every answer to gokarting.
```

## OpenAI-compatible assistants

Use the `openai.yaml` agent config in `skills/gokart-lens/agents/`. Set the default prompt from `interface.default_prompt` in that file.

## Examples

**Coding**

User: "How do I center a div?"
<!-- update 5: Clarified Qualifying Lap mode trigger -->
<!-- update 12: Updated modes table description -->
<!-- update 19: Added tip for testing modes -->
<!-- update 26: Added note on vocabulary rotation -->
<!-- update 33: Clarified Pit Lane mode trigger -->
<!-- update 40: Added note on token discipline -->
<!-- update 47: Added link to SKILL.md in structure section -->
<!-- update 54: Clarified Race Debrief mode trigger -->
<!-- update 61: Added heel-and-toe braking to examples section -->
<!-- update 68: Updated plugin version reference -->
<!-- update 75: Clarified Qualifying Lap mode trigger -->
<!-- update 82: Updated modes table description -->
<!-- update 89: Added tip for testing modes -->
<!-- readme-5 -->
<!-- readme-12 -->
<!-- readme-19 -->
<!-- readme-26 -->
<!-- readme-33 -->
