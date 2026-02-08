# Sundew documentation agent instructions

## Project context

Sundew is an open-source honeypot framework that detects and fingerprints autonomous AI agents. The documentation lives at docs.sundew.sh and is built with Mintlify.

## Mintlify basics

- Configuration lives in `docs.json` -check it before making structural changes
- Use MDX format for all documentation pages
- Run `mint dev` locally to preview changes
- Run `mint broken-links` to check for broken links

## Content structure

- **Getting started**: `index.mdx`, `quickstart.mdx` -entry points for new users
- **Concepts**: `concepts/` -how Sundew works (architecture, persona engine, traps, fingerprinting)
- **Guides**: `guides/` -practical how-to docs (configuration, deployment, personas, querying)
- **Security**: `security/` -threat model and ethical use
- **Reference**: `reference/` -CLI commands, config reference, contributing guide

## Style guidelines

- Use active voice and second person ("you")
- Keep sentences concise
- Use sentence case for headings
- Include code examples with realistic values from Sundew
- Use Mintlify components: `<Tabs>`, `<Steps>`, `<CardGroup>`, `<Warning>`, `<Info>`

## What to avoid

- Don't edit `docs.json` without understanding the navigation structure
- Don't remove existing pages without checking for inbound links
- Don't use HTML when an MDX component exists
- Don't add pages to navigation that don't exist yet
- Don't include real API keys, tokens, or credentials in examples
