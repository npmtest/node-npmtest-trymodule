# npmtest-trymodule

#### test coverage for  trymodule (v1.4.0)  [![npm package](https://img.shields.io/npm/v/npmtest-trymodule.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-trymodule) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-trymodule.svg)](https://travis-ci.org/npmtest/node-npmtest-trymodule)

#### It's never been easier to try nodejs modules!

[![NPM](https://nodei.co/npm/trymodule.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/trymodule)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-trymodule/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-trymodule/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-trymodule/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-trymodule/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-trymodule/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-trymodule/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-trymodule/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-trymodule/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-trymodule/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-trymodule/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-trymodule/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-trymodule/build/test-report.html](https://npmtest.github.io/node-npmtest-trymodule/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-trymodule/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-trymodule/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-trymodule/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-trymodule/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-trymodule/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-trymodule/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-trymodule/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-trymodule/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "trymodule",
    "version": "1.4.0",
    "description": "It's never been easier to try nodejs modules!",
    "main": "index.js",
    "scripts": {
        "test": "npm run lint;./functional_test.sh",
        "lint": "standard"
    },
    "bin": {
        "trymodule": "./cli.js"
    },
    "author": {
        "name": "Victor Bjelkholm",
        "url": "https://www.github.com/victorbjelkholm"
    },
    "license": "MIT",
    "dependencies": {
        "colors": "^1.1.2",
        "npmi": "^1.0.1",
        "repl.history": "^0.1.3"
    },
    "devDependencies": {
        "standard": "^6.0.8"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "fd57ea8eaf009856f5b0c1bfde8c3f9b7f92a426",
    "dist": {
        "shasum": "a1c168ef819256c3c24c88d6c81620f9fe72f403",
        "tarball": "https://registry.npmjs.org/trymodule/-/trymodule-1.4.0.tgz"
    },
    "maintainers": [
        {
            "name": "victorbjelkholm"
        }
    ],
    "directories": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
