# Leadey API Docs

The documentation site for the [Leadey](https://leadey.ai) API — signal-driven lead generation that sources, qualifies, and reaches the right people, automatically.

Built on [Mintlify](https://mintlify.com). Branding (logos, color tokens, DM Sans, the cinematic dark theme) follows the Leadey Design System: configuration in `docs.json`, custom styling in `style.css`, logos in `logo/`.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally:

```
npm i -g mint
```

Run the following command at the root of the docs, where `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## AI-assisted writing

Set up your AI coding tool to work with Mintlify:

```bash
npx skills add https://mintlify.com/docs
```

This installs Mintlify's documentation skill (component reference, writing standards, workflow guidance) for tools like Claude Code, Cursor, and Windsurf. See `AGENTS.md` for Leadey-specific terminology and voice.

## Publishing changes

Changes are deployed to production automatically after pushing to the default branch (via the Mintlify GitHub app connected from the [Mintlify dashboard](https://dashboard.mintlify.com)).

## Need help?

### Troubleshooting

- If your dev environment isn't running: run `mint update` to get the latest CLI.
- If a page loads as a 404: make sure you are running in a folder with a valid `docs.json`.

### Resources

- [Mintlify documentation](https://mintlify.com/docs)
- [Leadey](https://leadey.ai) · [Dashboard](https://app.leadey.ai)
