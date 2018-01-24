# sass-makedepend

[![npm](https://img.shields.io/npm/v/sass-makedepend.svg)](
    https://www.npmjs.com/package/sass-makedepend
) [![node](https://img.shields.io/node/v/sass-makedepend.svg)](
    https://nodejs.org/
) [![Libraries.io for GitHub](https://img.shields.io/librariesio/github/dead-beef/sass-makedepend.svg)](
    https://libraries.io/npm/sass-makedepend/
) [![license](https://img.shields.io/github/license/dead-beef/sass-makedepend.svg)](
    https://github.com/dead-beef/sass-makedepend/blob/master/LICENSE
)

## Overview

Makefile dependency generator for [Sass](http://sass-lang.com/).

## Requirements

- [`Node.js`](https://nodejs.org/)
- [`NPM`](https://nodejs.org/)

## Installation

```bash
npm install sass-makedepend
```

## Usage

```bash
  Usage: sass-makedepend [options] <file...>


  Options:

    -V, --version            output the version number
    -I, --load-path <paths>  sass load paths separated with ":" (default: "./node_modules")
    -p, --prefix <prefix>    target file prefix (default: dirname(file) + "/")
    -o, --suffix <suffix>    target file suffix (default: ".css")
    -i, --ignore <regexp>    ignore dependencies with absolute path matching <regexp>
    -m, --ignore-modules     ignore dependencies from module.paths
    -r, --relative           output dependency paths relative to current directory
    -h, --help               output usage information
```

## Licenses

* [`sass-makedepend`](https://github.com/dead-beef/sass-makedepend/blob/master/LICENSE)
