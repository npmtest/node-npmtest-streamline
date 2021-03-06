# npmtest-streamline

#### basic test coverage for  [streamline (v2.0.19)](http://github.com/Sage/streamlinejs)  [![npm package](https://img.shields.io/npm/v/npmtest-streamline.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-streamline) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-streamline.svg)](https://travis-ci.org/npmtest/node-npmtest-streamline)

#### Asynchronous Javascript for dummies

[![NPM](https://nodei.co/npm/streamline.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/streamline)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-streamline/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-streamline/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-streamline/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-streamline/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-streamline/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-streamline/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-streamline/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-streamline/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-streamline/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-streamline/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-streamline/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-streamline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-streamline/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-streamline/build/test-report.html](https://npmtest.github.io/node-npmtest-streamline/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-streamline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-streamline/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-streamline/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-streamline/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-streamline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-streamline/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-streamline/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-streamline/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Bruno Jouhier"
    },
    "bin": {
        "_node": "./bin/_node",
        "_coffee": "./bin/_coffee"
    },
    "bugs": {
        "url": "https://github.com/Sage/streamlinejs/issues"
    },
    "contributors": [
        {
            "name": "Bruno Jouhier"
        },
        {
            "name": "Preston Guillory"
        },
        {
            "name": "Will Conant"
        },
        {
            "name": "Aseem Kishore"
        },
        {
            "name": "Daniel Ennis"
        },
        {
            "name": "Marcel Laverdet",
            "url": "https://github.com/laverdet/"
        },
        {
            "name": "Evan Worley"
        },
        {
            "name": "anodos",
            "url": "https://github.com/anodos"
        },
        {
            "name": "Alan Gutierrez"
        },
        {
            "name": "Geoffry Song"
        }
    ],
    "dependencies": {
        "babel-core": "^6.3.26",
        "babel-plugin-streamline": "^2.0.19",
        "babel-preset-es2015": "^6.3.13",
        "colors": "^1.1.2",
        "commander": "^2.8.1",
        "fibers": "^1.0.6",
        "source-map-support": "git+https://github.com/Sage/node-source-map-support.git#catch-missing-sourcemap-element",
        "streamline-runtime": "^1.0.17",
        "typescript": "^2.0.0"
    },
    "description": "Asynchronous Javascript for dummies",
    "devDependencies": {
        "babelify": "^7.2.0",
        "browserify": "^12.0.1",
        "qunit": "git+https://github.com/Sage/node-qunit.git#sage",
        "uglifyify": "^3.0.4"
    },
    "directories": {},
    "dist": {
        "shasum": "04af53dce2fd28b105b9a71e5b3c8867379d8f75",
        "tarball": "https://registry.npmjs.org/streamline/-/streamline-2.0.19.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "cc795af21cc37990b91f6553d33ef33e5231014f",
    "homepage": "http://github.com/Sage/streamlinejs",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bjouhier"
        }
    ],
    "name": "streamline",
    "optionalDependencies": {
        "fibers": "^1.0.6"
    },
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/Sage/streamlinejs.git"
    },
    "scripts": {
        "prepublish": "node build.js || nodejs build.js",
        "test": "node test"
    },
    "version": "2.0.19"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
