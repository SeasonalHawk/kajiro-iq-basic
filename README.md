# Kajiro IQ Basic

> AI Fluency coaching tool for Claude and Claude Code. Teaches users to write better prompts through visible scoring, gap diagnosis, and before/after comparisons.

## What It Does

Kajiro IQ Basic is an educational coaching mode that makes prompt optimization visible. For every prompt you send, it:

1. Scores your prompt against the 14-point K-A-J-I-R-O rubric
2. Diagnoses each gap and explains why it matters
3. Rewrites to 14/14 with all gaps filled
4. Shows before/after comparison
5. Teaches the principle behind each improvement

Over time, you internalize the rubric and write better prompts naturally.

## The K-A-J-I-R-O Framework

| Dimension | Points | What It Measures |
|-----------|--------|-----------------|
| **K**indle | 0-4 | Deliverable clarity: format, structure, audience, success criteria |
| **A**rchitect | 0-3 | Step sequencing: inputs/outputs, dependencies, failure handling |
| **J**udge | 0-3 | Verification: checklists, iteration plans, examples |
| **I**nstruct | 0-4 | Role and quality: expert role, tone, standards, interaction rules |
| **Total** | **14** | |

## Commands

| Command | Action |
|---------|--------|
| `Score this prompt: [prompt]` | Score and show scorecard |
| `Diagnose my prompt: [prompt]` | Score, gap diagnosis, and questions |
| `Refine my prompt: [prompt]` | Score, diagnose, rewrite, and before/after |
| `Full Kajiro: [prompt]` | Complete 6-step process |
| `Quick score: [prompt]` | Fast scorecard only |
| `Fast forge: [prompt]` | Scorecard and refined prompt (no education) |
| `Explain Kajiro` | Framework overview (meta) |
| `Show the rubric` | Display full rubric (meta) |

## Installation

### Plugin Marketplace (Recommended)

Once accepted into the Anthropic Plugin Marketplace:

```
/plugin install kajiro-iq-basic
```

### Standalone Skill (Manual)

To use the skill directly without the full plugin:

```bash
git clone https://github.com/SeasonalHawk/kajiro-iq-basic
mkdir -p ~/.claude/skills/kajiro-iq-basic
cp kajiro-iq-basic/skills/kajiro-iq-basic/SKILL.md ~/.claude/skills/kajiro-iq-basic/SKILL.md
```

Claude Code automatically loads skills from `~/.claude/skills/` on startup.

## See Also

- **Kajiro IQ Pro**: Silent expert mode that optimizes behind the scenes without showing the process
- **kajiro.org**: Official website and methodology documentation

## License

MIT License. Copyright (C) 2025-2026 Kenneth Benavides.

The Kajiro methodology, K-A-J-I-R-O framework, 14-point rubric, and 21 diagnostic questions
are the intellectual property of Kenneth Benavides and are not covered by the MIT License.
Kajiro, Kajiro IQ, and Kajiro IQ Basic are trademarks of Kenneth Benavides.

https://kajiro.org
