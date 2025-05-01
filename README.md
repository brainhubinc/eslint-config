# @brainhubinc/eslint-config

[![npm version](https://img.shields.io/npm/v/@brainhubinc/eslint-config.svg)](https://www.npmjs.com/package/@brainhubinc/eslint-config)

Shared eslint config for BrainHub projects

## Usage

### For ES5 libs

Install peer dependencies via npx (npm 5+)
```bash
npx install-peerdeps --dev @brainhubinc/eslint-config
```
or
```bash
yarn add --dev @brainhubinc/eslint-config eslint-config-standard eslint-plugin-promise eslint-plugin-node eslint-plugin-es5 eslint-plugin-standard eslint-plugin-security eslint-plugin-import eslint-plugin-import-helpers eslint
```
Modify your .eslintrc:

```json
{
  "extends": "brainhub/lib"
}
```
### For React Hooks

Install:
```bash
yarn add --dev @brainhubinc/eslint-config eslint-plugin-react-hooks
```
Modify your .eslintrc:

```json
{
  "extends": "brainhub/react-hooks"
}
```

