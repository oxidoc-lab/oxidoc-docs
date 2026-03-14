# oxidoc-docs

The official documentation site for [Oxidoc](https://github.com/oxidoc-lab/oxidoc), deployed at [oxidoc-lab.github.io](https://oxidoc-lab.github.io).

This project was initially scaffolded with `oxidoc init` and then updated to serve as the reference implementation of an Oxidoc documentation site. It demonstrates real-world usage of Oxidoc's features including sections, OpenAPI integration, custom components, and deployment.

The GitHub Actions workflow (`.github/workflows/deploy.yml`) serves as an example of how to build and deploy an Oxidoc site to GitHub Pages.

## Development

```bash
# Install oxidoc
cargo install oxidoc-cli

# Start dev server
oxidoc dev

# Build for production
oxidoc build
```

## License

MIT
