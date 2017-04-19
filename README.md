# npmtest-catw

#### basic test coverage for  [catw (v1.0.1)](https://github.com/substack/catw)  [![npm package](https://img.shields.io/npm/v/npmtest-catw.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-catw) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-catw.svg)](https://travis-ci.org/npmtest/node-npmtest-catw)

#### concatenate file globs, watching for changes

[![NPM](https://nodei.co/npm/catw.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/catw)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-catw/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-catw/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-catw/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-catw/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-catw/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-catw/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-catw/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-catw/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-catw/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-catw/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-catw/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-catw/build/test-report.html](https://npmtest.github.io/node-npmtest-catw/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-catw/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-catw/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-catw/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-catw/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-catw/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-catw/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-catw/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-catw/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "bin": {
        "catw": "bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/substack/catw/issues"
    },
    "dependencies": {
        "defined": "~0.0.0",
        "glob": "~3.2.7",
        "globwatcher": "~1.2.2",
        "minimist": "~1.1.1",
        "resolve": "~0.6.1",
        "shallow-copy": "~0.0.1",
        "shell-quote": "~1.4.0",
        "stream-combiner": "~0.0.2",
        "through": "~2.3.4"
    },
    "description": "concatenate file globs, watching for changes",
    "devDependencies": {
        "brfs": "~0.0.8",
        "concat-stream": "~1.2.0",
        "mkdirp": "~0.3.5",
        "split": "~0.2.10",
        "tape": "~2.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "847aaa94527f2e4d97303e0e9175e17924ab0ec5",
        "tarball": "https://registry.npmjs.org/catw/-/catw-1.0.1.tgz"
    },
    "gitHead": "b3e7afdcd9799ef09d40efe6acd4b11a95b16029",
    "homepage": "https://github.com/substack/catw",
    "keywords": [
        "cat",
        "watch",
        "build",
        "concatenate",
        "css",
        "glob",
        "update",
        "recompile",
        "compile"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "substack"
        },
        {
            "name": "k88hudson"
        }
    ],
    "name": "catw",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/catw.git"
    },
    "scripts": {
        "test": "tape test/*.js"
    },
    "version": "1.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
