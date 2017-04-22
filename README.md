# npmtest-process

#### basic test coverage for  [process (v0.11.9)](https://github.com/shtylman/node-process#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-process.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-process) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-process.svg)](https://travis-ci.org/npmtest/node-npmtest-process)

#### process information for node.js and browsers

[![NPM](https://nodei.co/npm/process.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/process)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-process/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-process/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-process/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-process/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-process/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-process/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-process/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-process/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-process/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-process/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-process/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-process/build/test-report.html](https://npmtest.github.io/node-npmtest-process/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-process/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-process/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-process/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-process/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-process/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-process/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-process/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-process/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Roman Shtylman"
    },
    "browser": "./browser.js",
    "bugs": {
        "url": "https://github.com/shtylman/node-process/issues"
    },
    "dependencies": {},
    "description": "process information for node.js and browsers",
    "devDependencies": {
        "mocha": "2.2.1",
        "zuul": "^3.10.3"
    },
    "directories": {},
    "dist": {
        "shasum": "7bd5ad21aa6253e7da8682264f1e11d11c0318c1",
        "tarball": "https://registry.npmjs.org/process/-/process-0.11.9.tgz"
    },
    "engines": {
        "node": ">= 0.6.0"
    },
    "gitHead": "7d8c3702a8bbc43fa55f4bab74b150aef37001dd",
    "homepage": "https://github.com/shtylman/node-process#readme",
    "keywords": [
        "process"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "coolaj86"
        },
        {
            "name": "cwmma"
        },
        {
            "name": "defunctzombie"
        }
    ],
    "name": "process",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/shtylman/node-process.git"
    },
    "scripts": {
        "browser": "zuul --no-coverage --ui mocha-bdd --local 8080 -- test.js",
        "test": "mocha test.js"
    },
    "version": "0.11.9",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
