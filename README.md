Not much to see here, just my personal dotfiles for EcmaScript

# package.json

## Client + Server style Project

```bash
yarn add babel-polyfill

yarn add --dev babel-eslint concurrently eslint eslint-config-airbnb-base eslint-import-resolver-babel-module eslint-plugin-import eslint-plugin-promise babel-cli babel-core babel-plugin-module-resolver babel-plugin-transform-class-properties babel-preset-env
```

```json
{
  "start": "concurrently \"npm run server\" \"npm run client\"",
  "server": "babel-node ./server",
  "client": "node start-client.js"
}
```

# TODO

Should make different repos for different project styles instead of this.
