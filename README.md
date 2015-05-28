# npm-weekly-md

[![NPM version][npm-image]][npm-url]
[![Dependency Status][david_img]][david_site]

> Transform npm-weekly to markdown

## Install

```sh
$ npm install npm-weekly-md
```

## Usage

```js
var parse = require('npm-weekly-md')
var markdown = parse('http://blog.npmjs.org/post/119399973890/npm-weekly-17')
```

In command line:

```
npm-weekly-md http://blog.npmjs.org/post/119399973890/npm-weekly-17 > npm-weekly-17.md
```

## License
MIT © [C. T. Lin](https://github.com/chentsulin)

[npm-image]: https://img.shields.io/npm/v/npm-weekly-md.svg?style=flat-square
[npm-url]: https://npmjs.org/package/npm-weekly-md
[david_img]: https://img.shields.io/david/chentsulin/npm-weekly-md.svg
[david_site]: https://david-dm.org/chentsulin/npm-weekly-md
