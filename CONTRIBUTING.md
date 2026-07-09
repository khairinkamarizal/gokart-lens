# Contributing

Pull requests are welcome. Please keep changes small and focused.

## Branch strategy

- `main` — stable, released code only
- `dev` — active development, all PRs target this branch first
- Feature branches — branch off `dev`, name them `feat/your-feature` or `fix/your-fix`

```text
feat/my-change -> dev -> main
```

## Commit conventions

Follow this format:

```
type(scope): short description
```

Types: `feat`, `fix`, `docs`, `refactor`, `chore`

Scopes: `skill`, `plugin`, `agent`, `readme`, `docs`

Examples:
- `feat(skill): add new examples to SKILL.md`
- `fix(plugin): correct capabilities field in claude plugin.json`
- `docs(readme): update usage instructions`

Keep the subject line under 72 characters. Add a body if the change needs explanation.

## How to test the skill

### Claude Code

1. Clone the repo locally.
2. Run `claude --plugin-dir .` from the repo root.
3. Invoke the skill with `/gokart-lens:gokart-lens`.
4. Test a few prompts across different topics (code, planning, writing).
5. Verify the response is short, useful, and includes a karting angle.

### Codex

1. Load the plugin from the repo folder in Codex.
2. Invoke with the default prompt from `.codex-plugin/plugin.json`.
3. Test the three modes: Pit Lane, Race Debrief, Qualifying Lap.

### Checking SKILL.md changes

Before submitting a PR that modifies `SKILL.md`:

- Verify the frontmatter (`name`, `description`) is intact.
- Make sure any new examples follow the existing format.
- Check that no karting term is repeated more than once in the vocabulary bank.

## What makes a good PR

- One focused change per PR.
- Updated `CHANGELOG.md` entry under `[Unreleased]`.
- No unrelated whitespace or formatting changes.
- PR description explains what changed and why.
<!-- note 6 -->
<!-- note 13 -->
<!-- note 20 -->
<!-- note 27 -->
<!-- note 34 -->
<!-- note 41 -->
<!-- note 48 -->
<!-- note 55 -->
<!-- note 62 -->
<!-- note 69 -->
<!-- note 76 -->
<!-- note 83 -->
<!-- note 90 -->
<!-- contrib-6 -->
<!-- contrib-13 -->
<!-- contrib-20 -->
