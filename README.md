# npmtest-axon-rpc

#### basic test coverage for  axon-rpc (v0.0.3)  [![npm package](https://img.shields.io/npm/v/npmtest-axon-rpc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-axon-rpc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-axon-rpc.svg)](https://travis-ci.org/npmtest/node-npmtest-axon-rpc)

#### Remote procedure calls built on top of axon.

[![NPM](https://nodei.co/npm/axon-rpc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/axon-rpc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-axon-rpc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-axon-rpc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-axon-rpc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-axon-rpc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-axon-rpc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-axon-rpc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-axon-rpc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-axon-rpc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-axon-rpc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-axon-rpc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-axon-rpc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-axon-rpc/build/test-report.html](https://npmtest.github.io/node-npmtest-axon-rpc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-axon-rpc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-axon-rpc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-axon-rpc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-axon-rpc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-axon-rpc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-axon-rpc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-axon-rpc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-axon-rpc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "axon-rpc",
    "version": "0.0.3",
    "description": "Remote procedure calls built on top of axon.",
    "keywords": [
        "axon",
        "rpc",
        "cloud"
    ],
    "author": "TJ Holowaychuk <tj@learnboost.com>",
    "contributors": [
        {
            "name": "Bret Copeland",
            "url": "https://github.com/bretcope"
        }
    ],
    "dependencies": {
        "debug": "*",
        "commander": "1.0.5"
    },
    "devDependencies": {
        "axon": "2.0.0",
        "better-assert": "*",
        "mocha": "*"
    },
    "bin": {
        "arpc": "bin/arpc"
    },
    "main": "index",
    "scripts": {
        "test": "mocha --reporter spec"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/visionmedia/axon-rpc.git"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
