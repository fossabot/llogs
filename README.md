# LLOGS

> A logger that logs the information of your files, and puts all of the info in a generated text file.

[![Coverage Status](https://coveralls.io/repos/github/jvn11/llogs/badge.svg?branch=main)](https://coveralls.io/github/jvn11/llogs?branch=main)
[![Build Status](https://travis-ci.com/jvn11/llogs.svg?branch=main)](https://travis-ci.com/jvn11/llogs)
[![NPM Version](https://img.shields.io/npm/v/llogs.svg)](https://npmjs.com/package/llogs)

## Install

`npm install --save llogs`

## Use

`package.json`:

```json
// ...

"scripts": {
  "llog": "llog -f path/to/your/file.js"
}

// ...
```

## Flags

**NOTE** that llogs can log info about directories and files, and we have different flags for that:

### `-f, --file <filename>`: Watches a file

Example:

```shell
$ npx llog -f path/to/file.txt
```

### `-d, --dir <dirname>`: Watches a directory

Example:

```shell
$ npx llog -d path/to/dir
```

### Output

<br />

```
$ npx llog -d my/example/file.txt
Ready for changes (howlong | timeinms)
```

## License

Under the MIT License