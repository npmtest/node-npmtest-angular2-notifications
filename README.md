# npmtest-angular2-notifications

#### basic test coverage for  [angular2-notifications (v0.5.7)](https://github.com/flauc/angular2-notifications)  [![npm package](https://img.shields.io/npm/v/npmtest-angular2-notifications.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-angular2-notifications) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-angular2-notifications.svg)](https://travis-ci.org/npmtest/node-npmtest-angular2-notifications)

#### An easy to use notification library for angular 2

[![NPM](https://nodei.co/npm/angular2-notifications.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/angular2-notifications)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-angular2-notifications/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular2-notifications/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-angular2-notifications/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-angular2-notifications/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-angular2-notifications/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-angular2-notifications/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-angular2-notifications/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-angular2-notifications/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-angular2-notifications/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular2-notifications/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-angular2-notifications/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-angular2-notifications/build/test-report.html](https://npmtest.github.io/node-npmtest-angular2-notifications/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-angular2-notifications/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-angular2-notifications/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-angular2-notifications/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-angular2-notifications/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-angular2-notifications/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-angular2-notifications/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-angular2-notifications/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-angular2-notifications/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Filip Lauc"
    },
    "bugs": {
        "url": "https://github.com/flauc/angular2-notifications/issues"
    },
    "dependencies": {},
    "description": "An easy to use notification library for angular 2",
    "devDependencies": {
        "@angular/animations": "^4.0.1",
        "@angular/common": "^4.0.0",
        "@angular/compiler": "^4.0.0",
        "@angular/compiler-cli": "^4.0.0",
        "@angular/core": "^4.0.0",
        "@angular/platform-browser": "^4.0.0",
        "@angular/platform-browser-dynamic": "^4.0.0",
        "@types/jasmine": "2.5.38",
        "@types/node": "~6.0.60",
        "codelyzer": "~2.0.0",
        "core-js": "^2.4.1",
        "jasmine-core": "~2.5.2",
        "jasmine-spec-reporter": "~3.2.0",
        "karma": "~1.4.1",
        "karma-chrome-launcher": "~2.0.0",
        "karma-cli": "~1.0.1",
        "karma-coverage-istanbul-reporter": "^0.2.0",
        "karma-jasmine": "~1.1.0",
        "karma-jasmine-html-reporter": "^0.2.2",
        "protractor": "~5.1.0",
        "rxjs": "^5.1.0",
        "ts-node": "~2.0.0",
        "tslint": "~4.5.0",
        "typescript": "~2.2.0",
        "zone.js": "^0.8.4"
    },
    "directories": {},
    "dist": {
        "shasum": "a8a8e7db9b1623709c296cf11348935ae2892940",
        "tarball": "https://registry.npmjs.org/angular2-notifications/-/angular2-notifications-0.5.7.tgz"
    },
    "engines": {
        "node": ">=6.0.0"
    },
    "gitHead": "298b4e6aa04e4249b3d362e8badfe7055df2944f",
    "homepage": "https://github.com/flauc/angular2-notifications",
    "keywords": [
        "Angular",
        "2",
        "Library",
        "Notifications",
        "Notification",
        "Toast"
    ],
    "license": "MIT",
    "main": "./dist/index.js",
    "maintainers": [
        {
            "name": "flauc"
        }
    ],
    "name": "angular2-notifications",
    "optionalDependencies": {},
    "peerDependencies": {
        "@angular/core": "^4.0.1",
        "@angular/common": "^4.0.1",
        "@angular/platform-browser": "^4.0.0",
        "@angular/animations": "^4.0.1"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/flauc/angular2-notifications.git"
    },
    "scripts": {
        "build": "ngc -p tsconfig.json",
        "lint": "tslint --type-check --project tsconfig.json src/**/*.ts",
        "prepublish": "tsc",
        "test": "tsc && karma start",
        "tsc": "tsc"
    },
    "version": "0.5.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
