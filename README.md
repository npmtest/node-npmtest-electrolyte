# test coverage for  [electrolyte (v0.4.0)](https://github.com/jaredhanson/electrolyte#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-electrolyte.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-electrolyte) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-electrolyte.svg)](https://travis-ci.org/npmtest/node-npmtest-electrolyte)
#### Elegant dependency injection for Node.js.

[![NPM](https://nodei.co/npm/electrolyte.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electrolyte)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-electrolyte/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-electrolyte/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-electrolyte/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-electrolyte/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-electrolyte/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-electrolyte/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-electrolyte/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-electrolyte/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-electrolyte/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-electrolyte/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-electrolyte/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-electrolyte/build/test-report.html](https://npmtest.github.io/node-npmtest-electrolyte/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-electrolyte/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-electrolyte/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-electrolyte/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electrolyte/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electrolyte/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electrolyte/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-electrolyte/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-electrolyte/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jared Hanson",
        "url": "http://www.jaredhanson.net/"
    },
    "bugs": {
        "url": "http://github.com/jaredhanson/electrolyte/issues"
    },
    "contributors": [
        {
            "name": "Jeremie Miller",
            "url": "http://jeremie.com"
        }
    ],
    "dependencies": {
        "canonical-path": "0.0.2",
        "debug": "^2.2.0",
        "depd": "^1.0.1",
        "promise": "^7.1.1",
        "scripts": "0.1.x"
    },
    "description": "Elegant dependency injection for Node.js.",
    "devDependencies": {
        "chai": "3.x.x",
        "chai-express-handler": "git://github.com/jaredhanson/chai-express-handler.git",
        "make-node": "0.3.x",
        "mocha": "2.x.x",
        "sinon": "^1.17.4",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "332dd574d628dd53c1a1f765cc70e016b84decb1",
        "tarball": "https://registry.npmjs.org/electrolyte/-/electrolyte-0.4.0.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "548b5ea846ee4ef2406163fde57a3c46d2a776e4",
    "homepage": "https://github.com/jaredhanson/electrolyte#readme",
    "keywords": [
        "require",
        "dependency",
        "dependencies",
        "injection",
        "di",
        "ioc"
    ],
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://opensource.org/licenses/MIT"
        }
    ],
    "main": "./lib",
    "maintainers": [
        {
            "name": "jaredhanson"
        }
    ],
    "name": "electrolyte",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/jaredhanson/electrolyte.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --require test/bootstrap/node test/*.test.js test/**/*.test.js"
    },
    "version": "0.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
