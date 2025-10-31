# copprOS Documentation

Documentation site for **copprOS** - The Digital Identity OS. This documentation is deployed to `https://docs.ifth.is/copprOS` and provides comprehensive guides for using the Coppr platform.

## About copprOS

copprOS is the brand-new operating system behind the entire Coppr platform, enabling lifelong connections crafted to perfection. The documentation covers the three core components:

- **Coppr Link**: Your interactive digital profile that makes a lasting first impression
- **Coppr Card**: The sustainable business card made from recycled materials
- **Coppr Dashboard**: Manage your profile on the fly from any device

This repository contains the complete documentation structure and content for the copprOS platform.

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
