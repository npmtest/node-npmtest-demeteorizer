# npmtest-demeteorizer

#### basic test coverage for  [demeteorizer (v4.3.0)](https://github.com/OnModulus/demeteorizer#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-demeteorizer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-demeteorizer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-demeteorizer.svg)](https://travis-ci.org/npmtest/node-npmtest-demeteorizer)

#### Converts a Meteor app into a "standard" Node.js application.

[![NPM](https://nodei.co/npm/demeteorizer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/demeteorizer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-demeteorizer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-demeteorizer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-demeteorizer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-demeteorizer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-demeteorizer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-demeteorizer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-demeteorizer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-demeteorizer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-demeteorizer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-demeteorizer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-demeteorizer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-demeteorizer/build/test-report.html](https://npmtest.github.io/node-npmtest-demeteorizer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-demeteorizer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-demeteorizer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-demeteorizer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-demeteorizer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-demeteorizer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-demeteorizer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-demeteorizer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-demeteorizer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Modulus"
    },
    "bin": {
        "demeteorizer": "./bin/demeteorizer"
    },
    "bugs": {
        "url": "https://github.com/OnModulus/demeteorizer/issues"
    },
    "contributors": [
        {
            "name": "Brandon Cannaday"
        },
        {
            "name": "Bret Fisher"
        },
        {
            "name": "Matt Hernandez"
        },
        {
            "name": "Tarang Patel"
        },
        {
            "name": "Vincil Bishop"
        }
    ],
    "dependencies": {
        "commander": "2.9.0",
        "cross-spawn": "5.0.1",
        "fs-extra": "0.30.0",
        "hoek": "4.x.x",
        "semver": "5.1.0"
    },
    "description": "Converts a Meteor app into a \"standard\" Node.js application.",
    "devDependencies": {
        "code": "4.0.0",
        "lab": "11.2.1",
        "proxyquire": "1.7.10",
        "sinon": "1.17.6",
        "standard": "8.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "27751a48eab483d34c06642b0e343832f5d0f993",
        "tarball": "https://registry.npmjs.org/demeteorizer/-/demeteorizer-4.3.0.tgz"
    },
    "engines": {
        "node": ">=4",
        "npm": ">=3.10.8"
    },
    "gitHead": "c10c41a9c587dfed8617383ef2d1f99d5c819c49",
    "homepage": "https://github.com/OnModulus/demeteorizer#readme",
    "keywords": [
        "meteor"
    ],
    "license": "MIT",
    "main": "./lib/demeteorizer",
    "maintainers": [
        {
            "name": "fiveisprime"
        },
        {
            "name": "harlanj"
        },
        {
            "name": "jackboberg"
        }
    ],
    "name": "demeteorizer",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/OnModulus/demeteorizer.git"
    },
    "scripts": {
        "gen-coverage": "lab --coverage --reporter lcov --output coverage/lcov.info",
        "pretest": "standard",
        "test": "lab --threshold 100"
    },
    "version": "4.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
