# Contributing to Furlpay

Thanks for helping build the Furlpay ecosystem — SDKs, CLI, Elements, Account
Kit, the MCP server, and the x402 facilitator. This guide applies org-wide.

## Ways to contribute

- **Report bugs** — open an issue with a minimal reproduction and your environment.
- **Request features** — open an issue describing the use case, not just the fix.
- **Pull requests** — keep them focused; one concern per PR. Add or update tests
  where the package has them. Match the existing code style.
- **Questions** — use GitHub Discussions on the relevant repo.

## Development

Most packages are plain TypeScript with zero or minimal dependencies:

```bash
npm install
npm run build
npm test        # where the package defines tests
```

## Pull request checklist

- [ ] The build passes (`npm run build`) and tests pass (`npm test`).
- [ ] New behavior has a test, or you've explained why it can't be tested.
- [ ] Public API changes are reflected in the README.
- [ ] Commits are scoped and clearly described.

## Security

Do **not** open public issues for vulnerabilities. Email **hello@furlpay.com**
(see `SECURITY.md`). We aim to acknowledge within 48 hours.

## Licensing

By contributing, you agree your contributions are licensed under the MIT license
of the repository you're contributing to. These packages are developed in the
internal Furlpay monorepo and mirrored publicly; maintainers sync accepted PRs
upstream.
