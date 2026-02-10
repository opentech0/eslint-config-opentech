# Installation

```bash
yarn add @opentech0/eslint-config-opentech -D
```

# Usage

`.eslintrc.json`
```json
{
  "extends": "@opentech0/eslint-config-opentech"
}
```

`package.json`
```json
{
  "scripts": {
    "eslint": "./node_modules/.bin/eslint '**/*.js'",
    "eslint:fix": "./node_modules/.bin/eslint '**/*.js' --fix"
  }
}
```

# Extending the config

Simply add a `"rules"` key to your config, then add your overrides and additions there.

For example, to turn off the `no-console` rule:

```json
{
  "extends": "@opentech0/eslint-config-opentech",
  "rules": {
    "no-console": "off"
  }
}
```
"# eslint-config-opentech" 
