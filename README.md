# eslint-config-brainhub

[![npm version](https://img.shields.io/npm/v/eslint-config-brainhub.svg)](https://www.npmjs.com/package/eslint-config-brainhub)

Shared eslint config for BrainHub projects

## Usage

### For ES5 libs

Install peer dependencies via npx (npm 5+)
```bash
npx install-peerdeps --dev eslint-config-brainhub
```
or
```bash
yarn add --dev eslint-config-brainhub eslint-config-standard eslint-plugin-promise eslint-plugin-node eslint-plugin-es5 eslint-plugin-standard eslint-plugin-security eslint-plugin-import eslint-plugin-import-helpers eslint
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
yarn add --dev eslint-config-brainhub eslint-plugin-react-hooks
```
Modify your .eslintrc:

```json
{
  "extends": "brainhub/react-hooks"
}
```

