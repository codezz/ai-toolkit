# AI Toolkit

A collection of AI skills, agents, and plugins for LLMs.

## Skills

| Skill | Description |
|-------|-------------|
| [caveman](skills/caveman/) | Token-efficient telegraphic responses. Saves tokens without affecting code or external communication. |

## Installation

### Claude Code (plugin)

```bash
/plugin marketplace add codezz/ai-toolkit
/plugin install ai-toolkit
```

### Manual

Copy the skill to your local skills directory:

```bash
git clone https://github.com/codezz/ai-toolkit.git
cp -r ai-toolkit/skills/caveman ~/.claude/skills/caveman
```

## Structure

```
skills/       — reusable skills for LLMs
agents/       — autonomous agent definitions (coming soon)
plugins/      — plugin extensions (coming soon)
```

## License

MIT
