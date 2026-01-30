# Polos Documentation

Documentation for Polos, a durable execution platform for AI agents.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation changes locally:

```bash
npm i -g mint
```

Run the development server at the root of the documentation directory:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Project Structure

- `docs.json` - Main configuration file for navigation and settings
- `index.mdx` - Landing page
- `fundamentals/` - Core concepts and fundamentals
- `agents/` - Agent-specific documentation
- `workflows/` - Workflow documentation
- `guides/` - Guides and examples
- `observability/` - Observability and tracing
- `community/` - Community resources

## Publishing Changes

Changes are automatically deployed to production after pushing to the default branch via the Mintlify GitHub integration.

## Troubleshooting

- **Dev environment not running:** Run `mint update` to ensure you have the latest CLI version
- **Page loads as 404:** Make sure you're running `mint dev` in the directory containing `docs.json`
- **Styling issues:** Check `styles.css` for custom CSS overrides

## Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- [Polos GitHub Repository](https://github.com/polos-dev/polos)
