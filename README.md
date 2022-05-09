# `@primer-io/prettier-config`

Shared config for Prettier for frontend projects @ primer.io

# How to use

**Install**

```
yarn add --dev @primer-io/prettier-config
```

**a) use with package.json**

```
// package.json
{
  ...,
  "prettier": "@primer-io/prettier-config"
}
```

**b) use with .prettierrc.json**

```
// .prettierrc.json
"@primer-io/prettier-config"
```

**Overrides**

Options above do not allow to extend the configuration. For that, you need to use following approach:

```
// .prettierrc.js
module.exports = {
  ...require("@primer-io/prettier-config"),
  // custom overrides here
};
```

[More info on shared configurations](https://prettier.io/docs/en/configuration.html#sharing-configurations)