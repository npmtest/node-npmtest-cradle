# npmtest-cradle

#### test coverage for  [cradle (v0.7.1)](https://github.com/flatiron/cradle#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cradle.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cradle) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cradle.svg)](https://travis-ci.org/npmtest/node-npmtest-cradle)

#### the high-level, caching, CouchDB library

[![NPM](https://nodei.co/npm/cradle.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cradle)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cradle/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cradle/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cradle/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cradle/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cradle/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cradle/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cradle/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cradle/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cradle/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cradle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cradle/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cradle/build/test-report.html](https://npmtest.github.io/node-npmtest-cradle/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cradle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cradle/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cradle/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cradle/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cradle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cradle/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cradle/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cradle/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alexis Sellier"
    },
    "bugs": {
        "url": "https://github.com/flatiron/cradle/issues"
    },
    "contributors": [
        {
            "name": "Charlie Robbins"
        },
        {
            "name": "Maciej Malecki"
        }
    ],
    "dependencies": {
        "follow": "0.11.x",
        "request": "2.x.x",
        "vargs": "0.1.0"
    },
    "description": "the high-level, caching, CouchDB library",
    "devDependencies": {
        "async": "~0.9.0",
        "proxyquire": "^1.7.3",
        "sinon": "^1.17.2",
        "vows": "0.8.x"
    },
    "directories": {},
    "dist": {
        "shasum": "4c0b354aadfb7d4ae2a8f5cdbbfd63a345061044",
        "tarball": "https://registry.npmjs.org/cradle/-/cradle-0.7.1.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "20534493ae3aa0e6d80201a24b48acf19a27e4ac",
    "homepage": "https://github.com/flatiron/cradle#readme",
    "keywords": [
        "couchdb",
        "database",
        "couch"
    ],
    "license": "MIT",
    "main": "./lib/cradle",
    "maintainers": [
        {
            "name": "cloudhead"
        },
        {
            "name": "indexzero"
        },
        {
            "name": "nawitus"
        }
    ],
    "name": "cradle",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/flatiron/cradle.git"
    },
    "scripts": {
        "test": "node test/helpers/seed.js && vows --spec"
    },
    "url": "http://cloudhead.io/cradle",
    "version": "0.7.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
