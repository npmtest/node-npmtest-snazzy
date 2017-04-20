# npmtest-snazzy

#### basic test coverage for  [snazzy (v7.0.0)](https://github.com/feross/snazzy)  [![npm package](https://img.shields.io/npm/v/npmtest-snazzy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-snazzy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-snazzy.svg)](https://travis-ci.org/npmtest/node-npmtest-snazzy)

#### Format JavaScript Standard Style as Stylish (i.e. snazzy) output

[![NPM](https://nodei.co/npm/snazzy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/snazzy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-snazzy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-snazzy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-snazzy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-snazzy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-snazzy/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-snazzy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-snazzy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-snazzy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-snazzy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-snazzy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-snazzy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-snazzy/build/test-report.html](https://npmtest.github.io/node-npmtest-snazzy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-snazzy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-snazzy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-snazzy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-snazzy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-snazzy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-snazzy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-snazzy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-snazzy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "snazzy",
    "description": "Format JavaScript Standard Style as Stylish (i.e. snazzy) output",
    "version": "7.0.0",
    "author": {
        "name": "Feross Aboukhadijeh",
        "url": "http://feross.org/"
    },
    "bin": {
        "snazzy": "./bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/feross/snazzy/issues"
    },
    "dependencies": {
        "chalk": "^1.1.0",
        "inherits": "^2.0.1",
        "minimist": "^1.1.1",
        "readable-stream": "^2.0.6",
        "standard-json": "^1.0.0",
        "text-table": "^0.2.0"
    },
    "devDependencies": {
        "standard": "*"
    },
    "homepage": "https://github.com/feross/snazzy",
    "keywords": [
        "pretty",
        "pretty output",
        "snazzy standard",
        "standard",
        "standard pretty",
        "stylish",
        "stylish for standard",
        "stylish formatter",
        "stylish reporter",
        "stylish standard"
    ],
    "license": "MIT",
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/feross/snazzy.git"
    },
    "scripts": {
        "test": "standard --verbose | ./bin/cmd.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
