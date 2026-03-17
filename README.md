# Execution Control Protocol docs

This repository contains the documentation site for **ECP (Execution Control Protocol)**, built with [Mintlify](https://mintlify.com).

## What’s in here

- **Site config**: `docs.json`
- **Pages**: `**/*.mdx`
- **Comparisons**: `alternatives/` (ECP vs other stacks)
- **Project writing rules**: `AGENTS.md` and `.cursor/rules/docs-voice-seo.mdc`

## Develop locally

1. Install the Mintlify CLI:

```bash
npm i -g mint
```

2. From this repo root (where `docs.json` lives), run:

```bash
mint dev
```

Then open `http://localhost:3000`.

## Check for broken links

From the repo root:

```bash
mint broken-links
```

## AI-assisted writing (optional)

If you use an agent that supports the Skills CLI, you can install Mintlify’s docs skill:

```bash
npm install -g skills
skills add https://mintlify.com/docs
```

You can also install the ECP documentation skill from the live site:

```bash
npm install -g skills
skills add https://executioncontrolprotocol.io
```

## Contributing

See `CONTRIBUTING.md`.
