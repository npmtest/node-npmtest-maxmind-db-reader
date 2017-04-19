# npmtest-maxmind-db-reader

#### test coverage for  [maxmind-db-reader (v0.2.1)](https://github.com/PaddeK/node-maxmind-db#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-maxmind-db-reader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-maxmind-db-reader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-maxmind-db-reader.svg)](https://travis-ci.org/npmtest/node-npmtest-maxmind-db-reader)

#### This is the pure Node API for reading MaxMind DB files. MaxMind DB is a binary file format that stores data indexed by IP address subnets (IPv4 or IPv6).

[![NPM](https://nodei.co/npm/maxmind-db-reader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/maxmind-db-reader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-maxmind-db-reader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-maxmind-db-reader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-maxmind-db-reader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-maxmind-db-reader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-maxmind-db-reader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-maxmind-db-reader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-maxmind-db-reader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-maxmind-db-reader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-maxmind-db-reader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-maxmind-db-reader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-maxmind-db-reader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-maxmind-db-reader/build/test-report.html](https://npmtest.github.io/node-npmtest-maxmind-db-reader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-maxmind-db-reader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-maxmind-db-reader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-maxmind-db-reader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-maxmind-db-reader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-maxmind-db-reader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-maxmind-db-reader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-maxmind-db-reader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-maxmind-db-reader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Patrick Klös"
    },
    "bin": {
        "mmdb-geoip": "./repl"
    },
    "bugs": {
        "url": "https://github.com/PaddeK/node-maxmind-db/issues"
    },
    "contributors": [
        {
            "name": "Patrick Klös"
        },
        {
            "name": "Corné 'EaterOfCode' Oppelaar"
        },
        {
            "name": "Rajesh Segu"
        }
    ],
    "dependencies": {
        "big-integer": ">=1.1.5",
        "ip-address": "4.0.0"
    },
    "description": "This is the pure Node API for reading MaxMind DB files. MaxMind DB is a binary file format that stores data indexed by IP address subnets (IPv4 or IPv6).",
    "devDependencies": {
        "istanbul": "^0.3.13",
        "jshint": "2.4.2",
        "path": "^0.11.14",
        "scotch-tape": "0.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2b998781eff2c72b354d3cd83646e14f4951f123",
        "tarball": "https://registry.npmjs.org/maxmind-db-reader/-/maxmind-db-reader-0.2.1.tgz"
    },
    "engine": {
        "node": ">=0.8.0"
    },
    "gitHead": "676b26680c8932b8c56504bfc6388882ec5710a2",
    "homepage": "https://github.com/PaddeK/node-maxmind-db#readme",
    "keywords": [
        "Maxmind",
        "Maxmind DB",
        "Maxmind DB Reader",
        "GeoIP2",
        "GeoIP2 Lite"
    ],
    "licenses": [
        {
            "type": "LGPL 2.1",
            "url": "https://github.com/PaddeK/node-maxmind-db/blob/master/LICENSE"
        }
    ],
    "main": "./index.js",
    "maintainers": [
        {
            "name": "paddek"
        },
        {
            "name": "eaterofcode"
        }
    ],
    "name": "maxmind-db-reader",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/PaddeK/node-maxmind-db.git"
    },
    "scripts": {
        "cover": "istanbul cover --report cobertura --print detail tape -- test/test.js",
        "cover-html": "istanbul report html",
        "fast-test": "tape test/test.js",
        "test": "npm run cover -s"
    },
    "version": "0.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
