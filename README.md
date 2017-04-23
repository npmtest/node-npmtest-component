# npmtest-component

#### basic test coverage for  component (v1.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-component.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-component) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-component.svg)](https://travis-ci.org/npmtest/node-npmtest-component)

#### Component package manager consuming git repositories

[![NPM](https://nodei.co/npm/component.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/component)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-component/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-component/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-component/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-component/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-component/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-component/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-component/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-component/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-component/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-component/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-component/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-component/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-component/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-component/build/test-report.html](https://npmtest.github.io/node-npmtest-component/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-component/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-component/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-component/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-component/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-component/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-component/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-component/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-component/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "component",
    "version": "1.1.0",
    "description": "Component package manager consuming git repositories",
    "keywords": [
        "component",
        "package",
        "client",
        "browser",
        "module"
    ],
    "author": "TJ Holowaychuk <tj@vision-media.ca>",
    "repository": "componentjs/component",
    "dependencies": {
        "component-build": "^1.2.2",
        "component-consoler": "^2.0.0",
        "component-flatten": "^1.0.1",
        "component-ls": "^2.1.0",
        "component-outdated2": "^1.0.4",
        "component-pin": "^1.0.4",
        "component-resolver": "^1.3.0",
        "component-search2": "^1.1.1",
        "component-updater": "^1.0.4",
        "component-watcher": "^1.0.1",
        "component-remotes": "^1.2.0",
        "commander": "^2.2.0",
        "semver": "^2.2.1",
        "mkdirp": "~0.3.5",
        "rimraf": "^2.2.6",
        "superagent": "~0.17.0",
        "win-fork": "~1.1.1",
        "debug": "*",
        "co": "^3.0.0",
        "tiny-lr-fork": "0.0.5"
    },
    "devDependencies": {
        "mocha": "1",
        "should": "3"
    },
    "bin": {
        "component": "bin/component",
        "component-build": "bin/component-build",
        "component-crawl": "bin/component-crawl",
        "component-duplicates": "bin/component-duplicates",
        "component-help": "bin/component-help",
        "component-install": "bin/component-install",
        "component-link": "bin/component-link",
        "component-ls": "bin/component-ls",
        "component-outdated": "bin/component-outdated",
        "component-pin": "bin/component-pin",
        "component-search": "bin/component-search",
        "component-update": "bin/component-update",
        "component-validate": "bin/component-validate"
    },
    "main": "lib/component",
    "engines": {
        "node": ">= 0.10.0"
    },
    "scripts": {
        "test": "make test"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
