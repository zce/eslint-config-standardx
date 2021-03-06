# eslint-config-standardx

[![License][license-img]][license-url]
[![NPM Downloads][downloads-img]][downloads-url]
[![NPM Version][version-img]][version-url]
[![Dependency Status][dependency-img]][dependency-url]
[![devDependency Status][devdependency-img]][devdependency-url]
[![Code Style][style-img]][style-url]

> An extension of eslint-config-standard without peer dependencies, made for JavaScript.

## Installation

```shell
$ npm install eslint eslint-config-standardx --save-dev

# or yarn
$ yarn add eslint eslint-config-standardx -dev
```

## Usage

In your eslint config:

```javascript
// .eslintrc.js
module.exports = {
  extends: 'standardx'
}
```

Example command line usage for ESLint v7:

```shell
$ npx eslint .
```

## Motivation

Due to [a known limitation in ESLint](https://github.com/eslint/eslint/issues/3458). Many [ESLint shareable config](https://eslint.org/docs/developer-guide/shareable-configs) require a large number of peer dependencies. This leads to many inconveniences for developers to use.

My idea is to ignore these problems 😅, and install these peer dependencies directly.

Because I think these problems no longer exist in modern npm.

So this module is just a dependencies wrapper, internal use of [eslint-config-standard](https://github.com/standard/eslint-config-standard) and its peer dependencies.

## Related

- [zce/eslint-config-standard-ts](https://github.com/zce/eslint-config-standard-ts) - An extension of eslint-config-standard without peer dependencies, made for TypeScript.

## Contributing

1. **Fork** it on GitHub!
2. **Clone** the fork to your own machine.
3. **Checkout** your feature branch: `git checkout -b my-awesome-feature`
4. **Commit** your changes to your own branch: `git commit -am 'Add some feature'`
5. **Push** your work back up to your fork: `git push -u origin my-awesome-feature`
6. Submit a **Pull Request** so that we can review your changes.

> **NOTE**: Be sure to merge the latest from "upstream" before making a pull request!

## License

[MIT](LICENSE) &copy; [zce](https://zce.me)



[license-img]: https://img.shields.io/github/license/zce/eslint-config-standardx
[license-url]: https://github.com/zce/eslint-config-standardx/blob/master/LICENSE
[downloads-img]: https://img.shields.io/npm/dm/eslint-config-standardx
[downloads-url]: https://npmjs.org/package/eslint-config-standardx
[version-img]: https://img.shields.io/npm/v/eslint-config-standardx
[version-url]: https://npmjs.org/package/eslint-config-standardx
[dependency-img]: https://img.shields.io/david/zce/eslint-config-standardx
[dependency-url]: https://david-dm.org/zce/eslint-config-standardx
[devdependency-img]: https://img.shields.io/david/dev/zce/eslint-config-standardx
[devdependency-url]: https://david-dm.org/zce/eslint-config-standardx?type=dev
[style-img]: https://img.shields.io/badge/code_style-standard-brightgreen
[style-url]: https://standardx.com
