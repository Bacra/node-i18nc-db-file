I18NC-DB-FILE
==============


[![NPM Version][npm-image]][npm-url]
[![NPM Downloads][downloads-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Coveralls][coveralls-image]][coveralls-url]
[![NPM License][license-image]][npm-url]

# Install

```
npm install i18nc-db-file --save
```

# Useage

```javascript
var dbfile = require('i18nc-db-file');

dbfile([obj, file, dir]).then(function(dbTranslate) {});
var dbTranslate = dbfile.sync([obj, file, dir]);
```



[npm-image]: http://img.shields.io/npm/v/i18nc-db-file.svg
[downloads-image]: http://img.shields.io/npm/dm/i18nc-db-file.svg
[npm-url]: https://www.npmjs.org/package/i18nc-db-file
[travis-image]: http://img.shields.io/travis/Bacra/node-i18nc-db-file/master.svg?label=linux
[travis-url]: https://travis-ci.org/Bacra/node-i18nc-db-file
[coveralls-image]: https://img.shields.io/coveralls/Bacra/node-i18nc-db-file.svg
[coveralls-url]: https://coveralls.io/github/Bacra/node-i18nc-db-file
[license-image]: http://img.shields.io/npm/l/i18nc-db-file.svg
