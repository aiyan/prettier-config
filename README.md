# `@aiyan/prettier-config`

A [Prettier](https://prettier.io) configuration with reasonable defaults for TypeScript and React apps.

## Usage

### Installation

```bash
npm i -D @aiyan/prettier-config
```

### Using the configuration as-is

Edit `package.json`:

```jsonc
{
  // ...
  "prettier": "@aiyan/prettier-config"
}
```

### Extending the configuration

Use a `.prettierrc.js` file:

```javascript
module.exports = {
  ...require('@aiyan/prettier-config'),
  arrowParens: "always",
};
```
