# shareable-skills

Claude Code skills for IBM i development.

## Skills

| Skill | Description |
|-------|-------------|
| [`cl`](cl/SKILL.md) | Generate and review IBM i CL (Control Language) programs — OPM (`.clp`) and ILE (`.clle`) |
| [`dds`](dds/SKILL.md) | Generate and validate IBM DDS source for physical, logical, display, and printer files |
| [`rpg`](rpg/SKILL.md) | Generate ILE RPG programs, service programs, modules, test programs, and header files |

## Installation

Copy the skill directory you want into your Claude Code skills folder (e.g. `~/.claude/skills/`), or clone this whole repo there:

```sh
git clone <this-repo-url> ~/.claude/skills/shareable-skills
```

Each skill is invoked as `/cl`, `/dds`, or `/rpg` once installed.

## ⚠️ Use at your own risk

These skills generate code based on general IBM i conventions and are **not** a substitute for review by someone familiar with your shop's standards. Generated CL, DDS, and RPG may not match your naming conventions, security requirements, or compile cleanly in your environment. Always review, test, and compile generated code before deploying it — especially anything touching PII, production libraries, or job scheduling.
