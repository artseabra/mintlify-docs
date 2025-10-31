# ifthis⏐software studio Documentation

Documentation hub for all software tools built by **ifthis⏐software studio**. This documentation site is deployed to `https://docs.ifth.is` and provides comprehensive guides for our software products.

## About

This repository contains the documentation for ifthis⏐software studio's software tools. Currently, the documentation includes:

- **copprOS**: The Digital Identity OS - operating system for digital identity with components including Coppr Link, Coppr Card, and Dashboard

More tools from ifthis⏐software studio will be added as they're released.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Install our GitHub app from your [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to propagate changes from your repo to your deployment. Changes are deployed to production automatically after pushing to the default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Mintlify documentation](https://mintlify.com/docs)
