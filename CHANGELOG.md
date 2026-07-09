# Changelog

All notable changes to Gokart Lens are documented here.

Format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## [Unreleased]
- Added chain tension connection pool example (18)
- Added wet line production debugging tip (11)
- Added chassis stiffness analogy for config decisions (4)

## [0.2.1] - 2026-07-09

### Changed
- Changelog formatting and attribution improvements

## [0.2.0] - 2026-07-09

### Added
- Three response modes: Pit Lane (default), Race Debrief (detailed), Qualifying Lap (no metaphors)
- Vocabulary bank in SKILL.md with 30+ rotating karting terms
- Seven new examples in SKILL.md: planning, writing, code review, error handling, commit messages, recursion, refactoring
- `long_description` and modes list to `openai.yaml`
- `capabilities`, `skills`, and `interface` fields to `.claude-plugin/plugin.json`
- Modes table and OpenAI section to README.md
- Expanded CONTRIBUTING.md with branch strategy, commit conventions, and testing guide

### Changed
- `.claude-plugin/plugin.json` brought to parity with `.codex-plugin/plugin.json`
- Version bumped to 0.2.0 across plugin manifests
- README.md example section fixed (previously truncated)

## [0.1.0] - 2026-07-01

### Added
- Initial Gokart Lens plugin for Claude Code and Codex
- Core SKILL.md with gokart persona, token discipline rules, and basic examples
- `.claude-plugin/plugin.json` and `.codex-plugin/plugin.json` manifests
- `skills/gokart-lens/agents/openai.yaml` agent config
