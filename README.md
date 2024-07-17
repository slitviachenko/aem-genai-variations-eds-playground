# EDS Playground
The EDS Playground project for testing the Sidekick integration, etc.

## Environments
- Preview: https://main--aem-genai-variations-eds-playground--slitviachenko.hlx.page/
- Live: https://main--aem-genai-variations-eds-playground--slitviachenko.hlx.live/

## Installation

```sh
npm i
```

## Linting

```sh
npm run lint
```

## Local development

1. Create a new repository based on the `aem-boilerplate` template and add a mountpoint in the `fstab.yaml`
1. Add the [AEM Code Sync GitHub App](https://github.com/apps/aem-code-sync) to the repository
1. Install the [AEM CLI](https://github.com/adobe/helix-cli): `npm install -g @adobe/aem-cli`
1. Start AEM Proxy: `aem up` (opens your browser at `http://localhost:3000`)
1. Open the `aem-genai-variations-eds-playground` directory in your favorite IDE and start coding :)

## Useful links
- https://www.aem.live/docs/sidekick
- https://www.aem.live/docs/setup-adobe-sharepoint
