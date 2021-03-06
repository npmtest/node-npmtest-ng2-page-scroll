# npmtest-ng2-page-scroll

#### basic test coverage for  [ng2-page-scroll (v4.0.0-beta.7)](https://github.com/Nolanus/ng2-page-scroll#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ng2-page-scroll.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ng2-page-scroll) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ng2-page-scroll.svg)](https://travis-ci.org/npmtest/node-npmtest-ng2-page-scroll)

#### Animated scrolling functionality written in pure angular2

[![NPM](https://nodei.co/npm/ng2-page-scroll.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ng2-page-scroll)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ng2-page-scroll/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ng2-page-scroll/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ng2-page-scroll/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ng2-page-scroll/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ng2-page-scroll/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ng2-page-scroll/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ng2-page-scroll/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ng2-page-scroll/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ng2-page-scroll/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ng2-page-scroll/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ng2-page-scroll/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ng2-page-scroll/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ng2-page-scroll/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ng2-page-scroll/build/test-report.html](https://npmtest.github.io/node-npmtest-ng2-page-scroll/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ng2-page-scroll/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ng2-page-scroll/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ng2-page-scroll/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ng2-page-scroll/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ng2-page-scroll/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ng2-page-scroll/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ng2-page-scroll/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ng2-page-scroll/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sebastian Fuss"
    },
    "bugs": {
        "url": "https://github.com/Nolanus/ng2-page-scroll/issues"
    },
    "dependencies": {},
    "description": "Animated scrolling functionality written in pure angular2",
    "devDependencies": {
        "@angular/common": "^4.0.2",
        "@angular/compiler": "^4.0.2",
        "@angular/compiler-cli": "^4.0.2",
        "@angular/core": "^4.0.2",
        "@angular/platform-browser": "^4.0.2",
        "@angular/platform-server": "^4.0.2",
        "@angular/router": "^4.0.2",
        "@types/jasmine": "^2.5.45",
        "codelyzer": "~3.0.0",
        "jasmine-core": "~2.5.2",
        "jasmine-spec-reporter": "~4.0.0",
        "protractor": "5.1.1",
        "rimraf": "^2.5.4",
        "rollup": "^0.41.4",
        "rollup-plugin-uglify": "^1.0.1",
        "rxjs": "^5.1.0",
        "tslint": "^5.1.0",
        "typescript": "~2.2.1",
        "typings": "^2.1.0",
        "zone.js": "0.8.7"
    },
    "directories": {},
    "dist": {
        "shasum": "d49a14c652e5ada2f6546e06b38a288326922472",
        "tarball": "https://registry.npmjs.org/ng2-page-scroll/-/ng2-page-scroll-4.0.0-beta.7.tgz"
    },
    "gitHead": "643faf3bf984b7dd0a1689a40631ae551dcaddb7",
    "homepage": "https://github.com/Nolanus/ng2-page-scroll#readme",
    "keywords": [
        "angular2",
        "angularjs",
        "page",
        "scroll",
        "pagescroll",
        "animate",
        "move",
        "scrollto",
        "anchor"
    ],
    "license": "MIT",
    "main": "bundles/ng2-page-scroll.umd.js",
    "maintainers": [
        {
            "name": "nolanus"
        }
    ],
    "module": "ng2-page-scroll.js",
    "name": "ng2-page-scroll",
    "optionalDependencies": {},
    "peerDependencies": {
        "@angular/core": ">=2.4.0 <5.0.0",
        "@angular/common": ">=2.4.0 <5.0.0",
        "@angular/platform-browser": ">=2.4.0 <5.0.0",
        "@angular/router": ">=3.2.0 <5.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/Nolanus/ng2-page-scroll.git"
    },
    "scripts": {
        "bundle:clean": "rimraf bundles",
        "bundle:create": "npm run bundle:clean && npm run rollup && npm run rollup:min",
        "compile": "npm run lint:code && ngc -p tsconfig-build.json",
        "compile:tsc": "npm run lint && tsc -p tsconfig.json --noUnusedLocals",
        "demo": "npm install && npm run demo:clean && npm run demo:start",
        "demo:clean": "cd demo/ && npm uninstall ng2-page-scroll && npm install",
        "demo:start": "cd demo/ && npm start",
        "install:typings": "typings install",
        "lint": "npm run lint:code && npm run lint:test",
        "lint:code": "tslint ./src/**/*.ts -t verbose --exclude ./src/**/*.d.ts",
        "lint:test": "tslint ./test/**/*.ts -t verbose --exclude ./test/**/*.d.ts",
        "precompile": "npm run install:typings",
        "prepublish": "npm run compile && npm run bundle:create",
        "pretest": "npm run compile:tsc",
        "rollup": "rollup -c rollup.conf.js",
        "rollup:min": "rollup -c rollup-uglify.conf.js",
        "test": "protractor protractor.conf.js",
        "webdriver:init": "webdriver-manager update"
    },
    "typings": "ng2-page-scroll.d.ts",
    "version": "4.0.0-beta.7",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
