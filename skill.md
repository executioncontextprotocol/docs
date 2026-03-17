---
name: execution-control-protocol-docs
description: >-
  Use this skill when you need to understand or write documentation for ECP
  (Execution Control Protocol): concepts, manifests (Contexts), security and
  policies, CLI usage, and comparisons to other stacks.
---

# ECP (Execution Control Protocol) documentation skill

## What ECP is

ECP (Execution Control Protocol) is an open standard for defining, packaging, versioning, and running execution environments for AI agents. ECP is designed to embrace and extend MCP (Model Context Protocol), not replace it.

## When to use this skill

- You are writing or editing ECP docs (MDX) and want consistent terminology and tone.
- You need to explain where ECP fits in the agent stack (MCP, frameworks, execution control).
- You are adding new pages or updating navigation and internal links.
- You are improving docs for first-time users (quickstarts, examples, and common workflows).

## Key pages to reference

- Homepage: `/`
- Quickstart: `/getting-started/quickstart`
- Concepts: `/learn/concepts`
- Relationship to MCP: `/learn/relationship-to-mcp`
- Security: `/learn/security`
- CLI reference: `/reference/cli`
- Alternatives and comparisons: `/alternatives`

## Writing and publishing rules

- Use a technically friendly but light voice. Keep it forward-moving: goal, concept, next step.
- No emojis in docs.
- First mention on a page: write "ECP (Execution Control Protocol)". After that, vary naturally.
- Prefer installed CLIs over one-off runners. Show one-time install/link steps, then commands.
- Add helpful internal links (2 to 5) to keep readers moving.

## How to contribute safely

- Preview locally with `mint dev` from the docs repo root (where `docs.json` lives).
- Check links before shipping with `mint broken-links`.
