# eslint-config-killara
[![NPM version](https://img.shields.io/npm/v/eslint-config-killara.svg)](https://www.npmjs.com/package/eslint-config-killara)
[![build status](https://img.shields.io/travis/killara/eslint-config-killara/master.svg)](https://travis-ci.org/killara/eslint-config-killara)
[![dependency status](https://img.shields.io/david/dev/killara/eslint-config-killara.svg)](https://david-dm.org/killara/eslint-config-killara?type=dev)
[![downloads](https://img.shields.io/npm/dt/eslint-config-killara.svg)](https://www.npmjs.com/package/eslint-config-killara)

[Killara](https://www.npmjs.com/package/killara)'s ESLint config, based on [Standard](https://www.npmjs.com/package/eslint-config-standard)

## Usage
Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

To use the Killara shareable config, first run this:

```bash
npm install --save-dev eslint-config-killara eslint-config-standard eslint-plugin-standard eslint-plugin-promise eslint-plugin-import eslint-plugin-node
```

Then, add this to your .eslintrc file:

```
{
  "extends": "killara"
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.


## License

MIT
