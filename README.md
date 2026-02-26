# VecGrep Docs

Documentation for [VecGrep](https://github.com/VecGrep/VecGrep) — Cursor-style semantic code search as an MCP plugin for Claude Code.

Built with [Mintlify](https://mintlify.com).

## Development

Install the Mintlify CLI:

```bash
npm i -g mintlify
```

Preview locally:

```bash
mintlify dev
```

## Structure

```
mint.json                        ← Mintlify configuration
introduction.mdx
installation.mdx
quickstart.mdx
tools/
  index-codebase.mdx
  search-code.mdx
  get-index-status.mdx
configuration/
  environment-variables.mdx
  backends.mdx
  supported-languages.mdx
reference/
  architecture.mdx
  index-location.mdx
  acknowledgements.mdx
```

## Contributing

To update the docs, edit the relevant `.mdx` file and open a PR. Changes merged to `main` are deployed automatically.
