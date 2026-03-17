> Docs should contain public information only: installing, configuring, and running ECP.

# Documentation project instructions

## About this project

- Pages are MDX files with YAML frontmatter.
- Content is public-facing and focuses on installing, configuring, and running ECP.

## Terminology

- **ECP**: Prefer first mention as **“ECP (Execution Control Protocol)”**.
- **Execution Control Protocol**: Use naturally after first mention; don’t repeat every paragraph.
- **MCP**: Model Context Protocol; don’t expand unless the page is MCP-focused.
- **Context**: ECP Context (portable execution environment manifest). Capitalize when referring to the ECP object.
- **Executor / orchestrator**: Use these terms consistently (don’t swap with synonyms).

## Style preferences

- **Voice**: technically friendly but light; precise without hype; forward-moving (goal → concept → next step).
- **SEO**: helpful, non-spammy; use ECP + Execution Control Protocol variants naturally (see rule below).
- **Writing**:
  - Use active voice and second person (“you”)
  - Keep sentences concise — one idea per sentence
  - Use sentence case for headings
  - Prefer short paragraphs and concrete examples
  - Use “Related reading” / “Next steps” sections when useful
- **Formatting**:
  - Bold for UI elements: Click **Settings**
  - Code formatting for file names, commands, paths, and code references

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}

## Cursor rules

- Docs voice + SEO guidance lives in `.cursor/rules/docs-voice-seo.mdc` and applies to `**/*.{md,mdx}` in this repo.
