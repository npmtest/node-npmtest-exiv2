# npmtest-exiv2

#### basic test coverage for  [exiv2 (v0.6.3)](https://github.com/dberesford/exiv2node)  [![npm package](https://img.shields.io/npm/v/npmtest-exiv2.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-exiv2) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-exiv2.svg)](https://travis-ci.org/npmtest/node-npmtest-exiv2)

#### A native c++ extension for node.js that provides support for reading & writing image metadata via Exiv2.

[![NPM](https://nodei.co/npm/exiv2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/exiv2)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-exiv2/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-exiv2/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-exiv2/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-exiv2/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-exiv2/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-exiv2/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-exiv2/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-exiv2/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-exiv2/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-exiv2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-exiv2/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-exiv2/build/test-report.html](https://npmtest.github.io/node-npmtest-exiv2/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-exiv2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-exiv2/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-exiv2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-exiv2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-exiv2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-exiv2/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-exiv2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-exiv2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Damian Beresford",
        "url": "http://www.damianberesford.com/"
    },
    "name": "exiv2",
    "description": "A native c++ extension for node.js that provides support for reading & writing image metadata via Exiv2.",
    "version": "0.6.3",
    "homepage": "https://github.com/dberesford/exiv2node",
    "repository": {
        "type": "git",
        "url": "git://github.com/dberesford/exiv2node.git"
    },
    "dependencies": {
        "nan": "~2.2"
    },
    "devDependencies": {
        "should": "*",
        "mocha": "*"
    },
    "optionalDependencies": {},
    "engines": {
        "node": "~0.8.0"
    },
    "main": "exiv2",
    "scripts": {
        "preuninstall": "rm -rf build/*",
        "test": "mocha",
        "install": "node-gyp rebuild"
    },
    "gypfile": true,
    "contributors": [
        {
            "name": "Damian Beresford"
        },
        {
            "name": "Ryan French"
        },
        {
            "name": "Andrew Morton"
        }
    ],
    "readmeFilename": "README.md",
    "bugs": {
        "url": "https://github.com/dberesford/exiv2node/issues"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
