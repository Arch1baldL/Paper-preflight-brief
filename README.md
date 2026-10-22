# Paper-preflight-brief

A Codex skill that prepares a structured, source-grounded brief for close reading of a scientific paper. Current release: **1.0.0**.

## Contents

- `skills/paper-preflight-brief/SKILL.md` — skill instructions
- `skills/paper-preflight-brief/references/brief-template.md` — output template
- `skills/paper-preflight-brief/agents/openai.yaml` — display metadata

## Install

Copy `skills/paper-preflight-brief` into your Codex skills directory, usually `~/.codex/skills/`. The resulting path should be `~/.codex/skills/paper-preflight-brief/SKILL.md`. Then start a new Codex conversation and invoke `$paper-preflight-brief`.

The brief is written in English by default. It includes a core question, a checklist with Background and Low-Frequency Vocabulary, narrative waypoints, anticipated difficulties, and a landing check.

No license is included. Choose a license before inviting reuse or contributions.
