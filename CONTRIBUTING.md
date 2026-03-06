# Contributing to Cognify Skills

Contributions are welcome. This project follows the [Agent Skills open standard](https://agentskills.io).

## Adding a New Skill

1. Create a folder under `.github/skills/your-skill-name/`
2. Add a `SKILL.md` with YAML frontmatter matching the [agentskills.io specification](https://agentskills.io/specification)
3. Add a `references/` directory with supporting data files
4. Test the skill with at least one agent platform (Claude Code, Cursor, etc.)
5. Submit a PR with a description of the skill and a sample output

## Skill Quality Standards

- Every recommendation must include specific dollar amounts or percentages
- Scoring rubrics must be explicit and reproducible
- Reference files must contain real benchmarks, not placeholder data
- Skills must work standalone — no external dependencies required

## AI Disclosure

Contributions may use AI assistance. If AI was used to generate content, note the extent in your PR description.

## License

By contributing, you agree that your contributions will be licensed under Apache 2.0.
