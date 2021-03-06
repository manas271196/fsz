# fsz [![Build Status](https://travis-ci.org/HarryStevens/fsz.svg?branch=master)](https://travis-ci.org/HarryStevens/fsz) [![Coverage Status](https://coveralls.io/repos/github/HarryStevens/fsz/badge.svg?branch=master)](https://coveralls.io/github/HarryStevens/fsz?branch=master)

This library contains functions to supplement [Node's File System module](https://nodejs.org/api/fs.html#fs_file_system). It also exports the File System module itself, so you don't have to `require("fs")` either.

## Installation
```bash
npm install fsz --save
```
```js
var fsz = require("fsz");
```

## Usage

<a name="readJSON" href="#readJSON">#</a> fsz.<b>getDirectories</b>(<i>string</i>)

Gets a list of directories in another directory.

<a name="readJSON" href="#readJSON">#</a> fsz.<b>readJSON</b>(<i>string</i>)

Reads and parses a JSON file.


## Tests

```bash
npm test
```

## Contributing

In lieu of a formal style guide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code.