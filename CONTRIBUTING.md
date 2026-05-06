# Contribute to ChefOS docs

Pages are MDX files with YAML frontmatter. Navigation is configured in `docs.json`.

## Local workflow

1. Install the Mintlify CLI: `npm i -g mint`
2. Run `mint dev` from the repository root.
3. Update MDX pages and `docs.json` together when adding pages.
4. Run `mint broken-links` before opening a PR.

## Style

- Use active voice and address the reader directly.
- Keep sentences concise.
- Use sentence case for headings.
- Use code formatting for paths, commands, env vars, and API routes.
