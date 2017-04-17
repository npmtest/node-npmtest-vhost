# test coverage for  [vhost (v3.0.2)](https://github.com/expressjs/vhost)  [![npm package](https://img.shields.io/npm/v/npmtest-vhost.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vhost) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vhost.svg)](https://travis-ci.org/npmtest/node-npmtest-vhost)
#### virtual domain hosting

[![NPM](https://nodei.co/npm/vhost.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vhost)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vhost/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vhost/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vhost/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vhost/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vhost/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vhost/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vhost/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vhost/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vhost/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vhost/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vhost/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vhost/build/test-report.html](https://npmtest.github.io/node-npmtest-vhost/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vhost/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vhost/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vhost/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vhost/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vhost/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vhost/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vhost/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vhost/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/expressjs/vhost/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Jonathan Ong",
            "url": "http://jongleberry.com"
        }
    ],
    "dependencies": {},
    "description": "virtual domain hosting",
    "devDependencies": {
        "istanbul": "0.3.22",
        "mocha": "2.3.3",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2fb1decd4c466aa88b0f9341af33dc1aff2478d5",
        "tarball": "https://registry.npmjs.org/vhost/-/vhost-3.0.2.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "index.js"
    ],
    "gitHead": "2dff3f358265380328067d1ffc91e342b665f586",
    "homepage": "https://github.com/expressjs/vhost",
    "license": "MIT",
    "maintainers": [
        {
            "name": "tootallnate"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "dougwilson"
        },
        {
            "name": "tjholowaychuk"
        },
        {
            "name": "mscdex"
        },
        {
            "name": "fishrock123"
        },
        {
            "name": "defunctzombie"
        },
        {
            "name": "TooTallNate"
        }
    ],
    "name": "vhost",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/vhost.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "3.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
