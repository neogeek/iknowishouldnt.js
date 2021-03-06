# I Know I Shouldn't

> A micro-library that contains snippets of code useful for modifying strings and arrays. While it does modify the native prototype of String and Array, it does so with non-enumerable methods.

[![](https://api.travis-ci.org/neogeek/iknowishouldnt.js.svg?style=flat)](https://travis-ci.org/neogeek/iknowishouldnt.js)
[![](https://david-dm.org/neogeek/iknowishouldnt.js/dev-status.svg?style=flat)](https://david-dm.org/neogeek/iknowishouldnt.js?type=dev)
[![Greenkeeper badge](https://badges.greenkeeper.io/neogeek/iknowishouldnt.js.svg)](https://greenkeeper.io/)
[![Latest Documentation](https://doxdox.org/images/badge-flat.svg)](https://doxdox.org/neogeek/iknowishouldnt.js)

## String.prototype.format

Returns a formatted string.

| Character | Type |
| --------- | ---- |
| s | String |
| i | Integer |
| d | Digit |
| f | Float |

```javascript
'rgba(%i, %i, %i, %f)'.format(255, 0, 0, 0.5);
```

```javascript
'Hello %s'.format('World!');
```

## Array.prototype.chunk

Split an array into smaller chunks.

```javascript
[1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11].chunk(2);
```
