# npmtest-node-readability

#### basic test coverage for  [node-readability (v2.2.0)](https://github.com/luin/node-readability)  [![npm package](https://img.shields.io/npm/v/npmtest-node-readability.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-readability) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-readability.svg)](https://travis-ci.org/npmtest/node-npmtest-node-readability)

#### Turning any web page into a clean view.

[![NPM](https://nodei.co/npm/node-readability.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-readability)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-readability/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-readability/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-readability/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-readability/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-readability/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-readability/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-readability/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-readability/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-readability/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-readability/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-readability/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-readability/build/test-report.html](https://npmtest.github.io/node-npmtest-node-readability/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-readability/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-readability/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-readability/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-readability/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-readability/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-readability/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-readability/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-readability/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Zihua Li"
    },
    "bin": {
        "readability": "./src/cli.js"
    },
    "bugs": {
        "url": "https://github.com/luin/node-readability/issues"
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "dependencies": {
        "encoding": "~0.1.7",
        "jsdom": "^6.3.0",
        "minimist": "^1.2.0",
        "request": "~2.40.0"
    },
    "description": "Turning any web page into a clean view.",
    "devDependencies": {
        "cz-conventional-changelog": "^1.1.5",
        "mocha": "~1.8.2",
        "nock": "~0.27.1",
        "should": "~2.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "341606508ad80b14aac498feba9e8194d86778e7",
        "tarball": "https://registry.npmjs.org/node-readability/-/node-readability-2.2.0.tgz"
    },
    "engines": {
        "node": ">= 2"
    },
    "gitHead": "206b37021ceed0f029174bd3dd716e1677224ffa",
    "homepage": "https://github.com/luin/node-readability",
    "keywords": [
        "readability"
    ],
    "licenses": [
        {
            "type": "Apache License 2.0",
            "url": "http://www.apache.org/licenses/LICENSE-2.0"
        }
    ],
    "main": "./src/readability",
    "maintainers": [
        {
            "name": "luin"
        }
    ],
    "name": "node-readability",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/luin/node-readability.git"
    },
    "scripts": {
        "test": "mocha -R spec"
    },
    "version": "2.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
