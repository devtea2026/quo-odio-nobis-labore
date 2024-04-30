# @devtea2026/quo-odio-nobis-labore <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple list of possible Typed Array names.

## Example

```js
const assert = require('assert');

const names = require('@devtea2026/quo-odio-nobis-labore');

assert(Array.isArray(names));
assert(names.every(name => (
    typeof name === 'string'
    && typeof globalThis[name] === 'function'
    && globalThis[name].name === name
)));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@devtea2026/quo-odio-nobis-labore
[npm-version-svg]: https://versionbadg.es/ljharb/@devtea2026/quo-odio-nobis-labore.svg
[deps-svg]: https://david-dm.org/ljharb/@devtea2026/quo-odio-nobis-labore.svg
[deps-url]: https://david-dm.org/ljharb/@devtea2026/quo-odio-nobis-labore
[dev-deps-svg]: https://david-dm.org/ljharb/@devtea2026/quo-odio-nobis-labore/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@devtea2026/quo-odio-nobis-labore#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@devtea2026/quo-odio-nobis-labore.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@devtea2026/quo-odio-nobis-labore.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@devtea2026/quo-odio-nobis-labore.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@devtea2026/quo-odio-nobis-labore
[codecov-image]: https://codecov.io/gh/ljharb/@devtea2026/quo-odio-nobis-labore/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@devtea2026/quo-odio-nobis-labore/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@devtea2026/quo-odio-nobis-labore
[actions-url]: https://github.com/devtea2026/quo-odio-nobis-labore/actions
