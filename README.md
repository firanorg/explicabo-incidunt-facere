# @firanorg/explicabo-incidunt-facere <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@firanorg/explicabo-incidunt-facere');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@firanorg/explicabo-incidunt-facere
[npm-version-svg]: https://versionbadg.es/inspect-js/@firanorg/explicabo-incidunt-facere.svg
[deps-svg]: https://david-dm.org/inspect-js/@firanorg/explicabo-incidunt-facere.svg
[deps-url]: https://david-dm.org/inspect-js/@firanorg/explicabo-incidunt-facere
[dev-deps-svg]: https://david-dm.org/inspect-js/@firanorg/explicabo-incidunt-facere/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@firanorg/explicabo-incidunt-facere#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@firanorg/explicabo-incidunt-facere.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@firanorg/explicabo-incidunt-facere.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@firanorg/explicabo-incidunt-facere.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@firanorg/explicabo-incidunt-facere
[codecov-image]: https://codecov.io/gh/inspect-js/@firanorg/explicabo-incidunt-facere/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@firanorg/explicabo-incidunt-facere/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@firanorg/explicabo-incidunt-facere
[actions-url]: https://github.com/firanorg/explicabo-incidunt-facere/actions
