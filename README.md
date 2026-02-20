# FreeSH Documentation

This folder contains the Mintlify documentation site for FreeSH.

## Local Development

1. Install Mintlify CLI:

```bash
npm i -g mint
```

2. Start docs preview from this `docs/` directory (where `mint.json` exists):

```bash
mint dev
```

3. Open `http://localhost:3000`.

## Structure

- `mint.json`: site config, navigation, branding
- `introduction.mdx`: product overview
- `getting-started.mdx`: installation and first-use flow
- `*/overview.mdx`: feature guides by area

## Writing Guidelines

- Prefer task-based sections (`How to ...`, `Troubleshooting`) over marketing copy.
- Keep commands copy/paste ready.
- Reflect current product behavior, including feature flags.
- If behavior is platform-specific, call it out explicitly.

## Publishing

Docs deploy automatically when changes are pushed to the default branch (via Mintlify GitHub integration).
