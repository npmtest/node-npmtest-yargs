# npmtest-yargs

#### test coverage for  [yargs (v7.1.0)](http://yargs.js.org/)  [![npm package](https://img.shields.io/npm/v/npmtest-yargs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-yargs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-yargs.svg)](https://travis-ci.org/npmtest/node-npmtest-yargs)

#### yargs the modern, pirate-themed, successor to optimist.

[![NPM](https://nodei.co/npm/yargs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yargs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-yargs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-yargs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-yargs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-yargs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-yargs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-yargs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-yargs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-yargs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-yargs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-yargs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-yargs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-yargs/build/test-report.html](https://npmtest.github.io/node-npmtest-yargs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-yargs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-yargs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-yargs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yargs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yargs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yargs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-yargs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-yargs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/yargs/yargs/issues"
    },
    "dependencies": {
        "camelcase": "^3.0.0",
        "cliui": "^3.2.0",
        "decamelize": "^1.1.1",
        "get-caller-file": "^1.0.1",
        "os-locale": "^1.4.0",
        "read-pkg-up": "^1.0.1",
        "require-directory": "^2.1.1",
        "require-main-filename": "^1.0.1",
        "set-blocking": "^2.0.0",
        "string-width": "^1.0.2",
        "which-module": "^1.0.0",
        "y18n": "^3.2.1",
        "yargs-parser": "^5.0.0"
    },
    "description": "yargs the modern, pirate-themed, successor to optimist.",
    "devDependencies": {
        "chai": "^3.4.1",
        "chalk": "^1.1.3",
        "coveralls": "^2.11.11",
        "cpr": "^2.0.0",
        "cross-spawn": "^5.0.1",
        "es6-promise": "^4.0.2",
        "hashish": "0.0.4",
        "mocha": "^3.0.1",
        "nyc": "^10.0.0",
        "rimraf": "^2.5.0",
        "standard": "^8.6.0",
        "standard-version": "^3.0.0",
        "which": "^1.2.9"
    },
    "directories": {},
    "dist": {
        "shasum": "6ba318eb16961727f5d284f8ea003e8d6154d0c8",
        "tarball": "https://registry.npmjs.org/yargs/-/yargs-7.1.0.tgz"
    },
    "engine": {
        "node": ">=0.10"
    },
    "files": [
        "index.js",
        "yargs.js",
        "lib",
        "locales",
        "completion.sh.hbs",
        "LICENSE"
    ],
    "gitHead": "e7359d632595c3a5fcfd691994859b66e8943c85",
    "greenkeeper": {
        "ignore": [
            "string-width",
            "read-pkg-up",
            "camelcase"
        ]
    },
    "homepage": "http://yargs.js.org/",
    "keywords": [
        "argument",
        "args",
        "option",
        "parser",
        "parsing",
        "cli",
        "command"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "bcoe"
        },
        {
            "name": "chevex"
        },
        {
            "name": "nexdrew"
        },
        {
            "name": "nylen"
        }
    ],
    "name": "yargs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/yargs/yargs.git"
    },
    "scripts": {
        "coverage": "nyc report --reporter=text-lcov | coveralls",
        "pretest": "standard",
        "release": "standard-version",
        "test": "nyc --cache mocha --require ./test/before.js --timeout=8000 --check-leaks"
    },
    "standard": {
        "ignore": [
            "**/example/**"
        ]
    },
    "version": "7.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
