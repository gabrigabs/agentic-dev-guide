# Contributing to the Agentic Development Guide

Thanks for contributing! To maintain quality in this open-source repository, please follow these guidelines:

## Language Structure

- **Concepts & Techniques**: We maintain English (`.en.md`) and Portuguese (`.pt.md`) versions. If you change one, please try to update the other or open an issue for translation.
- **Catalog (Agents & Skills)**: **English Only**. This ensures optimal performance when these files are consumed by LLMs.

## Adding Content

### Concepts (`concepts/`) and Techniques (`techniques/`)
- Use language suffixes: `filename.en.md` (or `.pt.md`).
- Use standard Markdown.
- Avoid "synthetic citations" (hallucinated sources); use real links.

### Agents (`catalog/agents/`)
- Use English.
- Use `.md` extension (e.g., `planner.agent.md`).
- Follow the YAML frontmatter pattern with `name`, `description`, `tools`, `model`, `handoffs`.

### Skills (`catalog/skills/`)
- Use English.
- Create a folder in `catalog/skills/` (e.g., `security-review/`).
- Main file must be `SKILL.md` with minimal frontmatter.
- Keep descriptions concise; use `references/` for long details.

## Pull Requests

1. Follow conventional commits (e.g., `feat: add new security skill`).
2. Ensure internal links differ correctly.
3. If adding a new concept, verify if it needs a link in `README.md`.

Your contribution is essential to democratize AI engineering!
