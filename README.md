# test coverage for  [how-to-npm (v2.4.2)](https://github.com/workshopper/how-to-npm#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-how-to-npm.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-how-to-npm) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-how-to-npm.svg)](https://travis-ci.org/npmtest/node-npmtest-how-to-npm)
#### A module to teach you how to module.

[![NPM](https://nodei.co/npm/how-to-npm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/how-to-npm)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-how-to-npm/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-how-to-npm/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-how-to-npm/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-how-to-npm/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-how-to-npm/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-how-to-npm/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-how-to-npm/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-how-to-npm/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-how-to-npm/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-how-to-npm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-how-to-npm/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-how-to-npm/build/test-report.html](https://npmtest.github.io/node-npmtest-how-to-npm/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-how-to-npm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-how-to-npm/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-how-to-npm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-how-to-npm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-how-to-npm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-how-to-npm/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-how-to-npm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-how-to-npm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Isaac Z. Schlueter",
        "url": "http://blog.izs.me/"
    },
    "bin": {
        "how-to-npm": "index.js"
    },
    "bugs": {
        "url": "https://github.com/workshopper/how-to-npm/issues"
    },
    "bundleDependencies": [
        "workshopper-adventure",
        "concat-stream",
        "mkdirp",
        "rimraf",
        "semver",
        "which"
    ],
    "dependencies": {
        "concat-stream": "^1.4.7",
        "mkdirp": "^0.5.0",
        "rimraf": "^2.2.8",
        "semver": "^4.2.0",
        "update-notifier": "^1.0.3",
        "which": "^1.0.8",
        "workshopper-adventure": "^5.0.3"
    },
    "description": "A module to teach you how to module.",
    "devDependencies": {
        "standard": "^7.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "b4b58942294079a48d260e11000d0bf629e4db0b",
        "tarball": "https://registry.npmjs.org/how-to-npm/-/how-to-npm-2.4.2.tgz"
    },
    "gitHead": "58d88f3b31ec07869dd1372fbc68833e1610ee95",
    "homepage": "https://github.com/workshopper/how-to-npm#readme",
    "keywords": [
        "workshop",
        "adventure",
        "tutorial",
        "tutor",
        "npm"
    ],
    "license": "ISC",
    "maintainers": [
        {
            "name": "isaacs"
        },
        {
            "name": "julianduque"
        },
        {
            "name": "tdd"
        },
        {
            "name": "watilde"
        }
    ],
    "name": "how-to-npm",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/workshopper/how-to-npm.git"
    },
    "scripts": {
        "test": "standard"
    },
    "version": "2.4.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
