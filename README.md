# ai-skill-test-bdd

Generate BDD-style test files with GIVEN/WHEN/THEN comments that test only public API and observable outcomes; tuned for, but not limited to, TypeScript + vitest + testing-library. Use when asked to write or add tests for a specific file or module.

## Install

### Any agent

The [`skills`](https://github.com/vercel-labs/skills) CLI installs into Codex, OpenCode, Gemini CLI, Cursor, Copilot, Claude Code, and 70+ other agents:

```bash
npx skills add guillempuche/ai-skill-test-bdd
```

### Claude Code

```bash
# Add marketplace (uses repo slug)
/plugin marketplace add guillempuche/ai-skill-test-bdd

# Install plugin (plugin name is topic-only)
/plugin install test-bdd@guillempuche-ai-skill-test-bdd
```

### Gemini CLI

```bash
gemini skills install https://github.com/guillempuche/ai-skill-test-bdd.git --path skills/test-bdd
```

### Manual

Copy `skills/test-bdd` into `.agents/skills/` (Codex, Gemini CLI, OpenCode, Mastra Code, Cursor, Copilot) or `.claude/skills/` (Claude Code).

## Part of AI Standards

This skill is also available in the [ai-standards](https://github.com/guillempuche/ai-standards) bundle with other skills and agents.

## License

MIT
