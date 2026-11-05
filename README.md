# Korpus Legal AI Skill (`korpus-legal-ai`)

Official Open-Source Skill for **Anthropic Claude (Claude Code / Claude Desktop)**, **Google Gemini & Antigravity**, **OpenAI Codex / ChatGPT**, and **Cursor / Windsurf** to maximize legal analysis, case-law commentary, and citation verification using the **Korpus MCP Server** (`https://www.korpus.lu/api/v1/mcp`).

## Quick Install

### Claude Code / Claude Desktop
```bash
mkdir -p ~/.claude/skills/korpus-legal-ai
curl -fsSL https://raw.githubusercontent.com/maximecernot-crypto/korpus-skill/main/SKILL.md -o ~/.claude/skills/korpus-legal-ai/SKILL.md
```

### Google Gemini / Antigravity
```bash
mkdir -p ~/.gemini/config/skills/korpus-legal-ai
curl -fsSL https://raw.githubusercontent.com/maximecernot-crypto/korpus-skill/main/SKILL.md -o ~/.gemini/config/skills/korpus-legal-ai/SKILL.md
```

### OpenAI Codex / Cursor
```bash
curl -fsSL https://raw.githubusercontent.com/maximecernot-crypto/korpus-skill/main/AGENTS.md -o AGENTS.md
curl -fsSL https://raw.githubusercontent.com/maximecernot-crypto/korpus-skill/main/.cursorrules -o .cursorrules
```

## Documentation & API Keys
- **Korpus Skill Page**: https://www.korpus.lu/skill
- **Korpus MCP Server**: https://www.korpus.lu/api/mcp
- **Plans & Jurisdictions**: https://www.korpus.lu/tarifs
