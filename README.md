# oxidoc-docs

The official documentation site for [Oxidoc](https://github.com/oxidoc-lab/oxidoc), deployed at [oxidoc-lab.github.io](https://oxidoc-lab.github.io).

## Development

```bash
# Install oxidoc
curl -fsSL https://oxidoc.dev/install.sh | sh

# Start dev server
oxidoc dev

# Build for production
oxidoc build
```

## Deployment

Pushes to `main` trigger a GitHub Actions workflow that builds the site and deploys to GitHub Pages using the native `actions/deploy-pages` action.

## License

MIT
