# npmtest-run-browser

#### test coverage for  [run-browser (v2.0.2)](https://github.com/ForbesLindesay/run-browser)  [![npm package](https://img.shields.io/npm/v/npmtest-run-browser.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-run-browser) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-run-browser.svg)](https://travis-ci.org/npmtest/node-npmtest-run-browser)

#### The simplest way to run testling type tests in the browser

[![NPM](https://nodei.co/npm/run-browser.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/run-browser)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-run-browser/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-run-browser/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-run-browser/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-run-browser/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-run-browser/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-run-browser/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-run-browser/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-run-browser/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-run-browser/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-run-browser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-run-browser/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-run-browser/build/test-report.html](https://npmtest.github.io/node-npmtest-run-browser/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-run-browser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-run-browser/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-run-browser/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-run-browser/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-run-browser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-run-browser/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-run-browser/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-run-browser/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "ForbesLindesay"
    },
    "bin": {
        "run-browser": "./bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/ForbesLindesay/run-browser/issues"
    },
    "dependencies": {
        "browserify": "^3.28.0",
        "browserify-istanbul": "^0.1.2",
        "function-bind": "^1.0.2",
        "glob": "~3.2.7",
        "global": "^4.3.0",
        "istanbul": "^0.3.2",
        "jsonstream2": "^1.1.0",
        "minimist": "0.0.8",
        "phantomjs": "~1.9.7-1",
        "process": "^0.9.0",
        "tap-finished": "0.0.1",
        "through2-spy": "^1.2.0",
        "xhr": "^1.17.0"
    },
    "description": "The simplest way to run testling type tests in the browser",
    "devDependencies": {
        "linify": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "acf5496ada194da28a2c41657699e6914a1bca1d",
        "tarball": "https://registry.npmjs.org/run-browser/-/run-browser-2.0.2.tgz"
    },
    "gitHead": "52873b4e7e627c5dcce093adb7a20e40adaea70e",
    "homepage": "https://github.com/ForbesLindesay/run-browser",
    "keywords": [],
    "license": "MIT",
    "maintainers": [
        {
            "name": "forbeslindesay"
        },
        {
            "name": "raynos"
        }
    ],
    "name": "run-browser",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ForbesLindesay/run-browser.git"
    },
    "scripts": {
        "prepublish": "linify transform ./bin"
    },
    "version": "2.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
