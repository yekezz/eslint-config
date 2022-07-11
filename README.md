# eslint-config

- basic
- vue
- react
- typescript

## Install

```bash
pnpm i -D eslint @enochzzz/eslint-config
```

## Configure

in your `.eslintrc`

```json
{
  "extends": "@enochzzz"
}
```

> You don't need `.eslintignore` normally as it has been provided by the preset.

### Add script for package.json

For example:

```json
{
  "scripts": {
    "lint": "eslint .",
    "lint:fix": "eslint . --fix"
  }
}
```

### Config VS Code auto fix

Create `.vscode/settings.json`

```json
{
  "prettier.enable": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  }
}
```


## reference

- @antfu/eslint-config (安法师牛皮)
