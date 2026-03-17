> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill (prefer installed CLIs over one-off runners):
> `npm install -g skills && skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

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
