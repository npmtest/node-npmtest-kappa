# npmtest-kappa

#### basic test coverage for  kappa (v1.0.0-rc.14)  [![npm package](https://img.shields.io/npm/v/npmtest-kappa.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-kappa) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-kappa.svg)](https://travis-ci.org/npmtest/node-npmtest-kappa)

#### A hierarchical npm-registry proxy to make private registries easier. (Based on npm-delegate by @jden)

[![NPM](https://nodei.co/npm/kappa.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/kappa)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-kappa/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-kappa/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-kappa/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-kappa/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-kappa/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-kappa/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-kappa/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-kappa/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-kappa/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-kappa/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-kappa/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-kappa/build/test-report.html](https://npmtest.github.io/node-npmtest-kappa/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-kappa/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-kappa/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-kappa/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-kappa/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-kappa/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-kappa/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-kappa/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-kappa/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "kappa",
    "version": "1.0.0-rc.14",
    "description": "A hierarchical npm-registry proxy to make private registries easier. (Based on npm-delegate by @jden)",
    "main": "index.js",
    "bin": "kappa.js",
    "scripts": {
        "test": "tape test/*.js",
        "cover": "istanbul cover tape -- test/*.js",
        "lint": "jshint -c .jshintrc index.js lib/*.js"
    },
    "keywords": [
        "npm",
        "registry",
        "private",
        "proxy"
    ],
    "repository": "https://github.com/krakenjs/kappa.git",
    "author": "Erik Toth <ertoth@paypal.com>",
    "contributors": [
        "Trevor Livingston <trlivingston@paypal.com>"
    ],
    "licenses": [
        {
            "type": "Apache 2.0",
            "url": "http://www.apache.org/licenses/LICENSE-2.0.html"
        }
    ],
    "engines": {
        "node": ">=0.10.30"
    },
    "engineStrict": true,
    "dependencies": {
        "async": "^0.9.0",
        "content-type": "^1.0.1",
        "hapi": "^7.0.0",
        "hoek": "^2.4.1",
        "minimist": "^1.1.0",
        "shortstop": "^1.0.1",
        "shortstop-handlers": "^1.0.0",
        "wreck": "^5.0.0"
    },
    "devDependencies": {
        "istanbul": "^0.3.0",
        "jshint": "^2.5.4",
        "nock": "^0.45.0",
        "tape": "^2.14.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
