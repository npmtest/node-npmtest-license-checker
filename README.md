# npmtest-license-checker

#### basic test coverage for  [license-checker (v9.0.3)](https://github.com/davglass/license-checker#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-license-checker.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-license-checker) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-license-checker.svg)](https://travis-ci.org/npmtest/node-npmtest-license-checker)

#### Check license info for a pacakge

[![NPM](https://nodei.co/npm/license-checker.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/license-checker)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-license-checker/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-license-checker/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-license-checker/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-license-checker/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-license-checker/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-license-checker/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-license-checker/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-license-checker/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-license-checker/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-license-checker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-license-checker/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-license-checker/build/test-report.html](https://npmtest.github.io/node-npmtest-license-checker/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-license-checker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-license-checker/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-license-checker/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-license-checker/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-license-checker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-license-checker/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-license-checker/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-license-checker/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dav Glass"
    },
    "bin": {
        "license-checker": "./bin/license-checker"
    },
    "bugs": {
        "url": "http://github.com/davglass/license-checker/issues"
    },
    "contributors": [
        {
            "name": "Adam Weber"
        },
        {
            "name": "Andrew Couch"
        },
        {
            "name": "Asharma"
        },
        {
            "name": "Bryan English"
        },
        {
            "name": "Cory Reed"
        },
        {
            "name": "Damien Larmine"
        },
        {
            "name": "Dav Glass"
        },
        {
            "name": "Dick Wiggers"
        },
        {
            "name": "Drew Folta"
        },
        {
            "name": "Elijah Insua"
        },
        {
            "name": "Glen Arrowsmith"
        },
        {
            "name": "Holger Knust"
        },
        {
            "name": "James Bloomer"
        },
        {
            "name": "Ladislav Prskavec"
        },
        {
            "name": "Ladislav Prskavec"
        },
        {
            "name": "Mattias Amnefelt"
        },
        {
            "name": "Michael Williamson"
        },
        {
            "name": "Paul Mandel"
        },
        {
            "name": "Philipp Tusch"
        },
        {
            "name": "Stan Senotrusov"
        },
        {
            "name": "Stoyan Revov"
        },
        {
            "name": "Tero Keski-Valkama"
        },
        {
            "name": "Thomas Grainger"
        },
        {
            "name": "Tim Brust"
        },
        {
            "name": "Tim Oxley"
        },
        {
            "name": "Timothée Mazzucotelli"
        },
        {
            "name": "Yuri Zapuchlak"
        },
        {
            "name": "badunk"
        },
        {
            "name": "gdw2"
        }
    ],
    "dependencies": {
        "chalk": "~0.5.1",
        "debug": "^2.2.0",
        "mkdirp": "^0.3.5",
        "nopt": "^2.2.0",
        "read-installed": "~4.0.3",
        "semver": "^5.3.0",
        "treeify": "^1.0.1"
    },
    "description": "Check license info for a pacakge",
    "devDependencies": {
        "camden.jshint": "github:cfjedimaster/brackets-jshint",
        "detectionizr": "*",
        "format-package-json": "^0.2.0",
        "git-contributors": "^0.2.3",
        "github-changes": "^1.0.4",
        "istanbul": "^0.4.3",
        "jenkins-mocha": "^2.6.0",
        "jshint": "^2.9.4",
        "queue": "^1.0.0",
        "request": "^2.34.0",
        "rimraf": "^2.5.4",
        "yui-lint": "~0.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "bc9136911fef129d255a2255583765ff569fa316",
        "tarball": "https://registry.npmjs.org/license-checker/-/license-checker-9.0.3.tgz"
    },
    "gitHead": "f82b535d3b7f152fa00bb4680e94af18d1c1421d",
    "homepage": "https://github.com/davglass/license-checker#readme",
    "keywords": [
        "license",
        "cli",
        "checker",
        "oss"
    ],
    "license": "BSD-3-Clause",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "davglass"
        }
    ],
    "name": "license-checker",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/davglass/license-checker.git"
    },
    "scripts": {
        "changes": "github-changes -o davglass -r license-checker",
        "contrib": "./scripts/contrib.js",
        "posttest": "istanbul check-coverage",
        "pretest": "jshint --config ./node_modules/yui-lint/jshint.json ./lib/",
        "test": "jenkins-mocha ./tests/*.js"
    },
    "version": "9.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
