# @farischt/eslint-config

This library contains the [ESLint](https://eslint.org) configuration used by [Farischt](https://faris.chtatou.org).

## Installing the library

```bash
npm install --save-dev @farischt/eslint-config
```

## Using the library

To use the library, you'll need to add the following to your `.eslintrc.json` file:

```json
{
  "extends": "@farischt"
}
```

## Publishing updates

In order to publish an update of the library, you'll need to:

- Update the version field in the `package.json` file;
- Stage and commit all changes;
- Tag the new commit with the new version number; and
- Push all changes to the GitHub repository.

This can be done using the following commands:

```bash
npm version patch
git push origin main --tags
```

A GitHub Actions workflow will then automatically publish the package to the NPM registry.
